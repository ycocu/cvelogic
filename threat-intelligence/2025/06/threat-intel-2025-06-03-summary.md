# Daily Threat Intelligence — June 03, 2025

**Digest window (UTC):** 2025-06-03
**Generated:** 2026-06-02T07:32:49Z

## Threat brief

Qualcomm Multiple Chipsets: 3 CVEs added to CISA KEV today. · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Qualcomm Multiple Chipsets: 3 CVEs added to CISA KEV today.
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 3 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2025-21479
**Qualcomm Multiple Chipsets Incorrect Authorization Vulnerability**
- **Signals:** KEV
- **Asset:** qualcomm aqt1000_firmware
- **Attack:** Memory Corruption
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T13:48:16.837
- **CWE:** CWE-863
- **Risk score:** 88
- **KEV:** added 2025-06-03

> Memory corruption due to unauthorized command execution in GPU micronode while executing specific sequence of commands.

### CVE-2025-45854
**jehc jehc-bpm**
- **Signals:** CVSS
- **Asset:** jehc jehc-bpm
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2025-08-26T19:15:40.573
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-03)

> /server/executeExec of JEHC-BPM 2.0.1 allows attackers to execute arbitrary code via execParams.

### CVE-2025-32105
**sangoma img2020_firmware RCE**
- **Signals:** CVSS
- **Asset:** sangoma img2020_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-06-18T14:15:43.590
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-03)

> A buffer overflow in the the Sangoma IMG2020 HTTP server through 2.3.9.6 allows an unauthenticated user to achieve remote code execution.

### CVE-2025-21480
**Qualcomm Multiple Chipsets Incorrect Authorization Vulnerability**
- **Signals:** KEV
- **Asset:** qualcomm aqt1000_firmware
- **Attack:** Memory Corruption
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T13:48:12.673
- **CWE:** CWE-863
- **Risk score:** 88
- **KEV:** added 2025-06-03

> Memory corruption due to unauthorized command execution in GPU micronode while executing specific sequence of commands.

### CVE-2025-23097
**samsung exynos_1380_firmware Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** samsung exynos_1380_firmware
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-06T18:45:47.190
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-03)

> An issue was discovered in Samsung Mobile Processor Exynos 1380. The lack of a length check leads to out-of-bounds writes.

### CVE-2025-25022
**ibm cloud_pak_for_security**
- **Signals:** CVSS
- **Asset:** ibm cloud_pak_for_security
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-12T20:00:40.577
- **CWE:** CWE-260
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-06-03)

> IBM QRadar Suite Software 1.10.12.0 through 1.11.2.0 and IBM Cloud Pak for Security 1.10.0.0 through 1.10.11.0 could allow an unauthenticated user in the environment to obtain highly sensitive information in configuration files.

### CVE-2025-27038
**Qualcomm Multiple Chipsets Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** qualcomm ar8031_firmware
- **Attack:** Memory Corruption
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:10:48.700
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2025-06-03

> Memory corruption while rendering graphics using Adreno GPU drivers in Chrome.

### CVE-2025-32106
**audiocodes mp-112_firmware**
- **Signals:** CVSS
- **Asset:** audiocodes mp-112_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-06-18T14:15:43.780
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-03)

> In Audiocodes Mediapack MP-11x through 6.60A.369.002, a crafted POST request request may result in an unauthenticated remote user's ability to execute unauthorized code.

### CVE-2025-44148
**mailenable mailenable cross-site scripting**
- **Signals:** CVSS
- **Asset:** mailenable mailenable
- **Attack:** cross-site scripting
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-09T18:04:33.580
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-03)

> Cross Site Scripting (XSS) vulnerability in MailEnable before v10 allows a remote attacker to execute arbitrary code via the failure.aspx component

### CVE-2025-4517
**Allows arbitrary filesystem writes outside the extraction directory during extraction with filter="data".**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-06-03)

> Allows arbitrary filesystem writes outside the extraction directory during extraction with filter="data".


You are affected by this vulnerability if using the tarfile module to extract untrusted tar archives using TarFile.extractall() or TarFile.extract() using the filter= param…

### CVE-2025-4797
**The Golo - City Travel Guide WordPress Theme theme for WordPress is vulnerable to privilege escalation via account takeover in all versio...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-03)

> The Golo - City Travel Guide WordPress Theme theme for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 1.7.0. This is due to the plugin not properly validating a user's identity prior to setting an authorization cookie. T…

### CVE-2025-48951
**Auth0-PHP is a PHP SDK for Auth0 Authentication and Management APIs.**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-03)

> Auth0-PHP is a PHP SDK for Auth0 Authentication and Management APIs. Versions 8.0.0-BETA3 prior to 8.3.1 contain a vulnerability due to insecure deserialization of cookie data. If exploited, since SDKs process cookie content without prior authentication, a threat actor could send…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-03*
