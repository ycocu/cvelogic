# cvelogic — Open Vulnerability Intelligence

Daily CVE threat intelligence, published as JSON and Markdown.

Maintained by the [cvelogic team](https://www.cvelogic.com). Same data as the daily feed at [cvelogic.com](https://www.cvelogic.com) `/threat-intelligence/<day>`.

---

## Why this exists

Most CVEs never make it to the top of anyone's queue. A few do — because someone started exploiting them, because a PoC showed up, because the risk score jumped overnight.

We publish that shortlist every day: what moved, what to look at first. One JSON file for your tools, one Markdown summary if you just want to read it.

Same feed that runs on [cvelogic.com](https://www.cvelogic.com/threat-intelligence). Open, dated, and free to plug into whatever you already use.

---

## Repository layout

Schemas, daily JSON digests, and Markdown summaries.

```
cvelogic/
├── README.md
├── schemas/
│   ├── threat-intel.schema.json
│   ├── nvd-cve-api-2.0.schema.json
│   └── threat-intel.md
└── threat-intelligence/
    └── {year}/{month}/
        ├── threat-intel-{day}.json
        └── threat-intel-{day}-summary.md
```

---

## Data structure

### Files

| File | Path | Notes |
|------|------|-------|
| JSON | `threat-intelligence/{year}/{month}/threat-intel-{day}.json` | Source of truth |
| Summary | `threat-intelligence/{year}/{month}/threat-intel-{day}-summary.md` | Rendered from JSON |

`{day}` is UTC (`YYYY-MM-DD`). Canonical URL:

```
https://www.cvelogic.com/threat-intelligence/{day}
```

### JSON

Root fields (`threat-intel.schema.json`, version `2.2`):

| Field | Description |
|-------|-------------|
| `schema_version` | `2.2` |
| `generated_at` | ISO-8601 UTC |
| `day` | Digest end date |
| `window` | `{ utc_start, utc_end, days }` |
| `source` | Canonical URL |
| `summary` | `{ brief, bullets, counts }` |
| `cves[]` | Sorted by `rank` |

Each item in `cves[]`:

```
cves[]
├── cve_id, rank, risk_score, signal_types[]
├── signals          # what fired in the window
│   ├── kev      → { date_added }
│   ├── exploit  → { ref_published }
│   ├── epss     → { previous, current, delta }
│   ├── cvss     → { signal_date, previous_max, current_max }
│   └── patch    → { signal_date }
├── digest           # short card fields (title, vendor, product, …)
└── cve              # NVD API 2.0 object (vulnerabilities[].cve shape)
```

The `cve` object matches NVD `GET /rest/json/cves/2.0` field-for-field. Extensions are only in `signals` and `digest`.

Field reference: [`schemas/threat-intel.md`](schemas/threat-intel.md).

### Example

```json
{
  "schema_version": "2.2",
  "day": "2026-05-31",
  "source": "https://www.cvelogic.com/threat-intelligence/2026-05-31",
  "summary": {
    "brief": "Totolink N600r Firmware — exploitation likelihood rose sharply (EPSS 21% → 43%).",
    "counts": { "cves": 6, "kev": 0, "exploit": 0, "epss": 6, "cvss": 0, "patch": 0 }
  },
  "cves": [
    {
      "cve_id": "CVE-2022-26187",
      "rank": 1,
      "signal_types": ["EPSS"],
      "signals": {
        "epss": {
          "previous": { "score": 0.21167, "score_date": "2026-05-30" },
          "current":  { "score": 0.42776, "score_date": "2026-05-31" },
          "delta": 0.21609
        }
      },
      "digest": {
        "title": "totolink n600r_firmware Command Injection",
        "cvss_max": 9.8
      },
      "cve": { "id": "CVE-2022-26187", "descriptions": […], "metrics": {…} }
    }
  ]
}
```

---

## Usage

```bash
cat threat-intelligence/2026/05/threat-intel-2026-05-31.json
less threat-intelligence/2026/05/threat-intel-2026-05-31-summary.md
```

---

## Maintainer

| | |
|---|---|
| Team | [cvelogic team](https://www.cvelogic.com) |
| Site | [https://www.cvelogic.com](https://www.cvelogic.com) |
| Feed | `https://www.cvelogic.com/threat-intelligence/{day}` |
| Schema | `2.2` — `schemas/threat-intel.schema.json` |
| Docs | [`schemas/threat-intel.md`](schemas/threat-intel.md) |

Updated daily (UTC).

---

## License

MIT
