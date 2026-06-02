# Daily Threat Intelligence — December 03, 2025

**Digest window (UTC):** 2025-12-03
**Generated:** 2026-06-02T07:33:54Z

## Threat brief

OpenPLC ScadaBR added to CISA KEV — confirmed in-the-wild exploitation. · Djangoproject Django: public exploit or PoC linked (SQL Injection) · WordPress plugin RCE/exploit activity: 3 CVEs flagged today. · Wpdevart Poll\, Survey\, Questionnaire And Voting System — exploitation likelihood rose sharply (EPSS 55% → 73% · rising (+17%)).

## Executive summary

- OpenPLC ScadaBR added to CISA KEV — confirmed in-the-wild exploitation.
- Djangoproject Django: public exploit or PoC linked (SQL Injection)
- WordPress plugin RCE/exploit activity: 3 CVEs flagged today.
- Wpdevart Poll\, Survey\, Questionnaire And Voting System — exploitation likelihood rose sharply (EPSS 55% → 73% · rising (+17%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 13 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **25** |


## CVEs

### CVE-2021-26828
**OpenPLC ScadaBR Unrestricted Upload of File with Dangerous Type Vulnerability**
- **Signals:** KEV
- **Asset:** scadabr scadabr
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-04T14:47:47.693
- **CWE:** CWE-434
- **CWE:** CWE-434
- **Risk score:** 88
- **KEV:** added 2025-12-03

> OpenPLC ScadaBR through 0.9.1 on Linux and through 1.12.4 on Windows allows remote authenticated users to upload and execute arbitrary JSP files via view_edit.shtm.

### CVE-2017-15734
**phpmyfaq phpmyfaq CSRF**
- **Signals:** EXP
- **Asset:** phpmyfaq phpmyfaq
- **Attack:** CSRF
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-352
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> In phpMyFAQ before 2.9.9, there is Cross-Site Request Forgery (CSRF) in admin/stat.main.php.

### CVE-2021-24442
**wpdevart poll\,_survey\,_questionnaire_and_voting_system SQL Injection**
- **Signals:** EPSS
- **Asset:** wpdevart poll\,_survey\,_questionnaire_and_voting_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:53:04.950
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 55.0% (2025-11-29) → 72.5% (2025-12-03), Δ +17.5%**

> The Poll, Survey, Questionnaire and Voting system WordPress plugin before 1.5.3 did not sanitise, escape or validate the date_answers[] POST parameter before using it in a SQL statement when sending a Poll result, allowing unauthenticated users to perform SQL Injection attacks

### CVE-2017-15735
**phpmyfaq phpmyfaq CSRF**
- **Signals:** EXP
- **Asset:** phpmyfaq phpmyfaq
- **Attack:** CSRF
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-352
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> In phpMyFAQ before 2.9.9, there is Cross-Site Request Forgery (CSRF) for modifying a glossary.

### CVE-2017-15808
**phpmyfaq phpmyfaq CSRF**
- **Signals:** EXP
- **Asset:** phpmyfaq phpmyfaq
- **Attack:** CSRF
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-352
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> In phpMyFaq before 2.9.9, there is CSRF in admin/ajax.config.php.

### CVE-2017-6478
**mangoswebv4_project mangoswebv4 cross-site scripting**
- **Signals:** EXP
- **Asset:** mangoswebv4_project mangoswebv4
- **Attack:** cross-site scripting
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> paintballrefjosh/MaNGOSWebV4 before 4.0.8 is vulnerable to a reflected XSS in install/index.php (step parameter).

### CVE-2018-25080
**mobiledetect mobiledetect cross-site scripting**
- **Signals:** EXP
- **Asset:** mobiledetect mobiledetect
- **Attack:** cross-site scripting
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T15:15:44.680
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> A vulnerability, which was classified as problematic, has been found in MobileDetect 2.8.31. This issue affects the function initLayoutType of the file examples/session_example.php of the component Example. The manipulation of the argument $_SERVER['PHP_SELF'] leads to cross site…

### CVE-2019-16693
**phpipam phpipam SQL Injection**
- **Signals:** EXP
- **Asset:** phpipam phpipam
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T15:15:44.933
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> phpIPAM 1.4 allows SQL injection via the app/admin/custom-fields/order.php table parameter when action=add is used.

### CVE-2019-25024
**alleghenycreative openrepeater Command Injection**
- **Signals:** EXP
- **Asset:** alleghenycreative openrepeater
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T15:15:45.070
- **CWE:** CWE-78
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> OpenRepeater (ORP) before 2.2 allows unauthenticated command injection via shell metacharacters in the functions/ajax_system.php post_service parameter.

### CVE-2020-15716
**rosariosis rosariosis cross-site scripting**
- **Signals:** EXP
- **Asset:** rosariosis rosariosis
- **Attack:** cross-site scripting
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T15:15:45.380
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> RosarioSIS 6.7.2 is vulnerable to XSS, caused by improper validation of user-supplied input by the Preferences.php script. A remote attacker could exploit this vulnerability using the tab parameter in a crafted URL.

### CVE-2020-15718
**rosariosis rosariosis cross-site scripting**
- **Signals:** EXP
- **Asset:** rosariosis rosariosis
- **Attack:** cross-site scripting
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T15:15:45.540
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> RosarioSIS 6.7.2 is vulnerable to XSS, caused by improper validation of user-supplied input by the PrintSchedules.php script. A remote attacker could exploit this vulnerability using the include_inactive parameter in a crafted URL.

### CVE-2020-20969
**pluck-cms pluck**
- **Signals:** EXP
- **Asset:** pluck-cms pluck
- **CVSS max:** 7.2
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T15:15:45.677
- **CWE:** CWE-434
- **CWE:** CWE-434
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> File Upload vulnerability in PluckCMS v.4.7.10 allows a remote attacker to execute arbitrary code via the trashcan_restoreitem.php file.

### CVE-2020-5504
**debian debian_linux SQL Injection**
- **Signals:** EXP
- **Asset:** phpmyadmin phpmyadmin
- **Attack:** SQL Injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T15:15:46.240
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> In phpMyAdmin 4 before 4.9.4 and 5 before 5.0.1, SQL injection exists in the user accounts page. A malicious user could inject custom SQL in place of their own username when creating queries to this page. An attacker must have a valid MySQL account to access the server.

### CVE-2021-40617
**os4ed opensis SQL Injection**
- **Signals:** EXP
- **Asset:** os4ed opensis
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T15:15:46.750
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> An SQL Injection vulnerability exists in openSIS Community Edition version 8.0 via ForgotPassUserName.php.

### CVE-2024-32641
**masacms masacms RCE**
- **Signals:** CVSS
- **Asset:** masacms masacms
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-05T14:47:50.093
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-03)

> Masa CMS is an open source Enterprise Content Management platform. Masa CMS versions prior to 7.2.8, 7.3.13, and 7.4.6 are vulnerable to remote code execution. The vulnerability exists in the addParam function, which accepts user input via the criteria parameter. This input is su…

### CVE-2025-13342
**The Frontend Admin by DynamiApps plugin for WordPress is vulnerable to unauthorized modification of arbitrary WordPress options in all ve...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-03)

> The Frontend Admin by DynamiApps plugin for WordPress is vulnerable to unauthorized modification of arbitrary WordPress options in all versions up to, and including, 3.28.20. This is due to insufficient capability checks and input validation in the ActionOptions::run() save handl…

### CVE-2025-13390
**wpdirectorykit wp_directory_kit Auth Bypass**
- **Signals:** CVSS
- **Asset:** wpdirectorykit wp_directory_kit
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T21:17:39.083
- **CWE:** CWE-303
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-12-03)

> The WP Directory Kit plugin for WordPress is vulnerable to authentication bypass in all versions up to, and including, 1.4.4 due to incorrect implementation of the authentication algorithm in the "wdk_generate_auto_login_link" function. This is due to the feature using a cryptogr…

### CVE-2025-13486
**The Advanced Custom Fields: Extended plugin for WordPress is vulnerable to Remote Code Execution in versions 0.9.0.5 through 0.9.1.1 via...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-03)

> The Advanced Custom Fields: Extended plugin for WordPress is vulnerable to Remote Code Execution in versions 0.9.0.5 through 0.9.1.1 via the prepare_form() function. This is due to the function accepting user input and then passing that through call_user_func_array(). This makes …

### CVE-2025-34319
**TOTOLINK N300RT wireless router firmware versions prior to V3.4.0-B20250430 (discovered in V2.1.8-B20201030.1539) contain an OS command i...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-03)

> TOTOLINK N300RT wireless router firmware versions prior to V3.4.0-B20250430 (discovered in V2.1.8-B20201030.1539) contain an OS command injection vulnerability in the Boa formWsc handling functionality. An unauthenticated attacker can send specially crafted requests to trigger co…

### CVE-2025-55182
**Meta React Server Components Remote Code Execution Vulnerability**
- **Signals:** CVSS
- **Asset:** facebook react
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T02:00:02.557
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-12-03)

> A pre-authentication remote code execution vulnerability exists in React Server Components versions 19.0.0, 19.1.0, 19.1.1, and 19.2.0 including the following packages: react-server-dom-parcel, react-server-dom-turbopack, and react-server-dom-webpack. The vulnerable code unsafely…

### CVE-2025-64055
**fanvil x210_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** fanvil x210_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-09T02:18:23.843
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-03)

> An issue was discovered in Fanvil x210 V2 2.12.20 allowing unauthenticated attackers on the local network to access administrative functions of the device (e.g. file upload, firmware update, reboot...) via a crafted authentication bypass.

### CVE-2025-64459
**djangoproject django SQL Injection**
- **Signals:** EXP
- **Asset:** djangoproject django
- **Attack:** SQL Injection
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-10T18:25:59.883
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-12-03

> An issue was discovered in 5.1 before 5.1.14, 4.2 before 4.2.26, and 5.2 before 5.2.8.
The methods `QuerySet.filter()`, `QuerySet.exclude()`, and `QuerySet.get()`, and the class `Q()`, are subject to SQL injection when using a suitably crafted dictionary, with dictionary expansio…

### CVE-2025-65267
**frappe erpnext Privilege Escalation**
- **Signals:** CVSS
- **Asset:** frappe erpnext
- **Attack:** Privilege Escalation
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-05T18:35:19.883
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-12-03)

> In ERPNext v15.83.2 and Frappe Framework v15.86.0, improper validation of uploaded SVG avatar images allows attackers to embed malicious JavaScript. The payload executes when an administrator clicks the image link to view the avatar, resulting in stored cross-site scripting (XSS)…

### CVE-2025-66222
**thinkinai deepchat RCE**
- **Signals:** CVSS
- **Asset:** thinkinai deepchat
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-05T15:37:59.973
- **CWE:** CWE-94
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-12-03)

> DeepChat is a smart assistant uses artificial intelligence. In 0.5.0 and earlier, there is a Stored Cross-Site Scripting (XSS) vulnerability in the Mermaid diagram renderer allows an attacker to execute arbitrary JavaScript within the application context. By leveraging the expose…

### CVE-2025-66489
**cal cal.com**
- **Signals:** CVSS
- **Asset:** cal cal.com
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T16:03:36.057
- **CWE:** CWE-303
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-03)

> Cal.com is open-source scheduling software. Prior to 5.9.8, A flaw in the login credentials provider allows an attacker to bypass password verification when a TOTP code is provided, potentially gaining unauthorized access to user accounts. This issue exists due to problematic con…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-03*
