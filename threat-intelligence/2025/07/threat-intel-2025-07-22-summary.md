# Daily Threat Intelligence — July 22, 2025

**Digest window (UTC):** 2025-07-22
**Generated:** 2026-06-02T07:33:06Z

## Threat brief

Microsoft SharePoint: 2 CVEs added to CISA KEV today. · Livehelperchat Live Helper Chat: public exploit or PoC linked (XSS) · WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft SharePoint: 2 CVEs added to CISA KEV today.
- Livehelperchat Live Helper Chat: public exploit or PoC linked (XSS)
- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 6 |
| EXP (exploit / PoC) | 12 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **28** |


## CVEs

### CVE-2025-2775
**SysAid On-Prem Improper Restriction of XML External Entity Reference Vulnerability**
- **Signals:** KEV
- **Asset:** sysaid sysaid
- **Attack:** XXE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T16:58:55.380
- **CWE:** CWE-611
- **Risk score:** 88
- **KEV:** added 2025-07-22

> SysAid On-Prem versions <= 23.3.40 are vulnerable to an unauthenticated XML External Entity (XXE) vulnerability in the Checkin processing functionality,  allowing for administrator account takeover and file read primitives.

### CVE-2015-6176
**microsoft edge XSS**
- **Signals:** EXP
- **Asset:** microsoft edge
- **Attack:** XSS
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> Microsoft Edge mishandles HTML attributes in HTTP responses, which allows remote attackers to bypass a cross-site scripting (XSS) protection mechanism via unspecified vectors, aka "Microsoft Edge XSS Filter Bypass Vulnerability."

### CVE-2025-4285
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Rolantis Information Technologies A...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-22)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Rolantis Information Technologies Agentis allows SQL Injection.This issue affects Agentis: before 4.32.

### CVE-2020-36847
**simplefilelist simple_file_list RCE**
- **Signals:** EXP
- **Asset:** simplefilelist simple_file_list
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-29T20:37:27.933
- **CWE:** CWE-434
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> The Simple-File-List Plugin for WordPress is vulnerable to Remote Code Execution in versions up to, and including, 4.2.2 via the rename function which can be used to rename uploaded PHP code with a png extension to use a php extension. This allows unauthenticated attackers to exe…

### CVE-2023-45131
**discourse discourse**
- **Signals:** EXP
- **Asset:** discourse discourse
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:26:24.310
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> Discourse is an open source platform for community discussion. New chat messages can be read by making an unauthenticated POST request to MessageBus. This issue is patched in the 3.1.1 stable and 3.2.0.beta2 versions of Discourse. Users are advised to upgrade. There are no known …

### CVE-2025-2776
**SysAid On-Prem Improper Restriction of XML External Entity Reference Vulnerability**
- **Signals:** KEV
- **Asset:** sysaid sysaid
- **Attack:** XXE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T16:58:51.230
- **CWE:** CWE-611
- **Risk score:** 88
- **KEV:** added 2025-07-22

> SysAid On-Prem versions <= 23.3.40 are vulnerable to an unauthenticated XML External Entity (XXE) vulnerability in the Server URL processing functionality, allowing for administrator account takeover and file read primitives.

### CVE-2025-34077
**An authentication bypass vulnerability exists in the WordPress Pie Register plugin ≤ 3.7.1.4 that allows unauthenticated attackers to imp...**
- **Signals:** EXP
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> An authentication bypass vulnerability exists in the WordPress Pie Register plugin ≤ 3.7.1.4 that allows unauthenticated attackers to impersonate arbitrary users by submitting a crafted POST request to the login endpoint. By setting social_site=true and manipulating the user_id_s…

### CVE-2025-34143
**An authentication bypass vulnerability exists in ETQ Reliance on the CG (legacy) platform.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-22)

> An authentication bypass vulnerability exists in ETQ Reliance on the CG (legacy) platform. The application allowed login as the privileged internal SYSTEM user by manipulating the username field. The SYSTEM account does not require a password, enabling attackers with network acce…

### CVE-2025-49484
**A SQL injection vulnerability in the JS Jobs plugin versions 1.0.0-1.4.1 for Joomla allows low-privilege users to execute arbitrary SQL c...**
- **Signals:** EXP
- **Attack:** SQL Injection
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> A SQL injection vulnerability in the JS Jobs plugin versions 1.0.0-1.4.1 for Joomla allows low-privilege users to execute arbitrary SQL commands via the 'cvid' parameter in the employee application feature.

### CVE-2025-49704
**Microsoft SharePoint Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft sharepoint_server
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:12:33.713
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2025-07-22

> Improper control of generation of code ('code injection') in Microsoft Office SharePoint allows an authorized attacker to execute code over a network.

### CVE-2025-49706
**Microsoft SharePoint Improper Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft sharepoint_enterprise_server
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:12:29.023
- **CWE:** CWE-287
- **Risk score:** 88
- **KEV:** added 2025-07-22

> Improper authentication in Microsoft Office SharePoint allows an unauthorized attacker to perform spoofing over a network.

### CVE-2025-51396
**livehelperchat live_helper_chat XSS**
- **Signals:** EXP
- **Asset:** livehelperchat live_helper_chat
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-07T01:22:52.133
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> A stored cross-site scripting (XSS) vulnerability in Live Helper Chat v4.60 allows attackers to execute arbitrary web scripts or HTML via injecting a crafted payload into the Telegram Bot Username parameter.

### CVE-2025-51397
**livehelperchat live_helper_chat XSS**
- **Signals:** EXP
- **Asset:** livehelperchat live_helper_chat
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-07T01:23:37.413
- **CWE:** CWE-779
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> A stored cross-site scripting (XSS) vulnerability in the Facebook Chat module of Live Helper Chat v4.60 allows attackers to execute arbitrary web scripts or HTML via injecting a crafted payload into the Surname parameter under the Recipient' Lists.

### CVE-2025-51398
**livehelperchat live_helper_chat XSS**
- **Signals:** EXP
- **Asset:** livehelperchat live_helper_chat
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-07T01:30:15.550
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> A stored cross-site scripting (XSS) vulnerability in the Facebook registration page of Live Helper Chat v4.60 allows attackers to execute arbitrary web scripts or HTML via injecting a crafted payload into the Name parameter.

### CVE-2025-51400
**livehelperchat live_helper_chat XSS**
- **Signals:** EXP
- **Asset:** livehelperchat live_helper_chat
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-07T01:24:26.887
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> A stored cross-site scripting (XSS) vulnerability in the Personal Canned Messages of Live Helper Chat v4.60 allows attackers to execute arbitrary web scripts or HTML via injecting a crafted payload.

### CVE-2025-51401
**livehelperchat live_helper_chat XSS**
- **Signals:** EXP
- **Asset:** livehelperchat live_helper_chat
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-07T01:25:50.840
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> A stored cross-site scripting (XSS) vulnerability in the chat transfer function of Live Helper Chat v4.60 allows attackers to execute arbitrary web scripts or HTML via injecting a crafted payload into the operator name parameter.

### CVE-2025-51403
**livehelperchat live_helper_chat XSS**
- **Signals:** EXP
- **Asset:** livehelperchat live_helper_chat
- **Attack:** XSS
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-07T01:27:28.777
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> A stored cross-site scripting (XSS) vulnerability in the department assignment editing module of of Live Helper Chat v4.60 allows attackers to execute arbitrary web scripts or HTML via injecting a crafted payload into the Alias Nick parameter.

### CVE-2025-54309
**CrushFTP Unprotected Alternate Channel Vulnerability**
- **Signals:** KEV
- **Asset:** crushftp crushftp
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:25:42.887
- **CWE:** CWE-420
- **Risk score:** 88
- **KEV:** added 2025-07-22

> CrushFTP 10 before 10.8.5 and 11 before 11.3.4_23, when the DMZ proxy feature is not used, mishandles AS2 validation and consequently allows remote attackers to obtain admin access via HTTPS, as exploited in the wild in July 2025.

### CVE-2025-6187
**The bSecure plugin for WordPress is vulnerable to Privilege Escalation due to missing authorization within its order_info REST endpoint i...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-22)

> The bSecure plugin for WordPress is vulnerable to Privilege Escalation due to missing authorization within its order_info REST endpoint in versions 1.3.7 through 1.7.9. The plugin registers the /webhook/v2/order_info/ route with a permission_callback that always returns true, eff…

### CVE-2025-6523
**devolutions devolutions_server**
- **Signals:** CVSS
- **Asset:** devolutions devolutions_server
- **CVSS max:** 9.5
- **NVD status:** Modified
- **NVD modified:** 2025-11-25T18:15:54.433
- **CWE:** CWE-1391
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-07-22)

> Use of weak credentials in emergency authentication component in Devolutions Server allows an unauthenticated attacker to bypass authentication via brute forcing the short emergency codes generated by the server within a feasible timeframe.

This issue affects the following versi…

### CVE-2025-6558
**Google Chromium ANGLE and GPU Improper Input Validation Vulnerability**
- **Signals:** KEV
- **Asset:** google chrome
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T14:52:01.530
- **CWE:** CWE-20
- **Risk score:** 88
- **KEV:** added 2025-07-22

> Insufficient validation of untrusted input in ANGLE and GPU in Google Chrome prior to 138.0.7204.157 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: High)

### CVE-2025-7795
**tenda fh451_firmware Buffer Overflow**
- **Signals:** EXP
- **Asset:** tenda fh451_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-23T16:39:28.133
- **CWE:** CWE-119
- **Risk score:** 78
- **EXP:** ref published 2025-07-22

> A vulnerability, which was classified as critical, has been found in Tenda FH451 1.0.0.9. Affected by this issue is the function fromP2pListFilter of the file /goform/P2pListFilter. The manipulation of the argument page leads to stack-based buffer overflow. The attack may be laun…

### CVE-2025-8028
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:08.743
- **CWE:** CWE-1332
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-22)

> On arm64, a WASM `br_table` instruction with a lot of entries could lead to the label being too far from the instruction causing truncation and incorrect computation of the branch address. This vulnerability was fixed in Firefox 141, Firefox ESR 115.26, Firefox ESR 128.13, Firefo…

### CVE-2025-8031
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:09.433
- **CWE:** CWE-276
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-22)

> The `username:password` part was not correctly stripped from URLs in CSP reports potentially leaking HTTP Basic Authentication credentials. This vulnerability was fixed in Firefox 141, Firefox ESR 128.13, Firefox ESR 140.1, Thunderbird 141, Thunderbird 128.13, and Thunderbird 140…

### CVE-2025-8037
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:10.840
- **CWE:** CWE-614
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-22)

> Setting a nameless cookie with an equals sign in the value shadowed other cookies. Even if the nameless cookie was set over HTTP and the shadowed cookie included the `Secure` attribute. This vulnerability was fixed in Firefox 141, Firefox ESR 140.1, Thunderbird 141, and Thunderbi…

### CVE-2025-8038
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:11.023
- **CWE:** CWE-345
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-22)

> Thunderbird ignored paths when checking the validity of navigations in a frame. This vulnerability was fixed in Firefox 141, Firefox ESR 140.1, Thunderbird 141, and Thunderbird 140.1.

### CVE-2025-8043
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:12.743
- **CWE:** CWE-451
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-22)

> Focus incorrectly truncated URLs towards the beginning instead of around the origin. This vulnerability was fixed in Firefox 141.

### CVE-2025-8044
**mozilla firefox Memory Corruption**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:17:12.973
- **CWE:** CWE-119
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-22)

> Memory safety bugs present in Firefox 140 and Thunderbird 140. Some of these bugs showed evidence of memory corruption and we presume that with enough effort some of these could have been exploited to run arbitrary code. This vulnerability was fixed in Firefox 141 and Thunderbird…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-22*
