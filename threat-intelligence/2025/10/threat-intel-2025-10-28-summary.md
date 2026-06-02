# Daily Threat Intelligence — October 28, 2025

**Digest window (UTC):** 2025-10-28
**Generated:** 2026-06-02T07:33:41Z

## Threat brief

Dassault Systèmes DELMIA Apriso: 2 CVEs added to CISA KEV today. · Oracle Sun Products Suite — exploitation likelihood rose sharply (EPSS 31% → 68% · rising (+37%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Dassault Systèmes DELMIA Apriso: 2 CVEs added to CISA KEV today.
- Oracle Sun Products Suite — exploitation likelihood rose sharply (EPSS 31% → 68% · rising (+37%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2025-6205
**Dassault Systèmes DELMIA Apriso Missing Authorization Vulnerability**
- **Signals:** KEV
- **Asset:** 3ds delmia_apriso
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-29T12:49:53.960
- **CWE:** CWE-862
- **Risk score:** 88
- **KEV:** added 2025-10-28

> A missing authorization vulnerability affecting DELMIA Apriso from Release 2020 through Release 2025 could allow an attacker to gain privileged access to the application.

### CVE-2011-1511
**oracle sun_products_suite**
- **Signals:** EPSS
- **Asset:** oracle sun_products_suite
- **CVSS max:** 6.4
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **Risk score:** 81
- **EPSS 30.6% (2025-06-10) → 67.9% (2025-10-28), Δ +37.3%**

> Unspecified vulnerability in the Oracle GlassFish Server component in Oracle Sun Products Suite 2.1.1 and 3.0.1 allows remote attackers to execute arbitrary code via unknown vectors related to Administration.

### CVE-2025-12423
**azure-access blu-ic2_firmware DoS**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **Attack:** DoS
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T14:52:25.637
- **CWE:** CWE-248
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-28)

> Protocol manipulation might lead to denial of service.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5 .

### CVE-2025-12422
**azure-access blu-ic2_firmware**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T14:55:47.233
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-28)

> Vulnerable Upgrade Feature (Arbitrary File Write) may lead to obtaining super user permissions on board.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5.

### CVE-2025-12424
**azure-access blu-ic2_firmware Privilege Escalation**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **Attack:** Privilege Escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T14:45:20.907
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-28)

> Privilege Escalation through SUID-bit Binary.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5 .

### CVE-2025-12425
**azure-access blu-ic2_firmware Privilege Escalation**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **Attack:** Privilege Escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T14:41:22.743
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-28)

> Local Privilege Escalation.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5 .

### CVE-2025-36386
**ibm maximo_application_suite**
- **Signals:** CVSS
- **Asset:** ibm maximo_application_suite
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-21T14:10:18.257
- **CWE:** CWE-305
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-28)

> IBM Maximo Application Suite 9.0.0 through 9.0.15 and 9.1.0 through 9.1.4 could allow a remote attacker to bypass authentication mechanisms and gain unauthorized access to the application.

### CVE-2025-60355
**zhyd oneblog**
- **Signals:** CVSS
- **Asset:** zhyd oneblog
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-04T16:16:25.790
- **CWE:** CWE-1336
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-28)

> zhangyd-c OneBlog v2.3.9 and before was vulnerable to SSTI (Server-Side Template Injection) via FreeMarker templates.

### CVE-2025-61128
**Stack-based buffer overflow vulnerability in WAVLINK QUANTUM D3G/WL-WN530HG3 firmware M30HG3_V240730, and possibly other wavlink models a...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-28)

> Stack-based buffer overflow vulnerability in WAVLINK QUANTUM D3G/WL-WN530HG3 firmware M30HG3_V240730, and possibly other wavlink models allows attackers to execute arbitrary code via crafted referrer value POST to login.cgi.

### CVE-2025-61235
**An issue was discovered in Dataphone A920 v2025.07.161103.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-28)

> An issue was discovered in Dataphone A920 v2025.07.161103. A custom packet based on public documentation can be crafted, where some fields can contain arbitrary or trivial data. Normally, such data should cause the device to reject the packet. However, due to a lack of validation…

### CVE-2025-6204
**Dassault Systèmes DELMIA Apriso Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** 3ds delmia_apriso
- **CVSS max:** 8.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-29T12:49:33.617
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2025-10-28

> An Improper Control of Generation of Code (Code Injection) vulnerability affecting DELMIA Apriso from Release 2020 through Release 2025 could allow an attacker to execute arbitrary code.

### CVE-2025-62368
**Taiga is an open source project management platform.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-10-28)

> Taiga is an open source project management platform. In versions 6.8.3 and earlier, a remote code execution vulnerability exists in the Taiga API due to unsafe deserialization of untrusted data. This issue is fixed in version 6.9.0.

### CVE-2025-64095
**dnnsoftware dotnetnuke cross-site scripting**
- **Signals:** CVSS
- **Asset:** dnnsoftware dotnetnuke
- **Attack:** cross-site scripting
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-03T19:39:58.247
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-28)

> DNN (formerly DotNetNuke) is an open-source web content management platform (CMS) in the Microsoft ecosystem. Prior to 10.1.1, the default HTML editor provider allows unauthenticated file uploads and images can overwrite existing files. An unauthenticated user can upload and repl…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-28*
