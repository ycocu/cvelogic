# Daily Threat Intelligence — May 13, 2026

**Digest window (UTC):** 2026-05-13
**Generated:** 2026-06-02T07:04:00Z

## Threat brief

Nicolargo Glances: public exploit or PoC linked · Sudo — exploitation likelihood rose sharply (EPSS 47% → 57% · rising (+10%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Nicolargo Glances: public exploit or PoC linked
- Sudo — exploitation likelihood rose sharply (EPSS 47% → 57% · rising (+10%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 4 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2025-58434
**flowiseai flowise**
- **Signals:** EXP
- **Asset:** flowiseai flowise
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-20T02:54:59.667
- **CWE:** CWE-306
- **Risk score:** 78
- **EXP:** ref published 2026-05-13

> Flowise is a drag & drop user interface to build a customized large language model flow. In version 3.0.5 and earlier, the `forgot-password` endpoint in Flowise returns sensitive information including a valid password reset `tempToken` without authentication or verification. This…

### CVE-2026-21876
**owasp owasp_modsecurity_core_rule_set**
- **Signals:** EXP
- **Asset:** owasp owasp_modsecurity_core_rule_set
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-09T16:16:26.437
- **CWE:** CWE-794
- **Risk score:** 78
- **EXP:** ref published 2026-05-13

> The OWASP core rule set (CRS) is a set of generic attack detection rules for use with compatible web application firewalls. Prior to versions 4.22.0 and 3.3.8, the current rule 922110 has a bug when processing multipart requests with multiple parts. When the first rule in a chain…

### CVE-2025-32463
**Sudo Inclusion of Functionality from Untrusted Control Sphere Vulnerability**
- **Signals:** EPSS
- **Asset:** sudo_project sudo
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:26:48.393
- **CWE:** CWE-829
- **Risk score:** 82
- **EPSS 47.0% (2026-05-08) → 57.3% (2026-05-13), Δ +10.4%**

> Sudo before 1.9.17p1 allows local users to obtain root access because /etc/nsswitch.conf from a user-controlled directory is used with the --chroot option.

### CVE-2025-27851
**The locally served web site on the Garmin WDU (v1 1.4.6 and v2 5.0) allows a cross-site origin WebSocket hijacking attack.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-14T17:06:08.693
- **CWE:** CWE-352
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-13)

> The locally served web site on the Garmin WDU (v1 1.4.6 and v2 5.0) allows a cross-site origin WebSocket hijacking attack. Among other uses, the WDU utilizes WebSockets to control settings, including administrative settings. This allows a network attacker to take full control of …

### CVE-2026-0740
**The Ninja Forms - File Uploads plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'N...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-27T19:04:22.650
- **CWE:** CWE-434
- **Risk score:** 78
- **EXP:** ref published 2026-05-13

> The Ninja Forms - File Uploads plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'NF_FU_AJAX_Controllers_Uploads::handle_upload' function in all versions up to, and including, 3.3.26. This makes it possible for unauthenticated…

### CVE-2026-33641
**nicolargo glances**
- **Signals:** EXP
- **Asset:** nicolargo glances
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-07T14:59:46.823
- **CWE:** CWE-78
- **Risk score:** 78
- **EXP:** ref published 2026-05-13

> Glances is an open-source system cross-platform monitoring tool. Prior to version 4.5.3, Glances supports dynamic configuration values in which substrings enclosed in backticks are executed as system commands during configuration parsing. This behavior occurs in Config.get_value(…

### CVE-2026-44193
**opnsense opnsense RCE**
- **Signals:** CVSS
- **Asset:** opnsense opnsense
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-15T17:30:03.117
- **CWE:** CWE-88
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-13)

> OPNsense is a FreeBSD based firewall and routing platform. Prior to 26.1.7, the XMLRPC method opnsense.restore_config_section fails to sanitize user supplied input leading to Remote Code Execution. This vulnerability is fixed in 26.1.7.

### CVE-2026-44194
**opnsense opnsense RCE**
- **Signals:** CVSS
- **Asset:** opnsense opnsense
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-15T17:19:46.990
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-13)

> OPNsense is a FreeBSD based firewall and routing platform. Prior to 26.1.8, an authenticated Remote Code Execution (RCE) vulnerability in the OPNsense core allows a user with user-management privileges to execute arbitrary system commands as root. An attacker can bypass input val…

### CVE-2026-44377
**CubeCart is an ecommerce software solution.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-14T16:49:18.583
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-13)

> CubeCart is an ecommerce software solution. Prior to 6.7.0, an Authenticated Server-Side Template Injection (SSTI) vulnerability exists in multiple modules of CubeCart (including Email Templates and Documents). The application unsafely evaluates user-supplied input directly throu…

### CVE-2026-44381
**misp misp SQL Injection**
- **Signals:** CVSS
- **Asset:** misp misp
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-15T17:37:06.157
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-13)

> MISP is an open source threat intelligence and sharing platform. Prior to 2.5.37, a SQL injection vulnerability existed in the handling of user-controlled ordering parameters in the event and shadow attribute listing endpoints. The affected code accepted order or sort values from…

### CVE-2026-44442
**frappe erpnext privilege escalation**
- **Signals:** CVSS
- **Asset:** frappe erpnext
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-14T20:04:02.837
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-13)

> ERPNext is a free and open source Enterprise Resource Planning tool. Prior to 16.9.1, certain endpoints failed to enforce proper authorization checks, allowing users to modify data beyond their permitted role. This vulnerability is fixed in 16.9.1.

### CVE-2026-45053
**CubeCart is an ecommerce software solution.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-15T20:16:48.470
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-13)

> CubeCart is an ecommerce software solution. Prior to 6.7.0, an Authenticated Arbitrary File Upload vulnerability exists in the REST API File Manager endpoint (POST /api/v1/files) of CubeCart. The endpoint allows any holder of an API key with files:rw permission to upload PHP sour…

### CVE-2026-45158
**opnsense opnsense RCE**
- **Signals:** CVSS
- **Asset:** opnsense opnsense
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-15T16:19:38.600
- **CWE:** CWE-88
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-13)

> OPNsense is a FreeBSD based firewall and routing platform. Prior to 26.1.8, unsanitized user input is passed to the DHCP configuration of the configured interface, which is processed by a shell script, allowing remote code execution as root on the underlying operating system. Thi…

### CVE-2026-45714
**CubeCart is an ecommerce software solution.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-14T16:49:18.583
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-13)

> CubeCart is an ecommerce software solution. Prior to 6.7.0, an Authenticated Server-Side Template Injection (SSTI) vulnerability exists in multiple modules of CubeCart (including Email Templates, Invoices, Documents, and Contact Forms). The application unsafely evaluates user-sup…

### CVE-2026-8500
**Web::Passwd versions through 0.03 for Perl is vulnerable to RCE.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-14T18:16:51.490
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-13)

> Web::Passwd versions through 0.03 for Perl is vulnerable to RCE.

Web::Passwd is a small CGI application for managing htpasswd files using the htpasswd command.

The user parameter is not validated or escaped, and is used as the last argument on the command line, allowing for com…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-13*
