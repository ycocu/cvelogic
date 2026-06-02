# Daily Threat Intelligence — November 19, 2025

**Digest window (UTC):** 2025-11-19
**Generated:** 2026-06-02T07:33:49Z

## Threat brief

Google Chromium V8 added to CISA KEV — confirmed in-the-wild exploitation. · Adobe Flash Player — exploitation likelihood rose sharply (EPSS 41% → 61% · rising (+20%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Google Chromium V8 added to CISA KEV — confirmed in-the-wild exploitation.
- Adobe Flash Player — exploitation likelihood rose sharply (EPSS 41% → 61% · rising (+20%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2025-13223
**Google Chromium V8 Type Confusion Vulnerability**
- **Signals:** KEV
- **Asset:** google chrome
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-02T14:33:52.680
- **CWE:** CWE-843
- **CWE:** CWE-843
- **Risk score:** 88
- **KEV:** added 2025-11-19

> Type Confusion in V8 in Google Chrome prior to 142.0.7444.175 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page. (Chromium security severity: High)

### CVE-2017-2988
**adobe flash_player RCE**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-787
- **Risk score:** 84
- **EPSS 40.9% (2025-07-01) → 60.9% (2025-11-19), Δ +20.0%**

> Adobe Flash Player versions 24.0.0.194 and earlier have an exploitable memory corruption vulnerability when performing garbage collection. Successful exploitation could lead to arbitrary code execution.

### CVE-2025-63224
**itel idenc_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** itel idenc_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T19:46:26.840
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-19)

> The Itel DAB Encoder (IDEnc build 25aec8d) is vulnerable to Authentication Bypass due to improper JWT validation across devices. Attackers can reuse a valid JWT token obtained from one device to authenticate and gain administrative access to any other device running the same firm…

### CVE-2007-6189
**bitdefender online_anti-virus_scanner Buffer Overflow**
- **Signals:** EPSS
- **Asset:** bitdefender online_anti-virus_scanner
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 12.7% (2025-09-18) → 23.2% (2025-11-19), Δ +10.6%**

> A certain ActiveX control in (1) OScan8.ocx and (2) Oscan81.ocx in BitDefender Online Anti-Virus Scanner 8.0 allows remote attackers to execute arbitrary code via a long argument to the InitX method that begins with a "%%" sequence, which is misinterpreted as a Unicode string and…

### CVE-2025-13315
**lynxtechnology twonky_server**
- **Signals:** CVSS
- **Asset:** lynxtechnology twonky_server
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-02T16:42:19.270
- **CWE:** CWE-420
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-19)

> Twonky Server 8.5.2 on Linux and Windows is vulnerable to an access control flaw. An unauthenticated attacker can bypass web service API authentication controls to leak a log file and read the administrator's username and encrypted password.

### CVE-2025-34328
**audiocodes fax_server privilege escalation**
- **Signals:** CVSS
- **Asset:** audiocodes fax_server
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-12T16:10:36.253
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-19)

> AudioCodes Fax Server and Auto-Attendant IVR appliances versions up to and including 2.6.23 include a web administration component (F2MAdmin) that exposes an unauthenticated script-management endpoint at AudioCodes_files/utils/IVR/diagram/ajaxScript.php. The saveScript action wri…

### CVE-2025-34329
**audiocodes fax_server**
- **Signals:** CVSS
- **Asset:** audiocodes fax_server
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-12T16:09:44.737
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-19)

> AudioCodes Fax Server and Auto-Attendant IVR appliances versions up to and including 2.6.23 expose an unauthenticated backup upload endpoint at AudioCodes_files/ajaxBackupUploadFile.php in the F2MAdmin web interface. The script derives a backup folder path from application config…

### CVE-2025-63206
**dasannetworks ds2924_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** dasannetworks ds2924_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T14:09:23.310
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-19)

> An authentication bypass issue was discovered in Dasan Switch DS2924 web based interface, firmware versions 1.01.18 and 1.02.00, allowing attackers to gain escalated privileges via storing crafted cookies in the web browser.

### CVE-2025-63207
**rvr tex1002lcd_firmware**
- **Signals:** CVSS
- **Asset:** rvr tex30lcd\/s_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T19:55:05.057
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-19)

> The R.V.R Elettronica TEX product (firmware TEXL-000400, Web GUI TLAN-000400) is vulnerable to broken access control due to improper authentication checks on the /_Passwd.html endpoint. An attacker can send an unauthenticated POST request to change the Admin, Operator, and User p…

### CVE-2025-63210
**newtec celoxa504_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** newtec celoxa504_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T19:56:05.363
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-19)

> The Newtec Celox UHD (models: CELOXA504, CELOXA820) running firmware version celox-21.6.13 is vulnerable to an authentication bypass. An attacker can exploit this issue by modifying intercepted responses from the /celoxservice endpoint. By injecting a forged response body during …

### CVE-2025-63213
**qvidium opera11_firmware RCE**
- **Signals:** CVSS
- **Asset:** qvidium opera11_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T18:49:01.660
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-19)

> The QVidium Opera11 device (firmware version 2.9.0-Ax4x-opera11) is vulnerable to Remote Code Execution (RCE) due to improper input validation on the /cgi-bin/net_ping.cgi endpoint. An attacker can exploit this vulnerability by sending a specially crafted GET request with a malic…

### CVE-2025-65021
**rallly rallly**
- **Signals:** CVSS
- **Asset:** rallly rallly
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-25T15:32:53.190
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-19)

> Rallly is an open-source scheduling and collaboration tool. Prior to version 4.5.4, an Insecure Direct Object Reference (IDOR) vulnerability exists in the poll finalization feature of the application. Any authenticated user can finalize a poll they do not own by manipulating the …

### CVE-2025-65095
**Lookyloo is a web interface that allows users to capture a website page and then display a tree of domains that call each other.**
- **Signals:** CVSS
- **Attack:** XSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-11-19)

> Lookyloo is a web interface that allows users to capture a website page and then display a tree of domains that call each other. Prior to version 1.35.1, there is potential cross-site scripting on index and tree page. This issue has been patched in version 1.35.1.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-19*
