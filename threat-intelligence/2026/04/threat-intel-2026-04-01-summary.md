# Daily Threat Intelligence — April 01, 2026

**Digest window (UTC):** 2026-04-01
**Generated:** 2026-06-02T07:34:49Z

## Threat brief

Google Dawn added to CISA KEV — confirmed in-the-wild exploitation. · Microsoft Win32k — exploitation likelihood rose sharply (EPSS 28% → 54% · rising (+26%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Google Dawn added to CISA KEV — confirmed in-the-wild exploitation.
- Microsoft Win32k — exploitation likelihood rose sharply (EPSS 28% → 54% · rising (+26%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2026-5281
**Google Dawn Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** google chrome
- **Attack:** Use-After-Free
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-02T13:16:01.903
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2026-04-01

> Use after free in Dawn in Google Chrome prior to 146.0.7680.178 allowed a remote attacker who had compromised the renderer process to execute arbitrary code via a crafted HTML page. (Chromium security severity: High)

### CVE-2021-28310
**Microsoft Win32k Privilege Escalation Vulnerability**
- **Signals:** EPSS
- **Asset:** microsoft windows_10_1803
- **Attack:** Privilege Escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T19:55:23.683
- **CWE:** CWE-787
- **CWE:** CWE-787
- **Risk score:** 83
- **EPSS 27.8% (2026-02-18) → 54.0% (2026-04-01), Δ +26.1%**

> Win32k Elevation of Privilege Vulnerability

### CVE-2026-34569
**ci4-cms-erp ci4ms privilege escalation**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T16:35:35.977
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-01)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, the application fails to properly sanitize user-controlled input when creating or editing blog categories. An a…

### CVE-2010-1797
**apple iphone_os Buffer Overflow**
- **Signals:** EPSS
- **Asset:** apple iphone_os
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 48.4% (2025-08-11) → 59.7% (2026-04-01), Δ +11.3%**

> Multiple stack-based buffer overflows in the cff_decoder_parse_charstrings function in the CFF Type2 CharStrings interpreter in cff/cffgload.c in FreeType before 2.4.2, as used in Apple iOS before 4.0.2 on the iPhone and iPod touch and before 3.2.2 on the iPad, allow remote attac…

### CVE-2014-9357
**docker docker privilege escalation**
- **Signals:** EPSS
- **Asset:** docker docker
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-264
- **Risk score:** 85
- **EPSS 24.6% (2026-03-09) → 36.2% (2026-04-01), Δ +11.6%**

> Docker 1.3.2 allows remote attackers to execute arbitrary code with root privileges via a crafted (1) image or (2) build in a Dockerfile in an LZMA (.xz) archive, related to the chroot for archive extraction.

### CVE-2026-34559
**ci4-cms-erp ci4ms privilege escalation**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-13T18:02:00.033
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-01)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, the application fails to properly sanitize user-controlled input when creating or editing blog tags. An attacke…

### CVE-2026-34560
**ci4-cms-erp ci4ms cross-site scripting**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** cross-site scripting
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-13T18:00:22.750
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-01)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, the application renders user-controlled input unsafely within the logs interface. If any stored XSS payload exi…

### CVE-2026-34563
**ci4-cms-erp ci4ms cross-site scripting**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** cross-site scripting
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-07T21:33:51.717
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-01)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, the application fails to properly sanitize user-controlled input when handling backup uploads and processing ba…

### CVE-2026-34564
**ci4-cms-erp ci4ms privilege escalation**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-07T21:29:34.323
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-01)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, the application fails to properly sanitize user-controlled input when adding Pages to navigation menus through …

### CVE-2026-34565
**ci4-cms-erp ci4ms privilege escalation**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T16:43:31.467
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-01)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, the application fails to properly sanitize user-controlled input when adding Posts to navigation menus through …

### CVE-2026-34566
**ci4-cms-erp ci4ms privilege escalation**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T16:42:22.200
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-01)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, the application fails to properly sanitize user-controlled input within the Page Management functionality when …

### CVE-2026-34567
**ci4-cms-erp ci4ms privilege escalation**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T16:41:42.780
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-01)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, the application fails to properly sanitize user-controlled input when creating or editing blog posts within the…

### CVE-2026-34568
**ci4-cms-erp ci4ms privilege escalation**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T16:49:31.050
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-01)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, the application fails to properly sanitize user-controlled input when creating or editing blog posts. An attack…

### CVE-2026-34571
**ci4-cms-erp ci4ms XSS**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** XSS
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T16:33:14.173
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-01)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.31.0.0, a Stored Cross-Site Scripting (Stored XSS) vulnerability exists in the backend user management functionality. T…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-01*
