# Daily Threat Intelligence — November 18, 2025

**Digest window (UTC):** 2025-11-18
**Generated:** 2026-06-02T07:33:48Z

## Threat brief

Fortinet FortiWeb added to CISA KEV — confirmed in-the-wild exploitation. · Adobe Flash Player — exploitation likelihood rose sharply (EPSS 32% → 69% · rising (+37%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Fortinet FortiWeb added to CISA KEV — confirmed in-the-wild exploitation.
- Adobe Flash Player — exploitation likelihood rose sharply (EPSS 32% → 69% · rising (+37%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **21** |


## CVEs

### CVE-2025-58034
**Fortinet FortiWeb OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** fortinet fortiweb
- **Attack:** Command Injection
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-21T18:27:43.280
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2025-11-18

> An Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability [CWE-78] vulnerability in Fortinet FortiWeb 8.0.0 through 8.0.1, FortiWeb 7.6.0 through 7.6.5, FortiWeb 7.4.0 through 7.4.10, FortiWeb 7.2.0 through 7.2.11, FortiWeb 7.0.0 …

### CVE-2017-2933
**adobe flash_player RCE**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-787
- **Risk score:** 84
- **EPSS 32.0% (2025-11-06) → 69.1% (2025-11-18), Δ +37.1%**

> Adobe Flash Player versions 24.0.0.186 and earlier have an exploitable heap overflow vulnerability related to texture compression. Successful exploitation could lead to arbitrary code execution.

### CVE-2025-63216
**itel idgateway_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** itel idgateway_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T21:54:41.147
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-18)

> The Itel DAB Gateway (IDGat build c041640a) is vulnerable to Authentication Bypass due to improper JWT validation across devices. Attackers can reuse a valid JWT token obtained from one device to authenticate and gain administrative access to any other device running the same fir…

### CVE-2007-5911
**viewpoint media_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** viewpoint media_player
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 81
- **EPSS 5.2% (2025-08-29) → 19.9% (2025-11-18), Δ +14.7%**

> Multiple stack-based buffer overflows in the AxMetaStream ActiveX control in AxMetaStream.dll 3.3.2.26 in Viewpoint Media Player 3.2 allow remote attackers to execute arbitrary code via a long string argument to the (1) BroadcastKey, (2) BroadcastKeyFileURL, (3) Component, (4) Co…

### CVE-2009-3844
**hp openview_data_protector_application_recovery_manager Buffer Overflow**
- **Signals:** EPSS
- **Asset:** hp openview_data_protector_application_recovery_manager
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 66.3% (2025-08-26) → 76.6% (2025-11-18), Δ +10.3%**

> Stack-based buffer overflow in the OmniInet process in HP OpenView Data Protector Application Recovery Manager 5.50 and 6.0 allows remote attackers to execute arbitrary code or cause a denial of service via a crafted MSG_PROTOCOL packet.

### CVE-2017-2930
**adobe flash_player RCE**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-787
- **Risk score:** 81
- **EPSS 71.8% (2025-11-06) → 82.0% (2025-11-18), Δ +10.2%**

> Adobe Flash Player versions 24.0.0.186 and earlier have an exploitable memory corruption vulnerability due to a concurrency error when manipulating a display list. Successful exploitation could lead to arbitrary code execution.

### CVE-2017-2931
**adobe flash_player RCE**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-787
- **Risk score:** 84
- **EPSS 38.2% (2025-11-06) → 67.9% (2025-11-18), Δ +29.7%**

> Adobe Flash Player versions 24.0.0.186 and earlier have an exploitable memory corruption vulnerability related to the parsing of SWF metadata. Successful exploitation could lead to arbitrary code execution.

### CVE-2017-2932
**adobe flash_player RCE**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-416
- **Risk score:** 84
- **EPSS 38.2% (2025-11-06) → 64.4% (2025-11-18), Δ +26.1%**

> Adobe Flash Player versions 24.0.0.186 and earlier have an exploitable use after free vulnerability in the ActionScript MovieClip class. Successful exploitation could lead to arbitrary code execution.

### CVE-2017-2934
**adobe flash_player RCE**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-787
- **Risk score:** 84
- **EPSS 32.0% (2025-11-06) → 69.1% (2025-11-18), Δ +37.1%**

> Adobe Flash Player versions 24.0.0.186 and earlier have an exploitable heap overflow vulnerability when parsing Adobe Texture Format files. Successful exploitation could lead to arbitrary code execution.

### CVE-2017-2935
**adobe flash_player RCE**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-787
- **Risk score:** 84
- **EPSS 32.0% (2025-11-06) → 69.1% (2025-11-18), Δ +37.1%**

> Adobe Flash Player versions 24.0.0.186 and earlier have an exploitable heap overflow vulnerability when processing the Flash Video container file format. Successful exploitation could lead to arbitrary code execution.

### CVE-2017-2985
**adobe flash_player RCE**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-416
- **Risk score:** 83
- **EPSS 40.9% (2025-07-01) → 52.4% (2025-11-18), Δ +11.6%**

> Adobe Flash Player versions 24.0.0.194 and earlier have an exploitable use after free vulnerability in the ActionScript 3 BitmapData class. Successful exploitation could lead to arbitrary code execution.

### CVE-2021-28959
**zohocorp manageengine_eventlog_analyzer RCE**
- **Signals:** EPSS
- **Asset:** zohocorp manageengine_eventlog_analyzer
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:00:26.840
- **CWE:** CWE-22
- **Risk score:** 86
- **EPSS 3.9% (2025-03-30) → 24.1% (2025-11-18), Δ +20.3%**

> Zoho ManageEngine Eventlog Analyzer through 12147 is vulnerable to unauthenticated directory traversal via an entry in a ZIP archive. This leads to remote code execution.

### CVE-2025-54321
**ascertia signinghub**
- **Signals:** CVSS
- **Asset:** ascertia signinghub
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-20T19:00:58.973
- **CWE:** CWE-799
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-18)

> In Ascertia SigningHub through 8.6.8, there is a lack of rate limiting on the reset password function, leading to an email bombing vulnerability. An authenticated attacker can exploit this by automating reset password requests.

### CVE-2025-56643
**requarks wiki.js**
- **Signals:** CVSS
- **Asset:** requarks wiki.js
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T02:06:51.750
- **CWE:** CWE-613
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-18)

> Requarks Wiki.js 2.5.307 does not properly revoke or invalidate active JWT tokens when a user logs out. As a result, previously issued tokens remain valid and can be reused to access the system, even after logout. This behavior affects session integrity and may allow unauthorized…

### CVE-2025-63217
**itel id_mux_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** itel id_mux_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T21:57:14.860
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-18)

> The Itel DAB MUX (IDMUX build c041640a) is vulnerable to Authentication Bypass due to improper JWT validation across devices. Attackers can reuse a valid JWT token obtained from one device to authenticate and gain administrative access to any other device running the same firmwar…

### CVE-2025-63225
**eurolab-srl elts_100_firmware**
- **Signals:** CVSS
- **Asset:** eurolab-srl elts_100_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-04T20:54:01.817
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-18)

> The Eurolab ELTS100_UBX device (firmware version ELTS100v1.UBX) is vulnerable to Broken Access Control due to missing authentication on critical administrative endpoints. Attackers can directly access and modify sensitive system and network configurations, upload firmware, and ex…

### CVE-2025-63228
**dbbroadcast mozart_dds_next_1000_firmware RCE**
- **Signals:** CVSS
- **Asset:** dbbroadcast mozart_next_100_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-08T14:44:31.763
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-18)

> The Mozart FM Transmitter web management interface on version WEBMOZZI-00287, contains an unauthenticated file upload vulnerability in the /upload_file.php endpoint. An attacker can exploit this by sending a crafted POST request with a malicious file (e.g., a PHP webshell) to the…

### CVE-2025-63694
**dzzoffice dzzoffice SQL Injection**
- **Signals:** CVSS
- **Asset:** dzzoffice dzzoffice
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-20T19:16:32.317
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-18)

> DzzOffice v2.3.7 and before is vulnerable to SQL Injection in explorer/groupmanage.

### CVE-2025-63695
**dzzoffice dzzoffice**
- **Signals:** CVSS
- **Asset:** dzzoffice dzzoffice
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-20T19:04:23.467
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-18)

> DzzOffice v2.3.7 and before is vulnerable to Arbitrary File Upload in /dzz/system/ueditor/php/controller.php.

### CVE-2025-63994
**psolom richfilemanager**
- **Signals:** CVSS
- **Asset:** psolom richfilemanager
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T02:04:56.717
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-18)

> An arbitrary file upload vulnerability in the /php/UploadHandler.php component of RichFilemanager v2.7.6 allows attackers to execute arbitrary code via uploading a crafted file.

### CVE-2025-65015
**hsiaoming joserfc**
- **Signals:** CVSS
- **Asset:** hsiaoming joserfc
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T22:10:33.100
- **CWE:** CWE-770
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-11-18)

> joserfc is a Python library that provides an implementation of several JSON Object Signing and Encryption (JOSE) standards. In versions from 1.3.3 to before 1.3.5 and from 1.4.0 to before 1.4.2, the ExceededSizeError exception messages are embedded with non-decoded JWT token part…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-18*
