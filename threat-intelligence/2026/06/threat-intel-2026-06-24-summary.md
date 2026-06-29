# Daily Threat Intelligence — June 24, 2026

**Digest window (US Eastern, NVD):** 2026-06-24
**Generated:** 2026-06-29T10:33:11Z

## Threat brief

Palo Alto Networks Cloud Ngfw — exploitation likelihood rose sharply (EPSS 32% → 44% · rising (+11%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Palo Alto Networks Cloud Ngfw — exploitation likelihood rose sharply (EPSS 32% → 44% · rising (+11%)).
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

### CVE-2025-0133
**palo_alto_networks cloud_ngfw XSS**
- **Signals:** EPSS
- **Asset:** palo_alto_networks cloud_ngfw
- **Attack:** XSS
- **CVSS max:** 2.7
- **NVD status:** Deferred
- **NVD published:** 2025-05-14
- **NVD modified:** 2026-06-17
- **CWE:** CWE-79
- **Risk score:** 76
- **EPSS 32.1% (2026-06-22) → 43.5% (2026-06-24), Δ +11.4%**

> A reflected cross-site scripting (XSS) vulnerability in the GlobalProtect™ gateway and portal features of Palo Alto Networks PAN-OS® software enables execution of malicious JavaScript in the context of an authenticated Captive Portal user's browser when they click on a specially …

### CVE-2022-28171
**hikvision ds-a71024_firmware**
- **Signals:** EPSS
- **Asset:** hikvision ds-a71024_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD published:** 2022-06-27
- **NVD modified:** 2026-06-17
- **CWE:** CWE-78
- **CWE:** CWE-77
- **Risk score:** 80
- **EPSS 39.3% (2026-06-15) → 49.9% (2026-06-24), Δ +10.5%**

> The web module in some Hikvision Hybrid SAN/Cluster Storage products have the following security vulnerability. Due to the insufficient input validation, attacker can exploit the vulnerability to execute restricted commands by sending messages with malicious commands to the affec…

### CVE-2026-55454
**appsmith appsmith SSRF**
- **Signals:** CVSS
- **Asset:** appsmith appsmith
- **Attack:** SSRF
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD published:** 2026-06-24
- **NVD modified:** 2026-06-26
- **CWE:** CWE-749
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-24)

> Appsmith is a platform to build admin panels, internal tools, and dashboards. Prior to 2.1, the bundled Caddy reverse-proxy's admin API — which has no authentication by default — is bound on 0.0.0.0:2019 inside the container. While this listener is not directly published to the h…

### CVE-2026-39938
**cacti cacti**
- **Signals:** CVSS
- **Asset:** cacti cacti
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-06-24
- **NVD modified:** 2026-06-26
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-24)

> Cacti is an open source performance and fault management framework. Versions 1.2.30 and prior have unauthenticated LFI through graph_theme and rrdtool IPC serialization hardening. This issue has been resolved in version 1.2.31.

### CVE-2026-39948
**cacti cacti SQL injection**
- **Signals:** CVSS
- **Asset:** cacti cacti
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-06-24
- **NVD modified:** 2026-06-26
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-24)

> Cacti is an open source performance and fault management framework. In versions 1.2.30 and prior, the rfilter request parameter is retrieved via the raw accessor grv() (rather than gfrv() with FILTER_VALIDATE_IS_REGEX validation) and concatenated directly into RLIKE SQL clauses i…

### CVE-2026-39955
**cacti cacti SQL Injection**
- **Signals:** CVSS
- **Asset:** cacti cacti
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-06-24
- **NVD modified:** 2026-06-26
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-24)

> Cacti is an open source performance and fault management framework. Versions 1.2.30 and prior have pre-authentication SQL Injection via unanchored FILTER_VALIDATE_REGEXP in graph_view.php. This issue has been fixed in version 1.2.31.

### CVE-2026-50551
**SiYuan is an open-source personal knowledge management system.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD published:** 2026-06-24
- **NVD modified:** 2026-06-25
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-24)

> SiYuan is an open-source personal knowledge management system. Prior to 3.7.0, SiYuan contains a stored cross-site scripting (XSS) vulnerability in the Attribute View (database) asset cell renderer that escalates to remote code execution (RCE) in the Electron desktop client. This…

### CVE-2026-54067
**SiYuan is an open-source personal knowledge management system.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD published:** 2026-06-24
- **NVD modified:** 2026-06-25
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-24)

> SiYuan is an open-source personal knowledge management system. Prior to 3.7.0, CSS snippet body containing </style> breaks out of its surrounding <style> tag when renderSnippet() interpolates it via insertAdjacentHTML. A payload like runs arbitrary JavaScript in the renderer. On …

### CVE-2026-54069
**SiYuan is an open-source personal knowledge management system.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD published:** 2026-06-24
- **NVD modified:** 2026-06-25
- **CWE:** CWE-346
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-24)

> SiYuan is an open-source personal knowledge management system. Prior to 3.7.0, SiYuan Note's kernel HTTP server unconditionally trusts all chrome-extension:// origins, granting RoleAdministrator access to every installed browser extension without any authentication. Combined with…

### CVE-2026-54158
**SiYuan is an open-source personal knowledge management system.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD published:** 2026-06-24
- **NVD modified:** 2026-06-25
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-24)

> SiYuan is an open-source personal knowledge management system. Prior to 3.7.0, the attribute-view (database) cell renderer genAVValueHTML interpolates cell content raw in four of its branches: text, url, phone, and mAsset. A cell value like </textarea><img src=x onerror="..."> or…

### CVE-2026-55570
**SiYuan is an open-source personal knowledge management system.**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD published:** 2026-06-24
- **NVD modified:** 2026-06-25
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-06-24)

> SiYuan is an open-source personal knowledge management system. Prior to 3.7.0, it does not escape the untrusted fields (name, version, author, description) when they are serialized into the data-obj HTML attribute of each marketplace card. Because the attribute is single-quoted a…

### CVE-2026-55666
**Rocket.Chat is an open-source, secure, fully customizable communications platform.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD published:** 2026-06-24
- **NVD modified:** 2026-06-26
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-24)

> Rocket.Chat is an open-source, secure, fully customizable communications platform. Prior to 8.5.1, 8.4.4, 8.3.6, 8.2.6, 8.1.6, 8.0.7, and 7.10.13, in apps/meteor/app/apple/server/loginHandler.ts, handleIdentityToken parses a JWT issued by Apple during the OAuth flow. The try bloc…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-24*
