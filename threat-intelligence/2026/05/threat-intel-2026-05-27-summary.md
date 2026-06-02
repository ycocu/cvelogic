# Daily Threat Intelligence — May 27, 2026

**Digest window (UTC):** 2026-05-27
**Generated:** 2026-06-02T07:04:08Z

## Threat brief

Nx Console added to CISA KEV — confirmed in-the-wild exploitation. · Casbin Casdoor: public exploit or PoC linked (Path Traversal) · Apereo Xerte Online Toolkits — exploitation likelihood rose sharply (EPSS 0.6% → 70% · rising (+69%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Nx Console added to CISA KEV — confirmed in-the-wild exploitation.
- Casbin Casdoor: public exploit or PoC linked (Path Traversal)
- Apereo Xerte Online Toolkits — exploitation likelihood rose sharply (EPSS 0.6% → 70% · rising (+69%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 3 |
| EXP (exploit / PoC) | 7 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **30** |


## CVEs

### CVE-2026-45321
**TanStack Unspecified Vulnerability**
- **Signals:** KEV
- **Asset:** tanstack tanstack\/arktype-adapter
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-29T19:41:37.437
- **CWE:** CWE-506
- **Risk score:** 88
- **KEV:** added 2026-05-27

> On 2026-05-11, between approximately 19:20 and 19:26 UTC, 84 malicious versions across 42 @tanstack/* packages were published to the npm registry. The publishes were authenticated via the legitimate GitHub Actions OIDC trusted-publisher binding for TanStack/router, but the publis…

### CVE-2026-33534
**espocrm espocrm SSRF**
- **Signals:** EXP
- **Asset:** espocrm espocrm
- **Attack:** SSRF
- **CVSS max:** 4.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T00:12:27.860
- **CWE:** CWE-918
- **Risk score:** 78
- **EXP:** ref published 2026-05-27

> EspoCRM is an open source customer relationship management application. Versions 9.3.3 and below have an authenticated Server-Side Request Forgery (SSRF) vulnerability that allows bypassing the internal-host validation logic by using alternative IPv4 representations such as octal…

### CVE-2026-32985
**apereo xerte_online_toolkits**
- **Signals:** EPSS
- **Asset:** apereo xerte_online_toolkits
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-16T13:42:46.293
- **CWE:** CWE-306
- **CWE:** CWE-434
- **Risk score:** 85
- **EPSS 0.6% (2026-05-14) → 70.0% (2026-05-27), Δ +69.4%**

> Xerte Online Toolkits versions 3.14 and earlier contain an unauthenticated arbitrary file upload vulnerability in the template import functionality that allows remote attackers to execute arbitrary code by uploading a crafted ZIP archive containing malicious PHP payloads. Attacke…

### CVE-2012-2576
**solarwinds backup_profiler SQL Injection**
- **Signals:** EPSS
- **Asset:** solarwinds backup_profiler
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 41.1% (2026-01-15) → 66.8% (2026-05-27), Δ +25.7%**

> SQL injection vulnerability in the LoginServlet page in SolarWinds Storage Manager before 5.1.2, SolarWinds Storage Profiler before 5.1.2, and SolarWinds Backup Profiler before 5.1.2 allows remote attackers to execute arbitrary SQL commands via the loginName field.

### CVE-2013-10035
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 84
- **EPSS 41.9% (2026-04-16) → 62.3% (2026-05-27), Δ +20.4%**

> A code injection vulnerability exists in ProcessMaker Open Source versions 2.x when using the default 'neoclassic' skin. An authenticated user can execute arbitrary PHP code via multiple endpoints, including appFolderAjax.php, casesStartPage_Ajax.php, and cases_SchedulerGetPlugin…

### CVE-2014-125122
**Buffer Overflow · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Buffer Overflow
- **CVSS max:** 5.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 79
- **EPSS 31.8% (2025-12-27) → 51.7% (2026-05-27), Δ +19.9%**

> A stack-based buffer overflow vulnerability exists in the tmUnblock.cgi endpoint of the Linksys WRT120N wireless router. The vulnerability is triggered by sending a specially crafted HTTP POST request with an overly long TM_Block_URL parameter to the endpoint. By exploiting this …

### CVE-2014-125123
**SQL Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 34.1% (2026-04-16) → 60.0% (2026-05-27), Δ +25.9%**

> An unauthenticated SQL injection vulnerability exists in the Kloxo web hosting control panel (developed by LXCenter) prior to version 6.1.12. The flaw resides in the login-name parameter passed to lbin/webcommand.php, which fails to properly sanitize input, allowing an attacker t…

### CVE-2015-10144
**i13websolution thumbnail_carousel_slider RCE**
- **Signals:** EPSS
- **Asset:** i13websolution thumbnail_carousel_slider
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T14:57:31.360
- **CWE:** CWE-434
- **Risk score:** 84
- **EPSS 2.0% (2026-05-21) → 70.6% (2026-05-27), Δ +68.5%**

> The Responsive Thumbnail Slider plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type sanitization in the via the image uploader in versions up to 1.0.1. This makes it possible for authenticated attackers, with subscriber-level access and above, to…

### CVE-2019-19699
**centreon centreon RCE**
- **Signals:** EPSS
- **Asset:** centreon centreon
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:35:13.133
- **CWE:** CWE-269
- **Risk score:** 82
- **EPSS 8.9% (2025-11-21) → 38.9% (2026-05-27), Δ +30.0%**

> There is Authenticated remote code execution in Centreon Infrastructure Monitoring Software through 19.10 via Pollers misconfiguration, leading to system compromise via apache crontab misconfiguration, This allows the apache user to modify an executable file executed by root at 2…

### CVE-2020-24899
**nagios nagios_xi RCE**
- **Signals:** EPSS
- **Asset:** nagios nagios_xi
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:16:10.727
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 4.5% (2026-02-17) → 26.1% (2026-05-27), Δ +21.6%**

> Nagios XI 5.7.2 is affected by a remote code execution (RCE) vulnerability. An authenticated user can inject additional commands into normal webapp query.

### CVE-2023-28459
**pretalx pretalx Path Traversal**
- **Signals:** EPSS
- **Asset:** pretalx pretalx
- **Attack:** Path Traversal
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2025-02-05T17:15:19.507
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 81
- **EPSS 0.3% (2026-05-05) → 62.9% (2026-05-27), Δ +62.6%**

> pretalx 2.3.1 before 2.3.2 allows path traversal in HTML export (a non-default feature). Users were able to upload crafted HTML documents that trigger the reading of arbitrary files.

### CVE-2025-54068
**Laravel Livewire Code Injection Vulnerability**
- **Signals:** EPSS
- **Asset:** laravel livewire
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-20T18:36:12.533
- **CWE:** CWE-94
- **Risk score:** 85
- **EPSS 34.3% (2026-05-26) → 58.9% (2026-05-27), Δ +24.5%**

> Livewire is a full-stack framework for Laravel. In Livewire v3 up to and including v3.6.3, a vulnerability allows unauthenticated attackers to achieve remote command execution in specific scenarios. The issue stems from how certain component property updates are hydrated. This vu…

### CVE-2026-36355
**The rtl8192cd Wi-Fi kernel driver in the Realtek rtl819x Jungle SDK (all known versions through v3.4.14B) does not perform any access con...**
- **Signals:** EXP
- **CVSS max:** 7.7
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-07T15:53:49.717
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2026-05-27

> The rtl8192cd Wi-Fi kernel driver in the Realtek rtl819x Jungle SDK (all known versions through v3.4.14B) does not perform any access control checks on the write_mem (ioctl 0x89F5) and read_mem (ioctl 0x89F6) debug handlers, which are compiled into production builds via the uncon…

### CVE-2026-36356
**The GoAhead web server on MeiG Smart FORGE_SLT711 devices (firmware MDM9607.LE.1.0-00110-STD.PROD-1) allows unauthenticated OS command in...**
- **Signals:** EXP
- **Attack:** Command Injection
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-07T15:53:49.717
- **CWE:** CWE-78
- **Risk score:** 78
- **EXP:** ref published 2026-05-27

> The GoAhead web server on MeiG Smart FORGE_SLT711 devices (firmware MDM9607.LE.1.0-00110-STD.PROD-1) allows unauthenticated OS command injection via the /action/SetRemoteAccessCfg endpoint.

### CVE-2026-43284
**linux linux_kernel**
- **Signals:** EXP
- **Asset:** linux linux_kernel
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T18:16:49.533
- **CWE:** CWE-123
- **Risk score:** 78
- **EXP:** ref published 2026-05-27

> In the Linux kernel, the following vulnerability has been resolved:

xfrm: esp: avoid in-place decrypt on shared skb frags

MSG_SPLICE_PAGES can attach pages from a pipe directly to an skb. TCP
marks such skbs with SKBFL_SHARED_FRAG after skb_splice_from_iter(),
so later paths th…

### CVE-2026-43500
**linux linux_kernel**
- **Signals:** EXP
- **Asset:** linux linux_kernel
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-17T16:16:16.740
- **CWE:** CWE-787
- **CWE:** CWE-787
- **Risk score:** 78
- **EXP:** ref published 2026-05-27

> In the Linux kernel, the following vulnerability has been resolved:

rxrpc: Also unshare DATA/RESPONSE packets when paged frags are present

The DATA-packet handler in rxrpc_input_call_event() and the RESPONSE
handler in rxrpc_verify_response() copy the skb to a linear one before…

### CVE-2026-44262
**Scramble generates API documentation for Laravel project.**
- **Signals:** EXP
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T16:10:57.817
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2026-05-27

> Scramble generates API documentation for Laravel project. From 0.13.2 to before 0.13.22, when documentation endpoints are publicly accessible and validation rules reference user-controlled input, request supplied data may be evaluated during documentation generation, leading to e…

### CVE-2026-44590
**Sherlock hunts down social media accounts by username across social networks.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T16:32:14.400
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-27)

> Sherlock hunts down social media accounts by username across social networks. Prior to 0.16.1, the GitHub Actions workflow validate_modified_targets.yml is vulnerable to command injection via the pull_request_target trigger. Any GitHub user can execute arbitrary commands on the C…

### CVE-2026-44887
**Pi.Alert is a WIFI / LAN intruder detector with web service monitoring.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T15:29:42.387
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-27)

> Pi.Alert is a WIFI / LAN intruder detector with web service monitoring. Prior to 2026-05-07, Pi.Alert's web-based configuration editor allows arbitrary Python code to be injected into pialert.conf. Since the background scan daemon loads this file via Python's exec(), injected cod…

### CVE-2026-44888
**Pi.Alert is a WIFI / LAN intruder detector with web service monitoring.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T15:29:42.387
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-27)

> Pi.Alert is a WIFI / LAN intruder detector with web service monitoring. Prior to 2026-05-07, Pi.Alert's SaveConfigFile() endpoint writes user-supplied numeric config values (e.g., SMTP_PORT) directly into
pialert.conf without validation. Since pialert.conf is loaded via Python's …

### CVE-2026-45083
**The Goobi viewer is a web application that allows digitised material to be displayed in a web browser.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T15:29:42.387
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-27)

> The Goobi viewer is a web application that allows digitised material to be displayed in a web browser. From 4.8.0 to before 26.04.1, the Goobi viewer REST endpoint POST /api/v1/index/stream accepted an arbitrary Solr streaming expression from unauthenticated network clients and f…

### CVE-2026-45102
**OneUptime is an open-source monitoring and observability platform.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-06-01T18:50:57.210
- **CWE:** CWE-693
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-27)

> OneUptime is an open-source monitoring and observability platform. Prior to 10.0.98, OneUptime uses the Node.js' vm module as an isolation primitive. This API was not designed for that and can be escaped via error objects and infinite recursion. This vulnerability is fixed in 10.…

### CVE-2026-48027
**Nx Console Embedded Malicious Code Vulnerability**
- **Signals:** KEV
- **Asset:** nx nx_console
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T20:34:24.850
- **CWE:** CWE-506
- **Risk score:** 88
- **KEV:** added 2026-05-27

> Nx Console is the user interface for Nx & Lerna. On 19 May 2026, a malicious version of Nx Console, 18.95.0, was published at 12:30 PM UTC and removed soon after at 12:48 PM UTC, leaving it available for ~18 minutes in Visual Studio Marketplace. For OpenVSX, the problem was detec…

### CVE-2026-48150
**Budibase is an open-source low-code platform.**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-27T19:44:35.987
- **CWE:** CWE-915
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-05-27)

> Budibase is an open-source low-code platform. Prior to 3.39.0, /api/public/v1/roles/assign is guarded by the builderOrAdmin middleware, which passes any user who is a builder for the app id in the x-budibase-app-id header. That check admits both global builders and workspace-scop…

### CVE-2026-6815
**casbin casdoor Path Traversal**
- **Signals:** EXP
- **Asset:** casbin casdoor
- **Attack:** Path Traversal
- **CVSS max:** 5.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-01T16:38:43.600
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2026-05-27

> An arbitrary file write vulnerability exists in Casdoor's Local File System storage provider. Due to insufficient path sanitization, an authenticated attacker with administrative privileges can perform a Path Traversal attack to create or overwrite arbitrary files anywhere on the…

### CVE-2026-8362
**A stack-based buffer overflow condition exists in WOSDefaultHttpModule.dll when processing a long URL path starting with /woshome**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T20:26:29.583
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-27)

> A stack-based buffer overflow condition exists in WOSDefaultHttpModule.dll when processing a long URL path starting with /woshome

### CVE-2026-8363
**A stack-based buffer overflow condition exists in WOSDeviceDropFolder.dll when processing a long URL path starting with /resources:**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T20:26:29.583
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-27)

> A stack-based buffer overflow condition exists in WOSDeviceDropFolder.dll when processing a long URL path starting with /resources:

### CVE-2026-8364
**Gladinet Triofox Cloud Server Agent Access Service (GladServerAgentService.exe) listens on TCP port 7878 and processes remote HTTP messag...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T20:26:29.583
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-27)

> Gladinet Triofox Cloud Server Agent Access Service (GladServerAgentService.exe) listens on TCP port 7878 and processes remote HTTP messages with URL paths starting with /resources, /status, /sysinfo, /woshome, /Settings, /schedule, or /DavCache.

### CVE-2026-8398
**Daemon Tools Lite Embedded Malicious Code Vulnerability**
- **Signals:** KEV
- **Asset:** disc-soft daemon_tools
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-28T12:57:00.563
- **CWE:** CWE-506
- **Risk score:** 88
- **KEV:** added 2026-05-27

> A supply chain attack compromised the official installation packages of DAEMON Tools Lite (Windows versions 12.5.0.2421 through 12.5.0.2434), distributed from the legitimate website daemon-tools.cc between approximately April 8, 2026, and May 5, 2026. Attackers gained unauthorize…

### CVE-2026-9739
**Vulnerable to DNS rebinding attacks when using SSE (http://b/499408790).**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-29T15:42:56.873
- **CWE:** CWE-942
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-27)

> Vulnerable to DNS rebinding attacks when using SSE (http://b/499408790). During the beta phase, we implemented `allowed-origins` and `allowed-hosts` flags to align with MCP security guidelines. However, the hardcoded `Access-Control-Allow-Origin: *` header in the SSE initializati…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-27*
