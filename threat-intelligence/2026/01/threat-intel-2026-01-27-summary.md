# Daily Threat Intelligence — January 27, 2026

**Digest window (UTC):** 2026-01-27
**Generated:** 2026-06-02T07:34:17Z

## Threat brief

Fortinet Multiple Products added to CISA KEV — confirmed in-the-wild exploitation. · Adobe Coldfusion — exploitation likelihood rose sharply (EPSS 5.1% → 32% · rising (+27%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Fortinet Multiple Products added to CISA KEV — confirmed in-the-wild exploitation.
- Adobe Coldfusion — exploitation likelihood rose sharply (EPSS 5.1% → 32% · rising (+27%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2026-24858
**Fortinet Multiple Products Authentication Bypass Using an Alternate Path or Channel Vulnerability**
- **Signals:** KEV, CVSS
- **Asset:** fortinet fortianalyzer
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-12T18:47:28.407
- **CWE:** CWE-288
- **Risk score:** 97
- **KEV:** added 2026-01-27
- **CVSS critical:** 9.8 (disclosed 2026-01-27)

> An Authentication Bypass Using an Alternate Path or Channel vulnerability [CWE-288] vulnerability in Fortinet FortiAnalyzer 7.6.0 through 7.6.5, FortiAnalyzer 7.4.0 through 7.4.9, FortiAnalyzer 7.2.0 through 7.2.11, FortiAnalyzer 7.0.0 through 7.0.15, FortiManager 7.6.0 through 7…

### CVE-2022-38421
**adobe coldfusion RCE**
- **Signals:** EPSS
- **Asset:** adobe coldfusion
- **Attack:** RCE
- **CVSS max:** 7.2
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:16:26.613
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 5.1% (2025-11-21) → 32.0% (2026-01-27), Δ +26.9%**

> Adobe ColdFusion versions Update 14 (and earlier) and Update 4 (and earlier) are affected by an Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') vulnerability that could result in arbitrary code execution in the context of the current user. Exploitat…

### CVE-2025-14988
**A security issue has been identified in ibaPDA that could allow unauthorized actions on the file system under certain conditions.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-732
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-27)

> A security issue has been identified in ibaPDA that could allow unauthorized actions on the file system under certain conditions. This may impact the confidentiality, integrity, or availability of the system.

### CVE-2004-1264
**chbg chbg Buffer Overflow**
- **Signals:** EPSS
- **Asset:** chbg chbg
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 86
- **EPSS 7.3% (2025-05-17) → 25.6% (2026-01-27), Δ +18.3%**

> Buffer overflow in the simplify_path function in config.c for ChBg 1.5 allows remote attackers to execute arbitrary code via a crafted chbg scenario file.

### CVE-2007-0634
**sun solaris DoS**
- **Signals:** EPSS
- **Asset:** sun solaris
- **Attack:** DoS
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 83
- **EPSS 18.0% (2025-09-19) → 38.8% (2026-01-27), Δ +20.8%**

> Unspecified vulnerability in Sun Solaris 10 before 20070130 allows remote attackers to cause a denial of service (system crash) via certain ICMP packets.

### CVE-2022-45043
**tenda ax12_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** tenda ax12_firmware
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-22T20:15:25.490
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 83
- **EPSS 6.4% (2025-12-24) → 18.0% (2026-01-27), Δ +11.6%**

> Tenda AX12 V22.03.01.16_cn is vulnerable to command injection via goform/fast_setting_internet_set.

### CVE-2025-21589
**An Authentication Bypass Using an Alternate Path or Channel vulnerability in Juniper Networks Session Smart Router may allows a network-b...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T14:34:27.800
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-27)

> An Authentication Bypass Using an
Alternate Path or Channel vulnerability in Juniper Networks Session Smart
Router may allows a network-based attacker to bypass authentication
and take administrative control of the device.

This issue affects Session Smart Router: 



  *  from 5…

### CVE-2026-1480
**quatuor evaluacion_de_desempeno SQL Injection**
- **Signals:** CVSS
- **Asset:** quatuor evaluacion_de_desempeno
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-10T20:19:24.793
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-27)

> An out-of-band SQL injection vulnerability (OOB SQLi) has been detected in the Performance Evaluation (EDD) application developed by Gabinete Técnico de Programación. Exploiting this vulnerability in the parameter 'Id_usuario' in '/evaluacion_objetivos_anyo_sig_evalua.aspx', coul…

### CVE-2026-1481
**quatuor evaluacion_de_desempeno SQL Injection**
- **Signals:** CVSS
- **Asset:** quatuor evaluacion_de_desempeno
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-10T20:19:16.253
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-27)

> An out-of-band SQL injection vulnerability (OOB SQLi) has been detected in the Performance Evaluation (EDD) application developed by Gabinete Técnico de Programación. Exploiting this vulnerability in the parameter 'Id_usuario' in '/evaluacion_objetivos_anyo_sig_ver_auto.aspx', co…

### CVE-2026-1482
**quatuor evaluacion_de_desempeno SQL Injection**
- **Signals:** CVSS
- **Asset:** quatuor evaluacion_de_desempeno
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-10T20:19:32.393
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-27)

> An out-of-band SQL injection vulnerability (OOB SQLi) has been detected in the Performance Evaluation (EDD) application developed by Gabinete Técnico de Programación. Exploiting this vulnerability in the parameter 'Id_evaluacion' in '/evaluacion_objetivos_evalua_definido.aspx', c…

### CVE-2026-1483
**quatuor evaluacion_de_desempeno SQL Injection**
- **Signals:** CVSS
- **Asset:** quatuor evaluacion_de_desempeno
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-10T20:21:17.750
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-27)

> An out-of-band SQL injection vulnerability (OOB SQLi) has been detected in the Performance Evaluation (EDD) application developed by Gabinete Técnico de Programación. Exploiting this vulnerability in the parameter 'Id_usuario' in '/evaluacion_objetivos_ver_auto.aspx', could allow…

### CVE-2026-22039
**kyverno kyverno privilege escalation**
- **Signals:** CVSS
- **Asset:** kyverno kyverno
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T15:13:57.440
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-27)

> Kyverno is a policy engine designed for cloud native platform engineering teams. Versions prior to 1.16.3 and 1.15.3 have a critical authorization boundary bypass in namespaced Kyverno Policy apiCall. The resolved `urlPath` is executed using the Kyverno admission controller Servi…

### CVE-2026-24736
**squidex.io squidex**
- **Signals:** CVSS
- **Asset:** squidex.io squidex
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-12T21:30:02.060
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-27)

> Squidex is an open source headless content management system and content management hub. Versions of the application up to and including 7.21.0 allow users to define "Webhooks" as actions within the Rules engine. The url parameter in the webhook configuration does not appear to v…

### CVE-2026-24770
**infiniflow ragflow RCE**
- **Signals:** CVSS
- **Asset:** infiniflow ragflow
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T21:53:46.573
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-27)

> RAGFlow is an open-source RAG (Retrieval-Augmented Generation) engine. In version 0.23.1 and possibly earlier versions, the MinerU parser contains a "Zip Slip" vulnerability, allowing an attacker to overwrite arbitrary files on the server (leading to Remote Code Execution) via a …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-27*
