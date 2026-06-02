# Daily Threat Intelligence — October 09, 2025

**Digest window (UTC):** 2025-10-09
**Generated:** 2026-06-02T07:33:33Z

## Threat brief

Grafana Labs Grafana added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Grafana Labs Grafana added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2021-43798
**Grafana Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** grafana grafana
- **Attack:** Directory Traversal
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T14:47:13.760
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2025-10-09

> Grafana is an open-source platform for monitoring and observability. Grafana versions 8.0.0-beta1 through 8.3.0 (except for patched versions) iss vulnerable to directory traversal, allowing access to local files. The vulnerable URL path is: `<grafana_host_url>/public/plugins//`, …

### CVE-2025-59246
**microsoft entra_id privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft entra_id
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-16T20:50:39.237
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-09)

> Azure Entra ID Elevation of Privilege Vulnerability

### CVE-2025-59218
**microsoft entra_id privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft entra_id
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-16T20:50:55.807
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-10-09)

> Azure Entra ID Elevation of Privilege Vulnerability

### CVE-2025-35050
**newforma project_center privilege escalation**
- **Signals:** CVSS
- **Asset:** newforma project_center
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-09T18:19:59.573
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-09)

> Newforma Info Exchange (NIX) accepts serialized .NET data via the '/remoteweb/remote.rem' endpoint, allowing a remote, unauthenticated attacker to execute arbitrary code with 'NT AUTHORITY\NetworkService' privileges. The vulnerable endpoint is used by Newforma Project Center Serv…

### CVE-2025-35051
**newforma project_center privilege escalation**
- **Signals:** CVSS
- **Asset:** newforma project_center
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-26T19:04:18.887
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-10-09)

> Newforma Project Center Server (NPCS) accepts serialized .NET data via the '/ProjectCenter.rem' endpoint on 9003/tcp, allowing a remote, unauthenticated attacker to execute arbitrary code with 'NT AUTHORITY\NetworkService' privileges. According to the recommended architecture, th…

### CVE-2025-55321
**microsoft azure_monitor XSS**
- **Signals:** CVSS
- **Asset:** microsoft azure_monitor
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2025-10-23T22:15:38.683
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-09)

> Improper neutralization of input during web page generation ('cross-site scripting') in Azure Monitor allows an unauthorized attacker to perform spoofing over a network.

### CVE-2025-59252
**microsoft 365_word_copilot Command Injection**
- **Signals:** CVSS
- **Asset:** microsoft 365_word_copilot
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2025-12-11T20:16:20.943
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-09)

> Improper neutralization of special elements used in a command ('command injection') in Copilot allows an unauthorized attacker to disclose information over a network.

### CVE-2025-59272
**microsoft 365_copilot_chat Command Injection**
- **Signals:** CVSS
- **Asset:** microsoft 365_copilot_chat
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2025-12-11T20:16:22.240
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-09)

> Improper neutralization of special elements used in a command ('command injection') in Copilot allows an unauthorized attacker to perform information disclosure locally.

### CVE-2025-59286
**microsoft 365_copilot_chat Command Injection**
- **Signals:** CVSS
- **Asset:** microsoft 365_copilot_chat
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2025-12-11T20:16:23.637
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-09)

> Improper neutralization of special elements used in a command ('command injection') in Copilot allows an unauthorized attacker to disclose information over a network.

### CVE-2025-60316
**mayurik pet_grooming_management_software SQL Injection**
- **Signals:** CVSS
- **Asset:** mayurik pet_grooming_management_software
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-16T15:25:18.447
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-09)

> SourceCodester Pet Grooming Management Software 1.0 is vulnerable to SQL Injection in admin/view_customer.php via the ID parameter.

### CVE-2025-61928
**Better Auth is an authentication and authorization library for TypeScript.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-09)

> Better Auth is an authentication and authorization library for TypeScript. In versions prior to 1.3.26, unauthenticated attackers can create or modify API keys for any user by passing that user's id in the request body to the `api/auth/api-key/create` route. `session?.user ?? (au…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-09*
