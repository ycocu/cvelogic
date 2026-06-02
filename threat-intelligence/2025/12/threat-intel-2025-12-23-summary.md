# Daily Threat Intelligence — December 23, 2025

**Digest window (UTC):** 2025-12-23
**Generated:** 2026-06-02T07:34:02Z

## Threat brief

Boldgrid W3 Total Cache — exploitation likelihood rose sharply (EPSS 1.1% → 42% · rising (+40%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Boldgrid W3 Total Cache — exploitation likelihood rose sharply (EPSS 1.1% → 42% · rising (+40%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2012-6077
**boldgrid w3_total_cache**
- **Signals:** EPSS
- **Asset:** boldgrid w3_total_cache
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T01:45:46.337
- **CWE:** CWE-200
- **Risk score:** 82
- **EPSS 1.1% (2025-03-30) → 41.5% (2025-12-23), Δ +40.4%**

> W3 Total Cache before 0.9.2.5 allows remote attackers to retrieve password hash information due to insecure storage of database cache files.

### CVE-2022-22955
**vmware identity_manager Auth Bypass**
- **Signals:** EPSS
- **Asset:** vmware identity_manager
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:47:40.777
- **Risk score:** 86
- **EPSS 38.6% (2025-12-09) → 70.1% (2025-12-23), Δ +31.5%**

> VMware Workspace ONE Access has two authentication bypass vulnerabilities (CVE-2022-22955 & CVE-2022-22956) in the OAuth2 ACS framework. A malicious actor may bypass the authentication mechanism and execute any operation due to exposed endpoints in the authentication framework.

### CVE-2025-14931
**Hugging Face smolagents Remote Python Executor Deserialization of Untrusted Data Remote Code Execution Vulnerability.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-12-23)

> Hugging Face smolagents Remote Python Executor Deserialization of Untrusted Data Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of Hugging Face smolagents. Authentication is not required to explo…

### CVE-2025-14500
**IceWarp14 X-File-Operation Command Injection Remote Code Execution Vulnerability.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-23)

> IceWarp14 X-File-Operation Command Injection Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of IceWarp. Authentication is not required to exploit this vulnerability.

The specific flaw exists wit…

### CVE-2025-66209
**coollabs coolify Command Injection**
- **Signals:** CVSS
- **Asset:** coollabs coolify
- **Attack:** Command Injection
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2026-03-17T17:16:13.907
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-23)

> Coolify is an open-source and self-hostable tool for managing servers, applications, and databases. Prior to version 4.0.0-beta.451, an authenticated command injection vulnerability in the Database Backup functionality allows users with application/service management permissions …

### CVE-2025-66210
**coollabs coolify Command Injection**
- **Signals:** CVSS
- **Asset:** coollabs coolify
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2026-03-17T17:16:14.147
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-12-23)

> Coolify is an open-source and self-hostable tool for managing servers, applications, and databases. Prior to version 4.0.0-beta.451, an authenticated command injection vulnerability in the Database Import functionality allows users with application/service management permissions …

### CVE-2025-66211
**coollabs coolify Command Injection**
- **Signals:** CVSS
- **Asset:** coollabs coolify
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2026-03-17T17:16:14.323
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-12-23)

> Coolify is an open-source and self-hostable tool for managing servers, applications, and databases. Prior to version 4.0.0-beta.451, an authenticated command injection vulnerability in PostgreSQL Init Script Filename handling allows users with application/service management permi…

### CVE-2025-66212
**coollabs coolify Command Injection**
- **Signals:** CVSS
- **Asset:** coollabs coolify
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2026-03-17T17:16:14.493
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-12-23)

> Coolify is an open-source and self-hostable tool for managing servers, applications, and databases. Prior to version 4.0.0-beta.451, an authenticated command injection vulnerability in the Dynamic Proxy Configuration Filename handling allows users with application/service managem…

### CVE-2025-66213
**coollabs coolify Command Injection**
- **Signals:** CVSS
- **Asset:** coollabs coolify
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2026-03-17T17:16:14.670
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-12-23)

> Coolify is an open-source and self-hostable tool for managing servers, applications, and databases. Prior to version 4.0.0-beta.451, an authenticated command injection vulnerability in the File Storage Directory Mount Path functionality allows users with application/service manag…

### CVE-2025-68664
**langchain langchain_core**
- **Signals:** CVSS
- **Asset:** langchain langchain_core
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-13T15:58:23.373
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-23)

> LangChain is a framework for building agents and LLM-powered applications. Prior to versions 0.3.81 and 1.2.5, a serialization injection vulnerability exists in LangChain's dumps() and dumpd() functions. The functions do not escape dictionaries with 'lc' keys when serializing fre…

### CVE-2025-68667
**Conduit is a chat server powered by Matrix.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-23)

> Conduit is a chat server powered by Matrix. A vulnerability that affects a number of Conduit-derived homeservers allows a remote, unauthenticated attacker to force the target server to cryptographically sign arbitrary membership events. Affected products include Conduit prior to …

### CVE-2025-68669
**5ire 5ire RCE**
- **Signals:** CVSS
- **Asset:** 5ire 5ire
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD modified:** 2026-02-06T20:16:08.757
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-12-23)

> 5ire is a cross-platform desktop artificial intelligence assistant and model context protocol client. In versions 0.15.2 and prior, an RCE vulnerability exists in useMarkdown.ts, where the markdown-it-mermaid plugin is initialized with securityLevel: 'loose'. This configuration e…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-23*
