# Daily Threat Intelligence — December 22, 2025

**Digest window (UTC):** 2025-12-22
**Generated:** 2026-06-02T07:34:01Z

## Threat brief

Digiever DS-2105 Pro added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Digiever DS-2105 Pro added to CISA KEV — confirmed in-the-wild exploitation.
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

### CVE-2023-52163
**Digiever DS-2105 Pro Missing Authorization Vulnerability**
- **Signals:** KEV
- **Asset:** digiever ds-2105_pro_firmware
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-24T11:36:59.630
- **CWE:** CWE-862
- **Risk score:** 88
- **KEV:** added 2025-12-22

> Digiever DS-2105 Pro 3.1.0.71-11 devices allow time_tzsetup.cgi Command Injection. NOTE: This vulnerability only affects products that are no longer supported by the maintainer.

### CVE-2025-65856
**xiongmaitech xm530v200_x6-weq_8m_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** xiongmaitech xm530v200_x6-weq_8m_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-05T18:28:47.093
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-22)

> Authentication bypass vulnerability in Xiongmai XM530 IP cameras on Firmware V5.00.R02.000807D8.10010.346624.S.ONVIF 21.06 allows unauthenticated remote attackers to access sensitive device information and live video streams. The ONVIF implementation fails to enforce authenticati…

### CVE-2023-53955
**sound4 big_voice2_firmware privilege escalation**
- **Signals:** CVSS
- **Asset:** sound4 impact_firmware
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-13T18:23:14.093
- **CWE:** CWE-639
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-22)

> SOUND4 IMPACT/FIRST/PULSE/Eco v2.x contains an insecure direct object reference vulnerability that allows attackers to bypass authorization and access hidden system resources. Attackers can exploit the vulnerability by manipulating user-supplied input to execute privileged functi…

### CVE-2023-53960
**sound4 big_voice2_firmware SQL Injection**
- **Signals:** CVSS
- **Asset:** sound4 first_firmware
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-16T19:16:13.373
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-22)

> SOUND4 IMPACT/FIRST/PULSE/Eco version 2.x contains an SQL injection vulnerability in the 'index.php' authentication mechanism that allows attackers to manipulate login credentials. Attackers can inject malicious SQL code through the 'password' POST parameter to bypass authenticat…

### CVE-2023-53963
**sound4 big_voice2_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** sound4 impact_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-13T15:42:50.763
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-22)

> SOUND4 IMPACT/FIRST/PULSE/Eco v2.x contains an unauthenticated OS command injection vulnerability that allows remote attackers to execute arbitrary shell commands through the 'password' parameter. Attackers can exploit the login.php and index.php scripts by injecting shell comman…

### CVE-2023-53966
**sound4 linkandshare_transmitter**
- **Signals:** CVSS
- **Asset:** sound4 linkandshare_transmitter
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T17:12:25.897
- **CWE:** CWE-134
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-22)

> SOUND4 LinkAndShare Transmitter 1.1.2 contains a format string vulnerability that allows attackers to trigger memory stack overflows through maliciously crafted environment variables. Attackers can manipulate the username environment variable with format string payloads to potent…

### CVE-2023-53967
**dbbroadcast sft_dab_600\/c_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** dbbroadcast sft_dab_600\/c_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-26T16:50:44.873
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-22)

> Screen SFT DAB 600/C firmware 1.9.3 contains an authentication bypass vulnerability that allows attackers to change the admin password without requiring the current credentials. Attackers can exploit the userManager.cgx API endpoint by sending a crafted POST request with a new MD…

### CVE-2023-53968
**dbbroadcast sft_dab_600\/c_firmware**
- **Signals:** CVSS
- **Asset:** dbbroadcast sft_dab_600\/c_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-26T16:45:48.437
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-22)

> Screen SFT DAB 600/C Firmware 1.9.3 contains a session management vulnerability that allows attackers to bypass authentication controls by exploiting IP address session binding. Attackers can reuse the same IP address and issue unauthorized requests to the userManager API to remo…

### CVE-2023-53969
**dbbroadcast sft_dab_600\/c_firmware**
- **Signals:** CVSS
- **Asset:** dbbroadcast sft_dab_600\/c_firmware
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-26T16:50:55.857
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-22)

> Screen SFT DAB 600/C firmware 1.9.3 contains a session management vulnerability that allows attackers to bypass authentication controls by exploiting IP address session binding. Attackers can reuse the same IP address and issue unauthorized requests to the userManager API to chan…

### CVE-2023-53972
**webtareas_project webtareas SQL Injection**
- **Signals:** CVSS
- **Asset:** webtareas_project webtareas
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2025-12-27T17:15:45.230
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-22)

> WebTareas 2.4 contains a SQL injection vulnerability in the webTareasSID cookie parameter that allows unauthenticated attackers to manipulate database queries. Attackers can exploit error-based and time-based blind SQL injection techniques to extract database information and pote…

### CVE-2023-53975
**thedigitalcraft atomcms SQL Injection**
- **Signals:** CVSS
- **Asset:** thedigitalcraft atomcms
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-01-05T14:15:52.800
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-22)

> Atom CMS 2.0 contains an unauthenticated SQL injection vulnerability that allows remote attackers to manipulate database queries through unvalidated parameters. Attackers can inject malicious SQL code in the 'id' parameter of the admin index page to execute time-based blind SQL i…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-22*
