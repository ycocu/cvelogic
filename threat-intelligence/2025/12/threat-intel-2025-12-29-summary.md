# Daily Threat Intelligence — December 29, 2025

**Digest window (UTC):** 2025-12-29
**Generated:** 2026-06-02T07:34:04Z

## Threat brief

MongoDB And MongoDB Server added to CISA KEV — confirmed in-the-wild exploitation. · Nagios Xi — exploitation likelihood rose sharply (EPSS 6.4% → 39% · rising (+33%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- MongoDB And MongoDB Server added to CISA KEV — confirmed in-the-wild exploitation.
- Nagios Xi — exploitation likelihood rose sharply (EPSS 6.4% → 39% · rising (+33%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 5 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2025-14847
**MongoDB and MongoDB Server Improper Handling of Length Parameter Inconsistency Vulnerability**
- **Signals:** KEV
- **Asset:** mongodb mongodb
- **CVSS max:** 8.7
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-13T22:24:20.380
- **CWE:** CWE-130
- **Risk score:** 88
- **KEV:** added 2025-12-29

> Mismatched length fields in Zlib compressed protocol headers may allow a read of uninitialized heap memory by an unauthenticated client. This issue affects all MongoDB Server v7.0 prior to 7.0.28 versions, MongoDB Server v8.0 versions prior to 8.0.17, MongoDB Server v8.2 versions…

### CVE-2020-15901
**nagios nagios_xi**
- **Signals:** EPSS
- **Asset:** nagios nagios_xi
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:06:24.823
- **Risk score:** 84
- **EPSS 6.4% (2025-12-17) → 39.0% (2025-12-29), Δ +32.5%**

> In Nagios XI before 5.7.3, ajaxhelper.php allows remote authenticated attackers to execute arbitrary commands via cmdsubsys.

### CVE-2025-68562
**Unrestricted Upload of File with Dangerous Type vulnerability in RomanCode MapSVG mapsvg-lite-interactive-vector-maps allows Upload a Web...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:36:01.723
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-29)

> Unrestricted Upload of File with Dangerous Type vulnerability in RomanCode MapSVG mapsvg-lite-interactive-vector-maps allows Upload a Web Shell to a Web Server.This issue affects MapSVG: from n/a through <= 8.7.3.

### CVE-2008-6897
**andres_garcia getleft Buffer Overflow**
- **Signals:** EPSS
- **Asset:** andres_garcia getleft
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 6.3% (2025-12-25) → 23.3% (2025-12-29), Δ +17.0%**

> Multiple buffer overflows in Getleft.exe in Andres Garcia Getleft 1.2 allow remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a long (1) "a" HTML tag; a long src attribute in (2) embed, (3) img, or (4) script tags; (5) a long background…

### CVE-2022-41931
**xwiki xwiki**
- **Signals:** EPSS
- **Asset:** xwiki xwiki
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:24:05.783
- **CWE:** CWE-95
- **Risk score:** 83
- **EPSS 8.5% (2025-12-17) → 18.9% (2025-12-29), Δ +10.4%**

> xwiki-platform-icon-ui is vulnerable to Improper Neutralization of Directives in Dynamically Evaluated Code ('Eval Injection'). Any user with view rights on commonly accessible documents including the icon picker macro can execute arbitrary Groovy, Python or Velocity code in XWik…

### CVE-2022-41934
**xwiki xwiki**
- **Signals:** EPSS
- **Asset:** xwiki xwiki
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:24:06.210
- **CWE:** CWE-74
- **CWE:** CWE-116
- **Risk score:** 86
- **EPSS 9.4% (2025-12-17) → 23.6% (2025-12-29), Δ +14.2%**

> XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. Any user with view rights on commonly accessible documents including the menu macro can execute arbitrary Groovy, Python or Velocity code in XWiki leading to full access to th…

### CVE-2022-46538
**tenda f1203_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** tenda f1203_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T19:15:48.897
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 6.6% (2025-12-25) → 18.4% (2025-12-29), Δ +11.7%**

> Tenda F1203 V2.0.1.6 was discovered to contain a command injection vulnerability via the mac parameter at /goform/WriteFacMac.

### CVE-2024-25181
**vvveb vvvebjs SSRF**
- **Signals:** CVSS
- **Asset:** vvveb vvvebjs
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-07T14:50:45.963
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-29)

> A critical vulnerability has been identified in givanz VvvebJs 1.7.2, which allows both Server-Side Request Forgery (SSRF) and arbitrary file reading. The vulnerability stems from improper handling of user-supplied URLs in the "file_get_contents" function within the "save.php" fi…

### CVE-2024-25182
**vvveb vvvebjs**
- **Signals:** CVSS
- **Asset:** vvveb vvvebjs
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-02T22:15:43.363
- **CWE:** CWE-434
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-29)

> givanz VvvebJs 1.7.2 suffers from a File Upload vulnerability via save.php.

### CVE-2024-27480
**vvveb vvvebjs**
- **Signals:** CVSS
- **Asset:** vvveb vvvebjs
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-02T22:15:43.553
- **CWE:** CWE-434
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-29)

> givanz VvvebJs 1.7.2 is vulnerable to Insecure File Upload.

### CVE-2025-56333
**pangolin pangolin privilege escalation**
- **Signals:** CVSS
- **Asset:** pangolin pangolin
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-07T21:14:32.147
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-29)

> An issue in Fossorial fosrl/pangolin v.1.6.2 and before allows a remote attacker to escalate privileges via the 2FA component

### CVE-2025-65570
**jsish jsish**
- **Signals:** CVSS
- **Asset:** jsish jsish
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T20:04:10.750
- **CWE:** CWE-843
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-29)

> A type confusion in jsish 2.0 allows incorrect control flow during execution of the OP_NEXT opcode. When an “instanceof” expression uses an array element access as the left-hand operand inside a for-in loop, the instructions implementation leaves an additional array reference on …

### CVE-2025-68706
**kuwfi ac900_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** kuwfi ac900_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T02:21:29.610
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-29)

> A stack-based buffer overflow exists in the GoAhead-Webs HTTP daemon on KuWFi 4G LTE AC900 devices with firmware 1.0.13. The /goform/formMultiApnSetting handler uses sprintf() to copy the user-supplied pincode parameter into a fixed 132-byte stack buffer with no bounds checks. Th…

### CVE-2025-68860
**Authentication Bypass Using an Alternate Path or Channel vulnerability in Mobile Builder Mobile builder mobile-builder allows Authenticat...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:36:09.940
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-29)

> Authentication Bypass Using an Alternate Path or Channel vulnerability in Mobile Builder Mobile builder mobile-builder allows Authentication Abuse.This issue affects Mobile builder: from n/a through <= 1.4.2.

### CVE-2025-68897
**Improper Control of Generation of Code ('Code Injection') vulnerability in Mohammad I.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:36:11.967
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-29)

> Improper Control of Generation of Code ('Code Injection') vulnerability in Mohammad I. Okfie IF AS Shortcode if-as-shortcode allows Code Injection.This issue affects IF AS Shortcode: from n/a through <= 1.2.

### CVE-2025-68929
**frappe frappe RCE**
- **Signals:** CVSS
- **Asset:** frappe frappe
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T20:02:50.403
- **CWE:** CWE-1336
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-12-29)

> Frappe is a full-stack web application framework. Prior to versions 14.99.6 and 15.88.1, an authenticated user with specific permissions could be tricked into accessing a specially crafted link. This could lead to a malicious template being executed on the server, resulting in re…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-29*
