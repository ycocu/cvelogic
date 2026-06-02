# Daily threat intelligence JSON

## Standards

| Layer | Schema | Source |
|-------|--------|--------|
| **NVD CVE** | [nvd-cve-api-2.0.schema.json](./nvd-cve-api-2.0.schema.json) | [NVD CVE API 2.0](https://nvd.nist.gov/developers/vulnerabilities) — `vulnerabilities[].cve` |
| **Digest file** | [threat-intel.schema.json](./threat-intel.schema.json) | NVD `cve` + cvelogic extensions |

Ingest mapping: `vul_ingest/parsers/nvd.py` → `vuln.db` → export rebuilds official field names.

## Root document

| Field | Description |
|-------|-------------|
| `schema_version` | `2.2` — top-level `cve` (NVD API 2.0 object) |
| `cves[]` | See below |
| `source` | `https://www.cvelogic.com/threat-intelligence/{day}` |

## CVE entry (`cves[]`)

### `cve` — official NVD API 2.0

Same shape as `GET /rest/json/cves/2.0` → `vulnerabilities[].cve` (no extra `nvd` wrapper):

| Field | NVD |
|-------|-----|
| `id` | CVE-ID |
| `sourceIdentifier` | CNA / NVD source |
| `published` / `lastModified` | ISO-8601 |
| `vulnStatus` | e.g. Analyzed, Modified |
| `evaluatorComment` / `evaluatorSolution` / `evaluatorImpact` | optional |
| `cisaExploitAdd` / `cisaActionDue` / `cisaRequiredAction` / `cisaVulnerabilityName` | CISA fields on CVE record |
| `cveTags` | `[{ sourceIdentifier, tags[] }]` |
| `descriptions` | `[{ lang, value }]` **required** |
| `metrics` | `{ cvssMetricV40, cvssMetricV31, cvssMetricV30, cvssMetricV2 }` |
| `weaknesses` | `[{ source, type, description: [{lang,value}] }]` |
| `configurations` | `[{ nodes: [{ operator, negate, cpeMatch, children }] }]` |
| `references` | `[{ url, source, tags? }]` **required** |
| `vendorComments` | `[{ organization, comment, lastModified }]` |

### `signals` — cvelogic daily digest (extension)

| Field | Meaning |
|-------|---------|
| `kev` | `{ date_added }` — KEV added this window |
| `exploit` | `{ ref_published }` — new exploit ref |
| `epss` | `{ previous, current, delta }` — each with `score`, `score_date` |
| `cvss` | `{ signal_date, previous_max, current_max }` — new critical in window |
| `patch` | `{ signal_date }` |

### `digest` — cvelogic display (extension)

Short card fields: `title`, `vendor`, `product`, `description`, `attack_type`, `cvss_max`, `published`.
