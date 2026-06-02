# Daily Threat Intelligence — September 16, 2025

**Digest window (UTC):** 2025-09-16
**Generated:** 2026-06-02T07:33:25Z

## Threat brief

Sohamjuhin Tourism Management System: public exploit or PoC linked (RCE) · Powerdns Authoritative — exploitation likelihood rose sharply (EPSS 32% → 86% · rising (+54%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Sohamjuhin Tourism Management System: public exploit or PoC linked (RCE)
- Powerdns Authoritative — exploitation likelihood rose sharply (EPSS 32% → 86% · rising (+54%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 12 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **25** |


## CVEs

### CVE-2021-43579
**debian debian_linux RCE**
- **Signals:** EXP
- **Asset:** htmldoc_project htmldoc
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:29:28.970
- **CWE:** CWE-787
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> A stack-based buffer overflow in image_load_bmp() in HTMLDOC <= 1.9.13 results in remote code execution if the victim converts an HTML document linking to a crafted BMP file.

### CVE-2023-34927
**casbin casdoor CSRF**
- **Signals:** EXP
- **Asset:** casbin casdoor
- **Attack:** CSRF
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:07:40.793
- **CWE:** CWE-352
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> Casdoor v1.331.0 and below was discovered to contain a Cross-Site Request Forgery (CSRF) in the endpoint /api/set-password. This vulnerability allows attackers to arbitrarily change the victim user's password via supplying a crafted URL.

### CVE-2016-5427
**powerdns authoritative DoS**
- **Signals:** EPSS
- **Asset:** powerdns authoritative
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-399
- **Risk score:** 82
- **EPSS 32.0% (2025-03-30) → 85.5% (2025-09-16), Δ +53.5%**

> PowerDNS (aka pdns) Authoritative Server before 3.4.10 does not properly handle a . (dot) inside labels, which allows remote attackers to cause a denial of service (backend CPU consumption) via a crafted DNS query.

### CVE-2012-0266
**ntrglobal ntr_activex_control Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ntrglobal ntr_activex_control
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 55.4% (2025-03-30) → 73.7% (2025-09-16), Δ +18.3%**

> Multiple stack-based buffer overflows in the NTR ActiveX control before 2.0.4.8 allow remote attackers to execute arbitrary code via (1) a long bstrUrl parameter to the StartModule method, (2) a long bstrParams parameter to the Check method, a long bstrUrl parameter to the (3) Do…

### CVE-2016-4531
**rockwellautomation factorytalk_energrymetrix**
- **Signals:** EPSS
- **Asset:** rockwellautomation factorytalk_energrymetrix
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-285
- **Risk score:** 82
- **EPSS 6.2% (2025-09-10) → 21.0% (2025-09-16), Δ +14.8%**

> Rockwell Automation FactoryTalk EnergyMetrix before 2.20.00 does not invalidate credentials upon a logout action, which makes it easier for remote attackers to obtain access by leveraging an unattended workstation.

### CVE-2023-44487
**HTTP/2 Rapid Reset Attack Vulnerability**
- **Signals:** EXP
- **Asset:** siemens simatic_s7-1500_cpu_1518f-4_pn\/dp_mfp_firmware
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-12T15:10:32.260
- **CWE:** CWE-400
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> The HTTP/2 protocol allows a denial of service (server resource consumption) because request cancellation can reset many streams quickly, as exploited in the wild in August through October 2023.

### CVE-2024-13149
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection'), CWE - 200 - Exposure of Sensitive Information to an...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-01T13:16:27.630
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-16)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection'), CWE - 200 - Exposure of Sensitive Information to an Unauthorized Actor vulnerability in Arma Store Armalife allows SQL Injection.

This issue affects Armalife: through 20250916. 

NOTE: The vend…

### CVE-2025-10046
**The ELEX WooCommerce Google Shopping (Google Product Feed) plugin for WordPress is vulnerable to SQL Injection via the 'file_to_delete' p...**
- **Signals:** EXP
- **Attack:** SQL Injection
- **CVSS max:** 4.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> The ELEX WooCommerce Google Shopping (Google Product Feed) plugin for WordPress is vulnerable to SQL Injection via the 'file_to_delete' parameter in all versions up to, and including, 1.4.3 due to insufficient escaping on the user supplied parameter and lack of sufficient prepara…

### CVE-2025-21333
**Microsoft Windows Hyper-V NT Kernel Integration VSP Heap-based Buffer Overflow Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft windows_10_21h2
- **Attack:** Buffer Overflow
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-03T15:08:08.450
- **CWE:** CWE-122
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> Windows Hyper-V NT Kernel Integration VSP Elevation of Privilege Vulnerability

### CVE-2025-24893
**XWiki Platform Eval Injection Vulnerability**
- **Signals:** EXP
- **Asset:** xwiki xwiki
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T13:17:09.460
- **CWE:** CWE-95
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. Any guest can perform arbitrary remote code execution through a request to `SolrSearch`. This impacts the confidentiality, integrity and availability of the whole XWiki instal…

### CVE-2025-34183
**ilevia eve_x1_server_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** ilevia eve_x1_server_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-25T14:56:22.493
- **CWE:** CWE-532
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-16)

> Ilevia EVE X1 Server version ≤ 4.7.18.0.eden contains a vulnerability in its server-side logging mechanism that allows unauthenticated remote attackers to retrieve plaintext credentials from exposed .log files. This flaw enables full authentication bypass and system compromise th…

### CVE-2025-34184
**ilevia eve_x1_server_firmware DoS**
- **Signals:** CVSS
- **Asset:** ilevia eve_x1_server_firmware
- **Attack:** DoS
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-25T14:56:30.853
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-16)

> Ilevia EVE X1 Server version ≤ 4.7.18.0.eden contains an unauthenticated OS command injection vulnerability in the /ajax/php/login.php script. Remote attackers can execute arbitrary system commands by injecting payloads into the 'passwd' HTTP POST parameter, leading to full syste…

### CVE-2025-34186
**ilevia eve_x1_server_firmware**
- **Signals:** CVSS
- **Asset:** ilevia eve_x1_server_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T14:16:27.513
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-16)

> Ilevia EVE X1/X5 Server version ≤ 4.7.18.0.eden contains a vulnerability in its authentication mechanism. Unsanitized input is passed to a system() call for authentication, allowing attackers to inject special characters and manipulate command parsing. Because the binary interpre…

### CVE-2025-34187
**ilevia eve_x1_server_firmware Privilege Escalation**
- **Signals:** CVSS
- **Asset:** ilevia eve_x1_server_firmware
- **Attack:** Privilege Escalation
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-25T14:51:36.743
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-16)

> Ilevia EVE X1/X5 Server version ≤ 4.7.18.0.eden contains a misconfiguration in the sudoers file that allows passwordless execution of certain Bash scripts. If these scripts are writable by web-facing users or accessible via command injection, attackers can replace them with malic…

### CVE-2025-41243
**Spring Cloud Gateway Server Webflux may be vulnerable to Spring Environment property modification.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-16)

> Spring Cloud Gateway Server Webflux may be vulnerable to Spring Environment property modification.

An application should be considered vulnerable when all the following are true:

  *  The application is using Spring Cloud Gateway Server Webflux (Spring Cloud Gateway Server WebM…

### CVE-2025-47917
**arm mbed_tls Use-After-Free**
- **Signals:** EXP
- **Asset:** arm mbed_tls
- **Attack:** Use-After-Free
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:19:05.870
- **CWE:** CWE-416
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> Mbed TLS before 3.6.4 allows a use-after-free in certain situations of applications that are developed in accordance with the documentation. The function mbedtls_x509_string_to_names() takes a head argument that is documented as an output argument. The documentation does not sugg…

### CVE-2025-54391
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-16)

> A vulnerability in the EnableTwoFactorAuthRequest SOAP endpoint of Zimbra Collaboration (ZCS) allows an attacker with valid user credentials to bypass Two-Factor Authentication (2FA) protection. The attacker can configure an additional 2FA method (either a third-party authenticat…

### CVE-2025-55911
**oxygenz clipbucket**
- **Signals:** EXP
- **Asset:** oxygenz clipbucket
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T17:13:54.607
- **CWE:** CWE-77
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> An issue Clip Bucket v.5.5.2 Build#90 allows a remote attacker to execute arbitrary codes via the file_downloader.php and the file parameter

### CVE-2025-55912
**oxygenz clipbucket**
- **Signals:** EXP
- **Asset:** oxygenz clipbucket
- **CVSS max:** 7.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T17:14:53.060
- **CWE:** CWE-434
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> An issue in ClipBucket 5.5.0 and prior versions allows an unauthenticated attacker can exploit the plupload endpoint in photo_uploader.php to upload arbitrary files without any authentication, due to missing access controls in the upload handler

### CVE-2025-56557
**tuya tuya privilege escalation**
- **Signals:** CVSS
- **Asset:** tuya tuya
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-02T19:13:02.203
- **CWE:** CWE-250
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-16)

> An issue discovered in the Tuya Smart Life App 5.6.1 allows attackers to unprivileged control Matter devices via the Matter protocol.

### CVE-2025-57631
**tduckcloud tduck SQL Injection**
- **Signals:** CVSS
- **Asset:** tduckcloud tduck
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-23T16:43:11.133
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-16)

> SQL Injection vulnerability in TDuckCloud v.5.1 allows a remote attacker to execute arbitrary code via the Add a file upload module

### CVE-2025-57642
**sohamjuhin tourism_management_system RCE**
- **Signals:** EXP
- **Asset:** sohamjuhin tourism_management_system
- **Attack:** RCE
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T19:28:54.450
- **CWE:** CWE-434
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> A Shell Upload vulnerability in Tourism Management System 2.0 allows an attacker to upload and execute arbitrary PHP shell scripts on the server, leading to remote code execution and unauthorized access to the system. This can result in the compromise of sensitive data and system…

### CVE-2025-59334
**mohammadzain2008 linkr**
- **Signals:** CVSS
- **Asset:** mohammadzain2008 linkr
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-08T19:16:13.530
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-09-16)

> Linkr is a lightweight file delivery system that downloads files from a webserver. Linkr versions through 2.0.0 do not verify the integrity or authenticity of .linkr manifest files before using their contents, allowing a tampered manifest to inject arbitrary file entries into a p…

### CVE-2025-8311
**dotCMS versions 24.03.22 and after, identified a Boolean-based blind SQLi vulnerability in the /api/v1/contenttype endpoint.**
- **Signals:** EXP
- **Attack:** SQL injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> dotCMS versions 24.03.22 and after, identified a Boolean-based blind SQLi vulnerability in the /api/v1/contenttype endpoint. This endpoint uses the sites query parameter, which accepts a comma-separated list of site identifiers or keys.

The vulnerability was triggered via the si…

### CVE-2025-8573
**concretecms concrete_cms cross-site scripting**
- **Signals:** EXP
- **Asset:** concretecms concrete_cms
- **Attack:** cross-site scripting
- **CVSS max:** 4.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-04T15:54:04.350
- **CWE:** CWE-20
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-09-16

> Concrete CMS versions 9 through 9.4.2 are vulnerable to Stored XSS from Home Folder on Members Dashboard page.  Version 8 was not affected. A rogue admin could set up a malicious folder containing XSS to which users could be directed upon login. The Concrete CMS security team gav…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-16*
