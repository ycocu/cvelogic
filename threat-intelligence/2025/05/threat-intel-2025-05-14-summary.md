# Daily Threat Intelligence — May 14, 2025

**Digest window (UTC):** 2025-05-14
**Generated:** 2026-06-02T07:32:43Z

## Threat brief

Fortinet Multiple Products added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Fortinet Multiple Products added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2025-32756
**Fortinet Multiple Products Stack-Based Buffer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** fortinet fortimail
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-14T19:18:55.170
- **CWE:** CWE-121
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2025-05-14

> A stack-based buffer overflow vulnerability [CWE-121] vulnerability in Fortinet FortiCamera 2.1.0 through 2.1.3, FortiCamera 2.0 all versions, FortiCamera 1.1 all versions, FortiMail 7.6.0 through 7.6.2, FortiMail 7.4.0 through 7.4.4, FortiMail 7.2.0 through 7.2.7, FortiMail 7.0.…

### CVE-2025-47781
**rallly rallly**
- **Signals:** CVSS
- **Asset:** rallly rallly
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T22:04:15.023
- **CWE:** CWE-331
- **CWE:** CWE-331
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-14)

> Rallly is an open-source scheduling and collaboration tool. Versions up to and including 3.22.1 of the application features token based authentication. When a user attempts to login to the application, they insert their email and a 6 digit code is sent to their email address to c…

### CVE-2025-47889
**jenkins wso2_oauth**
- **Signals:** CVSS
- **Asset:** jenkins wso2_oauth
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-12T13:23:31.790
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-14)

> In Jenkins WSO2 Oauth Plugin 1.0 and earlier, authentication claims are accepted without validation by the "WSO2 Oauth" security realm, allowing unauthenticated attackers to log in to controllers using this security realm using any username and any password, including usernames t…

### CVE-2024-10865
**Improper Input validation leads to XSS or Cross-site Scripting vulnerability in OpenText Advanced Authentication.**
- **Signals:** CVSS
- **Attack:** XSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-05-14)

> Improper Input validation leads to XSS or Cross-site Scripting vulnerability in OpenText Advanced Authentication. This issue affects Advanced Authentication versions before 6.5.

### CVE-2025-27891
**samsung exynos_1080_firmware Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** samsung exynos_980_firmware
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-01T15:00:09.410
- **CWE:** CWE-125
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-14)

> An issue was discovered in Samsung Mobile Processor, Wearable Processor, and Modem Exynos 980, 990, 850, 1080, 2100, 1280, 2200, 1330, 1380, 1480, 2400, W920, W930, W1000, Modem 5123, Modem 5300, Modem 5400. The lack of a length check leads to out-of-bounds reads via malformed NA…

### CVE-2025-32363
**mediDOK before 2.5.18.43 allows remote attackers to achieve remote code execution on a target system via deserialization of untrusted data.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-14)

> mediDOK before 2.5.18.43 allows remote attackers to achieve remote code execution on a target system via deserialization of untrusted data.

### CVE-2025-4638
**pointclouds point_cloud_library**
- **Signals:** CVSS
- **Asset:** pointclouds point_cloud_library
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-21T14:10:50.760
- **CWE:** CWE-119
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-05-14)

> A vulnerability exists in the inftrees.c component of the zlib library, which is bundled within the PointCloudLibrary (PCL). This issue may allow context-dependent attackers to cause undefined behavior by exploiting improper pointer arithmetic.

Since version 1.14.0, PCL by defau…

### CVE-2025-4641
**Improper Restriction of XML External Entity Reference vulnerability in bonigarcia webdrivermanager WebDriverManager on Windows, MacOS, Li...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-611
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-14)

> Improper Restriction of XML External Entity Reference vulnerability in bonigarcia webdrivermanager WebDriverManager on Windows, MacOS, Linux (XML parsing components modules) allows Data Serialization External Entities Blowup. This vulnerability is associated with program files sr…

### CVE-2025-47292
**Cap Collectif is an online decision making platform that integrates several tools.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-05-14)

> Cap Collectif is an online decision making platform that integrates several tools. Before commit 812f2a7d271b76deab1175bdaf2be0b8102dd198, the `DebateAlternateArgumentsResolver` deserializes a `Cursor`, allowing any classes and which can be controlled by unauthenticated user. Exp…

### CVE-2025-47777
**5ire 5ire RCE**
- **Signals:** CVSS
- **Asset:** 5ire 5ire
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-22T21:26:26.727
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-05-14)

> 5ire is a cross-platform desktop artificial intelligence assistant and model context protocol client. Versions prior to 0.11.1 are vulnerable to stored cross-site scripting in chatbot responses due to insufficient sanitization. This, in turn, can lead to Remote Code Execution (RC…

### CVE-2025-47884
**jenkins openid_connect_provider**
- **Signals:** CVSS
- **Asset:** jenkins openid_connect_provider
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-12T13:48:38.967
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-14)

> In Jenkins OpenID Connect Provider Plugin 96.vee8ed882ec4d and earlier the generation of build ID Tokens uses potentially overridden values of environment variables, in conjunction with certain other plugins allowing attackers able to configure jobs to craft a build ID Token that…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-14*
