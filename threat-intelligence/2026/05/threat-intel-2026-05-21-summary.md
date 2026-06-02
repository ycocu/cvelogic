# Daily Threat Intelligence — May 21, 2026

**Digest window (UTC):** 2026-05-21
**Generated:** 2026-06-02T07:04:05Z

## Threat brief

Trend Micro Apex One added to CISA KEV — confirmed in-the-wild exploitation. · Frangoteam Fuxa: public exploit or PoC linked (Path Traversal) · WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Exploitation likelihood rose sharply (EPSS 47% → 67% · rising (+19%)).

## Executive summary

- Trend Micro Apex One added to CISA KEV — confirmed in-the-wild exploitation.
- Frangoteam Fuxa: public exploit or PoC linked (Path Traversal)
- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Exploitation likelihood rose sharply (EPSS 47% → 67% · rising (+19%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 2 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **24** |


## CVEs

### CVE-2025-34291
**Langflow Origin Validation Error Vulnerability**
- **Signals:** KEV
- **Asset:** langflow langflow
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2026-05-21T20:16:13.520
- **CWE:** CWE-346
- **Risk score:** 88
- **KEV:** added 2026-05-21

> Langflow versions up to and including 1.6.9 contain a chained vulnerability that enables account takeover and remote code execution. An overly permissive CORS configuration (allow_origins='*' with allow_credentials=True) combined with a refresh token cookie configured as SameSite…

### CVE-2026-25895
**frangoteam fuxa Path Traversal**
- **Signals:** EXP
- **Asset:** frangoteam fuxa
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T20:32:48.753
- **CWE:** CWE-22
- **Risk score:** 78
- **EXP:** ref published 2026-05-21

> FUXA is a web-based Process Visualization (SCADA/HMI/Dashboard) software. A path traversal vulnerability in FUXA allows an unauthenticated, remote attacker to write arbitrary files to arbitrary locations on the server filesystem. This affects FUXA through version 1.2.9. This issu…

### CVE-2014-125118
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 47.2% (2026-04-10) → 66.7% (2026-05-21), Δ +19.5%**

> A command injection vulnerability exists in the eScan Web Management Console version 5.5-2. The application fails to properly sanitize the 'pass' parameter when processing login requests to login.php, allowing an authenticated attacker with a valid username to inject arbitrary co…

### CVE-2013-10032
**get-simple getsimplecms RCE**
- **Signals:** EPSS
- **Asset:** get-simple getsimplecms
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-23T23:44:07.920
- **CWE:** CWE-306
- **CWE:** CWE-434
- **Risk score:** 84
- **EPSS 60.7% (2026-04-10) → 76.2% (2026-05-21), Δ +15.5%**

> An authenticated remote code execution vulnerability exists in GetSimpleCMS version 3.2.1. The application’s upload.php endpoint allows authenticated users to upload arbitrary files without proper validation of MIME types or extensions. By uploading a .pht file containing PHP cod…

### CVE-2014-125114
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 8.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 22.8% (2026-04-10) → 42.1% (2026-05-21), Δ +19.3%**

> A stack-based buffer overflow vulnerability exists in i-Ftp version 2.20 due to improper handling of the Time attribute within Schedule.xml. By placing a specially crafted Schedule.xml file in the i-Ftp application directory, a remote attacker can trigger a buffer overflow during…

### CVE-2014-125115
**SQL Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 85
- **EPSS 65.0% (2025-12-22) → 76.8% (2026-05-21), Δ +11.8%**

> An unauthenticated SQL injection vulnerability exists in Pandora FMS version 5.0 SP2 and earlier. The mobile/index.php endpoint fails to properly sanitize user input in the loginhash_data parameter, allowing attackers to extract administrator credentials or active session tokens …

### CVE-2014-125116
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 85
- **EPSS 54.5% (2026-04-10) → 67.5% (2026-05-21), Δ +13.1%**

> A remote code execution vulnerability exists in HybridAuth versions 2.0.9 through 2.2.2 due to insecure use of the install.php installation script. The script remains accessible after deployment and fails to sanitize input before writing to the application’s config.php file. An u…

### CVE-2014-125117
**dlink dsp-w215_firmware RCE**
- **Signals:** EPSS
- **Asset:** dlink dsp-w215_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-23T18:03:59.860
- **CWE:** CWE-20
- **Risk score:** 85
- **EPSS 48.5% (2025-12-22) → 62.5% (2026-05-21), Δ +14.1%**

> A stack-based buffer overflow vulnerability in the my_cgi.cgi component of certain D-Link devices, including the DSP-W215 version 1.02, can be exploited via a specially crafted HTTP POST request to the /common/info.cgi endpoint. This flaw enables an unauthenticated attacker to ac…

### CVE-2014-125119
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 8.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 16.1% (2026-04-10) → 32.7% (2026-05-21), Δ +16.5%**

> A filename spoofing vulnerability exists in WinRAR when opening specially crafted ZIP archives. The issue arises due to inconsistencies between the Central Directory and Local File Header entries in ZIP files. When viewed in WinRAR, the file name from the Central Directory is dis…

### CVE-2015-0291
**openssl openssl DoS**
- **Signals:** EPSS
- **Asset:** openssl openssl
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 78
- **EPSS 14.6% (2026-04-21) → 28.0% (2026-05-21), Δ +13.4%**

> The sigalgs implementation in t1_lib.c in OpenSSL 1.0.2 before 1.0.2a allows remote attackers to cause a denial of service (NULL pointer dereference and daemon crash) by using an invalid signature_algorithms extension in the ClientHello message during a renegotiation.

### CVE-2016-0128
**microsoft windows_10**
- **Signals:** EPSS
- **Asset:** microsoft windows_10
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-254
- **Risk score:** 81
- **EPSS 60.3% (2026-01-11) → 77.0% (2026-05-21), Δ +16.8%**

> The SAM and LSAD protocol implementations in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, and Windows 10 Gold and 1511 do not properly establish an RPC channel, which allows man-in-th…

### CVE-2021-22122
**fortinet fortiweb cross-site scripting**
- **Signals:** EPSS
- **Asset:** fortinet fortiweb
- **Attack:** cross-site scripting
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:49:32.910
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 55.6% (2026-04-07) → 70.0% (2026-05-21), Δ +14.4%**

> An improper neutralization of input during web page generation in FortiWeb GUI interface 6.3.0 through 6.3.7 and version before 6.2.4 may allow an unauthenticated, remote attacker to perform a reflected cross site scripting attack (XSS) by injecting malicious payload in different…

### CVE-2025-71210
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-05-21T15:05:28.023
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-21)

> A vulnerability in the Trend Micro Apex One management console could allow a remote attacker to upload malicious code and execute commands on affected installations.

Please note: although this vulnerability carries a technical critical CVSS rating, this was reported via respon…

### CVE-2025-71211
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-05-21T15:05:28.023
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-21)

> A vulnerability in the Trend Micro Apex One management console could allow a remote attacker to upload malicious code and execute commands on affected installations. This vulnerability is similar in scope to CVE-2025-71210 but affects a different executable. 

Please note: alth…

### CVE-2026-34926
**Trend Micro Apex One (On-Premise) Directory Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** Trend Micro Apex One
- **Attack:** Directory Traversal
- **CVSS max:** 6.7
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-05-21T20:16:14.027
- **CWE:** CWE-23
- **Risk score:** 88
- **KEV:** added 2026-05-21

> A directory traversal vulnerability in the Apex One (on-premise) server could allow a pre-authenticated local attacker to modify a key table on the server to inject malicious code to deploy to agents on affected installations.


This vulnerability is only exploitable on the on-p…

### CVE-2026-39531
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Wp Directory Kit WP Directory Kit a...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T19:10:36.607
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-21)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Wp Directory Kit WP Directory Kit allows Blind SQL Injection.

This issue affects WP Directory Kit: from n/a through 1.5.0.

### CVE-2026-43501
**In the Linux kernel, the following vulnerability has been resolved: ipv6: rpl: reserve mac_len headroom when recompressed SRH grows ipv6_...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-01T17:17:07.350
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-21)

> In the Linux kernel, the following vulnerability has been resolved:

ipv6: rpl: reserve mac_len headroom when recompressed SRH grows

ipv6_rpl_srh_rcv() decompresses an RFC 6554 Source Routing Header, swaps
the next segment into ipv6_hdr->daddr, recompresses, then pulls the old
h…

### CVE-2026-4631
**Cockpit's remote login feature passes user-supplied hostnames and usernames from the web interface to the SSH client without validation o...**
- **Signals:** EXP
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-10T21:16:28.053
- **CWE:** CWE-78
- **Risk score:** 78
- **EXP:** ref published 2026-05-21

> Cockpit's remote login feature passes user-supplied hostnames and usernames from the web interface to the SSH client without validation or sanitization. An attacker with network access to the Cockpit web service can craft a single HTTP request to the login endpoint that injects m…

### CVE-2026-48207
**Deserialization of untrusted data in Apache Fory PyFory.**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-05-21T19:16:53.700
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-21)

> Deserialization of untrusted data in Apache Fory PyFory. PyFory's ReduceSerializer could bypass documented DeserializationPolicy validation hooks during reduce-state restoration and global-name resolution. An application is vulnerable if it deserializes attacker-controlled data u…

### CVE-2026-48241
**Open ISES Tickets before 3.44.2 contains hardcoded MySQL database credentials in loader.php (a public-facing database utility) that are c...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T19:10:12.323
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-21)

> Open ISES Tickets before 3.44.2 contains hardcoded MySQL database credentials in loader.php (a public-facing database utility) that are committed to the source repository. Any actor with access to the public source tree (or an unauthenticated attacker with read access to the file…

### CVE-2026-48242
**Open ISES Tickets before 3.44.2 contains hardcoded MySQL database connection credentials (host, username, password, database name) in imp...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T19:10:12.323
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-21)

> Open ISES Tickets before 3.44.2 contains hardcoded MySQL database connection credentials (host, username, password, database name) in import_mdb.php. The credentials are embedded in source code committed to the public repository, allowing any reader of the source to obtain valid …

### CVE-2026-5118
**The Divi Form Builder plugin for WordPress is vulnerable to privilege escalation in versions up to, and including, 5.1.2.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T15:19:30.540
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-21)

> The Divi Form Builder plugin for WordPress is vulnerable to privilege escalation in versions up to, and including, 5.1.2. This is due to the plugin accepting a user-controlled 'role' parameter from POST data during user registration without validating it against the form's config…

### CVE-2026-6960
**The BookingPress Pro plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'bookingpres...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-05-21T22:16:48.643
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-21)

> The BookingPress Pro plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'bookingpress_validate_submitted_booking_form_func' function in all versions up to, and including, 5.6. This makes it possible for unauthenticated attacker…

### CVE-2026-8134
**concretecms concrete_cms Path Traversal**
- **Signals:** CVSS
- **Asset:** concretecms concrete_cms
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-26T19:02:40.553
- **CWE:** CWE-23
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-21)

> Concrete CMS 9.5.0 and below fails to sanitize path traversal sequences in the ptComposerFormLayoutSetControlCustomTemplate field when saving page type composer form layouts. An authenticated rogue administrator with composer form editing rights can exploit this to include arbitr…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-21*
