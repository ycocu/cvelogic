# Daily Threat Intelligence — May 29, 2025

**Digest window (UTC):** 2025-05-29
**Generated:** 2026-06-02T07:32:47Z

## Threat brief

Campcodes Online Hospital Management System: public exploit or PoC linked (SQL Injection) · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Campcodes Online Hospital Management System: public exploit or PoC linked (SQL Injection)
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 6 |
| EPSS rise | 0 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2024-0204
**fortra goanywhere_managed_file_transfer Auth Bypass**
- **Signals:** EXP
- **Asset:** fortra goanywhere_managed_file_transfer
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:46:03.627
- **CWE:** CWE-425
- **CWE:** CWE-425
- **Risk score:** 78
- **EXP:** ref published 2025-05-29

> Authentication bypass in Fortra's GoAnywhere MFT prior to 7.4.1 allows an unauthorized user to create an admin user via the administration portal.

### CVE-2024-28995
**SolarWinds Serv-U Path Traversal Vulnerability**
- **Signals:** EXP
- **Asset:** solarwinds serv-u
- **Attack:** Path Traversal
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T15:04:20.280
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2025-05-29

> SolarWinds Serv-U was susceptible to a directory transversal vulnerability that would allow access to read sensitive files on the host machine.

### CVE-2025-48748
**netwrix directory_manager**
- **Signals:** CVSS
- **Asset:** netwrix directory_manager
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-23T14:37:52.580
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-29)

> Netwrix Directory Manager (formerly Imanami GroupID) through v.10.0.7784.0 has a hard-coded password.

### CVE-2023-41591
**opennetworking onos**
- **Signals:** CVSS
- **Asset:** opennetworking onos
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-03T15:36:09.540
- **CWE:** CWE-290
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-29)

> An issue in Open Network Foundation ONOS v2.7.0 allows attackers to create fake IP/MAC addresses and potentially execute a man-in-the-middle attack on communications between fake and real hosts.

### CVE-2025-24071
**microsoft windows_10_1507**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-03T13:23:25.997
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2025-05-29

> Exposure of sensitive information to an unauthorized actor in Windows File Explorer allows an unauthorized attacker to perform spoofing over a network.

### CVE-2025-30466
**apple ipados**
- **Signals:** CVSS
- **Asset:** apple safari
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-02T19:19:41.870
- **CWE:** CWE-346
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-29)

> This issue was addressed through improved state management. This issue is fixed in Safari 18.4, iOS 18.4 and iPadOS 18.4, macOS Sequoia 15.4, visionOS 2.4. A website may be able to bypass Same Origin Policy.

### CVE-2025-31263
**apple macos**
- **Signals:** CVSS
- **Asset:** apple macos
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-02T15:59:55.480
- **CWE:** CWE-119
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-29)

> The issue was addressed with improved memory handling. This issue is fixed in macOS Sequoia 15.4. An app may be able to corrupt coprocessor memory.

### CVE-2025-3755
**Improper Validation of Specified Index, Position, or Offset in Input vulnerability in Mitsubishi Electric Corporation MELSEC iQ-F Series...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1285
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-29)

> Improper Validation of Specified Index, Position, or Offset in Input vulnerability in Mitsubishi Electric Corporation MELSEC iQ-F Series CPU modules allows a remote unauthenticated attacker to read information in the product, to cause a Denial-of-Service (DoS) condition in MELSOF…

### CVE-2025-4094
**unitedover digits**
- **Signals:** EXP
- **Asset:** unitedover digits
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-09T20:13:20.070
- **Risk score:** 78
- **EXP:** ref published 2025-05-29

> The DIGITS: WordPress Mobile Number Signup and Login WordPress plugin before 8.4.6.1 does not rate limit OTP validation attempts, making it straightforward for attackers to bruteforce them.

### CVE-2025-47933
**argoproj argo_cd XSS**
- **Signals:** CVSS
- **Asset:** argoproj argo_cd
- **Attack:** XSS
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-27T02:28:01.647
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-05-29)

> Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes. Prior to versions 2.13.8, 2.14.13, and 3.0.4, an attacker can perform arbitrary actions on behalf of the victim via the API. Due to the improper filtering of URL protocols in the repository page, an attacke…

### CVE-2025-48047
**An authenticated user can perform command injection via unsanitized input to the NetFax Server’s ping functionality via the /test.php end...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-05-29)

> An authenticated user can perform command injection via unsanitized input to the NetFax Server’s ping functionality via the /test.php endpoint.

### CVE-2025-48336
**Deserialization of Untrusted Data vulnerability in ThimPress Course Builder course-builder allows Object Injection.This issue affects Cou...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:07.847
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-29)

> Deserialization of Untrusted Data vulnerability in ThimPress Course Builder course-builder allows Object Injection.This issue affects Course Builder: from n/a through < 3.6.6.

### CVE-2025-4967
**esri portal_for_arcgis SSRF**
- **Signals:** CVSS
- **Asset:** esri portal_for_arcgis
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2025-12-15T20:15:51.473
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-29)

> Esri Portal for ArcGIS 11.4 and prior allows a remote, unauthenticated attacker to bypass the Portal’s SSRF protections.

### CVE-2025-4971
**Broadcom Automic Automation Agent Unix versions < 24.3.0 HF4 and < 21.0.13 HF1 allow low privileged users who have execution rights on th...**
- **Signals:** EXP
- **Attack:** privilege escalation
- **CVSS max:** 8.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-426
- **Risk score:** 78
- **EXP:** ref published 2025-05-29

> Broadcom Automic
Automation Agent Unix versions <
24.3.0 HF4 and < 21.0.13 HF1 allow low privileged users who have execution
rights on the agent executable to escalate their privileges.

### CVE-2025-5298
**campcodes online_hospital_management_system SQL Injection**
- **Signals:** EXP
- **Asset:** campcodes online_hospital_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-28T20:37:48.440
- **CWE:** CWE-74
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-05-29

> A vulnerability, which was classified as critical, was found in Campcodes Online Hospital Management System 1.0. Affected is an unknown function of the file /admin/betweendates-detailsreports.php. The manipulation of the argument fromdate/todate leads to sql injection. It is poss…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-29*
