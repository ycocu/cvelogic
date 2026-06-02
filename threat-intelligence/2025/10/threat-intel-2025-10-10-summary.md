# Daily Threat Intelligence — October 10, 2025

**Digest window (UTC):** 2025-10-10
**Generated:** 2026-06-02T07:33:34Z

## Threat brief

Sysaid — exploitation likelihood rose sharply (EPSS 68% → 81% · rising (+13%)). · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- Sysaid — exploitation likelihood rose sharply (EPSS 68% → 81% · rising (+13%)).
- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2015-2997
**sysaid sysaid Directory Traversal**
- **Signals:** EPSS
- **Asset:** sysaid sysaid
- **Attack:** Directory Traversal
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-200
- **Risk score:** 78
- **EPSS 67.6% (2025-10-09) → 80.8% (2025-10-10), Δ +13.2%**

> SysAid Help Desk before 15.2 allows remote attackers to obtain sensitive information via an invalid value in the accountid parameter to getAgentLogFile, as demonstrated by a large directory traversal sequence, which reveals the installation path in an error message.

### CVE-2025-60306
**code-projects simple_car_rental_system privilege escalation**
- **Signals:** CVSS
- **Asset:** code-projects simple_car_rental_system
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-16T15:40:45.507
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-10-10)

> code-projects Simple Car Rental System 1.0 has a permission bypass issue where low privilege users can forge high privilege sessions and perform sensitive operations.

### CVE-2025-60307
**carmelo computer_laboratory_system SQL Injection**
- **Signals:** CVSS
- **Asset:** carmelo computer_laboratory_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-21T17:41:41.817
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-10)

> code-projects Computer Laboratory System 1.0 has a SQL injection vulnerability, where entering a universal password in the Password field on the login page can bypass login attempts.

### CVE-2025-60269
**huayi-tec jeewms SQL Injection**
- **Signals:** CVSS
- **Asset:** huayi-tec jeewms
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-16T15:40:08.307
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-10)

> JEEWMS 20250820 is vulnerable to SQL Injection in the exportXls function located in the src/main/java/org/jeecgframework/web/cgreport/controller/excel/CgExportExcelController.java file.

### CVE-2025-61929
**cherry-ai cherry_studio**
- **Signals:** CVSS
- **Asset:** cherry-ai cherry_studio
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-04T17:47:27.223
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-10-10)

> Cherry Studio is a desktop client that supports for multiple LLM providers. Cherry Studio registers a custom protocol called `cherrystudio://`. When handling the MCP installation URL, it parses the base64-encoded configuration data and directly executes the command within it. In …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-10*
