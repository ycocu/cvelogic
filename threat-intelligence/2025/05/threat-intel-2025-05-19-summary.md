# Daily Threat Intelligence — May 19, 2025

**Digest window (UTC):** 2025-05-19
**Generated:** 2026-06-02T07:32:44Z

## Threat brief

Ivanti Endpoint Manager Mobile (EPMM): 2 CVEs added to CISA KEV today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Ivanti Endpoint Manager Mobile (EPMM): 2 CVEs added to CISA KEV today.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 6 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2023-38950
**ZKTeco BioTime Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** zkteco biotime
- **Attack:** Path Traversal
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T19:02:59.793
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2025-05-19

> A path traversal vulnerability in the iclock API of ZKTeco BioTime v8.5.5 allows unauthenticated attackers to read arbitrary files via supplying a crafted payload. This vulnerability was fixed in version 9.0.120240617.19506 of ZKBioTime.

### CVE-2025-39380
**Unrestricted Upload of File with Dangerous Type vulnerability in mojoomla Hospital Management System hospital-management allows Upload a...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:29:26.820
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-19)

> Unrestricted Upload of File with Dangerous Type vulnerability in mojoomla Hospital Management System hospital-management allows Upload a Web Shell to a Web Server.This issue affects Hospital Management System: from n/a through <= 47.0(20-11-2023).

### CVE-2025-39401
**Unrestricted Upload of File with Dangerous Type vulnerability in mojoomla WPAMS apartment-management allows Upload a Web Shell to a Web S...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:29:29.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-19)

> Unrestricted Upload of File with Dangerous Type vulnerability in mojoomla WPAMS apartment-management allows Upload a Web Shell to a Web Server.This issue affects WPAMS: from n/a through <= 44.0 (17-08-2023).

### CVE-2024-11182
**MDaemon Email Server Cross-Site Scripting (XSS) Vulnerability**
- **Signals:** KEV
- **Asset:** mdaemon mdaemon
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T20:11:36.900
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 88
- **KEV:** added 2025-05-19

> An XSS issue was discovered in 

MDaemon Email Server before version 24.5.1c. An attacker can send an HTML e-mail message 
with 
JavaScript in an img tag. This could
 allow a remote attacker

to load arbitrary JavaScript code in the context of a webmail user's browser window.

### CVE-2024-27443
**Synacor Zimbra Collaboration Suite (ZCS) Cross-Site Scripting (XSS) Vulnerability**
- **Signals:** KEV
- **Asset:** zimbra collaboration
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T12:49:00.460
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 88
- **KEV:** added 2025-05-19

> An issue was discovered in Zimbra Collaboration (ZCS) 9.0 and 10.0. A Cross-Site Scripting (XSS) vulnerability exists in the CalendarInvite feature of the Zimbra webmail classic user interface, because of improper input validation in the handling of the calendar header. An attack…

### CVE-2025-27920
**Srimax Output Messenger Directory Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** srimax output_messenger
- **Attack:** Directory Traversal
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:28:43.010
- **CWE:** CWE-24
- **Risk score:** 88
- **KEV:** added 2025-05-19

> Output Messenger before 2.0.63 was vulnerable to a directory traversal attack through improper file path handling. By using ../ sequences in parameters, attackers could access sensitive files outside the intended directory, potentially leading to configuration leakage or arbitrar…

### CVE-2025-39354
**themegoods grand_conference Deserialization**
- **Signals:** CVSS
- **Asset:** themegoods grand_conference
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T15:29:23.937
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-19)

> Deserialization of Untrusted Data vulnerability in ThemeGoods Grand Conference grandconference allows Object Injection.This issue affects Grand Conference: from n/a through <= 5.3.

### CVE-2025-39356
**Deserialization of Untrusted Data vulnerability in Chimpstudio Foodbakery Sticky Cart foodbakery-sticky-cart allows Object Injection.This...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:29:24.160
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-19)

> Deserialization of Untrusted Data vulnerability in Chimpstudio Foodbakery Sticky Cart foodbakery-sticky-cart allows Object Injection.This issue affects Foodbakery Sticky Cart: from n/a through <= 3.2.

### CVE-2025-39386
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in mojoomla Hospital Management System...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:29:27.477
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-19)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in mojoomla Hospital Management System hospital-management allows SQL Injection.This issue affects Hospital Management System: from n/a through <= 47.0(20-11-2023).

### CVE-2025-39389
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Solid Plugins AnalyticsWP allows SQ...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-28T19:31:55.083
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-19)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Solid Plugins AnalyticsWP allows SQL Injection.This issue affects AnalyticsWP: from n/a through 2.1.2.

### CVE-2025-39395
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in mojoomla WPAMS apartment-management...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:29:28.313
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-19)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in mojoomla WPAMS apartment-management allows SQL Injection.This issue affects WPAMS: from n/a through <= 44.0 (17-08-2023).

### CVE-2025-39402
**Unrestricted Upload of File with Dangerous Type vulnerability in mojoomla WPAMS apartment-management allows Upload a Web Shell to a Web S...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:29:29.170
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-05-19)

> Unrestricted Upload of File with Dangerous Type vulnerability in mojoomla WPAMS apartment-management allows Upload a Web Shell to a Web Server.This issue affects WPAMS: from n/a through <= 44.0 (17-08-2023).

### CVE-2025-4427
**Ivanti Endpoint Manager Mobile (EPMM) Authentication Bypass Vulnerability**
- **Signals:** KEV
- **Asset:** ivanti endpoint_manager_mobile
- **Attack:** Auth Bypass
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:55:27.977
- **CWE:** CWE-288
- **Risk score:** 88
- **KEV:** added 2025-05-19

> An authentication bypass in the API component of Ivanti Endpoint Manager Mobile 12.5.0.0 and prior allows attackers to access protected resources without proper credentials via the API.

### CVE-2025-4428
**Ivanti Endpoint Manager Mobile (EPMM) Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** ivanti endpoint_manager_mobile
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:55:22.277
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2025-05-19

> Remote Code Execution in API component in Ivanti Endpoint Manager Mobile 12.5.0.0 and prior on unspecified platforms allows authenticated attackers to execute arbitrary code via crafted API requests.

### CVE-2025-47949
**samlify_project samlify**
- **Signals:** CVSS
- **Asset:** samlify_project samlify
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-19T17:32:34.830
- **CWE:** CWE-347
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-05-19)

> samlify is a Node.js library for SAML single sign-on. A Signature Wrapping attack has been found in samlify prior to version 2.10.0, allowing an attacker to forge a SAML Response to authenticate as any user. An attacker would need a signed XML document by the identity provider. V…

### CVE-2025-48340
**Cross-Site Request Forgery (CSRF) vulnerability in Danny Vink User Profile Meta Manager user-profile-meta allows Privilege Escalation.Thi...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:08.420
- **CWE:** CWE-352
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-19)

> Cross-Site Request Forgery (CSRF) vulnerability in Danny Vink User Profile Meta Manager user-profile-meta allows Privilege Escalation.This issue affects User Profile Meta Manager: from n/a through <= 1.02.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-19*
