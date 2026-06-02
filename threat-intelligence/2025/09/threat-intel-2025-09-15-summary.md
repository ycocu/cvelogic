# Daily Threat Intelligence — September 15, 2025

**Digest window (UTC):** 2025-09-15
**Generated:** 2026-06-02T07:33:25Z

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

### CVE-2025-31255
**apple ipados privilege escalation**
- **Signals:** CVSS
- **Asset:** apple ipados
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-02T19:19:55.903
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-15)

> An authorization issue was addressed with improved state management. This issue is fixed in iOS 26 and iPadOS 26, macOS Sequoia 15.7, macOS Sonoma 14.8, macOS Tahoe 26, tvOS 26, watchOS 26. An app may be able to access sensitive user data.

### CVE-2025-52053
**totolink x6000r_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** totolink x6000r_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-20T02:49:46.760
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-15)

> TOTOLINK X6000R V9.4.0cu.1360_B20241207 was found to contain a command injection vulnerability in the sub_417D74 function via the file_name parameter. This vulnerability allows unauthenticated attackers to execute arbitrary commands via a crafted request.

### CVE-2025-57118
**phpgurukul online_library_management_system privilege escalation**
- **Signals:** CVSS
- **Asset:** phpgurukul online_library_management_system
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-18T16:48:50.220
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-15)

> An issue in PHPGurukul Online-Library-Management-System v3.0 allows an attacker to escalate privileges via the index.php

### CVE-2025-43342
**apple ipados**
- **Signals:** CVSS
- **Asset:** apple safari
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-02T19:20:30.237
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-15)

> A correctness issue was addressed with improved checks. This issue is fixed in Safari 26, iOS 18.7 and iPadOS 18.7, iOS 26 and iPadOS 26, macOS Tahoe 26, tvOS 26, visionOS 26, watchOS 26. Processing maliciously crafted web content may lead to an unexpected process crash.

### CVE-2025-43343
**apple ipados**
- **Signals:** CVSS
- **Asset:** apple safari
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-02T19:20:30.460
- **CWE:** CWE-119
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-15)

> The issue was addressed with improved memory handling. This issue is fixed in Safari 26, iOS 26 and iPadOS 26, macOS Tahoe 26, tvOS 26, visionOS 26, watchOS 26. Processing maliciously crafted web content may lead to an unexpected process crash.

### CVE-2025-43347
**apple ipados**
- **Signals:** CVSS
- **Asset:** apple ipados
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-02T19:20:31.280
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-15)

> This issue was addressed by removing the vulnerable code. This issue is fixed in iOS 26 and iPadOS 26, macOS Tahoe 26, tvOS 26, visionOS 26, watchOS 26. An input validation issue was addressed.

### CVE-2025-43359
**apple ipados**
- **Signals:** CVSS
- **Asset:** apple ipados
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-02T19:20:33.303
- **CWE:** CWE-670
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-15)

> A logic issue was addressed with improved state management. This issue is fixed in iOS 18.7 and iPadOS 18.7, iOS 26 and iPadOS 26, macOS Sequoia 15.7, macOS Sonoma 14.8, macOS Tahoe 26, tvOS 26, visionOS 26, watchOS 26. A UDP server socket bound to a local interface may become bo…

### CVE-2025-43362
**apple ipados**
- **Signals:** CVSS
- **Asset:** apple ipados
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-02T19:20:33.843
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-15)

> The issue was addressed with improved checks. This issue is fixed in iOS 18.7 and iPadOS 18.7, iOS 26 and iPadOS 26. An app may be able to monitor keystrokes without user permission.

### CVE-2025-46408
**avtech eagleeyes\(lite\)**
- **Signals:** CVSS
- **Asset:** avtech eagleeyes\(lite\)
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T14:51:26.313
- **CWE:** CWE-297
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-15)

> An issue was discovered in the methods push.lite.avtech.com.AvtechLib.GetHttpsResponse and push.lite.avtech.com.Push_HttpService.getNewHttpClient in AVTECH EagleEyes 2.0.0. The methods set ALLOW_ALL_HOSTNAME_VERIFIER, bypassing domain validation.

### CVE-2025-57174
**An issue was discovered in Siklu Communications Etherhaul 8010TX and 1200FX devices, Firmware 7.4.0 through 10.7.3 and possibly other pre...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-321
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-15)

> An issue was discovered in Siklu Communications Etherhaul 8010TX and 1200FX devices, Firmware 7.4.0 through 10.7.3 and possibly other previous versions. The rfpiped service listening on TCP port 555 which uses static AES encryption keys hardcoded in the binary. These keys are ide…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-15*
