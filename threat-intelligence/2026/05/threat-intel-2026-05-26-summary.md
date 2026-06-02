# Daily Threat Intelligence — May 26, 2026

**Digest window (UTC):** 2026-05-26
**Generated:** 2026-06-02T07:04:07Z

## Threat brief

LiteSpeed CPanel Plugin added to CISA KEV — confirmed in-the-wild exploitation. · Apache Http Server: public exploit or PoC linked (RCE) · WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Flowiseai Flowise — exploitation likelihood rose sharply (EPSS 0.2% → 57% · rising (+57%)).

## Executive summary

- LiteSpeed CPanel Plugin added to CISA KEV — confirmed in-the-wild exploitation.
- Apache Http Server: public exploit or PoC linked (RCE)
- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Flowiseai Flowise — exploitation likelihood rose sharply (EPSS 0.2% → 57% · rising (+57%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 4 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **25** |


## CVEs

### CVE-2026-48172
**LiteSpeed cPanel Plugin Privilege Escalation Vulnerability**
- **Signals:** KEV
- **Asset:** litespeedtech litespeed_cpanel_plugin
- **Attack:** Privilege Escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-26T20:19:13.460
- **CWE:** CWE-266
- **Risk score:** 88
- **KEV:** added 2026-05-26

> LiteSpeed User-End cPanel Plugin before 2.4.5 allows privilege escalation (possibly to root), as exploited in the wild in May 2026. Detection is best done via a command line of grep -rE "cpanel_jsonapi_func=redisAble" /var/cpanel/logs /usr/local/cpanel/logs/ 2>/dev/null in Bash. …

### CVE-2026-23918
**apache http_server RCE**
- **Signals:** EXP
- **Asset:** apache http_server
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-04T20:24:58.200
- **CWE:** CWE-415
- **Risk score:** 78
- **EXP:** ref published 2026-05-26

> Double Free and possible RCE vulnerability in Apache HTTP Server with the HTTP/2 protocol.

This issue affects Apache HTTP Server: 2.4.66.

Users are recommended to upgrade to version 2.4.67, which fixes the issue.

### CVE-2024-36420
**flowiseai flowise**
- **Signals:** EPSS
- **Asset:** flowiseai flowise
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T09:22:08.673
- **CWE:** CWE-74
- **CWE:** CWE-74
- **Risk score:** 82
- **EPSS 0.2% (2026-05-22) → 57.5% (2026-05-26), Δ +57.2%**

> Flowise is a drag & drop user interface to build a customized large language model flow. In version 1.4.3 of Flowise, the `/api/v1/openai-assistants-file` endpoint in `index.ts` is vulnerable to arbitrary file read due to lack of sanitization of the `fileName` body parameter. No …

### CVE-2007-5607
**hp instant_support Buffer Overflow**
- **Signals:** EPSS
- **Asset:** hp instant_support
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-94
- **Risk score:** 82
- **EPSS 16.7% (2026-02-21) → 32.9% (2026-05-26), Δ +16.2%**

> Buffer overflow in the RegistryString function in the HPISDataManagerLib.Datamgr ActiveX control in HPISDataManager.dll in HP Instant Support before 1.0.0.24 allows remote attackers to execute arbitrary code via a long first argument, a different vulnerability than CVE-2007-5604,…

### CVE-2020-12284
**canonical debian_linux Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ffmpeg ffmpeg
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:59:26.903
- **CWE:** CWE-787
- **Risk score:** 86
- **EPSS 6.4% (2025-12-28) → 22.0% (2026-05-26), Δ +15.6%**

> cbs_jpeg_split_fragment in libavcodec/cbs_jpeg.c in FFmpeg 4.1 and 4.2.2 has a heap-based buffer overflow during JPEG_MARKER_SOS handling because of a missing length check.

### CVE-2020-28908
**nagios fusion Privilege Escalation**
- **Signals:** EPSS
- **Asset:** nagios fusion
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:23:16.243
- **CWE:** CWE-77
- **Risk score:** 86
- **EPSS 33.3% (2025-11-21) → 48.2% (2026-05-26), Δ +14.9%**

> Command Injection in Nagios Fusion 4.1.8 and earlier allows for Privilege Escalation to nagios.

### CVE-2021-27856
**fatpipeinc ipvpn_firmware privilege escalation**
- **Signals:** EPSS
- **Asset:** fatpipeinc ipvpn_firmware
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:58:38.990
- **Risk score:** 86
- **EPSS 46.3% (2026-03-24) → 70.9% (2026-05-26), Δ +24.6%**

> FatPipe WARP, IPVPN, and MPVPN software prior to versions 10.1.2r60p91 and 10.2.2r42 includes an account named "cmuser" that has administrative privileges and no password. Older versions of FatPipe software may also be vulnerable. The FatPipe advisory identifier for this vulnerab…

### CVE-2022-44456
**contec conprosys_hmi_system**
- **Signals:** EPSS
- **Asset:** contec conprosys_hmi_system
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-17T15:15:49.467
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 86
- **EPSS 8.9% (2026-03-10) → 25.2% (2026-05-26), Δ +16.3%**

> CONPROSYS HMI System (CHS) Ver.3.4.4?and earlier allows a remote unauthenticated attacker to execute an arbitrary OS command on the server where the product is running by sending a specially crafted request.

### CVE-2023-31856
**totolink cp300\+_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** totolink cp300\+_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-01-23T16:15:29.030
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 86
- **EPSS 8.0% (2026-05-17) → 22.6% (2026-05-26), Δ +14.6%**

> A command injection vulnerability in the hostTime parameter in the function NTPSyncWithHostof TOTOLINK CP300+ V5.2cu.7594_B20200910 allows attackers to execute arbitrary commands via a crafted http packet.

### CVE-2023-7327
**Path Traversal · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Path Traversal
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 84
- **EPSS 0.8% (2026-04-22) → 17.6% (2026-05-26), Δ +16.9%**

> Ozeki SMS Gateway versions up to and including 10.3.208 contain a path traversal vulnerability. Successful exploitation allows an unauthenticated attacker to use URL-encoded traversal sequences to read arbitrary files from the underlying filesystem with the privileges of the gate…

### CVE-2024-9362
**Directory Traversal · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Directory Traversal
- **CVSS max:** 7.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 3.1% (2026-04-30) → 24.6% (2026-05-26), Δ +21.4%**

> An unauthenticated directory traversal vulnerability exists in Polyaxon, affecting the latest version. This vulnerability allows an attacker to retrieve directory information and file contents from the server without proper authorization, leading to sensitive information disclosu…

### CVE-2025-32778
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 25.4% (2026-05-24) → 44.7% (2026-05-26), Δ +19.3%**

> Web-Check is an all-in-one OSINT tool for analyzing any website. A command injection vulnerability exists in the screenshot API of the Web Check project (Lissy93/web-check). The issue stems from user-controlled input (url) being passed unsanitized into a shell command using exec(…

### CVE-2026-3660
**ibm engineering_lifecycle_management**
- **Signals:** CVSS
- **Asset:** ibm engineering_lifecycle_management
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-29T19:31:59.120
- **CWE:** CWE-863
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-26)

> IBM Engineering Lifecycle Management 7.0.3, 7.1.0, and 7.2.0 could allow an unauthenticated remote attacker to update server property files that would allow them to gain unauthorized access to the application.

### CVE-2026-41940
**WebPros cPanel & WHM and WP2 (WordPress Squared) Missing Authentication for Critical Function Vulnerability**
- **Signals:** EXP
- **Asset:** cpanel cpanel
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-04T18:09:42.300
- **CWE:** CWE-306
- **Risk score:** 78
- **EXP:** ref published 2026-05-26

> cPanel and WHM versions after 11.40 contain an authentication bypass vulnerability in the login flow that allows unauthenticated remote attackers to gain unauthorized access to the control panel.

### CVE-2026-42607
**RCE · Exploit activity**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T14:51:21.830
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2026-05-26

> Grav is a file-based Web platform. Prior to 2.0.0-beta.2, an authenticated user with administrative privileges can achieve Remote Code Execution (RCE) by uploading a specially crafted ZIP file through the "Direct Install" tool. While the system attempts to block direct .php file …

### CVE-2026-44444
**Lumiverse is a full-featured AI chat application.**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-27T15:16:27.937
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-26)

> Lumiverse is a full-featured AI chat application. Prior to 0.9.7, the Spindle extension build pipeline calls bun install without the --ignore-scripts flag before running the static backend safety scan (assertSafeBackendBundle). A malicious extension that ships a package.json with…

### CVE-2026-44449
**Lumiverse is a full-featured AI chat application.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-27T14:57:07.120
- **CWE:** CWE-88
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-26)

> Lumiverse is a full-featured AI chat application. Prior to 0.9.7, when the primary toSmbPath(fullPath) call throws, the method falls back to a dirname/basename split and only validates the directory prefix. The basename is concatenated directly into the smbclient -c script withou…

### CVE-2026-44450
**Lumiverse is a full-featured AI chat application.**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-05-27T14:57:07.120
- **CWE:** CWE-88
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-26)

> Lumiverse is a full-featured AI chat application. Prior to 0.9.7, the MCP server creation endpoint validates the command field against an allowlist of binary names but forwards the args array to the child process without any validation. Every binary on the allowlist accepts an in…

### CVE-2026-44451
**Lumiverse is a full-featured AI chat application.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-27T18:16:23.607
- **CWE:** CWE-693
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-26)

> Lumiverse is a full-featured AI chat application. Prior to 0.9.7, the component override system transpiles user-supplied TSX via Sucrase and evaluates it with new Function, shadowing dangerous globals (fetch, window, eval, etc.) with undefined. A static source validator (validate…

### CVE-2026-44895
**GitLab MCP Server lets an AI agent talk directly to GitLab.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-06-01T18:22:32.550
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-26)

> GitLab MCP Server lets an AI agent talk directly to GitLab. Prior to 0.6.0, the HTTP transport in src/transport.ts ships with no authentication layer at all and a wildcard Access-Control-Allow-Origin: * on every response. The structural defect is that the SSE server stands up a s…

### CVE-2026-48689
**pavel-odintsov fastnetmon Buffer Overflow**
- **Signals:** CVSS
- **Asset:** pavel-odintsov fastnetmon
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-27T02:16:33.807
- **CWE:** CWE-787
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-26)

> FastNetMon Community Edition through 1.2.9 contains an off-by-one heap-based buffer overflow in the dynamic_binary_buffer_t class (src/dynamic_binary_buffer.hpp). Five methods (append_dynamic_buffer, append_data_as_pointer, append_data_as_object_ptr, memcpy_from_ptr, memcpy_from_…

### CVE-2026-7567
**The Temporary Login plugin for WordPress is vulnerable to Authentication Bypass in versions up to and including 1.0.0.**
- **Signals:** EXP
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-01T15:26:24.553
- **CWE:** CWE-288
- **Risk score:** 78
- **EXP:** ref published 2026-05-26

> The Temporary Login plugin for WordPress is vulnerable to Authentication Bypass in versions up to and including 1.0.0. This is due to improper input validation in the maybe_login_temporary_user() function, which fails to verify that the 'temp-login-token' GET parameter is a scala…

### CVE-2026-9170
**ibm http_server**
- **Signals:** CVSS
- **Asset:** ibm http_server
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-27T19:16:25.223
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-26)

> IBM HTTP Server 8.5, and 9.0

### CVE-2026-9560
**openvpn connect Privilege Escalation**
- **Signals:** CVSS
- **Asset:** openvpn connect
- **Attack:** Privilege Escalation
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T18:08:50.350
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-26)

> Privilege escalation via background service of OpenVPN Connect 3.5.1 through 3.8.1 on macOS allows attackers to execute arbitrary commands with elevated privileges via local IPC channel

### CVE-2026-9642
**deltaww diaview**
- **Signals:** CVSS
- **Asset:** deltaww diaview
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-29T19:53:02.797
- **CWE:** CWE-321
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-26)

> There is a mitigation bypass / (incomplete fix) for CVE-2025-62582 (Unauthenticated Remote Database Access) 

An unauthenticated remote attacker can access configured databases in a DIAView project.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-26*
