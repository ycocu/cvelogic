# Daily Threat Intelligence — December 01, 2025

**Digest window (UTC):** 2025-12-01
**Generated:** 2026-06-02T07:33:53Z

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

### CVE-2025-63531
**shridharshukl blood_bank_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** shridharshukl blood_bank_management_system
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-02T03:03:24.593
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-12-01)

> A SQL injection vulnerability exists in the Blood Bank Management System 1.0 within the receiverLogin.php component. The application fails to properly sanitize user-supplied input in SQL queries, allowing an attacker to inject arbitrary SQL code. By manipulating the remail and rp…

### CVE-2025-51682
**mjobtime mjobtime privilege escalation**
- **Signals:** CVSS
- **Asset:** mjobtime mjobtime
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-04T18:21:39.747
- **CWE:** CWE-602
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-01)

> mJobtime 15.7.2 handles authorization on the client side, which allows an attacker to modify the client-side code and gain access to administrative features. Additionally, they can craft requests based on the client-side code to call these administrative functions directly.

### CVE-2025-51683
**mjobtime mjobtime SQL Injection**
- **Signals:** CVSS
- **Asset:** mjobtime mjobtime
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-04T18:16:35.267
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-01)

> A blind SQL Injection (SQLi) vulnerability in mJobtime v15.7.2 allows unauthenticated attackers to execute arbitrary SQL statements via a crafted POST request to the /Default.aspx/update_profile_Server endpoint .

### CVE-2025-3500
**avast antivirus Privilege Escalation**
- **Signals:** CVSS
- **Asset:** avast antivirus
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-06T15:34:52.030
- **CWE:** CWE-190
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-12-01)

> Integer Overflow or Wraparound vulnerability in Avast Antivirus (25.1.981.6) on Windows allows Privilege Escalation.This issue affects Antivirus: from 25.1.981.6 before 25.3.

### CVE-2025-63525
**shridharshukl blood_bank_management_system privilege escalation**
- **Signals:** CVSS
- **Asset:** shridharshukl blood_bank_management_system
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD modified:** 2026-01-06T21:15:43.240
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-12-01)

> An issue was discovered in Blood Bank Management System 1.0 allowing authenticated attackers to perform actions with escalated privileges via crafted request to delete.php.

### CVE-2025-63532
**shridharshukl blood_bank_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** shridharshukl blood_bank_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-04T18:08:16.560
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-12-01)

> A SQL injection vulnerability exists in the Blood Bank Management System 1.0 within the cancel.php component. The application fails to properly sanitize user-supplied input in SQL queries, allowing an attacker to inject arbitrary SQL code. By manipulating the search field, an att…

### CVE-2025-63535
**shridharshukl blood_bank_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** shridharshukl blood_bank_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-03T22:00:15.117
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-12-01)

> A SQL injection vulnerability exists in the Blood Bank Management System 1.0 within the abs.php component. The application fails to properly sanitize usersupplied input in SQL queries, allowing an attacker to inject arbitrary SQL code. By manipulating the search field, an attacke…

### CVE-2025-65836
**publiccms publiccms SSRF**
- **Signals:** CVSS
- **Asset:** publiccms publiccms
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-04T18:09:55.590
- **CWE:** CWE-918
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-01)

> PublicCMS V5.202506.b is vulnerable to SSRF. in the chat interface of SimpleAiAdminController.

### CVE-2025-66401
**kapilduraphe mcp_watch Command Injection**
- **Signals:** CVSS
- **Asset:** kapilduraphe mcp_watch
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-06T16:34:33.003
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-01)

> MCP Watch is a comprehensive security scanner for Model Context Protocol (MCP) servers. In 0.1.2 and earlier, the MCPScanner class contains a critical Command Injection vulnerability in the cloneRepo method. The application passes the user-supplied githubUrl argument directly to …

### CVE-2025-8351
**Heap-based Buffer Overflow, Out-of-bounds Read vulnerability in Avast Antivirus on MacOS when scanning a malformed file may allow Local E...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-122
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-12-01)

> Heap-based Buffer Overflow, Out-of-bounds Read vulnerability in Avast Antivirus on MacOS when scanning a malformed file may allow Local Execution of Code or Denial-of-Service of the anitvirus engine process.This issue affects Antivirus: from 8.3.70.94 before 8.3.70.98.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-01*
