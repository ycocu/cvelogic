# Daily Threat Intelligence — December 08, 2025

**Digest window (UTC):** 2025-12-08
**Generated:** 2026-06-02T07:33:56Z

## Threat brief

Array Networks ArrayOS AG added to CISA KEV — confirmed in-the-wild exploitation. · Pluck-cms Pluck: public exploit or PoC linked · Apache Dolphinscheduler — exploitation likelihood rose sharply (EPSS 7.3% → 21% · rising (+14%)). · 7 new critical disclosures — review patch status on exposed services.

## Executive summary

- Array Networks ArrayOS AG added to CISA KEV — confirmed in-the-wild exploitation.
- Pluck-cms Pluck: public exploit or PoC linked
- Apache Dolphinscheduler — exploitation likelihood rose sharply (EPSS 7.3% → 21% · rising (+14%)).
- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 1 |
| EPSS rise | 2 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2022-37055
**D-Link Routers Buffer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** dlink go-rt-ac750_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T02:00:02.557
- **CWE:** CWE-120
- **CWE:** CWE-120
- **Risk score:** 88
- **KEV:** added 2025-12-08

> D-Link Go-RT-AC750 GORTAC750_revA_v101b03 and GO-RT-AC750_revB_FWv200b02 are vulnerable to Buffer Overflow via cgibin, hnap_main,

### CVE-2018-11736
**pluck-cms pluck**
- **Signals:** EXP
- **Asset:** pluck-cms pluck
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:43:55.887
- **CWE:** CWE-434
- **Risk score:** 78
- **EXP:** ref published 2025-12-08

> An issue was discovered in Pluck before 4.7.7-dev2. /data/inc/images.php allows remote attackers to upload and execute arbitrary PHP code by using the image/jpeg content type for a .htaccess file.

### CVE-2022-45462
**apache dolphinscheduler Command Injection**
- **Signals:** EPSS
- **Asset:** apache dolphinscheduler
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-25T19:15:47.260
- **CWE:** CWE-77
- **Risk score:** 86
- **EPSS 7.3% (2025-11-30) → 21.3% (2025-12-08), Δ +13.9%**

> Alarm instance management has command injection when there is a specific command configured. It is only for logged-in users. We recommend you upgrade to version 2.0.6 or higher

### CVE-2008-1809
**novell edirectory Buffer Overflow**
- **Signals:** EPSS
- **Asset:** novell edirectory
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 22.9% (2025-03-30) → 33.3% (2025-12-08), Δ +10.4%**

> Heap-based buffer overflow in Novell eDirectory 8.7.3 before 8.7.3.10b, and 8.8 before 8.8.2 FTF2, allows remote attackers to execute arbitrary code via an LDAP search request containing "NULL search parameters."

### CVE-2025-27019
**nokia infinera_mtc-9_firmware**
- **Signals:** CVSS
- **Asset:** nokia infinera_mtc-9_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-22T18:55:45.403
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-08)

> Remote shell service (RSH) in Infinera MTC-9 version R22.1.1.0275 allows
 an attacker to utilize password-less user accounts and obtain 
system access by activating a reverse shell.This issue affects MTC-9: from R22.1.1.0275 before R23.0.

### CVE-2025-27020
**nokia infinera_mtc-9_firmware**
- **Signals:** CVSS
- **Asset:** nokia infinera_mtc-9_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-22T18:55:35.403
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-08)

> Improper configuration of the SSH service in Infinera MTC-9 allows an unauthenticated attacker to execute arbitrary commands and access data on file system

.


This issue affects MTC-9: from R22.1.1.0275 before R23.0.

### CVE-2025-48626
**google android privilege escalation**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-12-08T21:16:01.437
- **CWE:** CWE-693
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-08)

> In multiple locations, there is a possible way to launch an application from the background due to a precondition check failure. This could lead to remote escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2025-61318
**emlog emlog Directory Traversal**
- **Signals:** CVSS
- **Asset:** emlog emlog
- **Attack:** Directory Traversal
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-09T16:17:50.223
- **CWE:** CWE-24
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-08)

> Emlog Pro 2.5.20 has an arbitrary file deletion vulnerability. This vulnerability stems from the admin/template.php component and the admin/plugin.php component. They fail to perform path verification and dangerous code filtering for deletion parameters, allowing attackers to exp…

### CVE-2025-64081
**pamzey patients_waiting_area_queue_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** pamzey patients_waiting_area_queue_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-12-08T22:15:52.810
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-08)

> SQL injection vulnerability in /php/api_patient_schedule.php in SourceCodester Patients Waiting Area Queue Management System v1 allows attackers to execute arbitrary SQL commands via the appointmentID parameter.

### CVE-2025-65548
**cashu nutshell**
- **Signals:** CVSS
- **Asset:** cashu nutshell
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-15T15:56:44.717
- **CWE:** CWE-1284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-08)

> NUT-14 allows cashu tokens to be created with a preimage hash. However, nutshell (cashubtc/nuts) before 0.18.0 do not validate the size of preimage when the token is spent. The preimage is stored by the mint and attacker can exploit this vulnerability to fill the mint's db nd dis…

### CVE-2025-65849
**A cryptanalytic break in Altcha Proof-of-Work obfuscation mode version 0.8.0 and later allows for remote visitors to recover the Proof-of...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-327
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-08)

> A cryptanalytic break in Altcha Proof-of-Work obfuscation mode version 0.8.0 and later allows for remote visitors to recover the Proof-of-Work nonce in constant time via mathematical deduction. NOTE: this is disputed by the Supplier because the product's objective is "to discoura…

### CVE-2025-66644
**Array Networks ArrayOS AG OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** arraynetworks arrayos_ag
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T02:00:02.557
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2025-12-08

> Array Networks ArrayOS AG before 9.4.5.9 allows command injection, as exploited in the wild in August through December 2025.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-08*
