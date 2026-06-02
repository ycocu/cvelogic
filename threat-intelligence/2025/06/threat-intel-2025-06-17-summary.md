# Daily Threat Intelligence — June 17, 2025

**Digest window (UTC):** 2025-06-17
**Generated:** 2026-06-02T07:32:54Z

## Threat brief

Linux Kernel added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Linux Kernel added to CISA KEV — confirmed in-the-wild exploitation.
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

### CVE-2023-0386
**Linux Kernel Improper Ownership Management Vulnerability**
- **Signals:** KEV
- **Asset:** debian debian_linux
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-04T16:47:21.283
- **CWE:** CWE-282
- **Risk score:** 88
- **KEV:** added 2025-06-17

> A flaw was found in the Linux kernel, where unauthorized access to the execution of the setuid file with capabilities was found in the Linux kernel’s OverlayFS subsystem in how a user copies a capable file from a nosuid mount into another mount. This uid mapping bug allows a loca…

### CVE-2025-49444
**Unrestricted Upload of File with Dangerous Type vulnerability in merkulove Reformer for Elementor reformer-elementor allows Upload a Web...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:41.683
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-17)

> Unrestricted Upload of File with Dangerous Type vulnerability in merkulove Reformer for Elementor reformer-elementor allows Upload a Web Shell to a Web Server.This issue affects Reformer for Elementor: from n/a through <= 1.0.5.

### CVE-2025-49447
**Unrestricted Upload of File with Dangerous Type vulnerability in Fastw3b LLC FW Food Menu allows Using Malicious Files.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-28T19:33:08.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-17)

> Unrestricted Upload of File with Dangerous Type vulnerability in Fastw3b LLC FW Food Menu  allows Using Malicious Files. This issue affects FW Food Menu : from n/a through 6.0.0.

### CVE-2025-49212
**trendmicro trend_micro_endpoint_encryption RCE**
- **Signals:** CVSS
- **Asset:** trendmicro trend_micro_endpoint_encryption
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-08T21:09:04.560
- **CWE:** CWE-477
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-17)

> An insecure deserialization operation in the Trend Micro Endpoint Encryption PolicyServer could lead to a pre-authentication remote code execution on affected installations. Note that this vulnerability is similar to CVE-2025-49220 but is in a different method.

### CVE-2025-49213
**trendmicro trend_micro_endpoint_encryption RCE**
- **Signals:** CVSS
- **Asset:** trendmicro trend_micro_endpoint_encryption
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-08T21:09:21.877
- **CWE:** CWE-477
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-17)

> An insecure deserialization operation in the Trend Micro Endpoint Encryption PolicyServer could lead to a pre-authentication remote code execution on affected installations. Note that this vulnerability is similar to CVE-2025-49212 but is in a different method.

### CVE-2025-49216
**trendmicro trend_micro_endpoint_encryption Auth Bypass**
- **Signals:** CVSS
- **Asset:** trendmicro trend_micro_endpoint_encryption
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-08T21:10:36.310
- **CWE:** CWE-477
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-17)

> An authentication bypass vulnerability in the Trend Micro Endpoint Encryption PolicyServer could allow an attacker to access key methods as an admin user and modify product configurations on affected installations.

### CVE-2025-49217
**trendmicro trend_micro_endpoint_encryption RCE**
- **Signals:** CVSS
- **Asset:** trendmicro trend_micro_endpoint_encryption
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-08T21:10:49.183
- **CWE:** CWE-477
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-17)

> An insecure deserialization operation in the Trend Micro Endpoint Encryption PolicyServer could lead to a pre-authentication remote code execution on affected installations. Note that this vulnerability is similar to CVE-2025-49213 but is in a different method.

### CVE-2025-49219
**trendmicro apex_central RCE**
- **Signals:** CVSS
- **Asset:** trendmicro apex_central
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-08T21:06:23.910
- **CWE:** CWE-477
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-17)

> An insecure deserialization operation in Trend Micro Apex Central below versions 8.0.7007 could lead to a pre-authentication remote code execution on affected installations. Note that this vulnerability is similar to CVE-2025-49220 but is in a different method.

### CVE-2025-49220
**trendmicro apex_central RCE**
- **Signals:** CVSS
- **Asset:** trendmicro apex_central
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-08T21:06:21.787
- **CWE:** CWE-477
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-17)

> An insecure deserialization operation in Trend Micro Apex Central below version 8.0.7007 could lead to a pre-authentication remote code execution on affected installations. Note that this vulnerability is similar to CVE-2025-49219 but is in a different method.

### CVE-2025-49452
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Adrian Ladó PostaPanduri postapandu...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:42.600
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-17)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Adrian Ladó PostaPanduri postapanduri allows SQL Injection.This issue affects PostaPanduri: from n/a through <= 2.1.3.

### CVE-2025-49825
**Teleport provides connectivity, authentication, access controls and audit for infrastructure.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-863
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-17)

> Teleport provides connectivity, authentication, access controls and audit for infrastructure. Community Edition versions before and including 17.5.1 are vulnerable to remote authentication bypass. At time of posting, there is no available open-source patch.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-17*
