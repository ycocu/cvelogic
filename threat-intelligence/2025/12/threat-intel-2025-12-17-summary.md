# Daily Threat Intelligence — December 17, 2025

**Digest window (UTC):** 2025-12-17
**Generated:** 2026-06-02T07:33:59Z

## Threat brief

SonicWall SMA1000 Appliance added to CISA KEV — confirmed in-the-wild exploitation. · Goodtechsystems Goodtech Ssh — exploitation likelihood rose sharply (EPSS 16% → 50% · rising (+33%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- SonicWall SMA1000 Appliance added to CISA KEV — confirmed in-the-wild exploitation.
- Goodtechsystems Goodtech Ssh — exploitation likelihood rose sharply (EPSS 16% → 50% · rising (+33%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 3 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2025-20393
**Cisco Multiple Products Improper Input Validation Vulnerability**
- **Signals:** KEV
- **Asset:** cisco asyncos
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-16T14:00:12.647
- **CWE:** CWE-20
- **Risk score:** 88
- **KEV:** added 2025-12-17

> A vulnerability in the Spam Quarantine feature of Cisco AsyncOS Software for Cisco Secure Email Gateway and Cisco Secure Email and Web Manager could allow an unauthenticated, remote attacker to execute arbitrary system commands on an affected device with root privileges.

This …

### CVE-2008-4726
**goodtechsystems goodtech_ssh Buffer Overflow**
- **Signals:** EPSS
- **Asset:** goodtechsystems goodtech_ssh
- **Attack:** Buffer Overflow
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 84
- **EPSS 16.4% (2025-10-23) → 49.5% (2025-12-17), Δ +33.2%**

> Stack-based buffer overflow in the SFTP subsystem in GoodTech SSH 6.4 allows remote authenticated users to execute arbitrary code via a long string to the (1) open (aka SSH_FXP_OPEN), (2) unlink, (3) opendir, and other unspecified parameters.

### CVE-2025-68110
**churchcrm churchcrm**
- **Signals:** CVSS
- **Asset:** churchcrm churchcrm
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-18T18:29:30.070
- **CWE:** CWE-200
- **CWE:** CWE-209
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-17)

> ChurchCRM is an open-source church management system. Versions prior to 6.5.3 may disclose database information in an error message including the host, ip, username, and password. Version 6.5.3 fixes the issue.

### CVE-2008-4588
**etype eserv Buffer Overflow**
- **Signals:** EPSS
- **Asset:** etype eserv
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 9.1% (2025-12-05) → 28.5% (2025-12-17), Δ +19.4%**

> Stack-based buffer overflow in the FTP server in Etype Eserv 3.x, possibly 3.26, allows remote attackers to cause a denial of service (daemon crash) and possibly execute arbitrary code via a long argument to the ABOR command.

### CVE-2023-53914
**ulicms ulicms Auth Bypass**
- **Signals:** CVSS
- **Asset:** ulicms ulicms
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-24T17:04:53.853
- **CWE:** CWE-639
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-17)

> UliCMS 2023.1 contains an authentication bypass vulnerability that allows unauthenticated attackers to create admin users through mass assignment in the UserController. Attackers can send a crafted POST request to the admin index.php endpoint with specific parameters to generate …

### CVE-2023-53922
**tinywebgallery tinywebgallery RCE**
- **Signals:** CVSS
- **Asset:** tinywebgallery tinywebgallery
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-24T16:50:20.607
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-17)

> TinyWebGallery v2.5 contains a remote code execution vulnerability in the admin upload functionality that allows unauthenticated attackers to upload malicious PHP files. Attackers can upload .phar files with embedded system commands to execute arbitrary code on the server by acce…

### CVE-2023-53923
**ulicms ulicms Privilege Escalation**
- **Signals:** CVSS
- **Asset:** ulicms ulicms
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-12-18T19:16:19.793
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-17)

> UliCMS 2023.1 contains a privilege escalation vulnerability that allows unauthenticated attackers to create administrative accounts through the UserController endpoint. Attackers can send a crafted POST request to /dist/admin/index.php with specific parameters to generate a new a…

### CVE-2025-40602
**SonicWall SMA1000 Missing Authorization Vulnerability**
- **Signals:** KEV
- **Asset:** sonicwall sma6200_firmware
- **Attack:** Privilege Escalation
- **CVSS max:** 6.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T13:57:43.150
- **CWE:** CWE-250
- **Risk score:** 88
- **KEV:** added 2025-12-17

> A local privilege escalation vulnerability due to insufficient authorization in the SonicWall SMA1000 appliance management console (AMC).

### CVE-2025-59374
**ASUS Live Update Embedded Malicious Code Vulnerability**
- **Signals:** KEV
- **Asset:** asus live_update
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-18T15:42:03.790
- **CWE:** CWE-506
- **Risk score:** 88
- **KEV:** added 2025-12-17

> "UNSUPPORTED WHEN ASSIGNED" Certain versions of the ASUS Live Update client were distributed with unauthorized modifications introduced through a supply chain compromise. The modified builds could cause devices meeting specific targeting conditions to perform unintended actions. …

### CVE-2025-67876
**churchcrm churchcrm XSS**
- **Signals:** CVSS
- **Asset:** churchcrm churchcrm
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-18T18:30:45.957
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-17)

> ChurchCRM is an open-source church management system. A stored cross-site scripting (XSS) vulnerability exists in ChurchCRM versions 6.4.0 and prior that allows a low-privilege user with the “Manage Groups” permission to inject persistent JavaScript into group role names. The pay…

### CVE-2025-68109
**churchcrm churchcrm RCE**
- **Signals:** CVSS
- **Asset:** churchcrm churchcrm
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-18T18:30:07.923
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-17)

> ChurchCRM is an open-source church management system. In versions prior to 6.5.3, the Database Restore functionality does not validate the content or file extension of uploaded files. As a result, an attacker can upload a web shell file and subsequently upload a .htaccess file to…

### CVE-2025-68112
**churchcrm churchcrm SQL Injection**
- **Signals:** CVSS
- **Asset:** churchcrm churchcrm
- **Attack:** SQL Injection
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-18T18:28:00.853
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-12-17)

> ChurchCRM is an open-source church management system. In versions prior to 6.5.3, a SQL injection vulnerability in ChurchCRM's Event Attendee Editor allows authenticated users to execute arbitrary SQL commands, leading to complete database compromise, administrative credential th…

### CVE-2025-68275
**churchcrm churchcrm XSS**
- **Signals:** CVSS
- **Asset:** churchcrm churchcrm
- **Attack:** XSS
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-18T18:27:40.170
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-12-17)

> ChurchCRM is an open-source church management system. Versions prior to 6.5.3 have a stored cross-site scripting vulnerability on the pages `View Active People`, `View Inactive people`, and `View All People`. Version 6.5.3 fixes the issue.

### CVE-2025-68400
**churchcrm churchcrm SQL Injection**
- **Signals:** CVSS
- **Asset:** churchcrm churchcrm
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-18T16:46:12.477
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-17)

> ChurchCRM is an open-source church management system. A SQL Injection vulnerability exists in the legacy endpoint `/Reports/ConfirmReportEmail.php` in ChurchCRM prior to version 6.5.3. Although the feature was removed from the UI, the file remains deployed and reachable directly …

### CVE-2025-68435
**nicotsx zerobyte Auth Bypass**
- **Signals:** CVSS
- **Asset:** nicotsx zerobyte
- **Attack:** Auth Bypass
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-05T19:30:16.960
- **CWE:** CWE-305
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-17)

> Zerobyte is a backup automation tool Zerobyte versions prior to 0.18.5 and 0.19.0 contain an authentication bypass vulnerability where authentication middleware is not properly applied to API endpoints. This results in certain API endpoints being accessible without valid session …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-17*
