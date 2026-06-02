# Daily Threat Intelligence — May 23, 2025

**Digest window (UTC):** 2025-05-23
**Generated:** 2026-06-02T07:32:45Z

## Threat brief

Zohocorp Manageengine Supportcenter Plus — exploitation likelihood rose sharply (EPSS 7.3% → 42% · rising (+35%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Zohocorp Manageengine Supportcenter Plus — exploitation likelihood rose sharply (EPSS 7.3% → 42% · rising (+35%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2015-5149
**zohocorp manageengine_supportcenter_plus Directory Traversal**
- **Signals:** EPSS
- **Asset:** zohocorp manageengine_supportcenter_plus
- **Attack:** Directory Traversal
- **CVSS max:** 5.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-22
- **Risk score:** 79
- **EPSS 7.3% (2025-03-30) → 42.5% (2025-05-23), Δ +35.1%**

> Directory traversal vulnerability in Zoho ManageEngine SupportCenter Plus 7.90 allows remote authenticated users to write to arbitrary files via a .. (dot dot) in the component parameter in the Request component to workorder/Attachment.jsp.

### CVE-2015-1949
**ibm tivoli_storage_manager_fastback privilege escalation**
- **Signals:** EPSS
- **Asset:** ibm tivoli_storage_manager_fastback
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-77
- **Risk score:** 83
- **EPSS 4.1% (2025-03-30) → 14.4% (2025-05-23), Δ +10.2%**

> The server in IBM Tivoli Storage Manager FastBack 6.1 before 6.1.12 allows remote attackers to execute arbitrary commands with SYSTEM privileges via unspecified vectors.

### CVE-2025-47642
**Unrestricted Upload of File with Dangerous Type vulnerability in Ajar Productions Ajar in5 Embed ajar-productions-in5-embed allows Upload...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:30:39.893
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-23)

> Unrestricted Upload of File with Dangerous Type vulnerability in Ajar Productions Ajar in5 Embed ajar-productions-in5-embed allows Upload a Web Shell to a Web Server.This issue affects Ajar in5 Embed: from n/a through <= 3.1.5.

### CVE-2015-1938
**ibm tivoli_storage_manager_fastback**
- **Signals:** EPSS
- **Asset:** ibm tivoli_storage_manager_fastback
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-77
- **Risk score:** 83
- **EPSS 4.1% (2025-03-30) → 14.3% (2025-05-23), Δ +10.2%**

> The server in IBM Tivoli Storage Manager FastBack 6.1 before 6.1.12 allows remote attackers to execute arbitrary commands via unspecified vectors, a different vulnerability than CVE-2015-1986.

### CVE-2024-51101
**phpgurukul restaurant_table_booking_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul restaurant_table_booking_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-05-29T16:15:39.240
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-23)

> PHPGURUKUL Restaurant Table Booking System using PHP and MySQL v1.0 was discovered to contain a SQL injection vulnerability via the searchdata parameter at /rtbs/check-status.php.

### CVE-2024-51360
**phpgurukul hospital_management_system**
- **Signals:** CVSS
- **Asset:** phpgurukul hospital_management_system
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-05-29T16:15:39.787
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-23)

> An issue in Hospital Management System In PHP V4.0 allows a remote attacker to execute arbitrary code via the hms/doctor/edit-profile.php file

### CVE-2025-47646
**Weak Password Recovery Mechanism for Forgotten Password vulnerability in Gilblas Ngunte Possi PSW Front-end Login & Registration psw-logi...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-29T10:16:47.877
- **CWE:** CWE-640
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-23)

> Weak Password Recovery Mechanism for Forgotten Password vulnerability in Gilblas Ngunte Possi PSW Front-end Login & Registration psw-login-and-registration allows Password Recovery Exploitation.This issue affects PSW Front-end Login & Registration: from n/a through <= 1.13.

### CVE-2025-47658
**elula wsdesk**
- **Signals:** CVSS
- **Asset:** elula wsdesk
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T15:30:41.680
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-05-23)

> Unrestricted Upload of File with Dangerous Type vulnerability in ELEXtensions ELEX WordPress HelpDesk & Customer Ticketing System elex-helpdesk-customer-support-ticket-system allows Upload a Web Shell to a Web Server.This issue affects ELEX WordPress HelpDesk & Customer Ticketing…

### CVE-2025-47663
**Unrestricted Upload of File with Dangerous Type vulnerability in mojoomla Hospital Management System allows Upload a Web Shell to a Web S...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-28T19:32:31.833
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-05-23)

> Unrestricted Upload of File with Dangerous Type vulnerability in mojoomla Hospital Management System allows Upload a Web Shell to a Web Server. This issue affects Hospital Management System: from 47.0(20 through 11.

### CVE-2025-47687
**Unrestricted Upload of File with Dangerous Type vulnerability in StoreKeeper B.V.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:30:44.820
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-23)

> Unrestricted Upload of File with Dangerous Type vulnerability in StoreKeeper B.V. StoreKeeper for WooCommerce storekeeper-for-woocommerce allows Upload a Web Shell to a Web Server.This issue affects StoreKeeper for WooCommerce: from n/a through <= 14.4.4.

### CVE-2025-48283
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Majestic Support Majestic Support m...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:01.713
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-23)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Majestic Support Majestic Support majestic-support allows SQL Injection.This issue affects Majestic Support: from n/a through <= 1.1.0.

### CVE-2025-48287
**Deserialization of Untrusted Data vulnerability in Pagaleve Pix 4x sem juros - Pagaleve wc-pagaleve allows Object Injection.This issue af...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:02.190
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-23)

> Deserialization of Untrusted Data vulnerability in Pagaleve Pix 4x sem juros - Pagaleve wc-pagaleve allows Object Injection.This issue affects Pix 4x sem juros - Pagaleve: from n/a through <= 1.6.9.

### CVE-2025-48289
**Deserialization of Untrusted Data vulnerability in AncoraThemes Kids Planet kidsplanet allows Object Injection.This issue affects Kids Pl...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:02.403
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-23)

> Deserialization of Untrusted Data vulnerability in AncoraThemes Kids Planet kidsplanet allows Object Injection.This issue affects Kids Planet: from n/a through <= 2.2.14.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-23*
