# Daily Threat Intelligence — June 12, 2026

**Digest window (UTC):** 2026-06-12
**Generated:** 2026-06-15T14:09:47Z

## Threat brief

Oracle PeopleSoft Enterprise PeopleTools added to CISA KEV — confirmed in-the-wild exploitation. · Paperclipai — exploitation likelihood rose sharply (EPSS 0.8% → 66% · rising (+66%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Oracle PeopleSoft Enterprise PeopleTools added to CISA KEV — confirmed in-the-wild exploitation.
- Paperclipai — exploitation likelihood rose sharply (EPSS 0.8% → 66% · rising (+66%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **21** |


## CVEs

### CVE-2026-35273
**Oracle PeopleSoft Enterprise PeopleTools Missing Authentication for Critical Function Vulnerability**
- **Signals:** KEV
- **Asset:** oracle peoplesoft_enterprise_peopletools
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-12T19:15:27.297
- **CWE:** CWE-306
- **Risk score:** 88
- **KEV:** added 2026-06-12

> Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Updates Environment Management). Supported versions that are affected are 8.61 and 8.62. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP t…

### CVE-2026-41679
**paperclip paperclipai RCE**
- **Signals:** EPSS
- **Asset:** paperclip paperclipai
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T14:58:34.110
- **CWE:** CWE-287
- **Risk score:** 86
- **EPSS 0.8% (2026-06-04) → 66.4% (2026-06-12), Δ +65.6%**

> Paperclip is a Node.js server and React UI that orchestrates a team of AI agents to run a business. Prior to version 2026.416.0, an unauthenticated attacker can achieve full remote code execution on any network-accessible Paperclip instance running in `authenticated` mode with de…

### CVE-2026-50086
**The Aqara IAM/SSO gateway (gw-builder.aqara.com) exposes bidirectional AES round-trups against the platform's signing key without authent...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-12T17:16:25.547
- **CWE:** CWE-327
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-12)

> The Aqara IAM/SSO gateway (gw-builder.aqara.com) exposes bidirectional AES round-trups against the platform's signing key without authentication. This is an instance of "CWE-306: Missing Authentication for Critical Function" and "CWE-327: Use of a Broken or Risky Cryptographic Al…

### CVE-2015-7767
**konicaminolta ftp_utility Buffer Overflow**
- **Signals:** EPSS
- **Asset:** konicaminolta ftp_utility
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 81
- **EPSS 5.8% (2025-09-30) → 17.2% (2026-06-12), Δ +11.4%**

> Buffer overflow in Konica Minolta FTP Utility 1.0 allows remote attackers to execute arbitrary code or cause a denial of service (application crash) via a long USER command.

### CVE-2020-0665
**microsoft windows_10 privilege escalation**
- **Signals:** EPSS
- **Asset:** microsoft windows_10
- **Attack:** privilege escalation
- **CVSS max:** 8.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:53:57.460
- **Risk score:** 83
- **EPSS 16.8% (2026-05-25) → 30.3% (2026-06-12), Δ +13.5%**

> An elevation of privilege vulnerability exists in Active Directory Forest trusts due to a default setting that lets an attacker in the trusting forest request delegation of a TGT for an identity from the trusted forest, aka 'Active Directory Elevation of Privilege Vulnerability'.

### CVE-2022-40743
**apache traffic_server cross-site scripting**
- **Signals:** EPSS
- **Asset:** apache traffic_server
- **Attack:** cross-site scripting
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2025-04-17T15:15:47.180
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EPSS 8.2% (2026-06-11) → 19.3% (2026-06-12), Δ +11.1%**

> Improper Input Validation vulnerability for the xdebug plugin in Apache Software Foundation Apache Traffic Server can lead to cross site scripting and cache poisoning attacks.This issue affects Apache Traffic Server: 9.0.0 to 9.1.3. Users should upgrade to 9.1.4 or later versions…

### CVE-2022-42118
**liferay digital_experience_platform XSS**
- **Signals:** EPSS
- **Asset:** liferay liferay_portal
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2025-05-13T18:17:51.450
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 32.4% (2026-06-11) → 52.3% (2026-06-12), Δ +19.8%**

> A Cross-site scripting (XSS) vulnerability in the Portal Search module in Liferay Portal 7.1.0 through 7.4.2, and Liferay DXP 7.1 before fix pack 27, 7.2 before fix pack 15, and 7.3 before service pack 3 allows remote attackers to inject arbitrary web script or HTML via the `tag`…

### CVE-2024-51442
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-77
- **Risk score:** 84
- **EPSS 39.1% (2026-05-30) → 51.7% (2026-06-12), Δ +12.6%**

> Command Injection in Minidlna version v1.3.3 and before allows an attacker to execute arbitrary OS commands via a specially crafted minidlna.conf configuration file.

### CVE-2025-13339
**Path Traversal · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Path Traversal
- **CVSS max:** 7.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 0.1% (2025-12-18) → 30.0% (2026-06-12), Δ +30.0%**

> The Hippoo Mobile App for WooCommerce plugin for WordPress is vulnerable to Path Traversal in all versions up to, and including, 1.7.1 via the template_redirect() function. This makes it possible for unauthenticated attackers to read the contents of arbitrary files on the server,…

### CVE-2026-28742
**Naxclow devices use a uniform request-signing scheme based on a hard-coded, platform-wide salt embedded in every firmware image.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-12T19:16:26.743
- **CWE:** CWE-321
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-12)

> Naxclow devices use a uniform request-signing scheme based on a hard-coded, platform-wide salt embedded in every firmware image. Once this salt is recovered from any device, an attacker can generate valid signatures for arbitrary device or account operations due to the absence of…

### CVE-2026-3018
**SQL Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** SQL Injection
- **CVSS max:** 7.5
- **NVD status:** Deferred
- **NVD modified:** 2026-06-10T18:35:12.690
- **CWE:** CWE-89
- **Risk score:** 82
- **EPSS 0.0% (2026-06-11) → 17.6% (2026-06-12), Δ +17.5%**

> The Newsletters plugin for WordPress is vulnerable to time-based SQL Injection via the ‘wpmlsubscriber_id’ parameter in all versions up to, and including, 4.13 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query…

### CVE-2026-3300
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T18:11:16.583
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 0.3% (2026-04-06) → 34.9% (2026-06-12), Δ +34.7%**

> The Everest Forms Pro plugin for WordPress is vulnerable to Remote Code Execution via PHP Code Injection in all versions up to, and including, 1.9.12. This is due to the Calculation Addon's process_filter() function concatenating user-submitted form field values into a PHP code s…

### CVE-2026-41492
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-04-27T18:57:20.293
- **CWE:** CWE-200
- **Risk score:** 86
- **EPSS 0.2% (2026-05-13) → 27.0% (2026-06-12), Δ +26.8%**

> Dgraph is an open source distributed GraphQL database. Prior to 25.3.3, Dgraphl exposes the process command line through the unauthenticated /debug/vars endpoint on Alpha. Because the admin token is commonly supplied via the --security "token=..." startup flag, an unauthenticated…

### CVE-2026-44990
**ApostropheCMS is an open-source Node.js content management system, and sanitize-html provides a simple HTML sanitizer with a clear API.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD modified:** 2026-06-12T21:16:22.447
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-12)

> ApostropheCMS is an open-source Node.js content management system, and sanitize-html provides a simple HTML sanitizer with a clear API. Under the default configuration, versions of `sanitize-html` prior to 2.17.4 can turn attacker-controlled content inside a disallowed `xmp` elem…

### CVE-2026-46716
**Nezha Monitoring is a self-hostable, lightweight, servers and websites monitoring and O&M tool.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Received
- **NVD modified:** 2026-06-12T22:16:50.810
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-12)

> Nezha Monitoring is a self-hostable, lightweight, servers and websites monitoring and O&M tool. From version 1.4.0 to before version 2.0.8, a RoleMember user can create a scheduled cron task with Cover=CronCoverAll, Servers=[] and an arbitrary Command. At every tick of the schedu…

### CVE-2026-48558
**SimpleHelp versions 5.5.15 and prior and 6.0 pre-release versions contain an authentication bypass vulnerability in the OIDC authenticati...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD modified:** 2026-06-12T18:16:35.317
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-06-12)

> SimpleHelp versions 5.5.15 and prior and 6.0 pre-release versions contain an authentication bypass vulnerability in the OIDC authentication flow. When OIDC authentication is configured, identity tokens submitted during login are accepted without verifying their cryptographic sign…

### CVE-2026-50090
**The Aqara Cloud OAuth Authorization Endpoint (open-cn.aqara.com/oauth/authorize) is vulnerable to a redirect bypass due to lax controls o...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-12T17:16:26.170
- **CWE:** CWE-1289
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-12)

> The Aqara Cloud OAuth Authorization Endpoint (open-cn.aqara.com/oauth/authorize) is vulnerable to a redirect bypass due to lax controls on domain matching, which is an instance of "CWE-1289: Improper Validation of Unsafe Equivalence in Input" and has an estimated CVSS of CVSS:3.1…

### CVE-2026-50091
**Aqara Home Android (com.lumiunited.aqarahome) 6.0.0 (and white-label clients embedding the same liblumidevsdk.so) uses hard-coded cryptog...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-06-12T17:16:26.283
- **CWE:** CWE-321
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-12)

> Aqara Home Android (com.lumiunited.aqarahome) 6.0.0 (and white-label clients embedding the same liblumidevsdk.so) uses hard-coded cryptographic keys, which is an instance of "CWE-321: Use of Hard-coded Cryptographic Key" and has an estimated CVSS of CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S…

### CVE-2026-50101
**Naxclow devices use a server-side, per-device relay credential that never rotates and is re-issued to the device on each boot.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Received
- **NVD modified:** 2026-06-12T19:16:29.487
- **CWE:** CWE-262
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-12)

> Naxclow devices use a server-side, per-device relay credential that never rotates and is re-issued to the device on each boot. Because this credential remains valid indefinitely and cannot be reset or revoked by the legitimate owner, any party that obtains it through any exposure…

### CVE-2026-53519
**Nezha Monitoring is a self-hostable, lightweight, servers and websites monitoring and O&M tool.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Received
- **NVD modified:** 2026-06-12T22:16:51.953
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-12)

> Nezha Monitoring is a self-hostable, lightweight, servers and websites monitoring and O&M tool. Prior to version 2.0.13, fallbackToFrontend in the dashboard's NoRoute handler treats any URL whose raw string starts with /dashboard as an admin-frontend asset request. The check uses…

### CVE-2026-53609
**ApostropheCMS is an open-source Node.js content management system.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Received
- **NVD modified:** 2026-06-12T22:16:52.803
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-12)

> ApostropheCMS is an open-source Node.js content management system. In versions up to and including 4.30.0, `apos.util.set()` traverses dot-notation paths without sanitizing `__proto__`, allowing an authenticated editor to write arbitrary values to `Object.prototype` via the `$pul…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-12*
