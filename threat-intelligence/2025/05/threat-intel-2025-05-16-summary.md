# Daily Threat Intelligence — May 16, 2025

**Digest window (UTC):** 2025-05-16
**Generated:** 2026-06-02T07:32:43Z

## Threat brief

4 new critical disclosures — review patch status on exposed services.

## Executive summary

- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2025-47916
**invisioncommunity invisioncommunity RCE**
- **Signals:** CVSS
- **Asset:** invisioncommunity invisioncommunity
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-20T17:42:15.083
- **CWE:** CWE-1336
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-16)

> Invision Community 5.0.0 before 5.0.7 allows remote code execution via crafted template strings to themeeditor.php. The issue lies within the themeeditor controller (file: /applications/core/modules/front/system/themeeditor.php), where a protected method named customCss can be in…

### CVE-2025-40906
**BSON::XS versions 0.8.4 and earlier for Perl includes a bundled libbson 1.1.7, which has several vulnerabilities.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-16)

> BSON::XS versions 0.8.4 and earlier for Perl includes a bundled libbson 1.1.7, which has several vulnerabilities.

Those include CVE-2017-14227, CVE-2018-16790, CVE-2023-0437, CVE-2024-6381, CVE-2024-6383, and CVE-2025-0755. 

BSON-XS was the official Perl XS implementation of Mo…

### CVE-2025-39481
**imithemes eventer SQL Injection**
- **Signals:** CVSS
- **Asset:** imithemes eventer
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T15:29:38.647
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-16)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in imithemes Eventer eventer allows Blind SQL Injection.This issue affects Eventer: from n/a through < 3.11.4.

### CVE-2025-32643
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in mojoomla WPGYM allows Blind SQL Inj...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-28T19:31:47.600
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-16)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in mojoomla WPGYM allows Blind SQL Injection. This issue affects WPGYM: from n/a through 65.0.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-16*
