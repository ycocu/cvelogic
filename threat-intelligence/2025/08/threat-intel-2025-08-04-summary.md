# Daily Threat Intelligence — August 04, 2025

**Digest window (UTC):** 2025-08-04
**Generated:** 2026-06-02T07:33:10Z

## Threat brief

10 new critical disclosures — review patch status on exposed services.

## Executive summary

- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-46093
**liquidfiles liquidfiles**
- **Signals:** CVSS
- **Asset:** liquidfiles liquidfiles
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-07T14:29:07.530
- **CWE:** CWE-732
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-08-04)

> LiquidFiles before 4.1.2 supports FTP SITE CHMOD for mode 6777 (setuid and setgid), which allows FTPDrop users to execute arbitrary code as root by leveraging the Actionscript feature and the sudoers configuration.

### CVE-2025-51387
**axosoft gitkraken_desktop RCE**
- **Signals:** CVSS
- **Asset:** axosoft gitkraken_desktop
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T17:31:44.337
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-04)

> The GitKraken Desktop 10.8.0 and 11.1.0 is susceptible to code injection due to misconfigured Electron Fuses. Specifically, the following insecure settings were observed: RunAsNode is enabled and EnableNodeCliInspectArguments is not disabled. These configurations allow the applic…

### CVE-2025-51390
**totolink n600r_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** totolink n600r_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-15T16:07:35.060
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-04)

> TOTOLINK N600R V4.3.0cu.7647_B20210106 was discovered to contain a command injection vulnerability via the pin parameter in the setWiFiWpsConfig function.

### CVE-2013-10054
**An unauthenticated arbitrary file upload vulnerability exists in LibrettoCMS version 1.1.7 (and possibly earlier) contains an unauthentic...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-04)

> An unauthenticated arbitrary file upload vulnerability exists in LibrettoCMS version 1.1.7 (and possibly earlier) contains an unauthenticated arbitrary file upload vulnerability in its File Manager plugin. The upload handler located at adm/ui/js/ckeditor/plugins/pgrfilemanager/ph…

### CVE-2025-27212
**An Improper Input Validation in certain UniFi Access devices could allow a Command Injection by a malicious actor with access to UniFi Ac...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-04)

> An Improper Input Validation in certain UniFi Access devices could allow a Command Injection by a malicious actor with access to UniFi Access management network.

 

Affected Products:
UniFi Access Reader Pro (Version 2.14.21 and earlier)
UniFi Access G2 Reader Pro (Version…

### CVE-2025-34147
**An unauthenticated OS command injection vulnerability exists in the Shenzhen Aitemi M300 Wi-Fi Repeater (hardware model MT02).**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-04)

> An unauthenticated OS command injection vulnerability exists in the Shenzhen Aitemi M300 Wi-Fi Repeater (hardware model MT02). When configuring the device in Extender mode via its captive portal, the extap2g SSID field is inserted unescaped into a reboot-time shell script. This a…

### CVE-2025-50341
**A Boolean-based SQL injection vulnerability was discovered in Axelor 5.2.4 via the _domain parameter.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-04)

> A Boolean-based SQL injection vulnerability was discovered in Axelor 5.2.4 via the _domain parameter. An attacker can manipulate the SQL query logic and determine true/false conditions, potentially leading to data exposure or further exploitation.

### CVE-2025-50754
**Unisite CMS version 5.0 contains a stored Cross-Site Scripting (XSS) vulnerability in the "Report" functionality.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-08-04)

> Unisite CMS version 5.0 contains a stored Cross-Site Scripting (XSS) vulnerability in the "Report" functionality. A malicious script submitted by an attacker is rendered in the admin panel when viewed by an administrator. This allows attackers to hijack the admin session and, by …

### CVE-2025-51535
**craws openatlas SQL Injection**
- **Signals:** CVSS
- **Asset:** craws openatlas
- **Attack:** SQL Injection
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-20T03:16:23.350
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-04)

> Austrian Archaeological Institute (AI) OpenAtlas v8.11.0 as discovered to contain a SQL injection vulnerability.

### CVE-2025-52239
**zkea zkeacms**
- **Signals:** CVSS
- **Asset:** zkea zkeacms
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T16:10:59.810
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-04)

> An arbitrary file upload vulnerability in ZKEACMS v4.1 allows attackers to execute arbitrary code via a crafted file.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-04*
