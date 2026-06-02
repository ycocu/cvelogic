# Daily Threat Intelligence — June 19, 2025

**Digest window (UTC):** 2025-06-19
**Generated:** 2026-06-02T07:32:54Z

## Threat brief

Adobe Air — exploitation likelihood rose sharply (EPSS 52% → 71% · rising (+19%)). · 7 new critical disclosures — review patch status on exposed services.

## Executive summary

- Adobe Air — exploitation likelihood rose sharply (EPSS 52% → 71% · rising (+19%)).
- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **9** |


## CVEs

### CVE-2015-5574
**adobe air Use-After-Free**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** Use-After-Free
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 86
- **EPSS 52.3% (2025-03-30) → 71.0% (2025-06-19), Δ +18.7%**

> Use-after-free vulnerability in Adobe Flash Player before 18.0.0.241 and 19.x before 19.0.0.185 on Windows and OS X and before 11.2.202.521 on Linux, Adobe AIR before 19.0.0.190, Adobe AIR SDK before 19.0.0.190, and Adobe AIR SDK & Compiler before 19.0.0.190 allows attackers to e…

### CVE-2006-4313
**cisco vpn_3000_concentrator_series_software**
- **Signals:** EPSS
- **Asset:** cisco vpn_3000_concentrator_series_software
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 55.1% (2025-04-11) → 67.7% (2025-06-19), Δ +12.5%**

> Multiple unspecified vulnerabilities in Cisco VPN 3000 series concentrators before 4.1, 4.1.x up to 4.1(7)L, and 4.7.x up to 4.7(2)F allow attackers to execute the (1) CWD, (2) MKD, (3) CDUP, (4) RNFR, (5) SIZE, and (6) RMD FTP commands to modify files or create and delete direct…

### CVE-2025-50201
**wegia wegia Command Injection**
- **Signals:** CVSS
- **Asset:** wegia wegia
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-02T16:21:03.237
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-19)

> WeGIA is a web manager for charitable institutions. Prior to version 3.4.2, an OS Command Injection vulnerability was identified in the /html/configuracao/debug_info.php endpoint. The branch parameter is not properly sanitized before being concatenated and executed in a shell com…

### CVE-2024-45208
**The Versa Director SD-WAN orchestration platform which makes use of Cisco NCS application service.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-19)

> The Versa Director SD-WAN orchestration platform which makes use of Cisco NCS application service. Active and Standby Directors communicate over TCP ports 4566 and 4570 to exchange High Availability (HA) information using a shared password. Affected versions of Versa Director bou…

### CVE-2025-24288
**The Versa Director software exposes a number of services by default and allow attackers an easy foothold due to default credentials and m...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1188
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-19)

> The Versa Director software exposes a number of services by default and allow attackers an easy foothold due to default credentials and multiple accounts (most with sudo access) that utilize the same default credentials. By default, Versa director exposes ssh and postgres to the …

### CVE-2025-33117
**ibm qradar_security_information_and_event_manager privilege escalation**
- **Signals:** CVSS
- **Asset:** ibm qradar_security_information_and_event_manager
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-25T17:42:17.010
- **CWE:** CWE-73
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-19)

> IBM QRadar SIEM 7.5 through 7.5.0 Update Package 12  could allow a privileged user to modify configuration files that would allow the upload of a malicious autoupdate file to execute arbitrary commands.

### CVE-2025-4738
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Yirmibes Software MY ERP allows SQL...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-19)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Yirmibes Software MY ERP allows SQL Injection.This issue affects MY ERP: before 1.170.

### CVE-2025-52464
**meshtastic meshtastic_firmware**
- **Signals:** CVSS
- **Asset:** meshtastic meshtastic_firmware
- **CVSS max:** 9.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T16:52:14.950
- **CWE:** CWE-331
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-06-19)

> Meshtastic is an open source mesh networking solution. In versions from 2.5.0 to before 2.6.11, the flashing procedure of several hardware vendors was resulting in duplicated public/private keys. Additionally, the Meshtastic was failing to properly initialize the internal randomn…

### CVE-2025-52467
**pgai is a Python library that transforms PostgreSQL into a retrieval engine for RAG and Agentic applications.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-19)

> pgai is a Python library that transforms PostgreSQL into a retrieval engine for RAG and Agentic applications. Prior to commit 8eb3567, the pgai repository was vulnerable to an attack allowing the exfiltration of all secrets used in one workflow. In particular, the GITHUB_TOKEN wi…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-19*
