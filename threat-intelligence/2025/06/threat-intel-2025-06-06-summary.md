# Daily Threat Intelligence — June 06, 2025

**Digest window (UTC):** 2025-06-06
**Generated:** 2026-06-02T07:32:50Z

## Threat brief

Rockwellautomation Micrologix 1400 B Firmware — exploitation likelihood rose sharply (EPSS 15% → 37% · rising (+22%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Rockwellautomation Micrologix 1400 B Firmware — exploitation likelihood rose sharply (EPSS 15% → 37% · rising (+22%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2017-14464
**rockwellautomation micrologix_1400_b_firmware**
- **Signals:** EPSS
- **Asset:** rockwellautomation micrologix_1400_b_firmware
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:12:50.790
- **Risk score:** 86
- **EPSS 15.1% (2025-03-30) → 37.0% (2025-06-06), Δ +21.9%**

> An exploitable access control vulnerability exists in the data, program, and function file permissions functionality of Allen Bradley Micrologix 1400 Series B FRN 21.2 and before. A specially crafted packet can cause a read or write operation resulting in disclosure of sensitive …

### CVE-2025-3322
**An improper neutralization of inputs used in expression language allows remote code execution with the highest privileges on the server.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-917
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-06)

> An improper neutralization of inputs used in expression
language allows remote code execution with the highest privileges on the
server.

### CVE-2025-48780
**scshr hr_portal Deserialization**
- **Signals:** CVSS
- **Asset:** scshr hr_portal
- **Attack:** Deserialization
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-04T15:02:46.763
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-06-06)

> A deserialization of untrusted data vulnerability in the download file function of Soar Cloud HRD Human Resource Management System through version 7.3.2025.0408 allows remote attackers to execute arbitrary system commands via a crafted serialized object.

### CVE-2025-27531
**apache inlong Deserialization**
- **Signals:** CVSS
- **Asset:** apache inlong
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-23T14:24:00.320
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-06)

> Deserialization of Untrusted Data vulnerability in Apache InLong. 

This issue affects Apache InLong: from 1.13.0 before 2.1.0, 

this issue would allow an authenticated attacker to read arbitrary files by double writing the param.





Users are recommended to upgrade to version…

### CVE-2025-3365
**A missing protection against path traversal allows to access any file on the server.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-23
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-06)

> A missing protection against path traversal allows to access
any file on the server.

### CVE-2025-41646
**kunbus revpi_status**
- **Signals:** CVSS
- **Asset:** kunbus revpi_status
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-10T19:29:22.893
- **CWE:** CWE-704
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-06)

> An unauthorized remote attacker can bypass the authentication of the affected software package by misusing an incorrect type conversion. This leads to full compromise of the device

### CVE-2025-47586
**Improper Control of Filename for Include/Require Statement in PHP Program ('PHP Remote File Inclusion') vulnerability in StylemixThemes M...**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:30:32.920
- **CWE:** CWE-98
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-06-06)

> Improper Control of Filename for Include/Require Statement in PHP Program ('PHP Remote File Inclusion') vulnerability in StylemixThemes Motors - Events stm-motors-events allows PHP Local File Inclusion.This issue affects Motors - Events: from n/a through <= 1.4.7.

### CVE-2025-48782
**scshr hr_portal**
- **Signals:** CVSS
- **Asset:** scshr hr_portal
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-04T14:38:52.423
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-06-06)

> An unrestricted upload of file with dangerous type vulnerability in the upload file function of Soar Cloud HRD Human Resource Management System through version 7.3.2025.0408 allows remote attackers to execute arbitrary system commands via a malicious file.

### CVE-2025-49072
**Deserialization of Untrusted Data vulnerability in AncoraThemes Mr.**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:16.860
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-06)

> Deserialization of Untrusted Data vulnerability in AncoraThemes Mr. Murphy mr-murphy allows Object Injection.This issue affects Mr. Murphy: from n/a through < 1.2.12.1.

### CVE-2025-49073
**axiomthemes sweet_dessert Deserialization**
- **Signals:** CVSS
- **Asset:** axiomthemes sweet_dessert
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T15:31:16.973
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-06)

> Deserialization of Untrusted Data vulnerability in axiomthemes Sweet Dessert sweet-dessert allows Object Injection.This issue affects Sweet Dessert: from n/a through < 1.1.13.

### CVE-2025-5192
**scshr hr_portal**
- **Signals:** CVSS
- **Asset:** scshr hr_portal
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-04T14:28:22.197
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-06)

> A missing authentication for critical function vulnerability in the client application of Soar Cloud HRD Human Resource Management System through version 7.3.2025.0408 allows remote attackers to bypass authentication and access application functions.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-06*
