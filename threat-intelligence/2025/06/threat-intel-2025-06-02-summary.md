# Daily Threat Intelligence — June 02, 2025

**Digest window (UTC):** 2025-06-02
**Generated:** 2026-06-02T07:32:49Z

## Threat brief

Craft CMS: 2 CVEs added to CISA KEV today. · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- Craft CMS: 2 CVEs added to CISA KEV today.
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 5 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2021-32030
**ASUS Routers Improper Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** asus lyra_mini_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-10T14:41:07.340
- **CWE:** CWE-287
- **CWE:** CWE-287
- **Risk score:** 88
- **KEV:** added 2025-06-02

> The administrator application on ASUS GT-AC2900 devices before 3.0.0.4.386.42643 and Lyra Mini before 3.0.0.4_384_46630 allows authentication bypass when processing remote input from an unauthenticated user, leading to unauthorized access to the administrator interface. This rela…

### CVE-2025-49113
**RoundCube Webmail Deserialization of Untrusted Data Vulnerability**
- **Signals:** CVSS
- **Asset:** roundcube webmail
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T13:24:21.387
- **CWE:** CWE-502
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-06-02)

> Roundcube Webmail before 1.5.10 and 1.6.x before 1.6.11 allows remote code execution by authenticated users because the _from parameter in a URL is not validated in program/actions/settings/upload.php, leading to PHP Object Deserialization.

### CVE-2025-1750
**llamaindex llamaindex RCE**
- **Signals:** CVSS
- **Asset:** llamaindex llamaindex
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-31T16:08:49.087
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-02)

> An SQL injection vulnerability exists in the delete function of DuckDBVectorStore in run-llama/llama_index version v0.12.19. This vulnerability allows an attacker to manipulate the ref_doc_id parameter, enabling them to read and write arbitrary files on the server, potentially le…

### CVE-2023-39780
**ASUS RT-AX55 Routers OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** asus rt-ax55_firmware
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T14:39:25.973
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2025-06-02

> On ASUS RT-AX55 3.0.0.4.386.51598 devices, authenticated attackers can perform OS command injection via the /start_apply.htm qos_bw_rulelist parameter. NOTE: for the similar "token-generated module" issue, see CVE-2023-41345; for the similar "token-refresh module" issue, see CVE-…

### CVE-2024-56145
**Craft CMS Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** craftcms craft_cms
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T14:00:03.477
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2025-06-02

> Craft is a flexible, user-friendly CMS for creating custom digital experiences on the web and beyond. Users of affected versions are affected by this vulnerability if their php.ini configuration has `register_argc_argv` enabled. For these users an unspecified remote code executio…

### CVE-2025-0324
**axis axis_os Privilege Escalation**
- **Signals:** CVSS
- **Asset:** axis axis_os
- **Attack:** Privilege Escalation
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T15:42:33.923
- **CWE:** CWE-791
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-06-02)

> The VAPIX Device Configuration framework allowed a privilege escalation, enabling a lower-privileged user to gain administrator privileges.

### CVE-2025-20672
**mediatek mt7902_firmware memory safety**
- **Signals:** CVSS
- **Asset:** mediatek mt7902_firmware
- **Attack:** memory safety
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-02T15:41:26.327
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-02)

> In Bluetooth driver, there is a possible out of bounds write due to an incorrect bounds check. This could lead to local escalation of privilege with User execution privileges needed. User interaction is not needed for exploitation. Patch ID: WCNCR00412257; Issue ID: MSV-3292.

### CVE-2025-20674
**mediatek openwrt privilege escalation**
- **Signals:** CVSS
- **Asset:** openwrt openwrt
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-18T17:16:22.560
- **CWE:** CWE-863
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-02)

> In wlan AP driver, there is a possible way to inject arbitrary packet due to a missing permission check. This could lead to remote escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation. Patch ID: WCNCR00413202; Iss…

### CVE-2025-23099
**samsung exynos_1480_firmware Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** samsung exynos_1480_firmware
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-13T18:04:25.877
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-02)

> An issue was discovered in Samsung Mobile Processor Exynos 1480 and 2400. The lack of a length check leads to out-of-bounds writes.

### CVE-2025-35939
**Craft CMS External Control of Assumed-Immutable Web Parameter Vulnerability**
- **Signals:** KEV
- **Asset:** craftcms craft_cms
- **CVSS max:** 6.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:45:43.720
- **CWE:** CWE-472
- **Risk score:** 88
- **KEV:** added 2025-06-02

> Craft CMS stores arbitrary content provided by unauthenticated users in session files. This content could be accessed and executed, possibly using an independent vulnerability. Craft CMS redirects requests that require authentication to the login page and generates a session file…

### CVE-2025-37093
**hpe storeonce_system Auth Bypass**
- **Signals:** CVSS
- **Asset:** hpe storeonce_system
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-02T01:12:24.617
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-02)

> An authentication bypass vulnerability exists in HPE StoreOnce Software.

### CVE-2025-3935
**ConnectWise ScreenConnect Improper Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** connectwise screenconnect
- **Attack:** privilege escalation
- **CVSS max:** 8.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:55:32.970
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2025-06-02

> ScreenConnect versions 25.2.3 and earlier versions may be susceptible to a ViewState code injection attack. ASP.NET Web Forms use ViewState to preserve page and control state, with data encoded using Base64 protected by machine keys. 
It is important to note that to obtain these …

### CVE-2025-5086
**Dassault Systèmes DELMIA Apriso Deserialization of Untrusted Data Vulnerability**
- **Signals:** CVSS
- **Asset:** 3ds delmia_apriso
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-29T13:50:15.843
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-06-02)

> A deserialization of untrusted data vulnerability affecting DELMIA Apriso from Release 2020 through Release 2025 could lead to a remote code execution.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-02*
