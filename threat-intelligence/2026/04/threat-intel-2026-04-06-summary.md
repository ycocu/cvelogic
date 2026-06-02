# Daily Threat Intelligence — April 06, 2026

**Digest window (UTC):** 2026-04-06
**Generated:** 2026-06-02T07:34:51Z

## Threat brief

Fortinet FortiClient EMS added to CISA KEV — confirmed in-the-wild exploitation. · Fortinet FortiWeb: public exploit or PoC linked (Path Traversal) · Zohocorp Manageengine Opmanager — exploitation likelihood rose sharply (EPSS 7.9% → 36% · rising (+28%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Fortinet FortiClient EMS added to CISA KEV — confirmed in-the-wild exploitation.
- Fortinet FortiWeb: public exploit or PoC linked (Path Traversal)
- Zohocorp Manageengine Opmanager — exploitation likelihood rose sharply (EPSS 7.9% → 36% · rising (+28%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 7 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **19** |


## CVEs

### CVE-2026-35616
**Fortinet FortiClient EMS Improper Access Control Vulnerability**
- **Signals:** KEV
- **Asset:** fortinet forticlientems
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T18:12:57.863
- **CWE:** CWE-284
- **Risk score:** 88
- **KEV:** added 2026-04-06

> A improper access control vulnerability in Fortinet FortiClientEMS 7.4.5 through 7.4.6 may allow an unauthenticated attacker to execute unauthorized code or commands via crafted requests.

### CVE-2025-4123
**grafana grafana Path Traversal**
- **Signals:** EXP
- **Asset:** grafana grafana
- **Attack:** Path Traversal
- **CVSS max:** 7.6
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T20:16:28.470
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2026-04-06

> A cross-site scripting (XSS) vulnerability exists in Grafana caused by combining a client path traversal and open redirect. This allows attackers to redirect users to a website that hosts a frontend plugin that will execute arbitrary JavaScript. This vulnerability does not requir…

### CVE-2022-43473
**zohocorp manageengine_opmanager SSRF**
- **Signals:** EPSS
- **Asset:** zohocorp manageengine_opmanager
- **Attack:** SSRF
- **CVSS max:** 5.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:26:33.497
- **CWE:** CWE-611
- **Risk score:** 80
- **EPSS 7.9% (2026-03-31) → 35.6% (2026-04-06), Δ +27.6%**

> A blind XML External Entity (XXE) vulnerability exists in the Add UCS Device functionality of ManageEngine OpManager 12.6.168. A specially crafted XML file can lead to SSRF. An attacker can serve 
a malicious XML payload to trigger this vulnerability.

### CVE-2025-34040
**An arbitrary file upload vulnerability exists in the Zhiyuan OA platform via the wpsAssistServlet interface.**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-29T20:16:28.320
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2026-04-06

> An arbitrary file upload vulnerability exists in the Zhiyuan OA platform via the wpsAssistServlet interface. The realFileType and fileId parameters are improperly validated during multipart file uploads, allowing unauthenticated attackers to upload crafted JSP files outside of in…

### CVE-2025-4524
**The Madara – Responsive and modern WordPress theme for manga sites theme for WordPress is vulnerable to Local File Inclusion in all versi...**
- **Signals:** EXP
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-29T20:16:28.633
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2026-04-06

> The Madara – Responsive and modern WordPress theme for manga sites theme for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 2.2.2 via the 'template' parameter. This makes it possible for unauthenticated attackers to include and execute arbit…

### CVE-2025-54328
**samsung exynos_1080_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** samsung exynos_980_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-07T17:28:19.270
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-04-06)

> An issue was discovered in SMS in Samsung Mobile Processor, Wearable Processor, and Modem Exynos 980, 990, 850, 1080, 2100, 1280, 2200, 1330, 1380, 1480, 2400, 1580, 2500, 9110, W920, W930, W1000, Modem 5123, Modem 5300, and Modem 5400. A Stack-based Buffer Overflow occurs while …

### CVE-2025-55315
**microsoft asp.net_core**
- **Signals:** EXP
- **Asset:** microsoft asp.net_core
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2025-10-28T21:15:37.933
- **CWE:** CWE-444
- **Risk score:** 78
- **EXP:** ref published 2026-04-06

> Inconsistent interpretation of http requests ('http request/response smuggling') in ASP.NET Core allows an authorized attacker to bypass a security feature over a network.

### CVE-2025-58349
**samsung exynos_1080_firmware**
- **Signals:** CVSS
- **Asset:** samsung exynos_990_firmware
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-07T16:08:36.243
- **CWE:** CWE-400
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-06)

> An issue was discovered in L2 in Samsung Mobile Processor, Wearable Processor, and Modem Exynos 980, 990, 850, 1080, 2100, 1280, 2200, 1330, 1380, 1480, 2400, 1580, 2500, 9110, W920, W930, W1000, Modem 5123, Modem 5300, and Modem 5400. Incorrect handling of LTE MAC packets contai…

### CVE-2025-59254
**microsoft windows_10_1507 Buffer Overflow**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **Attack:** Buffer Overflow
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T15:25:36.400
- **CWE:** CWE-122
- **Risk score:** 78
- **EXP:** ref published 2026-04-06

> Heap-based buffer overflow in Windows DWM Core Library allows an authorized attacker to elevate privileges locally.

### CVE-2025-62215
**Microsoft Windows Race Condition Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1809
- **Attack:** privilege escalation
- **CVSS max:** 7.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-14T02:00:02.350
- **CWE:** CWE-362
- **Risk score:** 78
- **EXP:** ref published 2026-04-06

> Concurrent execution using shared resource with improper synchronization ('race condition') in Windows Kernel allows an authorized attacker to elevate privileges locally.

### CVE-2025-64446
**Fortinet FortiWeb Path Traversal Vulnerability**
- **Signals:** EXP
- **Asset:** fortinet fortiweb
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-21T18:27:33.730
- **CWE:** CWE-23
- **Risk score:** 78
- **EXP:** ref published 2026-04-06

> A relative path traversal vulnerability in Fortinet FortiWeb 8.0.0 through 8.0.1, FortiWeb 7.6.0 through 7.6.4, FortiWeb 7.4.0 through 7.4.9, FortiWeb 7.2.0 through 7.2.11, FortiWeb 7.0.0 through 7.0.11 may allow an attacker to execute administrative commands on the system via cr…

### CVE-2026-35050
**oobabooga textgen**
- **Signals:** CVSS
- **Asset:** oobabooga textgen
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T19:28:04.707
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-06)

> text-generation-webui is an open-source web interface for running Large Language Models. Prior to 4.1.1, users can save extention settings in "py" format and in the app root directory. This allows to overwrite python files, for instance the "download-model.py" file could be overw…

### CVE-2026-35171
**linuxfoundation kedro**
- **Signals:** CVSS
- **Asset:** linuxfoundation kedro
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T15:36:21.790
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-06)

> Kedro is a toolbox for production-ready data science. Prior to 1.3.0, Kedro allows the logging configuration file path to be set via the KEDRO_LOGGING_CONFIG environment variable and loads it without validation. The logging configuration schema supports the special () key, which …

### CVE-2026-35174
**chyrplite chyrp_lite Path Traversal**
- **Signals:** CVSS
- **Asset:** chyrplite chyrp_lite
- **Attack:** Path Traversal
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T15:37:14.427
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-06)

> Chyrp Lite is an ultra-lightweight blogging engine. Prior to 2026.01, a path traversal vulnerability exists in the administration console that allows an administrator or a user with Change Settings permission to change the uploads path to any folder. This vulnerability allows the…

### CVE-2026-35178
**forceworkbench forceworkbench RCE**
- **Signals:** CVSS
- **Asset:** forceworkbench forceworkbench
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-16T04:10:58.520
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-06)

> Workbench is a suite of tools for administrators and developers to interact with Salesforce.com organizations via the Force.com APIs. Prior to 65.0.0, Workbench contains remote code execution vulnerability in the timezone conversion flow, which processes attacker-controlled cooki…

### CVE-2026-35392
**goshs goshs**
- **Signals:** CVSS
- **Asset:** goshs goshs
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-09T21:20:20.510
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-06)

> goshs is a SimpleHTTPServer written in Go. Prior to 2.0.0-beta.3, PUT upload in httpserver/updown.go has no path sanitization. This vulnerability is fixed in 2.0.0-beta.3.

### CVE-2026-35393
**goshs goshs**
- **Signals:** CVSS
- **Asset:** goshs goshs
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-09T21:20:27.383
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-06)

> goshs is a SimpleHTTPServer written in Go. Prior to 2.0.0-beta.3, the POST multipart upload directory not sanitized. This vulnerability is fixed in 2.0.0-beta.3.

### CVE-2026-35459
**pyload-ng_project pyload-ng SSRF**
- **Signals:** CVSS
- **Asset:** pyload-ng_project pyload-ng
- **Attack:** SSRF
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-20T17:01:15.083
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-06)

> pyLoad is a free and open-source download manager written in Python. In 0.5.0b3.dev96 and earlier, pyLoad has a server-side request forgery (SSRF) vulnerability. The fix for CVE-2026-33992 added IP validation to BaseDownloader.download() that checks the hostname of the initial do…

### CVE-2026-35471
**goshs goshs Path Traversal**
- **Signals:** CVSS
- **Asset:** goshs goshs
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-09T21:20:35.993
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-06)

> goshs is a SimpleHTTPServer written in Go. Prior to 2.0.0-beta.3, tdeleteFile() missing return after path traversal check. This vulnerability is fixed in 2.0.0-beta.3.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-06*
