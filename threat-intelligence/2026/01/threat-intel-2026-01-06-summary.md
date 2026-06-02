# Daily Threat Intelligence — January 06, 2026

**Digest window (UTC):** 2026-01-06
**Generated:** 2026-06-02T07:34:08Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Qt-cute Quickteam — exploitation likelihood rose sharply (EPSS 32% → 85% · rising (+54%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Qt-cute Quickteam — exploitation likelihood rose sharply (EPSS 32% → 85% · rising (+54%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 7 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **17** |


## CVEs

### CVE-2009-1551
**qt-cute quickteam**
- **Signals:** EPSS
- **Asset:** qt-cute quickteam
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-94
- **Risk score:** 82
- **EPSS 31.6% (2025-09-25) → 85.2% (2026-01-06), Δ +53.7%**

> Multiple PHP remote file inclusion vulnerabilities in Qt quickteam 2 allow remote attackers to execute arbitrary PHP code via a URL in the (1) qte_web_path parameter to qte_web.php and the (2) qte_root parameter to bin/qte_init.php.

### CVE-2007-6254
**sap business_objects Buffer Overflow**
- **Signals:** EPSS
- **Asset:** sap business_objects
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 17.9% (2025-11-19) → 32.2% (2026-01-06), Δ +14.3%**

> Stack-based buffer overflow in the SAP Business Objects BusinessObjects RptViewerAX ActiveX control in RptViewerAX.dll in Business Objects 6.5 before CHF74 allows remote attackers to execute arbitrary code via unspecified vectors.

### CVE-2025-30996
**Unrestricted Upload of File with Dangerous Type vulnerability in Themify Themify Newsy newsy allows Upload a Web Shell to a Web Server.Th...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:27:29.643
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-06)

> Unrestricted Upload of File with Dangerous Type vulnerability in Themify Themify Newsy newsy allows Upload a Web Shell to a Web Server.This issue affects Themify Newsy: from n/a through <= 1.9.9.

### CVE-2009-1187
**poppler poppler DoS**
- **Signals:** EPSS
- **Asset:** poppler poppler
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-189
- **Risk score:** 77
- **EPSS 28.3% (2025-11-09) → 39.9% (2026-01-06), Δ +11.6%**

> Integer overflow in the JBIG2 decoding feature in Poppler before 0.10.6 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via vectors related to CairoOutputDev (CairoOutputDev.cc).

### CVE-2009-1586
**shemes grabit Buffer Overflow**
- **Signals:** EPSS
- **Asset:** shemes grabit
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 84
- **EPSS 32.3% (2025-04-26) → 43.7% (2026-01-06), Δ +11.4%**

> Stack-based buffer overflow in the NZB importer feature in GrabIt 1.7.2 Beta 3 and earlier allows remote attackers to execute arbitrary code via a crafted DTD reference in a DOCTYPE element in an NZB file.

### CVE-2009-1643
**sorinara soritong_mp3_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** sorinara soritong_mp3_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 84
- **EPSS 8.5% (2025-10-04) → 20.2% (2026-01-06), Δ +11.8%**

> Stack-based buffer overflow in Sorinara Soritong MP3 Player 1.0 allows remote attackers to execute arbitrary code via a crafted .m3u file.

### CVE-2009-2568
**sorinara streaming_audio_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** sorinara streaming_audio_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 19.7% (2025-04-26) → 30.0% (2026-01-06), Δ +10.3%**

> Stack-based buffer overflow in Sorinara Streaming Audio Player (SAP) 0.9 allows remote attackers to execute arbitrary code via a long string in a playlist (.m3u) file.

### CVE-2019-7442
**cyberark enterprise_password_vault XXE**
- **Signals:** EPSS
- **Asset:** cyberark enterprise_password_vault
- **Attack:** XXE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:48:14.750
- **CWE:** CWE-611
- **Risk score:** 84
- **EPSS 5.6% (2025-11-21) → 16.8% (2026-01-06), Δ +11.2%**

> An XML external entity (XXE) vulnerability in the Password Vault Web Access (PVWA) of CyberArk Enterprise Password Vault <=10.7 allows remote attackers to read arbitrary files or potentially bypass authentication via a crafted DTD in the SAML authentication system.

### CVE-2025-14942
**wolfssh wolfssh**
- **Signals:** CVSS
- **Asset:** wolfssh wolfssh
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-12T17:53:19.670
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-06)

> wolfSSH’s key exchange state machine can be manipulated to leak the client’s password in the clear, trick the client to send a bogus signature, or trick the client into skipping user authentication. This affects client applications with wolfSSH version 1.4.21 and earlier. Users o…

### CVE-2025-14996
**The AS Password Field In Default Registration Form plugin for WordPress is vulnerable to privilege escalation via account takeover in all...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-639
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-06)

> The AS Password Field In Default Registration Form plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 2.0.0. This is due to the plugin not properly validating a user's identity prior to updating their password. Th…

### CVE-2025-15001
**The FS Registration Password plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and i...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-639
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-06)

> The FS Registration Password plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 1.0.1. This is due to the plugin not properly validating a user's identity prior to updating their password. This makes it possible f…

### CVE-2025-15385
**tecno boomplay Auth Bypass**
- **Signals:** CVSS
- **Asset:** tecno boomplay
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T01:13:07.690
- **CWE:** CWE-345
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-06)

> Insufficient Verification of Data Authenticity vulnerability in TECNO Mobile com.Afmobi.Boomplayer allows Authentication Bypass.This issue affects com.Afmobi.Boomplayer: 7.4.63.

### CVE-2025-39477
**Missing Authorization vulnerability in Sfwebservice InWave Jobs iwjob allows Exploiting Incorrectly Configured Access Control Security Le...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:29:38.257
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-06)

> Missing Authorization vulnerability in Sfwebservice InWave Jobs iwjob allows Exploiting Incorrectly Configured Access Control Security Levels.This issue affects InWave Jobs: from n/a through <= 3.5.8.

### CVE-2025-60262
**h3c magic_ba1500l_firmware**
- **Signals:** CVSS
- **Asset:** h3c mc102-g_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T01:36:21.693
- **CWE:** CWE-276
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-06)

> An issue in H3C M102G HM1A0V200R010 wireless controller and BA1500L SWBA1A0V100R006 wireless access point, there is a misconfiguration vulnerability about vsftpd. Through this vulnerability, all files uploaded anonymously via the FTP protocol is automatically owned by the root us…

### CVE-2025-60534
**blueaccesstech cobalt_x1 Auth Bypass**
- **Signals:** CVSS
- **Asset:** blueaccesstech cobalt_x1
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T01:24:16.840
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-06)

> Blue Access Cobalt v02.000.195 suffers from an authentication bypass vulnerability, which allows an attacker to selectively proxy requests in order to operate functionality on the web application without the need to authenticate with legitimate credentials.

### CVE-2025-65212
**njhyst hy511_firmware**
- **Signals:** CVSS
- **Asset:** njhyst hy511_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T01:31:03.130
- **CWE:** CWE-565
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-06)

> An issue was discovered in NJHYST HY511 POE core before 2.1 and plugins before 0.1. The vulnerability stems from the device's insufficient cookie verification, allowing an attacker to directly request the configuration file address and download the core configuration file without…

### CVE-2026-21675
**color iccdev**
- **Signals:** CVSS
- **Asset:** color iccdev
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-12T21:00:31.740
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-06)

> iccDEV provides a set of libraries and tools for working with ICC color management profiles. Versions 2.3.1 and below contain a Use After Free vulnerability in the CIccXform::Create() function, where it deletes the hint. This issue is fixed in version 2.3.1.1.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-06*
