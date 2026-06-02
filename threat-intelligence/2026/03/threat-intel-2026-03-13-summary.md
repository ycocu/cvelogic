# Daily Threat Intelligence — March 13, 2026

**Digest window (UTC):** 2026-03-13
**Generated:** 2026-06-02T07:34:38Z

## Threat brief

Google Skia: 2 CVEs added to CISA KEV today. · Gaztek Ghttp — exploitation likelihood rose sharply (EPSS 12% → 31% · rising (+19%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Google Skia: 2 CVEs added to CISA KEV today.
- Gaztek Ghttp — exploitation likelihood rose sharply (EPSS 12% → 31% · rising (+19%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2026-3909
**Google Skia Out-of-Bounds Write Vulnerability**
- **Signals:** KEV
- **Asset:** google chrome
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-25T14:05:38.743
- **CWE:** CWE-787
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2026-03-13

> Out of bounds write in Skia in Google Chrome prior to 146.0.7680.75 allowed a remote attacker to perform out of bounds memory access via a crafted HTML page. (Chromium security severity: High)

### CVE-2001-0820
**gaztek ghttp Buffer Overflow**
- **Signals:** EPSS
- **Asset:** gaztek ghttp
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 12.3% (2025-07-01) → 31.3% (2026-03-13), Δ +18.9%**

> Buffer overflows in GazTek ghttpd 1.4 allows a remote attacker to execute arbitrary code via long arguments that are passed to (1) the Log function in util.c, or (2) serveconnection in protocol.c.

### CVE-2026-26954
**nyariv sandboxjs**
- **Signals:** CVSS
- **Asset:** nyariv sandboxjs
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-17T20:13:06.470
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-03-13)

> SandboxJS is a JavaScript sandboxing library. Prior to 0.8.34, it is possible to obtain arrays containing Function, which allows escaping the sandbox. Given an array containing Function, and Object.fromEntries, it is possible to construct {[p]: Function} where p is any constructi…

### CVE-2003-1396
**opera opera_browser Buffer Overflow**
- **Signals:** EPSS
- **Asset:** opera opera_browser
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-787
- **Risk score:** 80
- **EPSS 4.2% (2025-11-13) → 15.6% (2026-03-13), Δ +11.4%**

> Heap-based buffer overflow in Opera 6.05 through 7.10 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a filename with a long extension.

### CVE-2017-8869
**mediacoder mediacoder Buffer Overflow**
- **Signals:** EPSS
- **Asset:** mediacoder mediacoder
- **Attack:** Buffer Overflow
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 22.9% (2025-11-21) → 35.4% (2026-03-13), Δ +12.4%**

> Buffer overflow in MediaCoder 0.8.48.5888 allows remote attackers to execute arbitrary code via a crafted .m3u file.

### CVE-2019-19245
**napc xinet_elegant_6_asset_library SQL Injection**
- **Signals:** EPSS
- **Asset:** napc xinet_elegant_6_asset_library
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-02-02T10:15:28.720
- **CWE:** CWE-89
- **Risk score:** 84
- **EPSS 9.7% (2025-11-21) → 21.1% (2026-03-13), Δ +11.4%**

> NAPC Xinet Elegant 6 Asset Library 6.1.655 allows Pre-Authentication SQL Injection via the /elegant6/login LoginForm[username] field when double quotes are used.

### CVE-2026-25823
**HMS Networks Ewon Flexy with firmware before 15.0s4, Cosy+ with firmware 22.xx before 22.1s6, and Cosy+ with firmware 23.xx before 23.0s3...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-27T19:18:46.690
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-13)

> HMS Networks Ewon Flexy with firmware before 15.0s4, Cosy+ with firmware 22.xx before 22.1s6, and Cosy+ with firmware 23.xx before 23.0s3 have a stack buffer overflow that leads to a Denial of Service, which can also be exploited to achieve Unauthenticated Remote Code Execution.

### CVE-2026-31806
**freerdp freerdp**
- **Signals:** CVSS
- **Asset:** freerdp freerdp
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-17T14:27:20.100
- **CWE:** CWE-122
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-13)

> FreeRDP is a free implementation of the Remote Desktop Protocol. Prior to 3.24.0,  the gdi_surface_bits() function processes SURFACE_BITS_COMMAND messages sent by the RDP server. When the command is handled using NSCodec, the bmp.width and bmp.height values provided by the server…

### CVE-2026-31886
**dagu dagu**
- **Signals:** CVSS
- **Asset:** dagu dagu
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-18T15:24:15.453
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-13)

> Dagu is a workflow engine with a built-in Web user interface. Prior to 2.2.4, the dagRunId request field accepted by the inline DAG execution endpoints is passed directly into filepath.Join to construct a temporary directory path without any format validation. Go's filepath.Join …

### CVE-2026-32301
**centrifugal centrifugo SSRF**
- **Signals:** CVSS
- **Asset:** centrifugal centrifugo
- **Attack:** SSRF
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-18T18:02:29.327
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-13)

> Centrifugo is an open-source scalable real-time messaging server. Prior to 6.7.0, Centrifugo is vulnerable to Server-Side Request Forgery (SSRF) when configured with a dynamic JWKS endpoint URL using template variables (e.g. {{tenant}}). An unauthenticated attacker can craft a JW…

### CVE-2026-32304
**locutus locutus RCE**
- **Signals:** CVSS
- **Asset:** locutus locutus
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-19T13:48:33.690
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-13)

> Locutus brings stdlibs of other programming languages to JavaScript for educational purposes. Prior to 3.0.14, the create_function(args, code) function passes both parameters directly to the Function constructor without any sanitization, allowing arbitrary code execution. This is…

### CVE-2026-32306
**hackerbay oneuptime SQL injection**
- **Signals:** CVSS
- **Asset:** hackerbay oneuptime
- **Attack:** SQL injection
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-17T20:08:56.733
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-13)

> OneUptime is a solution for monitoring and managing online services. Prior to 10.0.23, the telemetry aggregation API accepts user-controlled aggregationType, aggregateColumnName, and aggregationTimestampColumnName parameters and interpolates them directly into ClickHouse SQL quer…

### CVE-2026-32367
**Improper Control of Generation of Code ('Code Injection') vulnerability in Yannick Lefebvre Modal Dialog modal-dialog allows Remote Code...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-22T21:30:26.497
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-13)

> Improper Control of Generation of Code ('Code Injection') vulnerability in Yannick Lefebvre Modal Dialog modal-dialog allows Remote Code Inclusion.This issue affects Modal Dialog: from n/a through <= 3.5.16.

### CVE-2026-32746
**gnu inetutils Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** gnu inetutils
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-05T18:15:51.730
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-13)

> telnetd in GNU inetutils through 2.7 allows an out-of-bounds write in the LINEMODE SLC (Set Local Characters) suboption handler because add_slc does not check whether the buffer is full.

### CVE-2026-3891
**The Pix for WooCommerce plugin for WordPress is vulnerable to arbitrary file uploads due to missing capability check and missing file typ...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-22T21:30:26.497
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-13)

> The Pix for WooCommerce plugin for WordPress is vulnerable to arbitrary file uploads due to missing capability check and missing file type validation in the 'lkn_pix_for_woocommerce_c6_save_settings' function in all versions up to, and including, 1.5.0. This makes it possible for…

### CVE-2026-3910
**Google Chromium V8 Improper Restriction of Operations Within the Bounds of a Memory Buffer Vulnerability**
- **Signals:** KEV
- **Asset:** google chrome
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T22:00:01.403
- **CWE:** CWE-94
- **CWE:** CWE-119
- **Risk score:** 88
- **KEV:** added 2026-03-13

> Inappropriate implementation in V8 in Google Chrome prior to 146.0.7680.75 allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page. (Chromium security severity: High)

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-13*
