# Daily Threat Intelligence — December 20, 2025

**Digest window (UTC):** 2025-12-20
**Generated:** 2026-06-02T07:34:01Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Nero Showtime — exploitation likelihood rose sharply (EPSS 8.5% → 26% · rising (+18%)).

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Nero Showtime — exploitation likelihood rose sharply (EPSS 8.5% → 26% · rising (+18%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2008-7079
**nero showtime Buffer Overflow**
- **Signals:** EPSS
- **Asset:** nero showtime
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 8.5% (2025-03-30) → 26.1% (2025-12-20), Δ +17.6%**

> Buffer overflow in Nero ShowTime 5.0.15.0 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a long entry in a .M3U playlist file.  NOTE: this issue might be related to CVE-2008-0619.

### CVE-2008-6935
**joe_fuhrman exodus DoS**
- **Signals:** EPSS
- **Asset:** joe_fuhrman exodus
- **Attack:** DoS
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 12.1% (2025-04-09) → 28.3% (2025-12-20), Δ +16.2%**

> Argument injection vulnerability in Exodus 0.10 allows remote attackers to inject arbitrary command line arguments, overwrite arbitrary files, and cause a denial of service via encoded spaces in an im:// URI.

### CVE-2025-13619
**The Flex Store Users plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.1.0.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-20)

> The Flex Store Users plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.1.0. This is due to the 'fsUserHandle::signup' and the 'fsSellerRole::add_role_seller' functions not restricting what user roles a user can register with. This …

### CVE-2025-13329
**The File Uploader for WooCommerce plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-20)

> The File Uploader for WooCommerce plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the callback function for the 'add-image-data' REST API endpoint in all versions up to, and including, 1.0.3. This makes it possible for unauthent…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-20*
