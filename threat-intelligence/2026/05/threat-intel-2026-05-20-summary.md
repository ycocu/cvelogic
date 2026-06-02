# Daily Threat Intelligence — May 20, 2026

**Digest window (UTC):** 2026-05-20
**Generated:** 2026-06-02T07:04:04Z

## Threat brief

Microsoft Defender: 6 CVEs added to CISA KEV today. · Qcubed — exploitation likelihood rose sharply (EPSS 32% → 61% · rising (+29%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Defender: 6 CVEs added to CISA KEV today.
- Qcubed — exploitation likelihood rose sharply (EPSS 32% → 61% · rising (+29%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 7 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **20** |


## CVEs

### CVE-2008-4250
**Microsoft Windows Buffer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_2000
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-21T12:57:17.353
- **CWE:** CWE-94
- **CWE:** CWE-119
- **Risk score:** 88
- **KEV:** added 2026-05-20

> The Server service in Microsoft Windows 2000 SP4, XP SP2 and SP3, Server 2003 SP1 and SP2, Vista Gold and SP1, Server 2008, and 7 Pre-Beta allows remote attackers to execute arbitrary code via a crafted RPC request that triggers the overflow during path canonicalization, as explo…

### CVE-2020-24912
**qcubed qcubed XSS**
- **Signals:** EPSS
- **Asset:** qcubed qcubed
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:16:11.890
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 31.9% (2026-03-05) → 60.9% (2026-05-20), Δ +29.0%**

> A reflected cross-site scripting (XSS) vulnerability in qcubed (all versions including 3.1.1) in profile.php via the stQuery-parameter allows unauthenticated attackers to steal sessions of authenticated users.

### CVE-2026-45444
**Unrestricted Upload of File with Dangerous Type vulnerability in WP Swings Gift Cards For WooCommerce Pro allows Using Malicious Files.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T15:19:30.540
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-20)

> Unrestricted Upload of File with Dangerous Type vulnerability in WP Swings Gift Cards For WooCommerce Pro allows Using Malicious Files.

This issue affects Gift Cards For WooCommerce Pro: from n/a through 4.2.6.

### CVE-2009-1537
**Microsoft DirectX NULL Byte Overwrite Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft directx
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-21T12:57:12.850
- **CWE:** CWE-158
- **Risk score:** 88
- **KEV:** added 2026-05-20

> Unspecified vulnerability in the QuickTime Movie Parser Filter in quartz.dll in DirectShow in Microsoft DirectX 7.0 through 9.0c on Windows 2000 SP4, Windows XP SP2 and SP3, and Windows Server 2003 SP2 allows remote attackers to execute arbitrary code via a crafted QuickTime medi…

### CVE-2009-3459
**Adobe Acrobat and Reader Heap-Based Buffer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** adobe acrobat
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-21T12:56:49.133
- **CWE:** CWE-119
- **CWE:** CWE-122
- **Risk score:** 88
- **KEV:** added 2026-05-20

> Heap-based buffer overflow in Adobe Reader and Acrobat 7.x before 7.1.4, 8.x before 8.1.7, and 9.x before 9.2 allows remote attackers to execute arbitrary code via a crafted PDF file that triggers memory corruption, as exploited in the wild in October 2009. NOTE: some of these de…

### CVE-2010-0249
**Microsoft Internet Explorer Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft internet_explorer
- **Attack:** Use-After-Free
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-21T12:57:01.463
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2026-05-20

> Use-after-free vulnerability in Microsoft Internet Explorer 6, 6 SP1, 7, and 8 on Windows 2000 SP4; Windows XP SP2 and SP3; Windows Server 2003 SP2; Windows Vista Gold, SP1, and SP2; Windows Server 2008 Gold, SP2, and R2; and Windows 7 allows remote attackers to execute arbitrary…

### CVE-2010-0364
**videolan vlc_media_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** videolan vlc_media_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 6.7% (2025-06-14) → 20.6% (2026-05-20), Δ +14.0%**

> Stack-based buffer overflow in VideoLAN VLC Media Player 0.8.6 allows user-assisted remote attackers to execute arbitrary code via an ogg file with a crafted Advanced SubStation Alpha Subtitle (.ass) file, probably involving the Dialogue field.

### CVE-2010-0806
**Microsoft Internet Explorer Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft internet_explorer
- **Attack:** Memory Corruption
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-21T12:57:10.303
- **CWE:** CWE-399
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2026-05-20

> Use-after-free vulnerability in the Peer Objects component (aka iepeers.dll) in Microsoft Internet Explorer 6, 6 SP1, and 7 allows remote attackers to execute arbitrary code via vectors involving access to an invalid pointer after the deletion of an object, as exploited in the wi…

### CVE-2019-8641
**apple iphone_os Out-of-Bounds Write**
- **Signals:** EPSS
- **Asset:** apple iphone_os
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:50:13.243
- **CWE:** CWE-125
- **Risk score:** 83
- **EPSS 10.9% (2026-03-02) → 21.2% (2026-05-20), Δ +10.3%**

> An out-of-bounds read was addressed with improved input validation.

### CVE-2026-23734
**XWiki Platform is a generic wiki platform.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T16:04:53.813
- **CWE:** CWE-23
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-20)

> XWiki Platform is a generic wiki platform. Versions prior to 18.1.0-rc-1, 17.10.3, 17.4.9, and 16.10.17 allow access to read configuration files by using URLs such as http://localhost:8080/bin/ssx/Main/WebHome?resource=/../../WEB-INF/xwiki.cfg&minify=false, leading to Path Traver…

### CVE-2026-33137
**XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T19:16:27.020
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-20)

> XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. XWiki Platform is a generic wiki platform. In versions starting with 15.10.6 and prior to 18.1.0-rc-1, 17.10.3, 17.4.9, and 16.10.17, the POST /wikis/{wikiName} API executes a…

### CVE-2026-39405
**Frappe Learning Management System (LMS) is a learning system that helps users structure their content.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T15:24:25.330
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-20)

> Frappe Learning Management System (LMS) is a learning system that helps users structure their content. In versions 2.50.0 and below, a user with course editing role could upload a SCORM ZIP package to write files outside the intended directory. This issue has been resolved in ver…

### CVE-2026-41091
**Microsoft Defender Link Following Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft malware_protection_engine
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-20T19:06:36.850
- **CWE:** CWE-59
- **Risk score:** 88
- **KEV:** added 2026-05-20

> Improper link resolution before file access ('link following') in Microsoft Defender allows an authorized attacker to elevate privileges locally.

### CVE-2026-45498
**Microsoft Defender Denial of Service Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft defender_antimalware_platform
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-28T10:49:44.453
- **CWE:** CWE-400
- **Risk score:** 88
- **KEV:** added 2026-05-20

> Microsoft Defender Denial of Service Vulnerability

### CVE-2026-47372
**Crypt::SaltedHash versions through 0.09 for Perl generate insecure random values for salts.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T16:04:53.813
- **CWE:** CWE-338
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-20)

> Crypt::SaltedHash versions through 0.09 for Perl generate insecure random values for salts.

These versions use the built-in rand function, which is predictable and unsuitable for cryptography.

### CVE-2026-8631
**hp linux_imaging_and_printing RCE**
- **Signals:** CVSS
- **Asset:** hp linux_imaging_and_printing
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-21T18:58:41.297
- **CWE:** CWE-122
- **CWE:** CWE-190
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-20)

> A potential security vulnerability has been identified in the HP Linux Imaging and Printing Software. This potential vulnerability may allow escalation of privileges and/or arbitrary code execution via an integer overflow in the hpcups processing path when handling crafted print …

### CVE-2026-9102
**A path traversal vulnerability exists in the Altium Enterprise Server ComparisonService due to missing filename sanitization in the Gerbe...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T15:24:25.330
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-20)

> A path traversal vulnerability exists in the Altium Enterprise Server ComparisonService due to missing filename sanitization in the Gerber file upload APIs. A regular authenticated workspace user can supply a crafted filename in the multipart Content-Disposition header to escape …

### CVE-2026-9129
**A path traversal vulnerability exists in the Altium Enterprise Server Viewer StorageController due to improper handling of file path rout...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T15:24:25.330
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-20)

> A path traversal vulnerability exists in the Altium Enterprise Server Viewer StorageController due to improper handling of file path route parameters. On on-premise deployments that use local filesystem storage, a regular authenticated user can supply a URL-encoded absolute path …

### CVE-2026-9139
**Taiko AG1000-01A SMS Alert Gateway Rev 7.3 and Rev 8 contains a hard-coded credential vulnerability in the embedded web configuration int...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T15:17:59.850
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-20)

> Taiko AG1000-01A SMS Alert Gateway Rev 7.3 and Rev 8 contains a hard-coded credential vulnerability in the embedded web configuration interface where authentication is implemented entirely in client-side JavaScript in login.zhtml, exposing static plaintext credentials in the page…

### CVE-2026-9141
**Taiko AG1000-01A SMS Alert Gateway Rev 7.3 and Rev 8 contains an authentication bypass vulnerability in the embedded web configuration in...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T15:17:59.850
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-20)

> Taiko AG1000-01A SMS Alert Gateway Rev 7.3 and Rev 8 contains an authentication bypass vulnerability in the embedded web configuration interface that allows unauthenticated attackers to access internal application pages without any session management or server-side authentication…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-20*
