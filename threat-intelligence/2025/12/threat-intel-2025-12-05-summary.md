# Daily Threat Intelligence — December 05, 2025

**Digest window (UTC):** 2025-12-05
**Generated:** 2026-06-02T07:33:55Z

## Threat brief

Meta React Server Components added to CISA KEV — confirmed in-the-wild exploitation. · WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Browsercrm — exploitation likelihood rose sharply (EPSS 21% → 68% · rising (+47%)). · 7 new critical disclosures — review patch status on exposed services.

## Executive summary

- Meta React Server Components added to CISA KEV — confirmed in-the-wild exploitation.
- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Browsercrm — exploitation likelihood rose sharply (EPSS 21% → 68% · rising (+47%)).
- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2025-55182
**Meta React Server Components Remote Code Execution Vulnerability**
- **Signals:** KEV
- **Asset:** facebook react
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T02:00:02.557
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2025-12-05

> A pre-authentication remote code execution vulnerability exists in React Server Components versions 19.0.0, 19.1.0, 19.1.1, and 19.2.0 including the following packages: react-server-dom-parcel, react-server-dom-turbopack, and react-server-dom-webpack. The vulnerable code unsafely…

### CVE-2008-2689
**browsercrm browsercrm**
- **Signals:** EPSS
- **Asset:** browsercrm browsercrm
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 21.2% (2025-11-07) → 68.0% (2025-12-05), Δ +46.8%**

> PHP remote file inclusion vulnerability in pub/clients.php in BrowserCRM 5.002.00 allows remote attackers to execute arbitrary PHP code via a URL in the bcrm_pub_root parameter.

### CVE-2025-66570
**yhirose cpp-httplib privilege escalation**
- **Signals:** CVSS
- **Asset:** yhirose cpp-httplib
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T15:02:46.533
- **CWE:** CWE-290
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-12-05)

> cpp-httplib is a C++11 single-file header-only cross platform HTTP/HTTPS library. Prior to 0.27.0, a vulnerability allows attacker-controlled HTTP headers to influence server-visible metadata, logging, and authorization decisions. An attacker can inject headers named REMOTE_ADDR,…

### CVE-2002-1452
**mywebserver mywebserver Buffer Overflow**
- **Signals:** EPSS
- **Asset:** mywebserver mywebserver
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 80
- **EPSS 5.6% (2025-03-30) → 16.3% (2025-12-05), Δ +10.7%**

> Buffer overflow in the search capability for MyWebServer 1.0.2 allows remote attackers to execute arbitrary code via a long searchTarget parameter.

### CVE-2020-36877
**ReQuest Serious Play F3 Media Server 7.0.3 contains an unauthenticated remote code execution vulnerability that allows attackers to execu...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-05)

> ReQuest Serious Play F3 Media Server 7.0.3 contains an unauthenticated remote code execution vulnerability that allows attackers to execute arbitrary commands as the web server user. Attackers can upload PHP executable files via the Quick File Uploader page, resulting in remote c…

### CVE-2020-9425
**rconfig rconfig**
- **Signals:** EPSS
- **Asset:** rconfig rconfig
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:40:36.720
- **CWE:** CWE-670
- **Risk score:** 82
- **EPSS 31.6% (2025-11-25) → 49.4% (2025-12-05), Δ +17.8%**

> An issue was discovered in includes/head.inc.php in rConfig before 3.9.4. An unauthenticated attacker can retrieve saved cleartext credentials via a GET request to settings.php. Because the application was not exiting after a redirect is applied, the rest of the page still execut…

### CVE-2025-12374
**The Email Verification, Email OTP, Block Spam Email, Passwordless login, Hide Login, Magic Login – User Verification plugin for WordPress...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-05)

> The Email Verification, Email OTP, Block Spam Email, Passwordless login, Hide Login, Magic Login – User Verification plugin for WordPress is vulnerable to authentication bypass in all versions up to, and including, 2.0.44. This is due to the plugin not properly validating that an…

### CVE-2025-13313
**The CRM Memberships plugin for WordPress is vulnerable to privilege escalation via password reset in all versions up to, and including, 2.6.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-05)

> The CRM Memberships plugin for WordPress is vulnerable to privilege escalation via password reset in all versions up to, and including, 2.6. This is due to missing authorization and authentication checks on the `ntzcrm_changepassword` AJAX action. This makes it possible for unaut…

### CVE-2025-34256
**advantech wise-deviceon_server**
- **Signals:** CVSS
- **Asset:** advantech wise-deviceon_server
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-15T19:16:32.673
- **CWE:** CWE-321
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-12-05)

> Advantech WISE-DeviceOn Server versions prior to 5.4 contain a hard-coded cryptographic key vulnerability. The product uses a static HS512 HMAC secret for signing EIRMMToken JWTs across all installations. The server accepts forged JWTs that need only contain a valid email claim, …

### CVE-2025-34291
**Langflow Origin Validation Error Vulnerability**
- **Signals:** CVSS
- **Asset:** langflow langflow
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2026-05-21T20:16:13.520
- **CWE:** CWE-346
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-12-05)

> Langflow versions up to and including 1.6.9 contain a chained vulnerability that enables account takeover and remote code execution. An overly permissive CORS configuration (allow_origins='*' with allow_credentials=True) combined with a refresh token cookie configured as SameSite…

### CVE-2025-64054
**fanvil x210_firmware DoS**
- **Signals:** CVSS
- **Asset:** fanvil x210_firmware
- **Attack:** DoS
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-09T02:17:20.193
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-12-05)

> A reflected Cross Site Scripting (XSS) vulnerability on Fanvil x210 2.12.20 devices allows attackers to cause a denial of service or potentially execute arbitrary commands via crafted POST request to the /cgi-bin/webconfig?page=upload&action=submit endpoint.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-05*
