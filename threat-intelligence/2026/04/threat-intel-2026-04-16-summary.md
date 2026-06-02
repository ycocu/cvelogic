# Daily Threat Intelligence — April 16, 2026

**Digest window (UTC):** 2026-04-16
**Generated:** 2026-06-02T07:34:56Z

## Threat brief

Apache ActiveMQ added to CISA KEV — confirmed in-the-wild exploitation. · Minidvblinux — exploitation likelihood rose sharply (EPSS 18% → 29% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apache ActiveMQ added to CISA KEV — confirmed in-the-wild exploitation.
- Minidvblinux — exploitation likelihood rose sharply (EPSS 18% → 29% · rising (+12%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2026-34197
**Apache ActiveMQ Improper Input Validation Vulnerability**
- **Signals:** KEV
- **Asset:** apache activemq
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-16T19:59:38.107
- **CWE:** CWE-20
- **Risk score:** 88
- **KEV:** added 2026-04-16

> Improper Input Validation, Improper Control of Generation of Code ('Code Injection') vulnerability in Apache ActiveMQ Broker, Apache ActiveMQ.

Apache ActiveMQ Classic exposes the Jolokia JMX-HTTP bridge at /api/jolokia/ on the web console. The default Jolokia access policy permi…

### CVE-2025-25038
**minidvblinux minidvblinux Command Injection**
- **Signals:** EPSS
- **Asset:** minidvblinux minidvblinux
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-22T17:46:41.027
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 17.7% (2026-03-06) → 29.2% (2026-04-16), Δ +11.5%**

> An OS command injection vulnerability exists in MiniDVBLinux version 5.4 and earlier. The system’s web-based management interface fails to properly sanitize user-supplied input before passing it to operating system commands. A remote unauthenticated attacker can exploit this vuln…

### CVE-2026-31843
**The goodoneuz/pay-uz Laravel package (<= 2.2.24) contains a critical vulnerability in the /payment/api/editable/update endpoint that allo...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-19T15:50:41.340
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-04-16)

> The goodoneuz/pay-uz Laravel package (<= 2.2.24) contains a critical vulnerability in the /payment/api/editable/update endpoint that allows unauthenticated attackers to overwrite existing PHP payment hook files. The endpoint is exposed via Route::any() without authentication midd…

### CVE-2026-3596
**The Riaxe Product Customizer plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 2.1.2.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-22T20:22:50.570
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-16)

> The Riaxe Product Customizer plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 2.1.2. The plugin registers an unauthenticated AJAX action ('wp_ajax_nopriv_install-imprint') that maps to the ink_pd_add_option() function. This function…

### CVE-2026-37338
**SourceCodester Simple Music Cloud Community System v1.0 is vulnerable to SQL Injection in the file /music/view_user.php.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-17T15:15:09.790
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-16)

> SourceCodester Simple Music Cloud Community System v1.0 is vulnerable to SQL Injection in the file /music/view_user.php.

### CVE-2026-37339
**SourceCodester Simple Music Cloud Community System v1.0 is vulnerable to SQL Injection in the file /music/view_genre.php.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-18T03:16:12.280
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-16)

> SourceCodester Simple Music Cloud Community System v1.0 is vulnerable to SQL Injection in the file /music/view_genre.php.

### CVE-2026-37340
**SourceCodester Simple Music Cloud Community System v1.0 is vulnerable to SQL Injection in the file /music/edit_music.php.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-18T03:16:12.437
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-16)

> SourceCodester Simple Music Cloud Community System v1.0 is vulnerable to SQL Injection in the file /music/edit_music.php.

### CVE-2026-37345
**SourceCodester Vehicle Parking Area Management System v1.0 is vulnerable to SQL Injection in the file /parking/manage_park.php.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-17T15:15:09.790
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-16)

> SourceCodester Vehicle Parking Area Management System v1.0 is vulnerable to SQL Injection in the file /parking/manage_park.php.

### CVE-2026-37347
**SourceCodester Payroll Management and Information System v1.0 is vulnerable to SQL Injection in the file /payroll/view_employee.php.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-17T15:15:09.790
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-16)

> SourceCodester Payroll Management and Information System v1.0 is vulnerable to SQL Injection in the file /payroll/view_employee.php.

### CVE-2026-40322
**b3log siyuan**
- **Signals:** CVSS
- **Asset:** b3log siyuan
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-20T14:51:24.213
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-04-16)

> SiYuan is an open-source personal knowledge management system. In versions 3.6.3 and below, Mermaid diagrams are rendered with securityLevel set to "loose", and the resulting SVG is injected into the DOM via innerHTML. This allows attacker-controlled javascript: URLs in Mermaid c…

### CVE-2026-5426
**Hard-coded ASP.NET/IIS machineKey value in Digital Knowledge KnowledgeDeliver deployments prior to February 24, 2026 allows adversaries t...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-26T19:16:29.123
- **CWE:** CWE-321
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-16)

> Hard-coded ASP.NET/IIS machineKey value in Digital Knowledge KnowledgeDeliver deployments prior to February 24, 2026 allows adversaries to circumvent ViewState validation mechanisms and achieve remote code execution via malicious ViewState deserialization attacks

### CVE-2026-6270
**fastify fastify\/middie**
- **Signals:** CVSS
- **Asset:** fastify fastify\/middie
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-14T15:41:44.877
- **CWE:** CWE-436
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-16)

> @fastify/middie versions 9.3.1 and earlier do not register inherited middleware directly on child plugin engine instances. When a Fastify application registers authentication middleware in a parent scope and then registers child plugins with @fastify/middie, the child scope does …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-16*
