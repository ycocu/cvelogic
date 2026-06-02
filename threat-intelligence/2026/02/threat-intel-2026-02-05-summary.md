# Daily Threat Intelligence — February 05, 2026

**Digest window (UTC):** 2026-02-05
**Generated:** 2026-06-02T07:34:21Z

## Threat brief

SmarterTools SmarterMail added to CISA KEV — confirmed in-the-wild exploitation. · Sun Solaris — exploitation likelihood rose sharply (EPSS 8.3% → 23% · rising (+14%)). · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- SmarterTools SmarterMail added to CISA KEV — confirmed in-the-wild exploitation.
- Sun Solaris — exploitation likelihood rose sharply (EPSS 8.3% → 23% · rising (+14%)).
- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-11953
**React Native Community CLI OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** react-native-community react_native_community_cli
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-06T19:43:47.703
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2026-02-05

> The Metro Development Server, which is opened by the React Native Community CLI, binds to external interfaces by default. The server exposes an endpoint that is vulnerable to OS command injection. This allows unauthenticated network attackers to send a POST request to the server …

### CVE-1999-0210
**sun solaris privilege escalation**
- **Signals:** EPSS
- **Asset:** sun solaris
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 86
- **EPSS 8.3% (2025-05-26) → 22.6% (2026-02-05), Δ +14.2%**

> Automount daemon automountd allows local or remote users to gain privileges via shell metacharacters.

### CVE-2025-68121
**golang go**
- **Signals:** CVSS
- **Asset:** golang go
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T14:16:16.170
- **CWE:** CWE-295
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-05)

> During session resumption in crypto/tls, if the underlying Config has its ClientCAs or RootCAs fields mutated between the initial handshake and the resumed handshake, the resumed handshake may succeed when it should have failed. This may happen when a user calls Config.Clone and …

### CVE-2004-1288
**siag o3read Buffer Overflow**
- **Signals:** EPSS
- **Asset:** siag o3read
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 84
- **EPSS 8.5% (2025-05-26) → 19.3% (2026-02-05), Δ +10.8%**

> Buffer overflow in the parse_html function in o3read.c for o3read 0.0.3 allows remote attackers to execute arbitrary code via a crafted SXW file.

### CVE-2020-37123
**Pinger 1.0 contains a remote code execution vulnerability that allows attackers to inject shell commands through the ping and socket para...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-05)

> Pinger 1.0 contains a remote code execution vulnerability that allows attackers to inject shell commands through the ping and socket parameters. Attackers can exploit the unsanitized input in ping.php to write arbitrary PHP files and execute system commands by appending shell met…

### CVE-2020-37125
**edimax ew-7438rpn_mini_firmware RCE**
- **Signals:** CVSS
- **Asset:** edimax ew-7438rpn_mini_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T18:09:41.337
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-05)

> Edimax EW-7438RPn-v3 Mini 1.27 contains a remote code execution vulnerability that allows unauthenticated attackers to execute arbitrary commands through the /goform/mp endpoint. Attackers can exploit the vulnerability by sending crafted POST requests with command injection paylo…

### CVE-2025-68723
**axigen axigen_mail_server XSS**
- **Signals:** CVSS
- **Asset:** axigen axigen_mail_server
- **Attack:** XSS
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2026-02-13T15:15:57.503
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-02-05)

> Axigen Mail Server before 10.5.57 contains multiple stored Cross-Site Scripting (XSS) vulnerabilities in the WebAdmin interface. Three instances exist: (1) the log file name parameter in the Local Services Log page, (2) certificate file content in the SSL Certificates View Usage …

### CVE-2026-0106
**google android privilege escalation**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-02-19T18:24:53.930
- **CWE:** CWE-119
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-05)

> In vpu_mmap of vpu_ioctl, there is a possible arbitrary address mmap due to a missing bounds check. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2026-24300
**microsoft azure_front_door privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_front_door
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-12T19:02:39.727
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-05)

> Azure Front Door Elevation of Privilege Vulnerability

### CVE-2026-24423
**SmarterTools SmarterMail Missing Authentication for Critical Function Vulnerability**
- **Signals:** KEV
- **Asset:** smartertools smartermail
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-06T16:45:15.323
- **CWE:** CWE-306
- **Risk score:** 88
- **KEV:** added 2026-02-05

> SmarterTools SmarterMail versions prior to build 9511 contain an unauthenticated remote code execution vulnerability in the ConnectToHub API method. The attacker could point the SmarterMail to the malicious HTTP server, which serves the malicious OS command. This command will be …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-05*
