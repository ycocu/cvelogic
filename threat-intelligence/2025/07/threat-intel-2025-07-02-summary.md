# Daily Threat Intelligence — July 02, 2025

**Digest window (UTC):** 2025-07-02
**Generated:** 2026-06-02T07:32:59Z

## Threat brief

Google Chromium V8 added to CISA KEV — confirmed in-the-wild exploitation. · Wing FTP Server: public exploit or PoC linked (RCE) · Adobe Acrobat — exploitation likelihood rose sharply (EPSS 7.2% → 26% · rising (+19%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Google Chromium V8 added to CISA KEV — confirmed in-the-wild exploitation.
- Wing FTP Server: public exploit or PoC linked (RCE)
- Adobe Acrobat — exploitation likelihood rose sharply (EPSS 7.2% → 26% · rising (+19%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 4 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2025-6554
**Google Chromium V8 Type Confusion Vulnerability**
- **Signals:** KEV
- **Asset:** google chrome
- **CVSS max:** 8.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T14:11:20.707
- **CWE:** CWE-843
- **Risk score:** 88
- **KEV:** added 2025-07-02

> Type confusion in V8 in Google Chrome prior to 138.0.7204.96 allowed a remote attacker to perform arbitrary read/write via a crafted HTML page. (Chromium security severity: High)

### CVE-2024-39930
**gogs gogs RCE**
- **Signals:** EXP
- **Asset:** gogs gogs
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-04-11T15:14:27.963
- **CWE:** CWE-88
- **Risk score:** 78
- **EXP:** ref published 2025-07-02

> The built-in SSH server of Gogs through 0.13.0 allows argument injection in internal/ssh/ssh.go, leading to remote code execution. Authenticated attackers can exploit this by opening an SSH connection and sending a malicious --split-string env request if the built-in SSH server i…

### CVE-2013-3355
**adobe acrobat DoS**
- **Signals:** EPSS
- **Asset:** adobe acrobat
- **Attack:** DoS
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 7.2% (2025-03-30) → 26.1% (2025-07-02), Δ +18.9%**

> Adobe Reader and Acrobat before 10.1.8 and 11.x before 11.0.04 on Windows and Mac OS X allow attackers to execute arbitrary code or cause a denial of service (memory corruption) via unspecified vectors, a different vulnerability than CVE-2013-3352 and CVE-2013-3354.

### CVE-2024-43425
**moodle moodle RCE**
- **Signals:** EXP
- **Asset:** moodle moodle
- **Attack:** RCE
- **CVSS max:** 8.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-01T16:01:21.307
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-07-02

> A flaw was found in Moodle. Additional restrictions are required to avoid a remote code execution risk in calculated question types. Note: This requires the capability to add/update questions.

### CVE-2025-20309
**cisco unified_communications_manager**
- **Signals:** CVSS
- **Asset:** cisco unified_communications_manager
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-03T15:23:28.870
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-02)

> A vulnerability in Cisco Unified Communications Manager (Unified CM) and Cisco Unified Communications Manager Session Management Edition (Unified CM SME) could allow an unauthenticated, remote attacker to log in to an affected device using the root account, which has default, sta…

### CVE-2025-34067
**An unauthenticated remote command execution vulnerability exists in the applyCT component of the Hikvision Integrated Security Management...**
- **Signals:** CVSS
- **Attack:** unsafe deserialization
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-02)

> An unauthenticated remote command execution vulnerability exists in the applyCT component of the Hikvision Integrated Security Management Platform due to the use of a vulnerable version of the Fastjson library. The endpoint /bic/ssoService/v1/applyCT deserializes untrusted user i…

### CVE-2025-34069
**gfi kerio_control Auth Bypass**
- **Signals:** CVSS
- **Asset:** gfi kerio_control
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-17T14:01:51.437
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-07-02)

> An authentication bypass vulnerability exists in GFI Kerio Control 9.4.5 due to insecure default proxy configuration and weak access control in the GFIAgent service. The non-transparent proxy on TCP port 3128 can be used to forward unauthenticated requests to internal services su…

### CVE-2025-34070
**gfi kerio_control privilege escalation**
- **Signals:** CVSS
- **Asset:** gfi kerio_control
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-17T13:56:58.470
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-02)

> A missing authentication vulnerability in the GFIAgent component of GFI Kerio Control 9.4.5 allows unauthenticated remote attackers to perform privileged operations. The GFIAgent service, responsible for integration with GFI AppManager, exposes HTTP services on ports 7995 and 799…

### CVE-2025-34071
**gfi kerio_control RCE**
- **Signals:** CVSS
- **Asset:** gfi kerio_control
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-17T13:41:43.400
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-02)

> A remote code execution vulnerability in GFI Kerio Control 9.4.5 allows attackers with administrative access to upload and execute arbitrary code through the firmware upgrade feature. The system upgrade mechanism accepts unsigned .img files, which can be modified to include malic…

### CVE-2025-34072
**A data exfiltration vulnerability exists in Anthropic’s deprecated Slack Model Context Protocol (MCP) Server via automatic link unfurling.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-02)

> A data exfiltration vulnerability exists in Anthropic’s deprecated Slack Model Context Protocol (MCP) Server via automatic link unfurling. When an AI agent using the Slack MCP Server processes untrusted data, it can be manipulated to generate messages containing attacker-crafted …

### CVE-2025-34073
**An unauthenticated command injection vulnerability exists in stamparm/maltrail (Maltrail) versions <=0.54.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-02)

> An unauthenticated command injection vulnerability exists in stamparm/maltrail (Maltrail) versions <=0.54. A remote attacker can execute arbitrary operating system commands via the username parameter in a POST request to the /login endpoint. This occurs due to unsafe handling of …

### CVE-2025-34074
**An authenticated remote code execution vulnerability exists in Lucee’s administrative interface due to insecure design in the scheduled t...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-02)

> An authenticated remote code execution vulnerability exists in Lucee’s administrative interface due to insecure design in the scheduled task functionality. An administrator with access to /lucee/admin/web.cfm can configure a scheduled job to retrieve a remote .cfm file from an at…

### CVE-2025-45813
**enensys ipguardv2_firmware**
- **Signals:** CVSS
- **Asset:** enensys ipguardv2_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-10T19:41:51.730
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-02)

> ENENSYS IPGuard v2 2.10.0 was discovered to contain hardcoded credentials.

### CVE-2025-45814
**novelsat ns2000_firmware**
- **Signals:** CVSS
- **Asset:** novelsat ns3000_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-10T19:45:37.673
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-02)

> Missing authentication checks in the query.fcgi endpoint of NS3000 v8.1.1.125110 , v7.2.8.124852 , and v7.x and NS2000 v7.02.08 allows attackers to execute a session hijacking attack.

### CVE-2025-47166
**microsoft sharepoint_enterprise_server Deserialization**
- **Signals:** EXP
- **Asset:** microsoft sharepoint_enterprise_server
- **Attack:** Deserialization
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-09T14:02:40.430
- **CWE:** CWE-502
- **Risk score:** 78
- **EXP:** ref published 2025-07-02

> Deserialization of untrusted data in Microsoft Office SharePoint allows an authorized attacker to execute code over a network.

### CVE-2025-47812
**Wing FTP Server Improper Neutralization of Null Byte or NUL Character Vulnerability**
- **Signals:** EXP
- **Asset:** wftpserver wing_ftp_server
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:26:31.650
- **CWE:** CWE-158
- **Risk score:** 78
- **EXP:** ref published 2025-07-02

> In Wing FTP Server before 7.4.4. the user and admin web interfaces mishandle '\0' bytes, ultimately allowing injection of arbitrary Lua code into user session files. This can be used to execute arbitrary system commands with the privileges of the FTP service (root or SYSTEM by de…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-02*
