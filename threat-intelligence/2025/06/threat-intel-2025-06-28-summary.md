# Daily Threat Intelligence — June 28, 2025

**Digest window (UTC):** 2025-06-28
**Generated:** 2026-06-02T07:32:58Z

## Threat brief

3 new critical disclosures — review patch status on exposed services.

## Executive summary

- 3 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 3 |
| Patch status change | 0 |
| **Total** | **3** |


## CVEs

### CVE-2025-32897
**apache seata Deserialization**
- **Signals:** CVSS
- **Asset:** apache seata
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-30T09:16:14.977
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-28)

> Deserialization of Untrusted Data vulnerability in Apache Seata (incubating).

This security vulnerability is the same as CVE-2024-47552, but the version range described in the CVE-2024-47552 definition is too narrow.
This issue affects Apache Seata (incubating): from 2.0.0 befor…

### CVE-2025-5304
**ptoffice pt_project_notebooks Privilege Escalation**
- **Signals:** CVSS
- **Asset:** ptoffice pt_project_notebooks
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-07T14:47:29.020
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-28)

> The PT Project Notebooks plugin for WordPress is vulnerable to Privilege Escalation due to missing authorization in the wpnb_pto_new_users_add() function in versions 1.0.0 through 1.1.3. This makes it possible for unauthenticated attackers to elevate their privileges to that of a…

### CVE-2025-53391
**The Debian zuluPolkit/CMakeLists.txt file for zuluCrypt through the zulucrypt_6.2.0-1 package has insecure PolicyKit allow_any/allow_inac...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-28)

> The Debian zuluPolkit/CMakeLists.txt file for zuluCrypt through the zulucrypt_6.2.0-1 package has insecure PolicyKit allow_any/allow_inactive/allow_active settings that allow a local user to escalate their privileges to root.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-28*
