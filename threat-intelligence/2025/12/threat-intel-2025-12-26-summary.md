# Daily Threat Intelligence — December 26, 2025

**Digest window (UTC):** 2025-12-26
**Generated:** 2026-06-02T07:34:03Z

## Threat brief

5 new critical disclosures — review patch status on exposed services.

## Executive summary

- 5 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 5 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2025-68668
**n8n n8n privilege escalation**
- **Signals:** CVSS
- **Asset:** n8n n8n
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2026-01-05T17:15:46.633
- **CWE:** CWE-693
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-26)

> n8n is an open source workflow automation platform. From version 1.0.0 to before 2.0.0, a sandbox bypass vulnerability exists in the Python Code Node that uses Pyodide. An authenticated user with permission to create or modify workflows can exploit this vulnerability to execute a…

### CVE-2024-44065
**magicbug cloudlog SQL Injection**
- **Signals:** CVSS
- **Asset:** magicbug cloudlog
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T21:35:07.857
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-26)

> Time-based blind SQL Injection vulnerability in Cloudlog v2.6.15 at the endpoint /index.php/logbookadvanced/search in the qsoresults parameter.

### CVE-2025-13915
**ibm api_connect**
- **Signals:** CVSS
- **Asset:** ibm api_connect
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T21:37:43.290
- **CWE:** CWE-305
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-26)

> IBM API Connect 10.0.8.0 through 10.0.8.5, and 10.0.11.0 could allow a remote attacker to bypass authentication mechanisms and gain unauthorized access to the application.

### CVE-2025-13158
**Prototype pollution vulnerability in apidoc-core versions 0.2.0 and all subsequent versions allows remote attackers to modify JavaScript...**
- **Signals:** CVSS
- **Attack:** DoS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-26)

> Prototype pollution vulnerability in apidoc-core versions 0.2.0 and all subsequent versions allows remote attackers to modify JavaScript object prototypes via malformed data structures, including the “define” property processed by the application, potentially leading to denial of…

### CVE-2025-68937
**Forgejo before 13.0.2 allows attackers to write to unintended files, and possibly obtain server shell access, because of mishandling of o...**
- **Signals:** CVSS
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-61
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-12-26)

> Forgejo before 13.0.2 allows attackers to write to unintended files, and possibly obtain server shell access, because of mishandling of out-of-repository symlink destinations for template repositories. This is also fixed for 11 LTS in 11.0.7 and later.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-26*
