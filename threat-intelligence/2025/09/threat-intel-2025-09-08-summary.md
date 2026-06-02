# Daily Threat Intelligence — September 08, 2025

**Digest window (UTC):** 2025-09-08
**Generated:** 2026-06-02T07:33:22Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Apple Cups — exploitation likelihood rose sharply (EPSS 17% → 28% · rising (+10%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Apple Cups — exploitation likelihood rose sharply (EPSS 17% → 28% · rising (+10%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2008-0053
**apple cups Buffer Overflow**
- **Signals:** EPSS
- **Asset:** apple cups
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 17.2% (2025-03-30) → 27.6% (2025-09-08), Δ +10.4%**

> Multiple buffer overflows in the HP-GL/2-to-PostScript filter in CUPS before 1.3.6 might allow remote attackers to execute arbitrary code via a crafted HP-GL/2 file.

### CVE-2025-58745
**wegia wegia**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-17T16:24:10.920
- **CWE:** CWE-94
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-09-08)

> WeGIA is a Web manager for charitable institutions. The fix for CVE-2025-22133 was not enough to remediate the arbitrary file upload vulnerability. The WeGIA only check MIME types for Excel files at endpoint `/html/socio/sistema/controller/controla_xlsx.php`, which can be bypasse…

### CVE-2025-57141
**ruisitech ruisibi RCE**
- **Signals:** CVSS
- **Asset:** ruisitech ruisibi
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T20:57:24.853
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-08)

> rsbi-os 4.7 is vulnerable to Remote Code Execution (RCE) in sqlite-jdbc.

### CVE-2025-54994
**@akoskm/create-mcp-server-stdio is an MCP server starter kit that uses the StdioServerTransport.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-08)

> @akoskm/create-mcp-server-stdio is an MCP server starter kit that uses the StdioServerTransport. Prior to version 0.0.13, the MCP Server is written in a way that is vulnerable to command injection vulnerability attacks as part of some of its MCP Server tool definition and impleme…

### CVE-2025-56266
**avigilon access_control_manager**
- **Signals:** CVSS
- **Asset:** avigilon access_control_manager
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T20:44:33.150
- **CWE:** CWE-74
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-08)

> A Host Header Injection vulnerability in Avigilon ACM v7.10.0.20 allows attackers to execute arbitrary code via supplying a crafted URL.

### CVE-2025-56267
**avigilon access_control_manager**
- **Signals:** CVSS
- **Asset:** avigilon access_control_manager
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T20:42:47.967
- **CWE:** CWE-1236
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-08)

> A CSV injection vulnerability in the /id_profiles endpoint of Avigilon ACM v7.10.0.20 allows attackers to execute arbitrary code via suuplying a crafted Excel file.

### CVE-2025-57285
**codecept codeceptjs Command Injection**
- **Signals:** CVSS
- **Asset:** codecept codeceptjs
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T20:37:59.793
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-08)

> codeceptjs 3.7.3 contains a command injection vulnerability in the emptyFolder function (lib/utils.js). The execSync command directly concatenates the user-controlled directoryPath parameter without sanitization or escaping, allowing attackers to execute arbitrary commands.

### CVE-2025-58450
**pREST (PostgreSQL REST), is an API that delivers an application on top of a Postgres database.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-08)

> pREST (PostgreSQL REST), is an API that delivers an application on top of a Postgres database. SQL injection is possible in versions prior to 2.0.0-rc3. The validation present in versions prior to 2.0.0-rc3 does not provide adequate protection from injection attempts. Version 2.0…

### CVE-2025-58746
**The Volkov Labs Business Links panel for Grafana provides an interface to navigate using external links, internal dashboards, time picker...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-09-08)

> The Volkov Labs Business Links panel for Grafana provides an interface to navigate using external links, internal dashboards, time pickers, and dropdown menus. Prior to version 2.4.0, a malicious actor with Editor privileges can escalate their privileges to Administrator and perf…

### CVE-2025-9113
**The Doccure Core plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'doccure_temp_up...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-08)

> The Doccure Core plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'doccure_temp_upload_to_media' function in all versions up to, and including, 1.5.3. This makes it possible for unauthenticated attackers to upload arbitrary f…

### CVE-2025-9114
**The Doccure theme for WordPress is vulnerable to Arbitrary User Password Change in versions up to, and including, 1.5.0.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-639
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-08)

> The Doccure theme for WordPress is vulnerable to Arbitrary User Password Change in versions up to, and including, 1.5.0. This is due to the plugin providing user-controlled access to objects, letting a user bypass authorization and access system resources. This makes it possible …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-08*
