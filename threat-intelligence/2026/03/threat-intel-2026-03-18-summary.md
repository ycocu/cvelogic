# Daily Threat Intelligence — March 18, 2026

**Digest window (UTC):** 2026-03-18
**Generated:** 2026-06-02T07:34:41Z

## Threat brief

Microsoft SharePoint added to CISA KEV — confirmed in-the-wild exploitation. · Geutebruck Ip Camera G-cam Efd-2250 Firmware — exploitation likelihood rose sharply (EPSS 38% → 65% · rising (+27%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft SharePoint added to CISA KEV — confirmed in-the-wild exploitation.
- Geutebruck Ip Camera G-cam Efd-2250 Firmware — exploitation likelihood rose sharply (EPSS 38% → 65% · rising (+27%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2025-66376
**Synacor Zimbra Collaboration Suite (ZCS) Cross-Site Scripting Vulnerability**
- **Signals:** KEV
- **Asset:** synacor zimbra_collaboration_suite
- **Attack:** XSS
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-18T20:13:37.087
- **CWE:** CWE-79
- **Risk score:** 88
- **KEV:** added 2026-03-18

> Zimbra Collaboration (ZCS) 10 before 10.0.18 and 10.1 before 10.1.13 allows Classic UI stored XSS via Cascading Style Sheets (CSS) @import directives in an HTML e-mail message.

### CVE-2017-5174
**geutebruck ip_camera_g-cam_efd-2250_firmware RCE**
- **Signals:** EPSS
- **Asset:** geutebruck ip_camera_g-cam_efd-2250_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-288
- **Risk score:** 86
- **EPSS 38.2% (2025-11-21) → 65.2% (2026-03-18), Δ +27.0%**

> An Authentication Bypass issue was discovered in Geutebruck IP Camera G-Cam/EFD-2250 Version 1.11.0.12. An authentication bypass vulnerability has been identified. The existing file system architecture could allow attackers to bypass the access control that may allow remote code …

### CVE-2026-32731
**apostrophecms import-export**
- **Signals:** CVSS
- **Asset:** apostrophecms import-export
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-24T21:31:54.240
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-18)

> ApostropheCMS is an open-source content management framework. Prior to version 3.5.3 of `@apostrophecms/import-export`,
The `extract()` function in `gzip.js` constructs file-write paths using `fs.createWriteStream(path.join(exportPath, header.name))`. `path.join()` does not resol…

### CVE-2016-10760
**seowonintech swr-300a_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** seowonintech swr-300a_firmware
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T02:44:41.013
- **CWE:** CWE-77
- **Risk score:** 84
- **EPSS 6.6% (2025-03-30) → 17.9% (2026-03-18), Δ +11.3%**

> On Seowon Intech routers, there is a Command Injection vulnerability in diagnostic.cgi via shell metacharacters in the ping_ipaddr parameter.

### CVE-2018-7297
**eq-3 homematic_central_control_unit_ccu2_firmware RCE**
- **Signals:** EPSS
- **Asset:** eq-3 homematic_central_control_unit_ccu2_firmware
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:11:57.443
- **Risk score:** 86
- **EPSS 46.6% (2025-12-30) → 59.3% (2026-03-18), Δ +12.7%**

> Remote Code Execution in the TCL script interpreter in eQ-3 AG Homematic CCU2 2.29.2 and earlier allows remote attackers to obtain read/write access and execute system commands on the device. This vulnerability can be exploited by unauthenticated attackers with access to the web …

### CVE-2025-15031
**lfprojects mlflow**
- **Signals:** CVSS
- **Asset:** lfprojects mlflow
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-23T17:48:45.340
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-18)

> A vulnerability in MLflow's pyfunc extraction process allows for arbitrary file writes due to improper handling of tar archive entries. Specifically, the use of `tarfile.extractall` without path validation enables crafted tar.gz files containing `..` or absolute paths to escape t…

### CVE-2026-20963
**Microsoft SharePoint Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft sharepoint_server
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-01T16:01:22.890
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2026-03-18

> Deserialization of untrusted data in Microsoft Office SharePoint allows an unauthorized attacker to execute code over a network.

### CVE-2026-25873
**OmniGen2-RL contains an unauthenticated remote code execution vulnerability in the reward server component that allows remote attackers t...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-19T13:25:00.570
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-18)

> OmniGen2-RL contains an unauthenticated remote code execution vulnerability in the reward server component that allows remote attackers to execute arbitrary commands by sending malicious HTTP POST requests. Attackers can exploit insecure pickle deserialization of request bodies t…

### CVE-2026-30701
**The web interface of the WiFi Extender WDR201A (HW V2.1, FW LFMZX28040922V1.02) contains hardcoded credential disclosure mechanisms (in t...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-23T16:16:45.580
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-18)

> The web interface of the WiFi Extender WDR201A (HW V2.1, FW LFMZX28040922V1.02) contains hardcoded credential disclosure mechanisms (in the form of Server Side Include) within multiple server-side web pages, including login.shtml and settings.shtml. These pages embed server-side …

### CVE-2026-30702
**The WiFi Extender WDR201A (HW V2.1, FW LFMZX28040922V1.02) implements a broken authentication mechanism in its web management interface.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-23T16:16:45.750
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-18)

> The WiFi Extender WDR201A (HW V2.1, FW LFMZX28040922V1.02) implements a broken authentication mechanism in its web management interface. The login page does not properly enforce session validation, allowing attackers to bypass authentication by directly accessing restricted web a…

### CVE-2026-30703
**A command injection vulnerability exists in the web management interface of the WiFi Extender WDR201A (HW V2.1, FW LFMZX28040922V1.02).**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-23T16:16:45.920
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-18)

> A command injection vulnerability exists in the web management interface of the WiFi Extender WDR201A (HW V2.1, FW LFMZX28040922V1.02). The adm.cgi endpoint improperly sanitizes user-supplied input provided to a command-related parameter in the sysCMD functionality.

### CVE-2026-30704
**The WiFi Extender WDR201A (HW V2.1, FW LFMZX28040922V1.02) exposes an unprotected UART interface through accessible hardware pads on the PCB**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-19T15:16:26.580
- **CWE:** CWE-912
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-18)

> The WiFi Extender WDR201A (HW V2.1, FW LFMZX28040922V1.02) exposes an unprotected UART interface through accessible hardware pads on the PCB

### CVE-2026-32633
**nicolargo glances**
- **Signals:** CVSS
- **Asset:** nicolargo glances
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-19T19:04:46.033
- **CWE:** CWE-200
- **CWE:** CWE-522
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-18)

> Glances is an open-source system cross-platform monitoring tool. Prior to version 4.5.2, in Central Browser mode, the `/api/4/serverslist` endpoint returns raw server objects from `GlancesServersList.get_servers_list()`. Those objects are mutated in-place during background pollin…

### CVE-2026-32698
**openproject openproject SQL Injection**
- **Signals:** CVSS
- **Asset:** openproject openproject
- **Attack:** SQL Injection
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-19T18:32:37.460
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-18)

> OpenProject is an open-source, web-based project management software. Versions prior to 16.6.9, 17.0.6, 17.1.3, and 17.2.1 are vulnerable to an SQL injection attack via a custom field's name. When that custom field was used in a Cost Report, the custom field's name was injected i…

### CVE-2026-32703
**openproject openproject**
- **Signals:** CVSS
- **Asset:** openproject openproject
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-19T19:23:00.593
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-03-18)

> OpenProject is an open-source, web-based project management software. In versions prior to 16.6.9, 17.0.6, 17.1.3, and 17.2.1, the Repositories module did not properly escape filenames displayed from repositories. This allowed an attacker with push access into the repository to c…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-18*
