# Daily Threat Intelligence — July 21, 2025

**Digest window (UTC):** 2025-07-21
**Generated:** 2026-06-02T07:33:05Z

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

### CVE-2025-54122
**Manager-io/Manager is accounting software.**
- **Signals:** CVSS
- **Attack:** SSRF
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-21)

> Manager-io/Manager is accounting software. A critical unauthenticated full read Server-Side Request Forgery (SSRF) vulnerability has been identified in the proxy handler component of both manager Desktop and Server edition versions up to and including 25.7.18.2519. This vulnerabi…

### CVE-2025-36846
**eveo urve_web_manager Command Injection**
- **Signals:** CVSS
- **Asset:** eveo urve_web_manager
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T17:58:47.920
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-21)

> An issue was discovered in Eveo URVE Web Manager 27.02.2025. The application exposes a /_internal/pc/vpro.php localhost endpoint to unauthenticated users that is vulnerable to OS Command Injection. The endpoint takes an input parameter that is passed directly into the shell_exec(…

### CVE-2025-44654
**linksys e2500_firmware Privilege Escalation**
- **Signals:** CVSS
- **Asset:** linksys e2500_firmware
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-02T21:03:26.243
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-21)

> In Linksys E2500 3.0.04.002, the chroot_local_user option is enabled in the vsftpd configuration file. This could lead to unauthorized access to system files, privilege escalation, or use of the compromised server as a pivot point for internal network attacks.

### CVE-2020-26799
**A reflected cross-site scripting (XSS) vulnerability was discovered in index.php on Luxcal 4.5.2 which allows an unauthenticated attacker...**
- **Signals:** CVSS
- **Attack:** XSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-21)

> A reflected cross-site scripting (XSS) vulnerability was discovered in index.php on Luxcal 4.5.2 which allows an unauthenticated attacker to steal other users' data.

### CVE-2025-44655
**totolink a7100ru_firmware Privilege Escalation**
- **Signals:** CVSS
- **Asset:** totolink a7100ru_firmware
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-07T17:58:19.833
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-21)

> In TOTOLink A7100RU V7.4, A950RG V5.9, and T10 V5.9, the chroot_local_user option is enabled in the vsftpd.conf. This could lead to unauthorized access to system files, privilege escalation, or use of the compromised server as a pivot point for internal network attacks.

### CVE-2025-44658
**netgear rax30_firmware**
- **Signals:** CVSS
- **Asset:** netgear rax30_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-07T17:57:40.350
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-21)

> In Netgear RAX30 V1.0.10.94, a PHP-FPM misconfiguration vulnerability is caused by not following the specification to only limit FPM to .php extensions. An attacker may exploit this by uploading malicious scripts disguised with alternate extensions and tricking the web server int…

### CVE-2025-52362
**Server-Side Request Forgery (SSRF) vulnerability exists in the URL processing functionality of PHProxy version 1.1.1 and prior.**
- **Signals:** CVSS
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-21)

> Server-Side Request Forgery (SSRF) vulnerability exists in the URL processing functionality of PHProxy version 1.1.1 and prior. The input validation for the _proxurl parameter can be bypassed, allowing a remote, unauthenticated attacker to submit a specially crafted URL

### CVE-2025-54071
**RomM (ROM Manager) allows users to scan, enrich, browse and play their game collections with a clean and responsive interface.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-21)

> RomM (ROM Manager) allows users to scan, enrich, browse and play their game collections with a clean and responsive interface. In versions 4.0.0-beta.3 and below, an authenticated arbitrary file write vulnerability exists in the /api/saves endpoint. This can lead to Remote Code E…

### CVE-2025-54127
**psu haxcms-nodejs privilege escalation**
- **Signals:** CVSS
- **Asset:** psu haxcms-nodejs
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-30T17:03:34.940
- **CWE:** CWE-1188
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-21)

> HAXcms with nodejs backend allows users to start the server in any HAXsite or HAXcms instance. In versions 11.0.6 and below, the NodeJS version of HAXcms uses an insecure default configuration designed for local development. The default configuration does not perform authorizatio…

### CVE-2025-7393
**mqanneh mail_login**
- **Signals:** CVSS
- **Asset:** mqanneh mail_login
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-27T14:22:22.903
- **CWE:** CWE-307
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-21)

> Improper Restriction of Excessive Authentication Attempts vulnerability in Drupal Mail Login allows Brute Force.This issue affects Mail Login: from 3.0.0 before 3.2.0, from 4.0.0 before 4.2.0.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-21*
