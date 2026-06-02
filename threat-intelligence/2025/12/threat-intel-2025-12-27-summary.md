# Daily Threat Intelligence — December 27, 2025

**Digest window (UTC):** 2025-12-27
**Generated:** 2026-06-02T07:34:03Z

## Threat brief

Mit Cgiemail — exploitation likelihood rose sharply (EPSS 16% → 44% · rising (+28%)). · 3 new critical disclosures — review patch status on exposed services.

## Executive summary

- Mit Cgiemail — exploitation likelihood rose sharply (EPSS 16% → 44% · rising (+28%)).
- 3 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 5 |
| CVSS critical disclosure | 3 |
| Patch status change | 0 |
| **Total** | **8** |


## CVEs

### CVE-2002-1652
**mit cgiemail Buffer Overflow**
- **Signals:** EPSS
- **Asset:** mit cgiemail
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 16.2% (2025-03-30) → 44.0% (2025-12-27), Δ +27.7%**

> Buffer overflow in cgicso.c for cgiemail 1.6 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a long query parameter.

### CVE-2003-1091
**DoS · EPSS dynamics**
- **Signals:** EPSS
- **Asset:** apple quicktime_broadcaster
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 17.7% (2025-03-30) → 37.1% (2025-12-27), Δ +19.5%**

> Integer overflow in MP3Broadcaster for Apple QuickTime/Darwin Streaming Server 4.1.3 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via malformed ID3 tags in MP3 files.

### CVE-2025-54322
**xspeeder sxzos RCE**
- **Signals:** CVSS
- **Asset:** xspeeder sxzos
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-09T20:33:24.920
- **CWE:** CWE-95
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-12-27)

> Xspeeder SXZOS through 2025-12-26 allows root remote code execution via base64-encoded Python code in the chkid parameter to vLogin.py. The title and oIP parameters are also used.

### CVE-2002-1605
**hp hp-ux Buffer Overflow**
- **Signals:** EPSS
- **Asset:** hp hp-ux
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 27.6% (2025-04-16) → 44.0% (2025-12-27), Δ +16.4%**

> Buffer overflow in HP Tru64 UNIX 5.1a, 5.1, 5.0a, 4.0g, and 4.0f allows attackers to execute arbitrary code via a long _XKB_CHARSET environment variable to (1) dxpause, (2) dxconsole, or (3) dtsession.

### CVE-2003-0470
**symantec security_check Buffer Overflow**
- **Signals:** EPSS
- **Asset:** symantec security_check
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 80
- **EPSS 17.7% (2025-03-30) → 27.9% (2025-12-27), Δ +10.3%**

> Buffer overflow in the "RuFSI Utility Class" ActiveX control (aka "RuFSI Registry Information Class"), as used for the Symantec Security Check service, allows remote attackers to execute arbitrary code via a long argument to CompareVersionStrings.

### CVE-2008-5764
**2500mhz worksimple**
- **Signals:** EPSS
- **Asset:** 2500mhz worksimple
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-94
- **Risk score:** 82
- **EPSS 28.4% (2025-07-18) → 38.7% (2025-12-27), Δ +10.3%**

> PHP remote file inclusion vulnerability in calendar.php in WorkSimple 1.2.1, when register_globals is enabled, allows remote attackers to execute arbitrary PHP code via a URL in the lang parameter.

### CVE-2025-66203
**lemon8866 streamvault RCE**
- **Signals:** CVSS
- **Asset:** lemon8866 streamvault
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-09T13:41:33.210
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-27)

> StreamVault is a video download integration solution. Prior to version 251126, a Remote Code Execution (RCE) vulnerability exists in the stream-vault application (SpiritApplication). The application allows administrators to configure yt-dlp arguments via the /admin/api/saveConfig…

### CVE-2025-68952
**eigent eigent RCE**
- **Signals:** CVSS
- **Asset:** eigent eigent
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-19T15:52:19.063
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-27)

> Eigent is a multi-agent Workforce. In version 0.0.60, a 1-click Remote Code Execution (RCE) vulnerability has been identified in Eigent. This vulnerability allows an attacker to execute arbitrary code on the victim's machine or server through a specific interaction (1-click). Thi…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-27*
