# Daily Threat Intelligence — October 14, 2025

**Digest window (UTC):** 2025-10-14
**Generated:** 2026-06-02T07:33:35Z

## Threat brief

Microsoft Windows: 2 CVEs added to CISA KEV today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows: 2 CVEs added to CISA KEV today.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 4 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2016-7836
**SKYSEA Client View Improper Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** skygroup skysea_client_view
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:06:39.240
- **CWE:** CWE-287
- **CWE:** CWE-287
- **Risk score:** 88
- **KEV:** added 2025-10-14

> SKYSEA Client View Ver.11.221.03 and earlier allows remote code execution via a flaw in processing authentication on the TCP connection with the management console program.

### CVE-2025-49708
**microsoft windows_10_1809 privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft windows_10_1809
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-23T15:45:57.530
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-10-14)

> Use after free in Microsoft Graphics Component allows an authorized attacker to elevate privileges over a network.

### CVE-2025-55315
**microsoft asp.net_core**
- **Signals:** CVSS
- **Asset:** microsoft asp.net_core
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2025-10-28T21:15:37.933
- **CWE:** CWE-444
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-10-14)

> Inconsistent interpretation of http requests ('http request/response smuggling') in ASP.NET Core allows an authorized attacker to bypass a security feature over a network.

### CVE-2025-11548
**A remote, unauthenticated privilege escalation in ibi WebFOCUS allows an attacker to gain administrative access to the application which...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-14)

> A remote, unauthenticated privilege escalation in ibi WebFOCUS allows an attacker to gain administrative access to the application which may lead to unauthenticated Remote Code Execution

### CVE-2025-11717
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:16:40.930
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-14)

> When switching between Android apps using the card carousel Firefox shows a black screen as its card image when a password-related screen was the last one being used. Prior to Firefox 144 the password edit screen was visible. This vulnerability was fixed in Firefox 144.

### CVE-2025-11719
**mozilla firefox Memory Corruption**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:16:41.257
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-14)

> Starting in Thunderbird 143, the use of the native messaging API by web extensions on Windows could lead to crashes caused by use-after-free memory corruption. This vulnerability was fixed in Firefox 144 and Thunderbird 144.

### CVE-2025-11721
**mozilla firefox Memory Corruption**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:16:41.590
- **CWE:** CWE-119
- **CWE:** CWE-119
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-14)

> Memory safety bug present in Firefox 143 and Thunderbird 143. This bug showed evidence of memory corruption and we presume that with enough effort this could have been exploited to run arbitrary code. This vulnerability was fixed in Firefox 144 and Thunderbird 144.

### CVE-2025-24990
**Microsoft Windows Untrusted Pointer Dereference Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-18T17:03:38.993
- **CWE:** CWE-822
- **Risk score:** 88
- **KEV:** added 2025-10-14

> Microsoft is aware of vulnerabilities in the third party Agere Modem driver that ships natively with supported Windows operating systems.  This is an announcement of the upcoming removal of ltmdm64.sys driver.  The driver has been removed in the October cumulative update.
Fax mod…

### CVE-2025-47827
**IGEL OS Use of a Key Past its Expiration Date Vulnerability**
- **Signals:** KEV
- **Asset:** igel igel_os
- **CVSS max:** 4.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:26:25.870
- **CWE:** CWE-347
- **Risk score:** 88
- **KEV:** added 2025-10-14

> In IGEL OS before 11, Secure Boot can be bypassed because the igel-flash-driver module improperly verifies a cryptographic signature. Ultimately, a crafted root filesystem can be mounted from an unverified SquashFS image.

### CVE-2025-49553
**adobe connect XSS**
- **Signals:** CVSS
- **Asset:** adobe connect
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T14:59:03.537
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-14)

> Adobe Connect versions 12.9 and earlier are affected by a DOM-based Cross-Site Scripting (XSS) vulnerability that could be exploited by an attacker to execute malicious scripts in a victim's browser. Exploitation of this issue requires user interaction in that a victim must navig…

### CVE-2025-59230
**Microsoft Windows Improper Access Control Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1507
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-03T13:47:09.720
- **CWE:** CWE-284
- **Risk score:** 88
- **KEV:** added 2025-10-14

> Improper access control in Windows Remote Access Connection Manager allows an authorized attacker to elevate privileges locally.

### CVE-2025-59287
**Microsoft Windows Server Update Service (WSUS) Deserialization of Untrusted Data Vulnerability**
- **Signals:** CVSS
- **Asset:** microsoft windows_server_2012
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-12T14:33:19.727
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-14)

> Deserialization of untrusted data in Windows Server Update Service allows an unauthorized attacker to execute code over a network.

### CVE-2025-62376
**pwn.college DOJO is an education platform for learning cybersecurity.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-10-14)

> pwn.college DOJO is an education platform for learning cybersecurity. Prior to commit 467db0b9ea0d9a929dc89b41f6eb59f7cfc68bef, the /workspace endpoint contains an improper authentication vulnerability that allows an attacker to access any active Windows VM without proper authori…

### CVE-2025-7328
**rockwellautomation 1783-natr_firmware**
- **Signals:** CVSS
- **Asset:** rockwellautomation 1783-natr_firmware
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-29T15:40:38.553
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-10-14)

> Multiple Broken Authentication security issues exist in the affected product. The security issues are due to missing authentication checks on critical functions. These could result in potential denial-of-service, admin account takeover, or NAT rule modifications. Devices would no…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-14*
