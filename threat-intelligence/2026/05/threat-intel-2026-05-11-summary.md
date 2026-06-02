# Daily Threat Intelligence — May 11, 2026

**Digest window (UTC):** 2026-05-11
**Generated:** 2026-06-02T07:03:59Z

## Threat brief

Exploitation likelihood rose sharply (EPSS 44% → 64% · rising (+20%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Exploitation likelihood rose sharply (EPSS 44% → 64% · rising (+20%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **20** |


## CVEs

### CVE-2025-34113
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 44.4% (2026-03-31) → 64.4% (2026-05-11), Δ +20.0%**

> An authenticated command injection vulnerability exists in Tiki Wiki CMS versions ≤14.1, ≤12.4 LTS, ≤9.10 LTS, and ≤6.14 via the `viewmode` GET parameter in `tiki-calendar.php`. When the calendar module is enabled and an authenticated user has permission to access it, an attacker…

### CVE-2025-34112
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 86
- **EPSS 49.7% (2026-03-31) → 68.6% (2026-05-11), Δ +18.9%**

> An authenticated multi-stage remote code execution vulnerability exists in Riverbed SteelCentral NetProfiler and NetExpress 10.8.7 virtual appliances. A SQL injection vulnerability in the '/api/common/1.0/login' endpoint can be exploited to create a new user account in the applia…

### CVE-2026-42869
**SOCFortress CoPilot focuses on providing a single pane of glass for all your security operations needs.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T18:31:17.630
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-11)

> SOCFortress CoPilot focuses on providing a single pane of glass for all your security operations needs. Prior to 0.1.57, SOCFortress CoPilot ships a hardcoded JWT signing secret as a fallback value in backend/app/auth/utils.py:28 and ships it verbatim in .env.example. Any deploym…

### CVE-2005-3390
**php php**
- **Signals:** EPSS
- **Asset:** php php
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 50.4% (2026-03-02) → 65.2% (2026-05-11), Δ +14.8%**

> The RFC1867 file upload feature in PHP 4.x up to 4.4.0 and 5.x up to 5.0.5, when register_globals is enabled, allows remote attackers to modify the GLOBALS array and bypass security protections of PHP applications via a multipart/form-data POST request with a "GLOBALS" fileupload…

### CVE-2006-7222
**guliverkli media_player_classic Buffer Overflow**
- **Signals:** EPSS
- **Asset:** guliverkli media_player_classic
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 81
- **EPSS 5.3% (2026-04-16) → 22.9% (2026-05-11), Δ +17.6%**

> Buffer overflow in the CFLICStream::_deltachunk function in FLICSource.cpp in Media Player Classic (MPC) 6.4.9.0 allows user-assisted remote attackers to execute arbitrary code via a crafted FLI file.

### CVE-2019-3963
**open-emr openemr cross-site scripting**
- **Signals:** EPSS
- **Asset:** open-emr openemr
- **Attack:** cross-site scripting
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:42:57.950
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 21.5% (2025-11-21) → 35.2% (2026-05-11), Δ +13.6%**

> In OpenEMR 5.0.1 and earlier, controller.php contains a reflected XSS vulnerability in the patient_id parameter. This could allow an attacker to execute arbitrary code in the context of a user's session.

### CVE-2025-34103
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 56.2% (2026-03-31) → 72.6% (2026-05-11), Δ +16.4%**

> An unauthenticated command injection vulnerability exists in WePresent WiPG-1000 firmware versions prior to 2.2.3.0, due to improper input handling in the undocumented /cgi-bin/rdfs.cgi endpoint. The Client parameter is not sanitized before being passed to a system call, allowing…

### CVE-2025-34104
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 85
- **EPSS 56.6% (2026-03-31) → 73.6% (2026-05-11), Δ +16.9%**

> An authenticated remote code execution vulnerability exists in Piwik (now Matomo) versions prior to 3.0.3 via the plugin upload mechanism. In vulnerable versions, an authenticated user with Superuser privileges can upload and activate a malicious plugin (ZIP archive), leading to …

### CVE-2025-34107
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 84
- **EPSS 56.7% (2026-03-31) → 73.6% (2026-05-11), Δ +16.9%**

> A buffer overflow vulnerability exists in the WinaXe FTP Client version 7.7 within the FTP banner parsing functionality, WCMDPA10.dll. When the client connects to a remote FTP server and receives an overly long '220 Server Ready' response, the vulnerable component responsible for…

### CVE-2025-34115
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 52.6% (2026-03-31) → 70.7% (2026-05-11), Δ +18.1%**

> An authenticated command injection vulnerability exists in OP5 Monitor through version 7.1.9 via the 'cmd_str' parameter in the command_test.php endpoint. A user with access to the web interface can exploit the 'Test this command' feature to execute arbitrary shell commands as th…

### CVE-2025-34116
**privilege escalation · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** privilege escalation
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 60.7% (2026-03-31) → 76.2% (2026-05-11), Δ +15.5%**

> A remote command execution vulnerability exists in IPFire before version 2.19 Core Update 101 via the 'proxy.cgi' CGI interface. An authenticated attacker can inject arbitrary shell commands through crafted values in the NCSA user creation form fields, leading to command executio…

### CVE-2026-38567
**HireFlow v1.2 is vulnerable to SQL injection in the /login and /search endpoints.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T15:06:07.407
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-11)

> HireFlow v1.2 is vulnerable to SQL injection in the /login and /search endpoints. User-supplied input is concatenated directly into SQL queries without parameterization. An unauthenticated attacker can bypass authentication by supplying a crafted username (e.g. admin'--) or extra…

### CVE-2026-42607
**Grav is a file-based Web platform.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T14:51:21.830
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-11)

> Grav is a file-based Web platform. Prior to 2.0.0-beta.2, an authenticated user with administrative privileges can achieve Remote Code Execution (RCE) by uploading a specially crafted ZIP file through the "Direct Install" tool. While the system attempts to block direct .php file …

### CVE-2026-42613
**Grav is a file-based Web platform.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T14:51:21.830
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-11)

> Grav is a file-based Web platform. Prior to 2.0.0-beta.2, the Login::register() method in the Login plugin accepts attacker-controlled groups and access fields from the registration POST data without server-side validation. When registration is enabled and groups or access are in…

### CVE-2026-42864
**FireFighter is an incident management application.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T17:24:36.160
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-11)

> FireFighter is an incident management application. Prior to 0.0.54, the POST /api/v2/firefighter/raid/jira_bot endpoint (CreateJiraBotView) is reachable without authentication (permission_classes = [permissions.AllowAny]). Its attachments payload is fetched server-side via httpx.…

### CVE-2026-42882
**oxyno-zeta/s3-proxy is an aws s3 proxy written in go.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T18:31:17.630
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-11)

> oxyno-zeta/s3-proxy is an aws s3 proxy written in go. Prior to 5.0.0, s3-proxy contains an authentication bypass caused by inconsistent URL path interpretation between the authentication middleware and the bucket handler. The authentication middleware evaluates resource path patt…

### CVE-2026-43899
**DeepChat is an open-source artificial intelligence agent platform that unifies models, tools, and agents.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T14:50:18.527
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-11)

> DeepChat is an open-source artificial intelligence agent platform that unifies models, tools, and agents. Prior to v1.0.4-beta.1, An incomplete mitigation for CVE-2025-55733 leaves DeepChat vulnerable to an arbitrary protocol execution bypass (RCE). While the patch correctly rest…

### CVE-2026-43900
**DeepChat is an open-source artificial intelligence agent platform that unifies models, tools, and agents.**
- **Signals:** CVSS
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T14:50:18.527
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-11)

> DeepChat is an open-source artificial intelligence agent platform that unifies models, tools, and agents. Prior to v1.0.4-beta.1, a Cross-Site Scripting (XSS) vulnerability exists due to a discrepancy between the backend validation layer and the frontend browser rendering engine.…

### CVE-2026-44643
**peerigon angular-expressions**
- **Signals:** CVSS
- **Asset:** peerigon angular-expressions
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-13T14:54:54.340
- **CWE:** CWE-95
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-11)

> Angular Expressions provides expressions for the Angular.JS web framework as a standalone module. Prior to 1.5.2, an attacker can write a malicious expression using filters that escapes the sandbox to execute arbitrary code on the system. This vulnerability is fixed in 1.5.2.

### CVE-2026-7813
**pgadmin pgadmin_4 privilege escalation**
- **Signals:** CVSS
- **Asset:** pgadmin pgadmin_4
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-26T13:50:13.823
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-11)

> Authorization vulnerability in pgAdmin 4 server mode affecting Server Groups, Servers, Shared Servers, Background Processes, and Debugger modules.

Multiple endpoints fetched user-owned objects without filtering by the requesting user's identity. An authenticated user could acces…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-11*
