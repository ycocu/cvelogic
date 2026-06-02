# Daily Threat Intelligence — February 03, 2026

**Digest window (UTC):** 2026-02-03
**Generated:** 2026-06-02T07:34:20Z

## Threat brief

Sangoma FreePBX: 2 CVEs added to CISA KEV today. · Foxitsoftware Phantompdf — exploitation likelihood rose sharply (EPSS 16% → 50% · rising (+34%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Sangoma FreePBX: 2 CVEs added to CISA KEV today.
- Foxitsoftware Phantompdf — exploitation likelihood rose sharply (EPSS 16% → 50% · rising (+34%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 4 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **20** |


## CVEs

### CVE-2021-39935
**GitLab Community and Enterprise Editions Server-Side Request Forgery (SSRF) Vulnerability**
- **Signals:** KEV
- **Asset:** gitlab gitlab
- **Attack:** SSRF
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-04T15:56:15.730
- **CWE:** CWE-918
- **CWE:** CWE-918
- **Risk score:** 88
- **KEV:** added 2026-02-03

> An issue has been discovered in GitLab CE/EE affecting all versions starting from 10.5 before 14.3.6, all versions starting from 14.4 before 14.4.4, all versions starting from 14.5 before 14.5.2. Unauthorized external users could perform Server Side Requests via the CI Lint API

### CVE-2018-3965
**foxitsoftware phantompdf RCE**
- **Signals:** EPSS
- **Asset:** foxitsoftware phantompdf
- **Attack:** RCE
- **CVSS max:** 8.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:06:23.907
- **CWE:** CWE-416
- **Risk score:** 83
- **EPSS 15.9% (2025-11-21) → 50.1% (2026-02-03), Δ +34.2%**

> An exploitable use-after-free vulnerability exists in the JavaScript engine of Foxit Software's Foxit PDF Reader version 9.1.0.5096. A specially crafted PDF document can trigger a previously freed object in memory to be reused, resulting in arbitrary code execution. An attacker n…

### CVE-2025-10878
**omran fikir_odalari_adminpando SQL Injection**
- **Signals:** CVSS
- **Asset:** omran fikir_odalari_adminpando
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-12T17:37:05.497
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-03)

> A SQL injection vulnerability exists in the login functionality of Fikir Odalari AdminPando 1.0.1 before 2026-01-26. The username and password parameters are vulnerable to SQL injection, allowing unauthenticated attackers to bypass authentication completely. Successful exploitati…

### CVE-1999-1579
**microsoft windows_nt DoS**
- **Signals:** EPSS
- **Asset:** microsoft windows_nt
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 27.1% (2025-05-20) → 42.0% (2026-02-03), Δ +14.9%**

> The Cenroll ActiveX control (xenroll.dll) for Terminal Server Editions of Windows NT 4.0 and Windows NT Server 4.0 before SP6 allows remote attackers to cause a denial of service (resource consumption) by creating a large number of arbitrary files on the target machine.

### CVE-2013-2817
**mitsubishielectric mc-worx_suite**
- **Signals:** EPSS
- **Asset:** mitsubishielectric mc-worx_suite
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-94
- **Risk score:** 83
- **EPSS 24.8% (2026-01-08) → 35.8% (2026-02-03), Δ +10.9%**

> An ActiveX control in IcoLaunch.dll in Mitsubishi Electric Automation MC-WorX Suite 8.02 allows user-assisted remote attackers to execute arbitrary programs via a crafted HTML document in conjunction with a Login Client button click.

### CVE-2018-3966
**foxitsoftware phantompdf RCE**
- **Signals:** EPSS
- **Asset:** foxitsoftware phantompdf
- **Attack:** RCE
- **CVSS max:** 8.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:06:24.020
- **CWE:** CWE-416
- **Risk score:** 83
- **EPSS 15.9% (2025-11-21) → 50.1% (2026-02-03), Δ +34.2%**

> An exploitable use-after-free vulnerability exists in the JavaScript engine of Foxit Software's Foxit PDF Reader version 9.1.0.5096. A specially crafted PDF document can trigger a previously freed object in memory to be reused, resulting in arbitrary code execution. An attacker n…

### CVE-2018-3967
**foxitsoftware phantompdf RCE**
- **Signals:** EPSS
- **Asset:** foxitsoftware phantompdf
- **Attack:** RCE
- **CVSS max:** 8.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:06:24.140
- **CWE:** CWE-416
- **Risk score:** 83
- **EPSS 16.0% (2025-11-21) → 50.1% (2026-02-03), Δ +34.1%**

> An exploitable use-after-free vulnerability exists in the JavaScript engine of Foxit Software's Foxit PDF Reader version 9.1.0.5096. A specially crafted PDF document can trigger a previously freed object in memory to be reused, resulting in arbitrary code execution. An attacker n…

### CVE-2019-19006
**Sangoma FreePBX Improper Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** sangoma freepbx
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-04T15:56:22.697
- **CWE:** CWE-287
- **CWE:** CWE-287
- **Risk score:** 88
- **KEV:** added 2026-02-03

> Sangoma FreePBX 115.0.16.26 and below, 14.0.13.11 and below, 13.0.197.13 and below have Incorrect Access Control.

### CVE-2020-37071
**CraftCMS 3 vCard Plugin 1.0.0 contains a deserialization vulnerability that allows unauthenticated attackers to execute arbitrary PHP cod...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-03)

> CraftCMS 3 vCard Plugin 1.0.0 contains a deserialization vulnerability that allows unauthenticated attackers to execute arbitrary PHP code through a crafted payload. Attackers can generate a malicious serialized payload that triggers remote code execution by exploiting the plugin…

### CVE-2020-37092
**Netis E1+ version 1.2.32533 contains a hardcoded root account vulnerability that allows unauthenticated attackers to access the device wi...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-03)

> Netis E1+ version 1.2.32533 contains a hardcoded root account vulnerability that allows unauthenticated attackers to access the device with predefined credentials. Attackers can leverage the embedded root account with a crackable password to gain full administrative access to the…

### CVE-2022-38418
**adobe coldfusion RCE**
- **Signals:** EPSS
- **Asset:** adobe coldfusion
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:16:26.210
- **CWE:** CWE-22
- **Risk score:** 86
- **EPSS 4.9% (2025-11-21) → 31.2% (2026-02-03), Δ +26.4%**

> Adobe ColdFusion versions Update 14 (and earlier) and Update 4 (and earlier) are affected by an Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') vulnerability that could result in arbitrary code execution in the context of the current user. Exploitat…

### CVE-2025-40551
**SolarWinds Web Help Desk Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** solarwinds web_help_desk
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-04T02:00:02.030
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2026-02-03

> SolarWinds Web Help Desk was found to be susceptible to an untrusted data deserialization vulnerability that could lead to remote code execution, which would allow an attacker to run commands on the host machine. This could be exploited without authentication.

### CVE-2025-64328
**Sangoma FreePBX OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** sangoma firestore
- **Attack:** Command Injection
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-24T19:30:59.130
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2026-02-03

> FreePBX Endpoint Manager is a module for managing telephony endpoints in FreePBX systems. In versions 17.0.2.36 and above before 17.0.3, the filestore module within the Administrative interface is vulnerable to a post-authentication command injection by an authenticated known use…

### CVE-2025-65078
**An untrusted search path vulnerability has been identified in the Embedded Solutions Framework in various Lexmark devices.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-426
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-03)

> An untrusted search path vulnerability has been identified in the Embedded Solutions Framework in various Lexmark devices. This vulnerability can be leveraged by an attacker to execute arbitrary code.

### CVE-2026-1341
**Avation Light Engine Pro exposes its configuration and control interface without any authentication or access control.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-03)

> Avation Light Engine Pro exposes its configuration and control interface without any authentication or access control.

### CVE-2026-1632
**MOMA Seismic Station Version v2.4.2520 and prior exposes its web management interface without requiring authentication, which could allow...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-03)

> MOMA Seismic Station Version v2.4.2520 and prior exposes its web management interface without requiring authentication, which could allow an unauthenticated attacker to modify configuration settings, acquire device data or remotely reset the device.

### CVE-2026-25150
**qwik qwik**
- **Signals:** CVSS
- **Asset:** qwik qwik
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-10T20:10:16.513
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-03)

> Qwik is a performance focused javascript framework. Prior to version 1.19.0, a prototype pollution vulnerability exists in the formToObj() function within @builder.io/qwik-city middleware. The function processes form field names with dot notation (e.g., user.name) to create neste…

### CVE-2026-25238
**pear pearweb SQL Injection**
- **Signals:** CVSS
- **Asset:** pear pearweb
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-05T18:01:30.977
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-03)

> PEAR is a framework and distribution system for reusable PHP components. Prior to version 1.33.0, a SQL injection vulnerability in bug subscription deletion may allow attackers to inject SQL via a crafted email value. This issue has been patched in version 1.33.0.

### CVE-2026-25241
**pear pearweb SQL Injection**
- **Signals:** CVSS
- **Asset:** pear pearweb
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-05T17:55:10.430
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-03)

> PEAR is a framework and distribution system for reusable PHP components. Prior to version 1.33.0, an unauthenticated SQL injection in the /get/<package>/<version> endpoint allows remote attackers to execute arbitrary SQL via a crafted package version. This issue has been patched …

### CVE-2026-25510
**ci4-cms-erp ci4ms RCE**
- **Signals:** CVSS
- **Asset:** ci4-cms-erp ci4ms
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-10T18:41:41.270
- **CWE:** CWE-94
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-02-03)

> CI4MS is a CodeIgniter 4-based CMS skeleton that delivers a production-ready, modular architecture with RBAC authorization and theme support. Prior to version 0.28.5.0, an authenticated user with file editor permissions can achieve Remote Code Execution (RCE) by leveraging the fi…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-03*
