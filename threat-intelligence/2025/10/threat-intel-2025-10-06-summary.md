# Daily Threat Intelligence — October 06, 2025

**Digest window (UTC):** 2025-10-06
**Generated:** 2026-06-02T07:33:32Z

## Threat brief

Microsoft Windows: 4 CVEs added to CISA KEV today. · Zohocorp Manageengine Opmanager — exploitation likelihood rose sharply (EPSS 35% → 67% · rising (+32%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows: 4 CVEs added to CISA KEV today.
- Zohocorp Manageengine Opmanager — exploitation likelihood rose sharply (EPSS 35% → 67% · rising (+32%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 7 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2010-3765
**Mozilla Multiple Products Remote Code Execution Vulnerability**
- **Signals:** KEV
- **Asset:** mozilla firefox
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T14:15:57.020
- **CWE:** CWE-119
- **CWE:** CWE-119
- **Risk score:** 88
- **KEV:** added 2025-10-06

> Mozilla Firefox 3.5.x through 3.5.14 and 3.6.x through 3.6.11, Thunderbird 3.1.6 before 3.1.6 and 3.0.x before 3.0.10, and SeaMonkey 2.x before 2.0.10, when JavaScript is enabled, allows remote attackers to execute arbitrary code via vectors related to nsCSSFrameConstructor::Cont…

### CVE-2020-11946
**zohocorp manageengine_opmanager**
- **Signals:** EPSS
- **Asset:** zohocorp manageengine_opmanager
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:58:57.610
- **CWE:** CWE-306
- **Risk score:** 82
- **EPSS 35.2% (2025-03-30) → 67.0% (2025-10-06), Δ +31.8%**

> Zoho ManageEngine OpManager before 125120 allows an unauthenticated user to retrieve an API key via a servlet call.

### CVE-2025-10363
**Deserialization of Untrusted Data vulnerability in Topal Solutions AG Topal Finanzbuchhaltung on Windows allows Remote Code Execution.Thi...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-06)

> Deserialization of Untrusted Data vulnerability in Topal Solutions AG Topal Finanzbuchhaltung on Windows allows Remote Code Execution.This issue affects at least Topal Finanzbuchhaltung: 10.1.5.20 and is fixed in version 11.2.12.00

### CVE-2010-3962
**Microsoft Internet Explorer Uninitialized Memory Corruption Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft internet_explorer
- **Attack:** Memory Corruption
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T10:35:19.197
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2025-10-06

> Use-after-free vulnerability in Microsoft Internet Explorer 6, 7, and 8 allows remote attackers to execute arbitrary code via vectors related to Cascading Style Sheets (CSS) token sequences and the clip attribute, aka an "invalid flag reference" issue or "Uninitialized Memory Cor…

### CVE-2011-3402
**Microsoft Windows Remote Code Execution Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_7
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T10:36:02.440
- **Risk score:** 88
- **KEV:** added 2025-10-06

> Unspecified vulnerability in the TrueType font parsing engine in win32k.sys in the kernel-mode drivers in Microsoft Windows XP SP2 and SP3, Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2, R2, and R2 SP1, and Windows 7 Gold and SP1 allows remote attackers to e…

### CVE-2013-3918
**Microsoft Windows Out-of-Bounds Write Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_7
- **Attack:** DoS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:41:52.243
- **CWE:** CWE-787
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2025-10-06

> The InformationCardSigninHelper Class ActiveX control in icardie.dll in Microsoft Windows XP SP2 and SP3, Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold an…

### CVE-2021-22555
**Linux Kernel Heap Out-of-Bounds Write Vulnerability**
- **Signals:** KEV
- **Asset:** netapp c400_firmware
- **Attack:** Memory Corruption
- **CVSS max:** 8.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:06:32.497
- **CWE:** CWE-787
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2025-10-06

> A heap out-of-bounds write affecting Linux since v2.6.19-rc1 was discovered in net/netfilter/x_tables.c. This allows an attacker to gain privileges or cause a DoS (via heap memory corruption) through user name space

### CVE-2021-43226
**Microsoft Windows Privilege Escalation Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1507
- **Attack:** Privilege Escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T19:17:05.200
- **Risk score:** 88
- **KEV:** added 2025-10-06

> Windows Common Log File System Driver Elevation of Privilege Vulnerability

### CVE-2025-36356
**ibm security_verify_access privilege escalation**
- **Signals:** CVSS
- **Asset:** ibm security_verify_access
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-15T19:20:17.190
- **CWE:** CWE-250
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-06)

> IBM Security Verify Access and IBM Security Verify Access Docker 10.0.0.0 through 10.0.9.0 and 11.0.0.0 through 11.0.1.0 could allow a locally authenticated user to escalate their privileges to root due to execution with more privileges than required.

### CVE-2025-57247
**The BATBToken smart contract (address 0xfbf1388408670c02f0dbbb74251d8ded1d63b7a2, Compiler Version v0.8.26+commit.8a97fa7a) contains inco...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-06)

> The BATBToken smart contract (address 0xfbf1388408670c02f0dbbb74251d8ded1d63b7a2, Compiler Version v0.8.26+commit.8a97fa7a) contains incorrect access control implementation in whitelist management functions. The setColdWhiteList() and setSpecialAddress() functions in the base ERC…

### CVE-2025-57515
**A SQL injection vulnerability has been identified in Uniclare Student Portal v2.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-06)

> A SQL injection vulnerability has been identified in Uniclare Student Portal v2. This flaw allows remote attackers to inject arbitrary SQL commands via vulnerable input fields, enabling the execution of time-delay functions to infer database responses.

### CVE-2025-60957
**endruntechnologies sonoma_d12_firmware DoS**
- **Signals:** CVSS
- **Asset:** endruntechnologies sonoma_d12_firmware
- **Attack:** DoS
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-10T16:36:14.710
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-10-06)

> OS Command Injection vulnerability in EndRun Technologies Sonoma D12 Network Time Server (GPS) F/W 6010-0071-000 Ver 4.00 allows attackers to execute arbitrary code, cause a denial of service, gain escalated privileges, and gain sensitive information.

### CVE-2025-60964
**endruntechnologies sonoma_d12_firmware DoS**
- **Signals:** CVSS
- **Asset:** endruntechnologies sonoma_d12_firmware
- **Attack:** DoS
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-10T16:14:44.910
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-06)

> OS Command Injection vulnerability in EndRun Technologies Sonoma D12 Network Time Server (GPS) F/W 6010-0071-000 Ver 4.00 allows attackers to execute arbitrary code, cause a denial of service, gain escalated privileges, gain sensitive information, and possibly other unspecified i…

### CVE-2025-60965
**endruntechnologies sonoma_d12_firmware DoS**
- **Signals:** CVSS
- **Asset:** endruntechnologies sonoma_d12_firmware
- **Attack:** DoS
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-10T16:14:55.330
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-06)

> OS Command Injection vulnerability in EndRun Technologies Sonoma D12 Network Time Server (GPS) F/W 6010-0071-000 Ver 4.00 allows attackers to execute arbitrary code, cause a denial of service, gain escalated privileges, gain sensitive information, and possibly other unspecified i…

### CVE-2025-61774
**PyVista provides 3D plotting and mesh analysis through an interface for the Visualization Toolkit (VTK).**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-06)

> PyVista provides 3D plotting and mesh analysis through an interface for the Visualization Toolkit (VTK). Version 0.46.3 of the PyVista Project is vulnerable to remote code execution via dependency confusion. Two pieces of code use`--extra-index-url`. But when `--extra-index-url` …

### CVE-2025-61777
**flagforge flagforge privilege escalation**
- **Signals:** CVSS
- **Asset:** flagforge flagforge
- **Attack:** privilege escalation
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T13:53:37.307
- **CWE:** CWE-200
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-06)

> Flag Forge is a Capture The Flag (CTF) platform. Starting in version 2.0.0 and prior to version 2.3.2, the `/api/admin/badge-templates` (GET) and `/api/admin/badge-templates/create` (POST) endpoints previously allowed access without authentication or authorization. This could hav…

### CVE-2025-61778
**Akka.NET is a .NET port of the Akka project from the Scala / Java community.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-290
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-06)

> Akka.NET is a .NET port of the Akka project from the Scala / Java community. In all versions of Akka.Remote from v1.2.0 to v1.5.51, TLS could be enabled via our `akka.remote.dot-netty.tcp` transport and this would correctly enforce private key validation on the server-side of inb…

### CVE-2025-61882
**Oracle E-Business Suite Unspecified Vulnerability**
- **Signals:** KEV
- **Asset:** oracle concurrent_processing
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:08:52.230
- **CWE:** CWE-287
- **Risk score:** 88
- **KEV:** added 2025-10-06

> Vulnerability in the Oracle Concurrent Processing product of Oracle E-Business Suite (component: BI Publisher Integration).  Supported versions that are affected are 12.2.3-12.2.14. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to c…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-06*
