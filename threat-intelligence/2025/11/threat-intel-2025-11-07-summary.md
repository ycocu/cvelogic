# Daily Threat Intelligence — November 07, 2025

**Digest window (UTC):** 2025-11-07
**Generated:** 2026-06-02T07:33:44Z

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

### CVE-2025-63689
**ycf1998 money-pos SQL Injection**
- **Signals:** CVSS
- **Asset:** ycf1998 money-pos
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-05T16:25:52.370
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-07)

> Multiple SQL injection vulnerabilitites in ycf1998 money-pos system before commit 11f276bd20a41f089298d804e43cb1c39d041e59 (2025-09-14) allows a remote attacker to execute arbitrary code via the orderby parameter

### CVE-2025-10230
**A flaw was found in Samba, in the front-end WINS hook handling: NetBIOS names from registration packets are passed to a shell without pro...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-07)

> A flaw was found in Samba, in the front-end WINS hook handling: NetBIOS names from registration packets are passed to a shell without proper validation or escaping. Unsanitized NetBIOS name data from WINS registration packets are inserted into a shell command and executed by the …

### CVE-2025-12352
**The Gravity Forms plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the copy_post_image...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-07)

> The Gravity Forms plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the copy_post_image() function in all versions up to, and including, 2.9.20. This makes it possible for unauthenticated attackers to upload arbitrary files on the…

### CVE-2020-36870
**Various Ruijie Gateway EG and NBR models firmware versions 11.1(6)B9P1 < 11.9(4)B12P1 contain a code execution vulnerability in the EWEB...**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-11-07)

> Various Ruijie Gateway EG and NBR models firmware versions 11.1(6)B9P1 < 11.9(4)B12P1 contain a code execution vulnerability in the EWEB management system that can be abused via front-end functionality. Attackers can exploit front-end code when features such as guest authenticati…

### CVE-2025-10870
**SQL injection vulnerability in DIAL's CentrosNet v2.64.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-07)

> SQL injection vulnerability in DIAL's CentrosNet v2.64. Allows an attacker to retrieve, create, update, and delete databases by sending POST and GET requests with the 'ultralogin' parameter in '/centrosnet/ultralogin.php'.

### CVE-2025-3222
**Improper Authentication vulnerability in GE Vernova Smallworld on Windows, Linux allows Authentication Abuse.This issue affects Smallworl...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-07)

> Improper Authentication vulnerability in GE Vernova Smallworld on Windows, Linux allows Authentication Abuse.This issue affects Smallworld: 5.3.3 and prior versions for Linux, and 5.3.4. and prior versions for Windows.

### CVE-2025-34299
**monstaftp monsta_ftp**
- **Signals:** CVSS
- **Asset:** monstaftp monsta_ftp
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T19:50:13.557
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-07)

> Monsta FTP versions 2.11 and earlier contain a vulnerability that allows unauthenticated arbitrary file uploads. This flaw enables attackers to execute arbitrary code by uploading a specially crafted file from a malicious (S)FTP server.

### CVE-2025-52425
**qnap qumagie SQL Injection**
- **Signals:** CVSS
- **Asset:** qnap qumagie
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-14T20:12:47.743
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-11-07)

> An SQL injection vulnerability has been reported to affect QuMagie. A remote attacker can exploit the vulnerability to execute unauthorized code or commands.

We have already fixed the vulnerability in the following versions:
QuMagie 2.7.0 and later

### CVE-2025-63690
**pig4cloud pig**
- **Signals:** CVSS
- **Asset:** pig4cloud pig
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-08T16:10:04.333
- **CWE:** CWE-470
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-07)

> In pig-mesh Pig versions 3.8.2 and below, when setting up scheduled tasks in the Quartz management function under the system management module, it is possible to execute any Java class with a parameterless constructor and its methods with parameter type String through reflection.…

### CVE-2025-63691
**pig4cloud pig**
- **Signals:** CVSS
- **Asset:** pig4cloud pig
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-08T16:08:59.600
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-11-07)

> In pig-mesh In Pig version 3.8.2 and below, within the Token Management function under the System Management module, the token query interface (/api/admin/sys-token/page) has an improper permission verification issue, which leads to information leakage. This interface can be call…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-07*
