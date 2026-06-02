# Daily Threat Intelligence — April 20, 2026

**Digest window (UTC):** 2026-04-20
**Generated:** 2026-06-02T07:34:58Z

## Threat brief

Cisco Catalyst SD-WAN Manger: 3 CVEs added to CISA KEV today. · Netapp 500f Firmware — exploitation likelihood rose sharply (EPSS 18% → 33% · rising (+16%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cisco Catalyst SD-WAN Manger: 3 CVEs added to CISA KEV today.
- Netapp 500f Firmware — exploitation likelihood rose sharply (EPSS 18% → 33% · rising (+16%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 8 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **20** |


## CVEs

### CVE-2024-27199
**JetBrains TeamCity Relative Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** jetbrains teamcity
- **Attack:** Path Traversal
- **CVSS max:** 7.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T12:48:17.757
- **CWE:** CWE-23
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2026-04-20

> In JetBrains TeamCity before 2023.11.4 path traversal allowing to perform limited admin actions  was possible

### CVE-2021-4044
**netapp 500f_firmware**
- **Signals:** EPSS
- **Asset:** openssl openssl
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:36:47.243
- **CWE:** CWE-835
- **Risk score:** 82
- **EPSS 17.6% (2026-03-04) → 33.3% (2026-04-20), Δ +15.7%**

> Internally libssl in OpenSSL calls X509_verify_cert() on the client side to verify a certificate supplied by a server. That function may return a negative return value to indicate an internal error (for example out of memory). Such a negative return value is mishandled by OpenSSL…

### CVE-2026-30269
**doorman doorman Privilege Escalation**
- **Signals:** CVSS
- **Asset:** doorman doorman
- **Attack:** Privilege Escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T15:24:09.560
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-20)

> Improper access control in Doorman v0.1.0 and v1.0.2 allows any authenticated user to update their own account role to a non-admin privileged role via /platform/user/{username}. The `role` field is accepted by the update model without a manage_users permission check for self-upda…

### CVE-2017-15663
**flexense disk_pulse DoS**
- **Signals:** EPSS
- **Asset:** flexense disk_pulse
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:14:58.630
- **CWE:** CWE-358
- **Risk score:** 81
- **EPSS 18.1% (2026-03-14) → 29.2% (2026-04-20), Δ +11.1%**

> In Flexense Disk Pulse Enterprise v10.1.18, the Control Protocol suffers from a denial of service vulnerability. The attack vector is a crafted SERVER_GET_INFO packet sent to control port 9120.

### CVE-2023-27351
**PaperCut NG/MF Improper Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** papercut papercut_mf
- **CVSS max:** 8.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T12:48:26.657
- **CWE:** CWE-287
- **Risk score:** 88
- **KEV:** added 2026-04-20

> This vulnerability allows remote attackers to bypass authentication on affected installations of PaperCut NG 22.0.5 (Build 63914). Authentication is not required to exploit this vulnerability. The specific flaw exists within the SecurityRequestFilter class. The issue results from…

### CVE-2025-2749
**Kentico Xperience Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** kentico xperience
- **Attack:** RCE
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T12:48:29.933
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2026-04-20

> An authenticated remote code execution in Kentico Xperience allows authenticated users Staging Sync Server to upload arbitrary data to path relative locations. This results in path traversal and arbitrary file upload, including content that can be executed server side leading to …

### CVE-2025-32975
**Quest KACE Systems Management Appliance (SMA) Improper Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** quest kace_systems_management_appliance
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T14:09:39.213
- **CWE:** CWE-287
- **Risk score:** 88
- **KEV:** added 2026-04-20

> Quest KACE Systems Management Appliance (SMA) 13.0.x before 13.0.385, 13.1.x before 13.1.81, 13.2.x before 13.2.183, 14.0.x before 14.0.341 (Patch 5), and 14.1.x before 14.1.101 (Patch 4) contains an authentication bypass vulnerability that allows attackers to impersonate legitim…

### CVE-2025-48700
**Synacor Zimbra Collaboration Suite (ZCS) Cross-site Scripting Vulnerability**
- **Signals:** KEV
- **Asset:** synacor zimbra_collaboration_suite
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T12:48:23.763
- **CWE:** CWE-79
- **Risk score:** 88
- **KEV:** added 2026-04-20

> An issue was discovered in Zimbra Collaboration (ZCS) 8.8.15 and 9.0 and 10.0 and 10.1. A Cross-Site Scripting (XSS) vulnerability in the Zimbra Classic UI allows attackers to execute arbitrary JavaScript within the user's session, potentially leading to unauthorized access to se…

### CVE-2026-20122
**Cisco Catalyst SD-WAN Manager Incorrect Use of Privileged APIs Vulnerability**
- **Signals:** KEV
- **Asset:** cisco catalyst_sd-wan_manager
- **Attack:** privilege escalation
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T11:59:56.777
- **CWE:** CWE-648
- **Risk score:** 88
- **KEV:** added 2026-04-20

> A vulnerability in the API of Cisco Catalyst SD-WAN Manager could allow an authenticated, remote attacker to overwrite arbitrary files on the local file system. To exploit this vulnerability, the attacker must have valid read-only credentials with API access on the affected syste…

### CVE-2026-20128
**Cisco Catalyst SD-WAN Manager Storing Passwords in a Recoverable Format Vulnerability**
- **Signals:** KEV
- **Asset:** cisco catalyst_sd-wan_manager
- **Attack:** privilege escalation
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T12:48:20.987
- **CWE:** CWE-257
- **Risk score:** 88
- **KEV:** added 2026-04-20

> A vulnerability in the Data Collection Agent (DCA) feature of Cisco Catalyst SD-WAN Manager could allow an unauthenticated, remote attacker to gain DCA user privileges on an affected system.

This vulnerability is due to the presence of a credential file for the DCA user on an …

### CVE-2026-20133
**Cisco Catalyst SD-WAN Manager Exposure of Sensitive Information to an Unauthorized Actor Vulnerability**
- **Signals:** KEV
- **Asset:** cisco catalyst_sd-wan_manager
- **Attack:** privilege escalation
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:56:21.973
- **CWE:** CWE-200
- **Risk score:** 88
- **KEV:** added 2026-04-20

> A vulnerability in Cisco Catalyst SD-WAN Software could allow an unauthenticated, remote attacker to view sensitive information on an affected system.
 This vulnerability is due to insufficient file system restrictions. An authenticated attacker with netadmin privileges could e…

### CVE-2026-29646
**In OpenXiangShan NEMU prior to 55295c4, when running with RVH (Hypervisor extension) enabled, a VS-mode guest write to the supervisor int...**
- **Signals:** CVSS
- **Attack:** DoS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-21T20:16:40.557
- **CWE:** CWE-267
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-20)

> In OpenXiangShan NEMU prior to 55295c4, when running with RVH (Hypervisor extension) enabled, a VS-mode guest write to the supervisor interrupt-enable CSR (sie) may be handled incorrectly and can influence machine-level interrupt enable state (mie). This breaks privilege/virtuali…

### CVE-2026-29649
**xiangshan nemu**
- **Signals:** CVSS
- **Asset:** xiangshan nemu
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T19:23:46.560
- **CWE:** CWE-693
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-20)

> NEMU contains an implementation flaw in its RISC-V Hypervisor CSR handling where henvcfg[7:4] (CBIE/CBCFE/CBZE-related fields) is incorrectly masked/updated based on menvcfg[7:4], so a machine-mode write to menvcfg can implicitly modify the hypervisor's environment configuration.…

### CVE-2026-32311
**flowsint flowsint**
- **Signals:** CVSS
- **Asset:** flowsint flowsint
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-21T20:31:52.157
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-20)

> Flowsint is an open-source OSINT graph exploration tool designed for cybersecurity investigation, transparency, and verification. Flowsint allows a user to create investigations, which are used to manage sketches and analyses. Sketches have controllable graphs, which are comprise…

### CVE-2026-32604
**linuxfoundation spinnaker**
- **Signals:** CVSS
- **Asset:** linuxfoundation spinnaker
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T18:30:30.983
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-20)

> Spinnaker is an open source, multi-cloud continuous delivery platform. In versions prior to 2026.1.0, 2026.0.1, 2025.4.2, and 2025.3.2, a bad actor can execute arbitrary commands very simply on the clouddriver pods. This can expose credentials, remove files, or inject resources e…

### CVE-2026-32613
**linuxfoundation spinnaker**
- **Signals:** CVSS
- **Asset:** linuxfoundation spinnaker
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T18:30:37.510
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-20)

> Spinnaker is an open source, multi-cloud continuous delivery platform. Echo like some other services, uses SPeL (Spring Expression Language) to process information - specifically around expected artifacts. In versions prior to 2026.1.0, 2026.0.1, 2025.4.2, and 2025.3.2, unlike or…

### CVE-2026-39109
**SQL Injection vulnerability in Apartment Visitors Management System Apartment Visitors Management System V1.1 within the username paramet...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-20T19:16:10.733
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-20)

> SQL Injection vulnerability in Apartment Visitors Management System Apartment Visitors Management System V1.1 within the username parameter of the login page (index.php). This allows an unauthenticated attacker to manipulate backend SQL queries during authentication and retrieve …

### CVE-2026-39918
**Vvveb prior to 1.0.8.1 contains a code injection vulnerability in the installation endpoint where the subdir POST parameter is written un...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-20T18:54:59.077
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-04-20)

> Vvveb prior to 1.0.8.1 contains a code injection vulnerability in the installation endpoint where the subdir POST parameter is written unsanitized into the env.php configuration file without escaping or validation. Attackers can inject arbitrary PHP code by breaking out of the st…

### CVE-2026-5450
**gnu glibc Buffer Overflow**
- **Signals:** CVSS
- **Asset:** gnu glibc
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T15:33:34.277
- **CWE:** CWE-122
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-20)

> Calling the scanf family of functions with a %mc (malloc'd character match) in the GNU C Library version 2.7 to version 2.43 with a format width specifier with an explicit width greater than 1024 could result in a one byte heap buffer overflow.

### CVE-2026-6257
**Vvveb CMS v1.0.8.2 contains a remote code execution vulnerability in its media management functionality where a missing return statement...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T00:16:56.793
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-04-20)

> Vvveb CMS v1.0.8.2 contains a remote code execution vulnerability in its media management functionality where a missing return statement in the file rename handler allows authenticated attackers to rename files to blocked extensions .php or .htaccess. Attackers can exploit this l…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-20*
