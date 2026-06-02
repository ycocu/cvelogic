# Daily Threat Intelligence — November 20, 2025

**Digest window (UTC):** 2025-11-20
**Generated:** 2026-06-02T07:33:49Z

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

### CVE-2025-49752
**microsoft azure_bastion_developer privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_bastion_developer
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-21T19:16:04.440
- **CWE:** CWE-294
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-20)

> Azure Bastion Elevation of Privilege Vulnerability

### CVE-2025-40604
**sonicwall email_security_appliance_5000_firmware RCE**
- **Signals:** CVSS
- **Asset:** sonicwall email_security_appliance_5000_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-12T15:44:04.973
- **CWE:** CWE-494
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-20)

> Download of Code Without Integrity Check Vulnerability in the SonicWall Email Security appliance loads root filesystem images without verifying signatures, allowing attackers with VMDK or datastore access to modify system files and gain persistent arbitrary code execution.

### CVE-2025-52410
**vishalmathur institute-of-current-students SQL Injection**
- **Signals:** CVSS
- **Asset:** vishalmathur institute-of-current-students
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-12T15:29:56.813
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-20)

> Institute-of-Current-Students v1.0 contains a time-based blind SQL injection vulnerability in the mydetailsstudent.php endpoint. The `myds` GET parameter is not adequately sanitized before being used in SQL queries.

### CVE-2025-10571
**Authentication Bypass Using an Alternate Path or Channel vulnerability in ABB ABB Ability Edgenius.This issue affects ABB Ability Edgeniu...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-11-20)

> Authentication Bypass Using an Alternate Path or Channel vulnerability in ABB ABB Ability Edgenius.This issue affects ABB Ability Edgenius: 3.2.0.0, 3.2.1.1.

### CVE-2025-34320
**BASIS BBj versions prior to 25.00 contain a Jetty-served web endpoint that fails to properly validate or canonicalize input path segments.**
- **Signals:** CVSS
- **Attack:** Directory Traversal
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-20)

> BASIS BBj versions prior to 25.00 contain a Jetty-served web endpoint that fails to properly validate or canonicalize input path segments. This allows unauthenticated directory traversal sequences to cause the server to read arbitrary system files accessible to the account runnin…

### CVE-2025-59245
**microsoft sharepoint_online privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft sharepoint_online
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-21T19:16:22.127
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-20)

> Microsoft SharePoint Online Elevation of Privilege Vulnerability

### CVE-2025-60738
**ilevia eve_x1_server_firmware**
- **Signals:** CVSS
- **Asset:** ilevia eve_x1_server_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T18:57:44.380
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-20)

> An issue in Ilevia EVE X1 Server Firmware Version v4.7.18.0.eden and before Logic Version v6.00 - 2025_07_21 and before allows a remote attacker to execute arbitrary code via the ping.php component does not perform secure filtering on IP parameters

### CVE-2025-63685
**quark quark_cloud_drive**
- **Signals:** CVSS
- **Asset:** quark quark_cloud_drive
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T18:05:05.273
- **CWE:** CWE-491
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-20)

> Quark Cloud Drive v3.23.2 has a DLL Hijacking vulnerability. This vulnerability stems from the insecure loading of system libraries. Specifically, the application does not validate the path or signature of [regsvr32.exe] it loads. An attacker can place a crafted malicious DLL in …

### CVE-2025-63807
**2dogz blogin**
- **Signals:** CVSS
- **Asset:** 2dogz blogin
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-15T16:59:02.453
- **CWE:** CWE-307
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-20)

> An issue was discovered in weijiang1994 university-bbs (aka Blogin) in commit 9e06bab430bfc729f27b4284ba7570db3b11ce84 (2025-01-13). A weak verification code generation mechanism combined with missing rate limiting allows attackers to perform brute-force attacks on verification c…

### CVE-2025-63888
**thinkphp thinkphp RCE**
- **Signals:** CVSS
- **Asset:** thinkphp thinkphp
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-25T15:40:00.237
- **CWE:** CWE-98
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-20)

> The read function in file thinkphp\library\think\template\driver\File.php in ThinkPHP 5.0.24 contains a remote code execution vulnerability.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-20*
