# Daily Threat Intelligence — June 09, 2026

**Digest window (UTC):** 2026-06-09
**Generated:** 2026-06-12T11:04:14Z

## Threat brief

Google Chromium V8 added to CISA KEV — confirmed in-the-wild exploitation. · BerriAI LiteLLM — exploitation likelihood rose sharply (EPSS 4.1% → 61% · rising (+57%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Google Chromium V8 added to CISA KEV — confirmed in-the-wild exploitation.
- BerriAI LiteLLM — exploitation likelihood rose sharply (EPSS 4.1% → 61% · rising (+57%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 3 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **23** |


## CVEs

### CVE-2026-11645
**Google Chromium V8 Out-of-Bounds Read and Write Vulnerability**
- **Signals:** KEV
- **Asset:** google chrome
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-09T19:41:08.533
- **CWE:** CWE-125
- **Risk score:** 88
- **KEV:** added 2026-06-09

> Out of bounds read and write in V8 in Google Chrome prior to 149.0.7827.103 allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page. (Chromium security severity: High)

### CVE-2026-42271
**BerriAI LiteLLM Command Injection Vulnerability**
- **Signals:** EPSS
- **Asset:** litellm litellm
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-09T01:22:09.190
- **CWE:** CWE-77
- **Risk score:** 84
- **EPSS 4.1% (2026-06-03) → 60.8% (2026-06-09), Δ +56.7%**

> LiteLLM is a proxy server (AI Gateway) to call LLM APIs in OpenAI (or native) format. From version 1.74.2 to before version 1.83.7, two endpoints used to preview an MCP server before saving it — POST /mcp-rest/test/connection and POST /mcp-rest/test/tools/list — accepted a full s…

### CVE-2026-47938
**Adobe Campaign Classic (ACC) versions 7.4.3 build 9394 and earlier are affected by a Server-Side Request Forgery (SSRF) vulnerability tha...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 10.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-10T18:35:49.083
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-09)

> Adobe Campaign Classic (ACC) versions 7.4.3 build 9394 and earlier are affected by a Server-Side Request Forgery (SSRF) vulnerability that could result in privilege escalation. Exploitation of this issue does not require user interaction. Scope is changed.

### CVE-2011-10009
**Path Traversal · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Path Traversal
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 84
- **EPSS 48.4% (2026-01-10) → 68.6% (2026-06-09), Δ +20.2%**

> S40 CMS v0.4.2 contains a path traversal vulnerability in its index.php page handler. The p parameter is not properly sanitized, allowing attackers to traverse the file system and access arbitrary files outside the web root. This can be exploited remotely without authentication b…

### CVE-2011-10010
**Path Traversal · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 85
- **EPSS 57.9% (2026-04-29) → 74.4% (2026-06-09), Δ +16.5%**

> QuickShare File Server 1.2.1 contains a path traversal vulnerability in its FTP service due to improper sanitation of user-supplied file paths. Authenticated users can exploit this flaw by submitting crafted sequences to access or write files outside the intended virtual director…

### CVE-2011-10018
**mybb mybb**
- **Signals:** EPSS
- **Asset:** mybb mybb
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T17:42:18.333
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 53.0% (2026-01-10) → 68.1% (2026-06-09), Δ +15.1%**

> myBB version 1.6.4 was distributed with an unauthorized backdoor embedded in the source code. The backdoor allowed remote attackers to execute arbitrary PHP code by injecting payloads into a specially crafted collapsed cookie. This vulnerability was introduced during packaging an…

### CVE-2012-10056
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 84
- **EPSS 36.8% (2026-04-29) → 57.7% (2026-06-09), Δ +20.9%**

> PHP Volunteer Management System v1.0.2 contains an arbitrary file upload vulnerability in its document upload functionality. Authenticated users can upload files to the mods/documents/uploads/ directory without any restriction on file type or extension. Because this directory is …

### CVE-2012-10058
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 86
- **EPSS 58.6% (2026-04-29) → 74.9% (2026-06-09), Δ +16.2%**

> RabidHamster R4 v1.25 contains a stack-based buffer overflow vulnerability due to unsafe use of sprintf() when logging malformed HTTP requests. A remote attacker can exploit this flaw by sending a specially crafted URI, resulting in arbitrary code execution under the context of t…

### CVE-2012-10059
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 47.8% (2026-04-29) → 67.2% (2026-06-09), Δ +19.3%**

> Dolibarr ERP/CRM versions <= 3.1.1 and <= 3.2.0 contain a post-authenticated OS command injection vulnerability in its database backup feature. The export.php script fails to sanitize the sql_compat parameter, allowing authenticated users to inject arbitrary system commands, resu…

### CVE-2022-44727
**lineagrafica eu_cookie_law_gdpr SQL Injection**
- **Signals:** EPSS
- **Asset:** lineagrafica eu_cookie_law_gdpr
- **Attack:** SQL Injection
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2025-05-01T14:15:33.490
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 85
- **EPSS 0.5% (2025-11-11) → 20.7% (2026-06-09), Δ +20.2%**

> The EU Cookie Law GDPR (Banner + Blocker) module before 2.1.3 for PrestaShop allows SQL Injection via a cookie ( lgcookieslaw or __lglaw ).

### CVE-2023-0830
**easynas easynas Command Injection**
- **Signals:** EPSS
- **Asset:** easynas easynas
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2025-05-01T15:16:19.190
- **CWE:** CWE-77
- **CWE:** CWE-78
- **Risk score:** 79
- **EPSS 38.5% (2026-04-07) → 58.5% (2026-06-09), Δ +20.0%**

> A vulnerability classified as critical has been found in EasyNAS 1.1.0. Affected is the function system of the file /backup.pl. The manipulation leads to os command injection. It is possible to launch the attack remotely. The exploit has been disclosed to the public and may be us…

### CVE-2026-10045
**Shenzhen Kangda Xin Intelligent Network Technology Company's router, model DR300, version 2.1.2.121, contains hardcoded login credentials...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-09T20:16:31.767
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-09)

> Shenzhen Kangda Xin Intelligent Network Technology Company's router, model DR300, version 2.1.2.121, contains hardcoded login credentials and has telnet enabled by default on WAN and LAN interfaces. These vulnerabilities allow attackers to read and write to memory, modify firmwar…

### CVE-2026-20245
**Cisco Catalyst SD-WAN Manager Improper Encoding or Escaping of Output Vulnerability**
- **Signals:** KEV
- **Asset:** cisco catalyst_sd-wan_manager
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-10T12:59:09.600
- **CWE:** CWE-116
- **Risk score:** 88
- **KEV:** added 2026-06-09

> A vulnerability in the CLI of Cisco Catalyst SD-WAN Controller, formerly SD-WAN vSmart, Cisco Catalyst SD-WAN Manager, formerly SD-WAN vManage, and Cisco Catalyst SD-WAN Validator, formerly SD-WAN vBond, could allow an authenticated, local attacker to execute arbitrary commands a…

### CVE-2026-26190
**milvus milvus Auth Bypass**
- **Signals:** EPSS
- **Asset:** milvus milvus
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T19:11:12.333
- **CWE:** CWE-306
- **Risk score:** 86
- **EPSS 0.5% (2026-03-27) → 15.1% (2026-06-09), Δ +14.6%**

> Milvus is an open-source vector database built for generative AI applications. Prior to 2.5.27 and 2.6.10, Milvus exposes TCP port 9091 by default, which enables authentication bypasses. The /expr debug endpoint uses a weak, predictable default authentication token derived from e…

### CVE-2026-30141
**An issue was discovered in bitbank2 AnimatedGIF v2.2.0.**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-10T20:16:26.227
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-09)

> An issue was discovered in bitbank2 AnimatedGIF v2.2.0. A buffer overflow in the DecodeLZW function allows remote attackers to cause a denial of service (crash) or potentially execute arbitrary code via a crafted GIF file.

### CVE-2026-34691
**adobe experience_manager XSS**
- **Signals:** CVSS
- **Asset:** adobe experience_manager
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-11T17:29:49.867
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-09)

> Adobe Experience Manager Forms JEE versions LTS SP1, 6.5.24.0 and earlier are affected by a stored Cross-Site Scripting (XSS) vulnerability that could be abused by an attacker to inject malicious scripts into vulnerable form fields. Malicious JavaScript may be executed in a victi…

### CVE-2026-36721
**A lack of cryptographic signature verification in the validateAccessToken function of bookcars v8.3 allows attackers to bypass authentica...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-10T15:16:33.783
- **CWE:** CWE-347
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-09)

> A lack of cryptographic signature verification in the validateAccessToken function of bookcars v8.3 allows attackers to bypass authentication via a forged JWT token.

### CVE-2026-36727
**An insecure authentication vulnerability in the /api/social-sign-in endpoint of bookcars v8.3 allows attackers to bypass authentication v...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-06-10T19:16:34.510
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-09)

> An insecure authentication vulnerability in the /api/social-sign-in endpoint of bookcars v8.3 allows attackers to bypass authentication via a forged JWT token.

### CVE-2026-44963
**A vulnerability allowing remote code execution (RCE) on the Backup Server by an authenticated domain user.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-10T20:58:14.500
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-09)

> A vulnerability allowing remote code execution (RCE) on the Backup Server by an authenticated domain user.

### CVE-2026-47928
**ColdFusion versions 2023.19, 2025.8 and earlier are affected by an Improper Input Validation vulnerability that could result in arbitrary...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-06-10T18:35:49.083
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-09)

> ColdFusion versions 2023.19, 2025.8 and earlier are affected by an Improper Input Validation vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue does not require user interaction. Scope is changed.

### CVE-2026-48303
**Adobe Campaign Classic (ACC) versions 7.4.3 build 9394 and earlier are affected by an Incorrect Authorization vulnerability that could re...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-06-10T18:35:49.083
- **CWE:** CWE-863
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-09)

> Adobe Campaign Classic (ACC) versions 7.4.3 build 9394 and earlier are affected by an Incorrect Authorization vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue does not require user interaction. Scope is cha…

### CVE-2026-49841
**freeswitch freeswitch**
- **Signals:** CVSS
- **Asset:** freeswitch freeswitch
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-10T15:07:23.493
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-09)

> FreeSWITCH is a Software Defined Telecom Stack enabling the digital transformation from proprietary telecom switches to a software implementation that runs on any commodity hardware. Prior to version 1.11.1, the mod_verto HTTP request handler allocates a fixed 2 MiB buffer for a …

### CVE-2026-7473
**Arista Extensible Operating System Incomplete Comparison with Missing Factors Vulnerability**
- **Signals:** KEV
- **Asset:** arista eos
- **CVSS max:** 6.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-09T20:48:49.580
- **CWE:** CWE-1023
- **Risk score:** 88
- **KEV:** added 2026-06-09

> On affected platforms running Arista EOS where a tunnel decapsulation configuration—such as VXLAN (Virtual Extensible LAN), decap-groups, or a GRE (Generic Routing Encapsulation) tunnel interface—is present, the switch will incorrectly decapsulate and forward other unexpected tun…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-09*
