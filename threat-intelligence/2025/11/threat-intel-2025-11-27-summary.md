# Daily Threat Intelligence — November 27, 2025

**Digest window (UTC):** 2025-11-27
**Generated:** 2026-06-02T07:33:52Z

## Threat brief

WordPress plugin RCE/exploit activity: 4 CVEs flagged today. · Mailenable Enterprise — exploitation likelihood rose sharply (EPSS 12% → 33% · rising (+21%)). · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 4 CVEs flagged today.
- Mailenable Enterprise — exploitation likelihood rose sharply (EPSS 12% → 33% · rising (+21%)).
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2008-1275
**mailenable mailenable_enterprise DoS**
- **Signals:** EPSS
- **Asset:** mailenable mailenable_enterprise
- **Attack:** DoS
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 83
- **EPSS 12.1% (2025-04-30) → 33.1% (2025-11-27), Δ +21.0%**

> Multiple unspecified vulnerabilities in the SMTP service in MailEnable Standard Edition 1.x, Professional Edition 3.x and earlier, and Enterprise Edition 3.x and earlier allow remote attackers to cause a denial of service (crash) via crafted (1) EXPN or (2) VRFY commands.

### CVE-2014-8269
**honeywell opos_suite Buffer Overflow**
- **Signals:** EPSS
- **Asset:** honeywell opos_suite
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 80
- **EPSS 6.2% (2025-03-30) → 17.1% (2025-11-27), Δ +10.9%**

> Multiple stack-based buffer overflows in (1) HWOPOSScale.ocx and (2) HWOPOSSCANNER.ocx in Honeywell OPOS Suite before 1.13.4.15 allow remote attackers to execute arbitrary code via a crafted file that is improperly handled by the Open method.

### CVE-2025-12419
**mattermost mattermost_server privilege escalation**
- **Signals:** CVSS
- **Asset:** mattermost mattermost_server
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-03T15:17:16.337
- **CWE:** CWE-303
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-11-27)

> Mattermost versions 10.12.x <= 10.12.1, 10.11.x <= 10.11.4, 10.5.x <= 10.5.12, 11.0.x <= 11.0.3 fail to properly validate OAuth state tokens during OpenID Connect authentication which allows an authenticated attacker with team creation privileges to take over a user account via m…

### CVE-2024-5539
**The Access Control Bypass vulnerability found in ALC WebCTRL and Carrier i-Vu in versions up to and including 8.5 allows a malicious acto...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-11-27)

> The Access Control Bypass vulnerability found in ALC WebCTRL and Carrier i-Vu in versions up to and including 8.5 allows a malicious actor to bypass intended access restrictions and expose sensitive information via the 

web based building automation server.

### CVE-2025-12140
**The application contains an insecure 'redirectToUrl' mechanism that incorrectly processes the value of the 'redirectUrlParameter' parameter.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-95
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-27)

> The application contains an insecure 'redirectToUrl' mechanism that incorrectly processes the value of the 'redirectUrlParameter' parameter. The application interprets the entered string of characters as a Java expression, allowing an unauthenticated attacer to perform arbitrary …

### CVE-2025-12421
**mattermost mattermost_server**
- **Signals:** CVSS
- **Asset:** mattermost mattermost_server
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-03T15:10:42.900
- **CWE:** CWE-303
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-11-27)

> Mattermost versions 11.0.x <= 11.0.2, 10.12.x <= 10.12.1, 10.11.x <= 10.11.4, 10.5.x <= 10.5.12 fail to to verify that the token used during the code exchange originates from the same authentication flow, which allows an authenticated user to perform account takeover via a specia…

### CVE-2025-13538
**The FindAll Listing plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.0.5.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-27)

> The FindAll Listing plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.0.5. This is due to the 'findall_listing_user_registration_additional_params' function not restricting what user roles a user can register with. This makes it po…

### CVE-2025-13539
**The FindAll Membership plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 1.0.4.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-27)

> The FindAll Membership plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 1.0.4. This is due to the plugin not properly logging in a user with the data that was previously verified through the 'findall_membership_check_facebook_user'…

### CVE-2025-13540
**The Tiare Membership plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.2.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-27)

> The Tiare Membership plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.2. This is due to the 'tiare_membership_init_rest_api_register' function not restricting what user roles a user can register with. This makes it possible for un…

### CVE-2025-13675
**The Tiger theme for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 101.2.1.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-27)

> The Tiger theme for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 101.2.1. This is due to the 'paypal-submit.php' file not restricting what user roles a user can register with. This makes it possible for unauthenticated attackers to supply …

### CVE-2025-8890
**Firmware in SDMC NE6037 routers prior to version 7.1.12.2.44 has a network diagnostics tool vulnerable to a shell command injection attacks.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-27)

> Firmware in SDMC NE6037 routers prior to version 7.1.12.2.44 has a network diagnostics tool vulnerable to a shell command injection attacks.
In order to exploit this vulnerability, an attacker has to log in to the router's administrative portal, which by default is reachable only…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-27*
