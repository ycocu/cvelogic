# Daily Threat Intelligence — May 08, 2025

**Digest window (UTC):** 2025-05-08
**Generated:** 2026-06-02T07:32:41Z

## Threat brief

10 new critical disclosures — review patch status on exposed services.

## Executive summary

- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-29813
**microsoft azure_devops Auth Bypass**
- **Signals:** CVSS
- **Asset:** microsoft azure_devops
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-02-13T20:17:05.733
- **CWE:** CWE-302
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-08)

> Authentication bypass by assumed-immutable data in Azure DevOps allows an unauthorized attacker to elevate privileges over a network.

### CVE-2025-29827
**microsoft azure_automation privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_automation
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-05T14:28:24.673
- **CWE:** CWE-285
- **CWE:** CWE-863
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-05-08)

> Improper authorization in Azure Automation allows an authorized attacker to elevate privileges over a network.

### CVE-2025-29972
**microsoft azure_storage_resource_provider SSRF**
- **Signals:** CVSS
- **Asset:** microsoft azure_storage_resource_provider
- **Attack:** SSRF
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2026-02-13T20:17:11.060
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-05-08)

> Server-side request forgery (ssrf) in Azure Storage Resource Provider allows an authorized attacker to perform spoofing over a network.

### CVE-2023-31585
**Grocery-CMS-PHP-Restful-API v1.3 is vulnerable to File Upload via /admin/add-category.php.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-08)

> Grocery-CMS-PHP-Restful-API v1.3 is vulnerable to File Upload via /admin/add-category.php.

### CVE-2025-27720
**The Pixmeo Osirix MD Web Portal sends credential information without encryption, which could allow an attacker to steal credentials.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-319
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-08)

> The Pixmeo Osirix MD Web Portal sends credential information without encryption, which could allow an attacker to steal credentials.

### CVE-2025-45789
**totolink a3100r_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** totolink a3100r_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-16T15:38:07.317
- **CWE:** CWE-787
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-08)

> TOTOLINK A3100R V5.9c.1527 is vulnerable to buffer overflow via the urlKeyword parameter in setParentalRules.

### CVE-2025-45790
**totolink a3100r_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** totolink a3100r_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-16T15:36:52.570
- **CWE:** CWE-787
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-08)

> TOTOLINK A3100R V5.9c.1527 is vulnerable to Buffer Overflow via the priority parameter in the setMacQos interface of /lib/cste_modules/firewall.so.

### CVE-2025-45797
**totolink a950rg_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** totolink a950rg_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-16T15:36:45.023
- **CWE:** CWE-787
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-08)

> TOTOlink A950RG V4.1.2cu.5204_B20210112 contains a buffer overflow vulnerability. The vulnerability arises from the improper input validation of the NoticeUrl parameter in the setNoticeCfg interface of /lib/cste_modules/system.so.

### CVE-2025-45798
**totolink a950rg_firmware**
- **Signals:** CVSS
- **Asset:** totolink a950rg_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-19T15:08:18.653
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-08)

> A command execution vulnerability exists in the TOTOLINK A950RG V4.1.2cu.5204_B20210112. The vulnerability is located in the setNoticeCfg interface within the /lib/cste_modules/system.so library, specifically in the processing of the IpTo parameter.

### CVE-2025-47733
**microsoft power_apps SSRF**
- **Signals:** CVSS
- **Asset:** microsoft power_apps
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-21T14:43:14.013
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-08)

> Server-Side Request Forgery (SSRF) in Microsoft Power Apps allows an unauthorized attacker to disclose information over a network

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-08*
