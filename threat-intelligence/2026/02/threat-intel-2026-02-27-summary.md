# Daily Threat Intelligence — February 27, 2026

**Digest window (UTC):** 2026-02-27
**Generated:** 2026-06-02T07:34:32Z

## Threat brief

Fetchmail — exploitation likelihood rose sharply (EPSS 13% → 33% · rising (+20%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Fetchmail — exploitation likelihood rose sharply (EPSS 13% → 33% · rising (+20%)).
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

### CVE-2001-1009
**fetchmail fetchmail privilege escalation**
- **Signals:** EPSS
- **Asset:** fetchmail fetchmail
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-264
- **Risk score:** 86
- **EPSS 13.1% (2025-06-17) → 33.3% (2026-02-27), Δ +20.1%**

> Fetchmail (aka fetchmail-ssl) before 5.8.17 allows a remote malicious (1) IMAP server or (2) POP/POP3 server to overwrite arbitrary memory and possibly gain privileges via a negative index number as part of a response to a LIST request.

### CVE-2026-28409
**wegia wegia RCE**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-03T18:20:07.170
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-27)

> WeGIA is a web manager for charitable institutions. Prior to version 3.6.5, a critical Remote Code Execution (RCE) vulnerability exists in the WeGIA application's database restoration functionality. An attacker with administrative access (which can be obtained via the previously …

### CVE-2026-28268
**vikunja vikunja**
- **Signals:** CVSS
- **Asset:** vikunja vikunja
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T21:03:09.780
- **CWE:** CWE-459
- **CWE:** CWE-640
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-27)

> Vikunja is an open-source self-hosted task management platform. Versions prior to 2.1.0 have a business logic vulnerability exists in the password reset mechanism of vikunja/api that allows password reset tokens to be reused indefinitely. Due to a failure to invalidate tokens upo…

### CVE-2026-27751
**sodola-network sl902-swtgw124as_firmware**
- **Signals:** CVSS
- **Asset:** sodola-network sl902-swtgw124as_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T02:08:00.523
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-27)

> SODOLA SL902-SWTGW124AS firmware versions through 200.1.20 contain a default credentials vulnerability that allows remote attackers to obtain administrative access to the management interface. Attackers can authenticate using the hardcoded default credentials without password cha…

### CVE-2026-27755
**sodola-network sl902-swtgw124as_firmware**
- **Signals:** CVSS
- **Asset:** sodola-network sl902-swtgw124as_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-03T19:09:12.973
- **CWE:** CWE-330
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-27)

> SODOLA SL902-SWTGW124AS firmware versions through 200.1.20 contain a weak session identifier generation vulnerability that allows attackers to forge authenticated sessions by computing predictable MD5-based cookies. Attackers who know or guess valid credentials can calculate the …

### CVE-2026-27947
**intermesh group-office RCE**
- **Signals:** CVSS
- **Asset:** intermesh group-office
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T16:07:30.840
- **CWE:** CWE-88
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-27)

> Group-Office is an enterprise customer relationship management and groupware tool. Versions prior to 26.0.9, 25.0.87, and 6.8.154 have an authenticated Remote Code Execution vulnerability in the TNEF attachment processing flow. The vulnerable path extracts attacker-controlled fil…

### CVE-2026-28408
**wegia wegia**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-03T18:22:19.377
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-27)

> WeGIA is a web manager for charitable institutions. Prior to version 3.6.5, the script in adicionar_tipo_docs_atendido.php does not go through the project's central controller and does not have its own authentication and permission checks. A malicious user could make a request th…

### CVE-2026-28411
**wegia wegia**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-03T17:56:18.417
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-27)

> WeGIA is a web manager for charitable institutions. Prior to version 3.6.5, an unsafe use of the `extract()` function on the `$_REQUEST` superglobal allows an unauthenticated attacker to overwrite local variables in multiple PHP scripts. This vulnerability can be leveraged to com…

### CVE-2026-28515
**opendcim opendcim privilege escalation**
- **Signals:** CVSS
- **Asset:** opendcim opendcim
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T15:03:39.680
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-27)

> openDCIM version 23.04, through commit 4467e9c4, contains a missing authorization vulnerability in install.php and container-install.php. The installer and upgrade handler expose LDAP configuration functionality without enforcing application role checks. Any authenticated user ca…

### CVE-2026-28516
**opendcim opendcim SQL Injection**
- **Signals:** CVSS
- **Asset:** opendcim opendcim
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T14:46:09.200
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-27)

> openDCIM version 23.04, through commit 4467e9c4, contains a SQL injection vulnerability in Config::UpdateParameter. The install.php and container-install.php handlers pass user-supplied input directly into SQL statements using string interpolation without prepared statements or p…

### CVE-2026-28517
**opendcim opendcim Command Injection**
- **Signals:** CVSS
- **Asset:** opendcim opendcim
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-12T01:16:45.947
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-27)

> openDCIM version 23.04, through commit 4467e9c4, contains an OS command injection vulnerability in report_network_map.php. The application retrieves the 'dot' configuration parameter from the database and passes it directly to exec() without validation or sanitization. If an atta…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-27*
