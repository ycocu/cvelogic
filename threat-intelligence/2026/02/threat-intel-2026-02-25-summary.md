# Daily Threat Intelligence — February 25, 2026

**Digest window (UTC):** 2026-02-25
**Generated:** 2026-06-02T07:34:30Z

## Threat brief

Cisco Catalyst SD-WAN Controller And Manager: 2 CVEs added to CISA KEV today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cisco Catalyst SD-WAN Controller And Manager: 2 CVEs added to CISA KEV today.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2022-20775
**Cisco SD-WAN Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** cisco catalyst_sd-wan_manager
- **Attack:** Path Traversal
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T16:20:09.420
- **CWE:** CWE-25
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2026-02-25

> A vulnerability in the CLI of Cisco SD-WAN Software could allow an authenticated, local attacker to gain elevated privileges.

This vulnerability is due to improper access controls on commands within the application CLI. An attacker could exploit this vulnerability by running a…

### CVE-2026-27613
**ritlabs tinyweb RCE**
- **Signals:** CVSS
- **Asset:** ritlabs tinyweb
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T03:21:58.263
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-25)

> TinyWeb is a web server (HTTP, HTTPS) written in Delphi for Win32. A vulnerability in versions prior to 2.01 allows unauthenticated remote attackers to bypass the web server's CGI parameter security controls. Depending on the server configuration and the specific CGI executable i…

### CVE-2026-24908
**open-emr openemr SQL Injection**
- **Signals:** CVSS
- **Asset:** open-emr openemr
- **Attack:** SQL Injection
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T14:42:29.287
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-02-25)

> OpenEMR is a free and open source electronic health records and medical practice management application. Prior to version 8.0.0, an SQL injection vulnerability in the Patient REST API endpoint allows authenticated users with API access to execute arbitrary SQL queries through the…

### CVE-2026-0542
**ServiceNow has addressed a remote code execution vulnerability that was identified in the ServiceNow AI platform.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-653
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-25)

> ServiceNow has addressed a remote code execution vulnerability that was identified in the ServiceNow AI platform.  This vulnerability could enable an unauthenticated user, in certain circumstances, to execute code within the ServiceNow Sandbox.   





ServiceNow addressed this v…

### CVE-2026-20127
**Cisco Catalyst SD-WAN Controller and Manager Authentication Bypass Vulnerability**
- **Signals:** KEV
- **Asset:** cisco catalyst_sd-wan_manager
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T16:20:02.187
- **CWE:** CWE-287
- **CWE:** CWE-287
- **Risk score:** 88
- **KEV:** added 2026-02-25

> A vulnerability in the peering authentication in Cisco Catalyst SD-WAN Controller, formerly SD-WAN vSmart, and Cisco Catalyst SD-WAN Manager, formerly SD-WAN vManage, could allow an unauthenticated, remote attacker to bypass authentication and obtain administrative privileges on …

### CVE-2026-27493
**n8n n8n RCE**
- **Signals:** CVSS
- **Asset:** n8n n8n
- **Attack:** RCE
- **CVSS max:** 9.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-05T16:29:28.867
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-02-25)

> n8n is an open source workflow automation platform. Prior to versions 2.10.1, 2.9.3, and 1.123.22, a second-order expression injection vulnerability existed in n8n's Form nodes that could allow an unauthenticated attacker to inject and evaluate arbitrary n8n expressions by submit…

### CVE-2026-27495
**n8n n8n**
- **Signals:** CVSS
- **Asset:** n8n n8n
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T03:41:31.603
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-25)

> n8n is an open source workflow automation platform. Prior to versions 2.10.1, 2.9.3, and 1.123.22, an authenticated user with permission to create or modify workflows could exploit a vulnerability in the JavaScript Task Runner sandbox to execute arbitrary code outside the sandbox…

### CVE-2026-27497
**n8n n8n SQL injection**
- **Signals:** CVSS
- **Asset:** n8n n8n
- **Attack:** SQL injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T03:35:58.510
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-25)

> n8n is an open source workflow automation platform. Prior to versions 2.10.1, 2.9.3, and 1.123.22, an authenticated user with permission to create or modify workflows could leverage the Merge node's SQL query mode to execute arbitrary code and write arbitrary files on the n8n ser…

### CVE-2026-27498
**n8n n8n RCE**
- **Signals:** CVSS
- **Asset:** n8n n8n
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T03:33:32.357
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-02-25)

> n8n is an open source workflow automation platform. Prior to versions 2.2.0 and 1.123.8, an authenticated user with permission to create or modify workflows could chain the Read/Write Files from Disk node with git operations to achieve remote code execution. By writing to specifi…

### CVE-2026-27575
**vikunja vikunja**
- **Signals:** CVSS
- **Asset:** vikunja vikunja
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-05T17:21:37.413
- **CWE:** CWE-521
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-25)

> Vikunja is an open-source self-hosted task management platform. Prior to version 2.0.0, the application allows users to set weak passwords (e.g., 1234, password) without enforcing minimum strength requirements. Additionally, active sessions remain valid after a user changes their…

### CVE-2026-27577
**n8n n8n**
- **Signals:** CVSS
- **Asset:** n8n n8n
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T14:00:14.260
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-25)

> n8n is an open source workflow automation platform. Prior to versions 2.10.1, 2.9.3, and 1.123.22, additional exploits in the expression evaluation of n8n have been identified and patched following CVE-2025-68613. An authenticated user with permission to create or modify workflow…

### CVE-2026-27739
**The Angular SSR is a server-rise rendering tool for Angular applications.**
- **Signals:** CVSS
- **Attack:** SSRF
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-25)

> The Angular SSR is a server-rise rendering tool for Angular applications. Versions prior to 21.2.0-rc.1, 21.1.5, 20.3.17, and 19.2.21 have a Server-Side Request Forgery (SSRF) vulnerability in the Angular SSR request handling pipeline. The vulnerability exists because Angular’s i…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-25*
