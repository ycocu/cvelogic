# Daily Threat Intelligence — January 14, 2026

**Digest window (UTC):** 2026-01-14
**Generated:** 2026-06-02T07:34:11Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2026-22238
**blusparkglobal bluvoyix privilege escalation**
- **Signals:** CVSS
- **Asset:** blusparkglobal bluvoyix
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T15:51:24.527
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-14)

> The vulnerability exists in BLUVOYIX due to improper authentication in the BLUVOYIX admin APIs. An unauthenticated remote attacker could exploit this vulnerability by sending specially crafted HTTP requests to the vulnerable admin API to create a new user with admin privileges. S…

### CVE-2026-22236
**blusparkglobal bluvoyix**
- **Signals:** CVSS
- **Asset:** blusparkglobal bluvoyix
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T15:49:19.107
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-14)

> The vulnerability exists in BLUVOYIX due to improper authentication in the BLUVOYIX backend APIs. An unauthenticated remote attacker could exploit this vulnerability by sending specially crafted HTTP requests to the vulnerable APIs. Successful exploitation of this vulnerability c…

### CVE-2026-22237
**blusparkglobal bluvoyix**
- **Signals:** CVSS
- **Asset:** blusparkglobal bluvoyix
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T15:50:01.883
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-14)

> The vulnerability exists in BLUVOYIX due to the exposure of sensitive internal API documentation. An unauthenticated remote attacker could exploit this vulnerability by sending specially crafted HTTP requests to the APIs exposed by the documentation. Successful exploitation of th…

### CVE-2025-14301
**The Integration Opvius AI for WooCommerce plugin for WordPress is vulnerable to Path Traversal in all versions up to, and including, 1.3.0.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-14)

> The Integration Opvius AI for WooCommerce plugin for WordPress is vulnerable to Path Traversal in all versions up to, and including, 1.3.0. This is due to the `process_table_bulk_actions()` function processing user-supplied file paths without authentication checks, nonce verifica…

### CVE-2025-14502
**The News and Blog Designer Bundle plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 1.1 vi...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-98
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-14)

> The News and Blog Designer Bundle plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 1.1 via the template parameter. This makes it possible for unauthenticated attackers to include and execute arbitrary .php files on the server, allow…

### CVE-2025-37184
**arubanetworks edgeconnect_sd-wan_orchestrator**
- **Signals:** CVSS
- **Asset:** arubanetworks edgeconnect_sd-wan_orchestrator
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-03T18:16:23.290
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-14)

> A vulnerability exists in an Orchestrator service that could allow an unauthenticated remote attacker to bypass multi-factor authentication requirements. Successful exploitation could allow an attacker to create an admin user account without the necessary multi-factor authenticat…

### CVE-2025-70968
**freeimage_project freeimage**
- **Signals:** CVSS
- **Asset:** freeimage_project freeimage
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-23T14:50:59.003
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-14)

> FreeImage 3.18.0 contains a Use After Free in PluginTARGA.cpp;loadRLE().

### CVE-2026-22239
**blusparkglobal bluvoyix**
- **Signals:** CVSS
- **Asset:** blusparkglobal bluvoyix
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T15:50:35.943
- **CWE:** CWE-400
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-14)

> The vulnerability exists in BLUVOYIX due to design flaws in the email sending API. An unauthenticated remote attacker could exploit this vulnerability by sending specially crafted HTTP requests to the vulnerable email sending API. Successful exploitation of this vulnerability cou…

### CVE-2026-22240
**blusparkglobal bluvoyix**
- **Signals:** CVSS
- **Asset:** blusparkglobal bluvoyix
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T15:50:22.353
- **CWE:** CWE-200
- **CWE:** CWE-522
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-14)

> The vulnerability exists in BLUVOYIX due to an improper password storage implementation and subsequent exposure via unauthenticated APIs. An unauthenticated remote attacker could exploit this vulnerability by sending specially crafted HTTP requests to the vulnerable users API to …

### CVE-2026-23550
**Incorrect Privilege Assignment vulnerability in Modular DS Modular DS modular-connector allows Privilege Escalation.This issue affects Mo...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:36:39.077
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-14)

> Incorrect Privilege Assignment vulnerability in Modular DS Modular DS modular-connector allows Privilege Escalation.This issue affects Modular DS: from n/a through <= 2.5.1.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-14*
