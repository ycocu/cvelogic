# Daily Threat Intelligence — September 06, 2025

**Digest window (UTC):** 2025-09-06
**Generated:** 2026-06-02T07:33:22Z

## Threat brief

3 new critical disclosures — review patch status on exposed services.

## Executive summary

- 3 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 3 |
| Patch status change | 0 |
| **Total** | **3** |


## CVEs

### CVE-2025-58443
**fogproject fogproject Auth Bypass**
- **Signals:** CVSS
- **Asset:** fogproject fogproject
- **Attack:** Auth Bypass
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-29T13:49:57.557
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-09-06)

> FOG is a free open-source cloning/imaging/rescue suite/inventory management system. Versions 1.5.10.1673 and below contain an authentication bypass vulnerability. It is possible for an attacker to perform an unauthenticated DB dump where they could pull a full SQL DB without cred…

### CVE-2025-8359
**The AdForest theme for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 6.0.9.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-06)

> The AdForest theme for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 6.0.9. This is due to the plugin not properly verifying a user's identity prior to authenticating them. This makes it possible for unauthenticated attackers to log in as …

### CVE-2025-58438
**internetarchive is a Python and Command-Line Interface to Archive.org In versions 5.5.0 and below, there is a directory traversal (path t...**
- **Signals:** CVSS
- **Attack:** Directory Traversal
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-09-06)

> internetarchive is a Python and Command-Line Interface to Archive.org In versions 5.5.0 and below, there is a directory traversal (path traversal) vulnerability in the File.download() method of the internetarchive library. The file.download() method does not properly sanitize use…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-06*
