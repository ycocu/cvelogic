# Daily Threat Intelligence — November 28, 2025

**Digest window (UTC):** 2025-11-28
**Generated:** 2026-06-02T07:33:52Z

## Threat brief

OpenPLC ScadaBR added to CISA KEV — confirmed in-the-wild exploitation.

## Executive summary

- OpenPLC ScadaBR added to CISA KEV — confirmed in-the-wild exploitation.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **3** |


## CVEs

### CVE-2021-26829
**OpenPLC ScadaBR Cross-site Scripting Vulnerability**
- **Signals:** KEV
- **Asset:** scadabr scadabr
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-01T15:23:18.697
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 88
- **KEV:** added 2025-11-28

> OpenPLC ScadaBR through 0.9.1 on Linux and through 1.12.4 on Windows allows stored XSS via system_settings.shtm.

### CVE-2025-66385
**UsersController::edit in Cerebrate before 1.30 allows an authenticated non-privileged user to escalate their privileges (e.g., obtain a h...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-472
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-11-28)

> UsersController::edit in Cerebrate before 1.30 allows an authenticated non-privileged user to escalate their privileges (e.g., obtain a higher role such as admin) via the user-edit endpoint by supplying or modifying role_id or organisation_id fields in the edit request.

### CVE-2025-64314
**huawei harmonyos**
- **Signals:** CVSS
- **Asset:** huawei harmonyos
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-02T02:32:29.050
- **CWE:** CWE-843
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-28)

> Permission control vulnerability in the memory management module.
Impact: Successful exploitation of this vulnerability may affect confidentiality.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-28*
