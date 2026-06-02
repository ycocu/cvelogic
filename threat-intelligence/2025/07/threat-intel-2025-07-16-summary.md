# Daily Threat Intelligence — July 16, 2025

**Digest window (UTC):** 2025-07-16
**Generated:** 2026-06-02T07:33:04Z

## Threat brief

Pivotx: public exploit or PoC linked (cross-site scripting) · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Pivotx: public exploit or PoC linked (cross-site scripting)
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 11 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **21** |


## CVEs

### CVE-2024-11605
**wp-publications_project wp-publications XSS**
- **Signals:** EXP
- **Asset:** wp-publications_project wp-publications
- **Attack:** XSS
- **CVSS max:** 4.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-12T17:03:14.057
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-07-16

> The wp-publications WordPress plugin through 1.2 does not escape filenames before outputting them back in the page, which could allow high privilege users such as admin to perform Stored Cross-Site Scripting attacks even when the unfiltered_html capability is disallowed (for exam…

### CVE-2025-1550
**keras keras RCE**
- **Signals:** EXP
- **Asset:** keras keras
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-31T16:55:39.920
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-07-16

> The Keras Model.load_model function permits arbitrary code execution, even with safe_mode=True, through a manually constructed, malicious .keras archive. By altering the config.json file within the archive, an attacker can specify arbitrary Python modules and functions, along wit…

### CVE-2025-20337
**Cisco Identity Services Engine Injection Vulnerability**
- **Signals:** CVSS
- **Asset:** cisco identity_services_engine
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T13:58:55.447
- **CWE:** CWE-74
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-16)

> A vulnerability in a specific API of Cisco ISE and Cisco ISE-PIC could allow an unauthenticated, remote attacker to execute arbitrary code on the underlying operating system as root. The attacker does not require any valid credentials to exploit this vulnerability.

This vulner…

### CVE-2024-58258
**SugarCRM before 13.0.4 and 14.x before 14.0.1 allows SSRF in the API module because a limited type of code injection can occur.**
- **Signals:** EXP
- **Attack:** SSRF
- **CVSS max:** 7.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-07-16

> SugarCRM before 13.0.4 and 14.x before 14.0.1 allows SSRF in the API module because a limited type of code injection can occur.

### CVE-2025-27210
**An incomplete fix has been identified for CVE-2025-23084 in Node.js, specifically affecting Windows device names like CON, PRN, and AUX.**
- **Signals:** EXP
- **CVSS max:** 7.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2025-07-16

> An incomplete fix has been identified for CVE-2025-23084 in Node.js, specifically affecting Windows device names like CON, PRN, and AUX. 

This vulnerability affects Windows users of `path.join` API.

### CVE-2025-3248
**Langflow Missing Authentication Vulnerability**
- **Signals:** EXP
- **Asset:** langflow langflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T13:57:48.910
- **CWE:** CWE-306
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-07-16

> Langflow versions prior to 1.3.0 are susceptible to code injection in 
the /api/v1/validate/code endpoint. A remote and unauthenticated attacker can send crafted HTTP requests to execute arbitrary
code.

### CVE-2025-34117
**A remote code execution vulnerability exists in multiple Netcore and Netis routers models with firmware released prior to August 2014 due...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-16)

> A remote code execution vulnerability exists in multiple Netcore and Netis routers models with firmware released prior to August 2014 due to the presence of an undocumented backdoor listener on UDP port 53413. Exact version boundaries remain undocumented. An unauthenticated remot…

### CVE-2025-34121
**An unauthenticated arbitrary file upload vulnerability exists in Idera Up.Time Monitoring Station versions up to and including 7.2.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-16)

> An unauthenticated arbitrary file upload vulnerability exists in Idera Up.Time Monitoring Station versions up to and including 7.2. The `wizards/post2file.php` script accepts arbitrary POST parameters, allowing attackers to upload crafted PHP files to the webroot. Successful expl…

### CVE-2025-34125
**An unauthenticated command injection vulnerability exists in the cookie handling process of the lighttpd web server on D-Link DSP-W110A1...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-16)

> An unauthenticated command injection vulnerability exists in the cookie handling process of the lighttpd web server on D-Link DSP-W110A1 firmware version 1.05B01. This occurs when specially crafted cookie values are processed, allowing remote attackers to execute arbitrary comman…

### CVE-2025-34127
**A stack-based buffer overflow exists in Achat v0.150 in its default configuration.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-16)

> A stack-based buffer overflow exists in Achat v0.150 in its default configuration. By sending a specially crafted message to the UDP port 9256, an attacker can overwrite the structured exception handler (SEH) due to insufficient bounds checking on user-supplied input leading to r…

### CVE-2025-34132
**A command injection vulnerability exists in LILIN Digital Video Recorder (DVR) devices prior to firmware version 2.0b60_20200207 via the...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-16)

> A command injection vulnerability exists in LILIN Digital Video Recorder (DVR) devices prior to firmware version 2.0b60_20200207 via the Server field in the NTPUpdate configuration. The web service at /z/zbin/dvr_box fails to properly sanitize input, allowing remote attackers to …

### CVE-2025-34300
**A template injection vulnerability exists in Sawtooth Software’s Lighthouse Studio versions prior to 9.16.14 via the ciwweb.pl http://ciw...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-16)

> A template injection vulnerability exists in Sawtooth Software’s Lighthouse Studio versions prior to 9.16.14 via the  ciwweb.pl http://ciwweb.pl/  Perl web application. Exploitation allows an unauthenticated attacker can execute arbitrary commands.

### CVE-2025-44177
**wss protop Directory Traversal**
- **Signals:** EXP
- **Asset:** wss protop
- **Attack:** Directory Traversal
- **CVSS max:** 8.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-18T18:55:26.647
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2025-07-16

> A directory traversal vulnerability was discovered in White Star Software Protop version 4.4.2-2024-11-27, specifically in the /pt3upd/ endpoint. An unauthenticated attacker can remotely read arbitrary files on the underlying OS using encoded traversal sequences.

### CVE-2025-49677
**microsoft windows_11_22h2 privilege escalation**
- **Signals:** EXP
- **Asset:** microsoft windows_11_22h2
- **Attack:** privilege escalation
- **CVSS max:** 7.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-15T17:16:51.970
- **CWE:** CWE-416
- **Risk score:** 78
- **EXP:** ref published 2025-07-16

> Use after free in Microsoft Brokering File System allows an authorized attacker to elevate privileges locally.

### CVE-2025-49744
**microsoft windows_10_1507 Buffer Overflow**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **Attack:** Buffer Overflow
- **CVSS max:** 7.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-17T21:59:50.070
- **CWE:** CWE-122
- **Risk score:** 78
- **EXP:** ref published 2025-07-16

> Heap-based buffer overflow in Microsoft Graphics Component allows an authorized attacker to elevate privileges locally.

### CVE-2025-52089
**totolink n300rb_firmware privilege escalation**
- **Signals:** EXP
- **Asset:** totolink n300rb_firmware
- **Attack:** privilege escalation
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2025-07-19T03:15:22.727
- **CWE:** CWE-306
- **Risk score:** 78
- **EXP:** ref published 2025-07-16

> A hidden remote support feature protected by a static secret in TOTOLINK N300RB firmware version 8.54 allows an authenticated attacker to execute arbitrary OS commands with root privileges.

### CVE-2025-52367
**pivotx pivotx cross-site scripting**
- **Signals:** EXP
- **Asset:** pivotx pivotx
- **Attack:** cross-site scripting
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T14:45:27.667
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-07-16

> Cross Site Scripting vulnerability in PivotX CMS v.3.0.0 RC 3 allows a remote attacker to execute arbitrary code via the subtitle field.

### CVE-2025-52714
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in shinetheme Traveler traveler allows...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:32:04.213
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-16)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in shinetheme Traveler traveler allows SQL Injection.This issue affects Traveler: from n/a through < 3.2.2.

### CVE-2025-52836
**Incorrect Privilege Assignment vulnerability in Unity Business Technology Pty Ltd The E-Commerce ERP profitori allows Privilege Escalatio...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:32:15.950
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-16)

> Incorrect Privilege Assignment vulnerability in Unity Business Technology Pty Ltd The E-Commerce ERP profitori allows Privilege Escalation.This issue affects The E-Commerce ERP: from n/a through <= 2.1.1.3.

### CVE-2025-53937
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-25T16:37:26.063
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-16)

> WeGIA is an open source web manager with a focus on the Portuguese language and charitable institutions. A SQL Injection vulnerability was identified in the `/controle/control.php` endpoint, specifically in the `cargo` parameter, of WeGIA prior to version 3.4.5. This vulnerabilit…

### CVE-2025-6563
**A cross-site scripting vulnerability is present in the hotspot of MikroTik's RouterOS on versions below 7.19.2.**
- **Signals:** EXP
- **Attack:** XSS
- **CVSS max:** 4.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 78
- **EXP:** ref published 2025-07-16

> A cross-site scripting vulnerability is present in the hotspot of MikroTik's RouterOS on versions below 7.19.2. An attacker can inject the `javascript` protocol in the `dst` parameter. When the victim browses to the malicious URL and logs in, the XSS executes. The POST request us…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-16*
