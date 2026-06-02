# Daily Threat Intelligence — July 10, 2025

**Digest window (UTC):** 2025-07-10
**Generated:** 2026-06-02T07:33:02Z

## Threat brief

Citrix NetScaler ADC And Gateway added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Citrix NetScaler ADC And Gateway added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2025-5777
**Citrix NetScaler ADC and Gateway Out-of-Bounds Read Vulnerability**
- **Signals:** KEV
- **Asset:** citrix netscaler_application_delivery_controller
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T20:10:26.470
- **CWE:** CWE-125
- **CWE:** CWE-908
- **CWE:** CWE-457
- **Risk score:** 88
- **KEV:** added 2025-07-10

> Insufficient input validation leading to memory overread when the NetScaler is configured as a Gateway (VPN virtual server, ICA Proxy, CVPN, RDP Proxy) OR AAA virtual server

### CVE-2025-47812
**Wing FTP Server Improper Neutralization of Null Byte or NUL Character Vulnerability**
- **Signals:** CVSS
- **Asset:** wftpserver wing_ftp_server
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:26:31.650
- **CWE:** CWE-158
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-10)

> In Wing FTP Server before 7.4.4. the user and admin web interfaces mishandle '\0' bytes, ultimately allowing injection of arbitrary Lua code into user session files. This can be used to execute arbitrary system commands with the privileges of the FTP service (root or SYSTEM by de…

### CVE-2025-2523
**The Honeywell Experion PKS and OneWireless WDM contains an Integer Underflow vulnerability in the component Control Data Access (CDA).**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-191
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-10)

> The Honeywell Experion PKS 

 and OneWireless WDM 

contains an Integer Underflow 

vulnerability 

in the component Control Data Access (CDA). An attacker could potentially exploit this vulnerability, leading to a Communication Channel Manipulation, which could result in a failu…

### CVE-2025-23048
**apache http_server**
- **Signals:** CVSS
- **Asset:** apache http_server
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T22:16:06.920
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-10)

> In some mod_ssl configurations on Apache HTTP Server 2.4.35 through to 2.4.63, an access control bypass by trusted clients is possible using TLS 1.3 session resumption.

Configurations are affected when mod_ssl is configured for multiple virtual hosts, with each restricted to a d…

### CVE-2025-34095
**An OS command injection vulnerability exists in Mako Server versions 2.5 and 2.6, specifically within the tutorial interface provided by...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-10)

> An OS command injection vulnerability exists in Mako Server versions 2.5 and 2.6, specifically within the tutorial interface provided by the examples/save.lsp endpoint. An unauthenticated attacker can send a crafted PUT request containing arbitrary Lua os.execute() code, which is…

### CVE-2025-34096
**A stack-based buffer overflow vulnerability exists in Easy File Sharing HTTP Server version 7.2.**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-119
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-10)

> A stack-based buffer overflow vulnerability exists in Easy File Sharing HTTP Server version 7.2. The flaw is triggered when a crafted POST request is sent to the /sendemail.ghp endpoint containing an overly long Email parameter. The application fails to properly validate the leng…

### CVE-2025-34099
**An unauthenticated command injection vulnerability exists in VICIdial versions 2.9 RC1 through 2.13 RC1, within the vicidial_sales_viewer...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-10)

> An unauthenticated command injection vulnerability exists in VICIdial versions 2.9 RC1 through 2.13 RC1, within the vicidial_sales_viewer.php component when password encryption is enabled (a non-default configuration). The application improperly passes the HTTP Basic Authenticati…

### CVE-2025-34100
**An unrestricted file upload vulnerability exists in BuilderEngine 3.5.0 via the integration of the elFinder 2.0 file manager and its use...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-10)

> An unrestricted file upload vulnerability exists in BuilderEngine 3.5.0 via the integration of the elFinder 2.0 file manager and its use of the jQuery File Upload plugin. The plugin fails to properly validate or restrict file types or locations during upload operations, allowing …

### CVE-2025-34101
**An unauthenticated command injection vulnerability exists in Serviio Media Server versions 1.4 through 1.8 on Windows, in the /rest/actio...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-10)

> An unauthenticated command injection vulnerability exists in Serviio Media Server versions 1.4 through 1.8 on Windows, in the /rest/action API endpoint exposed by the console component (default port 23423). The checkStreamUrl method accepts a VIDEO parameter that is passed unsani…

### CVE-2025-34102
**A remote code execution vulnerability exists in CryptoLog (PHP version, discontinued since 2009) due to a chained exploitation of SQL inj...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-10)

> A remote code execution vulnerability exists in CryptoLog (PHP version, discontinued since 2009) due to a chained exploitation of SQL injection and command injection vulnerabilities. An unauthenticated attacker can gain shell access as the web server user by first exploiting a SQ…

### CVE-2025-53371
**DiscordNotifications is an extension for MediaWiki that sends notifications of actions in your Wiki to a Discord channel.**
- **Signals:** CVSS
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-400
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-10)

> DiscordNotifications is an extension for MediaWiki that sends notifications of actions in your Wiki to a Discord channel. DiscordNotifications allows sending requests via curl and file_get_contents to arbitrary URLs set via $wgDiscordIncomingWebhookUrl and $wgDiscordAdditionalInc…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-10*
