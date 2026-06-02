# Daily Threat Intelligence — August 07, 2025

**Digest window (UTC):** 2025-08-07
**Generated:** 2026-06-02T07:33:11Z

## Threat brief

10 new critical disclosures — review patch status on exposed services.

## Executive summary

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

### CVE-2025-53767
**microsoft azure_openai privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_openai
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T17:32:03.190
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-07)

> Azure OpenAI Elevation of Privilege Vulnerability

### CVE-2023-41530
**kishan0725 hospital_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** kishan0725 hospital_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-11T14:45:20.757
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-07)

> Hospital Management System v4 was discovered to contain a SQL injection vulnerability via the app_contact parameter in appsearch.php.

### CVE-2025-50692
**foxcms foxcms Code Execution**
- **Signals:** CVSS
- **Asset:** foxcms foxcms
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T19:48:25.637
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-07)

> FoxCMS <=v1.2.5 is vulnerable to Code Execution in admin/template_file/editFile.html.

### CVE-2025-30404
**An integer overflow vulnerability in the loading of ExecuTorch models can cause overlapping allocations, potentially resulting in code ex...**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-190
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-07)

> An integer overflow vulnerability in the loading of ExecuTorch models can cause overlapping allocations, potentially resulting in code execution or other undesirable effects. This issue affects ExecuTorch prior to commit d158236b1dc84539c1b16843bc74054c9dcba006.

### CVE-2025-30405
**An integer overflow vulnerability in the loading of ExecuTorch models can cause objects to be placed outside their allocated memory area,...**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-190
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-07)

> An integer overflow vulnerability in the loading of ExecuTorch models can cause objects to be placed outside their allocated memory area, potentially resulting in code execution or other undesirable effects. This issue affects ExecuTorch prior to commit 0830af8207240df8d7f35b984c…

### CVE-2025-45765
**ruby-jwt v3.0.0.beta1 was discovered to contain weak encryption.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-326
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-07)

> ruby-jwt v3.0.0.beta1 was discovered to contain weak encryption. NOTE: the Supplier's perspective is "keysize is not something that is enforced by this library. Currently more recent versions of OpenSSL are enforcing some key sizes and those restrictions apply to the users of thi…

### CVE-2025-53792
**microsoft azure_portal privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_portal
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T17:34:08.153
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-07)

> Azure Portal Elevation of Privilege Vulnerability

### CVE-2025-54949
**A heap buffer overflow vulnerability in the loading of ExecuTorch models can potentially result in code execution or other undesirable ef...**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-07)

> A heap buffer overflow vulnerability in the loading of ExecuTorch models can potentially result in code execution or other undesirable effects. This issue affects ExecuTorch prior to commit ede82493dae6d2d43f8c424e7be4721abe5242be

### CVE-2025-54950
**An out-of-bounds access vulnerability in the loading of ExecuTorch models can cause the runtime to crash and potentially result in code e...**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-125
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-07)

> An out-of-bounds access vulnerability in the loading of ExecuTorch models can cause the runtime to crash and potentially result in code execution or other undesirable effects. This issue affects ExecuTorch prior to commit b6b7a16df5e7852d976d8c34c8a7e9a1b6f7d005.

### CVE-2025-54951
**A group of related buffer overflow vulnerabilities in the loading of ExecuTorch models can cause the runtime to crash and potentially res...**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-07)

> A group of related buffer overflow vulnerabilities in the loading of ExecuTorch models can cause the runtime to crash and potentially result in code execution or other undesirable effects. This issue affects ExecuTorch prior to commit cea9b23aa8ff78aff92829a466da97461cc7930c.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-07*
