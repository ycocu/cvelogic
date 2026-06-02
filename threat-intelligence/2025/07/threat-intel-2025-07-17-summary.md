# Daily Threat Intelligence — July 17, 2025

**Digest window (UTC):** 2025-07-17
**Generated:** 2026-06-02T07:33:04Z

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

### CVE-2025-25257
**Fortinet FortiWeb SQL Injection Vulnerability**
- **Signals:** CVSS
- **Asset:** fortinet fortiweb
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T16:49:01.030
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-17)

> An improper neutralization of special elements used in an SQL command ('SQL Injection') vulnerability [CWE-89] vulnerability in Fortinet FortiWeb 7.6.0 through 7.6.3, FortiWeb 7.4.0 through 7.4.7, FortiWeb 7.2.0 through 7.2.10, FortiWeb 7.0.0 through 7.0.10 allows an unauthentica…

### CVE-2025-52046
**totolink a3300r_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** totolink a3300r_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-26T13:09:07.543
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-17)

> Totolink A3300R V17.0.0cu.596_B20250515 was found to contain a command injection vulnerability in the sub_4197C0 function via the mac and desc parameters. This vulnerability allows unauthenticated attackers to execute arbitrary commands via a crafted request.

### CVE-2025-50240
**nbcio-boot v1.0.3 was discovered to contain a SQL injection vulnerability via the userIds parameter at /sys/user/deleteRecycleBin.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-17)

> nbcio-boot v1.0.3 was discovered to contain a SQL injection vulnerability via the userIds parameter at /sys/user/deleteRecycleBin.

### CVE-2025-23266
**NVIDIA Container Toolkit for all platforms contains a vulnerability in some hooks used to initialize the container, where an attacker cou...**
- **Signals:** CVSS
- **Attack:** DoS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-426
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-07-17)

> NVIDIA Container Toolkit for all platforms contains a vulnerability in some hooks used to initialize the container, where an attacker could execute arbitrary code with elevated permissions. A successful exploit of this vulnerability might lead to escalation of privileges, data ta…

### CVE-2025-53867
**Island Lake WebBatch before 2025C allows Remote Code Execution via a crafted URL.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-17)

> Island Lake WebBatch before 2025C allows Remote Code Execution via a crafted URL.

### CVE-2025-53964
**goldendict goldendict**
- **Signals:** CVSS
- **Asset:** goldendict goldendict
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T16:43:59.190
- **CWE:** CWE-749
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-07-17)

> GoldenDict 1.5.0 and 1.5.1 has an exposed dangerous method that allows reading and modifying files when a user adds a crafted dictionary and then searches for any term included in that dictionary.

### CVE-2025-54060
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-30T19:57:48.837
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-17)

> WeGIA is an open source web manager with a focus on the Portuguese language and charitable institutions. A SQL Injection vulnerability was identified in versions prior to 3.4.6 in the `idatendido_familiares` parameter of the `/html/funcionario/dependente_editarInfoPessoal.php` en…

### CVE-2025-54061
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-30T19:57:59.433
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-17)

> WeGIA is an open source web manager with a focus on the Portuguese language and charitable institutions. A SQL Injection vulnerability was identified in versions prior to 3.4.6 in the `idatendido_familiares` parameter of the `/html/funcionario/dependente_editarDoc.php` endpoint. …

### CVE-2025-54062
**wegia wegia SQL Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-30T19:58:29.140
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-17)

> WeGIA is an open source web manager with a focus on the Portuguese language and charitable institutions. A SQL Injection vulnerability was identified in versions prior to 3.4.6 in the `/html/funcionario/profile_dependente.php` endpoint, specifically in the `id_dependente` paramet…

### CVE-2025-54068
**Laravel Livewire Code Injection Vulnerability**
- **Signals:** CVSS
- **Asset:** laravel livewire
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-20T18:36:12.533
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-07-17)

> Livewire is a full-stack framework for Laravel. In Livewire v3 up to and including v3.6.3, a vulnerability allows unauthenticated attackers to achieve remote command execution in specific scenarios. The issue stems from how certain component property updates are hydrated. This vu…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-17*
