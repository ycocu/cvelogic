# Daily Threat Intelligence — June 05, 2026

**Digest window (UTC):** 2026-06-05
**Generated:** 2026-06-06T03:58:09Z

## Threat brief

SolarWinds Serv-U added to CISA KEV — confirmed in-the-wild exploitation. · The Contest Gallery – Upload & Vote Photos, Media, Sell with PayPal & Stripe plugin for WordPress...: public exploit or PoC linked (SQL Injection) · Microsoft Sharepoint Server — exploitation likelihood rose sharply (EPSS 12% → 32% · rising (+20%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- SolarWinds Serv-U added to CISA KEV — confirmed in-the-wild exploitation.
- The Contest Gallery – Upload & Vote Photos, Media, Sell with PayPal & Stripe plugin for WordPress...: public exploit or PoC linked (SQL Injection)
- Microsoft Sharepoint Server — exploitation likelihood rose sharply (EPSS 12% → 32% · rising (+20%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 1 |
| EPSS rise | 9 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **21** |


## CVEs

### CVE-2026-28318
**SolarWinds Serv-U Uncontrolled Resource Consumption Vulnerability**
- **Signals:** KEV
- **Asset:** solarwinds serv-u
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-05T19:32:38.510
- **CWE:** CWE-400
- **Risk score:** 88
- **KEV:** added 2026-06-05

> SolarWinds Serv-U is susceptible to specially crafted POST requests that crash the Serv-U service without authentication using Content-Encoding: deflate. Mitigation steps are provided to secure customer environments in the SolarWinds Trust Center if you are unable to deploy the u…

### CVE-2026-3180
**The Contest Gallery – Upload & Vote Photos, Media, Sell with PayPal & Stripe plugin for WordPress is vulnerable to blind SQL Injection vi...**
- **Signals:** EXP
- **Attack:** SQL Injection
- **CVSS max:** 7.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-22T21:26:58.303
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2026-06-05

> The Contest Gallery – Upload & Vote Photos, Media, Sell with PayPal & Stripe plugin for WordPress is vulnerable to blind SQL Injection via the ‘cgLostPasswordEmail’ and the ’cgl_mail’ parameter in all versions up to, and including, 28.1.4 due to insufficient escaping on the user …

### CVE-2025-54897
**microsoft sharepoint_server Deserialization**
- **Signals:** EPSS
- **Asset:** microsoft sharepoint_server
- **Attack:** Deserialization
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T16:45:25.173
- **CWE:** CWE-502
- **Risk score:** 84
- **EPSS 11.9% (2026-05-26) → 31.9% (2026-06-05), Δ +19.9%**

> Deserialization of untrusted data in Microsoft Office SharePoint allows an authorized attacker to execute code over a network.

### CVE-2003-1567
**microsoft internet_information_services**
- **Signals:** EPSS
- **Asset:** microsoft internet_information_services
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-28T19:16:20.260
- **CWE:** CWE-200
- **CWE:** CWE-200
- **Risk score:** 82
- **EPSS 66.5% (2026-05-29) → 79.9% (2026-06-05), Δ +13.4%**

> The undocumented TRACK method in Microsoft Internet Information Services (IIS) 5.0 returns the content of the original request in the body of the response, which makes it easier for remote attackers to steal cookies and authentication credentials, or bypass the HttpOnly protectio…

### CVE-2005-2150
**microsoft windows_2000**
- **Signals:** EPSS
- **Asset:** microsoft windows_2000
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 77
- **EPSS 26.8% (2025-12-28) → 38.2% (2026-06-05), Δ +11.4%**

> Windows NT 4.0 and Windows 2000 before URP1 for Windows 2000 SP4 does not properly prevent NULL sessions from accessing certain alternate named pipes, which allows remote attackers to (1) list Windows services via svcctl or (2) read eventlogs via eventlog.

### CVE-2015-2797
**airties air_firmware Buffer Overflow**
- **Signals:** EPSS
- **Asset:** airties air_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 77.0% (2026-03-04) → 87.4% (2026-06-05), Δ +10.4%**

> Stack-based buffer overflow in AirTies Air 6372, 5760, 5750, 5650TT, 5453, 5444TT, 5443, 5442, 5343, 5342, 5341, and 5021 DSL modems with firmware 1.0.2.0 and earlier allows remote attackers to execute arbitrary code via a long string in the redirect parameter to cgi-bin/login.

### CVE-2016-9841
**apple active_iq_unified_manager**
- **Signals:** EPSS
- **Asset:** zlib zlib
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **Risk score:** 83
- **EPSS 13.5% (2026-05-29) → 23.6% (2026-06-05), Δ +10.1%**

> inffast.c in zlib 1.2.8 might allow context-dependent attackers to have unspecified impact by leveraging improper pointer arithmetic.

### CVE-2018-13380
**fortinet fortios XSS**
- **Signals:** EPSS
- **Asset:** fortinet fortios
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:46:59.383
- **CWE:** CWE-79
- **Risk score:** 78
- **EPSS 22.9% (2026-04-19) → 37.4% (2026-06-05), Δ +14.5%**

> A Cross-site Scripting (XSS) vulnerability in Fortinet FortiOS 6.0.0 to 6.0.4, 5.6.0 to 5.6.7, 5.4.0 to 5.4.12, 5.2 and below and Fortinet FortiProxy 2.0.0, 1.2.8 and below under SSL VPN web portal allows attacker to execute unauthorized malicious script code via the error or mes…

### CVE-2020-5504
**debian debian_linux SQL Injection**
- **Signals:** EPSS
- **Asset:** phpmyadmin phpmyadmin
- **Attack:** SQL Injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T15:15:46.240
- **CWE:** CWE-89
- **Risk score:** 83
- **EPSS 10.6% (2026-05-31) → 22.2% (2026-06-05), Δ +11.5%**

> In phpMyAdmin 4 before 4.9.4 and 5 before 5.0.1, SQL injection exists in the user accounts page. A malicious user could inject custom SQL in place of their own username when creating queries to this page. An attacker must have a valid MySQL account to access the server.

### CVE-2022-27043
**yearning yearning Directory Traversal**
- **Signals:** EPSS
- **Asset:** yearning yearning
- **Attack:** Directory Traversal
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:55:01.210
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 25.5% (2026-03-22) → 44.7% (2026-06-05), Δ +19.2%**

> Yearning versions 2.3.1 and 2.3.2 Interstellar GA and 2.3.4 - 2.3.6 Neptune is vulnerable to Directory Traversal.

### CVE-2022-28508
**mantisbt mantisbt cross-site scripting**
- **Signals:** EPSS
- **Asset:** mantisbt mantisbt
- **Attack:** cross-site scripting
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:57:27.417
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 7.1% (2026-06-03) → 22.0% (2026-06-05), Δ +14.9%**

> An XSS issue was discovered in browser_search_plugin.php in MantisBT before 2.25.2. Unescaped output of the return parameter allows an attacker to inject code into a hidden input field.

### CVE-2026-11414
**A hard-coded cryptographic key is used by Altium Enterprise Server to sign file download URLs in the Vault service.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 10.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-05T20:49:52.790
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-05)

> A hard-coded cryptographic key is used by Altium Enterprise Server to sign file download URLs in the Vault service. Because the key is identical across all installations, an unauthenticated network attacker who can reach the server can forge valid download signatures and retrieve…

### CVE-2026-11419
**A path traversal vulnerability exists in the Altium Enterprise Server Vault Service UploadController due to improper validation of a user...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-05T20:49:52.790
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-05)

> A path traversal vulnerability exists in the Altium Enterprise Server Vault Service UploadController due to improper validation of a user-controlled path component in image upload requests. An authenticated user can supply a crafted absolute path so that the configured storage ro…

### CVE-2026-11420
**Two path traversal vulnerabilities in the Network Installation Service (NIS) of Altium Enterprise Server allow an unauthenticated network...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 10.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-05T20:49:52.790
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-05)

> Two path traversal vulnerabilities in the Network Installation Service (NIS) of Altium Enterprise Server allow an unauthenticated network attacker to write arbitrary files to any writable location on the server filesystem and to read package archive files from the server. No auth…

### CVE-2026-11423
**A path traversal vulnerability exists in the Altium Enterprise Server Collaboration Service due to improper handling of user-supplied fil...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Received
- **NVD modified:** 2026-06-05T21:16:29.353
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-05)

> A path traversal vulnerability exists in the Altium Enterprise Server Collaboration Service due to improper handling of user-supplied filenames in the MCAD and Simulation file download flows. A regular authenticated user can submit a collaboration message containing a crafted fil…

### CVE-2026-11429
**A path traversal vulnerability exists in the Git Service component shared by Altium Enterprise Server and Altium 365.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Received
- **NVD modified:** 2026-06-05T22:16:47.503
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-05)

> A path traversal vulnerability exists in the Git Service component shared by Altium Enterprise Server and Altium 365. The service accepts a sequence of post-clone file-manipulation operations that use user-supplied paths without validation, allowing an authenticated user with bas…

### CVE-2026-45758
**Guardrails AI is a Python framework that helps build AI applications.**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-05T20:51:20.400
- **CWE:** CWE-506
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-05)

> Guardrails AI is a Python framework that helps build AI applications. On May 11, 2026 at approximately 6:00 PM Pacific, an attacker published a malicious version of `guardrails-ai` (0.10.1) to PyPI. Aany user who installed `guardrails-ai==0.10.1` from PyPI on May 11, 2026 may be …

### CVE-2026-45777
**OpenXDMoD is an open framework for collecting and analyzing HPC metrics.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-06-05T20:48:30.267
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-05)

> OpenXDMoD is an open framework for collecting and analyzing HPC metrics. Starting in version 9.5.0 and prior to version 11.0.3, an attacker can remotely execute arbitrary system commands on the web server hosting Open XDMoD with the privileges of the web server process. This coul…

### CVE-2026-45779
**OpenXDMoD is an open framework for collecting and analyzing HPC metrics.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-06-05T20:48:30.267
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-05)

> OpenXDMoD is an open framework for collecting and analyzing HPC metrics. An SQL injection vulnerability exists in Open XDMoD versions prior to 10.0.3 that allows an unauthenticated remote attacker to execute arbitrary SQL statements. Exploitation requires no authentication or use…

### CVE-2026-46399
**HAX CMS helps manage microsite universe with PHP or NodeJs backends.**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-06-05T19:20:19.607
- **CWE:** CWE-15
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-05)

> HAX CMS helps manage microsite universe with PHP or NodeJs backends. The PHP version of HAX CMS prior to version 26.0.0 has an authenticated file overwrite vulnerability. An attacker can exploit this vulnerability to configure malicious Git filter commands and achieve code execut…

### CVE-2026-46496
**HAX CMS helps manage microsite universe with PHP or NodeJs backends.**
- **Signals:** CVSS
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-06-05T20:17:34.710
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-05)

> HAX CMS helps manage microsite universe with PHP or NodeJs backends. A stored cross-site scripting (XSS) vulnerability exists in versions prior to 26.0.0 due to improper sanitization of the `<video-player>` component. The component allows `javascript:` URIs in the `source` attrib…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-05*
