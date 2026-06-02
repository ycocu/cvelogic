# Daily Threat Intelligence — August 11, 2025

**Digest window (UTC):** 2025-08-11
**Generated:** 2026-06-02T07:33:13Z

## Threat brief

Getgrav Grav: public exploit or PoC linked (RCE) · 3s-software Codesys Gateway-server — exploitation likelihood rose sharply (EPSS 60% → 70% · rising (+11%)). · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Getgrav Grav: public exploit or PoC linked (RCE)
- 3s-software Codesys Gateway-server — exploitation likelihood rose sharply (EPSS 60% → 70% · rising (+11%)).
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 16 |
| EPSS rise | 1 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **26** |


## CVEs

### CVE-2023-32235
**ghost ghost Directory Traversal**
- **Signals:** EXP
- **Asset:** ghost ghost
- **Attack:** Directory Traversal
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2025-01-29T17:15:26.147
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> Ghost before 5.42.1 allows remote attackers to read arbitrary files within the active theme's folder via /assets/built%2F..%2F..%2F/ directory traversal. This occurs in frontend/web/middleware/static-theme.js.

### CVE-2024-27198
**JetBrains TeamCity Authentication Bypass Vulnerability**
- **Signals:** EXP
- **Asset:** jetbrains teamcity
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T20:48:18.440
- **CWE:** CWE-288
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> In JetBrains TeamCity before 2023.11.4 authentication bypass allowing to perform admin actions was possible

### CVE-2012-4705
**3s-software codesys_gateway-server Directory Traversal**
- **Signals:** EPSS
- **Asset:** 3s-software codesys_gateway-server
- **Attack:** Directory Traversal
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-22
- **Risk score:** 84
- **EPSS 59.8% (2025-03-30) → 70.4% (2025-08-11), Δ +10.6%**

> Directory traversal vulnerability in 3S CODESYS Gateway-Server before 2.3.9.27 allows remote attackers to execute arbitrary code via vectors involving a crafted pathname.

### CVE-2012-10037
**PhpTax version 0.8 contains a remote code execution vulnerability in drawimage.php.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-11)

> PhpTax version 0.8 contains a remote code execution vulnerability in drawimage.php. The pfilez GET parameter is unsafely passed to the exec() function without sanitization. A remote attacker can inject arbitrary shell commands, leading to code execution under the web server's con…

### CVE-2012-10038
**Auxilium RateMyPet contains an unauthenticated arbitrary file upload vulnerability in upload_banners.php.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-11)

> Auxilium RateMyPet contains an unauthenticated arbitrary file upload vulnerability in upload_banners.php. The banner upload feature fails to validate file types or enforce authentication, allowing remote attackers to upload malicious PHP files. These files are stored in a web-acc…

### CVE-2012-10039
**ZEN Load Balancer versions 2.0 and 3.0-rc1 contain a command injection vulnerability in content2-2.cgi.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-11)

> ZEN Load Balancer versions 2.0 and 3.0-rc1 contain a command injection vulnerability in content2-2.cgi. The filelog parameter is passed directly into a backtick-delimited exec() call without sanitation. An authenticated attacker can inject arbitrary shell commands, resulting in r…

### CVE-2012-10040
**Openfiler v2.x contains a command injection vulnerability in the system.html page.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-11)

> Openfiler v2.x contains a command injection vulnerability in the system.html page. The device parameter is used to instantiate a NetworkCard object, whose constructor in network.inc calls exec() with unsanitized input. An authenticated attacker can exploit this to execute arbitra…

### CVE-2023-40028
**ghost ghost**
- **Signals:** EXP
- **Asset:** ghost ghost
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:18:33.280
- **CWE:** CWE-22
- **CWE:** CWE-59
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> Ghost is an open source content management system. Versions prior to 5.59.1 are subject to a vulnerability which allows authenticated users to upload files that are symlinks. This can be exploited to perform an arbitrary file read of any file on the host operating system. Site ad…

### CVE-2024-32640
**MASA CMS is an Enterprise Content Management platform based on open source technology.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-11)

> MASA CMS is an Enterprise Content Management platform based on open source technology. Versions prior to 7.4.5, 7.3.12, and 7.2.7 contain a SQL injection vulnerability in the `processAsyncObject` method that can result in remote code execution. Versions 7.4.5, 7.3.12, and 7.2.7 c…

### CVE-2024-4879
**ServiceNow Improper Input Validation Vulnerability**
- **Signals:** EXP
- **Asset:** servicenow servicenow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-03T18:58:11.717
- **CWE:** CWE-1287
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> ServiceNow has addressed an input validation vulnerability that was identified in Vancouver and Washington DC Now Platform releases. This vulnerability could enable an unauthenticated user to remotely execute code within the context of the Now Platform. ServiceNow applied an upda…

### CVE-2025-20124
**cisco identity_services_engine Deserialization**
- **Signals:** EXP
- **Asset:** cisco identity_services_engine
- **Attack:** Deserialization
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-03-28T13:22:42.077
- **CWE:** CWE-502
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> A vulnerability in an API of Cisco ISE could allow an authenticated, remote attacker to execute arbitrary commands as the root user on an affected device.

This vulnerability is due to insecure deserialization of user-supplied Java byte streams by the affected software. An atta…

### CVE-2025-20125
**cisco identity_services_engine privilege escalation**
- **Signals:** EXP
- **Asset:** cisco identity_services_engine
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-03-28T13:37:16.650
- **CWE:** CWE-285
- **CWE:** CWE-862
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> A vulnerability in an API of Cisco ISE could allow an authenticated, remote attacker with valid read-only credentials to obtain sensitive information, change node configurations, and restart the node.

This vulnerability is due to a lack of authorization in a specific API and i…

### CVE-2025-2783
**Google Chromium Mojo Sandbox Escape Vulnerability**
- **Signals:** EXP
- **Asset:** google chrome
- **CVSS max:** 8.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T14:06:49.887
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> Incorrect handle provided in unspecified circumstances in Mojo in Google Chrome on Windows prior to 134.0.6998.177 allowed a remote attacker to perform a sandbox escape via a malicious file. (Chromium security severity: High)

### CVE-2025-41228
**VMware ESXi and vCenter Server contain a reflected cross-site scripting vulnerability due to improper input validation.**
- **Signals:** EXP
- **Attack:** XSS
- **CVSS max:** 4.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> VMware ESXi and vCenter Server contain a reflected cross-site scripting vulnerability due to improper input validation. A malicious actor with network access to the login page of certain ESXi host or vCenter Server URL paths may exploit this issue to steal cookies or redirect to …

### CVE-2025-45146
**codefuse modelcache Deserialization**
- **Signals:** CVSS
- **Asset:** codefuse modelcache
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T18:06:14.457
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-11)

> ModelCache for LLM through v0.2.0 was discovered to contain an deserialization vulnerability via the component /manager/data_manager.py. This vulnerability allows attackers to execute arbitrary code via supplying crafted data.

### CVE-2025-49730
**microsoft windows_10_1507 privilege escalation**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-16T16:38:28.820
- **CWE:** CWE-122
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> Time-of-check time-of-use (toctou) race condition in Microsoft Windows QoS scheduler allows an authorized attacker to elevate privileges locally.

### CVE-2025-50286
**getgrav grav RCE**
- **Signals:** EXP
- **Asset:** getgrav grav
- **Attack:** RCE
- **CVSS max:** 8.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T19:18:37.380
- **CWE:** CWE-434
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> A Remote Code Execution (RCE) vulnerability in Grav CMS v1.7.48 allows an authenticated admin to upload a malicious plugin via the /admin/tools/direct-install interface. Once uploaded, the plugin is automatically extracted and loaded, allowing arbitrary PHP code execution and rev…

### CVE-2025-53187
**Due to an issue in configuration, code that was intended for debugging purposes was included in the market release of the ASPECT FW allow...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-11)

> Due to an issue in configuration, code that was intended for debugging purposes was included in the market release of the ASPECT FW allowing an attacker to bypass authentication. This vulnerability may allow an attacker to change the system time, access files, and make function c…

### CVE-2025-53770
**Microsoft SharePoint Deserialization of Untrusted Data Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft sharepoint_server
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:12:40.607
- **CWE:** CWE-502
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> Deserialization of untrusted data in on-premises Microsoft SharePoint Server allows an unauthorized attacker to execute code over a network.
Microsoft is aware that an exploit for CVE-2025-53770 exists in the wild.
Microsoft is preparing and fully testing a comprehensive update t…

### CVE-2025-5777
**Citrix NetScaler ADC and Gateway Out-of-Bounds Read Vulnerability**
- **Signals:** EXP
- **Asset:** citrix netscaler_application_delivery_controller
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T20:10:26.470
- **CWE:** CWE-125
- **CWE:** CWE-908
- **CWE:** CWE-457
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> Insufficient input validation leading to memory overread when the NetScaler is configured as a Gateway (VPN virtual server, ICA Proxy, CVPN, RDP Proxy) OR AAA virtual server

### CVE-2025-7679
**The ASPECT system allows users to bypass authentication.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-08-11)

> The ASPECT system allows users to bypass authentication.
 This issue affects all versions of ASPECT

### CVE-2025-7769
**Tigo Energy's CCA is vulnerable to a command injection vulnerability in the /cgi-bin/mobile_api endpoint when the DEVICE_PING command is...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-77
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> Tigo Energy's CCA is vulnerable to a command injection vulnerability in the /cgi-bin/mobile_api endpoint when the DEVICE_PING command is called, allowing remote code execution due to improper handling of user input. When used with default credentials, this enables attackers to ex…

### CVE-2025-8471
**projectworlds online_admission_system SQL Injection**
- **Signals:** EXP
- **Asset:** projectworlds online_admission_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-29T01:00:01.613
- **CWE:** CWE-74
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> A vulnerability, which was classified as critical, has been found in projectworlds Online Admission System 1.0. This issue affects some unknown processing of the file /adminlogin.php. The manipulation of the argument a_id leads to sql injection. The attack may be initiated remote…

### CVE-2025-8550
**pybbs_project pybbs cross-site scripting**
- **Signals:** EXP
- **Asset:** pybbs_project pybbs
- **Attack:** cross-site scripting
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-29T01:00:01.613
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> A vulnerability was found in atjiu pybbs up to 6.0.0. It has been declared as problematic. Affected by this vulnerability is an unknown functionality of the file /admin/topic/list. The manipulation of the argument Username leads to cross site scripting. The attack can be launched…

### CVE-2025-8730
**A vulnerability was found in Belkin F9K1009 and F9K1010 2.00.04/2.00.09 and classified as critical.**
- **Signals:** EXP
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-259
- **Risk score:** 78
- **EXP:** ref published 2025-08-11

> A vulnerability was found in Belkin F9K1009 and F9K1010 2.00.04/2.00.09 and classified as critical. Affected by this issue is some unknown functionality of the component Web Interface. The manipulation leads to hard-coded credentials. The attack may be launched remotely. The expl…

### CVE-2025-8853
**Official Document Management System developed by 2100 Technology has an Authentication Bypass vulnerability, allowing unauthenticated rem...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-290
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-11)

> Official Document Management System developed by 2100 Technology has an Authentication Bypass vulnerability, allowing unauthenticated remote attackers to obtain any user's connection token and use it to log into the system as that user.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-11*
