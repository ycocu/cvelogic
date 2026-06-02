# Daily Threat Intelligence — April 14, 2026

**Digest window (UTC):** 2026-04-14
**Generated:** 2026-06-02T07:34:55Z

## Threat brief

Microsoft SharePoint Server: 2 CVEs added to CISA KEV today. · Abus Tvip 10000 Firmware — exploitation likelihood rose sharply (EPSS 49% → 62% · rising (+14%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft SharePoint Server: 2 CVEs added to CISA KEV today.
- Abus Tvip 10000 Firmware — exploitation likelihood rose sharply (EPSS 49% → 62% · rising (+14%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2009-0238
**Microsoft Office Remote Code Execution**
- **Signals:** KEV
- **Asset:** microsoft excel
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:42:50.857
- **CWE:** CWE-94
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2026-04-14

> Microsoft Office Excel 2000 SP3, 2002 SP3, 2003 SP3, and 2007 SP1; Excel Viewer 2003 Gold and SP3; Excel Viewer; Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats SP1; and Excel in Microsoft Office 2004 and 2008 for Mac allow remote attackers to execute arbitra…

### CVE-2018-17879
**abus tvip_10000_firmware**
- **Signals:** EPSS
- **Asset:** abus tvip_10000_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:55:07.530
- **CWE:** CWE-78
- **Risk score:** 86
- **EPSS 48.7% (2025-12-07) → 62.2% (2026-04-14), Δ +13.5%**

> An issue was discovered on certain ABUS TVIP cameras. The CGI scripts allow remote attackers to execute code via system() as root. There are several injection points in various scripts.

### CVE-2026-35031
**jellyfin jellyfin Path Traversal**
- **Signals:** CVSS
- **Asset:** jellyfin jellyfin
- **Attack:** Path Traversal
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T17:44:25.707
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-14)

> Jellyfin is an open source self hosted media server. Versions prior to 10.11.7 contain a vulnerability chain in the subtitle upload endpoint (POST /Videos/{itemId}/Subtitles), where the Format field is not validated, allowing path traversal via the file extension and enabling arb…

### CVE-2026-27246
**adobe connect XSS**
- **Signals:** CVSS
- **Asset:** adobe connect
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T19:35:59.880
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-14)

> Adobe Connect versions 2025.3, 12.10 and earlier are affected by a DOM-based Cross-Site Scripting (XSS) vulnerability. An attacker could exploit this issue by manipulating the DOM environment to execute malicious JavaScript within the context of the victim's browser. Exploitation…

### CVE-2026-27303
**adobe connect RCE**
- **Signals:** CVSS
- **Asset:** adobe connect
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T19:36:22.250
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-04-14)

> Adobe Connect versions 2025.3, 12.10 and earlier are affected by a Deserialization of Untrusted Data vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue does not require user interaction. Scope is changed.

### CVE-2026-27304
**adobe coldfusion RCE**
- **Signals:** CVSS
- **Asset:** adobe coldfusion
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-16T14:42:47.237
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-14)

> ColdFusion versions 2023.18, 2025.6 and earlier are affected by an Improper Input Validation vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue does not require user interaction.

### CVE-2026-32201
**Microsoft SharePoint Server Improper Input Validation Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft sharepoint_server
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-28T14:27:53.370
- **CWE:** CWE-20
- **Risk score:** 88
- **KEV:** added 2026-04-14

> Improper input validation in Microsoft Office SharePoint allows an unauthorized attacker to perform spoofing over a network.

### CVE-2026-33824
**microsoft windows_10_1607**
- **Signals:** CVSS
- **Asset:** microsoft windows_10_1607
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-17T19:21:23.993
- **CWE:** CWE-415
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-14)

> Double free in Windows IKE Extension allows an unauthorized attacker to execute code over a network.

### CVE-2026-34457
**oauth2_proxy_project oauth2_proxy Auth Bypass**
- **Signals:** CVSS
- **Asset:** oauth2_proxy_project oauth2_proxy
- **Attack:** Auth Bypass
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T14:14:48.253
- **CWE:** CWE-290
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-14)

> OAuth2 Proxy is a reverse proxy that provides authentication using OAuth2 providers. Versions prior to 7.15.2 contain a configuration-dependent authentication bypass in deployments where OAuth2 Proxy is used with an auth_request-style integration (such as nginx auth_request) and …

### CVE-2026-34615
**adobe connect RCE**
- **Signals:** CVSS
- **Asset:** adobe connect
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T19:36:40.277
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-14)

> Adobe Connect versions 2025.3, 12.10 and earlier are affected by a Deserialization of Untrusted Data vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue does not require user interaction. Scope is changed.

### CVE-2026-35033
**jellyfin jellyfin**
- **Signals:** CVSS
- **Asset:** jellyfin jellyfin
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T14:02:45.350
- **CWE:** CWE-88
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-14)

> Jellyfin is an open source self hosted media server. Versions prior to 10.11.7 contain an unauthenticated arbitrary file read vulnerability via ffmpeg argument injection through the StreamOptions query parameter parsing mechanism. The ParseStreamOptions method in StreamingHelpers…

### CVE-2026-39399
**NuGet Gallery is a package repository that powers nuget.org.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-17T15:38:09.243
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-04-14)

> NuGet Gallery is a package repository that powers nuget.org. A security vulnerability exists in the NuGetGallery backend job’s handling of .nuspec files within NuGet packages. An attacker can supply a crafted nuspec file with malicious metadata, leading to cross package metadata …

### CVE-2026-5752
**Sandbox Escape Vulnerability in Terrarium allows arbitrary code execution with root privileges on a host process via JavaScript prototype...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-21T15:16:37.563
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-14)

> Sandbox Escape Vulnerability in Terrarium allows arbitrary code execution with root privileges on a host process via JavaScript prototype chain traversal.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-14*
