# Daily Threat Intelligence — June 16, 2025

**Digest window (UTC):** 2025-06-16
**Generated:** 2026-06-02T07:32:53Z

## Threat brief

Apple Multiple Products added to CISA KEV — confirmed in-the-wild exploitation. · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apple Multiple Products added to CISA KEV — confirmed in-the-wild exploitation.
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2023-33538
**TP-Link Multiple Routers Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** tp-link tl-wr940n_firmware
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T14:32:16.313
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 88
- **KEV:** added 2025-06-16

> TP-Link TL-WR940N V2/V4, TL-WR841N V8/V10, and TL-WR740N V1/V2 was discovered to contain a command injection vulnerability via the component /userRpm/WlanNetworkRpm .

### CVE-2025-47868
**apache nuttx Buffer Overflow**
- **Signals:** CVSS
- **Asset:** apache nuttx
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-17T19:38:08.090
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-16)

> Out-of-bounds Write resulting in possible Heap-based Buffer Overflow vulnerability was discovered in tools/bdf-converter font conversion utility that is part of Apache NuttX RTOS repository. This standalone program is optional and neither part of NuttX RTOS nor Applications runti…

### CVE-2025-47869
**apache nuttx Buffer Overflow**
- **Signals:** CVSS
- **Asset:** apache nuttx
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-17T19:37:52.710
- **CWE:** CWE-119
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-16)

> Improper Restriction of Operations within the Bounds of a Memory Buffer vulnerability was discovered in Apache NuttX RTOS apps/exapmles/xmlrpc application. In this example application device stats structure that stored remotely provided parameters had hardcoded buffer size which …

### CVE-2025-40916
**Mojolicious::Plugin::CaptchaPNG version 1.05 for Perl uses a weak random number source for generating the captcha.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-338
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-16)

> Mojolicious::Plugin::CaptchaPNG version 1.05 for Perl uses a weak random number source for generating the captcha.

That version uses the built-in rand() function for generating the captcha text as well as image noise, which is insecure.

### CVE-2025-43200
**Apple Multiple Products Unspecified Vulnerability**
- **Signals:** KEV
- **Asset:** apple ipados
- **CVSS max:** 4.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T14:29:07.400
- **Risk score:** 88
- **KEV:** added 2025-06-16

> This issue was addressed with improved checks. This issue is fixed in iOS 15.8.4 and iPadOS 15.8.4, iOS 16.7.11 and iPadOS 16.7.11, iOS 18.3.1 and iPadOS 18.3.1, iPadOS 17.7.5, macOS Sequoia 15.3.1, macOS Sonoma 14.7.4, macOS Ventura 13.7.4, visionOS 2.3.1, watchOS 11.3.1. A logi…

### CVE-2025-49794
**A use-after-free vulnerability was found in libxml2.**
- **Signals:** CVSS
- **Attack:** Use-After-Free
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T13:17:20.283
- **CWE:** CWE-825
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-16)

> A use-after-free vulnerability was found in libxml2. This issue occurs when parsing XPath elements under certain circumstances when the XML schematron has the <sch:name path="..."/> schema elements. This flaw allows a malicious actor to craft a malicious XML document used as inpu…

### CVE-2025-49796
**A vulnerability was found in libxml2.**
- **Signals:** CVSS
- **Attack:** DoS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T13:17:20.660
- **CWE:** CWE-125
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-16)

> A vulnerability was found in libxml2. Processing certain sch:name elements from the input XML file can trigger a memory corruption issue. This flaw allows an attacker to craft a malicious XML input file that can lead libxml to crash, resulting in a denial of service or other poss…

### CVE-2025-6169
**The WIMP website co-construction management platform from HAMASTAR Technology has a SQL Injection vulnerability, allowing unauthenticated...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-16)

> The WIMP website co-construction management platform from HAMASTAR Technology has a SQL Injection vulnerability, allowing unauthenticated remote attackers to inject arbitrary SQL commands to read, modify, and delete database contents.

### CVE-2025-6172
**Permission vulnerability in the mobile application (com.afmobi.boomplayer) may lead to the risk of unauthorized operation.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-16)

> Permission vulnerability in the mobile application (com.afmobi.boomplayer) may lead to the risk of unauthorized operation.

### CVE-2025-6179
**google chrome_os**
- **Signals:** CVSS
- **Asset:** google chrome_os
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-02T18:23:31.617
- **CWE:** CWE-276
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-16)

> Permissions Bypass in Extension Management in Google ChromeOS         16181.27.0 on managed Chrome devices allows a local attacker to disable extensions and access Developer Mode, including loading additional extensions via exploiting vulnerabilities using the ExtHang3r and ExtPr…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-16*
