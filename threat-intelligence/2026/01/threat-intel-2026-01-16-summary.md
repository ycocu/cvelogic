# Daily Threat Intelligence — January 16, 2026

**Digest window (UTC):** 2026-01-16
**Generated:** 2026-06-02T07:34:12Z

## Threat brief

Tony Million Tuniac — exploitation likelihood rose sharply (EPSS 6.0% → 26% · rising (+20%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Tony Million Tuniac — exploitation likelihood rose sharply (EPSS 6.0% → 26% · rising (+20%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 9 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **19** |


## CVEs

### CVE-2009-4867
**tony_million tuniac Buffer Overflow**
- **Signals:** EPSS
- **Asset:** tony_million tuniac
- **Attack:** Buffer Overflow
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 77
- **EPSS 6.0% (2025-03-30) → 26.0% (2026-01-16), Δ +19.9%**

> Buffer overflow in Tuniac 090517c allows remote attackers to cause a denial of service (application crash) or possibly execute arbitrary code via a long URL in a .m3u playlist file.

### CVE-2017-12478
**kaseya unitrends_backup privilege escalation**
- **Signals:** EPSS
- **Asset:** kaseya unitrends_backup
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-287
- **Risk score:** 86
- **EPSS 63.6% (2025-12-02) → 81.6% (2026-01-16), Δ +18.0%**

> It was discovered that the api/storage web interface in Unitrends Backup (UB) before 10.0.0 has an issue in which one of its input parameters was not validated. A remote attacker could use this flaw to bypass authentication and execute arbitrary commands with root privilege on th…

### CVE-2026-23800
**Incorrect Privilege Assignment vulnerability in Modular DS modular-connector allows Privilege Escalation.This issue affects Modular DS: f...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-16)

> Incorrect Privilege Assignment vulnerability in Modular DS modular-connector allows Privilege Escalation.This issue affects Modular DS: from 2.5.2 before 2.6.0.

### CVE-2009-2917
**imtoo mpeg_encoder Buffer Overflow**
- **Signals:** EPSS
- **Asset:** imtoo mpeg_encoder
- **Attack:** Buffer Overflow
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 77
- **EPSS 4.6% (2025-03-30) → 17.2% (2026-01-16), Δ +12.6%**

> Stack-based buffer overflow in ImTOO MPEG Encoder 3.1.53 allows remote attackers to cause a denial of service (crash) or possibly execute arbitrary code via a crafted string in a (1) .cue or (2) .m3u playlist file.

### CVE-2009-2961
**kolmck kol_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** kolmck kol_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 5.0% (2025-03-30) → 17.2% (2026-01-16), Δ +12.3%**

> Stack-based buffer overflow in Thaddy de Konng KOL Player 1.0 allows remote attackers to cause a denial of service (crash) or execute arbitrary code via a long URL in a .MP3 playlist file.

### CVE-2009-3428
**otbcode easy_music_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** otbcode easy_music_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 9.6% (2025-03-30) → 25.9% (2026-01-16), Δ +16.3%**

> Stack-based buffer overflow in Easy Music Player 1.0.0.2 allows remote attackers to execute arbitrary code via a crafted .wav file.

### CVE-2009-4863
**ultraplayer ultraplayer_media_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ultraplayer ultraplayer_media_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 8.0% (2025-10-01) → 23.2% (2026-01-16), Δ +15.2%**

> Stack-based buffer overflow in UltraPlayer Media Player 2.112 allows remote attackers to execute arbitrary code via a long string in a .usk file.

### CVE-2010-1939
**apple safari Use-After-Free**
- **Signals:** EPSS
- **Asset:** apple safari
- **Attack:** Use-After-Free
- **CVSS max:** 7.6
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-399
- **Risk score:** 82
- **EPSS 50.7% (2025-05-06) → 64.9% (2026-01-16), Δ +14.1%**

> Use-after-free vulnerability in Apple Safari 4.0.5 on Windows allows remote attackers to execute arbitrary code by using window.open to create a popup window for a crafted HTML document, and then calling the parent window's close method, which triggers improper handling of a dele…

### CVE-2012-10064
**Omni Secure Files plugin versions prior to 0.1.14 contain an arbitrary file upload vulnerability in the bundled plupload example endpoint.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-16)

> Omni Secure Files plugin versions prior to 0.1.14 contain an arbitrary file upload vulnerability in the bundled plupload example endpoint. The /wp-content/plugins/omni-secure-files/plupload/examples/upload.php handler allows unauthenticated uploads without enforcing safe file typ…

### CVE-2014-4862
**netmaster cbw700_software**
- **Signals:** EPSS
- **Asset:** netmaster cbw700_software
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-200
- **Risk score:** 78
- **EPSS 54.3% (2025-10-09) → 70.4% (2026-01-16), Δ +16.2%**

> The Netmaster CBW700N cable modem with software 81.447.392110.729.024 has an SNMP community of public, which allows remote attackers to obtain sensitive credential, key, and SSID information via an SNMP request.

### CVE-2015-6946
**microfocus accurev Buffer Overflow**
- **Signals:** EPSS
- **Asset:** microfocus accurev
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 26.2% (2025-06-29) → 37.1% (2026-01-16), Δ +10.9%**

> Multiple stack-based buffer overflows in the Reprise License Manager service in Borland AccuRev allow remote attackers to execute arbitrary code via the (1) akey or (2) actserver parameter to the activate_doit function or (3) licfile parameter to the service_startup_doit function…

### CVE-2025-14510
**Incorrect Implementation of Authentication Algorithm vulnerability in ABB ABB Ability OPTIMAX.This issue affects ABB Ability OPTIMAX: 6.1...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-303
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-16)

> Incorrect Implementation of Authentication Algorithm vulnerability in ABB ABB Ability OPTIMAX.This issue affects ABB Ability OPTIMAX: 6.1, 6.2, from 6.3.0 before 6.3.1-251120, from 6.4.0 before 6.4.1-251120.

### CVE-2025-14894
**livewire-filemanager filemanager RCE**
- **Signals:** CVSS
- **Asset:** livewire-filemanager filemanager
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-23T17:04:25.370
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-16)

> Livewire Filemanager, commonly used in Laravel applications, contains LivewireFilemanagerComponent.php, which does not perform file type and MIME validation, allowing for RCE through upload of a malicious php file that can then be executed via the /storage/ URL if a commonly perf…

### CVE-2025-60021
**apache brpc Command Injection**
- **Signals:** CVSS
- **Asset:** apache brpc
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-21T13:46:39.423
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-16)

> Remote command injection vulnerability in heap profiler builtin service in Apache bRPC ((all versions < 1.15.0)) on all platforms allows attacker to inject remote command.



Root Cause: The bRPC heap profiler built-in service (/pprof/heap) does not validate the user-provided ext…

### CVE-2026-21623
**stackideas easydiscuss cross-site scripting**
- **Signals:** CVSS
- **Asset:** stackideas easydiscuss
- **Attack:** cross-site scripting
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T18:42:53.640
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-16)

> Lack of input filterung leads to a persistent XSS vulnerability in the forum post handling of the Easy Discuss component for Joomla.

### CVE-2026-21624
**stackideas easydiscuss cross-site scripting**
- **Signals:** CVSS
- **Asset:** stackideas easydiscuss
- **Attack:** cross-site scripting
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T18:43:24.353
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-16)

> Lack of input filterung leads to a persistent XSS vulnerability in the user avatar text handling of the Easy Discuss component for Joomla.

### CVE-2026-23523
**openagentplatform dive**
- **Signals:** CVSS
- **Asset:** openagentplatform dive
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-09T20:45:56.863
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-01-16)

> Dive is an open-source MCP Host Desktop Application that enables integration with function-calling LLMs. Prior to 0.13.0, crafted deeplink can install an attacker-controlled MCP server configuration without sufficient user confirmation and can lead to arbitrary local command exec…

### CVE-2026-23722
**wegia wegia XSS**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** XSS
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T18:27:52.323
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-16)

> WeGIA is a Web Manager for Charitable Institutions. Prior to 3.6.2, a Reflected Cross-Site Scripting (XSS) vulnerability was discovered in the WeGIA system, specifically within the html/memorando/insere_despacho.php file. The application fails to properly sanitize or encode user-…

### CVE-2026-23744
**mcpjam inspector RCE**
- **Signals:** CVSS
- **Asset:** mcpjam inspector
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T14:19:59.880
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-16)

> MCPJam inspector is the local-first development platform for MCP servers. Versions 1.4.2 and earlier are vulnerable to remote code execution (RCE) vulnerability, which allows an attacker to send a crafted HTTP request that triggers the installation of an MCP server, leading to RC…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-16*
