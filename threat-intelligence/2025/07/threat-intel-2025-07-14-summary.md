# Daily Threat Intelligence — July 14, 2025

**Digest window (UTC):** 2025-07-14
**Generated:** 2026-06-02T07:33:03Z

## Threat brief

Wing FTP Server added to CISA KEV — confirmed in-the-wild exploitation. · Trendmicro Password Manager — exploitation likelihood rose sharply (EPSS 13% → 43% · rising (+31%)). · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- Wing FTP Server added to CISA KEV — confirmed in-the-wild exploitation.
- Trendmicro Password Manager — exploitation likelihood rose sharply (EPSS 13% → 43% · rising (+31%)).
- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2025-47812
**Wing FTP Server Improper Neutralization of Null Byte or NUL Character Vulnerability**
- **Signals:** KEV
- **Asset:** wftpserver wing_ftp_server
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:26:31.650
- **CWE:** CWE-158
- **Risk score:** 88
- **KEV:** added 2025-07-14

> In Wing FTP Server before 7.4.4. the user and admin web interfaces mishandle '\0' bytes, ultimately allowing injection of arbitrary Lua code into user session files. This can be used to execute arbitrary system commands with the privileges of the FTP service (root or SYSTEM by de…

### CVE-2016-3987
**trendmicro password_manager**
- **Signals:** EPSS
- **Asset:** trendmicro password_manager
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-284
- **Risk score:** 86
- **EPSS 12.6% (2025-03-30) → 43.1% (2025-07-14), Δ +30.6%**

> The HTTP server in Trend Micro Password Manager allows remote web servers to execute arbitrary commands via the url parameter to (1) api/openUrlInDefaultBrowser or (2) api/showSB.

### CVE-2025-53823
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2025-07-15T20:15:50.333
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-14)

> WeGIA is an open source web manager with a focus on the Portuguese language and charitable institutions. Versions prior to 3.4.5 have a SQL Injection vulnerability in the endpoint `/WeGIA/html/socio/sistema/processa_deletar_socio.php`, in the `id_socio` parameter. This vulnerabil…

### CVE-2009-4000
**hp power_manager Directory Traversal**
- **Signals:** EPSS
- **Asset:** hp power_manager
- **Attack:** Directory Traversal
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-22
- **Risk score:** 85
- **EPSS 20.1% (2025-06-13) → 31.6% (2025-07-14), Δ +11.4%**

> Directory traversal vulnerability in goform/formExportDataLogs in HP Power Manager before 4.2.10 allows remote attackers to overwrite arbitrary files, and execute arbitrary code, via directory traversal sequences in the fileName parameter.

### CVE-2011-3165
**hp openview_network_node_manager**
- **Signals:** EPSS
- **Asset:** hp openview_network_node_manager
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **Risk score:** 86
- **EPSS 21.3% (2025-07-03) → 42.8% (2025-07-14), Δ +21.5%**

> Unspecified vulnerability in HP OpenView Network Node Manager (OV NNM) 7.51 and 7.53 allows remote attackers to execute arbitrary code via unknown vectors, aka ZDI-CAN-1208.

### CVE-2011-3166
**hp openview_network_node_manager**
- **Signals:** EPSS
- **Asset:** hp openview_network_node_manager
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **Risk score:** 86
- **EPSS 21.3% (2025-07-03) → 42.8% (2025-07-14), Δ +21.5%**

> Unspecified vulnerability in HP OpenView Network Node Manager (OV NNM) 7.51 and 7.53 allows remote attackers to execute arbitrary code via unknown vectors, aka ZDI-CAN-1209.

### CVE-2025-50756
**wavlink wn535k3_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** wavlink wn535k3_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-03T00:43:04.920
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-14)

> Wavlink WN535K3 20191010 was found to contain a command injection vulnerability in the set_sys_adm function via the newpass parameter. This vulnerability allows attackers to execute arbitrary commands via a crafted request.

### CVE-2025-53825
**dokploy dokploy RCE**
- **Signals:** CVSS
- **Asset:** dokploy dokploy
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-11T20:46:59.363
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-14)

> Dokploy is a free, self-hostable Platform as a Service (PaaS). Prior to version 0.24.3, an unauthenticated preview deployment vulnerability in Dokploy allows any user to execute arbitrary code and access sensitive environment variables by simply opening a pull request on a public…

### CVE-2025-53833
**LaRecipe is an application that allows users to create documentation with Markdown inside a Laravel app.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1336
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-14)

> LaRecipe is an application that allows users to create documentation with Markdown inside a Laravel app. Versions prior to 2.8.1 are vulnerable to Server-Side Template Injection (SSTI), which could potentially lead to Remote Code Execution (RCE) in vulnerable configurations. Atta…

### CVE-2025-53835
**xwiki xwiki cross-site scripting**
- **Signals:** CVSS
- **Asset:** xwiki xwiki
- **Attack:** cross-site scripting
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-26T17:52:40.370
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-07-14)

> XWiki Rendering is a generic rendering system that converts textual input in a given syntax (wiki syntax, HTML, etc) into another syntax (XHTML, etc). Starting in version 5.4.5 and prior to version 14.10, the XHTML syntax depended on the `xdom+xml/current` syntax which allows the…

### CVE-2025-7451
**The iSherlock developed by Hgiga has an OS Command Injection vulnerability, allowing unauthenticated remote attackers to inject arbitrary...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-14)

> The iSherlock developed by Hgiga has an OS Command Injection vulnerability, allowing unauthenticated remote attackers to inject arbitrary OS commands and execute them on the server. This vulnerability has already been exploited. Please update immediately.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-14*
