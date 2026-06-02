# Daily Threat Intelligence — August 12, 2025

**Digest window (UTC):** 2025-08-12
**Generated:** 2026-06-02T07:33:13Z

## Threat brief

Microsoft Internet Explorer: 2 CVEs added to CISA KEV today. · Archive Zip Antivirus Engine — exploitation likelihood rose sharply (EPSS 14% → 40% · rising (+26%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Internet Explorer: 2 CVEs added to CISA KEV today.
- Archive Zip Antivirus Engine — exploitation likelihood rose sharply (EPSS 14% → 40% · rising (+26%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 3 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2007-0671
**Microsoft Office Excel Remote Code Execution Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft access
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T13:52:33.260
- **Risk score:** 88
- **KEV:** added 2025-08-12

> Unspecified vulnerability in Microsoft Excel 2000, XP, 2003, and 2004 for Mac, and possibly other Office products, allows remote user-assisted attackers to execute arbitrary code via unknown attack vectors, as demonstrated by Exploit-MSExcel.h in targeted zero-day attacks.

### CVE-2004-0934
**archive_zip antivirus_engine**
- **Signals:** EPSS
- **Asset:** archive_zip archive_zip
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 14.2% (2025-03-30) → 39.9% (2025-08-12), Δ +25.8%**

> Kaspersky 3.x to 4.x allows remote attackers to bypass antivirus protection via a compressed file with both local and global headers set to zero, which does not prevent the compressed file from being opened on a target system.

### CVE-2025-55169
**wegia wegia Path Traversal**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** Path Traversal
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T01:30:59.277
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-12)

> WeGIA is an open source web manager with a focus on the Portuguese language and charitable institutions. Prior to version 3.4.8, a path traversal vulnerability was discovered in the WeGIA application, html/socio/sistema/download_remessa.php endpoint. This vulnerability could allo…

### CVE-2013-3893
**Microsoft Internet Explorer Resource Management Errors Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft internet_explorer
- **Attack:** Use-After-Free
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:46:27.067
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2025-08-12

> Use-after-free vulnerability in the SetMouseCapture implementation in mshtml.dll in Microsoft Internet Explorer 6 through 11 allows remote attackers to execute arbitrary code via crafted JavaScript strings, as demonstrated by use of an ms-help: URL that triggers loading of hxds.d…

### CVE-2020-26566
**motion_project motion DoS**
- **Signals:** EPSS
- **Asset:** motion_project motion
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:20:05.790
- **CWE:** CWE-125
- **Risk score:** 80
- **EPSS 1.7% (2025-03-30) → 12.0% (2025-08-12), Δ +10.3%**

> A Denial of Service condition in Motion-Project Motion 3.2 through 4.3.1 allows remote unauthenticated users to cause a webu.c segmentation fault and kill the main process via a crafted HTTP request.

### CVE-2025-24325
**Improper input validation in the Linux kernel-mode driver for some Intel(R) 800 Series Ethernet before version 1.17.2 may allow an authen...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-12)

> Improper input validation in the Linux kernel-mode driver for some Intel(R) 800 Series Ethernet before version 1.17.2 may allow an authenticated user to potentially enable escalation of privilege via local access.

### CVE-2025-25256
**fortinet fortisiem Command Injection**
- **Signals:** CVSS
- **Asset:** fortinet fortisiem
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-08-15T18:15:27.583
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-12)

> An improper neutralization of special elements used in an OS command ('OS Command Injection') vulnerability [CWE-78] in Fortinet FortiSIEM version 7.3.0 through 7.3.1, 7.2.0 through 7.2.5, 7.1.0 through 7.1.7, 7.0.0 through 7.0.3 and before 6.7.9 allows an unauthenticated attacke…

### CVE-2025-49457
**zoom meeting_software_development_kit privilege escalation**
- **Signals:** CVSS
- **Asset:** zoom meeting_software_development_kit
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-08T15:44:28.283
- **CWE:** CWE-426
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-08-12)

> Untrusted search path in certain Zoom Clients for Windows may allow an unauthenticated user to conduct an escalation of privilege via network access

### CVE-2025-50165
**microsoft windows_11_24h2**
- **Signals:** CVSS
- **Asset:** microsoft windows_11_24h2
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T17:05:02.893
- **CWE:** CWE-822
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-12)

> Untrusted pointer dereference in Microsoft Graphics Component allows an unauthorized attacker to execute code over a network.

### CVE-2025-50171
**microsoft windows_server_2022 privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft windows_server_2022
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T17:06:56.290
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-12)

> Missing authorization in Remote Desktop Server allows an unauthorized attacker to perform spoofing over a network.

### CVE-2025-53766
**microsoft office Buffer Overflow**
- **Signals:** CVSS
- **Asset:** microsoft office
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T17:11:06.503
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-12)

> Heap-based buffer overflow in Windows GDI+ allows an unauthorized attacker to execute code over a network.

### CVE-2025-55010
**kanboard kanboard Deserialization**
- **Signals:** CVSS
- **Asset:** kanboard kanboard
- **Attack:** Deserialization
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-22T17:28:18.667
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-12)

> Kanboard is project management software that focuses on the Kanban methodology. Prior to version 1.2.47, an unsafe deserialization vulnerability in the ProjectEventActvityFormatter allows admin users the ability to instantiate arbitrary php objects by modifying the event["data"] …

### CVE-2025-55167
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-18T15:36:00.293
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-12)

> WeGIA is an open source web manager with a focus on the Portuguese language and charitable institutions. Prior to version 3.4.8, a SQL Injection vulnerability was identified in the /html/funcionario/dependente_remover.php endpoint, specifically in the id_dependente parameter. Thi…

### CVE-2025-55168
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T01:30:09.880
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-12)

> WeGIA is an open source web manager with a focus on the Portuguese language and charitable institutions. Prior to version 3.4.8, a SQL Injection vulnerability was identified in the /html/saude/aplicar_medicamento.php endpoint, specifically in the id_fichamedica parameter. This vu…

### CVE-2025-8088
**RARLAB WinRAR Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** rarlab winrar
- **Attack:** Path Traversal
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T15:50:59.680
- **CWE:** CWE-35
- **Risk score:** 88
- **KEV:** added 2025-08-12

> A path traversal vulnerability affecting the Windows version of WinRAR allows the attackers to execute arbitrary code by crafting malicious archive files. This vulnerability was exploited in the wild and was discovered by Anton Cherepanov, Peter Košinár, and Peter Strýček
     fr…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-12*
