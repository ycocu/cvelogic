# Daily Threat Intelligence — March 30, 2026

**Digest window (UTC):** 2026-03-30
**Generated:** 2026-06-02T07:34:48Z

## Threat brief

Citrix NetScaler added to CISA KEV — confirmed in-the-wild exploitation. · Centreon — exploitation likelihood rose sharply (EPSS 8.7% → 59% · rising (+50%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Citrix NetScaler added to CISA KEV — confirmed in-the-wild exploitation.
- Centreon — exploitation likelihood rose sharply (EPSS 8.7% → 59% · rising (+50%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **17** |


## CVEs

### CVE-2026-3055
**Citrix NetScaler Out-of-Bounds Read Vulnerability**
- **Signals:** KEV
- **Asset:** citrix netscaler_application_delivery_controller
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T13:18:14.213
- **CWE:** CWE-125
- **Risk score:** 88
- **KEV:** added 2026-03-30

> Insufficient input validation in NetScaler ADC and NetScaler Gateway when configured as a SAML IDP leading to memory overread

### CVE-2022-42426
**centreon centreon SQL injection**
- **Signals:** EPSS
- **Asset:** centreon centreon
- **Attack:** SQL injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:24:57.033
- **CWE:** CWE-89
- **Risk score:** 84
- **EPSS 8.7% (2026-01-23) → 59.0% (2026-03-30), Δ +50.3%**

> This vulnerability allows remote attackers to escalate privileges on affected installations of Centreon. Authentication is required to exploit this vulnerability. The specific flaw exists within the handling of requests to modify poller broker configuration. The issue results fro…

### CVE-2026-30307
**roocode roo_code Command Injection**
- **Signals:** CVSS
- **Asset:** roocode roo_code
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T15:57:26.460
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-30)

> Roo Code's command auto-approval module contains a critical OS command injection vulnerability that renders its whitelist security mechanism completely ineffective. The system relies on fragile regular expressions to parse command structures; while it attempts to intercept danger…

### CVE-2006-5925
**elinks elinks**
- **Signals:** EPSS
- **Asset:** elinks elinks
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 82
- **EPSS 20.5% (2025-10-18) → 33.2% (2026-03-30), Δ +12.7%**

> Links web browser 1.00pre12 and Elinks 0.9.2 with smbclient installed allows remote attackers to execute arbitrary code via shell metacharacters in an smb:// URI, as demonstrated by using PUT and GET statements.

### CVE-2009-1890
**apache debian_linux DoS**
- **Signals:** EPSS
- **Asset:** apache http_server
- **Attack:** DoS
- **CVSS max:** 7.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-400
- **Risk score:** 82
- **EPSS 21.6% (2026-03-04) → 37.9% (2026-03-30), Δ +16.3%**

> The stream_reqbody_cl function in mod_proxy_http.c in the mod_proxy module in the Apache HTTP Server before 2.3.3, when a reverse proxy is configured, does not properly handle an amount of streamed data that exceeds the Content-Length value, which allows remote attackers to cause…

### CVE-2022-21482
**netapp active_iq_unified_manager privilege escalation**
- **Signals:** EPSS
- **Asset:** oracle mysql
- **Attack:** privilege escalation
- **CVSS max:** 6.3
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:44:48.320
- **Risk score:** 79
- **EPSS 1.9% (2026-01-21) → 13.3% (2026-03-30), Δ +11.4%**

> Vulnerability in the MySQL Cluster product of Oracle MySQL (component: Cluster: General). Supported versions that are affected are 8.0.28 and prior. Difficult to exploit vulnerability allows high privileged attacker with access to the physical communication segment attached to th…

### CVE-2022-21483
**netapp active_iq_unified_manager privilege escalation**
- **Signals:** EPSS
- **Asset:** oracle mysql
- **Attack:** privilege escalation
- **CVSS max:** 6.3
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:44:48.453
- **Risk score:** 79
- **EPSS 1.9% (2026-01-21) → 13.3% (2026-03-30), Δ +11.4%**

> Vulnerability in the MySQL Cluster product of Oracle MySQL (component: Cluster: General). Supported versions that are affected are 7.4.35 and prior, 7.5.25 and prior, 7.6.21 and prior and 8.0.28 and prior. Difficult to exploit vulnerability allows high privileged attacker with ac…

### CVE-2022-42428
**centreon centreon SQL injection**
- **Signals:** EPSS
- **Asset:** centreon centreon
- **Attack:** SQL injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:24:57.267
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 84
- **EPSS 18.5% (2026-01-23) → 59.0% (2026-03-30), Δ +40.5%**

> This vulnerability allows remote attackers to escalate privileges on affected installations of Centreon. Authentication is required to exploit this vulnerability. The specific flaw exists within the handling of requests to modify poller broker configuration. The issue results fro…

### CVE-2026-30306
**rahmanazhar sakadev**
- **Signals:** CVSS
- **Asset:** rahmanazhar sakadev
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-08T15:49:50.410
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-30)

> In its design for automatic terminal command execution, SakaDev offers two options: Execute safe commands and execute all commands. The description for the former states that commands determined by the model to be safe will be automatically executed, whereas if the model judges a…

### CVE-2026-30308
**presidio hai_build**
- **Signals:** CVSS
- **Asset:** presidio hai_build
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-08T15:44:35.610
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-30)

> In its design for automatic terminal command execution, HAI Build Code Generator offers two options: Execute safe commands and Execute all commands. The description for the former states that commands determined by the model to be safe will be automatically executed, whereas if t…

### CVE-2026-30313
**cline cline Command Injection**
- **Signals:** CVSS
- **Asset:** cline cline
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-08T15:38:06.820
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-30)

> DSAI-Cline's command auto-approval module contains a critical OS command injection vulnerability that renders its whitelist security mechanism completely ineffective. The system relies on string-based parsing to validate commands; while it intercepts dangerous operators such as ;…

### CVE-2026-31946
**frentix openolat**
- **Signals:** CVSS
- **Asset:** frentix openolat
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-02T16:49:44.503
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-30)

> OpenOlat is an open source web-based e-learning platform for teaching, learning, assessment and communication. From version 10.5.4 to before version 20.2.5, OpenOLAT's OpenID Connect implicit flow implementation does not verify JWT signatures. The JSONWebToken.parse() method sile…

### CVE-2026-33026
**nginxui nginx_ui**
- **Signals:** CVSS
- **Asset:** nginxui nginx_ui
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-01T18:16:43.630
- **CWE:** CWE-312
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-30)

> Nginx UI is a web user interface for the Nginx web server. Prior to version 2.3.4, the nginx-ui backup restore mechanism allows attackers to tamper with encrypted backup archives and inject malicious configuration during restoration. This issue has been patched in version 2.3.4.

### CVE-2026-34557
**ci4-cms-erp ci4ms privilege escalation**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T16:53:19.183
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-30)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, the application fails to properly sanitize user-controlled input within group and role management functionality…

### CVE-2026-34558
**ci4-cms-erp ci4ms privilege escalation**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T16:10:04.077
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-30)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, the application fails to properly sanitize user-controlled input within the Methods Management functionality wh…

### CVE-2026-4257
**The Contact Form by Supsystic plugin for WordPress is vulnerable to Server-Side Template Injection (SSTI) leading to Remote Code Executio...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T18:11:16.583
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-30)

> The Contact Form by Supsystic plugin for WordPress is vulnerable to Server-Side Template Injection (SSTI) leading to Remote Code Execution (RCE) in all versions up to, and including, 1.7.36. This is due to the plugin using the Twig `Twig_Loader_String` template engine without san…

### CVE-2026-4789
**kyverno kyverno SSRF**
- **Signals:** CVSS
- **Asset:** kyverno kyverno
- **Attack:** SSRF
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T18:17:51.837
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-30)

> Kyverno, versions 1.16.0 and later, are vulnerable to SSRF due to unrestricted CEL HTTP functions.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-30*
