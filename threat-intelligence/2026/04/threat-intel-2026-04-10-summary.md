# Daily Threat Intelligence — April 10, 2026

**Digest window (UTC):** 2026-04-10
**Generated:** 2026-06-02T07:34:53Z

## Threat brief

Unquoted Search Path or Element vulnerability in NetBT Consulting Services Inc.: public exploit or PoC linked · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Unquoted Search Path or Element vulnerability in NetBT Consulting Services Inc.: public exploit or PoC linked
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 1 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2025-14018
**Unquoted Search Path or Element vulnerability in NetBT Consulting Services Inc.**
- **Signals:** EXP
- **CVSS max:** 7.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-428
- **Risk score:** 78
- **EXP:** ref published 2026-04-10

> Unquoted Search Path or Element vulnerability in NetBT Consulting Services Inc. E-Fatura allows Leveraging/Manipulating Configuration File Search Paths, Redirect Access to Libraries.This issue affects e-Fatura: before 1.2.15.

### CVE-2026-36234
**itsourcecode online_student_enrollment_system SQL Injection**
- **Signals:** CVSS
- **Asset:** itsourcecode online_student_enrollment_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T17:40:46.070
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-10)

> itsourcecode Online Student Enrollment System v1.0 is vulnerable to SQL Injection in newCourse.php via the 'coursename' parameter.

### CVE-2026-36235
**itsourcecode online_student_enrollment_system SQL Injection**
- **Signals:** CVSS
- **Asset:** itsourcecode online_student_enrollment_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T17:40:30.570
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-10)

> A SQL injection vulnerability was found in the scheduleSubList.php file of itsourcecode Online Student Enrollment System v1.0. The reason for this issue is that the 'subjcode' parameter is directly embedded into the SQL query via string interpolation without any sanitization or v…

### CVE-2026-23781
**bmc control-m\/managed_file_transfer**
- **Signals:** CVSS
- **Asset:** bmc control-m\/managed_file_transfer
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T19:11:38.623
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-10)

> An issue was discovered in BMC Control-M/MFT 9.0.20 through 9.0.22. A set of default debug user credentials is hardcoded in cleartext within the application package. If left unchanged, these credentials can be easily obtained and may allow unauthorized access to the MFT API debug…

### CVE-2026-32892
**chamilo chamilo_lms Command Injection**
- **Signals:** CVSS
- **Asset:** chamilo chamilo_lms
- **Attack:** Command Injection
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-17T21:30:50.533
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-10)

> Chamilo LMS is a learning management system. Prior to 1.11.38 and 2.0.0-RC.3, Chamilo LMS contains an OS Command Injection vulnerability in the file move function. The move() function in fileManage.lib.php passes user-controlled path values directly into exec() shell commands wit…

### CVE-2026-33698
**chamilo chamilo_lms**
- **Signals:** CVSS
- **Asset:** chamilo chamilo_lms
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-16T18:48:33.323
- **CWE:** CWE-552
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-10)

> Chamilo LMS is a learning management system. Prior to 1.11.38, a chained attack can enable otherwise-blocked PHP code from the main/install/ directory and allow an unauthenticated attacker to modify existing files or create new files where allowed by system permissions. This only…

### CVE-2026-33707
**chamilo chamilo_lms**
- **Signals:** CVSS
- **Asset:** chamilo chamilo_lms
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-16T18:25:38.720
- **CWE:** CWE-640
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-10)

> Chamilo LMS is a learning management system. Prior to 1.11.38 and 2.0.0-RC.3, the default password reset mechanism generates tokens using sha1($email) with no random component, no expiration, and no rate limiting. An attacker who knows a user's email can compute the reset token a…

### CVE-2026-36236
**janobe engineers_online_portal SQL Injection**
- **Signals:** CVSS
- **Asset:** janobe engineers_online_portal
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T17:42:10.680
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-10)

> SourceCodester Engineers Online Portal v1.0 is vulnerable to SQL Injection in update_password.php via the new_password parameter.

### CVE-2026-40157
**praison praisonai**
- **Signals:** CVSS
- **Asset:** praison praisonai
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T15:07:36.003
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-10)

> PraisonAI is a multi-agent teams system. Prior to 4.5.128, cmd_unpack in the recipe CLI extracts .praison tar archives using raw tar.extract() without validating archive member paths. A .praison bundle containing ../../ entries will write files outside the intended output directo…

### CVE-2026-40177
**ajenti ajenti_plugin_core**
- **Signals:** CVSS
- **Asset:** ajenti ajenti_plugin_core
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T19:31:16.883
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-10)

> ajenti.plugin.core defines all necessary core elements to allow Ajenti to run properly. Prior to 0.112, if the 2FA was activated, it was possible to bypass the password authentication This vulnerability is fixed in 0.112.

### CVE-2026-40189
**goshs goshs privilege escalation**
- **Signals:** CVSS
- **Asset:** goshs goshs
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T20:08:54.533
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-10)

> goshs is a SimpleHTTPServer written in Go. Prior to 2.0.0-beta.4, goshs enforces the documented per-folder .goshs ACL/basic-auth mechanism for directory listings and file reads, but it does not enforce the same authorization checks for state-changing routes. An unauthenticated at…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-10*
