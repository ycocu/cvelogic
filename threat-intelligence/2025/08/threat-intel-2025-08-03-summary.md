# Daily Threat Intelligence — August 03, 2025

**Digest window (UTC):** 2025-08-03
**Generated:** 2026-06-02T07:33:10Z

## Threat brief

Tesigandia Gandia Integra Total: public exploit or PoC linked (SQL Injection) · Lacaveprods Intellitamper — exploitation likelihood rose sharply (EPSS 12% → 24% · rising (+12%)).

## Executive summary

- Tesigandia Gandia Integra Total: public exploit or PoC linked (SQL Injection)
- Lacaveprods Intellitamper — exploitation likelihood rose sharply (EPSS 12% → 24% · rising (+12%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 7 |
| EPSS rise | 1 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **8** |


## CVEs

### CVE-2025-41373
**tesigandia gandia_integra_total SQL Injection**
- **Signals:** EXP
- **Asset:** tesigandia gandia_integra_total
- **Attack:** SQL Injection
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-08T18:41:23.173
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-08-03

> A SQL injection vulnerability has been found in Gandia Integra Total of TESI from version 2.1.2217.3 to v4.4.2236.1. The vulnerability allows an authenticated attacker to retrieve, create, update and delete databases through the 'idestudio' parameter in /encuestas/integraweb[_v4]…

### CVE-2025-54589
**9001 copyparty XSS**
- **Signals:** EXP
- **Asset:** 9001 copyparty
- **Attack:** XSS
- **CVSS max:** 6.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-22T14:38:17.617
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-08-03

> Copyparty is a portable file server. In versions 1.18.6 and below, when accessing the recent uploads page at `/?ru`, users can filter the results using an input field at the top. This field appends a filter parameter to the URL, which reflects its value directly into a `<script>`…

### CVE-2006-2494
**lacaveprods intellitamper Buffer Overflow**
- **Signals:** EPSS
- **Asset:** lacaveprods intellitamper
- **Attack:** Buffer Overflow
- **CVSS max:** 5.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 11.9% (2025-03-30) → 24.0% (2025-08-03), Δ +12.1%**

> Stack-based buffer overflow in IntelliTamper 2.07 allows remote attackers to execute arbitrary code via a crafted .map file.

### CVE-2023-3460
**ultimatemember ultimate_member**
- **Signals:** EXP
- **Asset:** ultimatemember ultimate_member
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:17:19.017
- **Risk score:** 78
- **EXP:** ref published 2025-08-03

> The Ultimate Member WordPress plugin before 2.6.7 does not prevent visitors from creating user accounts with arbitrary capabilities, effectively allowing attackers to create administrator accounts at will. This is actively being exploited in the wild.

### CVE-2025-49683
**microsoft windows_10_1507**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-15T17:17:05.277
- **CWE:** CWE-122
- **Risk score:** 78
- **EXP:** ref published 2025-08-03

> Integer overflow or wraparound in Virtual Hard Disk (VHDX) allows an unauthorized attacker to execute code locally.

### CVE-2025-49741
**microsoft edge_chromium**
- **Signals:** EXP
- **Asset:** microsoft edge_chromium
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2025-07-08T17:16:03.223
- **CWE:** CWE-268
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2025-08-03

> No cwe for this issue in Microsoft Edge (Chromium-based) allows an unauthorized attacker to disclose information over a network.

### CVE-2025-54769
**xorux lpar2rrd RCE**
- **Signals:** EXP
- **Asset:** xorux lpar2rrd
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:19:15.053
- **CWE:** CWE-24
- **Risk score:** 78
- **EXP:** ref published 2025-08-03

> An authenticated, read-only user can upload a file and perform a directory traversal to have the uploaded file placed in a location of their choosing.  This can be used to overwrite existing PERL modules within the application to achieve remote code execution (RCE) by an attacker…

### CVE-2025-8191
**macrozheng mall cross-site scripting**
- **Signals:** EXP
- **Asset:** macrozheng mall
- **Attack:** cross-site scripting
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-29T01:00:01.613
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-08-03

> A vulnerability, which was classified as problematic, was found in macrozheng mall up to 1.0.3. Affected is an unknown function of the file /swagger-ui/index.html of the component Swagger UI. The manipulation of the argument configUrl leads to cross site scripting. It is possible…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-03*
