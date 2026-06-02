# Daily Threat Intelligence — May 17, 2025

**Digest window (UTC):** 2025-05-17
**Generated:** 2026-06-02T07:32:43Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · 5 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- 5 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 5 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2025-4918
**mozilla firefox Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:01.407
- **CWE:** CWE-125
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-17)

> An attacker was able to perform an out-of-bounds read or write on a JavaScript `Promise` object. This vulnerability was fixed in Firefox 138.0.4, Firefox ESR 128.10.1, Firefox ESR 115.23.1, Thunderbird 128.10.2, and Thunderbird 138.0.2.

### CVE-2025-4389
**The Crawlomatic Multipage Scraper Post Generator plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type va...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-17)

> The Crawlomatic Multipage Scraper Post Generator plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the crawlomatic_generate_featured_image() function in all versions up to, and including, 2.6.8.1. This makes it possible for unauth…

### CVE-2025-4391
**The Echo RSS Feed Post Generator plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-17)

> The Echo RSS Feed Post Generator plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the echo_generate_featured_image() function in all versions up to, and including, 5.4.8.1. This makes it possible for unauthenticated attackers to …

### CVE-2025-47945
**donetick donetick**
- **Signals:** CVSS
- **Asset:** donetick donetick
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-12T16:28:42.797
- **CWE:** CWE-453
- **CWE:** CWE-1188
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-17)

> Donetick an open-source app for managing tasks and chores. Prior to version 0.1.44, the application uses JSON Web Tokens (JWT) for authentication, but the signing secret has a weak default value. While the responsibility is left to the system administrator to change it, this appr…

### CVE-2025-48187
**infiniflow ragflow**
- **Signals:** CVSS
- **Asset:** infiniflow ragflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-12T16:29:12.860
- **CWE:** CWE-307
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-17)

> RAGFlow through 0.18.1 allows account takeover because it is possible to conduct successful brute-force attacks against email verification codes to perform arbitrary account registration, login, and password reset. Codes are six digits and there is no rate limiting.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-17*
