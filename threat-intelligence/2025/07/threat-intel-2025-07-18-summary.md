# Daily Threat Intelligence — July 18, 2025

**Digest window (UTC):** 2025-07-18
**Generated:** 2026-06-02T07:33:05Z

## Threat brief

Fortinet FortiWeb added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Fortinet FortiWeb added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2025-25257
**Fortinet FortiWeb SQL Injection Vulnerability**
- **Signals:** KEV
- **Asset:** fortinet fortiweb
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T16:49:01.030
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 88
- **KEV:** added 2025-07-18

> An improper neutralization of special elements used in an SQL command ('SQL Injection') vulnerability [CWE-89] vulnerability in Fortinet FortiWeb 7.6.0 through 7.6.3, FortiWeb 7.4.0 through 7.4.7, FortiWeb 7.2.0 through 7.2.10, FortiWeb 7.0.0 through 7.0.10 allows an unauthentica…

### CVE-2025-49746
**microsoft azure_machine_learning privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_machine_learning
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T17:23:37.280
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-07-18)

> Improper authorization in Azure Machine Learning allows an authorized attacker to elevate privileges over a network.

### CVE-2025-49747
**microsoft azure_machine_learning privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_machine_learning
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T17:24:01.320
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-07-18)

> Missing authorization in Azure Machine Learning allows an authorized attacker to elevate privileges over a network.

### CVE-2025-26855
**A SQL injection in Articles Calendar extension 1.0.0 - 1.0.1.0007 for Joomla allows attackers to execute arbitrary SQL commands.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-18)

> A SQL injection in Articles Calendar extension 1.0.0 - 1.0.1.0007 for Joomla allows attackers to execute arbitrary SQL commands.

### CVE-2025-46001
**simogeo filemanager**
- **Signals:** CVSS
- **Asset:** simogeo filemanager
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-14T14:28:20.217
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-18)

> An arbitrary file upload vulnerability in the is_allowed_file_type() function of Filemanager v2.3.0 allows attackers to execute arbitrary code via uploading a crafted PHP file.

### CVE-2025-47158
**microsoft azure_devops Auth Bypass**
- **Signals:** CVSS
- **Asset:** microsoft azure_devops
- **Attack:** Auth Bypass
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T17:21:14.360
- **CWE:** CWE-302
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-07-18)

> Authentication bypass by assumed-immutable data in Azure DevOps allows an unauthorized attacker to elevate privileges over a network.

### CVE-2025-54079
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-30T19:59:30.557
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-18)

> WeGIA is an open source web manager with a focus on the Portuguese language and charitable institutions. A SQL Injection vulnerability was identified in versions prior to 3.4.6 in the endpoint `/html/atendido/Profile_Atendido.php`, in the `idatendido` parameter. This vulnerabilit…

### CVE-2025-54309
**CrushFTP Unprotected Alternate Channel Vulnerability**
- **Signals:** CVSS
- **Asset:** crushftp crushftp
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:25:42.887
- **CWE:** CWE-420
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-07-18)

> CrushFTP 10 before 10.8.5 and 11 before 11.3.4_23, when the DMZ proxy feature is not used, mishandles AS2 validation and consequently allows remote attackers to obtain admin access via HTTPS, as exploited in the wild in July 2025.

### CVE-2025-7395
**A certificate verification error in wolfSSL when building with the WOLFSSL_SYS_CA_CERTS and WOLFSSL_APPLE_NATIVE_CERT_VALIDATION options...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-07-18)

> A certificate verification error in wolfSSL when building with the WOLFSSL_SYS_CA_CERTS and WOLFSSL_APPLE_NATIVE_CERT_VALIDATION options results in the wolfSSL
 client failing to properly verify the server certificate's domain name,
 allowing any certificate issued by a trusted C…

### CVE-2025-7444
**The LoginPress Pro plugin for WordPress is vulnerable to authentication bypass in all versions up to, and including, 5.0.1.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-18)

> The LoginPress Pro plugin for WordPress is vulnerable to authentication bypass in all versions up to, and including, 5.0.1. This is due to insufficient verification on the user being returned by the social login token. This makes it possible for unauthenticated attackers to log i…

### CVE-2025-7783
**Use of Insufficiently Random Values vulnerability in form-data allows HTTP Parameter Pollution (HPP).**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-330
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-18)

> Use of Insufficiently Random Values vulnerability in form-data allows HTTP Parameter Pollution (HPP). This vulnerability is associated with program files lib/form_data.Js.

This issue affects form-data: < 2.5.4, 3.0.0 - 3.0.3, 4.0.0 - 4.0.3.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-18*
