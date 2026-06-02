# Daily Threat Intelligence — August 13, 2025

**Digest window (UTC):** 2025-08-13
**Generated:** 2026-06-02T07:33:13Z

## Threat brief

N-able N-Central: 2 CVEs added to CISA KEV today. · Ayman Akt Ircit — exploitation likelihood rose sharply (EPSS 5.4% → 26% · rising (+20%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- N-able N-Central: 2 CVEs added to CISA KEV today.
- Ayman Akt Ircit — exploitation likelihood rose sharply (EPSS 5.4% → 26% · rising (+20%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2025-8875
**N-able N-Central Insecure Deserialization Vulnerability**
- **Signals:** KEV
- **Asset:** n-able n-central
- **Attack:** Deserialization
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T14:58:50.500
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2025-08-13

> Deserialization of Untrusted Data vulnerability in N-able N-central allows Local Execution of Code.This issue affects N-central: before 2025.3.1.

### CVE-2002-1891
**ayman_akt ircit Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ayman_akt ircit
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 5.4% (2025-03-30) → 25.7% (2025-08-13), Δ +20.3%**

> Buffer overflow in IRCIT 0.3.1 IRC client allows remote attackers to execute arbitrary code via a long invite request.

### CVE-2011-10018
**mybb mybb**
- **Signals:** CVSS
- **Asset:** mybb mybb
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T17:42:18.333
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-13)

> myBB version 1.6.4 was distributed with an unauthorized backdoor embedded in the source code. The backdoor allowed remote attackers to execute arbitrary PHP code by injecting payloads into a specially crafted collapsed cookie. This vulnerability was introduced during packaging an…

### CVE-2011-10016
**Real Networks Netzip Classic version 7.5.1.86 is vulnerable to a stack-based buffer overflow when parsing a specially crafted ZIP archive.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-13)

> Real Networks Netzip Classic version 7.5.1.86 is vulnerable to a stack-based buffer overflow when parsing a specially crafted ZIP archive. The vulnerability is triggered when the application attempts to process a file name within the archive that exceeds the expected buffer size.…

### CVE-2011-10017
**Snort Report versions < 1.3.2 contains a remote command execution vulnerability in the nmap.php and nbtscan.php scripts.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-13)

> Snort Report versions < 1.3.2 contains a remote command execution vulnerability in the nmap.php and nbtscan.php scripts. These scripts fail to properly sanitize user input passed via the target GET parameter, allowing attackers to inject arbitrary shell commands. Exploitation req…

### CVE-2011-10019
**spreecommerce spree**
- **Signals:** CVSS
- **Asset:** spreecommerce spree
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-24T00:31:10.940
- **CWE:** CWE-94
- **CWE:** CWE-1321
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-13)

> Spreecommerce versions prior to 0.60.2 contains a remote command execution vulnerability in its search functionality. The application fails to properly sanitize input passed via the search[send][] parameter, which is dynamically invoked using Ruby’s send method. This allows attac…

### CVE-2012-10054
**umbraco umbraco_cms RCE**
- **Signals:** CVSS
- **Asset:** umbraco umbraco_cms
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-19T17:02:51.163
- **CWE:** CWE-22
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-13)

> Umbraco CMS versions prior to 4.7.1 are vulnerable to unauthenticated remote code execution via the codeEditorSave.asmx SOAP endpoint, which exposes a SaveDLRScript operation that permits arbitrary file uploads without authentication. By exploiting a path traversal flaw in the fi…

### CVE-2012-10055
**ComSndFTP FTP Server version 1.3.7 Beta contains a format string vulnerability in its handling of the USER command.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-134
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-13)

> ComSndFTP FTP Server version 1.3.7 Beta contains a format string vulnerability in its handling of the USER command. By sending a specially crafted username containing format specifiers, a remote attacker can overwrite a hardcoded function pointer in memory (specifically WSACleanu…

### CVE-2012-10058
**RabidHamster R4 v1.25 contains a stack-based buffer overflow vulnerability due to unsafe use of sprintf() when logging malformed HTTP req...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-13)

> RabidHamster R4 v1.25 contains a stack-based buffer overflow vulnerability due to unsafe use of sprintf() when logging malformed HTTP requests. A remote attacker can exploit this flaw by sending a specially crafted URI, resulting in arbitrary code execution under the context of t…

### CVE-2012-10059
**Dolibarr ERP/CRM versions <= 3.1.1 and <= 3.2.0 contain a post-authenticated OS command injection vulnerability in its database backup fe...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-13)

> Dolibarr ERP/CRM versions <= 3.1.1 and <= 3.2.0 contain a post-authenticated OS command injection vulnerability in its database backup feature. The export.php script fails to sanitize the sql_compat parameter, allowing authenticated users to inject arbitrary system commands, resu…

### CVE-2012-10060
**sysax multi_server RCE**
- **Signals:** CVSS
- **Asset:** sysax multi_server
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T14:16:22.100
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-13)

> Sysax Multi Server versions prior to 5.55 contain a stack-based buffer overflow in its SSH service. When a remote attacker supplies an overly long username during authentication, the server copies the input to a fixed-size stack buffer without proper bounds checking. This allows …

### CVE-2022-28033
**thedigitalcraft atomcms SQL Injection**
- **Signals:** EPSS
- **Asset:** thedigitalcraft atomcms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:56:39.290
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 39.1% (2025-04-30) → 58.4% (2025-08-13), Δ +19.3%**

> Atom.CMS 2.0 is vulnerable to SQL Injection via Atom.CMS_admin_uploads.php

### CVE-2025-34154
**UnForm Server Manager versions prior to 10.1.12 expose an unauthenticated file read vulnerability via its log file analysis interface.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-08-13)

> UnForm Server Manager versions prior to 10.1.12 expose an unauthenticated file read vulnerability via its log file analysis interface. The flaw resides in the arc endpoint, which accepts a fl parameter to specify the log file to be opened. Due to insufficient input validation and…

### CVE-2025-8876
**N-able N-Central Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** n-able n-central
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T14:58:04.440
- **CWE:** CWE-20
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2025-08-13

> Improper Input Validation vulnerability in N-able N-central allows OS Command Injection.This issue affects N-central: before 2025.3.1.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-13*
