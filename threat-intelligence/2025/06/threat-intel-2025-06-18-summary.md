# Daily Threat Intelligence — June 18, 2025

**Digest window (UTC):** 2025-06-18
**Generated:** 2026-06-02T07:32:54Z

## Threat brief

7 new critical disclosures — review patch status on exposed services.

## Executive summary

- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2025-46157
**efrotech timetrax**
- **Signals:** CVSS
- **Asset:** efrotech timetrax
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-26T15:53:12.230
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-06-18)

> An issue in EfroTech Time Trax v.1.0 allows a remote attacker to execute arbitrary code via the file attachment function in the leave request form

### CVE-2025-20260
**clamav clamav Buffer Overflow**
- **Signals:** CVSS
- **Asset:** clamav clamav
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T19:15:47.690
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-18)

> A vulnerability in the PDF scanning processes of ClamAV could allow an unauthenticated, remote attacker to cause a buffer overflow condition, cause a denial of service (DoS) condition, or execute arbitrary code on an affected device.

This vulnerability exists because memory bu…

### CVE-2025-26198
**vishalmathur cloudclassroom-php_project SQL Injection**
- **Signals:** CVSS
- **Asset:** vishalmathur cloudclassroom-php_project
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-09T18:31:21.063
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-18)

> CloudClassroom-PHP-Project v1.0 contains a critical SQL Injection vulnerability in the loginlinkadmin.php component. The application fails to sanitize user-supplied input in the admin login form before directly including it in SQL queries. This allows unauthenticated attackers to…

### CVE-2025-1562
**funnelkit funnelkit_automations**
- **Signals:** CVSS
- **Asset:** funnelkit funnelkit_automations
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-09T18:55:22.080
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-18)

> The Recover WooCommerce Cart Abandonment, Newsletter, Email Marketing, Marketing Automation By FunnelKit plugin for WordPress is vulnerable to unauthorized arbitrary plugin installation due to a missing capability check on the install_or_activate_addon_plugins() function and a we…

### CVE-2025-26199
**vishalmathur cloudclassroom-php_project**
- **Signals:** CVSS
- **Asset:** vishalmathur cloudclassroom-php_project
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-09T18:25:05.543
- **CWE:** CWE-319
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-18)

> CloudClassroom-PHP-Project v1.0 is affected by an insecure credential transmission vulnerability. The application transmits passwords over unencrypted HTTP during the login process, exposing sensitive credentials to potential interception by network-based attackers. A remote atta…

### CVE-2025-45784
**dlink dph-400s_firmware**
- **Signals:** CVSS
- **Asset:** dlink dph-400se_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-22T14:24:59.443
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-18)

> D-Link DPH-400S/SE VoIP Phone v1.01 contains hardcoded provisioning variables, including PROVIS_USER_PASSWORD, which may expose sensitive user credentials. An attacker with access to the firmware image can extract these credentials using static analysis tools such as strings or x…

### CVE-2025-51381
**An authentication bypass vulnerability exists in KCM3100 Ver1.4.2 and earlier.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-18)

> An authentication bypass vulnerability exists in KCM3100 Ver1.4.2 and earlier. If this vulnerability is exploited, an attacker may bypass the authentication of the product from within the LAN to which the product is connected.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-18*
