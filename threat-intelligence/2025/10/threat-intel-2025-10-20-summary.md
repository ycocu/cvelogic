# Daily Threat Intelligence — October 20, 2025

**Digest window (UTC):** 2025-10-20
**Generated:** 2026-06-02T07:33:37Z

## Threat brief

Kentico Xperience CMS: 2 CVEs added to CISA KEV today. · Adobe Bridge — exploitation likelihood rose sharply (EPSS 8.3% → 26% · rising (+18%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Kentico Xperience CMS: 2 CVEs added to CISA KEV today.
- Adobe Bridge — exploitation likelihood rose sharply (EPSS 8.3% → 26% · rising (+18%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 5 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2022-48503
**Apple Multiple Products Unspecified Vulnerability**
- **Signals:** KEV
- **Asset:** apple safari
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-23T18:47:53.243
- **CWE:** CWE-129
- **Risk score:** 88
- **KEV:** added 2025-10-20

> The issue was addressed with improved bounds checks. This issue is fixed in tvOS 15.6, watchOS 8.7, iOS 15.6 and iPadOS 15.6, macOS Monterey 12.5, Safari 15.6. Processing web content may lead to arbitrary code execution.

### CVE-2020-9552
**adobe bridge RCE**
- **Signals:** EPSS
- **Asset:** adobe bridge
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:40:51.330
- **CWE:** CWE-787
- **Risk score:** 83
- **EPSS 8.2% (2025-06-12) → 26.5% (2025-10-20), Δ +18.2%**

> Adobe Bridge versions 10.0 have a heap-based buffer overflow vulnerability. Successful exploitation could lead to arbitrary code execution.

### CVE-2025-12001
**azure-access blu-ic2_firmware cross-site scripting**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **Attack:** cross-site scripting
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T20:15:52.710
- **CWE:** CWE-20
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-20)

> Lack of application manifest sanitation could lead to potential stored XSS.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5.

### CVE-2018-25118
**GeoVision embedded IP devices, confirmed on GV-BX1500 and GV-MFD1501, contain a remote command injection vulnerability via /PictureCatch....**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-20)

> GeoVision embedded IP devices, confirmed on GV-BX1500 and GV-MFD1501, contain a remote command injection vulnerability via /PictureCatch.cgi that enables an attacker to execute arbitrary commands on the device. The vulnerable models have been declared end-of-life (EOL) by the ven…

### CVE-2025-10678
**NetBird VPN when installed using vendor's provided script failed to remove or change default password of an admin account created by ZITA...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-20)

> NetBird VPN when installed using vendor's provided script failed to remove or change default password of an admin account created by ZITADEL.
This issue affects instances installed using vendor's provided script. This issue may affect instances created with Docker if the default …

### CVE-2025-2746
**Kentico Xperience CMS Authentication Bypass Using an Alternate Path or Channel Vulnerability**
- **Signals:** KEV
- **Asset:** kentico xperience
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T13:58:06.383
- **CWE:** CWE-288
- **Risk score:** 88
- **KEV:** added 2025-10-20

> An authentication bypass vulnerability in Kentico Xperience allows authentication bypass via the Staging Sync Server password handling of empty SHA1 usernames in digest authentication. Authentication bypass allows an attacker to control administrative objects.This issue affects X…

### CVE-2025-2747
**Kentico Xperience CMS Authentication Bypass Using an Alternate Path or Channel Vulnerability**
- **Signals:** KEV
- **Asset:** kentico xperience
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T13:58:01.850
- **CWE:** CWE-288
- **Risk score:** 88
- **KEV:** added 2025-10-20

> An authentication bypass vulnerability in Kentico Xperience allows authentication bypass via the Staging Sync Server component password handling for the server defined None type. Authentication bypass allows an attacker to control administrative objects.This issue affects Xperien…

### CVE-2025-31342
**An unrestricted upload of file with dangerous type vulnerability in the upload file function of Galaxy Software Services Corporation Vita...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-20)

> An unrestricted upload of file with dangerous type vulnerability in the upload file function of Galaxy Software Services Corporation Vitals ESP Forum Module through 1.3 version allows remote authenticated users to execute arbitrary system commands via a malicious file.

### CVE-2025-33073
**Microsoft Windows SMB Client Improper Access Control Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1507
- **Attack:** privilege escalation
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:12:42.667
- **CWE:** CWE-284
- **Risk score:** 88
- **KEV:** added 2025-10-20

> Improper access control in Windows SMB allows an authorized attacker to elevate privileges over a network.

### CVE-2025-41028
**A SQL Injection vulnerability has been found in Epsilon RH by Grupo Castilla.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-20)

> A SQL Injection vulnerability has been found in Epsilon RH by Grupo Castilla. This vulnerability allows an attacker to retrieve, create, update and delete database via sending a POST request using the parameter ‘sEstadoUsr’ in ‘/epsilonnetws/WSAvisos.asmx’.

### CVE-2025-54957
**An issue was discovered in Dolby UDC 4.5 through 4.13.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-190
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-20)

> An issue was discovered in Dolby UDC 4.5 through 4.13. A crash of the DD+ decoder process can occur when a malformed DD+ bitstream is processed. When Evolution data is processed by evo_priv.c from the DD+ bitstream, the decoder writes that data into a buffer. The length calculati…

### CVE-2025-61303
**Hatching Triage Sandbox Windows 10 build 2004 (2025-08-14) and Windows 10 LTSC 2021(2025-08-14) contains a vulnerability in its Windows b...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-400
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-20)

> Hatching Triage Sandbox Windows 10 build 2004 (2025-08-14) and Windows 10 LTSC 2021(2025-08-14) contains a vulnerability in its Windows behavioral analysis engine that allows a submitted malware sample to evade detection and cause denial-of-analysis. The vulnerability is triggere…

### CVE-2025-61455
**SQL Injection vulnerability exists in Bhabishya-123 E-commerce 1.0, specifically within the signup.inc.php endpoint.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-20)

> SQL Injection vulnerability exists in Bhabishya-123 E-commerce 1.0, specifically within the signup.inc.php endpoint. The application directly incorporates unsanitized user inputs into SQL queries, allowing unauthenticated attackers to bypass authentication and gain full access.

### CVE-2025-61884
**Oracle E-Business Suite Server-Side Request Forgery (SSRF) Vulnerability**
- **Signals:** KEV
- **Asset:** oracle configurator
- **Attack:** SSRF
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:08:49.037
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2025-10-20

> Vulnerability in the Oracle Configurator product of Oracle E-Business Suite (component: Runtime UI).  Supported versions that are affected are 12.2.3-12.2.14. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle Config…

### CVE-2025-61932
**Motex LANSCOPE Endpoint Manager Improper Verification of Source of a Communication Channel Vulnerability**
- **Signals:** CVSS
- **Asset:** motex lanscope_endpoint_manager
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-23T13:00:14.270
- **CWE:** CWE-940
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-20)

> Lanscope Endpoint Manager (On-Premises) (Client program (MR) and Detection agent (DA)) improperly verifies the origin of incoming requests, allowing an attacker to execute arbitrary code by sending specially crafted packets.

### CVE-2025-9574
**Missing Authentication for Critical Function vulnerability in ABB ALS-mini-s4 IP, ABB ALS-mini-s8 IP.This issue affects .**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-10-20)

> Missing Authentication for Critical Function vulnerability in ABB ALS-mini-s4 IP, ABB ALS-mini-s8 IP.This issue affects . 

All firmware versions with the Serial Number from 2000 to 5166

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-20*
