# Daily Threat Intelligence — May 19, 2026

**Digest window (UTC):** 2026-05-19
**Generated:** 2026-06-02T07:04:03Z

## Threat brief

Yiiframework Yii — exploitation likelihood rose sharply (EPSS 59% → 79% · rising (+20%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Yiiframework Yii — exploitation likelihood rose sharply (EPSS 59% → 79% · rising (+20%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2024-58136
**Yiiframework Yii Improper Protection of Alternate Path Vulnerability**
- **Signals:** EPSS
- **Asset:** yiiframework yii
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:28:54.540
- **CWE:** CWE-424
- **Risk score:** 84
- **EPSS 59.0% (2026-05-18) → 78.9% (2026-05-19), Δ +19.9%**

> Yii 2 before 2.0.52 mishandles the attaching of behavior that is defined by an __class array key, a CVE-2024-4990 regression, as exploited in the wild in February through April 2025.

### CVE-2022-4978
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 32.4% (2025-12-20) → 49.4% (2026-05-19), Δ +17.0%**

> Remote Control Server, maintained by Steppschuh, 3.1.1.12 allows unauthenticated remote code execution when authentication is disabled, which is the default configuration. The server exposes a custom UDP-based control protocol that accepts remote keyboard input events without ver…

### CVE-2026-34234
**CtrlPanel is open-source billing software for hosting providers.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-20T17:16:21.257
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-19)

> CtrlPanel is open-source billing software for hosting providers. In versions 1.1.1 and prior, the web-based installer (public/installer/index.php) is vulnerable to unauthenticated Remote Code Execution (RCE) because it performs the install.lock check only after including and exec…

### CVE-2012-0392
**apache struts Code Execution**
- **Signals:** EPSS
- **Asset:** apache struts
- **Attack:** Code Execution
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **Risk score:** 81
- **EPSS 75.0% (2026-04-27) → 90.3% (2026-05-19), Δ +15.3%**

> The CookieInterceptor component in Apache Struts before 2.3.1.1 does not use the parameter-name whitelist, which allows remote attackers to execute arbitrary commands via a crafted HTTP Cookie header that triggers Java code execution through a static method.

### CVE-2012-0393
**apache struts**
- **Signals:** EPSS
- **Asset:** apache struts
- **CVSS max:** 6.4
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-264
- **Risk score:** 81
- **EPSS 58.5% (2026-03-17) → 73.6% (2026-05-19), Δ +15.1%**

> The ParameterInterceptor component in Apache Struts before 2.3.1.1 does not prevent access to public constructors, which allows remote attackers to create or overwrite arbitrary files via a crafted parameter that triggers the creation of a Java object.

### CVE-2023-31126
**xwiki xwiki XSS**
- **Signals:** EPSS
- **Asset:** xwiki xwiki
- **Attack:** XSS
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD modified:** 2025-01-28T18:15:31.827
- **CWE:** CWE-86
- **CWE:** CWE-79
- **Risk score:** 84
- **EPSS 9.2% (2026-05-18) → 21.6% (2026-05-19), Δ +12.4%**

> `org.xwiki.commons:xwiki-commons-xml` is an XML library used by the open-source wiki platform XWiki. The HTML sanitizer, introduced in version 14.6-rc-1, allows the injection of arbitrary HTML code and thus cross-site scripting via invalid data attributes. This vulnerability does…

### CVE-2023-32070
**xwiki rendering XSS**
- **Signals:** EPSS
- **Asset:** xwiki rendering
- **Attack:** XSS
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2025-01-27T18:15:35.993
- **CWE:** CWE-83
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 83
- **EPSS 11.0% (2026-05-12) → 21.9% (2026-05-19), Δ +10.9%**

> XWiki Platform is a generic wiki platform. Prior to version 14.6-rc-1, HTML rendering didn't check for dangerous attributes/attribute values. This allowed cross-site scripting (XSS) attacks via attributes and link URLs, e.g., supported in XWiki syntax. This has been patched in XW…

### CVE-2026-31070
**The LalanaChami Pharmacy Management System (commit 5c3d028) allows unauthenticated remote attackers to escalate privileges by self-assign...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-20T14:16:40.350
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-19)

> The LalanaChami Pharmacy Management System (commit 5c3d028) allows unauthenticated remote attackers to escalate privileges by self-assigning an administrative role during registration. The /api/user/signup endpoint fails to validate the role parameter in the request body

### CVE-2026-31071
**API endpoints in LalanaChami Pharmacy Management System (commit 5c3d028) lack authentication middleware.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-20T14:16:40.560
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-19)

> API endpoints in LalanaChami Pharmacy Management System (commit 5c3d028) lack authentication middleware. Unauthenticated remote attackers can exploit this to dump all user records (including bcrypt password hashes) via /api/user/getUserData, modify drug inventory, and access priv…

### CVE-2026-31072
**The JSONSerializer and CBORSerializer in APScheduler (all versions including 3.10.x and 4.0.0a5) are vulnerable to Remote Code Execution...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-20T17:16:20.947
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-19)

> The JSONSerializer and CBORSerializer in APScheduler (all versions including 3.10.x and 4.0.0a5) are vulnerable to Remote Code Execution (RCE) via Insecure Deserialization. The unmarshal_object function allows for arbitrary class instantiation and state injection by dynamically i…

### CVE-2026-33642
**Kitty is a cross-platform GPU based terminal.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-05-19T21:08:41.030
- **CWE:** CWE-125
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-19)

> Kitty is a cross-platform GPU based terminal. In versions 0.46.2 and below, the handle_compose_command() function in kitty/graphics.c performs bounds validation on composition offsets using unsigned 32-bit arithmetic that is subject to integer wrapping, potentially leading to Hea…

### CVE-2026-36829
**An authentication bypass vulnerability exists in the embedded HTTP server of Panabit PAP-XM320 up to and including v7.7.**
- **Signals:** CVSS
- **Attack:** Directory Traversal
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-19T18:16:21.613
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-19)

> An authentication bypass vulnerability exists in the embedded HTTP server of Panabit PAP-XM320 up to and including v7.7. The server validates session cookies using a filesystem existence check based on a user-controlled cookie value without proper sanitization, allowing directory…

### CVE-2026-37281
**An OS command injection vulnerability in the /stream-to-vlc Express route in hitarth-gg Zenshin before 2.7.0 allows remote attackers to e...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-20T17:16:21.467
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-19)

> An OS command injection vulnerability in the /stream-to-vlc Express route in hitarth-gg Zenshin before 2.7.0 allows remote attackers to execute arbitrary commands via the url parameter.

### CVE-2026-47357
**tenable terrascan SSRF**
- **Signals:** CVSS
- **Asset:** tenable terrascan
- **Attack:** SSRF
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-20T14:23:12.183
- **CWE:** CWE-73
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-19)

> Terrascan v1.18.3 and prior are vulnerable to Server-Side Request Forgery (SSRF) via the remote_url parameter in the remote directory scan endpoint (POST /v1/{iac}/{iacVersion}/{cloud}/remote/dir/scan) when running in server mode. An unauthenticated remote attacker can supply an …

### CVE-2026-47358
**tenable terrascan SSRF**
- **Signals:** CVSS
- **Asset:** tenable terrascan
- **Attack:** SSRF
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-20T14:18:30.710
- **CWE:** CWE-73
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-05-19)

> Terrascan v1.18.3 and prior are vulnerable to Server-Side Request Forgery (SSRF) via external URL resolution in uploaded IaC templates when running in server mode. When Terrascan parses uploaded ARM templates or CloudFormation templates, it resolves external URLs referenced withi…

### CVE-2026-8495
**date_ical_project date_ical privilege escalation**
- **Signals:** CVSS
- **Asset:** date_ical_project date_ical
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T15:14:11.787
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-19)

> Missing Authorization vulnerability in Drupal Date iCal allows Forceful Browsing.

This issue affects Date iCal: from 0.0.0 before 4.0.15.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-19*
