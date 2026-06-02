# Daily Threat Intelligence — December 12, 2025

**Digest window (UTC):** 2025-12-12
**Generated:** 2026-06-02T07:33:58Z

## Threat brief

Google Chromium added to CISA KEV — confirmed in-the-wild exploitation. · WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Sonicwall Sma 200 Firmware — exploitation likelihood rose sharply (EPSS 58% → 82% · rising (+25%)). · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- Google Chromium added to CISA KEV — confirmed in-the-wild exploitation.
- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Sonicwall Sma 200 Firmware — exploitation likelihood rose sharply (EPSS 58% → 82% · rising (+25%)).
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2018-4063
**Sierra Wireless AirLink ALEOS Unrestricted Upload of File with Dangerous Type Vulnerability**
- **Signals:** KEV
- **Asset:** sierrawireless aleos
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-15T15:18:49.987
- **CWE:** CWE-434
- **CWE:** CWE-434
- **Risk score:** 88
- **KEV:** added 2025-12-12

> An exploitable remote code execution vulnerability exists in the upload.cgi functionality of Sierra Wireless AirLink ES450 FW 4.9.3. A specially crafted HTTP request can upload a file, resulting in executable code being uploaded, and routable, to the webserver. An attacker can ma…

### CVE-2021-20039
**sonicwall sma_200_firmware**
- **Signals:** EPSS
- **Asset:** sonicwall sma_200_firmware
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2025-09-05T18:15:35.313
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 57.8% (2025-11-21) → 82.5% (2025-12-12), Δ +24.6%**

> Improper neutralization of special elements in the SMA100 management interface '/cgi-bin/viewcert' POST http method allows a remote authenticated attacker to inject arbitrary commands as a 'nobody' user. This vulnerability affected SMA 200, 210, 400, 410 and 500v appliances.

### CVE-2025-67728
**shaneisrael fireshare Path Traversal**
- **Signals:** CVSS
- **Asset:** shaneisrael fireshare
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-22T19:05:45.840
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-12)

> Fireshare facilitates self-hosted media and link sharing. Versions 1.2.30 and below allow an authenticated user, or unauthenticated user if the Public Uploads setting is enabled, to craft a malicious filename when uploading a video file. The malicious filename is then concatenate…

### CVE-2008-3733
**eo-video eo-video Buffer Overflow**
- **Signals:** EPSS
- **Asset:** eo-video eo-video
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 18.7% (2025-10-10) → 43.0% (2025-12-12), Δ +24.3%**

> Stack-based buffer overflow in EO Video (eo-video) 1.36 allows remote attackers to cause a denial of service (application crash) or execute arbitrary code via a .eop (aka playlist) file with a ProjectElement element that contains a long Name element.

### CVE-2024-58299
**PCMan FTP Server 2.0 contains a buffer overflow vulnerability in the 'pwd' command that allows remote attackers to execute arbitrary code.**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-12)

> PCMan FTP Server 2.0 contains a buffer overflow vulnerability in the 'pwd' command that allows remote attackers to execute arbitrary code. Attackers can send a specially crafted payload during the FTP login process to overwrite memory and potentially gain system access.

### CVE-2025-12963
**The LazyTasks – Project & Task Management with Collaboration, Kanban and Gantt Chart plugin for WordPress is vulnerable to privilege esca...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-12)

> The LazyTasks – Project & Task Management with Collaboration, Kanban and Gantt Chart plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 1.2.29. This is due to the plugin not properly validating a user's identity v…

### CVE-2025-14174
**Google Chromium Out of Bounds Memory Access Vulnerability**
- **Signals:** KEV
- **Asset:** google chrome
- **Attack:** memory safety
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-15T15:16:08.650
- **CWE:** CWE-787
- **CWE:** CWE-119
- **Risk score:** 88
- **KEV:** added 2025-12-12

> Out of bounds memory access in ANGLE in Google Chrome on Mac prior to 143.0.7499.110 allowed a remote attacker to perform out of bounds memory access via a crafted HTML page. (Chromium security severity: High)

### CVE-2025-14344
**The Multi Uploader for Gravity Forms plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validati...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-12)

> The Multi Uploader for Gravity Forms plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the 'plupload_ajax_delete_file' function in all versions up to, and including, 1.1.7. This makes it possible for unauthenticated attacker…

### CVE-2025-54947
**apache streampark**
- **Signals:** CVSS
- **Asset:** apache streampark
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-15T17:20:46.757
- **CWE:** CWE-321
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-12)

> In Apache StreamPark versions 2.0.0 through 2.1.7, a security vulnerability involving a hard-coded encryption key exists. This vulnerability occurs because the system uses a fixed, immutable key for encryption instead of dynamically generating or securely configuring the key. Att…

### CVE-2025-58130
**apache fineract**
- **Signals:** CVSS
- **Asset:** apache fineract
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-18T14:54:40.857
- **CWE:** CWE-522
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-12)

> Insufficiently Protected Credentials vulnerability in Apache Fineract.

This issue affects Apache Fineract: through 1.11.0. The issue is fixed in version 1.12.1.

Users are encouraged to upgrade to version 1.13.0, the latest release.

### CVE-2025-65854
**mineadmin mineadmin**
- **Signals:** CVSS
- **Asset:** mineadmin mineadmin
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T20:02:23.077
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-12)

> Insecure permissions in the scheduled tasks feature of MineAdmin v3.x allows attackers to execute arbitrary commands and execute a full account takeover.

### CVE-2025-66430
**plesk plesk**
- **Signals:** CVSS
- **Asset:** plesk plesk
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-06T14:59:12.427
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-12)

> Plesk 18.0 has Incorrect Access Control.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-12*
