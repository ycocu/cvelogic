# Daily Threat Intelligence — October 07, 2025

**Digest window (UTC):** 2025-10-07
**Generated:** 2026-06-02T07:33:33Z

## Threat brief

Synacor Zimbra Collaboration Suite (ZCS) added to CISA KEV — confirmed in-the-wild exploitation. · Zte Zxhn H108n R1a Firmware — exploitation likelihood rose sharply (EPSS 17% → 35% · rising (+18%)). · 5 new critical disclosures — review patch status on exposed services.

## Executive summary

- Synacor Zimbra Collaboration Suite (ZCS) added to CISA KEV — confirmed in-the-wild exploitation.
- Zte Zxhn H108n R1a Firmware — exploitation likelihood rose sharply (EPSS 17% → 35% · rising (+18%)).
- 5 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 5 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2025-27915
**Synacor Zimbra Collaboration Suite (ZCS) Cross-site Scripting Vulnerability**
- **Signals:** KEV
- **Asset:** synacor zimbra_collaboration_suite
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-04T16:45:11.053
- **CWE:** CWE-79
- **Risk score:** 88
- **KEV:** added 2025-10-07

> An issue was discovered in Zimbra Collaboration (ZCS) 9.0 and 10.0 and 10.1. A stored cross-site scripting (XSS) vulnerability exists in the Classic Web Client due to insufficient sanitization of HTML content in ICS files. When a user views an e-mail message containing a maliciou…

### CVE-2015-7248
**zte zxhn_h108n_r1a_firmware**
- **Signals:** EPSS
- **Asset:** zte zxhn_h108n_r1a_firmware
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-200
- **Risk score:** 82
- **EPSS 17.2% (2025-03-30) → 35.4% (2025-10-07), Δ +18.2%**

> ZTE ZXHN H108N R1A devices before ZTE.bhs.ZXHNH108NR1A.k_PE allow remote attackers to discover usernames and password hashes by reading the cgi-bin/webproc HTML source code, a different vulnerability than CVE-2015-8703.

### CVE-2025-44823
**nagios log_server**
- **Signals:** CVSS
- **Asset:** nagios log_server
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T16:41:01.823
- **CWE:** CWE-497
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-10-07)

> Nagios Log Server before 2024R1.3.2 allows authenticated users to retrieve cleartext administrative API keys via a /nagioslogserver/index.php/api/system/get_users call. This is GL:NLS#475.

### CVE-2025-0603
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Callvision Healthcare Callvision Em...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-07)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Callvision Healthcare Callvision Emergency Code allows SQL Injection, Blind SQL Injection.This issue affects Callvision Emergency Code: before V3.0.

### CVE-2025-11462
**Improper Link Resolution Before File Access in the AWS VPN Client for macOS versions 1.3.2- 5.2.0 allows a local user to execute code wit...**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-59
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-07)

> Improper Link Resolution Before File Access in the AWS VPN Client for macOS versions 1.3.2- 5.2.0 allows a local user to execute code with elevated privileges. Insufficient validation checks on the log destination directory during log rotation could allow a non-administrator user…

### CVE-2025-3450
**An Improper Resource Locking vulnerability in the SDM component of B&R Automation Runtime versions before 6.3 and before Q4.93 may allow...**
- **Signals:** CVSS
- **Attack:** DoS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-413
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-07)

> An Improper Resource Locking vulnerability in the SDM component of B&R Automation Runtime versions before 6.3 and before Q4.93 may allow an unauthenticated network-based attacker to delete data causing denial of service conditions.

### CVE-2025-52021
**A SQL Injection vulnerability exists in the edit_product.php file of PuneethReddyHC Online Shopping System Advanced 1.0.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-07)

> A SQL Injection vulnerability exists in the edit_product.php file of PuneethReddyHC Online Shopping System Advanced 1.0. The product_id GET parameter is unsafely passed to a SQL query without proper validation or parameterization.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-07*
