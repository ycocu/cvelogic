# Daily Threat Intelligence — March 20, 2026

**Digest window (UTC):** 2026-03-20
**Generated:** 2026-06-02T07:34:42Z

## Threat brief

Apple Multiple Products: 3 CVEs added to CISA KEV today. · Themerex Addons — exploitation likelihood rose sharply (EPSS 48% → 67% · rising (+19%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apple Multiple Products: 3 CVEs added to CISA KEV today.
- Themerex Addons — exploitation likelihood rose sharply (EPSS 48% → 67% · rising (+19%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 5 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2025-31277
**Apple Multiple Products Buffer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** apple safari
- **Attack:** Buffer Overflow
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T14:30:40.733
- **CWE:** CWE-119
- **Risk score:** 88
- **KEV:** added 2026-03-20

> The issue was addressed with improved memory handling. This issue is fixed in Safari 18.6, iOS 18.6 and iPadOS 18.6, macOS Sequoia 15.6, tvOS 18.6, visionOS 2.6, watchOS 11.6. Processing maliciously crafted web content may lead to memory corruption.

### CVE-2020-10257
**themerex addons**
- **Signals:** EPSS
- **Asset:** themerex addons
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:55:05.053
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 47.8% (2025-12-19) → 66.6% (2026-03-20), Δ +18.8%**

> The ThemeREX Addons plugin before 2020-03-09 for WordPress lacks access control on the /trx_addons/v2/get/sc_layout REST API endpoint, allowing for PHP functions to be executed by any users, because includes/plugin.rest-api.php calls trx_addons_rest_get_sc_layout with an unsafe s…

### CVE-2024-44722
**anolis sysak**
- **Signals:** CVSS
- **Asset:** anolis sysak
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T20:48:22.810
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-20)

> SysAK v2.0 and before is vulnerable to command execution via aaa;cat /etc/passwd.

### CVE-2021-45793
**slims senayan_library_management_system SQL Injection**
- **Signals:** EPSS
- **Asset:** slims senayan_library_management_system
- **Attack:** SQL Injection
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:33:03.730
- **CWE:** CWE-89
- **Risk score:** 82
- **EPSS 15.4% (2026-03-14) → 31.5% (2026-03-20), Δ +16.1%**

> Slims9 Bulian 9.4.2 is affected by SQL injection in lib/comment.inc.php. User data can be obtained.

### CVE-2021-45968
**jivesoftware cloud_phone_system SSRF**
- **Signals:** EPSS
- **Asset:** jivesoftware jive
- **Attack:** SSRF
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:33:23.793
- **CWE:** CWE-918
- **Risk score:** 82
- **EPSS 71.6% (2026-03-14) → 86.8% (2026-03-20), Δ +15.2%**

> An issue was discovered in xmppserver jar in the XMPP Server component of the JIve platform, as used in Pascom Cloud Phone System before 7.20.x (and in other products). An endpoint in the backend Tomcat server of the Pascom allows SSRF, a related issue to CVE-2019-18394.

### CVE-2025-32432
**Craft CMS Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** craftcms craft_cms
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-20T19:14:20.843
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2026-03-20

> Craft is a flexible, user-friendly CMS for creating custom digital experiences on the web and beyond. Starting from version 3.0.0-RC1 to before 3.9.15, 4.0.0-RC1 to before 4.14.15, and 5.0.0-RC1 to before 5.6.17, Craft is vulnerable to remote code execution. This is a high-impact…

### CVE-2025-43510
**Apple Multiple Products Improper Locking Vulnerability**
- **Signals:** KEV
- **Asset:** apple ipados
- **Attack:** Memory Corruption
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T14:28:19.317
- **CWE:** CWE-667
- **Risk score:** 88
- **KEV:** added 2026-03-20

> A memory corruption issue was addressed with improved lock state checking. This issue is fixed in iOS 18.7.2 and iPadOS 18.7.2, iOS 26.1 and iPadOS 26.1, macOS Sequoia 15.7.2, macOS Sonoma 14.8.2, macOS Tahoe 26.1, tvOS 26.1, visionOS 26.1, watchOS 26.1. A malicious application m…

### CVE-2025-43520
**Apple Multiple Products Classic Buffer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** apple ipados
- **Attack:** Buffer Overflow
- **CVSS max:** 5.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T14:28:03.810
- **CWE:** CWE-120
- **Risk score:** 88
- **KEV:** added 2026-03-20

> A memory corruption issue was addressed with improved memory handling. This issue is fixed in iOS 18.7.2 and iPadOS 18.7.2, iOS 26.1 and iPadOS 26.1, macOS Sequoia 15.7.2, macOS Sonoma 14.8.2, macOS Tahoe 26.1, tvOS 26.1, visionOS 26.1, watchOS 26.1. A malicious application may b…

### CVE-2025-54068
**Laravel Livewire Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** laravel livewire
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-20T18:36:12.533
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2026-03-20

> Livewire is a full-stack framework for Laravel. In Livewire v3 up to and including v3.6.3, a vulnerability allows unauthenticated attackers to achieve remote command execution in specific scenarios. The issue stems from how certain component property updates are hydrated. This vu…

### CVE-2026-21732
**imaginationtech ddk Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** imaginationtech ddk
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T16:55:05.810
- **CWE:** CWE-823
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-03-20)

> A web page that contains unusual GPU shader code is loaded into the GPU compiler process and can trigger a write out-of-bounds write crash in the GPU shader compiler library. On certain platforms, when the compiler process has system privileges this could enable further exploits …

### CVE-2026-22172
**openclaw openclaw privilege escalation**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-24T21:20:45.707
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-20)

> OpenClaw versions prior to 2026.3.12 contain an authorization bypass vulnerability in the WebSocket connect path that allows shared-token or password-authenticated connections to self-declare elevated scopes without server-side binding. Attackers can exploit this logic flaw to pr…

### CVE-2026-22898
**qnap qvr_pro**
- **Signals:** CVSS
- **Asset:** qnap qvr_pro
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T14:33:30.040
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-20)

> A missing authentication for critical function vulnerability has been reported to affect QVR Pro. The remote attackers can then exploit the vulnerability to gain access to the system.

We have already fixed the vulnerability in the following version:
QVR Pro 2.7.4.14 and later

### CVE-2026-25192
**ctek charge_portal**
- **Signals:** CVSS
- **Asset:** ctek charge_portal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-06T15:19:41.897
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-20)

> WebSocket endpoints lack proper authentication mechanisms, enabling attackers to perform unauthorized station impersonation and manipulate data sent to the backend. An unauthenticated attacker can connect to the OCPP WebSocket endpoint using a known or discovered charging station…

### CVE-2026-29796
**igl eparking.fi**
- **Signals:** CVSS
- **Asset:** igl eparking.fi
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-13T16:33:23.903
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-20)

> WebSocket endpoints lack proper authentication mechanisms, enabling attackers to perform unauthorized station impersonation and manipulate data sent to the backend. An unauthenticated attacker can connect to the OCPP WebSocket endpoint using a known or discovered charging station…

### CVE-2026-33135
**wegia wegia XSS**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-20T19:25:45.043
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-20)

> WeGIA is a web manager for charitable institutions. Versions 3.6.6 and below have a Reflected Cross-Site Scripting (XSS) vulnerability in the novo_memorandoo.php endpoint. An attacker can inject arbitrary JavaScript into the sccs GET parameter, which is directly echoed into the H…

### CVE-2026-33136
**wegia wegia XSS**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-20T19:23:40.980
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-20)

> WeGIA is a web manager for charitable institutions. Versions 3.6.6 and below have a Reflected Cross-Site Scripting (XSS) vulnerability in the listar_memorandos_ativos.php endpoint. An attacker can inject arbitrary JavaScript or HTML tags into the sccd GET parameter, which is then…

### CVE-2026-33186
**grpc grpc privilege escalation**
- **Signals:** CVSS
- **Asset:** grpc grpc
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-10T20:49:17.737
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-20)

> gRPC-Go is the Go language implementation of gRPC. Versions prior to 1.79.3 have an authorization bypass resulting from improper input validation of the HTTP/2 `:path` pseudo-header. The gRPC-Go server was too lenient in its routing logic, accepting requests where the `:path` omi…

### CVE-2026-3584
**The Kali Forms plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 2.4.9 via the 'form_proc...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-22T21:32:08.360
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-20)

> The Kali Forms plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 2.4.9 via the 'form_process' function. This is due to the 'prepare_post_data' function mapping user-supplied keys directly into internal placeholder storage, combined …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-20*
