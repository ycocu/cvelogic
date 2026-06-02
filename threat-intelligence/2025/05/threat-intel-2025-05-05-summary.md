# Daily Threat Intelligence — May 05, 2025

**Digest window (UTC):** 2025-05-05
**Generated:** 2026-06-02T07:32:40Z

## Threat brief

Langflow added to CISA KEV — confirmed in-the-wild exploitation. · Advantech R-seenet — exploitation likelihood rose sharply (EPSS 9.9% → 28% · rising (+18%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Langflow added to CISA KEV — confirmed in-the-wild exploitation.
- Advantech R-seenet — exploitation likelihood rose sharply (EPSS 9.9% → 28% · rising (+18%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2025-3248
**Langflow Missing Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** langflow langflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T13:57:48.910
- **CWE:** CWE-306
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2025-05-05

> Langflow versions prior to 1.3.0 are susceptible to code injection in 
the /api/v1/validate/code endpoint. A remote and unauthenticated attacker can send crafted HTTP requests to execute arbitrary
code.

### CVE-2021-21804
**advantech r-seenet Code Execution**
- **Signals:** EPSS
- **Asset:** advantech r-seenet
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:49:00.403
- **CWE:** CWE-98
- **CWE:** CWE-829
- **Risk score:** 86
- **EPSS 9.9% (2025-03-30) → 27.8% (2025-05-05), Δ +17.9%**

> A local file inclusion (LFI) vulnerability exists in the options.php script functionality of Advantech R-SeeNet v 2.4.12 (20.10.2020). A specially crafted HTTP request can lead to arbitrary PHP code execution. An attacker can send a crafted HTTP request to trigger this vulnerabil…

### CVE-2025-1909
**buddyboss buddyboss_platform Auth Bypass**
- **Signals:** CVSS
- **Asset:** buddyboss buddyboss_platform
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-28T20:03:54.720
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-05)

> The BuddyBoss Platform Pro plugin for WordPress is vulnerable to authentication bypass in versions up to, and including, 2.7.01. This is due to insufficient verification on the user being supplied during the Apple OAuth authenticate request through the plugin. This makes it possi…

### CVE-2025-4318
**The AWS Amplify Studio UI component property expressions in the aws-amplify/amplify-codegen-ui package lack input validation.**
- **Signals:** CVSS
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-95
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-05-05)

> The AWS Amplify Studio UI component property expressions in the aws-amplify/amplify-codegen-ui package lack input validation. This could potentially allow an authenticated user who has access to create or modify components to run arbitrary JavaScript code during the component ren…

### CVE-2025-44071
**seacms seacms RCE**
- **Signals:** CVSS
- **Asset:** seacms seacms
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-13T20:03:39.143
- **CWE:** CWE-94
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-05)

> SeaCMS v13.3 was discovered to contain a remote code execution (RCE) vulnerability via the component phomebak.php. This vulnerability allows attackers to execute arbitrary code via a crafted request.

### CVE-2025-44072
**seacms seacms SQL Injection**
- **Signals:** CVSS
- **Asset:** seacms seacms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-13T20:05:16.493
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-05)

> SeaCMS v13.3 was discovered to contain a SQL injection vulnerability via the component admin_manager.php.

### CVE-2025-44074
**seacms seacms SQL Injection**
- **Signals:** CVSS
- **Asset:** seacms seacms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-13T20:05:29.563
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-05)

> SeaCMS v13.3 was discovered to contain a SQL injection vulnerability via the component admin_topic.php.

### CVE-2025-45607
**liaoxuefeng itranswarp**
- **Signals:** CVSS
- **Asset:** liaoxuefeng itranswarp
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-16T20:17:27.537
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-05)

> An issue in the component /manage/ of itranswarp v2.19 allows attackers to bypass authentication via a crafted request.

### CVE-2025-45611
**java-aodeng hope-boot**
- **Signals:** CVSS
- **Asset:** java-aodeng hope-boot
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-14T20:50:05.040
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-05)

> Incorrect access control in the /user/edit/ component of hope-boot v1.0.0 allows attackers to bypass authentication via a crafted GET request.

### CVE-2025-45612
**exrick xmall**
- **Signals:** CVSS
- **Asset:** exrick xmall
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-16T20:00:50.837
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-05)

> Incorrect access control in xmall v1.1 allows attackers to bypass authentication via a crafted GET request to /index.

### CVE-2025-45615
**user-xiangpeng yaoqishan**
- **Signals:** CVSS
- **Asset:** user-xiangpeng yaoqishan
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T15:18:40.497
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-05)

> Incorrect access control in the /admin/ API of yaoqishan v0.0.1-SNAPSHOT allows attackers to gain access to Admin rights via a crafted request.

### CVE-2025-45616
**baidu brcc**
- **Signals:** CVSS
- **Asset:** baidu brcc
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T15:08:53.267
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-05)

> Incorrect access control in the /admin/** API of brcc v1.2.0 allows attackers to gain access to Admin rights via a crafted request.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-05*
