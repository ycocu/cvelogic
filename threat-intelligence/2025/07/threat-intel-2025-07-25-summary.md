# Daily Threat Intelligence — July 25, 2025

**Digest window (UTC):** 2025-07-25
**Generated:** 2026-06-02T07:33:07Z

## Threat brief

Adobe Acrobat Reader — exploitation likelihood rose sharply (EPSS 60% → 72% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Adobe Acrobat Reader — exploitation likelihood rose sharply (EPSS 60% → 72% · rising (+12%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2008-2549
**adobe acrobat_reader DoS**
- **Signals:** EPSS
- **Asset:** adobe acrobat_reader
- **Attack:** DoS
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 77
- **EPSS 59.5% (2025-03-30) → 71.9% (2025-07-25), Δ +12.3%**

> Adobe Acrobat Reader 8.1.2 and earlier, and before 7.1.1, allows remote attackers to cause a denial of service (application crash) and possibly execute arbitrary code via a malformed PDF document, as demonstrated by 2008-HI2.pdf.

### CVE-2014-125115
**An unauthenticated SQL injection vulnerability exists in Pandora FMS version 5.0 SP2 and earlier.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-25)

> An unauthenticated SQL injection vulnerability exists in Pandora FMS version 5.0 SP2 and earlier. The mobile/index.php endpoint fails to properly sanitize user input in the loginhash_data parameter, allowing attackers to extract administrator credentials or active session tokens …

### CVE-2025-46199
**getgrav grav cross-site scripting**
- **Signals:** CVSS
- **Asset:** getgrav grav
- **Attack:** cross-site scripting
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-15T14:32:27.690
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-25)

> Cross Site Scripting vulnerability in grav v.1.7.48 and before allows an attacker to execute arbitrary code via a crafted script to the form fields

### CVE-2014-125116
**A remote code execution vulnerability exists in HybridAuth versions 2.0.9 through 2.2.2 due to insecure use of the install.php installati...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-25)

> A remote code execution vulnerability exists in HybridAuth versions 2.0.9 through 2.2.2 due to insecure use of the install.php installation script. The script remains accessible after deployment and fails to sanitize input before writing to the application’s config.php file. An u…

### CVE-2014-125117
**dlink dsp-w215_firmware RCE**
- **Signals:** CVSS
- **Asset:** dlink dsp-w215_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-23T18:03:59.860
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-25)

> A stack-based buffer overflow vulnerability in the my_cgi.cgi component of certain D-Link devices, including the DSP-W215 version 1.02, can be exploited via a specially crafted HTTP POST request to the /common/info.cgi endpoint. This flaw enables an unauthenticated attacker to ac…

### CVE-2014-125118
**A command injection vulnerability exists in the eScan Web Management Console version 5.5-2.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-25)

> A command injection vulnerability exists in the eScan Web Management Console version 5.5-2. The application fails to properly sanitize the 'pass' parameter when processing login requests to login.php, allowing an authenticated attacker with a valid username to inject arbitrary co…

### CVE-2025-29628
**A Gardyn Azure IoT Hub connection string is downloaded over an insecure HTTP connection in Gardyn Home Kit firmware before master.619, Ho...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-924
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-25)

> A Gardyn Azure IoT Hub connection string is downloaded over an insecure HTTP connection in Gardyn Home Kit firmware before master.619, Home Kit Mobile Application before 2.11.0, and Home Kit Cloud API before 2.12.2026 leaving the string vulnerable to interception and modification…

### CVE-2025-29629
**Gardyn Home Kit firmware before master.619, Home Kit Mobile Application before 2.11.0, and Home Kit Cloud API before 2.12.2026 use weak d...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1392
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-25)

> Gardyn Home Kit firmware before master.619, Home Kit Mobile Application before 2.11.0, and Home Kit Cloud API before 2.12.2026 use weak default credentials for secure shell access. This may result in attackers gaining access to exposed Gardyn Home Kits.

### CVE-2025-29631
**Gardyn Home Kit firmware before master.619, Home Kit Mobile Application before 2.11.0, and Home Kit Cloud API before 2.12.2026 allow comm...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-25)

> Gardyn Home Kit firmware before master.619, Home Kit Mobile Application before 2.11.0, and Home Kit Cloud API before 2.12.2026 allow command injection through vulnerable methods that do not sanitize input before passing content to the operating system for execution. The vulnerabi…

### CVE-2025-30135
**iroadau fx2_firmware**
- **Signals:** CVSS
- **Asset:** iroadau fx2_firmware
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T20:23:29.610
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-25)

> An issue was discovered on IROAD Dashcam FX2 devices. Dumping Files Over HTTP and RTSP Without Authentication can occur. It lacks authentication controls on its HTTP and RTSP interfaces, allowing attackers to retrieve sensitive files and video recordings. By connecting to http://…

### CVE-2025-45777
**abeltechsoft chavara_matrimony**
- **Signals:** CVSS
- **Asset:** abeltechsoft chavara_matrimony
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-10T21:42:45.687
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-25)

> An issue in the OTP mechanism of Chavara Family Welfare Centre Chavara Matrimony Site v2.0 allows attackers to bypass authentication via supplying a crafted request.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-25*
