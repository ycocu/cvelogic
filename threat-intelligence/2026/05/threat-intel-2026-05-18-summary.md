# Daily Threat Intelligence — May 18, 2026

**Digest window (UTC):** 2026-05-18
**Generated:** 2026-06-02T07:04:03Z

## Threat brief

Ipswitch Ws Ftp Server — exploitation likelihood rose sharply (EPSS 5.9% → 79% · rising (+73%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Ipswitch Ws Ftp Server — exploitation likelihood rose sharply (EPSS 5.9% → 79% · rising (+73%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2006-5000
**ipswitch ws_ftp_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ipswitch ws_ftp_server
- **Attack:** Buffer Overflow
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 81
- **EPSS 5.9% (2026-04-10) → 79.1% (2026-05-18), Δ +73.2%**

> Multiple buffer overflows in WS_FTP Server 5.05 before Hotfix 1, and possibly other versions down to 5.0, have unknown impact and remote authenticated attack vectors via the (1) XCRC, (2) XMD5, and (3) XSHA1 commands.  NOTE: in the early publication of this identifier on 20060926…

### CVE-2006-5028
**swsoft plesk Directory Traversal**
- **Signals:** EPSS
- **Asset:** swsoft plesk
- **Attack:** Directory Traversal
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 78
- **EPSS 36.5% (2025-09-05) → 66.4% (2026-05-18), Δ +29.9%**

> Directory traversal vulnerability in filemanager/filemanager.php in SWsoft Plesk 7.5 Reload and Plesk 7.6 for Microsoft Windows allows remote attackers to list arbitrary directories via a ../ (dot dot slash) in the file parameter in a chdir action.

### CVE-2026-42822
**microsoft azure_local privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_local
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-21T23:45:12.540
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-18)

> Improper authentication in Azure Local Disconnected Operations allows an unauthorized attacker to elevate privileges over a network.

### CVE-2015-10140
**connekthq ajax_load_more**
- **Signals:** EPSS
- **Asset:** connekthq ajax_load_more
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-09T21:16:07.553
- **CWE:** CWE-862
- **CWE:** CWE-862
- **Risk score:** 84
- **EPSS 57.1% (2026-04-07) → 73.9% (2026-05-18), Δ +16.8%**

> The Ajax Load More plugin before 2.8.1.2 does not have authorisation in some of its AJAX actions, allowing any authenticated users, such as subscriber, to upload and delete arbitrary files.

### CVE-2019-0768
**microsoft internet_explorer**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:17:14.997
- **CWE:** CWE-20
- **Risk score:** 77
- **EPSS 72.4% (2026-03-18) → 85.5% (2026-05-18), Δ +13.1%**

> A security feature bypass vulnerability exists when Internet Explorer VBScript execution policy does not properly restrict VBScript under specific conditions, and to allow requests that should otherwise be ignored, aka 'Internet Explorer Security Feature Bypass Vulnerability'. Th…

### CVE-2021-42885
**totolink ex1200t_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** totolink ex1200t_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:28:16.243
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 9.5% (2025-11-21) → 21.8% (2026-05-18), Δ +12.3%**

> TOTOLINK EX1200T V4.1.2cu.5215 contains a remote command injection vulnerability in function setDeviceMac of the file global.so which can control deviceName to attack.

### CVE-2023-24215
**Incorrect access control in the /uci/get/ endpoint of NOVUS AirGate 4G firmware v1.1.16 allows unauthenticated attackers to obtain admini...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-19T15:16:25.950
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-18)

> Incorrect access control in the /uci/get/ endpoint of NOVUS AirGate 4G firmware v1.1.16 allows unauthenticated attackers to obtain administrator credentials via a crafted POST request.

### CVE-2024-32739
**cyberpower powerpanel SQL Injection**
- **Signals:** EPSS
- **Asset:** cyberpower powerpanel
- **Attack:** SQL Injection
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-23T12:15:13.847
- **CWE:** CWE-89
- **Risk score:** 80
- **EPSS 57.8% (2026-05-13) → 68.1% (2026-05-18), Δ +10.3%**

> A sql injection vulnerability exists in CyberPower PowerPanel Enterprise prior to v2.8.3. An unauthenticated remote attacker can leak sensitive information via the "query_ptask_verbose" function within MCUDBHelper.

### CVE-2026-25244
**openjsf webdriverio RCE**
- **Signals:** CVSS
- **Asset:** openjsf webdriverio
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-19T21:08:29.203
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-18)

> WebdriverIO is a test automation framework for unit, e2e and component testing using WebDriver, WebDriver BiDi and Appium. Versions below 9.24.0 contain a command injection vulnerability leading to remote code execution (RCE) in test orchestration. Git permits branch names contai…

### CVE-2026-27130
**Dokploy is a free, self-hostable Platform as a Service (PaaS).**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-05-19T17:16:21.520
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-18)

> Dokploy is a free, self-hostable Platform as a Service (PaaS). Versions 0.26.6 and below have OS command injection through the appName parameter. 3 chained issues cause this problem: inadequate input sanitization, lack of schema validation and direct shell interpolation. User-con…

### CVE-2026-41947
**dify dify privilege escalation**
- **Signals:** CVSS
- **Asset:** dify dify
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T17:16:43.990
- **CWE:** CWE-639
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-18)

> Dify before version 1.14.2 contains an authorization bypass vulnerability that allows authenticated editor users to set and enable trace configurations for any application regardless of tenant ownership. Attackers can exploit missing tenant ownership checks in the trace configura…

### CVE-2026-41948
**dify dify Path Traversal**
- **Signals:** CVSS
- **Asset:** dify dify
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T17:16:44.200
- **CWE:** CWE-23
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-18)

> Dify version 1.14.1 and prior contain a path traversal vulnerability that allows authenticated users to manipulate requests forwarded to the Plugin Daemon's internal REST API by exploiting insufficient URL path sanitization. Attackers can traverse out of their authorized tenant p…

### CVE-2026-45829
**A pre-authentication, code injection vulnerability in version 1.0.0 or later of the ChromaDB Python project allows an unauthenticated att...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-19T14:16:46.977
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-18)

> A pre-authentication, code injection vulnerability in version 1.0.0 or later of the ChromaDB Python project allows an unauthenticated attacker to run arbitrary code on the server by sending a malicious model repository and trust_remote_code set to true in the /api/v2/tenants/{ten…

### CVE-2026-7304
**lmsys sglang RCE**
- **Signals:** CVSS
- **Asset:** lmsys sglang
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-19T13:38:09.460
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-18)

> SGLangs multimodal generation runtime is vulnerable to unauthenticated remote code execution when the --enable-custom-logit-processor option is enabled, as Python objects loaded via dill.loads() will be deserialized without validation.

### CVE-2026-8836
**A vulnerability was found in lwIP up to 2.2.1.**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T19:26:31.620
- **CWE:** CWE-119
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-18)

> A vulnerability was found in lwIP up to 2.2.1. Affected is the function snmp_parse_inbound_frame of the file src/apps/snmp/snmp_msg.c of the component snmpv3 USM Handler. Performing a manipulation of the argument msgAuthenticationParameters results in stack-based buffer overflow.…

### CVE-2026-8838
**Unsafe use of Python's eval() on server-received data in the vector_in() function in amazon-redshift-python-driver before 2.1.14 allows a...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-19T14:24:20.997
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-18)

> Unsafe use of Python's eval() on server-received data in the vector_in() function in amazon-redshift-python-driver before 2.1.14 allows a rogue server or man-in-the-middle actor to execute arbitrary code on the client. 



To remediate this issue, users should upgrade to version …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-18*
