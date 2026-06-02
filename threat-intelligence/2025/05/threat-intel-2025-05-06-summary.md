# Daily Threat Intelligence — May 06, 2025

**Digest window (UTC):** 2025-05-06
**Generated:** 2026-06-02T07:32:40Z

## Threat brief

FreeType added to CISA KEV — confirmed in-the-wild exploitation. · Frappe Erpnext: public exploit or PoC linked (Privilege Escalation) · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- FreeType added to CISA KEV — confirmed in-the-wild exploitation.
- Frappe Erpnext: public exploit or PoC linked (Privilege Escalation)
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 2 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2025-27363
**FreeType Out-of-Bounds Write Vulnerability**
- **Signals:** KEV
- **Asset:** freetype freetype
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 8.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-20T13:15:39.743
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2025-05-06

> An out of bounds write exists in FreeType versions 2.13.0 and below (newer versions of FreeType are not vulnerable) when attempting to parse font subglyph structures related to TrueType GX and variable font files. The vulnerable code assigns a signed short value to an unsigned lo…

### CVE-2025-28062
**frappe erpnext Privilege Escalation**
- **Signals:** EXP
- **Asset:** frappe erpnext
- **Attack:** Privilege Escalation
- **CVSS max:** 8.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-17T14:13:04.563
- **CWE:** CWE-352
- **Risk score:** 78
- **EXP:** ref published 2025-05-06

> A Cross-Site Request Forgery (CSRF) vulnerability was discovered in ERPNEXT 14.82.1 and 14.74.3. The vulnerability allows an attacker to perform unauthorized actions such as user deletion, password resets, and privilege escalation due to missing CSRF protections.

### CVE-2025-47419
**Cleartext Transmission of Sensitive Information vulnerability in Crestron Automate VX allows Sniffing Network Traffic.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-319
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-06)

> Cleartext Transmission of Sensitive Information vulnerability in Crestron Automate VX allows Sniffing Network Traffic.

The device allows Web UI and API access over non-secure network ports which exposes sensitive information such as user passwords.


This issue affects Automate …

### CVE-2024-12225
**quarkus quarkus**
- **Signals:** CVSS
- **Asset:** quarkus quarkus
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-31T18:10:06.313
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-06)

> A vulnerability was found in Quarkus in the quarkus-security-webauthn module. The Quarkus WebAuthn module publishes default REST endpoints for registering and logging users in while allowing developers to provide custom REST endpoints. When developers provide custom REST endpoint…

### CVE-2025-0855
**The PGS Core plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 5.8.0 via deserialization o...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-06)

> The PGS Core plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 5.8.0 via deserialization of untrusted input in the 'import_header' function. This makes it possible for unauthenticated attackers to inject a PHP Object. No known POP ch…

### CVE-2025-25014
**elastic kibana RCE**
- **Signals:** CVSS
- **Asset:** elastic kibana
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-02T16:26:53.280
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-06)

> A Prototype pollution vulnerability in Kibana leads to arbitrary code execution via crafted HTTP requests to machine learning and reporting endpoints.

### CVE-2025-4041
**In Optigo Networks ONS NC600 versions 4.2.1-084 through 4.7.2-330, an attacker could connect with the device's ssh server and utilize the...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-06)

> In Optigo Networks ONS NC600 versions 4.2.1-084 through 4.7.2-330, an attacker could connect with the device's ssh server and utilize the system's components to perform OS command executions.

### CVE-2025-44073
**seacms seacms SQL Injection**
- **Signals:** CVSS
- **Asset:** seacms seacms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-12T17:09:21.733
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-06)

> SeaCMS v13.3 was discovered to contain a SQL injection vulnerability via the component admin_comment_news.php.

### CVE-2025-44899
**tenda rx3_firmware**
- **Signals:** CVSS
- **Asset:** tenda rx3_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-04T17:25:44.830
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-06)

> There is a stack overflow vulnerability in Tenda RX3 V1.0br_V16.03.13.11 In the fromSetWifiGusetBasic function of the web url /goform/ WifiGuestSet, the manipulation of the parameter shareSpeed leads to stack overflow.

### CVE-2025-45492
**netgear ex8000_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** netgear ex8000_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-13T20:19:44.220
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-06)

> Netgear EX8000 V1.0.0.126 is vulnerable to Command Injection via the Iface parameter in the action_wireless function.

### CVE-2025-46572
**passport-wsfed-saml2 provides passport strategy for both WS-fed and SAML2 protocol.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-06)

> passport-wsfed-saml2 provides passport strategy for both WS-fed and SAML2 protocol. A vulnerability present starting in version 3.0.5 up to and including version 4.6.3 allows an attacker to impersonate any user during SAML authentication by crafting a SAMLResponse. This can be do…

### CVE-2025-46816
**goshs is a SimpleHTTPServer written in Go.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-05-06)

> goshs is a SimpleHTTPServer written in Go. Starting in version 0.3.4 and prior to version 1.0.5, running goshs without arguments makes it possible for anyone to execute commands on the server. The function `dispatchReadPump` does not checks the option cli `-c`, thus allowing anyo…

### CVE-2025-47226
**snipeitapp snipe-it privilege escalation**
- **Signals:** EXP
- **Asset:** snipeitapp snipe-it
- **Attack:** privilege escalation
- **CVSS max:** 5.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-03T14:44:17.277
- **CWE:** CWE-425
- **CWE:** CWE-639
- **Risk score:** 78
- **EXP:** ref published 2025-05-06

> Grokability Snipe-IT before 8.1.0 has incorrect authorization for accessing asset information.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-06*
