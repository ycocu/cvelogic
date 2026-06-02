# Daily Threat Intelligence — May 13, 2025

**Digest window (UTC):** 2025-05-13
**Generated:** 2026-06-02T07:32:42Z

## Threat brief

Microsoft Windows: 5 CVEs added to CISA KEV today. · Kentico Xperience: public exploit or PoC linked (cross-site scripting) · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows: 5 CVEs added to CISA KEV today.
- Kentico Xperience: public exploit or PoC linked (cross-site scripting)
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 5 |
| EXP (exploit / PoC) | 3 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2025-30400
**Microsoft Windows DWM Core Library Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1809
- **Attack:** Use-After-Free
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:13:34.180
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2025-05-13

> Use after free in Windows DWM allows an authorized attacker to elevate privileges locally.

### CVE-2024-11237
**tp-link vn020-f3v\(t\)_firmware Buffer Overflow**
- **Signals:** EXP
- **Asset:** tp-link vn020-f3v\(t\)_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2024-11-19T19:04:14.987
- **CWE:** CWE-119
- **CWE:** CWE-787
- **Risk score:** 78
- **EXP:** ref published 2025-05-13

> A vulnerability, which was classified as critical, has been found in TP-Link VN020 F3v(T) TT_V6.2.1021. Affected by this issue is some unknown functionality of the component DHCP DISCOVER Packet Parser. The manipulation of the argument hostname leads to stack-based buffer overflo…

### CVE-2025-45861
**totolink a3002r_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** totolink a3002r_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-15T18:37:49.147
- **CWE:** CWE-120
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-13)

> TOTOLINK A3002R v4.0.0-B20230531.1404 was discovered to contain a buffer overflow via the routername parameter in the formDnsv6 interface.

### CVE-2025-30397
**Microsoft Windows Scripting Engine Type Confusion Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:13:37.647
- **CWE:** CWE-843
- **Risk score:** 88
- **KEV:** added 2025-05-13

> Access of resource using incompatible type ('type confusion') in Microsoft Scripting Engine allows an unauthorized attacker to execute code over a network.

### CVE-2025-32370
**kentico xperience cross-site scripting**
- **Signals:** EXP
- **Asset:** kentico xperience
- **Attack:** cross-site scripting
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-04-08T18:54:51.523
- **CWE:** CWE-912
- **CWE:** CWE-434
- **Risk score:** 78
- **EXP:** ref published 2025-05-13

> Kentico Xperience before 13.0.178 has a specific set of allowed ContentUploader file extensions for unauthenticated uploads; however, because .zip is processed through TryZipProviderSafe, there is additional functionality to create files with other extensions. NOTE: this is a sep…

### CVE-2025-32701
**Microsoft Windows Common Log File System (CLFS) Driver Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1507
- **Attack:** Use-After-Free
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:13:08.060
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2025-05-13

> Use after free in Windows Common Log File System Driver allows an authorized attacker to elevate privileges locally.

### CVE-2025-32706
**Microsoft Windows Common Log File System (CLFS) Driver Heap-Based Buffer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1507
- **Attack:** Buffer Overflow
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:13:04.750
- **CWE:** CWE-20
- **Risk score:** 88
- **KEV:** added 2025-05-13

> Improper input validation in Windows Common Log File System Driver allows an authorized attacker to elevate privileges locally.

### CVE-2025-32709
**Microsoft Windows Ancillary Function Driver for WinSock Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1507
- **Attack:** Use-After-Free
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T21:37:17.017
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2025-05-13

> Null pointer dereference in Windows Ancillary Function Driver for WinSock allows an authorized attacker to elevate privileges locally.

### CVE-2025-3605
**The Frontend Login and Registration Blocks plugin for WordPress is vulnerable to privilege escalation via account takeover in all version...**
- **Signals:** EXP
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-639
- **Risk score:** 78
- **EXP:** ref published 2025-05-13

> The Frontend Login and Registration Blocks plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 1.1.1. This is due to the plugin not properly validating a user's identity prior to updating their details like email v…

### CVE-2025-43559
**adobe coldfusion RCE**
- **Signals:** CVSS
- **Asset:** adobe coldfusion
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-15T18:40:43.160
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-13)

> ColdFusion versions 2025.1, 2023.13, 2021.19 and earlier are affected by an Improper Input Validation vulnerability that could result in arbitrary code execution in the context of the current user. A high-privileged attacker could leverage this vulnerability to bypass security me…

### CVE-2025-43560
**adobe coldfusion RCE**
- **Signals:** CVSS
- **Asset:** adobe coldfusion
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-19T20:35:23.227
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-13)

> ColdFusion versions 2025.1, 2023.13, 2021.19 and earlier are affected by an Improper Input Validation vulnerability that could result in arbitrary code execution in the context of the current user. A high-privileged attacker could leverage this vulnerability to bypass security me…

### CVE-2025-43561
**adobe coldfusion RCE**
- **Signals:** CVSS
- **Asset:** adobe coldfusion
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-19T20:35:36.023
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-13)

> ColdFusion versions 2025.1, 2023.13, 2021.19 and earlier are affected by an Incorrect Authorization vulnerability that could result in arbitrary code execution in the context of the current user. A high-privileged attacker could leverage this vulnerability to bypass authenticatio…

### CVE-2025-43562
**adobe coldfusion RCE**
- **Signals:** CVSS
- **Asset:** adobe coldfusion
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-19T20:36:17.270
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-13)

> ColdFusion versions 2025.1, 2023.13, 2021.19 and earlier are affected by an Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability that could result in arbitrary code execution in the context of the current user. A high-privileged…

### CVE-2025-43563
**adobe coldfusion privilege escalation**
- **Signals:** CVSS
- **Asset:** adobe coldfusion
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-15T18:40:38.210
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-13)

> ColdFusion versions 2025.1, 2023.13, 2021.19 and earlier are affected by an Improper Access Control vulnerability that could result in arbitrary file system read. A high-privileged attacker could leverage this vulnerability to access or modify sensitive data without proper author…

### CVE-2025-43564
**adobe coldfusion privilege escalation**
- **Signals:** CVSS
- **Asset:** adobe coldfusion
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-15T18:40:34.563
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-13)

> ColdFusion versions 2025.1, 2023.13, 2021.19 and earlier are affected by an Improper Access Control vulnerability that could result in arbitrary file system read. A high-privileged attacker could leverage this vulnerability to access or modify sensitive data without proper author…

### CVE-2025-43567
**adobe connect XSS**
- **Signals:** CVSS
- **Asset:** adobe connect
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-19T20:28:59.800
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-13)

> Adobe Connect versions 12.8 and earlier are affected by a reflected Cross-Site Scripting (XSS) vulnerability that could be abused by an attacker to inject malicious scripts into vulnerable form fields. Malicious JavaScript may be executed in a victim’s browser when they browse to…

### CVE-2025-45863
**totolink a3002r_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** totolink a3002r_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-23T18:55:24.013
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-13)

> TOTOLINK A3002R v4.0.0-B20230531.1404 was discovered to contain a buffer overflow via the macstr parameter in the formMapDelDevice interface.

### CVE-2025-45865
**totolink a3002r_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** totolink a3002r_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-15T18:37:31.917
- **CWE:** CWE-120
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-13)

> TOTOLINK A3002R v4.0.0-B20230531.1404 was discovered to contain a buffer overflow via the dnsaddr parameter in the formDhcpv6s interface.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-13*
