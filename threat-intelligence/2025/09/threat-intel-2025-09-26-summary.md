# Daily Threat Intelligence — September 26, 2025

**Digest window (UTC):** 2025-09-26
**Generated:** 2026-06-02T07:33:29Z

## Threat brief

Bolintech Dreamftp Server — exploitation likelihood rose sharply (EPSS 6.2% → 26% · rising (+19%)). · 5 new critical disclosures — review patch status on exposed services.

## Executive summary

- Bolintech Dreamftp Server — exploitation likelihood rose sharply (EPSS 6.2% → 26% · rising (+19%)).
- 5 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 5 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2007-0338
**bolintech dreamftp_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** bolintech dreamftp_server
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 82
- **EPSS 6.2% (2025-09-06) → 25.5% (2025-09-26), Δ +19.3%**

> Heap-based buffer overflow in Dream FTP Server allows remote attackers to execute arbitrary code via a USER command with a large number of format string specifiers, which triggers the overflow during processing of the Server Log.

### CVE-2014-8423
**arris vap2500_firmware**
- **Signals:** EPSS
- **Asset:** arris vap2500_firmware
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-74
- **Risk score:** 84
- **EPSS 31.1% (2025-03-30) → 41.7% (2025-09-26), Δ +10.6%**

> Unspecified vulnerability in the management portal in ARRIS VAP2500 before FW08.41 allows remote attackers to execute arbitrary commands via unknown vectors.

### CVE-2025-58384
**In DOXENSE WATCHDOC before 6.1.1.5332, Deserialization of Untrusted Data can lead to remote code execution through the .NET Remoting libr...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-26)

> In DOXENSE WATCHDOC before 6.1.1.5332, Deserialization of Untrusted Data can lead to remote code execution through the .NET Remoting library in the Watchdoc administration interface.

### CVE-2025-55187
**drivelock drivelock privilege escalation**
- **Signals:** CVSS
- **Asset:** drivelock drivelock
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-08T20:20:03.193
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-09-26)

> In DriveLock 24.1.4 before 24.1.5, 24.2.5 before 24.2.6, and 25.1.2 before 25.1.4, attackers can gain elevated privileges.

### CVE-2025-59934
**Formbricks is an open source qualtrics alternative.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-09-26)

> Formbricks is an open source qualtrics alternative. Prior to version 4.0.1, Formbricks is missing JWT signature verification. This vulnerability stems from a token validation routine that only decodes JWTs (jwt.decode) without verifying their signatures. Both the email verificati…

### CVE-2025-60156
**Cross-Site Request Forgery (CSRF) vulnerability in webandprint AR For WordPress ar-for-wordpress allows Upload a Web Shell to a Web Serve...**
- **Signals:** CVSS
- **Attack:** CSRF
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:34:19.470
- **CWE:** CWE-352
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-09-26)

> Cross-Site Request Forgery (CSRF) vulnerability in webandprint AR For WordPress ar-for-wordpress allows Upload a Web Shell to a Web Server.This issue affects AR For WordPress: from n/a through <= 8.36.

### CVE-2025-60219
**Unrestricted Upload of File with Dangerous Type vulnerability in HaruTheme WooCommerce Designer Pro wc-designer-pro allows Upload a Web S...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:34:24.327
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-26)

> Unrestricted Upload of File with Dangerous Type vulnerability in HaruTheme WooCommerce Designer Pro wc-designer-pro allows Upload a Web Shell to a Web Server.This issue affects WooCommerce Designer Pro: from n/a through <= 1.9.24.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-26*
