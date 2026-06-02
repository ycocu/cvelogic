# Daily Threat Intelligence — October 31, 2025

**Digest window (UTC):** 2025-10-31
**Generated:** 2026-06-02T07:33:42Z

## Threat brief

Flowiseai Flowise: public exploit or PoC linked (RCE) · WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Microsoft Windows 10 — exploitation likelihood rose sharply (EPSS 13% → 25% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Flowiseai Flowise: public exploit or PoC linked (RCE)
- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Microsoft Windows 10 — exploitation likelihood rose sharply (EPSS 13% → 25% · rising (+12%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 1 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2025-59528
**flowiseai flowise RCE**
- **Signals:** EXP
- **Asset:** flowiseai flowise
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-23T16:45:09.443
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-10-31

> Flowise is a drag & drop user interface to build a customized large language model flow. In version 3.0.5, Flowise is vulnerable to remote code execution. The CustomMCP node allows users to input configuration settings for connecting to an external MCP server. This node parses th…

### CVE-2016-3237
**microsoft windows_10**
- **Signals:** EPSS
- **Asset:** microsoft windows_10
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-264
- **Risk score:** 81
- **EPSS 13.1% (2025-09-14) → 24.9% (2025-10-31), Δ +11.8%**

> Kerberos in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607 allows man-in-the-middle attackers to bypass authentication via vectors related to a fallb…

### CVE-2025-12553
**azure-access blu-ic2_firmware**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-10T14:48:31.427
- **CWE:** CWE-599
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-31)

> Email Server Certificate Verification Disabled.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5.

### CVE-2025-29270
**Incorrect access control in the realtime.cgi endpoint of Deep Sea Electronics devices DSE855 v1.1.0 to v1.1.26 allows attackers to gain a...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-31)

> Incorrect access control in the realtime.cgi endpoint of Deep Sea Electronics devices DSE855 v1.1.0 to v1.1.26 allows attackers to gain access to the admin panel and complete control of the device.

### CVE-2025-48983
**veeam veeam_backup_\&_replication RCE**
- **Signals:** CVSS
- **Asset:** veeam veeam_backup_\&_replication
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2025-12-01T21:15:50.527
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-10-31)

> A vulnerability in the Mount service of Veeam Backup & Replication, which allows for remote code execution (RCE) on the Backup infrastructure hosts by an authenticated domain user.

### CVE-2025-52665
**ui unifi_access**
- **Signals:** CVSS
- **Asset:** ui unifi_access
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-12T14:51:21.057
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-31)

> A malicious actor with access to the management network could exploit a misconfiguration in UniFi’s door access application, UniFi Access, that exposed a management API without proper authentication. This vulnerability was introduced in Version 3.3.22 and was fixed in Version 4.0…

### CVE-2025-5397
**The Noo JobMonster theme for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 4.8.1.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-31)

> The Noo JobMonster theme for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 4.8.1. This is due to the check_login() function not properly verifying a user's identity prior to successfully authenticating them  This makes it possible for unau…

### CVE-2025-57108
**vtk vtk Use-After-Free**
- **Signals:** CVSS
- **Asset:** vtk vtk
- **Attack:** Use-After-Free
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:37:49.520
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-31)

> Kitware VTK (Visualization Toolkit) through 9.5.0 contains a heap use-after-free vulnerability in vtkGLTFDocumentLoader. The vulnerability manifests during mesh object copy operations where vector members are accessed after the underlying memory has been freed, specifically when …

### CVE-2025-64385
**The equipment initially can be configured using the manufacturer's application, by Wi-Fi, by the web server or with the manufacturer’s so...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-10-31)

> The equipment initially can be configured using the manufacturer's application, by Wi-Fi, by the web server or with the manufacturer’s software.
Using the manufacturer's software, the device can be configured via UDP. Analyzing this communication, it has been observed that any as…

### CVE-2025-64388
**Denial of service of the web server through specific requests to this protocol**
- **Signals:** CVSS
- **Attack:** DoS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-400
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-10-31)

> Denial of service of the web server through specific requests to this protocol

### CVE-2025-6520
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Abis Technology BAPSIS allows Blind...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-31)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Abis Technology BAPSIS allows Blind SQL Injection.This issue affects BAPSIS: before 202510271606.

### CVE-2025-8489
**The King Addons for Elementor – Free Elements, Widgets, Templates, and Features for Elementor plugin for WordPress is vulnerable to privi...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-31)

> The King Addons for Elementor – Free Elements, Widgets, Templates, and Features for Elementor plugin for WordPress is vulnerable to privilege escalation in versions 24.12.92 to 51.1.14 . This is due to the plugin not properly restricting the roles that users can register with. Th…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-31*
