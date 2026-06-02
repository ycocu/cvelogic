# Daily Threat Intelligence — May 12, 2026

**Digest window (UTC):** 2026-05-12
**Generated:** 2026-06-02T07:03:59Z

## Threat brief

Exploitation likelihood rose sharply (EPSS 50% → 70% · rising (+20%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Exploitation likelihood rose sharply (EPSS 50% → 70% · rising (+20%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 9 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **19** |


## CVEs

### CVE-2025-34120
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 84
- **EPSS 50.2% (2025-12-13) → 69.9% (2026-05-12), Δ +19.8%**

> An unauthenticated file download vulnerability exists in LimeSurvey versions from 2.0+ up to and including 2.06+ Build 151014. The application fails to validate serialized input to the admin backup endpoint (`index.php/admin/update/sa/backup`), allowing attackers to specify arbit…

### CVE-2025-34128
**Buffer Overflow · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Buffer Overflow
- **CVSS max:** 8.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 84
- **EPSS 52.1% (2026-04-01) → 70.4% (2026-05-12), Δ +18.3%**

> A buffer overflow vulnerability exists in the X360 VideoPlayer ActiveX control (VideoPlayer.ocx) version 2.6 when handling overly long arguments to the ConvertFile() method. An attacker can exploit this vulnerability by supplying crafted input to cause memory corruption and execu…

### CVE-2026-42288
**ChurchCRM is an open-source church management system.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T16:16:30.823
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-12)

> ChurchCRM is an open-source church management system. Prior to 7.3.2, The fix for CVE-2026-39337 is incomplete. The pre-authentication remote code execution vulnerability in ChurchCRM's setup wizard via unsanitized DB_PASSWORD remains fully exploitable This vulnerability is fixed…

### CVE-2001-1088
**microsoft outlook**
- **Signals:** EPSS
- **Asset:** microsoft outlook
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 35.6% (2026-03-16) → 47.8% (2026-05-12), Δ +12.2%**

> Microsoft Outlook 8.5 and earlier, and Outlook Express 5 and earlier, with the "Automatically put people I reply to in my address book" option enabled, do not notify the user when the "Reply-To" address is different than the "From" address, which could allow an untrusted remote a…

### CVE-2025-34117
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 82
- **EPSS 50.3% (2025-12-13) → 60.7% (2026-05-12), Δ +10.4%**

> A remote code execution vulnerability exists in multiple Netcore and Netis routers models with firmware released prior to August 2014 due to the presence of an undocumented backdoor listener on UDP port 53413. Exact version boundaries remain undocumented. An unauthenticated remot…

### CVE-2025-34119
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 8.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 84
- **EPSS 29.6% (2025-12-13) → 45.3% (2026-05-12), Δ +15.7%**

> A remote file disclosure vulnerability exists in EasyCafe Server 2.2.14, exploitable by unauthenticated remote attackers via TCP port 831. The server listens for a custom protocol where opcode 0x43 can be used to request arbitrary files by absolute path. If the file exists and is…

### CVE-2025-34121
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 85
- **EPSS 67.8% (2026-04-01) → 80.6% (2026-05-12), Δ +12.7%**

> An unauthenticated arbitrary file upload vulnerability exists in Idera Up.Time Monitoring Station versions up to and including 7.2. The `wizards/post2file.php` script accepts arbitrary POST parameters, allowing attackers to upload crafted PHP files to the webroot. Successful expl…

### CVE-2025-34123
**Buffer Overflow · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Buffer Overflow
- **CVSS max:** 8.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 82
- **EPSS 8.7% (2026-04-01) → 19.9% (2026-05-12), Δ +11.1%**

> A stack-based buffer overflow vulnerability exists in VideoCharge Studio 2.12.3.685 when processing a specially crafted .VSC configuration file. The issue occurs due to improper handling of user-supplied data in the XML 'Name' attribute, leading to an SEH overwrite condition. An …

### CVE-2025-34124
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 8.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 12.6% (2026-04-01) → 27.0% (2026-05-12), Δ +14.3%**

> A buffer overflow vulnerability exists in Heroes of Might and Magic III Complete 4.0.0.0, HD Mod 3.808 build 9, and Demo 1.0.0.0 via malicious .h3m map files that exploit object sprite name parsing logic. The vulnerability occurs during in-game map loading when a crafted object n…

### CVE-2025-34127
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 85
- **EPSS 56.3% (2026-04-01) → 73.3% (2026-05-12), Δ +17.0%**

> A stack-based buffer overflow exists in Achat v0.150 in its default configuration. By sending a specially crafted message to the UDP port 9256, an attacker can overwrite the structured exception handler (SEH) due to insufficient bounds checking on user-supplied input leading to r…

### CVE-2026-41901
**Thymeleaf is a server-side Java template engine for web and standalone environments.**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T16:10:57.817
- **CWE:** CWE-917
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-05-12)

> Thymeleaf is a server-side Java template engine for web and standalone environments. Prior to 3.1.5.RELEASE, a security bypass vulnerability exists in the expression execution mechanisms of Thymeleaf. Although the library provides mechanisms to avoid the execution of potentially …

### CVE-2026-42196
**django-s3file is a lightweight file upload input for Django and Amazon S3.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T18:15:26.870
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-12)

> django-s3file is a lightweight file upload input for Django and Amazon S3. Prior to 7.0.2, S3FileMiddleware is vulnerable to relative path traversal attacks, where an attacker can use a modified request to escape pre-signed upload locations and have the Django application load fi…

### CVE-2026-42854
**espressif arduino-esp32**
- **Signals:** CVSS
- **Asset:** espressif arduino-esp32
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-18T13:09:58.927
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-12)

> arduino-esp32 is an Arduino core for the ESP32, ESP32-S2, ESP32-S3, ESP32-C3, ESP32-C6 and ESP32-H2 microcontrollers. Prior to 3.3.8, the WebServer multipart form parser in arduino-esp32 allocates a Variable Length Array (VLA) on the stack whose size is derived from an attacker-c…

### CVE-2026-43948
**wger is a free, open-source workout and fitness manager.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T16:16:53.397
- **CWE:** CWE-863
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-12)

> wger is a free, open-source workout and fitness manager. Prior to 2.6, the reset_user_password and gym_permissions_user_edit views in wger perform a gym-scope authorization check using Python object comparison (!=) that evaluates None != None as False, silently bypassing the guar…

### CVE-2026-44257
**efw4.X is an Enterprise Framework for Web.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T16:16:31.293
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-12)

> efw4.X is an Enterprise Framework for Web. Prior to 4.08.010, efw.file.FileManager.unZip writes zip entries to disk using new File(baseDir, zipEntry.getName()) with no canonical-path check. An entry name such as ../../../pwned.jsp escapes the intended extraction directory and lan…

### CVE-2026-44258
**efw4.X is an Enterprise Framework for Web.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-14T13:16:19.357
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-12)

> efw4.X is an Enterprise Framework for Web. Prior to 4.08.010, the elfinder_checkRisk function validates target and targets for path traversal and home containment, but does not validate the dst (destination) parameter used by elfinder_paste. An attacker can copy or move files fro…

### CVE-2026-44262
**Scramble generates API documentation for Laravel project.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T16:10:57.817
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-12)

> Scramble generates API documentation for Laravel project. From 0.13.2 to before 0.13.22, when documentation endpoints are publicly accessible and validation rules reference user-controlled input, request supplied data may be evaluated during documentation generation, leading to e…

### CVE-2026-44547
**ChurchCRM is an open-source church management system.**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T16:16:58.563
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-12)

> ChurchCRM is an open-source church management system. From 7.2.0 to 7.2.2, The fix for CVE-2026-4058 is incomplete. The hardening commit was merged and then silently stripped from src/api/routes/public/public-user.php by an unrelated PR before any 7.2.x tag was cut. Every shipped…

### CVE-2026-45185
**exim exim Use-After-Free**
- **Signals:** CVSS
- **Asset:** exim exim
- **Attack:** Use-After-Free
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-28T18:46:27.410
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-12)

> Exim before 4.99.3, in certain GnuTLS configurations, has a remotely reachable use-after-free in the BDAT body parsing path. It is triggered when a client sends a TLS close_notify mid-body during a CHUNKING transfer, followed by a final cleartext byte on the same TCP connection. …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-12*
