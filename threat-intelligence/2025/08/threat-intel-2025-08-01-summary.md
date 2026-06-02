# Daily Threat Intelligence — August 01, 2025

**Digest window (UTC):** 2025-08-01
**Generated:** 2026-06-02T07:33:09Z

## Threat brief

Acftp — exploitation likelihood rose sharply (EPSS 27% → 40% · rising (+13%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Acftp — exploitation likelihood rose sharply (EPSS 27% → 40% · rising (+13%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2006-2242
**acftp acftp DoS**
- **Signals:** EPSS
- **Asset:** acftp acftp
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 27.3% (2025-03-30) → 40.2% (2025-08-01), Δ +12.9%**

> acFTP 1.4 allows remote attackers to cause a denial of service (application crash) via a long string with "{" (brace) characters to the USER command.

### CVE-2025-50870
**Institute-of-Current-Students 1.0 is vulnerable to Incorrect Access Control in the mydetailsstudent.php endpoint.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-01)

> Institute-of-Current-Students 1.0 is vulnerable to Incorrect Access Control in the mydetailsstudent.php endpoint. The myds GET parameter accepts an email address as input and directly returns the corresponding student's personal information without validating the identity or perm…

### CVE-2013-10060
**netgear dgn2200b_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** netgear dgn2200b_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-23T17:07:29.847
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-01)

> An authenticated OS command injection vulnerability exists in Netgear routers (tested on the DGN2200B model) firmware versions 1.0.0.36 and prior via the pppoe.cgi endpoint. A remote attacker with valid credentials can execute arbitrary commands via crafted input to the pppoe_use…

### CVE-2013-10047
**An unrestricted file upload vulnerability exists in MiniWeb HTTP Server <= Build 300 that allows unauthenticated remote attackers to uplo...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-01)

> An unrestricted file upload vulnerability exists in MiniWeb HTTP Server <= Build 300 that allows unauthenticated remote attackers to upload arbitrary files to the server’s filesystem. By abusing the upload handler and crafting a traversal path, an attacker can place a malicious .…

### CVE-2013-10048
**dlink dir-300_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** dlink dir-300_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-23T17:41:57.273
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-01)

> An OS command injection vulnerability exists in various legacy D-Link routers—including DIR-300 rev B and DIR-600 (firmware ≤ 2.13 and ≤ 2.14b01, respectively)—due to improper input handling in the unauthenticated command.php endpoint. By sending specially crafted POST requests, …

### CVE-2013-10049
**An OS command injection vulnerability exists in multiple Raidsonic NAS devices—specifically tested on IB-NAS5220 and IB-NAS4220—via the u...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-01)

> An OS command injection vulnerability exists in multiple Raidsonic NAS devices—specifically tested on IB-NAS5220 and IB-NAS4220—via the unauthenticated timeHandler.cgi endpoint exposed through the web interface. The CGI script fails to properly sanitize user-supplied input in the…

### CVE-2013-10051
**instantcms instantcms Code Execution**
- **Signals:** CVSS
- **Asset:** instantcms instantcms
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T16:50:05.700
- **CWE:** CWE-95
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-01)

> A remote PHP code execution vulnerability exists in InstantCMS version 1.6 and earlier due to unsafe use of eval() within the search view handler. Specifically, user-supplied input passed via the look parameter is concatenated into a PHP expression and executed without proper san…

### CVE-2013-10055
**An unauthenticated arbitrary file upload vulnerability exists in Havalite CMS version 1.1.7 (and possibly earlier) in the upload.php script.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-01)

> An unauthenticated arbitrary file upload vulnerability exists in Havalite CMS version 1.1.7 (and possibly earlier) in the upload.php script. The application fails to enforce proper file extension validation and authentication checks, allowing remote attackers to upload malicious …

### CVE-2025-54574
**squid-cache squid RCE**
- **Signals:** CVSS
- **Asset:** squid-cache squid
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-05T17:15:43.620
- **CWE:** CWE-122
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-01)

> Squid is a caching proxy for the Web. In versions 6.3 and below, Squid is vulnerable to a heap buffer overflow and possible remote code execution attack when processing URN due to incorrect buffer management. This has been fixed in version 6.4. To work around this issue, disable …

### CVE-2025-54792
**localsend localsend**
- **Signals:** CVSS
- **Asset:** localsend localsend
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-03T14:12:26.090
- **CWE:** CWE-300
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-01)

> LocalSend is an open-source app to securely share files and messages with nearby devices over local networks without needing an internet connection. In versions 1.16.1 and below, a critical Man-in-the-Middle (MitM) vulnerability in the software's discovery protocol allows an unau…

### CVE-2025-6000
**hashicorp vault Code Execution**
- **Signals:** CVSS
- **Asset:** hashicorp vault
- **Attack:** Code Execution
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-13T18:08:08.770
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-01)

> A privileged Vault operator within the root namespace with write permission to {{sys/audit}} may obtain code execution on the underlying host if a plugin directory is set in Vault’s configuration. Fixed in Vault Community Edition 1.20.1 and Vault Enterprise 1.20.1, 1.19.7, 1.18.1…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-01*
