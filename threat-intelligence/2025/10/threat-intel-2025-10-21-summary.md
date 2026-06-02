# Daily Threat Intelligence — October 21, 2025

**Digest window (UTC):** 2025-10-21
**Generated:** 2026-06-02T07:33:38Z

## Threat brief

Apache Isis — exploitation likelihood rose sharply (EPSS 8.9% → 22% · rising (+13%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apache Isis — exploitation likelihood rose sharply (EPSS 8.9% → 22% · rising (+13%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2022-42466
**apache isis**
- **Signals:** EPSS
- **Asset:** apache isis
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2025-05-08T20:15:22.127
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 8.9% (2025-10-20) → 22.0% (2025-10-21), Δ +13.1%**

> Prior to 2.0.0-M9, it was possible for an end-user to set the value of an editable string property of a domain object to a value that would be rendered unchanged when the value was saved. In particular, the end-user could enter javascript or similar and this would be executed. As…

### CVE-2025-12004
**Incorrect Permission Assignment for Critical Resource vulnerability in The Wikimedia Foundation Mediawiki - Lockdown Extension allows Pri...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-732
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-21)

> Incorrect Permission Assignment for Critical Resource vulnerability in The Wikimedia Foundation Mediawiki - Lockdown Extension allows Privilege Abuse. Fixed in Mediawiki Core Action APIThis issue affects Mediawiki - Lockdown Extension: from master before 1.42.

### CVE-2025-53037
**oracle financial_services_analytical_applications_infrastructure**
- **Signals:** CVSS
- **Asset:** oracle financial_services_analytical_applications_infrastructure
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-23T16:08:38.390
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-21)

> Vulnerability in the Oracle Financial Services Analytical Applications Infrastructure product of Oracle Financial Services Applications (component: Platform).  Supported versions that are affected are 8.0.7.9, 8.0.8.7 and  8.1.2.5. Easily exploitable vulnerability allows unauthen…

### CVE-2025-10640
**An unauthenticated attacker with access to TCP port 12306 of the WorkExaminer server can exploit missing server-side authentication check...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-602
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-21)

> An unauthenticated attacker with access to TCP port 12306 of the WorkExaminer server can exploit missing server-side authentication checks to bypass the login prompt in the WorkExaminer Professional console to gain administrative access to the WorkExaminer server and therefore al…

### CVE-2025-10916
**The FormGent WordPress plugin before 1.0.4 is vulnerable to arbitrary file deletion due to insufficient file path validation.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-21)

> The FormGent  WordPress plugin before 1.0.4 is vulnerable to arbitrary file deletion due to insufficient file path validation. This makes it possible for unauthenticated attackers to delete arbitrary files on the server.

### CVE-2025-11534
**The affected Raisecom devices allow SSH sessions to be established without completing user authentication.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-21)

> The affected Raisecom devices allow SSH sessions to be established without completing user authentication. This could allow attackers to gain shell access without valid credentials.

### CVE-2025-11625
**wolfssh wolfssh Auth Bypass**
- **Signals:** CVSS
- **Asset:** wolfssh wolfssh
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-04T20:43:02.470
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-21)

> Improper host authentication vulnerability in wolfSSH version 1.4.20 and earlier clients that allows authentication bypass and leaking of clients credentials.

### CVE-2025-53072
**oracle marketing**
- **Signals:** CVSS
- **Asset:** oracle marketing
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T14:36:58.140
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-21)

> Vulnerability in the Oracle Marketing product of Oracle E-Business Suite (component: Marketing Administration).  Supported versions that are affected are 12.2.3-12.2.14. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Or…

### CVE-2025-60772
**Improper authentication in the web-based management interface of NETLINK HG322G V1.0.00-231017, allows a remote unauthenticated attacker...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-21)

> Improper authentication in the web-based management interface of NETLINK HG322G V1.0.00-231017, allows a remote unauthenticated attacker to escalate privileges and lock out the legitimate administrator via crafted HTTP requests.

### CVE-2025-61757
**Oracle Fusion Middleware Missing Authentication for Critical Function Vulnerability**
- **Signals:** CVSS
- **Asset:** oracle identity_manager
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-24T13:38:20.900
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-21)

> Vulnerability in the Identity Manager product of Oracle Fusion Middleware (component: REST WebServices).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromi…

### CVE-2025-62481
**oracle marketing**
- **Signals:** CVSS
- **Asset:** oracle marketing
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:19:45.387
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-21)

> Vulnerability in the Oracle Marketing product of Oracle E-Business Suite (component: Marketing Administration).  Supported versions that are affected are 12.2.3-12.2.14. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Or…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-21*
