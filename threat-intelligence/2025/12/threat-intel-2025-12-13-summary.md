# Daily Threat Intelligence — December 13, 2025

**Digest window (UTC):** 2025-12-13
**Generated:** 2026-06-02T07:33:58Z

## Threat brief

WordPress plugin RCE/exploit activity: 3 CVEs flagged today. · 7 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 3 CVEs flagged today.
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

### CVE-2025-10738
**The URL Shortener Plugin For WordPress plugin for WordPress is vulnerable to SQL Injection via the ‘analytic_id’ parameter in all version...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-13)

> The URL Shortener Plugin For WordPress plugin for WordPress is vulnerable to SQL Injection via the ‘analytic_id’ parameter in all versions up to, and including, 3.0.7 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQ…

### CVE-2025-14440
**The JAY Login & Register plugin for WordPress is vulnerable to authentication bypass in versions up to, and including, 2.4.01.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-565
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-13)

> The JAY Login & Register plugin for WordPress is vulnerable to authentication bypass in versions up to, and including, 2.4.01. This is due to incorrect authentication checking in the 'jay_login_register_process_switch_back' function with the 'jay_login_register_process_switch_bac…

### CVE-2025-11693
**The Export WP Page to Static HTML & PDF plugin for WordPress is vulnerable to Sensitive Information Exposure in all versions up to, and i...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-13)

> The Export WP Page to Static HTML & PDF plugin for WordPress is vulnerable to Sensitive Information Exposure in all versions up to, and including, 4.3.4 through publicly exposed cookies.txt files containing authentication cookies. This makes it possible for unauthenticated attack…

### CVE-2025-36747
**growatt shine_lan-x_firmware**
- **Signals:** CVSS
- **Asset:** growatt shine_lan-x_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-14T18:05:23.253
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-12-13)

> ShineLan-X contains a set of credentials for an FTP server was found within the firmware, allowing testers to establish an insecure FTP connection with the server. This may allow an attacker to replace legitimate files being deployed to devices with their own malicious versions, …

### CVE-2025-36751
**Encryption is missing on the configuration interface for Growatt ShineLan-X and MIC 3300TL-X.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-311
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-12-13)

> Encryption is missing on the configuration interface for Growatt ShineLan-X and MIC 3300TL-X. This allows an attacker with access to the network to intercept and potentially manipulate communication requests between the inverter and its cloud endpoint.

### CVE-2025-36752
**growatt shine_lan-x_firmware**
- **Signals:** CVSS
- **Asset:** growatt shine_lan-x_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-14T18:05:00.300
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-12-13)

> Growatt ShineLan-X communication dongle has an undocumented backup account with undocumented credentials which allows significant level access to the device, such as allowing any attacker to access the Setting Center. This means that this is effectively backdoor for all devices u…

### CVE-2025-36754
**The authentication mechanism on web interface is not properly implemented.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-290
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-13)

> The authentication mechanism on web interface is not properly implemented. It is possible to bypass authentication checks by crafting a post request with new settings since there is no session token or authentication in place. This would allow an attacker for instance to point th…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-13*
