# Daily Threat Intelligence — May 15, 2026

**Digest window (UTC):** 2026-05-15
**Generated:** 2026-06-02T07:04:01Z

## Threat brief

Microsoft added to CISA KEV — confirmed in-the-wild exploitation. · Microsoft Windows 10 1607: public exploit or PoC linked · Siemens Automation License Manager — exploitation likelihood rose sharply (EPSS 14% → 48% · rising (+34%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft added to CISA KEV — confirmed in-the-wild exploitation.
- Microsoft Windows 10 1607: public exploit or PoC linked
- Siemens Automation License Manager — exploitation likelihood rose sharply (EPSS 14% → 48% · rising (+34%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 1 |
| EPSS rise | 9 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **21** |


## CVEs

### CVE-2026-42897
**Microsoft Exchange Server Cross-Site Scripting Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft exchange_server
- **Attack:** XSS
- **CVSS max:** 8.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-15T19:35:52.963
- **CWE:** CWE-79
- **Risk score:** 88
- **KEV:** added 2026-05-15

> Improper neutralization of input during web page generation ('cross-site scripting') in Microsoft Exchange Server allows an unauthorized attacker to perform spoofing over a network.

### CVE-2026-33829
**microsoft windows_10_1607**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1607
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-21T14:16:04.630
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2026-05-15

> Exposure of sensitive information to an unauthorized actor in Windows Snipping Tool allows an unauthorized attacker to perform spoofing over a network.

### CVE-2011-4529
**siemens automation_license_manager Buffer Overflow**
- **Signals:** EPSS
- **Asset:** siemens automation_license_manager
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 14.5% (2026-04-27) → 48.3% (2026-05-15), Δ +33.8%**

> Multiple buffer overflows in Siemens Automation License Manager (ALM) 4.0 through 5.1+SP1+Upd1 allow remote attackers to execute arbitrary code via a long serialid field in an _licensekey command, as demonstrated by the (1) check_licensekey or (2) read_licensekey command.

### CVE-2011-4530
**siemens automation_license_manager DoS**
- **Signals:** EPSS
- **Asset:** siemens automation_license_manager
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-20
- **Risk score:** 78
- **EPSS 11.3% (2026-04-27) → 35.3% (2026-05-15), Δ +24.1%**

> Siemens Automation License Manager (ALM) 4.0 through 5.1+SP1+Upd1 does not properly copy fields obtained from clients, which allows remote attackers to cause a denial of service (exception and daemon crash) via long fields, as demonstrated by fields to the (1) open_session->works…

### CVE-2011-4531
**siemens automation_license_manager DoS**
- **Signals:** EPSS
- **Asset:** siemens automation_license_manager
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-20
- **Risk score:** 78
- **EPSS 13.3% (2026-04-27) → 35.3% (2026-05-15), Δ +22.0%**

> Siemens Automation License Manager (ALM) 4.0 through 5.1+SP1+Upd1 allows remote attackers to cause a denial of service (NULL pointer dereference and daemon crash) via crafted content in a (1) get_target_ocx_param or (2) send_target_ocx_param command.

### CVE-2015-10139
**vibethemes wordpress_learning_management_system_ Privilege Escalation**
- **Signals:** EPSS
- **Asset:** vibethemes wordpress_learning_management_system_
- **Attack:** Privilege Escalation
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T15:49:59.177
- **CWE:** CWE-269
- **Risk score:** 84
- **EPSS 48.5% (2026-04-04) → 67.7% (2026-05-15), Δ +19.2%**

> The WPLMS theme for WordPress is vulnerable to Privilege Escalation in versions 1.5.2 to 1.8.4.1 via the 'wp_ajax_import_data' AJAX action. This makes it possible for authenticated attackers to change otherwise restricted settings and potentially create a new accessible admin acc…

### CVE-2018-4222
**apple icloud**
- **Signals:** EPSS
- **Asset:** apple safari
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:07:00.107
- **CWE:** CWE-125
- **Risk score:** 84
- **EPSS 39.8% (2026-04-06) → 56.0% (2026-05-15), Δ +16.2%**

> An issue was discovered in certain Apple products. iOS before 11.4 is affected. Safari before 11.1.1 is affected. iCloud before 7.5 on Windows is affected. iTunes before 12.7.5 on Windows is affected. tvOS before 11.4 is affected. watchOS before 4.3.1 is affected. The issue invol…

### CVE-2020-13122
**noviflow noviware Command Injection**
- **Signals:** EPSS
- **Asset:** noviflow noviware
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:00:42.163
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 7.5% (2025-11-21) → 22.5% (2026-05-15), Δ +15.0%**

> The novish command-line interface, included in NoviFlow NoviWare before NW500.2.12 and deployed on NoviSwitch devices, is vulnerable to command injection in the "show status destination ipaddr" command. This could be used by a read-only user (monitoring group) or admin to execute…

### CVE-2021-24731
**genetechsolutions pie_register SQL Injection**
- **Signals:** EPSS
- **Asset:** genetechsolutions pie_register
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:53:39.093
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 53.1% (2025-11-21) → 68.1% (2026-05-15), Δ +15.0%**

> The Registration Forms – User profile, Content Restriction, Spam Protection, Payment Gateways, Invitation Codes WordPress plugin before 3.7.1.6 does not properly escape user data before using it in a SQL statement in the wp-json/pie/v1/login REST API endpoint, leading to an SQL i…

### CVE-2021-47965
**WordPress Plugin WP Super Edit 2.5.4 and earlier contains an unrestricted file upload vulnerability in the FCKeditor component that allow...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T17:05:46.240
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-15)

> WordPress Plugin WP Super Edit 2.5.4 and earlier contains an unrestricted file upload vulnerability in the FCKeditor component that allows attackers to upload dangerous file types without validation. Attackers can upload arbitrary files through the filemanager upload endpoint to …

### CVE-2025-28146
**edimax br-6478ac_v3_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** edimax br-6478ac_v3_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-28T17:53:37.343
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 17.4% (2026-05-13) → 33.4% (2026-05-15), Δ +16.0%**

> Edimax AC1200 Wave 2 Dual-Band Gigabit Router BR-6478AC V3 1.0.15 was discovered to contain a command injection vulnerability via fota_url in /boafrm/formLtefotaUpgradeQuectel

### CVE-2026-2031
**An Improper Access Control vulnerability in several internal API endpoints for Google Cloud Application Integration prior to 2026-01-23 a...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-18T19:32:38.777
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-15)

> An Improper Access Control vulnerability in several internal API endpoints for Google Cloud Application Integration prior to 2026-01-23 allows a remote, unauthenticated attacker to disclose sensitive internal information and execute arbitrary code using specially crafted HTTP req…

### CVE-2026-2441
**Google Chromium CSS Use-After-Free Vulnerability**
- **Signals:** EPSS
- **Asset:** google chrome
- **Attack:** Use-After-Free
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T13:24:55.920
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 84
- **EPSS 9.5% (2026-05-01) → 23.1% (2026-05-15), Δ +13.7%**

> Use after free in CSS in Google Chrome prior to 145.0.7632.75 allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page. (Chromium security severity: High)

### CVE-2026-41258
**OpenMRS is an open source electronic medical record system platform.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T19:59:59.590
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-15)

> OpenMRS is an open source electronic medical record system platform. From 2.7.0 to before 2.7.9 and 2.8.6, the ConceptReferenceRangeUtility.evaluateCriteria() method in OpenMRS Core evaluates database-stored criteria strings as Apache Velocity templates without any sandbox config…

### CVE-2026-42155
**Magento Long Term Support (LTS) is an unofficial, community-driven project provides an alternative to the Magento Community Edition e-com...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T19:35:04.993
- **CWE:** CWE-330
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-15)

> Magento Long Term Support (LTS) is an unofficial, community-driven project provides an alternative to the Magento Community Edition e-commerce platform with a high level of backward compatibility. Prior to 20.18.0, the XML-RPC / SOAP API session ID is generated using an outdated,…

### CVE-2026-44551
**openwebui open_webui**
- **Signals:** CVSS
- **Asset:** openwebui open_webui
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-18T18:35:23.590
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-15)

> Open WebUI is a self-hosted artificial intelligence platform designed to operate entirely offline. Prior to 0.9.0, the LDAP authentication endpoint does not validate that the submitted password is non-empty before performing a Simple Bind against the LDAP server. The LdapForm Pyd…

### CVE-2026-44699
**LibJWT is a C JSON Web Token Library.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T19:59:59.590
- **CWE:** CWE-327
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-15)

> LibJWT is a C JSON Web Token Library. From 3.0.0 to 3.3.2, libjwt accepts an RSA JWK that does not contain an alg parameter as the verification key for an HS256/HS384/HS512 token. In the OpenSSL backend, this causes HMAC verification to run with a zero-length key, so an attacker …

### CVE-2026-44717
**MCP Calculate Server is a mathematical calculation service based on MCP protocol and SymPy library.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T19:59:59.590
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-15)

> MCP Calculate Server is a mathematical calculation service based on MCP protocol and SymPy library. Prior to 0.1.1, the use of eval() to evaluate mathematical expressions without proper input sanitization leads to remote code execution. This vulnerability is fixed in 0.1.1.

### CVE-2026-45010
**phpMyFAQ before 4.1.2 contains an improper restriction of excessive authentication attempts vulnerability in the /admin/check endpoint, w...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-28T16:16:25.767
- **CWE:** CWE-307
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-15)

> phpMyFAQ before 4.1.2 contains an improper restriction of excessive authentication attempts vulnerability in the /admin/check endpoint, which accepts arbitrary user-id parameters without session binding or rate limiting. Unauthenticated attackers can brute-force any user's six-di…

### CVE-2026-45035
**tabby tabby**
- **Signals:** CVSS
- **Asset:** tabby tabby
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-19T19:41:53.460
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-15)

> Tabby (formerly Terminus) is a highly configurable terminal emulator. Prior to 1.0.233, Tabby registers itself as the handler for the tabby:// URL scheme on all platforms. The URL scheme handler supports a run command that directly executes OS commands with no user confirmation, …

### CVE-2026-46364
**phpMyFAQ before 4.1.2 contains an unauthenticated SQL injection vulnerability in BuiltinCaptcha::garbageCollector() and BuiltinCaptcha::s...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-28T16:16:27.087
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-15)

> phpMyFAQ before 4.1.2 contains an unauthenticated SQL injection vulnerability in BuiltinCaptcha::garbageCollector() and BuiltinCaptcha::saveCaptcha() methods that interpolate unsanitized User-Agent headers into DELETE and INSERT queries. Unauthenticated attackers can exploit the …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-15*
