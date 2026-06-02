# Daily Threat Intelligence — January 13, 2026

**Digest window (UTC):** 2026-01-13
**Generated:** 2026-06-02T07:34:11Z

## Threat brief

Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation. · Sonicwall Sma 200 Firmware — exploitation likelihood rose sharply (EPSS 0.5% → 29% · rising (+29%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation.
- Sonicwall Sma 200 Firmware — exploitation likelihood rose sharply (EPSS 0.5% → 29% · rising (+29%)).
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

### CVE-2026-20805
**Microsoft Windows Information Disclosure Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1607
- **Attack:** Info Disclosure
- **CVSS max:** 5.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-14T13:44:31.180
- **CWE:** CWE-200
- **Risk score:** 88
- **KEV:** added 2026-01-13

> Exposure of sensitive information to an unauthorized actor in Desktop Windows Manager allows an authorized attacker to disclose information locally.

### CVE-2024-53703
**sonicwall sma_200_firmware Code Execution**
- **Signals:** EPSS
- **Asset:** sonicwall sma_200_firmware
- **Attack:** Code Execution
- **CVSS max:** 8.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-04T17:15:33.343
- **CWE:** CWE-121
- **Risk score:** 83
- **EPSS 0.5% (2025-11-21) → 29.1% (2026-01-13), Δ +28.7%**

> A vulnerability in the SonicWall SMA100 SSLVPN firmware 10.2.1.13-72sv and earlier versions mod_httprp library loaded by the Apache web server allows remote attackers to cause Stack-based buffer overflow and potentially lead to code execution.

### CVE-2026-23478
**cal cal.com**
- **Signals:** CVSS
- **Asset:** cal cal.com
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T19:29:07.787
- **CWE:** CWE-602
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-13)

> Cal.com is open-source scheduling software. From 3.1.6 to before 6.0.7, there is a vulnerability in a custom NextAuth JWT callback that allows attackers to gain full authenticated access to any user's account by supplying a target email address via session.update(). This vulnerab…

### CVE-2002-0682
**apache tomcat XSS**
- **Signals:** EPSS
- **Asset:** apache tomcat
- **Attack:** XSS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 66.6% (2025-07-27) → 83.1% (2026-01-13), Δ +16.5%**

> Cross-site scripting vulnerability in Apache Tomcat 4.0.3 allows remote attackers to execute script as other web users via script in a URL with the /servlet/ mapping, which does not filter the script when an exception is thrown by the servlet.

### CVE-2014-6041
**google android_browser**
- **Signals:** EPSS
- **Asset:** google android_browser
- **CVSS max:** 5.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-264
- **Risk score:** 80
- **EPSS 61.2% (2025-11-20) → 77.6% (2026-01-13), Δ +16.4%**

> The Android WebView in Android before 4.4 allows remote attackers to bypass the Same Origin Policy via a crafted attribute containing a \u0000 character, as demonstrated by an onclick="window.open('\u0000javascript: sequence to the Android Browser application 4.2.1 or a third-par…

### CVE-2017-2479
**apple icloud**
- **Signals:** EPSS
- **Asset:** apple safari
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-20
- **Risk score:** 81
- **EPSS 8.8% (2025-12-10) → 24.7% (2026-01-13), Δ +15.9%**

> An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. iCloud before 6.2 on Windows is affected. iTunes before 12.6 on Windows is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows …

### CVE-2020-36911
**cobbr covenant RCE**
- **Signals:** CVSS
- **Asset:** cobbr covenant
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T00:56:25.460
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-13)

> Covenant 0.1.3 - 0.5 contains a remote code execution vulnerability that allows attackers to craft malicious JWT tokens with administrative privileges. Attackers can generate forged tokens with admin roles and upload custom DLL payloads to execute arbitrary commands on the target…

### CVE-2022-46598
**trendnet tew-755ap_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** trendnet tew-755ap_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-11T17:15:38.053
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 5.2% (2026-01-01) → 16.6% (2026-01-13), Δ +11.4%**

> TRENDnet TEW755AP 1.13B01 was discovered to contain a command injection vulnerability via the wps_sta_enrollee_pin parameter in the action set_sta_enrollee_pin_5g function.

### CVE-2022-50893
**viaviweb wallpaper_admin RCE**
- **Signals:** CVSS
- **Asset:** viaviweb wallpaper_admin
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-22T20:13:41.477
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-13)

> VIAVIWEB Wallpaper Admin 1.0 contains an unauthenticated remote code execution vulnerability in the image upload functionality. Attackers can upload a malicious PHP file through the add_gallery_image.php endpoint to execute arbitrary code on the server.

### CVE-2022-50905
**e107 e107 XSS**
- **Signals:** CVSS
- **Asset:** e107 e107
- **Attack:** XSS
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-21T15:16:05.383
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-13)

> e107 CMS version 3.2.1 contains multiple vulnerabilities that allow cross-site scripting (XSS) attacks. The first vulnerability is a reflected XSS that occurs in the news comment functionality when authenticated users interact with the comment form. An attacker can inject malicio…

### CVE-2022-50912
**impresscms impresscms**
- **Signals:** CVSS
- **Asset:** impresscms impresscms
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T19:26:43.090
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-13)

> ImpressCMS 1.4.4 contains a file upload vulnerability with weak extension sanitization that allows attackers to upload potentially malicious files. Attackers can bypass file upload restrictions by using alternative file extensions .php2.php6.php7.phps.pht to execute arbitrary PHP…

### CVE-2022-50919
**tdarr tdarr RCE**
- **Signals:** CVSS
- **Asset:** tdarr tdarr
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T18:54:53.383
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-13)

> Tdarr 2.00.15 contains an unauthenticated remote code execution vulnerability in its Help terminal that allows attackers to inject and chain arbitrary commands. Attackers can exploit the lack of input filtering by chaining commands like `--help; curl .py | python` to execute remo…

### CVE-2023-54329
**inbit inbit_messenger privilege escalation**
- **Signals:** CVSS
- **Asset:** inbit inbit_messenger
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T15:47:32.033
- **CWE:** CWE-121
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-13)

> Inbit Messenger 4.6.0 - 4.9.0 contains a remote command execution vulnerability that allows unauthenticated attackers to execute arbitrary commands by exploiting a stack overflow in the messenger's protocol. Attackers can send specially crafted XML packets to port 10883 with a ma…

### CVE-2023-54330
**inbit inbit_messenger Buffer Overflow**
- **Signals:** CVSS
- **Asset:** inbit inbit_messenger
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T15:48:11.273
- **CWE:** CWE-121
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-13)

> Inbit Messenger versions 4.6.0 to 4.9.0 contain a remote stack-based buffer overflow vulnerability that allows unauthenticated attackers to execute arbitrary code by sending malformed network packets. Attackers can craft a specially designed payload targeting the messenger's netw…

### CVE-2023-54335
**extplorer extplorer Auth Bypass**
- **Signals:** CVSS
- **Asset:** extplorer extplorer
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T19:25:21.073
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-13)

> eXtplorer 2.1.14 contains an authentication bypass vulnerability that allows attackers to login without a password by manipulating the login request. Attackers can exploit this flaw to upload malicious PHP files and execute remote commands on the vulnerable file management system…

### CVE-2023-54339
**webgrind_project webgrind**
- **Signals:** CVSS
- **Asset:** webgrind_project webgrind
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T19:21:26.087
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-13)

> Webgrind 1.1 contains a remote command execution vulnerability that allows unauthenticated attackers to inject OS commands via the dataFile parameter in index.php. Attackers can execute arbitrary system commands by manipulating the dataFile parameter, such as using payload '0%27%…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-13*
