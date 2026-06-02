# Daily Threat Intelligence — May 29, 2026

**Digest window (UTC):** 2026-05-29
**Generated:** 2026-06-02T07:04:08Z

## Threat brief

Palo Alto Networks PAN-OS added to CISA KEV — confirmed in-the-wild exploitation. · Wftpserver Wing Ftp Server: public exploit or PoC linked (RCE) · WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Microsoft Windows — exploitation likelihood rose sharply (EPSS 25% → 43% · rising (+18%)).

## Executive summary

- Palo Alto Networks PAN-OS added to CISA KEV — confirmed in-the-wild exploitation.
- Wftpserver Wing Ftp Server: public exploit or PoC linked (RCE)
- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Microsoft Windows — exploitation likelihood rose sharply (EPSS 25% → 43% · rising (+18%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 14 |
| EPSS rise | 7 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **32** |


## CVEs

### CVE-2026-0257
**Palo Alto Networks PAN-OS Authentication Bypass Vulnerability**
- **Signals:** KEV
- **Asset:** paloaltonetworks pan-os
- **Attack:** Auth Bypass
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-01T12:33:52.710
- **CWE:** CWE-565
- **Risk score:** 88
- **KEV:** added 2026-05-29

> Authentication bypass vulnerabilities in the GlobalProtect portal and gateway of Palo Alto Networks PAN-OS® software allows the attacker to bypass security restrictions and establish an unauthorized VPN connection.

Panorama and Cloud NGFW are not impacted by these issues.

### CVE-2026-0770
**langflow langflow RCE**
- **Signals:** EXP
- **Asset:** langflow langflow
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T16:43:44.047
- **CWE:** CWE-829
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> Langflow exec_globals Inclusion of Functionality from Untrusted Control Sphere Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of Langflow. Authentication is not required to exploit this vulnerabi…

### CVE-2019-0543
**Microsoft Windows Privilege Escalation Vulnerability**
- **Signals:** EPSS
- **Asset:** microsoft windows_10_1507
- **Attack:** Privilege Escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-14T19:21:28.287
- **CWE:** CWE-287
- **CWE:** CWE-287
- **Risk score:** 83
- **EPSS 24.5% (2026-04-07) → 42.7% (2026-05-29), Δ +18.2%**

> An elevation of privilege vulnerability exists when Windows improperly handles authentication requests, aka "Microsoft Windows Elevation of Privilege Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2019, Windows …

### CVE-2017-5930
**opensuse leap**
- **Signals:** EPSS
- **Asset:** opensuse leap
- **CVSS max:** 3.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-862
- **Risk score:** 77
- **EPSS 46.2% (2026-05-28) → 58.7% (2026-05-29), Δ +12.5%**

> The AliasHandler component in PostfixAdmin before 3.0.2 allows remote authenticated domain admins to delete protected aliases via the delete parameter to delete.php, involving a missing permission check.

### CVE-2018-11780
**apache debian_linux RCE**
- **Signals:** EPSS
- **Asset:** apache spamassassin
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:44:01.327
- **CWE:** CWE-94
- **Risk score:** 85
- **EPSS 6.8% (2026-04-03) → 18.7% (2026-05-29), Δ +11.9%**

> A potential Remote Code Execution bug exists with the PDFInfo plugin in Apache SpamAssassin before 3.4.2.

### CVE-2021-36754
**powerdns authoritative_server Out-of-Bounds Write**
- **Signals:** EPSS
- **Asset:** powerdns authoritative_server
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:14:01.510
- **CWE:** CWE-119
- **Risk score:** 80
- **EPSS 81.3% (2026-03-19) → 91.8% (2026-05-29), Δ +10.5%**

> PowerDNS Authoritative Server 4.5.0 before 4.5.1 allows anybody to crash the process by sending a specific query (QTYPE 65535) that causes an out-of-bounds exception.

### CVE-2023-2947
**open-emr openemr XSS**
- **Signals:** EPSS
- **Asset:** open-emr openemr
- **Attack:** XSS
- **CVSS max:** 4.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:59:37.553
- **CWE:** CWE-79
- **Risk score:** 78
- **EPSS 22.5% (2026-03-23) → 35.2% (2026-05-29), Δ +12.7%**

> Cross-site Scripting (XSS) - Stored in GitHub repository openemr/openemr prior to 7.0.1.

### CVE-2023-2949
**open-emr openemr XSS**
- **Signals:** EPSS
- **Asset:** open-emr openemr
- **Attack:** XSS
- **CVSS max:** 8.3
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:59:37.783
- **CWE:** CWE-79
- **Risk score:** 79
- **EPSS 71.8% (2026-04-25) → 83.4% (2026-05-29), Δ +11.6%**

> Cross-site Scripting (XSS) - Reflected in GitHub repository openemr/openemr prior to 7.0.1.

### CVE-2023-30192
**prestashop possearchproducts SQL Injection**
- **Signals:** EPSS
- **Asset:** prestashop possearchproducts
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-01-27T17:15:13.077
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 31.8% (2026-05-23) → 44.6% (2026-05-29), Δ +12.8%**

> Prestashop possearchproducts 1.7 is vulnerable to SQL Injection via PosSearch::find().

### CVE-2026-0926
**The Prodigy Commerce plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 3.3.0 via the 'para...**
- **Signals:** EXP
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-98
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> The Prodigy Commerce plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 3.3.0 via the 'parameters[template_name]' parameter. This makes it possible for unauthenticated attackers to include and read arbitrary files or execute arbitrary…

### CVE-2026-1830
**The Quick Playground plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 1.3.1.**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T18:03:42.203
- **CWE:** CWE-862
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> The Quick Playground plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 1.3.1. This is due to insufficient authorization checks on REST API endpoints that expose a sync code and allow arbitrary file uploads. This makes it possible fo…

### CVE-2026-32202
**Microsoft Windows Protection Mechanism Failure Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1607
- **CVSS max:** 4.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-26T20:00:21.270
- **CWE:** CWE-693
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> Protection mechanism failure in Windows Shell allows an unauthorized attacker to perform spoofing over a network.

### CVE-2026-34472
**zte zxhn_h188a_firmware**
- **Signals:** EXP
- **Asset:** zte zxhn_h188a_firmware
- **CVSS max:** 7.1
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T07:16:18.260
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> Unauthenticated credential disclosure in the wizard interface in ZTE ZXHN H188A V6.0.10P2_TE and V6.0.10P3N3_TE allows unauthenticated attackers on the local network to retrieve sensitive credentials from the router's web management interface, including the default administrator …

### CVE-2026-34473
**Unauthenticated DoS in ZTE H8102E, H168N, H167A, H199A, H288A, H198A, H267A, H267N, H268A, H388X, H196A, H369A, H268N, H208N, H367N, H181...**
- **Signals:** EXP
- **CVSS max:** 7.5
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-26T07:16:18.467
- **CWE:** CWE-400
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> Unauthenticated DoS in ZTE H8102E, H168N, H167A, H199A, H288A, H198A, H267A, H267N, H268A, H388X, H196A, H369A, H268N, H208N, H367N, H181A, and H196Q. A denial-of-service condition can be triggered against the router's web interface by sending an oversized application/x-www-form-…

### CVE-2026-34474
**Sensitive data exposure leading to admin/WLAN credential leak in ZTE ZXHN H298A 1.1 and H108N 2.6.**
- **Signals:** EXP
- **Attack:** Auth Bypass
- **CVSS max:** 7.5
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-26T07:16:18.630
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> Sensitive data exposure leading to admin/WLAN credential leak in ZTE ZXHN H298A 1.1 and H108N 2.6. A crafted request to the router web interface can expose sensitive device and account information. In affected builds, the response may include the administrator password and WLAN P…

### CVE-2026-42471
**Unsafe deserialization vulnerability in MixPHP Framework 2.x thru 2.2.17.**
- **Signals:** EXP
- **Attack:** Deserialization
- **CVSS max:** 8.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T19:39:58.510
- **CWE:** CWE-502
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> Unsafe deserialization vulnerability in MixPHP Framework 2.x thru 2.2.17. The sync-invoke client (Connection.php:76) calls unserialize() on data received from the server response, enabling client-side RCE if connecting to a malicious server.

### CVE-2026-43284
**linux linux_kernel**
- **Signals:** EXP
- **Asset:** linux linux_kernel
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T18:16:49.533
- **CWE:** CWE-123
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

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
- **EXP:** ref published 2026-05-29

> In the Linux kernel, the following vulnerability has been resolved:

rxrpc: Also unshare DATA/RESPONSE packets when paged frags are present

The DATA-packet handler in rxrpc_input_call_event() and the RESPONSE
handler in rxrpc_verify_response() copy the skb to a linear one before…

### CVE-2026-44376
**cross-site scripting · Exploit activity**
- **Signals:** EXP
- **Attack:** cross-site scripting
- **CVSS max:** 6.1
- **NVD status:** Deferred
- **NVD modified:** 2026-06-01T21:16:44.973
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> CubeCart is an ecommerce software solution. Prior to 6.7.0, an unauthenticated Reflected XSS vulnerability exists in the CubeCart v6.x search feature. Due to a logic flaw in classes/catalogue.class.php, user input is reflected without sanitization only when a search returns exact…

### CVE-2026-44403
**wftpserver wing_ftp_server RCE**
- **Signals:** EXP
- **Asset:** wftpserver wing_ftp_server
- **Attack:** RCE
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-14T14:50:51.863
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> Wing FTP Server before 8.1.3 contains an authenticated remote code execution vulnerability in the session serialization mechanism that allows authenticated administrators to inject arbitrary Lua code through the domain admin mydirectory field. Attackers can exploit unsafe seriali…

### CVE-2026-44649
**SillyTavern is a locally installed user interface that allows users to interact with text generation large language models, image generat...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T20:17:38.110
- **CWE:** CWE-290
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-29)

> SillyTavern is a locally installed user interface that allows users to interact with text generation large language models, image generation engines, and text-to-speech voice models. Prior to 1.18.0, SillyTavern accepts Remote-User (Authelia) and X-Authentik-Username (Authentik) …

### CVE-2026-44650
**SillyTavern is a locally installed user interface that allows users to interact with text generation large language models, image generat...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T20:17:38.110
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-29)

> SillyTavern is a locally installed user interface that allows users to interact with text generation large language models, image generation engines, and text-to-speech voice models. Prior to 1.18.0, POST /api/extensions/delete endpoint accepts extensionName: "." which bypasses s…

### CVE-2026-44680
**MikroORM is a TypeScript ORM for Node.js based on Data Mapper, Unit of Work and Identity Map patterns.**
- **Signals:** EXP
- **Attack:** SQL injection
- **CVSS max:** 7.6
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T20:24:19.650
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> MikroORM is a TypeScript ORM for Node.js based on Data Mapper, Unit of Work and Identity Map patterns. Prior to @mikro-orm/knex 6.6.14 and @mikro-orm/sql 7.0.14, MikroORM's identifier-quoting helper (Platform.quoteIdentifier and the postgres/mssql overrides) and its JSON-path emi…

### CVE-2026-45372
**yhirose cpp-httplib**
- **Signals:** CVSS
- **Asset:** yhirose cpp-httplib
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2026-06-01T19:16:51.283
- **CWE:** CWE-93
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-29)

> cpp-httplib is a C++11 single-file header-only cross platform HTTP/HTTPS library. Prior to 0.44.0, when cpp-httplib's server parses an incoming request, it applies percent-decoding to every header value except Location and Referer. The validity check (is_field_value) is run befor…

### CVE-2026-45661
**Dokploy is a free, self-hostable Platform as a Service (PaaS).**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T20:25:00.760
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-29)

> Dokploy is a free, self-hostable Platform as a Service (PaaS). In 0.26.5 and earlier, a critical path traversal vulnerability exists in Dokploy v0.26.5 that allows authenticated users to write arbitrary files to the filesystem during application deployment. When combined with Dok…

### CVE-2026-45668
**Trilium Notes is a cross-platform, hierarchical note taking application focused on building large personal knowledge bases.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-06-01T18:50:57.210
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-29)

> Trilium Notes is a cross-platform, hierarchical note taking application focused on building large personal knowledge bases. Prior to 0.102.2, a malicious ZIP archive imported with safe import enabled achieves RCE via #docName path traversal and XSS by combining a payload note (ty…

### CVE-2026-45697
**Formie is a Craft CMS plugin for creating forms.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T20:21:38.773
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-29)

> Formie is a Craft CMS plugin for creating forms. Prior to 2.2.20 and 3.1.24, unauthenticated users could submit crafted values into Hidden fields (with Default value → Custom) that were evaluated as Twig during submission handling, which could lead to serious compromise of the Cr…

### CVE-2026-46300
**linux linux_kernel**
- **Signals:** EXP
- **Asset:** linux linux_kernel
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-30T11:17:28.003
- **CWE:** CWE-787
- **Risk score:** 78
- **EXP:** ref published 2026-05-29

> In the Linux kernel, the following vulnerability has been resolved:

net: skbuff: preserve shared-frag marker during coalescing

skb_try_coalesce() can attach paged frags from @from to @to.  If @from
has SKBFL_SHARED_FRAG set, the resulting @to skb can contain the same
externally…

### CVE-2026-47744
**Shopper is a Headless e-commerce Admin Panel.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-05-29T20:17:38.110
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-29)

> Shopper is a Headless e-commerce Admin Panel. Prior to 2.8.0, two distinct authorization defects in the team settings allowed any authenticated panel user to take over the RBAC system. Settings/Team/Index had no mount() authorization. Any authenticated user could load the page an…

### CVE-2026-5386
**The affected KMW CCTV Security Cameras are vulnerable to a critical unauthenticated password reset.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-01T17:07:57.203
- **CWE:** CWE-620
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-29)

> The affected KMW CCTV Security Cameras are vulnerable to a critical unauthenticated password reset. This flaw allows an attacker to remotely reset the administrator password to a known value without authentication, granting full access to the camera feeds and settings.

### CVE-2026-7786
**Jinan USR IOT Technology Limited (PUSR) USR-W610 RS232/485 to Wi-Fi/Ethernet Converter device firmware contains plaintext administrative...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-01T17:07:57.203
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-29)

> Jinan USR IOT Technology Limited (PUSR) USR-W610 RS232/485 to Wi-Fi/Ethernet Converter
device firmware contains plaintext administrative credentials embedded in the firmware image. These credentials can be extracted through firmware analysis and used to authenticate to device ser…

### CVE-2026-9051
**There is an authentication bypass vulnerability in the NI SystemLink Enterprise Dashboard application that may allow an unauthenticated r...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.3
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-01T17:06:59.370
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-29)

> There is an authentication bypass vulnerability in the NI SystemLink Enterprise Dashboard application that may allow an unauthenticated remote attacker to bypass authentication controls leading to privilege escalation or information disclosure.  Successful exploitation requires a…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-29*
