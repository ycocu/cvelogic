# Daily Threat Intelligence — July 09, 2025

**Digest window (UTC):** 2025-07-09
**Generated:** 2026-06-02T07:33:01Z

## Threat brief

WordPress plugin RCE/exploit activity: 4 CVEs flagged today. · Microsoft Windows 95 — exploitation likelihood rose sharply (EPSS 37% → 49% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 4 CVEs flagged today.
- Microsoft Windows 95 — exploitation likelihood rose sharply (EPSS 37% → 49% · rising (+12%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-1999-1105
**microsoft windows_95**
- **Signals:** EPSS
- **Asset:** microsoft windows_95
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 36.7% (2025-03-30) → 48.7% (2025-07-09), Δ +12.0%**

> Windows 95, when Remote Administration and File Sharing for NetWare Networks is enabled, creates a share (C$) when an administrator logs in remotely, which allows remote attackers to read arbitrary files by mapping the network drive.

### CVE-2016-1558
**dlink dap-2230_firmware Buffer Overflow**
- **Signals:** EPSS
- **Asset:** dlink dap-3662_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 4.6% (2025-05-17) → 14.9% (2025-07-09), Δ +10.3%**

> Buffer overflow in D-Link DAP-2310 2.06 and earlier, DAP-2330 1.06 and earlier, DAP-2360 2.06 and earlier, DAP-2553 H/W ver. B1 3.05 and earlier, DAP-2660 1.11 and earlier, DAP-2690 3.15 and earlier, DAP-2695 1.16 and earlier, DAP-3320 1.00 and earlier, and DAP-3662 1.01 and earl…

### CVE-2025-34077
**An authentication bypass vulnerability exists in the WordPress Pie Register plugin ≤ 3.7.1.4 that allows unauthenticated attackers to imp...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-09)

> An authentication bypass vulnerability exists in the WordPress Pie Register plugin ≤ 3.7.1.4 that allows unauthenticated attackers to impersonate arbitrary users by submitting a crafted POST request to the login endpoint. By setting social_site=true and manipulating the user_id_s…

### CVE-2025-3498
**An unauthenticated user with management network access can get and modify the Radiflow iSAP Smart Collector (CentOS 7 - VSAP 1.20) config...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-07-09)

> An unauthenticated user with management network access can get and 
modify the Radiflow iSAP Smart Collector (CentOS 7 - VSAP 1.20) 
configuration. The device has two web servers that expose unauthenticated REST APIs on the management network (TCP
ports 8084 and 8086). An attacke…

### CVE-2025-3499
**The device has two web servers that expose unauthenticated REST APIs on the management network (TCP ports 8084 and 8086).**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-09)

> The device has two web servers that expose unauthenticated REST APIs on the management network (TCP
ports 8084 and 8086). Exploiting OS command injection through these APIs, an attacker can send arbitrary
commands that are executed with administrative permissions by the underlyin…

### CVE-2025-4606
**The Sala - Startup & SaaS WordPress Theme theme for WordPress is vulnerable to privilege escalation via account takeover in all versions...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-620
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-09)

> The Sala - Startup & SaaS WordPress Theme theme for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 1.1.4. This is due to the theme not properly validating a user's identity prior to updating their details like password. …

### CVE-2025-4828
**schiocco support_board RCE**
- **Signals:** CVSS
- **Asset:** schiocco support_board
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-14T15:14:26.103
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-09)

> The Support Board plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the sb_file_delete function in all versions up to, and including, 3.8.0. This makes it possible for attackers to delete arbitrary files on the server, which…

### CVE-2025-4855
**schiocco support_board privilege escalation**
- **Signals:** CVSS
- **Asset:** schiocco support_board
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-14T15:10:54.030
- **CWE:** CWE-639
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-09)

> The Support Board plugin for WordPress is vulnerable to unauthorized access/modification/deletion of data due to use of hardcoded default secrets in the sb_encryption() function in all versions up to, and including, 3.8.0. This makes it possible for unauthenticated attackers to b…

### CVE-2025-53546
**Folo organizes feeds content into one timeline.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-829
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-09)

> Folo organizes feeds content into one timeline. Using pull_request_target on .github/workflows/auto-fix-lint-format-commit.yml can be exploited by attackers, since untrusted code can be executed having full access to secrets (from the base repo). By exploiting the vulnerability i…

### CVE-2025-53620
**@builder.io/qwik-city is the meta-framework for Qwik.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-248
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-07-09)

> @builder.io/qwik-city is the meta-framework for Qwik. When a Qwik Server Action QRL is executed it dynamically load the file containing the symbol. When an invalid qfunc is sent, the server does not handle the thrown error. The error then causes Node JS to exit. This vulnerabilit…

### CVE-2025-53624
**The Docusaurus gists plugin adds a page to your Docusaurus instance, displaying all public gists of a GitHub user.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-09)

> The Docusaurus gists plugin adds a page to your Docusaurus instance, displaying all public gists of a GitHub user. docusaurus-plugin-content-gists versions prior to 4.0.0 are vulnerable to exposing GitHub Personal Access Tokens in production build artifacts when passed through pl…

### CVE-2025-6514
**mcp-remote is exposed to OS command injection when connecting to untrusted MCP servers due to crafted input from the authorization_endpoi...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-07-09)

> mcp-remote is exposed to OS command injection when connecting to untrusted MCP servers due to crafted input from the authorization_endpoint response URL

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-09*
