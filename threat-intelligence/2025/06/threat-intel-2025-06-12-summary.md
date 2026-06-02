# Daily Threat Intelligence — June 12, 2025

**Digest window (UTC):** 2025-06-12
**Generated:** 2026-06-02T07:32:52Z

## Threat brief

Emc Alphastor — exploitation likelihood rose sharply (EPSS 34% → 56% · rising (+23%)). · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- Emc Alphastor — exploitation likelihood rose sharply (EPSS 34% → 56% · rising (+23%)).
- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2013-0946
**emc alphastor Buffer Overflow**
- **Signals:** EPSS
- **Asset:** emc alphastor
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 33.7% (2025-03-30) → 56.4% (2025-06-12), Δ +22.7%**

> Buffer overflow in the Library Control Program (LCP) in EMC AlphaStor 4.0 before build 910 allows remote attackers to execute arbitrary code via crafted commands.

### CVE-2025-4973
**amentotech workreap Auth Bypass**
- **Signals:** CVSS
- **Asset:** amentotech workreap
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-10T00:13:10.950
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-12)

> The Workreap plugin for WordPress, used by the Workreap - Freelance Marketplace WordPress Theme, is vulnerable to authentication bypass in all versions up to, and including, 3.3.1. This is due to the plugin not properly verifying a user's identity prior to logging them in when ve…

### CVE-2022-4976
**Archive::Unzip::Burst from 0.01 through 0.09 for Perl contains a bundled InfoZip library that is affected by several vulnerabilities.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-12)

> Archive::Unzip::Burst from 0.01 through 0.09 for Perl contains a bundled InfoZip library that is affected by several vulnerabilities.

The bundled library is affected by CVE-2014-8139, CVE-2014-8140 and CVE-2014-8141.

### CVE-2024-56158
**xwiki xwiki SQL injection**
- **Signals:** CVSS
- **Asset:** xwiki xwiki
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-12T15:16:01.537
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-12)

> XWiki is a generic wiki platform. It's possible to execute any SQL query in Oracle by using the function like DBMS_XMLGEN or DBMS_XMLQUERY. The XWiki query validator does not sanitize functions that would be used in a simple select and Hibernate allows using any native function i…

### CVE-2025-49467
**A SQL injection vulnerability in JEvents component before 3.6.88 and 3.6.82.1 for Joomla was discovered.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-12)

> A SQL injection vulnerability in JEvents component before 3.6.88 and 3.6.82.1 for Joomla was discovered. The extension is vulnerable to SQL injection via publicly accessible actions to list events by date ranges.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-12*
