# Daily Threat Intelligence — March 03, 2026

**Digest window (UTC):** 2026-03-03
**Generated:** 2026-06-02T07:34:33Z

## Threat brief

Qualcomm Multiple Chipsets added to CISA KEV — confirmed in-the-wild exploitation. · Wegia: public exploit or PoC linked (SQL Injection) · Vtiger Crm — exploitation likelihood rose sharply (EPSS 18% → 36% · rising (+19%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Qualcomm Multiple Chipsets added to CISA KEV — confirmed in-the-wild exploitation.
- Wegia: public exploit or PoC linked (SQL Injection)
- Vtiger Crm — exploitation likelihood rose sharply (EPSS 18% → 36% · rising (+19%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 4 |
| EPSS rise | 8 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **24** |


## CVEs

### CVE-2026-21385
**Qualcomm Multiple Chipsets Memory Corruption Vulnerability**
- **Signals:** KEV
- **Asset:** qualcomm sm7675p_firmware
- **Attack:** Memory Corruption
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T18:13:00.207
- **CWE:** CWE-190
- **Risk score:** 88
- **KEV:** added 2026-03-03

> Memory corruption while using alignments for memory allocation.

### CVE-2023-6553
**backupbliss backup_migration RCE**
- **Signals:** EXP
- **Asset:** backupbliss backup_migration
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-08T18:18:37.693
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2026-03-03

> The Backup Migration plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 1.3.7 via the /includes/backup-heart.php file. This is due to an attacker being able to control the values passed to an include, and subsequently leverage that t…

### CVE-2011-4670
**vtiger vtiger_crm XSS**
- **Signals:** EPSS
- **Asset:** vtiger vtiger_crm
- **Attack:** XSS
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-79
- **Risk score:** 77
- **EPSS 17.5% (2025-10-23) → 36.2% (2026-03-03), Δ +18.6%**

> Multiple cross-site scripting (XSS) vulnerabilities in vTiger CRM 5.2.1 and earlier allow remote attackers to inject arbitrary web script or HTML via the (1) viewname parameter in a CalendarAjax action, (2) activity_mode parameter in a DetailView action, (3) contact_id and (4) pa…

### CVE-2013-3846
**microsoft internet_explorer DoS**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **Attack:** DoS
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-399
- **Risk score:** 85
- **EPSS 54.0% (2025-10-18) → 66.8% (2026-03-03), Δ +12.9%**

> Use-after-free vulnerability in Microsoft Internet Explorer 9 and 10 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted CSpliceTreeEngine::InsertSplice object in an HTML document, aka "Internet Explorer Memory Corrupti…

### CVE-2013-6189
**hp application_information_optimizer**
- **Signals:** EPSS
- **Asset:** hp application_information_optimizer
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **Risk score:** 84
- **EPSS 42.8% (2025-03-30) → 53.7% (2026-03-03), Δ +10.9%**

> Unspecified vulnerability in the Archive Query Server in HP Application Information Optimizer (formerly HP Database Archiving) 6.2, 6.3, 6.4, and 7.0 allows remote attackers to execute arbitrary code via unknown vectors, aka ZDI-CAN-1666.

### CVE-2014-4060
**microsoft windows_media_center Use-After-Free**
- **Signals:** EPSS
- **Asset:** microsoft windows_media_center
- **Attack:** Use-After-Free
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-416
- **Risk score:** 80
- **EPSS 16.0% (2025-03-23) → 27.7% (2026-03-03), Δ +11.7%**

> Use-after-free vulnerability in MCPlayer.dll in Microsoft Windows Media Center TV Pack for Windows Vista, Windows 7 SP1, and Windows Media Center for Windows 8 and 8.1 allows remote attackers to execute arbitrary code via a crafted Office document that triggers deletion of a CSyn…

### CVE-2014-9390
**apple egit**
- **Signals:** EPSS
- **Asset:** git-scm git
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T02:20:45.663
- **CWE:** CWE-20
- **Risk score:** 86
- **EPSS 60.0% (2025-12-05) → 77.2% (2026-03-03), Δ +17.2%**

> Git before 1.8.5.6, 1.9.x before 1.9.5, 2.0.x before 2.0.5, 2.1.x before 2.1.4, and 2.2.x before 2.2.1 on Windows and OS X; Mercurial before 3.2.3 on Windows and OS X; Apple Xcode before 6.2 beta 3; mine all versions before 08-12-2014; libgit2 all versions up to 0.21.2; Egit all …

### CVE-2015-6023
**netcommwireless hspa_3g10wve_firmware**
- **Signals:** EPSS
- **Asset:** netcommwireless hspa_3g10wve_firmware
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-284
- **Risk score:** 82
- **EPSS 5.0% (2025-04-09) → 21.6% (2026-03-03), Δ +16.5%**

> ping.cgi in NetCommWireless HSPA 3G10WVE wireless routers with firmware before 3G10WVE-L101-S306ETS-C01_R05 allows remote attackers to bypass intended access restrictions via a direct request.  NOTE: this issue can be combined with CVE-2015-6024 to execute arbitrary commands.

### CVE-2017-12965
**apache2triad apache2triad**
- **Signals:** EPSS
- **Asset:** apache2triad apache2triad
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-384
- **Risk score:** 86
- **EPSS 7.5% (2025-03-30) → 22.2% (2026-03-03), Δ +14.8%**

> Session fixation vulnerability in Apache2Triad 1.5.4 allows remote attackers to hijack web sessions via the PHPSESSID parameter.

### CVE-2021-27886
**docker_dashboard_project docker_dashboard Command Injection**
- **Signals:** EPSS
- **Asset:** docker_dashboard_project docker_dashboard
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:58:41.943
- **CWE:** CWE-78
- **Risk score:** 86
- **EPSS 4.1% (2025-11-21) → 22.4% (2026-03-03), Δ +18.3%**

> rakibtg Docker Dashboard before 2021-02-28 allows command injection in backend/utilities/terminal.js via shell metacharacters in the command parameter of an API request. NOTE: this is NOT a Docker, Inc. product.

### CVE-2023-3643
**carel boss_mini_firmware**
- **Signals:** EXP
- **Asset:** carel boss_mini_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:17:44.260
- **CWE:** CWE-73
- **Risk score:** 78
- **EXP:** ref published 2026-03-03

> A vulnerability was found in Boss Mini 1.4.0 Build 6221. It has been classified as critical. This affects an unknown part of the file boss/servlet/document. The manipulation of the argument path leads to file inclusion. It is possible to initiate the attack remotely. The exploit …

### CVE-2025-25198
**mailcow mailcow:_dockerized**
- **Signals:** EXP
- **Asset:** mailcow mailcow\
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-01T17:39:39.557
- **CWE:** CWE-601
- **Risk score:** 78
- **EXP:** ref published 2026-03-03

> mailcow: dockerized is an open source groupware/email suite based on docker. Prior to version 2025-01a, a vulnerability in mailcow's password reset functionality allows an attacker to manipulate the `Host HTTP` header to generate a password reset link pointing to an attacker-cont…

### CVE-2025-62360
**wegia wegia SQL Injection**
- **Signals:** EXP
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-20T16:04:04.377
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2026-03-03

> WeGIA is an open source Web Manager for Institutions with a focus on Portuguese language users.Prior to 3.5.1, a SQL Injection vulnerability was identified in the /html/funcionario/dependente_documento.php endpoint, specifically in the id_dependente parameter. This vulnerability …

### CVE-2026-22719
**Broadcom VMware Aria Operations Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** vmware aria_operations
- **Attack:** RCE
- **CVSS max:** 8.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T15:08:13.743
- **CWE:** CWE-77
- **Risk score:** 88
- **KEV:** added 2026-03-03

> VMware Aria Operations contains a command injection vulnerability. A malicious unauthenticated actor may exploit this issue to execute arbitrary commands which may lead to remote code execution in VMware Aria Operations while support-assisted product migration is in progress. 

T…

### CVE-2026-25146
**open-emr openemr**
- **Signals:** CVSS
- **Asset:** open-emr openemr
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T21:56:00.543
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-03-03)

> OpenEMR is a free and open source electronic health records and medical practice management application. From 5.0.2 to before 8.0.0, there are (at least) two paths where the gateway_api_key secret value is rendered to the client in plaintext. These secret keys being leaked could …

### CVE-2026-2590
**devolutions remote_desktop_manager**
- **Signals:** CVSS
- **Asset:** devolutions remote_desktop_manager
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-10T13:16:35.887
- **CWE:** CWE-20
- **CWE:** CWE-295
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-03)

> Improper
 enforcement of the Disable password saving in vaults setting in the 
connection entry component in Devolutions Remote Desktop Manager 2025.3.30 and earlier allows an authenticated user to persist credentials in vault entries, 
potentially exposing sensitive information …

### CVE-2026-26266
**aliasvault aliasvault XSS**
- **Signals:** CVSS
- **Asset:** aliasvault aliasvault
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-05T21:22:01.810
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-03)

> AliasVault is a privacy-first password manager with built-in email aliasing. A stored cross-site scripting (XSS) vulnerability was identified in the email rendering feature of AliasVault Web Client versions 0.25.3 and lower. When viewing received emails on an alias, the HTML cont…

### CVE-2026-26279
**froxlor froxlor**
- **Signals:** CVSS
- **Asset:** froxlor froxlor
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-05T21:19:02.577
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-03)

> Froxlor is open source server administration software. Prior to 2.3.4, a typo in Froxlor's input validation code (== instead of =) completely disables email format checking for all settings fields declared as email type. This allows an authenticated admin to store arbitrary strin…

### CVE-2026-27012
**devcode openstamanager Privilege Escalation**
- **Signals:** CVSS
- **Asset:** devcode openstamanager
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-05T18:19:03.887
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-03)

> OpenSTAManager is an open source management software for technical assistance and invoicing. In 2.9.8 and earlier, a privilege escalation and authentication bypass vulnerability in OpenSTAManager allows any attacker to arbitrarily change a user's group (idgruppo) by directly call…

### CVE-2026-27971
**qwik qwik Deserialization**
- **Signals:** CVSS
- **Asset:** qwik qwik
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-05T17:57:37.233
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-03-03)

> Qwik is a performance focused javascript framework. qwik <=1.19.0 is vulnerable to RCE due to an unsafe deserialization vulnerability in the server$ RPC mechanism that allows any unauthenticated user to execute arbitrary code on the server with a single HTTP request. Affects any …

### CVE-2026-28289
**freescout freescout RCE**
- **Signals:** CVSS
- **Asset:** freescout freescout
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T19:29:44.933
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-03-03)

> FreeScout is a free help desk and shared inbox built with PHP's Laravel framework. A patch bypass vulnerability for CVE-2026-27636 in FreeScout 1.8.206 and earlier allows any authenticated user with file upload permissions to achieve Remote Code Execution (RCE) on the server by u…

### CVE-2026-3130
**devolutions devolutions_server**
- **Signals:** CVSS
- **Asset:** devolutions devolutions_server
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T20:36:33.843
- **CWE:** CWE-841
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-03)

> Improper Enforcement of Behavioral Controls in Devolutions Server 2025.3.15 and earlier allows an authenticated attacker with the delete permission to delete a PAM account that is currently checked out by selecting it alongside at least one non-checked-out account and performing …

### CVE-2026-3204
**devolutions devolutions_server**
- **Signals:** CVSS
- **Asset:** devolutions devolutions_server
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-05T15:04:34.670
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-03)

> Improper
 input validation in the error message page in Devolutions Server 2025.3.16 and earlier allows remote attackers to spoof the displayed error message via a specially crafted URL.

### CVE-2026-3224
**devolutions devolutions_server Auth Bypass**
- **Signals:** CVSS
- **Asset:** devolutions devolutions_server
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-05T15:05:49.170
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-03)

> Authentication bypass in the Microsoft Entra ID (Azure AD) authentication mode in Devolutions Server 2025.3.15.0 and earlier allows an unauthenticated user to authenticate as an arbitrary Entra ID user via a forged JSON Web Token (JWT).

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-03*
