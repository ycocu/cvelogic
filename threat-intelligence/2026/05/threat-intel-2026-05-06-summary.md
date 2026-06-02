# Daily Threat Intelligence — May 06, 2026

**Digest window (UTC):** 2026-05-06
**Generated:** 2026-06-02T07:03:56Z

## Threat brief

Palo Alto Networks PAN-OS added to CISA KEV — confirmed in-the-wild exploitation. · Exploitation likelihood rose sharply (EPSS 54% → 69% · rising (+15%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Palo Alto Networks PAN-OS added to CISA KEV — confirmed in-the-wild exploitation.
- Exploitation likelihood rose sharply (EPSS 54% → 69% · rising (+15%)).
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

### CVE-2026-0300
**Palo Alto Networks PAN-OS Out-of-bounds Write Vulnerability**
- **Signals:** KEV
- **Asset:** paloaltonetworks pan-os
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-12T18:47:21.360
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2026-05-06

> A buffer overflow vulnerability in the User-ID™ Authentication Portal (aka Captive Portal) service of Palo Alto Networks PAN-OS software allows an unauthenticated attacker to execute arbitrary code with root privileges on the PA-Series and VM-Series firewalls by sending specially…

### CVE-2025-34101
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 85
- **EPSS 53.9% (2025-12-07) → 68.8% (2026-05-06), Δ +14.9%**

> An unauthenticated command injection vulnerability exists in Serviio Media Server versions 1.4 through 1.8 on Windows, in the /rest/action API endpoint exposed by the console component (default port 23423). The checkStreamUrl method accepts a VIDEO parameter that is passed unsani…

### CVE-2026-40281
**thecodingmachine gotenberg**
- **Signals:** CVSS
- **Asset:** thecodingmachine gotenberg
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-11T14:46:07.127
- **CWE:** CWE-88
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-06)

> Gotenberg is a Docker-powered stateless API for PDF files. In versions 8.30.1 and earlier, the metadata write endpoint validates metadata keys for control characters but leaves metadata values unsanitized. A newline character in a metadata value splits the ExifTool stdin line int…

### CVE-2006-6651
**intel 2200bg_proset_wireless Memory Corruption**
- **Signals:** EPSS
- **Asset:** intel 2200bg_proset_wireless
- **Attack:** Memory Corruption
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 80
- **EPSS 8.1% (2025-08-08) → 19.6% (2026-05-06), Δ +11.5%**

> Race condition in W29N51.SYS in the Intel 2200BG wireless driver 9.0.3.9 allows remote attackers to cause memory corruption and execute arbitrary code via a series of crafted beacon frames.  NOTE: some details are obtained solely from third party information.

### CVE-2016-0997
**adobe air Use-After-Free**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** Use-After-Free
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-416
- **Risk score:** 84
- **EPSS 52.5% (2026-05-04) → 64.5% (2026-05-06), Δ +12.0%**

> Use-after-free vulnerability in Adobe Flash Player before 18.0.0.333 and 19.x through 21.x before 21.0.0.182 on Windows and OS X and before 11.2.202.577 on Linux, Adobe AIR before 21.0.0.176, Adobe AIR SDK before 21.0.0.176, and Adobe AIR SDK & Compiler before 21.0.0.176 allows a…

### CVE-2016-0999
**adobe air Use-After-Free**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** Use-After-Free
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-416
- **Risk score:** 84
- **EPSS 52.5% (2026-05-04) → 64.5% (2026-05-06), Δ +12.0%**

> Use-after-free vulnerability in Adobe Flash Player before 18.0.0.333 and 19.x through 21.x before 21.0.0.182 on Windows and OS X and before 11.2.202.577 on Linux, Adobe AIR before 21.0.0.176, Adobe AIR SDK before 21.0.0.176, and Adobe AIR SDK & Compiler before 21.0.0.176 allows a…

### CVE-2016-1000
**adobe air Use-After-Free**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** Use-After-Free
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-416
- **Risk score:** 84
- **EPSS 50.0% (2026-05-04) → 62.4% (2026-05-06), Δ +12.4%**

> Use-after-free vulnerability in Adobe Flash Player before 18.0.0.333 and 19.x through 21.x before 21.0.0.182 on Windows and OS X and before 11.2.202.577 on Linux, Adobe AIR before 21.0.0.176, Adobe AIR SDK before 21.0.0.176, and Adobe AIR SDK & Compiler before 21.0.0.176 allows a…

### CVE-2016-1002
**adobe air DoS**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** DoS
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 84
- **EPSS 46.7% (2026-05-04) → 60.8% (2026-05-06), Δ +14.1%**

> Adobe Flash Player before 18.0.0.333 and 19.x through 21.x before 21.0.0.182 on Windows and OS X and before 11.2.202.577 on Linux, Adobe AIR before 21.0.0.176, Adobe AIR SDK before 21.0.0.176, and Adobe AIR SDK & Compiler before 21.0.0.176 allow attackers to execute arbitrary cod…

### CVE-2018-17442
**dlink central_wifimanager**
- **Signals:** EPSS
- **Asset:** dlink central_wifimanager
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:54:25.470
- **CWE:** CWE-434
- **Risk score:** 82
- **EPSS 6.7% (2026-04-24) → 17.4% (2026-05-06), Δ +10.7%**

> An issue was discovered on D-Link Central WiFi Manager before v 1.03r0100-Beta1. An unrestricted file upload vulnerability in the onUploadLogPic endpoint allows remote authenticated users to execute arbitrary PHP code.

### CVE-2023-29511
**xwiki xwiki**
- **Signals:** EPSS
- **Asset:** xwiki xwiki
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:57:12.303
- **CWE:** CWE-95
- **Risk score:** 86
- **EPSS 14.4% (2026-04-27) → 29.2% (2026-05-06), Δ +14.9%**

> XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. Any user with edit rights on a page (e.g., it's own user page), can execute arbitrary Groovy, Python or Velocity code in XWiki leading to full access to the XWiki installation…

### CVE-2023-30537
**xwiki xwiki**
- **Signals:** EPSS
- **Asset:** xwiki xwiki
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:00:22.683
- **CWE:** CWE-95
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 14.5% (2026-04-27) → 29.4% (2026-05-06), Δ +14.9%**

> XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. Any user with the right to add an object on a page can execute arbitrary Groovy, Python or Velocity code in XWiki leading to full access to the XWiki installation. The root ca…

### CVE-2025-34096
**Buffer Overflow · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 53.3% (2026-03-26) → 66.6% (2026-05-06), Δ +13.3%**

> A stack-based buffer overflow vulnerability exists in Easy File Sharing HTTP Server version 7.2. The flaw is triggered when a crafted POST request is sent to the /sendemail.ghp endpoint containing an overly long Email parameter. The application fails to properly validate the leng…

### CVE-2026-40076
**openmrs openmrs Path Traversal**
- **Signals:** CVSS
- **Asset:** openmrs openmrs
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-11T14:55:45.457
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-06)

> OpenMRS Core is an open source electronic medical record system platform. In versions 2.7.8 and earlier and versions 2.8.0 through 2.8.5, the module upload endpoint at POST `/openmrs/ws/rest/v1/module` is vulnerable to a Zip Slip path traversal attack. During automatic extraction…

### CVE-2026-41930
**Vvveb before version 1.0.8.2 contains a hard-coded credentials vulnerability in its docker-compose-apache.yaml configuration that allows...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-06T20:16:32.540
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-06)

> Vvveb before version 1.0.8.2 contains a hard-coded credentials vulnerability in its docker-compose-apache.yaml configuration that allows unauthenticated attackers to access the bundled phpMyAdmin container with pre-configured database credentials. Attackers can connect to the php…

### CVE-2026-43575
**openclaw openclaw Auth Bypass**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-07T17:03:55.283
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-06)

> OpenClaw versions 2026.2.21 before 2026.4.10 contain an authentication bypass vulnerability in the sandbox noVNC helper route that exposes interactive browser session credentials. Attackers can access the noVNC helper route without bridge authentication to gain unauthorized acces…

### CVE-2026-43578
**openclaw openclaw Privilege Escalation**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **Attack:** Privilege Escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-07T17:04:24.023
- **CWE:** CWE-184
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-06)

> OpenClaw versions 2026.3.31 before 2026.4.10 contain a privilege escalation vulnerability where heartbeat owner downgrade detection misses local background async exec completion events. Attackers can exploit this by providing untrusted completion content to leave a run in a more …

### CVE-2026-43581
**openclaw openclaw**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-07T14:41:17.497
- **CWE:** CWE-1188
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-05-06)

> OpenClaw before 2026.4.10 contains an improper network binding vulnerability in the sandbox browser CDP relay that exposes Chrome DevTools Protocol on 0.0.0.0. Attackers can access the DevTools protocol outside intended local sandbox boundaries by exploiting the overly broad bind…

### CVE-2026-43585
**openclaw openclaw**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-07T19:36:59.427
- **CWE:** CWE-672
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-06)

> OpenClaw before 2026.4.15 captures resolved bearer-auth configuration at startup, allowing revoked tokens to remain valid after SecretRef rotation. Gateway HTTP and WebSocket handlers fail to re-resolve authentication per-request, enabling attackers to use rotated-out bearer toke…

### CVE-2026-44109
**openclaw openclaw Auth Bypass**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-07T19:40:45.520
- **CWE:** CWE-1188
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-06)

> OpenClaw before 2026.4.15 contains an authentication bypass vulnerability in Feishu webhook and card-action validation that allows unauthenticated requests to reach command dispatch. Missing encryptKey configuration and blank callback tokens fail open instead of rejecting request…

### CVE-2026-7908
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-06T23:41:13.650
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-06)

> Use after free in Fullscreen in Google Chrome prior to 148.0.7778.96 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: High)

### CVE-2026-7910
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD modified:** 2026-05-12T20:16:46.490
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-06)

> Use after free in Views in Google Chrome prior to 148.0.7778.96 allowed a remote attacker who had compromised the renderer process to bypass site isolation via a crafted HTML page. (Chromium security severity: High)

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-06*
