# Daily Threat Intelligence — November 12, 2025

**Digest window (UTC):** 2025-11-12
**Generated:** 2026-06-02T07:33:46Z

## Threat brief

Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 3 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2025-62215
**Microsoft Windows Race Condition Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1809
- **Attack:** privilege escalation
- **CVSS max:** 7.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-14T02:00:02.350
- **CWE:** CWE-362
- **Risk score:** 88
- **KEV:** added 2025-11-12

> Concurrent execution using shared resource with improper synchronization ('race condition') in Windows Kernel allows an authorized attacker to elevate privileges locally.

### CVE-2025-11367
**n-able n-central RCE**
- **Signals:** CVSS
- **Asset:** n-able n-central
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-14T19:31:50.133
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-12)

> The N-central Software Probe < 2025.4 is vulnerable to Remote Code Execution via deserialization

### CVE-2025-56385
**wellsky harmony Auth Bypass**
- **Signals:** CVSS
- **Asset:** wellsky harmony
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T16:23:29.657
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-12)

> A SQL injection vulnerability exists in the login functionality of WellSky Harmony version 4.1.0.2.83 within the 'xmHarmony.asp' endpoint. User-supplied input to the 'TXTUSERID' parameter is not properly sanitized before being incorporated into a SQL query. Successful authenticat…

### CVE-2021-4464
**FiberHome AN5506-04-FA firmware versions up to and including RP2631 and HG6245D prior to RP2602 contain a stack-based buffer overflow, as...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-12)

> FiberHome AN5506-04-FA firmware versions up to and including RP2631 and HG6245D prior to RP2602 contain a stack-based buffer overflow, as the HTTP service ('webs') fails to enforce maximum lengths for Cookie header values. When a cookie longer than 511 bytes is processed, a stack…

### CVE-2025-11366
**n-able n-central Path Traversal**
- **Signals:** CVSS
- **Asset:** n-able n-central
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-14T19:32:19.650
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-11-12)

> N-central < 2025.4 is vulnerable to authentication bypass via path traversal

### CVE-2025-12480
**Gladinet Triofox Improper Access Control Vulnerability**
- **Signals:** KEV
- **Asset:** gladinet triofox
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-14T02:00:02.350
- **CWE:** CWE-284
- **Risk score:** 88
- **KEV:** added 2025-11-12

> Triofox versions prior to 16.7.10368.56560, are vulnerable to an Improper Access Control flaw that allows access to initial setup pages even after setup is complete.

### CVE-2025-46608
**dell data_lakehouse privilege escalation**
- **Signals:** CVSS
- **Asset:** dell data_lakehouse
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-05T20:39:41.723
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-12)

> Dell Data Lakehouse, versions prior to 1.6.0.0, contain(s) an Improper Access Control vulnerability. A high privileged attacker with remote access could potentially exploit this vulnerability, leading to Elevation of privileges. This vulnerability is considered Critical, as it ma…

### CVE-2025-63289
**sogexia sogexia**
- **Signals:** CVSS
- **Asset:** sogexia sogexia
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-05T19:23:25.003
- **CWE:** CWE-321
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-12)

> Sogexia Android App Compile Affected SDK v35, Max SDK 32 and fixed in v36, was discovered to contain hardcoded encryption keys in the encryption_helper.dart file

### CVE-2025-63353
**fiberhome hg6145f1_firmware**
- **Signals:** CVSS
- **Asset:** fiberhome hg6145f1_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T16:52:00.467
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-12)

> A vulnerability in FiberHome GPON ONU HG6145F1 RP4423 allows the device's factory default Wi-Fi password (WPA/WPA2 pre-shared key) to be predicted from the SSID. The device generates default passwords using a deterministic algorithm that derives the router passphrase from the SSI…

### CVE-2025-63666
**tenda ac15_firmware**
- **Signals:** CVSS
- **Asset:** tenda ac15_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-17T18:59:20.080
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-12)

> Tenda AC15 v15.03.05.18_multi) issues an authentication cookie that exposes the account password hash to the client and uses a short, low-entropy suffix as the session identifier. An attacker with network access or the ability to run JS in a victim browser can steal the cookie an…

### CVE-2025-64280
**centralsquare community_development SQL Injection**
- **Signals:** CVSS
- **Asset:** centralsquare community_development
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T16:44:00.870
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-12)

> A SQL Injection Vulnerability in CentralSquare Community Development 19.5.7 allows attackers to inject SQL via the permit_no field.

### CVE-2025-64281
**centralsquare community_development Auth Bypass**
- **Signals:** CVSS
- **Asset:** centralsquare community_development
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T16:42:59.320
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-12)

> An Authentication Bypass issue in CentralSquare Community Development 19.5.7 allows attackers to access the admin panel without admin credentials.

### CVE-2025-9242
**WatchGuard Firebox Out-of-Bounds Write Vulnerability**
- **Signals:** KEV
- **Asset:** watchguard fireware
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-14T02:00:02.350
- **CWE:** CWE-787
- **Risk score:** 88
- **KEV:** added 2025-11-12

> An Out-of-bounds Write vulnerability in WatchGuard Fireware OS may allow a remote unauthenticated attacker to execute arbitrary code. This vulnerability affects both the Mobile User VPN with IKEv2 and the Branch Office VPN using IKEv2 when configured with a dynamic gateway peer.T…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-12*
