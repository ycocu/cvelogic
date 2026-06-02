# Daily Threat Intelligence — July 11, 2025

**Digest window (UTC):** 2025-07-11
**Generated:** 2026-06-02T07:33:02Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Adobe Digital Editions — exploitation likelihood rose sharply (EPSS 16% → 34% · rising (+17%)). · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Adobe Digital Editions — exploitation likelihood rose sharply (EPSS 16% → 34% · rising (+17%)).
- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2016-0954
**adobe digital_editions DoS**
- **Signals:** EPSS
- **Asset:** adobe digital_editions
- **Attack:** DoS
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 16.3% (2025-03-30) → 33.7% (2025-07-11), Δ +17.4%**

> Adobe Digital Editions before 4.5.1 allows attackers to execute arbitrary code or cause a denial of service (memory corruption) via unspecified vectors.

### CVE-2025-7503
**An OEM IP camera manufactured by Shenzhen Liandian Communication Technology LTD exposes a Telnet service (port 23) with undocumented, def...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-11)

> An OEM IP camera manufactured by Shenzhen Liandian Communication Technology LTD exposes a Telnet service (port 23) with undocumented, default credentials. The Telnet service is enabled by default and is not disclosed or configurable via the device’s web interface or user manual. …

### CVE-2025-5392
**The GB Forms DB plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 1.0.2 via the gbfdb_tal...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-11)

> The GB Forms DB plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 1.0.2 via the gbfdb_talk_to_front() function. This is due to the function accepting user input and then passing that through call_user_func(). This makes it possible …

### CVE-2025-30023
**axis camera_station RCE**
- **Signals:** CVSS
- **Asset:** axis camera_station
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-23T21:14:03.220
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-07-11)

> The communication protocol used between client and server had a flaw that could lead to an authenticated user performing a remote code execution attack.

### CVE-2025-50121
**A CWE-78: Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability exists that could caus...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-07-11)

> A CWE-78: Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection')
vulnerability exists that could cause unauthenticated remote code execution when a malicious folder is created
over the web interface HTTP when enabled. HTTP is disabled by defaul…

### CVE-2025-52579
**Emerson ValveLink Products store sensitive information in cleartext in memory.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-316
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-11)

> Emerson ValveLink Products store sensitive information in cleartext in memory. The 
sensitive memory might be saved to disk, stored in a core dump, or 
remain uncleared if the product crashes, or if the programmer does not 
properly clear the memory before freeing it.

### CVE-2025-7401
**The Premium Age Verification / Restriction for WordPress plugin for WordPress is vulnerable to arbitrary file read and write due to the e...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-11)

> The Premium Age Verification / Restriction for WordPress plugin for WordPress is vulnerable to arbitrary file read and write due to the existence of an insufficiently protected remote support functionality in remote_tunnel.php in all versions up to, and including, 3.0.2. This mak…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-11*
