# Daily Threat Intelligence — September 20, 2025

**Digest window (UTC):** 2025-09-20
**Generated:** 2026-06-02T07:33:27Z

## Threat brief

Open Newsletter — exploitation likelihood rose sharply (EPSS 9.4% → 26% · rising (+17%)).

## Executive summary

- Open Newsletter — exploitation likelihood rose sharply (EPSS 9.4% → 26% · rising (+17%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 1 |
| Patch status change | 0 |
| **Total** | **2** |


## CVEs

### CVE-2006-6785
**open_newsletter open_newsletter**
- **Signals:** EPSS
- **Asset:** open_newsletter open_newsletter
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 82
- **EPSS 9.4% (2025-08-16) → 26.4% (2025-09-20), Δ +17.0%**

> The (1) settings.php and (2) subscribers.php scripts in Open Newsletter 2.5 and earlier do not exit when authentication fails, which allows remote attackers to perform unauthorized administrative actions, or execute arbitrary code in conjunction with another vulnerability.

### CVE-2025-40925
**Starch versions 0.14 and earlier generate session ids insecurely.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-338
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-20)

> Starch versions 0.14 and earlier generate session ids insecurely.

The default session id generator returns a SHA-1 hash seeded with a counter, the epoch time, the built-in rand function, the PID, and internal Perl reference addresses. The PID will come from a small set of number…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-20*
