# Daily Threat Intelligence — March 05, 2026

**Digest window (UTC):** 2026-03-05
**Generated:** 2026-06-02T07:34:34Z

## Threat brief

Apple Multiple Products: 3 CVEs added to CISA KEV today. · Upredsun Isharer File Sharing Wizard — exploitation likelihood rose sharply (EPSS 18% → 34% · rising (+16%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apple Multiple Products: 3 CVEs added to CISA KEV today.
- Upredsun Isharer File Sharing Wizard — exploitation likelihood rose sharply (EPSS 18% → 34% · rising (+16%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 5 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 5 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **20** |


## CVEs

### CVE-2021-30952
**Apple Multiple Products Integer Overflow or Wraparound Vulnerability**
- **Signals:** KEV
- **Asset:** apple safari
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T13:44:17.940
- **CWE:** CWE-190
- **CWE:** CWE-190
- **Risk score:** 88
- **KEV:** added 2026-03-05

> An integer overflow was addressed with improved input validation. This issue is fixed in tvOS 15.2, macOS Monterey 12.1, Safari 15.2, iOS 15.2 and iPadOS 15.2, watchOS 8.3. Processing maliciously crafted web content may lead to arbitrary code execution.

### CVE-2010-2330
**upredsun isharer_file_sharing_wizard Buffer Overflow**
- **Signals:** EPSS
- **Asset:** upredsun isharer_file_sharing_wizard
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 17.6% (2025-11-09) → 33.7% (2026-03-05), Δ +16.2%**

> Stack-based buffer overflow in iSharer File Sharing Wizard 1.5.0 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a long Content-Length header.

### CVE-2026-0848
**nltk nltk RCE**
- **Signals:** CVSS
- **Asset:** nltk nltk
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T14:56:46.883
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-03-05)

> NLTK versions <=3.9.2 are vulnerable to arbitrary code execution due to improper input validation in the StanfordSegmenter module. The module dynamically loads external Java .jar files without verification or sandboxing. An attacker can supply or replace the JAR file, enabling th…

### CVE-2007-0059
**apple quicktime**
- **Signals:** EPSS
- **Asset:** apple quicktime
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 81
- **EPSS 11.9% (2025-08-24) → 25.8% (2026-03-05), Δ +13.9%**

> Cross-zone scripting vulnerability in Apple Quicktime 3 to 7.1.3 allows remote user-assisted attackers to execute arbitrary code and list filesystem contents via a QuickTime movie (.MOV) with an HREF Track (HREFTrack) that contains an automatic action tag with a local URI, which …

### CVE-2008-0100
**white_dune white_dune Buffer Overflow**
- **Signals:** EPSS
- **Asset:** white_dune white_dune
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 15.1% (2025-10-27) → 29.0% (2026-03-05), Δ +13.9%**

> Stack-based buffer overflow in the Scene::errorf function in Scene.cpp in White_Dune 0.29 beta791 and earlier allows remote attackers to execute arbitrary code via a long string in a .WRL file.

### CVE-2010-2311
**power-tab power_tab_editor Buffer Overflow**
- **Signals:** EPSS
- **Asset:** power-tab power_tab_editor
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 8.0% (2025-11-07) → 23.2% (2026-03-05), Δ +15.2%**

> Stack-based buffer overflow in Power Tab Editor 1.7 build 80 allows user-assisted remote attackers to execute arbitrary code via a .ptb file with a long font name.

### CVE-2010-2329
**rosoftengineering rosoft_audio_converter Buffer Overflow**
- **Signals:** EPSS
- **Asset:** rosoftengineering rosoft_audio_converter
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 10.3% (2025-11-09) → 23.0% (2026-03-05), Δ +12.7%**

> Buffer overflow in Rosoft Audio Converter 4.4.4 allows remote attackers to execute arbitrary code via a long playlist entry in a .m3u file.

### CVE-2017-7921
**Hikvision Multiple Products Improper Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** hikvision ds-2cd2032-i_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:06:58.603
- **CWE:** CWE-287
- **CWE:** CWE-287
- **Risk score:** 88
- **KEV:** added 2026-03-05

> An Improper Authentication issue was discovered in Hikvision DS-2CD2xx2F-I Series V5.2.0 build 140721 to V5.4.0 build 160530, DS-2CD2xx0F-I Series V5.2.0 build 140721 to V5.4.0 Build 160401, DS-2CD2xx2FWD Series V5.3.1 build 150410 to V5.4.4 Build 161125, DS-2CD4x2xFWD Series V5.…

### CVE-2021-22681
**Rockwell Multiple Products Insufficient Protected Credentials Vulnerability**
- **Signals:** KEV
- **Asset:** rockwellautomation factorytalk_services_platform
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T13:44:06.370
- **CWE:** CWE-522
- **CWE:** CWE-522
- **Risk score:** 88
- **KEV:** added 2026-03-05

> Rockwell Automation Studio 5000 Logix Designer Versions 21 and later, and RSLogix 5000 Versions 16 through 20 use a key to verify Logix controllers are communicating with Rockwell Automation CompactLogix 1768, 1769, 5370, 5380, 5480: ControlLogix 5550, 5560, 5570, 5580; DriveLogi…

### CVE-2023-41974
**Apple iOS and iPadOS Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** apple ipados
- **Attack:** Use-After-Free
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-12T13:25:14.333
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2026-03-05

> A use-after-free issue was addressed with improved memory management. This issue is fixed in iOS 17 and iPadOS 17, iOS 15.8.7 and iPadOS 15.8.7. An app may be able to execute arbitrary code with kernel privileges.

### CVE-2023-43000
**Apple Multiple products Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** apple safari
- **Attack:** Memory Corruption
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-12T13:25:11.910
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2026-03-05

> A use-after-free issue was addressed with improved memory management. This issue is fixed in macOS Ventura 13.5, iOS 16.6 and iPadOS 16.6, Safari 16.6, iOS 15.8.7 and iPadOS 15.8.7. Processing maliciously crafted web content may lead to memory corruption.

### CVE-2026-21536
**microsoft devices_pricing_program RCE**
- **Signals:** CVSS
- **Asset:** microsoft devices_pricing_program
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-16T15:40:44.357
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-05)

> Microsoft Devices Pricing Program Remote Code Execution Vulnerability

### CVE-2026-21622
**hex hexpm**
- **Signals:** CVSS
- **Asset:** hex hexpm
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-06T17:17:07.780
- **CWE:** CWE-613
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-03-05)

> Insufficient Session Expiration vulnerability in hexpm hexpm/hexpm ('Elixir.Hexpm.Accounts.PasswordReset' module) allows Account Takeover.

Password reset tokens generated via the "Reset your password" flow do not expire. When a user requests a password reset, Hex sends an email …

### CVE-2026-28391
**openclaw openclaw**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-10T18:18:45.970
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-03-05)

> OpenClaw versions prior to 2026.2.2 fail to properly validate Windows cmd.exe metacharacters in allowlist-gated exec requests (non-default configuration), allowing attackers to bypass command approval restrictions. Remote attackers can craft command strings with shell metacharact…

### CVE-2026-28446
**openclaw openclaw Auth Bypass**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-11T14:16:26.753
- **CWE:** CWE-303
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-03-05)

> OpenClaw versions prior to 2026.2.1 with the voice-call extension installed and enabled contain an authentication bypass vulnerability in inbound allowlist policy validation that accepts empty caller IDs and uses suffix-based matching instead of strict equality. Remote attackers …

### CVE-2026-28466
**openclaw openclaw**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-09T15:30:16.490
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-05)

> OpenClaw versions prior to 2026.2.14 contain a vulnerability in the gateway in which it fails to sanitize internal approval fields in node.invoke parameters, allowing authenticated clients to bypass exec approval gating for system.run commands. Attackers with valid gateway creden…

### CVE-2026-28470
**openclaw openclaw**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-25T15:16:40.070
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-03-05)

> OpenClaw versions prior to 2026.2.2 contain an exec approvals (must be enabled) allowlist bypass vulnerability that allows attackers to execute arbitrary commands by injecting command substitution syntax. Attackers can bypass the allowlist protection by embedding unescaped $() or…

### CVE-2026-28472
**openclaw openclaw**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-09T20:40:40.920
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-03-05)

> OpenClaw versions prior to 2026.2.2 contain a vulnerability in the gateway WebSocket connect handshake in which it allows skipping device identity checks when auth.token is present but not validated. Attackers can connect to the gateway without providing device identity or pairin…

### CVE-2026-28474
**openclaw openclaw**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-06T14:49:59.807
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-05)

> OpenClaw's Nextcloud Talk plugin versions prior to 2026.2.6 accept equality matching on the mutable actor.name display name field for allowlist validation, allowing attackers to bypass DM and room allowlists. An attacker can change their Nextcloud display name to match an allowli…

### CVE-2026-29188
**filebrowser filebrowser**
- **Signals:** CVSS
- **Asset:** filebrowser filebrowser
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T19:42:36.507
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-05)

> File Browser provides a file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit files. Prior to version 2.61.1, a broken access control vulnerability in the TUS protocol DELETE endpoint allows authenticated users with on…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-05*
