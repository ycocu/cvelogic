# Daily Threat Intelligence — September 22, 2025

**Digest window (UTC):** 2025-09-22
**Generated:** 2026-06-02T07:33:28Z

## Threat brief

Adobe Acrobat Reader — exploitation likelihood rose sharply (EPSS 37% → 53% · rising (+17%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Adobe Acrobat Reader — exploitation likelihood rose sharply (EPSS 37% → 53% · rising (+17%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2006-6236
**adobe acrobat_reader DoS**
- **Signals:** EPSS
- **Asset:** adobe acrobat_reader
- **Attack:** DoS
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 85
- **EPSS 36.9% (2025-07-22) → 53.4% (2025-09-22), Δ +16.5%**

> Adobe Reader (Adobe Acrobat Reader) 7.0 through 7.0.8 allows remote attackers to cause a denial of service and possibly execute arbitrary code via a long argument string to the (1) src, (2) setPageMode, (3) setLayoutMode, and (4) setNamedDest methods in an AcroPDF ActiveX control…

### CVE-2020-9634
**adobe framemaker RCE**
- **Signals:** EPSS
- **Asset:** adobe framemaker
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:41:00.213
- **CWE:** CWE-787
- **Risk score:** 83
- **EPSS 3.9% (2025-08-09) → 15.5% (2025-09-22), Δ +11.6%**

> Adobe Framemaker versions 2019.0.5 and below have an out-of-bounds write vulnerability. Successful exploitation could lead to arbitrary code execution.

### CVE-2025-59528
**flowiseai flowise RCE**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-23T16:45:09.443
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-22)

> Flowise is a drag & drop user interface to build a customized large language model flow. In version 3.0.5, Flowise is vulnerable to remote code execution. The CustomMCP node allows users to input configuration settings for connecting to an external MCP server. This node parses th…

### CVE-2020-9635
**adobe framemaker RCE**
- **Signals:** EPSS
- **Asset:** adobe framemaker
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:41:00.323
- **CWE:** CWE-787
- **Risk score:** 83
- **EPSS 3.9% (2025-08-09) → 15.5% (2025-09-22), Δ +11.6%**

> Adobe Framemaker versions 2019.0.5 and below have an out-of-bounds write vulnerability. Successful exploitation could lead to arbitrary code execution.

### CVE-2020-9636
**adobe framemaker RCE**
- **Signals:** EPSS
- **Asset:** adobe framemaker
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:41:00.427
- **CWE:** CWE-787
- **Risk score:** 82
- **EPSS 3.5% (2025-08-09) → 13.7% (2025-09-22), Δ +10.3%**

> Adobe Framemaker versions 2019.0.5 and below have a memory corruption vulnerability. Successful exploitation could lead to arbitrary code execution.

### CVE-2025-35042
**airship.ai acropolis privilege escalation**
- **Signals:** CVSS
- **Asset:** airship.ai acropolis
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T12:28:20.500
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-22)

> Airship AI Acropolis includes a default administrative account that uses the same credentials on every installation. Instances of Airship AI that do not change this account password are vulnerable to a remote attacker logging in and gaining the privileges of this account. Fixed i…

### CVE-2025-56074
**phpgurukul park_ticketing_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul park_ticketing_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-25T19:14:55.033
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-22)

> A SQL Injection vulnerability was discovered in the foreigner-bwdates-reports-details.php file of PHPGurukul Park Ticketing Management System v2.0. This vulnerability allows remote attackers to execute arbitrary SQL code via the fromdate parameter in a POST request.

### CVE-2025-57432
**blackmagicdesign web_presenter_4k_firmware**
- **Signals:** CVSS
- **Asset:** blackmagicdesign web_presenter_hd_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-14T19:56:50.727
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-22)

> Blackmagic Web Presenter version 3.3 exposes a Telnet service on port 9977 that accepts unauthenticated commands. This service allows remote attackers to manipulate stream settings, including changing video modes and possibly altering device functionality. No credentials or authe…

### CVE-2025-57437
**blackmagicdesign web_presenter_hd_firmware**
- **Signals:** CVSS
- **Asset:** blackmagicdesign web_presenter_hd_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-10T21:03:59.970
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-22)

> The Blackmagic Web Presenter HD firmware version 3.3 exposes sensitive information via an unauthenticated Telnet service on port 9977. When connected, the service reveals extensive device configuration data including: - Model, version, and unique identifiers - Network settings in…

### CVE-2025-57441
**blackmagicdesign atem_mini_pro_firmware**
- **Signals:** CVSS
- **Asset:** blackmagicdesign atem_mini_pro_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T20:34:42.913
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-22)

> The Blackmagic ATEM Mini Pro 2.7 exposes sensitive device and stream configuration information via an unauthenticated Telnet service on port 9990. Upon connection, the attacker can access a protocol preamble that leaks the video mode, routing configuration, input/output labels, d…

### CVE-2025-57601
**AiKaan Cloud Controller uses a single hardcoded SSH private key and the username `proxyuser` for remote terminal access to all managed Io...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-22)

> AiKaan Cloud Controller uses a single hardcoded SSH private key and the username `proxyuser` for remote terminal access to all managed IoT/edge devices. When an administrator initiates "Open Remote Terminal" from the AiKaan dashboard, the controller sends this same static private…

### CVE-2025-57602
**Insufficient hardening of the proxyuser account in the AiKaan IoT management platform, combined with the use of a shared, hardcoded SSH p...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-22)

> Insufficient hardening of the proxyuser account in the AiKaan IoT management platform, combined with the use of a shared, hardcoded SSH private key, allows remote attackers to authenticate to the cloud controller, gain interactive shell access, and pivot into other connected IoT …

### CVE-2025-58255
**Cross-Site Request Forgery (CSRF) vulnerability in yonisink Custom Post Type Images custom-post-types-image allows Code Injection.This is...**
- **Signals:** CVSS
- **Attack:** CSRF
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:33:23.603
- **CWE:** CWE-352
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-09-22)

> Cross-Site Request Forgery (CSRF) vulnerability in yonisink Custom Post Type Images custom-post-types-image allows Code Injection.This issue affects Custom Post Type Images: from n/a through <= 0.5.

### CVE-2025-59434
**Flowise is a drag & drop user interface to build a customized large language model flow.**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-09-22)

> Flowise is a drag & drop user interface to build a customized large language model flow. Prior to August 2025 Cloud-Hosted Flowise, an authenticated vulnerability in Flowise Cloud allows any user on the free tier to access sensitive environment variables from other tenants via th…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-22*
