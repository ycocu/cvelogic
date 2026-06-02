# Daily Threat Intelligence — December 15, 2025

**Digest window (UTC):** 2025-12-15
**Generated:** 2026-06-02T07:33:59Z

## Threat brief

Apple Multiple Products added to CISA KEV — confirmed in-the-wild exploitation. · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apple Multiple Products added to CISA KEV — confirmed in-the-wild exploitation.
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-43529
**Apple Multiple Products Use-After-Free WebKit Vulnerability**
- **Signals:** KEV
- **Asset:** apple safari
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T14:17:40.310
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2025-12-15

> A use-after-free issue was addressed with improved memory management. This issue is fixed in Safari 26.2, iOS 18.7.3 and iPadOS 18.7.3, iOS 26.2 and iPadOS 26.2, macOS Tahoe 26.2, tvOS 26.2, visionOS 26.2, watchOS 26.2. Processing maliciously crafted web content may lead to arbit…

### CVE-2025-65213
**mthreads torch_musa RCE**
- **Signals:** CVSS
- **Asset:** mthreads torch_musa
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-07T20:51:19.160
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-15)

> MooreThreads torch_musa through all versions contains an unsafe deserialization vulnerability in torch_musa.utils.compare_tool. The compare_for_single_op() and nan_inf_track_for_single_op() functions use pickle.load() on user-controlled file paths without validation, allowing arb…

### CVE-2025-14156
**The Fox LMS – WordPress LMS Plugin plugin for WordPress is vulnerable to privilege escalation in all versions up to, and including, 1.0.5.1.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-15)

> The Fox LMS – WordPress LMS Plugin plugin for WordPress is vulnerable to privilege escalation in all versions up to, and including, 1.0.5.1. This is due to the plugin not properly validating the 'role' parameter when creating new users via the `/fox-lms/v1/payments/create-order` …

### CVE-2023-53872
**Wp2Fac 1.0 contains an OS command injection vulnerability in the send.php endpoint that allows remote attackers to execute arbitrary syst...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-15)

> Wp2Fac 1.0 contains an OS command injection vulnerability in the send.php endpoint that allows remote attackers to execute arbitrary system commands. Attackers can inject shell commands through the 'numara' parameter by appending shell commands with '&' operators to execute malic…

### CVE-2023-53877
**phpjabbers bus_reservation_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpjabbers bus_reservation_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-18T22:36:03.887
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-15)

> Bus Reservation System 1.1 contains a SQL injection vulnerability in the pickup_id parameter that allows attackers to manipulate database queries. Attackers can exploit boolean-based, error-based, and time-based blind SQL injection techniques to steal information from the databas…

### CVE-2023-53881
**ruijienetworks reyee_os**
- **Signals:** CVSS
- **Asset:** ruijienetworks reyee_os
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-18T22:38:22.163
- **CWE:** CWE-319
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-12-15)

> ReyeeOS 1.204.1614 contains an unencrypted CWMP communication vulnerability that allows attackers to intercept and manipulate device communication through a man-in-the-middle attack. Attackers can create a fake CWMP server to inject and execute arbitrary commands on Ruijie Reyee …

### CVE-2025-13888
**A flaw was found in OpenShift GitOps.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-266
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-15)

> A flaw was found in OpenShift GitOps. Namespace admins can create ArgoCD Custom Resources (CRs) that trick the system into granting them elevated permissions in other namespaces, including privileged namespaces. An authenticated attacker can then use these elevated permissions to…

### CVE-2025-14611
**Gladinet CentreStack and Triofox Hard Coded Cryptographic Vulnerability**
- **Signals:** KEV
- **Asset:** gladinet centrestack
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T13:48:02.743
- **CWE:** CWE-798
- **Risk score:** 88
- **KEV:** added 2025-12-15

> Gladinet CentreStack and Triofox prior to version 16.12.10420.56791 used hardcoded values for their implementation of the AES cryptoscheme. This degrades security for public exposed endpoints that may make use of it and may offer arbitrary local file inclusion when provided a spe…

### CVE-2025-55895
**totolink a3300r_firmware**
- **Signals:** CVSS
- **Asset:** totolink a3300r_firmware
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-17T19:21:10.510
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-15)

> TOTOLINK A3300R V17.0.0cu.557_B20221024 and N200RE V9.3.5u.6448_B20240521 and V9.3.5u.6437_B20230519 are vulnerable to Incorrect Access Control. Attackers can send payloads to the interface without logging in (remote).

### CVE-2025-66844
**getgrav grav SSRF**
- **Signals:** CVSS
- **Asset:** getgrav grav
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-17T15:38:46.163
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-15)

> In grav <1.7.49.5, a SSRF (Server-Side Request Forgery) vector may be triggered via Twig templates when page content is processed by Twig and the configuration allows undefined PHP functions to be registered

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-15*
