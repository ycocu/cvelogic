# Daily Threat Intelligence — December 02, 2025

**Digest window (UTC):** 2025-12-02
**Generated:** 2026-06-02T07:33:54Z

## Threat brief

Android Framework: 2 CVEs added to CISA KEV today. · Phpipam: public exploit or PoC linked (cross-site scripting) · Christos Zoulas File 1 — exploitation likelihood rose sharply (EPSS 5.9% → 21% · rising (+15%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Android Framework: 2 CVEs added to CISA KEV today.
- Phpipam: public exploit or PoC linked (cross-site scripting)
- Christos Zoulas File 1 — exploitation likelihood rose sharply (EPSS 5.9% → 21% · rising (+15%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 6 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **21** |


## CVEs

### CVE-2025-48572
**Android Framework Privilege Escalation Vulnerability**
- **Signals:** KEV
- **Asset:** google android
- **Attack:** Privilege Escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T02:00:02.557
- **CWE:** CWE-306
- **Risk score:** 88
- **KEV:** added 2025-12-02

> In multiple locations, there is a possible way to launch activities from the background due to a permissions bypass. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2022-0088
**yourls yourls CSRF**
- **Signals:** EXP
- **Asset:** yourls yourls
- **Attack:** CSRF
- **CVSS max:** 7.4
- **NVD status:** Modified
- **NVD modified:** 2026-02-16T15:18:32.940
- **CWE:** CWE-352
- **Risk score:** 78
- **EXP:** ref published 2025-12-02

> Cross-Site Request Forgery (CSRF) in GitHub repository yourls/yourls prior to 1.8.3.

### CVE-2003-1092
**christos_zoulas file_1**
- **Signals:** EPSS
- **Asset:** christos_zoulas file_1
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 5.9% (2025-03-30) → 20.8% (2025-12-02), Δ +14.9%**

> Unknown vulnerability in the "Automatic File Content Type Recognition (AFCTR) Tool version of the file package before 3.41, related to "a memory allocation problem," has unknown impact.

### CVE-2008-1769
**videolan vlc DoS**
- **Signals:** EPSS
- **Asset:** videolan vlc
- **Attack:** DoS
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-399
- **Risk score:** 81
- **EPSS 14.1% (2025-06-14) → 26.6% (2025-12-02), Δ +12.6%**

> VLC before 0.8.6f allow remote attackers to cause a denial of service (crash) via a crafted Cinepak file that triggers an out-of-bounds array access and memory corruption.

### CVE-2008-1881
**videolan vlc Buffer Overflow**
- **Signals:** EPSS
- **Asset:** videolan vlc
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 79
- **EPSS 43.0% (2025-03-30) → 54.0% (2025-12-02), Δ +11.0%**

> Stack-based buffer overflow in the ParseSSA function (modules/demux/subtitle.c) in VLC 0.8.6e allows remote attackers to execute arbitrary code via a long subtitle in an SSA file.  NOTE: this issue is due to an incomplete fix for CVE-2007-6681.

### CVE-2022-3766
**phpmyfaq phpmyfaq XSS**
- **Signals:** EXP
- **Asset:** phpmyfaq phpmyfaq
- **Attack:** XSS
- **CVSS max:** 7.3
- **NVD status:** Modified
- **NVD modified:** 2026-02-16T15:18:33.647
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-12-02

> Cross-site Scripting (XSS) - Reflected in GitHub repository thorsten/phpmyfaq prior to 3.1.8.

### CVE-2023-1211
**phpipam phpipam SQL Injection**
- **Signals:** EXP
- **Asset:** phpipam phpipam
- **Attack:** SQL Injection
- **CVSS max:** 7.2
- **NVD status:** Modified
- **NVD modified:** 2026-02-16T15:18:33.927
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-12-02

> SQL Injection in GitHub repository phpipam/phpipam prior to v1.5.2.

### CVE-2023-33362
**piwigo piwigo SQL Injection**
- **Signals:** EXP
- **Asset:** piwigo piwigo
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T14:15:22.500
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-12-02

> Piwigo 13.6.0 is vulnerable to SQL Injection via in the "profile" function.

### CVE-2024-41357
**phpipam phpipam cross-site scripting**
- **Signals:** EXP
- **Asset:** phpipam phpipam
- **Attack:** cross-site scripting
- **CVSS max:** 7.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-04-23T18:34:02.137
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-12-02

> phpipam 1.6 is vulnerable to Cross Site Scripting (XSS) via /app/admin/powerDNS/record-edit.php.

### CVE-2024-41358
**phpipam phpipam cross-site scripting**
- **Signals:** EXP
- **Asset:** phpipam phpipam
- **Attack:** cross-site scripting
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2026-01-26T16:15:57.223
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-12-02

> phpipam 1.6 is vulnerable to Cross Site Scripting (XSS) via app\admin\import-export\import-load-data.php.

### CVE-2025-13510
**The Iskra iHUB and iHUB Lite smart metering gateway exposes its web management interface without requiring authentication, allowing unaut...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-02)

> The Iskra iHUB and iHUB Lite smart metering gateway exposes its web management interface without requiring authentication, allowing unauthenticated users to access and modify critical device settings.

### CVE-2025-13542
**The DesignThemes LMS plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.0.4.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-02)

> The DesignThemes LMS plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.0.4. This is due to the 'dtlms_register_user_front_end' function not restricting what user roles a user can register with. This makes it possible for unauthenti…

### CVE-2025-13658
**privilege escalation**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-02)

> A vulnerability in Longwatch devices allows unauthenticated HTTP GET requests to execute arbitrary code via an exposed endpoint, due to the absence of code signing and execution controls. Exploitation results in SYSTEM-level privileges.

### CVE-2025-13828
**SummaryA non privileged user can install and remove arbitrary packages via composer for a composer based installed, even if the flag in u...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-12-02)

> SummaryA non privileged user can install and remove arbitrary packages via composer for a composer based installed, even if the flag in update settings for enable composer based update is unticked.

ImpactA low-privileged user of the platform can install malicious code to obtain …

### CVE-2025-48633
**Android Framework Information Disclosure Vulnerability**
- **Signals:** KEV
- **Asset:** google android
- **Attack:** Info Disclosure
- **CVSS max:** 5.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T02:00:02.557
- **Risk score:** 88
- **KEV:** added 2025-12-02

> In hasAccountsOnAnyUser of DevicePolicyManagerService.java, there is a possible way to add a Device Owner after provisioning due to a logic error in the code. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not …

### CVE-2025-58386
**terminalfour terminalfour privilege escalation**
- **Signals:** CVSS
- **Asset:** terminalfour terminalfour
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T18:27:13.727
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-02)

> In Terminalfour 8 through 8.4.1.1, the userLevel parameter in the user management function is not subject to proper server-side authorization checks. A Power User can intercept and modify this parameter to assign the Administrator role to other existing lower-privileged accounts,…

### CVE-2025-60736
**anisha online_medicine_guide SQL Injection**
- **Signals:** CVSS
- **Asset:** anisha online_medicine_guide
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-05T18:56:40.780
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-02)

> code-projects Online Medicine Guide 1.0 is vulnerable to SQL Injection in /login.php via the upass parameter.

### CVE-2025-60854
**dlink r15_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** dlink r15_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-06T00:00:26.173
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-02)

> A vulnerability has been found in D-Link R15 (AX1500) 1.20.01 and below. By manipulating the model name parameter during a password change request in the web administrator page, it is possible to trigger a command injection in httpd.

### CVE-2025-65358
**hashenudara edoc-doctor-appointment-system SQL Injection**
- **Signals:** CVSS
- **Asset:** hashenudara edoc-doctor-appointment-system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-03T20:22:29.533
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-02)

> Edoc-doctor-appointment-system v1.0.1 was discovered to contain SQl injection vulnerability via the 'docid' parameter at /admin/appointment.php.

### CVE-2025-65656
**dcatadmin dcat_admin**
- **Signals:** CVSS
- **Asset:** dcatadmin dcat_admin
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-03T18:19:43.993
- **CWE:** CWE-98
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-02)

> dcat-admin v2.2.3-beta and before is vulnerable to file inclusion in admin/src/Extend/VersionManager.php.

### CVE-2025-65896
**long2ice asyncmy SQL Injection**
- **Signals:** CVSS
- **Asset:** long2ice asyncmy
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T18:23:23.187
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-02)

> SQL injection vulnerability in long2ice assyncmy thru 0.2.10 allows attackers to execute arbitrary SQL commands via crafted dict keys.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-02*
