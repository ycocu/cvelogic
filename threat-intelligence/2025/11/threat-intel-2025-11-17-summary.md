# Daily Threat Intelligence — November 17, 2025

**Digest window (UTC):** 2025-11-17
**Generated:** 2026-06-02T07:33:48Z

## Threat brief

Eiqnetworks Enterprise Security Analyzer — exploitation likelihood rose sharply (EPSS 4.5% → 20% · rising (+15%)). · 5 new critical disclosures — review patch status on exposed services.

## Executive summary

- Eiqnetworks Enterprise Security Analyzer — exploitation likelihood rose sharply (EPSS 4.5% → 20% · rising (+15%)).
- 5 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 5 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2007-5699
**eiqnetworks enterprise_security_analyzer Buffer Overflow**
- **Signals:** EPSS
- **Asset:** eiqnetworks enterprise_security_analyzer
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 81
- **EPSS 4.5% (2025-08-17) → 19.7% (2025-11-17), Δ +15.1%**

> Stack-based buffer overflow in eIQNetworks Enterprise Security Analyzer (ESA) 2.5 allows remote attackers to execute arbitrary code via certain data on TCP port 10616 that results in a long argument to the SEARCHREPORT command, a different vector than CVE-2007-2059.

### CVE-2008-1947
**apache tomcat XSS**
- **Signals:** EPSS
- **Asset:** apache tomcat
- **Attack:** XSS
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-79
- **Risk score:** 75
- **EPSS 49.1% (2025-03-30) → 59.3% (2025-11-17), Δ +10.2%**

> Cross-site scripting (XSS) vulnerability in Apache Tomcat 5.5.9 through 5.5.26 and 6.0.0 through 6.0.16 allows remote attackers to inject arbitrary web script or HTML via the name parameter (aka the hostname attribute) to host-manager/html/add.

### CVE-2024-44659
**phpgurukul online_shopping_portal SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul online_shopping_portal
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-18T20:44:41.657
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-17)

> PHPGurukul Online Shopping Portal 2.0 is vulnerable to SQL Injection via the email parameter in forgot-password.php.

### CVE-2025-10460
**A SQL Injection vulnerability on an endpoint in BEIMS Contractor Web, a legacy product that is no longer maintained or patched by the ven...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-11-17)

> A SQL Injection vulnerability on an endpoint in BEIMS Contractor Web, a legacy product that is no longer maintained or patched by the vendor, allows an unauthorised user to retrieve sensitive database contents via unsanitized parameter input. This vulnerability occurs due to impr…

### CVE-2025-13284
**ThinPLUS developed by ThinPLUS has an OS Command Injection vulnerability, allowing unauthenticated remote attackers to inject arbitrary O...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-17)

> ThinPLUS developed by ThinPLUS has an OS Command Injection vulnerability, allowing unauthenticated remote attackers to inject arbitrary OS commands and execute them on the server.

### CVE-2025-63747
**testmanagement qatraq privilege escalation**
- **Signals:** CVSS
- **Asset:** testmanagement qatraq
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-26T15:50:35.877
- **CWE:** CWE-521
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-17)

> QaTraq 6.9.2 ships with administrative account credentials which are enabled in default installations and permit immediate login via the web application login page. Because the account provides administrative privileges in the default configuration, an attacker who can reach the …

### CVE-2025-9501
**The W3 Total Cache WordPress plugin before 2.8.13 is vulnerable to command injection via the _parse_dynamic_mfunc function, allowing unau...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-11-17)

> The W3 Total Cache WordPress plugin before 2.8.13 is vulnerable to command injection via the _parse_dynamic_mfunc function, allowing unauthenticated users to execute PHP commands by submitting a comment with a malicious payload to a post.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-17*
