# Daily Threat Intelligence — September 27, 2025

**Digest window (UTC):** 2025-09-27
**Generated:** 2026-06-02T07:33:29Z

## Threat brief

Vote Pro — exploitation likelihood rose sharply (EPSS 6.0% → 18% · rising (+12%)).

## Executive summary

- Vote Pro — exploitation likelihood rose sharply (EPSS 6.0% → 18% · rising (+12%)).

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

### CVE-2007-0504
**vote_pro vote_pro**
- **Signals:** EPSS
- **Asset:** vote_pro vote_pro
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 85
- **EPSS 6.0% (2025-09-14) → 17.5% (2025-09-27), Δ +11.5%**

> Eval injection vulnerability in poll_frame.php in Vote! Pro 4.0, and possibly other scripts, allows remote attackers to execute arbitrary code via the poll_id parameter, which is supplied to an eval function call, a different vulnerability type than CVE-2005-4632.

### CVE-2025-59936
**get-jwks contains fetch utils for JWKS keys.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-116
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-09-27)

> get-jwks contains fetch utils for JWKS keys. In versions prior to 11.0.2, a vulnerability in get-jwks can lead to cache poisoning in the JWKS key-fetching mechanism. When the iss (issuer) claim is validated only after keys are retrieved from the cache, it is possible for cached k…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-27*
