# Daily Threat Intelligence — August 25, 2025

**Digest window (UTC):** 2025-08-25
**Generated:** 2026-06-02T07:33:18Z

## Threat brief

Citrix Session Recording: 2 CVEs added to CISA KEV today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Citrix Session Recording: 2 CVEs added to CISA KEV today.
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

### CVE-2024-8068
**Citrix Session Recording Improper Privilege Management Vulnerability**
- **Signals:** KEV
- **Asset:** citrix session_recording
- **Attack:** Privilege Escalation
- **CVSS max:** 8.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:42:34.467
- **CWE:** CWE-269
- **Risk score:** 88
- **KEV:** added 2025-08-25

> Privilege escalation to NetworkService Account access in Citrix Session Recording when an attacker is an authenticated user in the same Windows Active Directory domain as the session recording server domain

### CVE-2025-54492
**libbiosig_project libbiosig RCE**
- **Signals:** CVSS
- **Asset:** libbiosig_project libbiosig
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T19:16:11.197
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-25)

> A stack-based buffer overflow vulnerability exists in the MFER parsing functionality of The Biosig Project libbiosig 3.9.0 and Master Branch (35a819fa). A specially crafted MFER file can lead to arbitrary code execution. An attacker can provide a malicious file to trigger this vu…

### CVE-2025-54493
**libbiosig_project libbiosig RCE**
- **Signals:** CVSS
- **Asset:** libbiosig_project libbiosig
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T19:16:11.307
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-25)

> A stack-based buffer overflow vulnerability exists in the MFER parsing functionality of The Biosig Project libbiosig 3.9.0 and Master Branch (35a819fa). A specially crafted MFER file can lead to arbitrary code execution. An attacker can provide a malicious file to trigger this vu…

### CVE-2024-8069
**Citrix Session Recording Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** citrix session_recording
- **Attack:** RCE
- **CVSS max:** 8.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:42:29.560
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2025-08-25

> Limited remote code execution with privilege of a NetworkService Account access in Citrix Session Recording if the attacker is an authenticated user on the same intranet as the session recording server

### CVE-2025-48384
**Git Link Following Vulnerability**
- **Signals:** KEV
- **Asset:** git-scm git
- **CVSS max:** 8.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T14:52:47.590
- **CWE:** CWE-59
- **Risk score:** 88
- **KEV:** added 2025-08-25

> Git is a fast, scalable, distributed revision control system with an unusually rich command set that provides both high-level operations and full access to internals. When reading a config value, Git strips any trailing carriage return and line feed (CRLF). When writing a config …

### CVE-2025-50722
**sparkshop sparkshop**
- **Signals:** CVSS
- **Asset:** sparkshop sparkshop
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-09T18:57:52.620
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-25)

> Insecure Permissions vulnerability in sparkshop v.1.1.7 allows a remote attacker to execute arbitrary code via the Common.php component

### CVE-2025-50900
**getrebuild rebuild**
- **Signals:** CVSS
- **Asset:** getrebuild rebuild
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T17:54:22.767
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-25)

> An issue was discovered in getrebuild/rebuild 4.0.4. The affected source code class is com.rebuild.web.RebuildWebInterceptor, and the affected function is preHandle In the filter code, use CodecUtils.urlDecode(request.getRequestURI()) to obtain the URL-decoded request path, and t…

### CVE-2025-53118
**An authentication bypass vulnerability exists which allows an unauthenticated attacker to control administrator backup functions, leading...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-25)

> An authentication bypass vulnerability exists which allows an unauthenticated attacker to control administrator backup functions, leading to compromise of passwords, secrets, and application session tokens stored by the Unified PAM.

### CVE-2025-53120
**A path traversal vulnerability in unauthenticated upload functionality allows a malicious actor to upload binaries and scripts to the ser...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-25)

> A path traversal vulnerability in unauthenticated upload functionality allows a malicious actor to upload binaries and scripts to the server’s configuration and web root directories, achieving remote code execution on the Unified PAM server.

### CVE-2025-54494
**libbiosig_project libbiosig RCE**
- **Signals:** CVSS
- **Asset:** libbiosig_project libbiosig
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T19:16:11.420
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-25)

> A stack-based buffer overflow vulnerability exists in the MFER parsing functionality of The Biosig Project libbiosig 3.9.0 and Master Branch (35a819fa). A specially crafted MFER file can lead to arbitrary code execution. An attacker can provide a malicious file to trigger this vu…

### CVE-2025-55575
**SQL Injection vulnerability in SMM Panel 3.1 allowing remote attackers to gain sensitive information via a crafted HTTP request with acti...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-25)

> SQL Injection vulnerability in SMM Panel 3.1 allowing remote attackers to gain sensitive information via a crafted HTTP request with action=service_detail.

### CVE-2025-56212
**phpgurukul hospital_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul hospital_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-06T14:16:21.277
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-25)

> phpgurukul Hospital Management System 4.0 is vulnerable to SQL Injection in add-doctor.php via the docname parameter.

### CVE-2025-56214
**phpgurukul hospital_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul hospital_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-06T14:16:21.767
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-25)

> phpgurukul Hospital Management System 4.0 is vulnerable to SQL Injection in index.php via the username parameter.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-25*
