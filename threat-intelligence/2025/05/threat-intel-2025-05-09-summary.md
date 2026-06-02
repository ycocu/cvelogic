# Daily Threat Intelligence — May 09, 2025

**Digest window (UTC):** 2025-05-09
**Generated:** 2026-06-02T07:32:41Z

## Threat brief

Apache Activemq: public exploit or PoC linked (DoS) · Microsoft Index Server — exploitation likelihood rose sharply (EPSS 67% → 83% · rising (+16%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apache Activemq: public exploit or PoC linked (DoS)
- Microsoft Index Server — exploitation likelihood rose sharply (EPSS 67% → 83% · rising (+16%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 5 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2024-21111
**oracle vm_virtualbox privilege escalation**
- **Signals:** EXP
- **Asset:** oracle vm_virtualbox
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2025-05-09T18:16:03.100
- **CWE:** CWE-269
- **Risk score:** 78
- **EXP:** ref published 2025-05-09

> Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).  Supported versions that are affected are Prior to 7.0.16. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Oracle VM VirtualBox exe…

### CVE-2024-38193
**Microsoft Windows Ancillary Function Driver for WinSock Privilege Escalation Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **Attack:** Privilege Escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T14:18:22.977
- **CWE:** CWE-416
- **Risk score:** 78
- **EXP:** ref published 2025-05-09

> Windows Ancillary Function Driver for WinSock Elevation of Privilege Vulnerability

### CVE-2000-0098
**microsoft index_server**
- **Signals:** EPSS
- **Asset:** microsoft index_server
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 67.1% (2025-03-30) → 82.7% (2025-05-09), Δ +15.6%**

> Microsoft Index Server allows remote attackers to determine the real path for a web directory via a request to an Internet Data Query file that does not exist.

### CVE-2025-2011
**The Slider & Popup Builder by Depicter plugin for WordPress is vulnerable to generic SQL Injection via the ‘s' parameter in all versions...**
- **Signals:** EXP
- **Attack:** SQL Injection
- **CVSS max:** 7.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-05-09

> The Slider & Popup Builder by Depicter plugin for WordPress is vulnerable to generic SQL Injection via the ‘s' parameter in all versions up to, and including, 3.6.1 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL …

### CVE-2025-27007
**Incorrect Privilege Assignment vulnerability in Brainstorm Force OttoKit suretriggers allows Privilege Escalation.This issue affects Otto...**
- **Signals:** EXP
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:26:14.197
- **CWE:** CWE-266
- **Risk score:** 78
- **EXP:** ref published 2025-05-09

> Incorrect Privilege Assignment vulnerability in Brainstorm Force OttoKit suretriggers allows Privilege Escalation.This issue affects OttoKit: from n/a through <= 1.0.82.

### CVE-2025-27533
**apache activemq DoS**
- **Signals:** EXP
- **Asset:** apache activemq
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:18:02.323
- **CWE:** CWE-789
- **Risk score:** 78
- **EXP:** ref published 2025-05-09

> Memory Allocation with Excessive Size Value vulnerability in Apache ActiveMQ.

During unmarshalling of OpenWire commands the size value of buffers was not properly validated which could lead to excessive memory allocation and be exploited to cause a denial of service (DoS) by dep…

### CVE-2025-28200
**govicture rx1800_firmware**
- **Signals:** CVSS
- **Asset:** govicture rx1800_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-12T16:35:09.547
- **CWE:** CWE-521
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-09)

> Victure RX1800 EN_V1.0.0_r12_110933 was discovered to utilize a weak default password which includes the last 8 digits of the Mac address.

### CVE-2025-45513
**tenda fh451_firmware**
- **Signals:** CVSS
- **Asset:** tenda fh451_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-24T00:51:51.153
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-09)

> Tenda FH451 V1.0.0.9 has a stack overflow vulnerability in the function.P2pListFilter.

### CVE-2025-45885
**phpgurukul vehicle_parking_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul vehicle_parking_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-28T13:40:22.817
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-09)

> PHPGURUKUL Vehicle Parking Management System v1.13 is vulnerable to SQL injection in the /vpms/users/login.php file. Attackers can inject malicious code from the parameter 'emailcont' and use it directly in SQL queries.

### CVE-2025-45887
**wanglongcn yifang SSRF**
- **Signals:** CVSS
- **Asset:** wanglongcn yifang
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-12T16:39:34.730
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-09)

> Yifang CMS v2.0.2 is vulnerable to Server-Side Request Forgery (SSRF) in /api/file/getRemoteContent.

### CVE-2025-46188
**lerouxyxchire client_database_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** lerouxyxchire client_database_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-22T19:03:17.713
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-09)

> SourceCodester Client Database Management System 1.0 is vulnerable to SQL Injection in superadmin_phpmyadmin.php.

### CVE-2025-46189
**lerouxyxchire client_database_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** lerouxyxchire client_database_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-22T19:01:31.820
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-09)

> SourceCodester Client Database Management System 1.0 is vulnerable to SQL Injection in user_order_customer_update.php via the order_id POST parameter.

### CVE-2025-46190
**lerouxyxchire client_database_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** lerouxyxchire client_database_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-22T18:51:35.560
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-09)

> SourceCodester Client Database Management System 1.0 is vulnerable to SQL Injection in user_delivery_update.php via the order_id POST parameter.

### CVE-2025-46191
**lerouxyxchire client_database_management_system**
- **Signals:** CVSS
- **Asset:** lerouxyxchire client_database_management_system
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-22T18:52:07.867
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-09)

> Arbitrary File Upload in user_payment_update.php in SourceCodester Client Database Management System 1.0 allows unauthenticated users to upload arbitrary files via the uploaded_file_cancelled field. Due to the absence of proper file extension checks, MIME type validation, and aut…

### CVE-2025-46192
**lerouxyxchire client_database_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** lerouxyxchire client_database_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-22T18:47:48.530
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-09)

> SourceCodester Client Database Management System 1.0 is vulnerable to SQL Injection in user_payment_update.php via the order_id POST parameter.

### CVE-2025-46193
**lerouxyxchire client_database_management_system RCE**
- **Signals:** CVSS
- **Asset:** lerouxyxchire client_database_management_system
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-22T18:49:22.817
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-09)

> SourceCodester Client Database Management System 1.0 is vulnerable to Remote code execution via Arbitrary file upload in user_proposal_update_order.php.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-09*
