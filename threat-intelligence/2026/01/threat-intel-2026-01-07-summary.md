# Daily Threat Intelligence — January 07, 2026

**Digest window (UTC):** 2026-01-07
**Generated:** 2026-06-02T07:34:08Z

## Threat brief

Hewlett Packard Enterprise (HPE) OneView added to CISA KEV — confirmed in-the-wild exploitation. · Sonicspot Audioactive Player — exploitation likelihood rose sharply (EPSS 10% → 28% · rising (+18%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Hewlett Packard Enterprise (HPE) OneView added to CISA KEV — confirmed in-the-wild exploitation.
- Sonicspot Audioactive Player — exploitation likelihood rose sharply (EPSS 10% → 28% · rising (+18%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2009-0556
**Microsoft Office PowerPoint Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft office_powerpoint
- **Attack:** Memory Corruption
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:47:07.837
- **CWE:** CWE-94
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2026-01-07

> Microsoft Office PowerPoint 2000 SP3, 2002 SP3, and 2003 SP3, and PowerPoint in Microsoft Office 2004 for Mac, allows remote attackers to execute arbitrary code via a PowerPoint file with an OutlineTextRefAtom containing an an invalid index value that triggers memory corruption, …

### CVE-2009-1815
**sonicspot audioactive_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** sonicspot audioactive_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 10.3% (2025-10-18) → 28.5% (2026-01-07), Δ +18.2%**

> Stack-based buffer overflow in Sonic Spot Audioactive Player 1.93b allows remote attackers to execute arbitrary code via a long string in a playlist file, as demonstrated by a long .mp3 URL in a .m3u file.

### CVE-2025-61492
**gongrzhe terminal-controller-mcp Command Injection**
- **Signals:** CVSS
- **Asset:** gongrzhe terminal-controller-mcp
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T01:40:38.973
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-07)

> A command injection vulnerability in the execute_command function of terminal-controller-mcp 0.1.7 allows attackers to execute arbitrary commands via a crafted input.

### CVE-2009-1644
**sorinara streaming_audio_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** sorinara streaming_audio_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 9.2% (2025-10-04) → 26.1% (2026-01-07), Δ +16.9%**

> Stack-based buffer overflow in Sorinara Streaming Audio Player 0.9 allows remote attackers to execute arbitrary code via a crafted .pla file.

### CVE-2009-1645
**mini-stream easy_rm-mp3_converter Buffer Overflow**
- **Signals:** EPSS
- **Asset:** mini-stream easy_rm-mp3_converter
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 11.3% (2025-10-04) → 25.6% (2026-01-07), Δ +14.3%**

> Multiple stack-based buffer overflows in Mini-stream Easy RM-MP3 Converter 3.0.0.7 allow remote attackers to execute arbitrary code via (1) a long rtsp URL in a .ram file and (2) a long string in the HREF attribute of a REF element in a .asx file.

### CVE-2009-1660
**urusoft viplay3 Buffer Overflow**
- **Signals:** EPSS
- **Asset:** urusoft viplay3
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 8.1% (2025-12-03) → 23.3% (2026-01-07), Δ +15.3%**

> Stack-based buffer overflow in URUWorks ViPlay3 3.0 and earlier allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a long file entry in a .vpl file.

### CVE-2009-1674
**microchip mplab_ide Buffer Overflow**
- **Signals:** EPSS
- **Asset:** microchip mplab_ide
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 84
- **EPSS 5.2% (2025-03-30) → 17.1% (2026-01-07), Δ +11.9%**

> Stack-based buffer overflow in Microchip MPLAB IDE 8.30 allows user-assisted remote attackers to execute arbitrary code via a long .cof pathname in a [TOOL_SETTINGS] section in a .mcp file, possibly a related issue to CVE-2009-1608.

### CVE-2009-1817
**digimode10 maya Buffer Overflow**
- **Signals:** EPSS
- **Asset:** digimode10 maya
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 6.7% (2025-10-18) → 20.6% (2026-01-07), Δ +14.0%**

> Multiple buffer overflows in DigiMode Maya 1.0.2 allow remote attackers to execute arbitrary code via a long string in a malformed (1) .m3u or (2) .m3l playlist file.

### CVE-2025-12543
**redhat build_of_apache_camel**
- **Signals:** CVSS
- **Asset:** redhat build_of_apache_camel
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD modified:** 2026-03-18T16:16:22.420
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-01-07)

> A flaw was found in the Undertow HTTP server core, which is used in WildFly, JBoss EAP, and other Java applications. The Undertow library fails to properly validate the Host header in incoming HTTP requests.As a result, requests containing malformed or malicious Host headers are …

### CVE-2025-32303
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Mojoomla WPCHURCH church-management...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:28:56.083
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-07)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Mojoomla WPCHURCH church-management allows Blind SQL Injection.This issue affects WPCHURCH: from n/a through <= 2.7.0.

### CVE-2025-37164
**Hewlett Packard Enterprise (HPE) OneView Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** hpe oneview
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-10T02:00:01.860
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2026-01-07

> A remote code execution issue exists in HPE OneView.

### CVE-2025-47552
**Deserialization of Untrusted Data vulnerability in Digital zoom studio DZS Video Gallery dzs-videogallery allows Object Injection.This is...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:30:28.423
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-07)

> Deserialization of Untrusted Data vulnerability in Digital zoom studio DZS Video Gallery dzs-videogallery allows Object Injection.This issue affects DZS Video Gallery: from n/a through <= 12.39.

### CVE-2025-69222
**librechat librechat SSRF**
- **Signals:** CVSS
- **Asset:** librechat librechat
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T21:36:03.330
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-07)

> LibreChat is a ChatGPT clone with additional features. Version 0.8.1-rc2 is prone to a server-side request forgery (SSRF)
vulnerability due to missing restrictions of the Actions feature in the default configuration. LibreChat enables users to configure agents with predefined ins…

### CVE-2026-0650
**OpenFlagr versions prior to and including 1.1.18 contain an authentication bypass vulnerability in the HTTP middleware.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-07)

> OpenFlagr versions prior to and including 1.1.18 contain an authentication bypass vulnerability in the HTTP middleware. Due to improper handling of path normalization in the whitelist logic, crafted requests can bypass authentication and access protected API endpoints without val…

### CVE-2026-21854
**tarkov tarkov_data_manager Auth Bypass**
- **Signals:** CVSS
- **Asset:** tarkov tarkov_data_manager
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T16:21:11.813
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-07)

> The Tarkov Data Manager is a tool to manage the Tarkov item data. Prior to 02 January 2025, an authentication bypass vulnerability in the login endpoint allows any unauthenticated user to gain full admin access to the Tarkov Data Manager admin panel by exploiting a JavaScript pro…

### CVE-2026-21855
**tarkov tarkov_data_manager cross-site scripting**
- **Signals:** CVSS
- **Asset:** tarkov tarkov_data_manager
- **Attack:** cross-site scripting
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T16:20:50.047
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-07)

> The Tarkov Data Manager is a tool to manage the Tarkov item data. Prior to 02 January 2025, a reflected Cross Site Scripting (XSS) vulnerability in the toast notification system allows any attacker to execute arbitrary JavaScript in the context of a victim's browser session by cr…

### CVE-2026-22540
**The massive sending of ARP requests causes a denial of service on one board of the charger that allows control of the EV interfaces.**
- **Signals:** CVSS
- **Attack:** DoS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-400
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-07)

> The massive sending of ARP requests causes a denial of service on one board of the charger that allows control of the EV interfaces. Since the board must be operating correctly for the charger to also function correctly.

### CVE-2026-22542
**An attacker with access to the system's internal network can cause a denial of service on the system by making two concurrent connections...**
- **Signals:** CVSS
- **Attack:** DoS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-400
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-07)

> An attacker with access to the system's internal network can cause a denial of service on the system by making two concurrent connections through the Telnet service.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-07*
