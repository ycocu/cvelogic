# Daily Threat Intelligence — April 08, 2026

**Digest window (UTC):** 2026-04-08
**Generated:** 2026-06-02T07:34:52Z

## Threat brief

Ivanti Endpoint Manager Mobile (EPMM) added to CISA KEV — confirmed in-the-wild exploitation. · 7-zip: public exploit or PoC linked (RCE) · Microsoft Windows 10 — exploitation likelihood rose sharply (EPSS 63% → 76% · rising (+13%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Ivanti Endpoint Manager Mobile (EPMM) added to CISA KEV — confirmed in-the-wild exploitation.
- 7-zip: public exploit or PoC linked (RCE)
- Microsoft Windows 10 — exploitation likelihood rose sharply (EPSS 63% → 76% · rising (+13%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 6 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **19** |


## CVEs

### CVE-2026-1340
**Ivanti Endpoint Manager Mobile (EPMM) Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** ivanti endpoint_manager_mobile
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-09T14:03:31.767
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2026-04-08

> A code injection in Ivanti Endpoint Manager Mobile allowing attackers to achieve unauthenticated remote code execution.

### CVE-2023-33177
**xibosignage xibo Path Traversal**
- **Signals:** EXP
- **Asset:** xibosignage xibo
- **Attack:** Path Traversal
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:05:03.337
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2026-04-08

> Xibo is a content management system (CMS). A path traversal vulnerability exists in the Xibo CMS whereby a specially crafted zip file can be uploaded to the CMS via the layout import function by an authenticated user which would allow creation of files outside of the CMS library …

### CVE-2021-1678
**microsoft windows_10**
- **Signals:** EPSS
- **Asset:** microsoft windows_10
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:44:52.620
- **Risk score:** 84
- **EPSS 63.4% (2025-12-28) → 76.0% (2026-04-08), Δ +12.5%**

> Windows Print Spooler Spoofing Vulnerability

### CVE-2013-0984
**apple mac_os_x DoS**
- **Signals:** EPSS
- **Asset:** apple mac_os_x
- **Attack:** DoS
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 15.8% (2026-03-25) → 26.1% (2026-04-08), Δ +10.4%**

> Directory Service in Apple Mac OS X through 10.6.8 allows remote attackers to execute arbitrary code or cause a denial of service (daemon crash) via a crafted message.

### CVE-2025-11001
**7-zip 7-zip RCE**
- **Signals:** EXP
- **Asset:** 7-zip 7-zip
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-24T15:07:32.807
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2026-04-08

> 7-Zip ZIP File Parsing Directory Traversal Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of 7-Zip. Interaction with this product is required to exploit this vulnerability but attack vectors may …

### CVE-2025-26633
**Microsoft Windows Management Console (MMC) Improper Neutralization Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 7.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:13:29.327
- **CWE:** CWE-707
- **Risk score:** 78
- **EXP:** ref published 2026-04-08

> Improper neutralization in Microsoft Management Console allows an unauthorized attacker to bypass a security feature locally.

### CVE-2025-48868
**horilla horilla RCE**
- **Signals:** EXP
- **Asset:** horilla horilla
- **Attack:** RCE
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-29T14:06:57.020
- **CWE:** CWE-95
- **Risk score:** 78
- **EXP:** ref published 2026-04-08

> Horilla is a free and open source Human Resource Management System (HRMS). An authenticated Remote Code Execution (RCE) vulnerability exists in Horilla 1.3.0 due to the unsafe use of Python’s eval() function on a user-controlled query parameter in the project_bulk_archive view. T…

### CVE-2025-52221
**tenda ac6_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** tenda ac6_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-13T11:36:50.943
- **CWE:** CWE-787
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-08)

> Tenda AC6 15.03.05.16_multi is vulnerable to Buffer Overflow in the formSetCfm function via the funcname, funcpara1, and funcpara2 parameters.

### CVE-2025-64446
**Fortinet FortiWeb Path Traversal Vulnerability**
- **Signals:** EXP
- **Asset:** fortinet fortiweb
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-21T18:27:33.730
- **CWE:** CWE-23
- **Risk score:** 78
- **EXP:** ref published 2026-04-08

> A relative path traversal vulnerability in Fortinet FortiWeb 8.0.0 through 8.0.1, FortiWeb 7.6.0 through 7.6.4, FortiWeb 7.4.0 through 7.4.9, FortiWeb 7.2.0 through 7.2.11, FortiWeb 7.0.0 through 7.0.11 may allow an attacker to execute administrative commands on the system via cr…

### CVE-2025-6965
**sqlite sqlite Memory Corruption**
- **Signals:** EXP
- **Asset:** sqlite sqlite
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-14T10:16:29.853
- **CWE:** CWE-197
- **Risk score:** 78
- **EXP:** ref published 2026-04-08

> There exists a vulnerability in SQLite versions before 3.50.2 where the number of aggregate terms could exceed the number of columns available. This could lead to a memory corruption issue. We recommend upgrading to version 3.50.2 or above.

### CVE-2026-2942
**The ProSolution WP Client plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'proSol...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T18:05:09.240
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-08)

> The ProSolution WP Client plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'proSol_fileUploadProcess' function in all versions up to, and including, 1.9.9. This makes it possible for unauthenticated attackers to upload arbitr…

### CVE-2026-31017
**frappe erpnext SSRF**
- **Signals:** CVSS
- **Asset:** frappe erpnext
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T15:46:59.460
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-08)

> A Server-Side Request Forgery (SSRF) vulnerability exists in the Print Format functionality of ERPNext v16.0.1 and Frappe Framework v16.1.1, where user-supplied HTML is insufficiently sanitized before being rendered into PDF. When generating PDFs from user-controlled HTML content…

### CVE-2026-3199
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-13T15:02:47.353
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-08)

> A vulnerability in the task management component of Sonatype Nexus Repository versions 3.22.1 through 3.90.2 allows an authenticated attacker with task creation permissions to execute arbitrary code, bypassing the nexus.scripts.allowCreation security control.

### CVE-2026-39860
**nixos nix**
- **Signals:** CVSS
- **Asset:** nixos nix
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-15T16:12:21.480
- **CWE:** CWE-61
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-04-08)

> Nix is a package manager for Linux and other Unix systems. A bug in the fix for CVE-2024-27297 allowed for arbitrary overwrites of files writable by the Nix process orchestrating the builds (typically the Nix daemon running as root in multi-user installations) by following symlin…

### CVE-2026-39888
**praison praisonai**
- **Signals:** CVSS
- **Asset:** praison praisonai
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-15T18:02:58.940
- **CWE:** CWE-657
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-08)

> PraisonAI is a multi-agent teams system. Prior to 1.5.115, execute_code() in praisonaiagents.tools.python_tools defaults to sandbox_mode="sandbox", which runs user code in a subprocess wrapped with a restricted __builtins__ dict and an AST-based blocklist. The AST blocklist embed…

### CVE-2026-39890
**praison praisonai**
- **Signals:** CVSS
- **Asset:** praison praisonai
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-15T17:56:13.590
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-08)

> PraisonAI is a multi-agent teams system. Prior to 4.5.115, the AgentService.loadAgentFromFile method uses the js-yaml library to parse YAML files without disabling dangerous tags (such as !!js/function and !!js/undefined). This allows an attacker to craft a malicious YAML file th…

### CVE-2026-40035
**ryandfir unfurl RCE**
- **Signals:** CVSS
- **Asset:** ryandfir unfurl
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-17T16:03:26.810
- **CWE:** CWE-489
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-08)

> Unfurl through 2025.08 contains an improper input validation vulnerability in config parsing that enables Flask debug mode by default. The debug configuration value is read as a string and passed directly to app.run(), causing any non-empty string to evaluate truthy, allowing att…

### CVE-2026-5874
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-13T17:57:38.287
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-04-08)

> Use after free in PrivateAI in Google Chrome prior to 147.0.7727.55 allowed a remote attacker who convinced a user to engage in specific UI gestures to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: Medium)

### CVE-2026-5902
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-13T21:14:13.800
- **CWE:** CWE-362
- **CWE:** CWE-362
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-08)

> Race in Media in Google Chrome on Android prior to 147.0.7727.55 allowed a remote attacker who had compromised the renderer process to corrupt media stream metadata via a crafted HTML page. (Chromium security severity: Low)

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-08*
