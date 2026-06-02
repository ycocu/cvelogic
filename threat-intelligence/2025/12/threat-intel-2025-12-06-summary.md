# Daily Threat Intelligence — December 06, 2025

**Digest window (UTC):** 2025-12-06
**Generated:** 2026-06-02T07:33:55Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Asus Nas-m25 Firmware — exploitation likelihood rose sharply (EPSS 21% → 55% · rising (+34%)).

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Asus Nas-m25 Firmware — exploitation likelihood rose sharply (EPSS 21% → 55% · rising (+34%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2022-4221
**asus nas-m25_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** asus nas-m25_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:34:49.130
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 86
- **EPSS 21.3% (2025-12-02) → 55.2% (2025-12-06), Δ +33.9%**

> Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in Asus NAS-M25 allows an unauthenticated attacker to inject arbitrary OS commands via unsanitized cookie values.This issue affects NAS-M25: through 1.0.1.7.

### CVE-2016-5397
**apache thrift Command Injection**
- **Signals:** EPSS
- **Asset:** apache thrift
- **Attack:** Command Injection
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T02:54:14.087
- **CWE:** CWE-77
- **Risk score:** 84
- **EPSS 7.6% (2025-10-18) → 22.6% (2025-12-06), Δ +15.0%**

> The Apache Thrift Go client library exposed the potential during code generation for command injection due to using an external formatting tool. Affected Apache Thrift 0.9.3 and older, Fixed in Apache Thrift 0.10.0.

### CVE-2025-12673
**The Flex QR Code Generator plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the update...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-06)

> The Flex QR Code Generator plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the update_qr_code() function in all versions up to, and including, 1.2.7. This makes it possible for unauthenticated attackers to upload arbitrary files…

### CVE-2002-2379
**cisco as5350 DoS**
- **Signals:** EPSS
- **Asset:** cisco as5350
- **Attack:** DoS
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-310
- **Risk score:** 81
- **EPSS 29.7% (2025-09-16) → 40.9% (2025-12-06), Δ +11.2%**

> Cisco AS5350 IOS 12.2(11)T with access control lists (ACLs) applied and possibly with ssh running allows remote attackers to cause a denial of service (crash) via a port scan, possibly due to an ssh bug. NOTE: this issue could not be reproduced by the vendor

### CVE-2025-13377
**10web 10web_booster**
- **Signals:** CVSS
- **Asset:** 10web 10web_booster
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-11T21:45:39.327
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-12-06)

> The 10Web Booster – Website speed optimization, Cache & Page Speed optimizer plugin for WordPress is vulnerable to arbitrary folder deletion due to insufficient file path validation in the get_cache_dir_for_page_from_url() function in all versions up to, and including, 2.32.7. Th…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-06*
