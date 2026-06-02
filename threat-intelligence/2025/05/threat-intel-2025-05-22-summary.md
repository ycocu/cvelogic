# Daily Threat Intelligence — May 22, 2025

**Digest window (UTC):** 2025-05-22
**Generated:** 2026-06-02T07:32:45Z

## Threat brief

Samsung MagicINFO 9 Server added to CISA KEV — confirmed in-the-wild exploitation. · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Samsung MagicINFO 9 Server added to CISA KEV — confirmed in-the-wild exploitation.
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-4632
**Samsung MagicINFO 9 Server Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** samsung magicinfo_9_server
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-03T18:58:05.080
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2025-05-22

> Improper limitation of a pathname to a restricted directory vulnerability in Samsung MagicINFO 9 Server version before 21.1052 allows attackers to write arbitrary file as system authority.

### CVE-2024-41195
**ocuco innovation privilege escalation**
- **Signals:** CVSS
- **Asset:** ocuco innovation
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-30T01:16:38.953
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-22)

> An issue in Ocuco Innovation - INNOVASERVICEINTF.EXE v2.10.24.17 allows attackers to bypass authentication and escalate privileges to Administrator via a crafted TCP packet.

### CVE-2024-41196
**ocuco innovation privilege escalation**
- **Signals:** CVSS
- **Asset:** ocuco innovation
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-30T01:16:32.857
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-22)

> An issue in Ocuco Innovation - REPORTSERVER.EXE v2.10.24.13 allows attackers to bypass authentication and escalate privileges to Administrator via a crafted TCP packet.

### CVE-2024-13955
**2nd Order SQL injection vulnerabilities in ASPECT allow unintended access and manipulation of database repositories if administrator cred...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-05-22)

> 2nd Order SQL injection vulnerabilities in ASPECT allow unintended access and manipulation of database repositories if administrator credentials become compromised.This issue affects ASPECT-Enterprise: through 3.*; NEXUS Series: through 3.*; MATRIX Series: through 3.*.

### CVE-2024-41197
**ocuco innovation privilege escalation**
- **Signals:** CVSS
- **Asset:** ocuco innovation
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-30T01:15:41.757
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-22)

> An issue in Ocuco Innovation - INVCLIENT.EXE v2.10.24.5 allows attackers to bypass authentication and escalate privileges to Administrator via a crafted TCP packet.

### CVE-2024-41198
**ocuco innovation privilege escalation**
- **Signals:** CVSS
- **Asset:** ocuco innovation
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-30T01:15:33.680
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-22)

> An issue in Ocuco Innovation - REPORTS.EXE v2.10.24.13 allows attackers to bypass authentication and escalate privileges to Administrator via a crafted TCP packet.

### CVE-2024-48853
**An escalation of privilege vulnerability in ASPECT could provide an attacker root access to a server when logged in as a "non" root ASPEC...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-286
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-05-22)

> An escalation of privilege vulnerability in ASPECT could provide an attacker root access to a server when logged in as a "non" root ASPECT user. This issue affects ASPECT-Enterprise: through 3.08.03; NEXUS Series: through 3.08.03; MATRIX Series: through 3.08.03.

### CVE-2024-6914
**wso2 api_manager privilege escalation**
- **Signals:** CVSS
- **Asset:** wso2 api_manager
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-06T13:56:53.380
- **CWE:** CWE-863
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-22)

> An incorrect authorization vulnerability exists in multiple WSO2 products due to a business logic flaw in the account recovery-related SOAP admin service. A malicious actor can exploit this vulnerability to reset the password of any user account, leading to a complete account tak…

### CVE-2025-32814
**infoblox netmri SQL Injection**
- **Signals:** CVSS
- **Asset:** infoblox netmri
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-03T12:59:57.153
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-22)

> An issue was discovered in Infoblox NETMRI before 7.6.1. Unauthenticated SQL Injection can occur.

### CVE-2025-3484
**meddream pacs_server RCE**
- **Signals:** CVSS
- **Asset:** meddream pacs_server
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-11T14:39:05.253
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-22)

> MedDream PACS Server DICOM File Parsing Stack-based Buffer Overflow Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of MedDream PACS Server. Authentication is not required to exploit this vulnerab…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-22*
