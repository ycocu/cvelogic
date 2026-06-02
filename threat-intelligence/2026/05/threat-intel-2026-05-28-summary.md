# Daily Threat Intelligence — May 28, 2026

**Digest window (UTC):** 2026-05-28
**Generated:** 2026-06-02T07:04:08Z

## Threat brief

Exploitation likelihood rose sharply (EPSS 52% → 74% · rising (+22%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Exploitation likelihood rose sharply (EPSS 52% → 74% · rising (+22%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **20** |


## CVEs

### CVE-2013-10063
**Path Traversal · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Path Traversal
- **CVSS max:** 6.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 81
- **EPSS 52.0% (2026-04-17) → 73.9% (2026-05-28), Δ +21.9%**

> A path traversal vulnerability exists in the Netgear SPH200D Skype phone firmware versions <= 1.0.4.80 in its embedded web server. Authenticated attackers can exploit crafted GET requests to access arbitrary files outside the web root by injecting traversal sequences. This can ex…

### CVE-2009-0919
**apachefriends xampp**
- **Signals:** EPSS
- **Asset:** apachefriends xampp
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-255
- **Risk score:** 82
- **EPSS 1.7% (2025-09-15) → 23.5% (2026-05-28), Δ +21.8%**

> XAMPP installs multiple packages with insecure default passwords, which makes it easier for remote attackers to obtain access via (1) the "lampp" default password for the "nobody" account within the included ProFTPD installation, (2) a blank default password for the "root" accoun…

### CVE-2026-8809
**The Advanced Custom Fields: Extended plugin for WordPress is vulnerable to Privilege Escalation via Validation Bypass in all versions up...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T02:40:08.093
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-28)

> The Advanced Custom Fields: Extended plugin for WordPress is vulnerable to Privilege Escalation via Validation Bypass in all versions up to and including 0.9.2.5. The vulnerability exists due to the after_validate_save_post() function unconditionally trusting the attacker-control…

### CVE-2013-10049
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 55.4% (2026-04-17) → 76.0% (2026-05-28), Δ +20.6%**

> An OS command injection vulnerability exists in multiple Raidsonic NAS devices—specifically tested on IB-NAS5220 and IB-NAS4220—via the unauthenticated timeHandler.cgi endpoint exposed through the web interface. The CGI script fails to properly sanitize user-supplied input in the…

### CVE-2013-10058
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 8.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 50.8% (2026-04-17) → 65.6% (2026-05-28), Δ +14.8%**

> An authenticated OS command injection vulnerability exists in various Linksys router models (tested on WRT160Nv2) running firmware version v2.0.03 via the apply.cgi endpoint. The web interface fails to properly sanitize user-supplied input passed to the ping_size parameter during…

### CVE-2013-10059
**dlink dir-615h_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** dlink dir-615h_firmware
- **Attack:** Command Injection
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-23T19:10:54.760
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 54.9% (2026-04-17) → 72.4% (2026-05-28), Δ +17.5%**

> An authenticated OS command injection vulnerability exists in various D-Link routers (tested on DIR-615H1 running firmware version 8.04) via the tools_vct.htm endpoint. The web interface fails to sanitize input passed from the ping_ipaddr parameter to the tools_vct.htm diagnostic…

### CVE-2017-5991
**artifex debian_linux**
- **Signals:** EPSS
- **Asset:** artifex mupdf
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-476
- **Risk score:** 82
- **EPSS 17.6% (2025-12-11) → 33.2% (2026-05-28), Δ +15.6%**

> An issue was discovered in Artifex MuPDF before 1912de5f08e90af1d9d0a9791f58ba3afdb9d465. The pdf_run_xobject function in pdf-op-run.c encounters a NULL pointer dereference during a Fitz fz_paint_pixmap_with_mask painting operation. Versions 1.11 and later are unaffected.

### CVE-2020-10532
**watchguard ad_helper_firmware**
- **Signals:** EPSS
- **Asset:** watchguard ad_helper_firmware
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:55:31.830
- **CWE:** CWE-312
- **Risk score:** 82
- **EPSS 0.3% (2025-11-21) → 16.3% (2026-05-28), Δ +16.0%**

> The AD Helper component in WatchGuard Fireware before 5.8.5.10317 allows remote attackers to discover cleartext passwords via the /domains/list URI.

### CVE-2020-10957
**dovecot dovecot**
- **Signals:** EPSS
- **Asset:** dovecot dovecot
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:56:27.067
- **CWE:** CWE-476
- **Risk score:** 82
- **EPSS 8.1% (2026-04-19) → 23.6% (2026-05-28), Δ +15.5%**

> In Dovecot before 2.3.10.1, unauthenticated sending of malformed parameters to a NOOP command causes a NULL Pointer Dereference and crash in submission-login, submission, or lmtp.

### CVE-2021-28548
**adobe photoshop RCE**
- **Signals:** EPSS
- **Asset:** adobe photoshop
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:59:49.603
- **CWE:** CWE-120
- **Risk score:** 83
- **EPSS 5.8% (2026-05-03) → 22.5% (2026-05-28), Δ +16.7%**

> Adobe Photoshop versions 21.2.6 (and earlier) and 22.3 (and earlier) are affected by a Buffer Overflow vulnerability when parsing a specially crafted JSX file. An unauthenticated attacker could leverage this vulnerability to achieve arbitrary code execution in the context of the …

### CVE-2025-5947
**Privilege Escalation · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-639
- **Risk score:** 86
- **EPSS 43.2% (2026-05-25) → 61.7% (2026-05-28), Δ +18.5%**

> The Service Finder Bookings plugin for WordPress is vulnerable to privilege escalation via authentication bypass in all versions up to, and including, 6.0. This is due to the plugin not properly validating a user's cookie value prior to logging them in through the service_finder_…

### CVE-2026-9872
**google chrome memory safety**
- **Signals:** CVSS
- **Asset:** google chrome
- **Attack:** memory safety
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-01T18:45:09.070
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-28)

> Out of bounds write in GPU in Google Chrome on Android prior to 148.0.7778.216 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: Critical)

### CVE-2026-9874
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-29T17:04:15.220
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-28)

> Use after free in Dawn in Google Chrome prior to 148.0.7778.216 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: Critical)

### CVE-2026-9875
**google chrome memory safety**
- **Signals:** CVSS
- **Asset:** google chrome
- **Attack:** memory safety
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-01T18:45:00.900
- **CWE:** CWE-125
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-28)

> Out of bounds read in WebGL in Google Chrome on Android prior to 148.0.7778.216 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: Critical)

### CVE-2026-9876
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-01T18:44:53.453
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-28)

> Use after free in WebGL in Google Chrome on Android prior to 148.0.7778.216 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: Critical)

### CVE-2026-9881
**Use after free in Bluetooth in Google Chrome on Mac prior to 148.0.7778.216 allowed an attacker who convinced a user to install a malicio...**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-05-29T16:16:34.497
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-05-28)

> Use after free in Bluetooth in Google Chrome on Mac prior to 148.0.7778.216 allowed an attacker who convinced a user to install a malicious extension to potentially perform a sandbox escape via a crafted Chrome Extension. (Chromium security severity: Critical)

### CVE-2026-9886
**Use after free in Base in Google Chrome on Mac prior to 148.0.7778.216 allowed a remote attacker to potentially perform a sandbox escape...**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-05-29T16:16:34.787
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-28)

> Use after free in Base in Google Chrome on Mac prior to 148.0.7778.216 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: Critical)

### CVE-2026-9891
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-29T17:15:18.660
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-05-28)

> Use after free in Extensions in Google Chrome prior to 148.0.7778.216 allowed a remote attacker who had compromised the renderer process to potentially perform a sandbox escape via a crafted Chrome Extension. (Chromium security severity: Critical)

### CVE-2026-9918
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-01T18:48:43.230
- **CWE:** CWE-269
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-28)

> Inappropriate implementation in Tint in Google Chrome prior to 148.0.7778.216 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: High)

### CVE-2026-9967
**google chrome memory safety**
- **Signals:** CVSS
- **Asset:** google chrome
- **Attack:** memory safety
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-01T17:22:08.447
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-28)

> Out of bounds write in GPU in Google Chrome prior to 148.0.7778.216 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: High)

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-28*
