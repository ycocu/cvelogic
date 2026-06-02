# Daily Threat Intelligence — May 14, 2026

**Digest window (UTC):** 2026-05-14
**Generated:** 2026-06-02T07:04:00Z

## Threat brief

Cisco Catalyst SD-WAN added to CISA KEV — confirmed in-the-wild exploitation. · Epati Antikor Next Generation Firewall: public exploit or PoC linked (Auth Bypass) · Microsoft Internet Explorer — exploitation likelihood rose sharply (EPSS 28% → 47% · rising (+18%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cisco Catalyst SD-WAN added to CISA KEV — confirmed in-the-wild exploitation.
- Epati Antikor Next Generation Firewall: public exploit or PoC linked (Auth Bypass)
- Microsoft Internet Explorer — exploitation likelihood rose sharply (EPSS 28% → 47% · rising (+18%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 3 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **17** |


## CVEs

### CVE-2026-20182
**Cisco Catalyst SD-WAN Controller Authentication Bypass Vulnerability**
- **Signals:** KEV
- **Asset:** cisco catalyst_sd-wan_manager
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-15T12:45:53.990
- **CWE:** CWE-287
- **Risk score:** 88
- **KEV:** added 2026-05-14

> May 2026: This security advisory provides the details and fix information for a vulnerability that was discovered and fixed after the  was disclosed in February 2026. This new advisory is for a new vulnerability in the control connection handshaking. The  section of this advisory…

### CVE-2026-25994
**pjsip pjsip Buffer Overflow**
- **Signals:** EXP
- **Asset:** pjsip pjsip
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-19T19:23:29.843
- **CWE:** CWE-120
- **Risk score:** 78
- **EXP:** ref published 2026-05-14

> PJSIP is a free and open source multimedia communication library written in C. In 2.16 and earlier, a buffer overflow vulnerability exists in PJNATH ICE Session when processing credentials with excessively long usernames.

### CVE-2020-1062
**microsoft internet_explorer RCE**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **Attack:** RCE
- **CVSS max:** 7.6
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:09:40.100
- **CWE:** CWE-787
- **Risk score:** 82
- **EPSS 28.4% (2026-01-15) → 46.8% (2026-05-14), Δ +18.4%**

> A remote code execution vulnerability exists when Internet Explorer improperly accesses objects in memory, aka 'Internet Explorer Memory Corruption Vulnerability'. This CVE ID is unique from CVE-2020-1092.

### CVE-2011-4532
**siemens automation_license_manager Path Traversal**
- **Signals:** EPSS
- **Asset:** siemens automation_license_manager
- **Attack:** Path Traversal
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-22
- **Risk score:** 78
- **EPSS 3.1% (2026-04-27) → 19.2% (2026-05-14), Δ +16.1%**

> Absolute path traversal vulnerability in the ALMListView.ALMListCtrl ActiveX control in almaxcx.dll in the graphical user interface in Siemens Automation License Manager (ALM) 2.0 through 5.1+SP1+Upd2 allows remote attackers to overwrite arbitrary files via the Save method.

### CVE-2024-23535
**ivanti avalanche Path Traversal**
- **Signals:** EPSS
- **Asset:** ivanti avalanche
- **Attack:** Path Traversal
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-06T18:28:37.263
- **CWE:** CWE-22
- **Risk score:** 84
- **EPSS 48.2% (2026-01-06) → 61.8% (2026-05-14), Δ +13.6%**

> A Path Traversal vulnerability in web component of Ivanti Avalanche before 6.4.3 allows a remote authenticated attacker to execute arbitrary commands as SYSTEM.

### CVE-2026-2624
**epati antikor_next_generation_firewall Auth Bypass**
- **Signals:** EXP
- **Asset:** epati antikor_next_generation_firewall
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T17:29:01.797
- **CWE:** CWE-306
- **Risk score:** 78
- **EXP:** ref published 2026-05-14

> Missing Authentication for Critical Function vulnerability in ePati Cyber ​​Security Technologies Inc. Antikor Next Generation Firewall (NGFW) allows Authentication Bypass.This issue affects Antikor Next Generation Firewall (NGFW): from v.2.0.1298 before v.2.0.1301.

### CVE-2026-4257
**The Contact Form by Supsystic plugin for WordPress is vulnerable to Server-Side Template Injection (SSTI) leading to Remote Code Executio...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T18:11:16.583
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2026-05-14

> The Contact Form by Supsystic plugin for WordPress is vulnerable to Server-Side Template Injection (SSTI) leading to Remote Code Execution (RCE) in all versions up to, and including, 1.7.36. This is due to the plugin using the Twig `Twig_Loader_String` template engine without san…

### CVE-2026-44212
**PrestaShop is an open source e-commerce web application.**
- **Signals:** CVSS
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-15T14:30:03.170
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-14)

> PrestaShop is an open source e-commerce web application. Prior to 8.2.6 and 9.1.1, there is a stored Cross-Site Scripting (XSS) vulnerability in the PrestaShop back-office Customer Service view. An unauthenticated attacker can submit the public Contact Us form with a malicious em…

### CVE-2026-44523
**Note Mark is an open-source note-taking application.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-15T15:16:52.960
- **CWE:** CWE-326
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-14)

> Note Mark is an open-source note-taking application. Prior to 0.19.4, no minimum length or entropy is enforced on the JWT_SECRET configuration value. The application accepts any base64-decodable secret regardless of size, including secrets as short as 1 byte. This vulnerability i…

### CVE-2026-44588
**SiYuan is an open-source personal knowledge management system.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-15T15:16:53.200
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-14)

> SiYuan is an open-source personal knowledge management system. Prior to 3.7.0,  he tooltip mouseover handler in app/src/block/popover.ts reads aria-label via getAttribute and passes it through decodeURIComponent before assigning to messageElement.innerHTML in app/src/dialog/toolt…

### CVE-2026-44592
**Gradient is a nix-based continuous integration system.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-15T14:44:49.877
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-14)

> Gradient is a nix-based continuous integration system. In 1.1.0, when GRADIENT_DISCOVERABLE=true (the default, and the NixOS module default), anyone who can reach /proto can register as a worker without any credentials by sending a fresh, never-registered worker UUID. The resulti…

### CVE-2026-44666
**HRConvert2 is a self-hosted, drag-and-drop & nosql file conversion server & share tool.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-15T15:16:53.630
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-14)

> HRConvert2 is a self-hosted, drag-and-drop & nosql file conversion server & share tool. Prior to 3.3.8, the sanitizeString() function in convertCore.php is missing backtick (`) and tab (\t) from its strip list. User input then reaches shell_exec(), where the shell interprets thes…

### CVE-2026-44670
**SiYuan is an open-source personal knowledge management system.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-15T15:16:53.737
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-14)

> SiYuan is an open-source personal knowledge management system. Prior to 3.7.0, the kernel stores Attribute View (AV / database) names without any HTML escape, then a render template uses raw strings.ReplaceAll(tpl, "${avName}", nodeAvName) to embed the name in HTML before pushing…

### CVE-2026-45375
**SiYuan is an open-source personal knowledge management system.**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-16T01:16:17.333
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-05-14)

> SiYuan is an open-source personal knowledge management system. Prior to 3.7.0, SiYuan's Bazaar (community marketplace) renders the name and version fields of a package's plugin.json (and the equivalent theme.json / template.json / widget.json / icon.json) into the Settings → Mark…

### CVE-2026-8511
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-18T18:34:17.750
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-14)

> Use after free in UI in Google Chrome prior to 148.0.7778.168 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: Critical)

### CVE-2026-8580
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-19T15:18:41.387
- **CWE:** CWE-416
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-14)

> Use after free in Mojo in Google Chrome prior to 148.0.7778.168 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: Medium)

### CVE-2026-8634
**Crabbox prior to v0.12.0 contains an environment variable exposure vulnerability that allows attackers with access to a malicious or comp...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-15T15:16:56.913
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-14)

> Crabbox prior to v0.12.0 contains an environment variable exposure vulnerability that allows attackers with access to a malicious or compromised repository to forward local secrets such as API tokens, cloud credentials, and broker tokens into the remote command environment. Attac…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-14*
