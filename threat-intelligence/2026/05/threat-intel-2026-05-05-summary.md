# Daily Threat Intelligence — May 05, 2026

**Digest window (UTC):** 2026-05-05
**Generated:** 2026-06-02T07:03:56Z

## Threat brief

Netgear Prosafe Network Management System — exploitation likelihood rose sharply (EPSS 14% → 69% · rising (+55%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Netgear Prosafe Network Management System — exploitation likelihood rose sharply (EPSS 14% → 69% · rising (+55%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2021-27272
**netgear prosafe_network_management_system**
- **Signals:** EPSS
- **Asset:** netgear prosafe_network_management_system
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:57:44.233
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 14.2% (2026-03-31) → 69.0% (2026-05-05), Δ +54.8%**

> This vulnerability allows remote attackers to delete arbitrary files on affected installations of NETGEAR ProSAFE Network Management System 1.6.0.26. Although authentication is required to exploit this vulnerability, the existing authentication mechanism can be bypassed. The spec…

### CVE-2025-4322
**Privilege Escalation · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-620
- **Risk score:** 86
- **EPSS 31.1% (2026-03-16) → 43.9% (2026-05-05), Δ +12.7%**

> The Motors theme for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 5.6.67. This is due to the theme not properly validating a user's identity prior to updating their password. This makes it possible for unauthenticated …

### CVE-2026-27960
**citeum opencti Privilege Escalation**
- **Signals:** CVSS
- **Asset:** citeum opencti
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-12T13:45:07.770
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-05)

> OpenCTI is an open source platform for managing cyber threat intelligence knowledge and observables. In versions 6.6.0 through 6.9.12, there is a privilege escalation vulnerability that can be exploited by unauthenticated attackers to query the API as any existing user, including…

### CVE-2023-30628
**kiwitcms kiwi_tcms Command Injection**
- **Signals:** EPSS
- **Asset:** kiwitcms kiwi_tcms
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:00:32.690
- **CWE:** CWE-78
- **Risk score:** 81
- **EPSS 2.7% (2026-04-26) → 12.9% (2026-05-05), Δ +10.2%**

> Kiwi TCMS is an open source test management system. In kiwitcms/Kiwi v12.2 and prior and kiwitcms/enterprise v12.2 and prior,
the `changelog.yml` workflow is vulnerable to command injection attacks because of using an untrusted `github.head_ref` field. The `github.head_ref` value…

### CVE-2026-28780
**apache http_server Buffer Overflow**
- **Signals:** CVSS
- **Asset:** apache http_server
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-06T20:31:10.843
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-05)

> Heap-based Buffer Overflow vulnerability in mod_proxy_ajp of Apache HTTP Server.
If mod_proxy_ajp connects to a malicious AJP server this AJP server can send a malicious AJP message back to mod_proxy_ajp and cause it to write 4 attacker controlled bytes after the end of a heap ba…

### CVE-2026-33324
**fit2cloud sqlbot SQL injection**
- **Signals:** CVSS
- **Asset:** fit2cloud sqlbot
- **Attack:** SQL injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T19:22:59.910
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-05)

> SQLBot is an intelligent Text-to-SQL system based on large language models and RAG. In versions 1.7.0 and earlier, the Text2SQL chat interface is vulnerable to prompt injection. The user-provided question parameter is directly concatenated into the LLM prompt without filtering or…

### CVE-2026-34084
**phpoffice phpspreadsheet**
- **Signals:** CVSS
- **Asset:** phpoffice phpspreadsheet
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T17:10:03.243
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-05)

> PhpSpreadsheet is a library for reading and writing spreadsheet files. In versions 1.30.2 and earlier, 2.0.0 through 2.1.14, 2.2.0 through 2.4.3, 3.3.0 through 3.10.3, and 4.0.0 through 5.5.0, when the filename argument to IOFactory::load() is user-controlled, an attacker can sup…

### CVE-2026-34458
**sandboxie-plus sandboxie privilege escalation**
- **Signals:** CVSS
- **Asset:** sandboxie-plus sandboxie
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-07T19:48:58.380
- **CWE:** CWE-93
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-05)

> Sandboxie-Plus is an open source sandbox-based isolation software for Windows. In versions 1.17.2 and earlier, an INI injection vulnerability allows any standard local user to bypass configuration restrictions (EditAdminOnly and ConfigPassword) and inject arbitrary directives int…

### CVE-2026-38428
**kestra kestra SQL Injection**
- **Signals:** CVSS
- **Asset:** kestra kestra
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T19:24:29.867
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-05)

> Kestra v1.3.3 and before is vulnerable to SQL Injection. The vulnerability occurs because user-controlled input from a GET parameter is directly concatenated into an SQL query without proper sanitization or parameterization. As a result, attackers can inject arbitrary SQL express…

### CVE-2026-38431
**frappe erpnext**
- **Signals:** CVSS
- **Asset:** frappe erpnext
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T17:06:43.360
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-05)

> ERPNext v15.103.1 and before is vulnerable to Server-Side Template Injection (SSTI). An attacker with permission to create or edit email templates can inject template expressions that are executed on the server when the template is rendered.

### CVE-2026-40329
**Masa CMS is an open source content management system.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T20:24:04.853
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-05)

> Masa CMS is an open source content management system. In versions 7.5.2 and earlier, a SQL injection vulnerability exists in the beanFeed.cfc component within the getQuery function's processing of the sortBy parameter. The application fails to properly sanitize or parameterize th…

### CVE-2026-40330
**Masa CMS is an open source content management system.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T20:24:04.853
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-05)

> Masa CMS is an open source content management system. In versions 7.2.0 through 7.2.9, 7.3.0 through 7.3.14, 7.4.0 through 7.4.9, and 7.5.0 through 7.5.2, a SQL injection vulnerability exists in the beanFeed.cfc component within the getQuery function's handling of the sortDirecti…

### CVE-2026-40331
**Masa CMS is an open source content management system.**
- **Signals:** CVSS
- **Attack:** SQL injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T20:24:04.853
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-05)

> Masa CMS is an open source content management system. In versions 7.2.0 through 7.2.9, 7.3.0 through 7.3.14, 7.4.0 through 7.4.9, and 7.5.0 through 7.5.2, the unauthenticated JSON API accepts an altTable parameter that is stored via the setAltTable() method without validation or …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-05*
