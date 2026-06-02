# Daily Threat Intelligence — August 29, 2025

**Digest window (UTC):** 2025-08-29
**Generated:** 2026-06-02T07:33:19Z

## Threat brief

Sangoma FreePBX added to CISA KEV — confirmed in-the-wild exploitation. · Trendnet Tew733gr Firmware — exploitation likelihood rose sharply (EPSS 3.2% → 18% · rising (+15%)). · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- Sangoma FreePBX added to CISA KEV — confirmed in-the-wild exploitation.
- Trendnet Tew733gr Firmware — exploitation likelihood rose sharply (EPSS 3.2% → 18% · rising (+15%)).
- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **8** |


## CVEs

### CVE-2025-57819
**Sangoma FreePBX Authentication Bypass Vulnerability**
- **Signals:** KEV
- **Asset:** sangoma freepbx
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:58:40.963
- **CWE:** CWE-89
- **Risk score:** 88
- **KEV:** added 2025-08-29

> FreePBX is an open-source web-based graphical user interface. FreePBX 15, 16, and 17 endpoints are vulnerable due to insufficiently sanitized user-supplied data allowing unauthenticated access to FreePBX Administrator leading to arbitrary database manipulation and remote code exe…

### CVE-2022-37053
**trendnet tew733gr_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** trendnet tew733gr_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:14:21.710
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 3.2% (2025-05-23) → 18.4% (2025-08-29), Δ +15.3%**

> TRENDnet TEW733GR v1.03B01 is vulnerable to Command injection via /htdocs/upnpinc/gena.php.

### CVE-2025-58159
**wegia wegia RCE**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-24T18:36:12.110
- **CWE:** CWE-94
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-08-29)

> WeGIA is a Web manager for charitable institutions. Prior to version 3.4.11, a remote code execution vulnerability was identified, caused by improper validation of uploaded files. The application allows an attacker to upload files with arbitrary filenames, including those with a …

### CVE-2024-46484
**trendnet tv-ip410_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** trendnet tv-ip410_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-08T16:42:27.080
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-29)

> TRENDnet TV-IP410 vA1.0R was discovered to contain an OS command injection vulnerability via the /server/cgi-bin/testserv.cgi component.

### CVE-2025-44033
**aaluoxiang oa_system SQL Injection**
- **Signals:** CVSS
- **Asset:** aaluoxiang oa_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-19T17:06:22.677
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-29)

> SQL injection vulnerability in oa_system oasys v.1.1 allows a remote attacker to execute arbitrary code via the allDirector() method declaration in src/main/java/cn/gson/oasys/mappers/AddressMapper.java

### CVE-2025-52856
**qnap qvr**
- **Signals:** CVSS
- **Asset:** qnap qvr
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T21:58:30.410
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-29)

> An improper authentication vulnerability has been reported to affect VioStor. If a remote attacker, they can then exploit the vulnerability to compromise the security of the system.

We have already fixed the vulnerability in the following version:
VioStor 5.1.6 build 20250621 an…

### CVE-2025-8857
**Clinic Image System developed by Changing contains hard-coded Credentials, allowing unauthenticated remote attackers to log into the syst...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-29)

> Clinic Image System developed by Changing contains hard-coded Credentials, allowing unauthenticated remote attackers to log into the system using administrator credentials embedded in the source code.

### CVE-2025-8861
**TSA developed by Changing has a Missing Authentication vulnerability, allowing unauthenticated remote attackers to read, modify, and dele...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-29)

> TSA developed by Changing has a Missing Authentication vulnerability, allowing unauthenticated remote attackers to read, modify, and delete database contents.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-29*
