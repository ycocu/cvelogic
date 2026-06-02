# Daily Threat Intelligence — May 07, 2025

**Digest window (UTC):** 2025-05-07
**Generated:** 2026-06-02T07:32:40Z

## Threat brief

GeoVision Multiple Devices: 2 CVEs added to CISA KEV today. · Microsoft Office Compatibility Pack — exploitation likelihood rose sharply (EPSS 38% → 53% · rising (+15%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- GeoVision Multiple Devices: 2 CVEs added to CISA KEV today.
- Microsoft Office Compatibility Pack — exploitation likelihood rose sharply (EPSS 38% → 53% · rising (+15%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2024-11120
**GeoVision Devices OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** geovision gv-vs12_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T20:09:53.680
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2025-05-07

> Certain EOL GeoVision devices have an OS Command Injection vulnerability. Unauthenticated remote attackers can exploit this vulnerability to inject and execute arbitrary system commands on the device. Moreover, this vulnerability has already been exploited by attackers, and we ha…

### CVE-2015-1651
**microsoft office_compatibility_pack Use-After-Free**
- **Signals:** EPSS
- **Asset:** microsoft office_compatibility_pack
- **Attack:** Use-After-Free
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 85
- **EPSS 38.0% (2025-03-30) → 53.1% (2025-05-07), Δ +15.1%**

> Use-after-free vulnerability in Microsoft Word 2007 SP3, Word Viewer, and Office Compatibility Pack SP3 allows remote attackers to execute arbitrary code via a crafted Office document, aka "Microsoft Office Component Use After Free Vulnerability."

### CVE-2025-46828
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-02T16:30:44.907
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-07)

> WeGIA is a web manager for charitable institutions.  An unauthenticated SQL Injection vulnerability was identified in versions up to and including 3.3.0 in the endpoint `/html/socio/sistema/get_socios.php`, specifically in the query parameter. This issue allows attackers to injec…

### CVE-2002-0052
**microsoft internet_explorer**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 22.3% (2025-03-30) → 34.4% (2025-05-07), Δ +12.1%**

> Internet Explorer 6.0 and earlier does not properly handle VBScript in certain domain security checks, which allows remote attackers to read arbitrary files.

### CVE-2002-0057
**microsoft internet_explorer**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 28.5% (2025-03-30) → 41.8% (2025-05-07), Δ +13.3%**

> XMLHTTP control in Microsoft XML Core Services 2.6 and later does not properly handle IE Security Zone settings, which allows remote attackers to read arbitrary files by specifying a local file as an XML Data Source.

### CVE-2022-24305
**zohocorp manageengine_sharepoint_manager_plus Privilege Escalation**
- **Signals:** EPSS
- **Asset:** zohocorp manageengine_sharepoint_manager_plus
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:50:08.073
- **Risk score:** 84
- **EPSS 1.8% (2025-03-30) → 13.1% (2025-05-07), Δ +11.3%**

> Zoho ManageEngine SharePoint Manager Plus before 4329 is vulnerable to a sensitive data leak that leads to privilege escalation.

### CVE-2024-6047
**GeoVision Devices OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** geovision gv-dsp_lpr_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T19:23:34.360
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2025-05-07

> Certain EOL GeoVision devices fail to properly filter user input for the specific functionality. Unauthenticated remote attackers can exploit this vulnerability to inject and execute arbitrary system commands on the device.

### CVE-2025-20188
**cisco ios_xe**
- **Signals:** CVSS
- **Asset:** cisco ios_xe
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-23T15:15:11.117
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-07)

> A vulnerability in the Out-of-Band Access Point (AP) Image Download, the Clean Air Spectral Recording, and the client debug bundles features of Cisco IOS XE Software for Wireless LAN Controllers (WLCs) could allow an unauthenticated, remote attacker to upload arbitrary files to a…

### CVE-2025-2775
**SysAid On-Prem Improper Restriction of XML External Entity Reference Vulnerability**
- **Signals:** CVSS
- **Asset:** sysaid sysaid
- **Attack:** XXE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T16:58:55.380
- **CWE:** CWE-611
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-07)

> SysAid On-Prem versions <= 23.3.40 are vulnerable to an unauthenticated XML External Entity (XXE) vulnerability in the Checkin processing functionality,  allowing for administrator account takeover and file read primitives.

### CVE-2025-2776
**SysAid On-Prem Improper Restriction of XML External Entity Reference Vulnerability**
- **Signals:** CVSS
- **Asset:** sysaid sysaid
- **Attack:** XXE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T16:58:51.230
- **CWE:** CWE-611
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-07)

> SysAid On-Prem versions <= 23.3.40 are vulnerable to an unauthenticated XML External Entity (XXE) vulnerability in the Server URL processing functionality, allowing for administrator account takeover and file read primitives.

### CVE-2025-2777
**sysaid sysaid XXE**
- **Signals:** CVSS
- **Asset:** sysaid sysaid
- **Attack:** XXE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-27T14:35:46.827
- **CWE:** CWE-611
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-07)

> SysAid On-Prem versions <= 23.3.40 are vulnerable to an unauthenticated XML External Entity (XXE) vulnerability in the lshw processing functionality,  allowing for administrator account takeover and file read primitives.

### CVE-2025-3476
**Incorrect Authorization vulnerability in OpenText™ Operations Bridge Manager.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-05-07)

> Incorrect Authorization vulnerability in OpenText™ Operations Bridge Manager. The vulnerability could allows privilege escalation by authenticated users.This issue affects Operations Bridge Manager: 2023.05, 23.4, 24.2, 24.4.

### CVE-2025-36546
**f5 f5os-a**
- **Signals:** CVSS
- **Asset:** f5 f5os-a
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-21T18:42:57.403
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-05-07)

> On an F5OS system, if the root user had previously configured the system to allow login via SSH key-based authentication, and then enabled Appliance Mode; access via SSH key-based authentication is still allowed. For an attacker to exploit this vulnerability they must obtain the …

### CVE-2025-4104
**The Frontend Dashboard plugin for WordPress is vulnerable to Privilege Escalation due to a missing capability check on the fed_wp_ajax_fe...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-07)

> The Frontend Dashboard plugin for WordPress is vulnerable to Privilege Escalation due to a missing capability check on the fed_wp_ajax_fed_login_form_post() function in versions 1.0 to 2.2.6. This makes it possible for unauthenticated attackers to reset the administrator’s email …

### CVE-2025-47549
**themefic ultimate_before_after_image_slider_\&_gallery**
- **Signals:** CVSS
- **Asset:** themefic ultimate_before_after_image_slider_\&_gallery
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T15:30:28.047
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-07)

> Unrestricted Upload of File with Dangerous Type vulnerability in Themefic BEAF beaf-before-and-after-gallery allows Upload a Web Shell to a Web Server.This issue affects BEAF: from n/a through <= 4.6.10.

### CVE-2025-47657
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Productive Minds Productive Commerc...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-28T19:32:31.470
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-07)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Productive Minds Productive Commerce productive-commerce allows SQL Injection.This issue affects Productive Commerce: from n/a through <= 1.1.40.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-07*
