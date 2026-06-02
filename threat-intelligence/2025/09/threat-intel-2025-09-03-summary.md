# Daily Threat Intelligence — September 03, 2025

**Digest window (UTC):** 2025-09-03
**Generated:** 2026-06-02T07:33:21Z

## Threat brief

TP-Link Multiple Routers: 2 CVEs added to CISA KEV today. · Microsoft Windows 10 — exploitation likelihood rose sharply (EPSS 41% → 57% · rising (+16%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- TP-Link Multiple Routers: 2 CVEs added to CISA KEV today.
- Microsoft Windows 10 — exploitation likelihood rose sharply (EPSS 41% → 57% · rising (+16%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2023-50224
**TP-Link TL-WR841N Authentication Bypass by Spoofing Vulnerability**
- **Signals:** KEV
- **Asset:** tp-link tl-wr841n_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:05:21.053
- **CWE:** CWE-290
- **Risk score:** 88
- **KEV:** added 2025-09-03

> TP-Link TL-WR841N dropbearpwd Improper Authentication Information Disclosure Vulnerability. This vulnerability allows network-adjacent attackers to disclose sensitive information on affected installations of TP-Link TL-WR841N routers. Authentication is not required to exploit thi…

### CVE-2019-0888
**microsoft windows_10 RCE**
- **Signals:** EPSS
- **Asset:** microsoft windows_10
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2025-05-20T18:15:29.123
- **Risk score:** 84
- **EPSS 40.6% (2025-05-21) → 57.1% (2025-09-03), Δ +16.4%**

> A remote code execution vulnerability exists in the way that ActiveX Data Objects (ADO) handle objects in memory. An attacker who successfully exploited the vulnerability could execute arbitrary code with the victim user’s privileges.
An attacker could craft a website that exploi…

### CVE-2024-32444
**inspirythemes realhomes Privilege Escalation**
- **Signals:** CVSS
- **Asset:** inspirythemes realhomes
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T15:18:15.717
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-03)

> Incorrect Privilege Assignment vulnerability in InspiryThemes RealHomes realhomes allows Privilege Escalation.This issue affects RealHomes: from n/a through <= 4.3.6.

### CVE-2024-43166
**apache dolphinscheduler**
- **Signals:** CVSS
- **Asset:** apache dolphinscheduler
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T22:16:03.300
- **CWE:** CWE-276
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-03)

> Incorrect Default Permissions vulnerability in Apache DolphinScheduler.

This issue affects Apache DolphinScheduler: before 3.2.2.

Users are recommended to upgrade to version 3.3.1, which fixes the issue.

### CVE-2025-1740
**Improper Restriction of Excessive Authentication Attempts vulnerability in Akinsoft MyRezzta allows Authentication Bypass, Password Recov...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-307
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-03)

> Improper Restriction of Excessive Authentication Attempts vulnerability in Akinsoft MyRezzta allows Authentication Bypass, Password Recovery Exploitation, Brute Force.This issue affects MyRezzta: from s2.03.01 before v2.05.01.

### CVE-2025-53690
**Sitecore Multiple Products Deserialization of Untrusted Data Vulnerability**
- **Signals:** CVSS
- **Asset:** sitecore experience_commerce
- **Attack:** Deserialization
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T20:39:16.593
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-09-03)

> Deserialization of Untrusted Data vulnerability in Sitecore Experience Manager (XM), Sitecore Experience Platform (XP) allows Code Injection.This issue affects Experience Manager (XM): through 9.0; Experience Platform (XP): through 9.0.

### CVE-2025-53693
**sitecore experience_commerce**
- **Signals:** CVSS
- **Asset:** sitecore experience_commerce
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-08T18:28:13.110
- **CWE:** CWE-470
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-03)

> Use of Externally-Controlled Input to Select Classes or Code ('Unsafe Reflection') vulnerability in Sitecore Sitecore Experience Manager (XM), Sitecore Experience Platform (XP) allows Cache Poisoning.This issue affects Sitecore Experience Manager (XM): from 9.0 through 9.3, from …

### CVE-2025-55747
**xwiki xwiki**
- **Signals:** CVSS
- **Asset:** xwiki xwiki
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-10T17:47:28.840
- **CWE:** CWE-23
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-03)

> XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. In versions  6.1-milestone-2 through 16.10.6, configuration files are accessible through the webjars API. This is fixed in version 16.10.7.

### CVE-2025-55748
**xwiki xwiki**
- **Signals:** CVSS
- **Asset:** xwiki xwiki
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-10T17:24:13.273
- **CWE:** CWE-23
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-03)

> XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. In versions 4.2-milestone-2 through 16.10.6, configuration files are accessible through jsx and sx endpoints. It's possible to access and read configuration files by using URL…

### CVE-2025-56752
**ruijie rg-es205gc-p_firmware**
- **Signals:** CVSS
- **Asset:** ruijie rg-es228gs-p_firmware
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-29T18:36:43.327
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-09-03)

> A vulnerability in the Ruijie RG-ES series switch firmware ESW_1.0(1)B1P39 enables remote attackers to fully bypass authentication mechanisms, providing them with unrestricted access to alter administrative settings and potentially seize control of affected devices via crafted HT…

### CVE-2025-57052
**davegamble cjson Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** davegamble cjson
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T19:16:12.460
- **CWE:** CWE-125
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-03)

> cJSON 1.5.0 through 1.7.18 allows out-of-bounds access via the decode_array_index_from_pointer function in cJSON_Utils.c, allowing remote attackers to bypass array bounds checking and access restricted data via malformed JSON pointer strings containing alphanumeric characters.

### CVE-2025-57148
**phpgurukul online_shopping_portal**
- **Signals:** CVSS
- **Asset:** phpgurukul online_shopping_portal
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-06T15:17:06.043
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-03)

> phpgurukul Online Shopping Portal 2.0 is vulnerable to Arbitrary File Upload in /admin/insert-product.php, due to the lack of extension validation.

### CVE-2025-9377
**TP-Link Archer C7(EU) and TL-WR841N/ND(MS) OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** tp-link tl-wr841n_firmware
- **Attack:** Command Injection
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-03T18:55:06.440
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2025-09-03

> The authenticated remote command execution (RCE) vulnerability exists  in the Parental Control page on TP-Link Archer C7(EU) V2 and TL-WR841N/ND(MS) V9.

This issue affects Archer C7(EU) V2: before 241108 and TL-WR841N/ND(MS) V9: before 241108.

Both products have reached the sta…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-03*
