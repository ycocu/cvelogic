# Daily Threat Intelligence — May 04, 2026

**Digest window (UTC):** 2026-05-04
**Generated:** 2026-06-02T07:03:56Z

## Threat brief

Linux Kernel: public exploit or PoC linked (Use-After-Free) · Etherpad Lite — exploitation likelihood rose sharply (EPSS 60% → 77% · rising (+17%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Linux Kernel: public exploit or PoC linked (Use-After-Free)
- Etherpad Lite — exploitation likelihood rose sharply (EPSS 60% → 77% · rising (+17%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 6 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2025-60690
**linksys e1200_firmware Buffer Overflow**
- **Signals:** EXP
- **Asset:** linksys e1200_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-17T16:16:18.367
- **CWE:** CWE-121
- **Risk score:** 78
- **EXP:** ref published 2026-05-04

> A stack-based buffer overflow exists in the get_merge_ipaddr function of the httpd binary on Linksys E1200 v2 routers (Firmware E1200_v2.0.11.001_us.tar.gz). The function concatenates up to four user-supplied CGI parameters matching <parameter>_0~3 into a fixed-size buffer (a2) w…

### CVE-2026-21250
**microsoft windows_11_24h2 privilege escalation**
- **Signals:** EXP
- **Asset:** microsoft windows_11_24h2
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T19:49:34.573
- **CWE:** CWE-822
- **Risk score:** 78
- **EXP:** ref published 2026-05-04

> Untrusted pointer dereference in Windows HTTP.sys allows an authorized attacker to elevate privileges locally.

### CVE-2018-9845
**etherpad etherpad_lite**
- **Signals:** EPSS
- **Asset:** etherpad etherpad_lite
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:15:47.760
- **CWE:** CWE-178
- **Risk score:** 86
- **EPSS 60.2% (2026-01-19) → 77.2% (2026-05-04), Δ +17.0%**

> Etherpad Lite before 1.6.4 is exploitable for admin access.

### CVE-2017-8734
**microsoft edge Memory Corruption**
- **Signals:** EPSS
- **Asset:** microsoft edge
- **Attack:** Memory Corruption
- **CVSS max:** 7.6
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 58.1% (2026-03-17) → 70.0% (2026-05-04), Δ +11.9%**

> Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to the way that Microsoft Edge accesses objects in memory, aka "Microsoft Edge Memory Corruption Vulnerabili…

### CVE-2025-40271
**In the Linux kernel, the following vulnerability has been resolved: fs/proc: fix uaf in proc_readdir_de() Pde is erased from subdir rbtre...**
- **Signals:** EXP
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 78
- **EXP:** ref published 2026-05-04

> In the Linux kernel, the following vulnerability has been resolved:

fs/proc: fix uaf in proc_readdir_de()

Pde is erased from subdir rbtree through rb_erase(), but not set the node
to EMPTY, which may result in uaf access.  We should use RB_CLEAR_NODE()
set the erased node to EM…

### CVE-2025-68930
**traccar traccar**
- **Signals:** EXP
- **Asset:** traccar traccar
- **CVSS max:** 7.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T16:30:45.903
- **CWE:** CWE-1385
- **Risk score:** 78
- **EXP:** ref published 2026-05-04

> Versions of the Traccar open-source GPS tracking system up to and including 6.11.1 contain a Cross-Site WebSocket Hijacking (CSWSH) vulnerability in the `/api/socket` endpoint. The application fails to validate the `Origin` header during the WebSocket handshake. This allows a rem…

### CVE-2026-23231
**linux linux_kernel Use-After-Free**
- **Signals:** EXP
- **Asset:** linux linux_kernel
- **Attack:** Use-After-Free
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-02T15:16:24.693
- **CWE:** CWE-416
- **Risk score:** 78
- **EXP:** ref published 2026-05-04

> In the Linux kernel, the following vulnerability has been resolved:

netfilter: nf_tables: fix use-after-free in nf_tables_addchain()

nf_tables_addchain() publishes the chain to table->chains via
list_add_tail_rcu() (in nft_chain_add()) before registering hooks.
If nf_tables_reg…

### CVE-2026-27483
**mindsdb mindsdb Path Traversal**
- **Signals:** EXP
- **Asset:** mindsdb mindsdb
- **Attack:** Path Traversal
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T15:35:44.480
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2026-05-04

> MindsDB is a platform for building artificial intelligence from enterprise data. Prior to version 25.9.1.1, there is a path traversal vulnerability in Mindsdb's /api/files interface, which an authenticated attacker can exploit to achieve remote command execution. The vulnerabilit…

### CVE-2026-41922
**WDR201A WiFi Extender (HW V2.1, FW LFMZX28040922V1.02) contains an OS command injection vulnerability in the wireless.cgi binary that all...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T14:16:36.380
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-04)

> WDR201A WiFi Extender (HW V2.1, FW LFMZX28040922V1.02) contains an OS command injection vulnerability in the wireless.cgi binary that allows unauthenticated remote attackers to execute arbitrary shell commands by injecting malicious input into the sz11gChannel or PIN POST paramet…

### CVE-2026-41923
**WDR201A WiFi Extender (HW V2.1, FW LFMZX28040922V1.02) contains an OS command injection vulnerability in the internet.cgi binary that all...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T19:47:31.297
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-04)

> WDR201A WiFi Extender (HW V2.1, FW LFMZX28040922V1.02) contains an OS command injection vulnerability in the internet.cgi binary that allows unauthenticated remote attackers to execute arbitrary shell commands by injecting malicious input into the gateway POST parameter. Attacker…

### CVE-2026-41924
**WDR201A WiFi Extender (HW V2.1, FW LFMZX28040922V1.02) contains an OS command injection vulnerability in the makeRequest.cgi binary that...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T19:47:31.297
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-04)

> WDR201A WiFi Extender (HW V2.1, FW LFMZX28040922V1.02) contains an OS command injection vulnerability in the makeRequest.cgi binary that allows unauthenticated remote attackers to execute arbitrary shell commands by injecting malicious input into the set_time or StartSniffer func…

### CVE-2026-41925
**WDR201A WiFi Extender (HW V2.1, FW LFMZX28040922V1.02) contains an OS command injection vulnerability in the adm.cgi binary's reboot_time...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T19:47:31.297
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-04)

> WDR201A WiFi Extender (HW V2.1, FW LFMZX28040922V1.02) contains an OS command injection vulnerability in the adm.cgi binary's reboot_time function that allows unauthenticated remote attackers to execute arbitrary shell commands by injecting malicious input into the reboot_time PO…

### CVE-2026-41926
**WDR201A WiFi Extender (HW V2.1, FW LFMZX28040922V1.02) contains an OS command injection vulnerability in the firewall.cgi binary across f...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T19:47:31.297
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-04)

> WDR201A WiFi Extender (HW V2.1, FW LFMZX28040922V1.02) contains an OS command injection vulnerability in the firewall.cgi binary across five request handlers that apply insufficient input validation. Attackers can inject arbitrary shell commands through vulnerable parameters like…

### CVE-2026-42088
**openc3 cosmos**
- **Signals:** CVSS
- **Asset:** openc3 cosmos
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-13T20:47:46.973
- **CWE:** CWE-250
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-05-04)

> OpenC3 COSMOS provides the functionality needed to send commands to and receive data from one or more embedded systems. Prior to version 7.0.0-rc3, the Script Runner widget allows users to execute Python and Ruby scripts directly from the openc3-COSMOS-script-runner-api container…

### CVE-2026-42231
**n8n n8n**
- **Signals:** CVSS
- **Asset:** n8n n8n
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-06T17:14:03.970
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-04)

> n8n is an open source workflow automation platform. Prior to versions 1.123.32, 2.17.4, and 2.18.1, a flaw in the xml2js library used to parse XML request bodies in n8n's webhook handler allowed prototype pollution via a crafted XML payload. An authenticated user with permission …

### CVE-2026-42232
**n8n n8n RCE**
- **Signals:** CVSS
- **Asset:** n8n n8n
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-06T17:15:28.223
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-04)

> n8n is an open source workflow automation platform. Prior to versions 1.123.32, 2.17.4, and 2.18.1, an authenticated user with permission to create or modify workflows could achieve global prototype pollution via the XML Node leading to RCE when combined with other nodes exploiti…

### CVE-2026-42238
**nginxui nginx_ui**
- **Signals:** CVSS
- **Asset:** nginxui nginx_ui
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-06T14:45:44.013
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-05-04)

> Nginx UI is a web user interface for the Nginx web server. Prior to version 2.3.8, nginx-ui exposes a backup restore endpoint (POST /api/restore) that is completely unauthenticated during the first 10 minutes after process startup on any fresh installation. An unauthenticated rem…

### CVE-2026-42796
**workiva arelle RCE**
- **Signals:** CVSS
- **Asset:** workiva arelle
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T18:54:25.937
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-04)

> Arelle before 2.39.10 contains an unauthenticated remote code execution vulnerability in the /rest/configure REST endpoint that accepts a plugins query parameter and forwards it to the plugin manager without authentication or authorization. Attackers can supply a URL to a malicio…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-04*
