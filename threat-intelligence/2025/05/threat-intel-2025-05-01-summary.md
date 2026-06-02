# Daily Threat Intelligence — May 01, 2025

**Digest window (UTC):** 2025-05-01
**Generated:** 2026-06-02T07:32:38Z

## Threat brief

Apache HTTP Server added to CISA KEV — confirmed in-the-wild exploitation. · Microsoft Windows: public exploit or PoC linked · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apache HTTP Server added to CISA KEV — confirmed in-the-wild exploitation.
- Microsoft Windows: public exploit or PoC linked
- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 1 |
| EPSS rise | 0 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **9** |


## CVEs

### CVE-2023-44221
**SonicWall SMA100 Appliances OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** sonicwall sma_200_firmware
- **Attack:** Command Injection
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T15:56:29.743
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2025-05-01

> Improper neutralization of special elements in the SMA100 SSL-VPN management interface allows a remote authenticated attacker with administrative privilege to inject arbitrary commands as a 'nobody' user, potentially leading to OS Command Injection Vulnerability.

### CVE-2025-24054
**Microsoft Windows NTLM Hash Disclosure Spoofing Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T21:25:23.527
- **CWE:** CWE-73
- **Risk score:** 78
- **EXP:** ref published 2025-05-01

> External control of file name or path in Windows NTLM allows an unauthorized attacker to perform spoofing over a network.

### CVE-2025-46337
**ADOdb is a PHP database class library that provides abstractions for performing queries and managing databases.**
- **Signals:** CVSS
- **Attack:** SQL injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-01)

> ADOdb is a PHP database class library that provides abstractions for performing queries and managing databases. Prior to version 5.22.9, improper escaping of a query parameter may allow an attacker to execute arbitrary SQL statements when the code using ADOdb connects to a Postgr…

### CVE-2024-38475
**Apache HTTP Server Improper Escaping of Output Vulnerability**
- **Signals:** KEV
- **Asset:** apache http_server
- **Attack:** Code Execution
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-17T21:49:55.247
- **CWE:** CWE-116
- **Risk score:** 88
- **KEV:** added 2025-05-01

> Improper escaping of output in mod_rewrite in Apache HTTP Server 2.4.59 and earlier allows an attacker to map URLs to filesystem locations that are permitted to be served by the server but are not intentionally/directly reachable by any URL, resulting in code execution or source …

### CVE-2024-48905
**sematell replyone**
- **Signals:** CVSS
- **Asset:** sematell replyone
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-04T17:26:59.047
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-01)

> Sematell ReplyOne 7.4.3.0 has Insecure Permissions for the /rest/sessions endpoint.

### CVE-2025-24522
**KUNBUS Revolution Pi OS Bookworm 01/2025 is vulnerable because authentication is not configured by default for the Node-RED server.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-305
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-01)

> KUNBUS Revolution Pi OS Bookworm 01/2025 is vulnerable because authentication is not configured by default for the Node-RED server. This can give an unauthenticated remote attacker full access to the Node-RED server where they can run arbitrary commands on the underlying operatin…

### CVE-2025-27007
**Incorrect Privilege Assignment vulnerability in Brainstorm Force OttoKit suretriggers allows Privilege Escalation.This issue affects Otto...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:26:14.197
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-01)

> Incorrect Privilege Assignment vulnerability in Brainstorm Force OttoKit suretriggers allows Privilege Escalation.This issue affects OttoKit: from n/a through <= 1.0.82.

### CVE-2025-32011
**KUNBUS PiCtory versions 2.5.0 through 2.11.1 have an authentication bypass vulnerability where a remote attacker can bypass authenticatio...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-305
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-01)

> KUNBUS PiCtory versions 2.5.0 through 2.11.1 have an authentication bypass vulnerability where a remote attacker can bypass authentication to get access due to a path traversal.

### CVE-2025-47154
**LibJS in Ladybird before f5a6704 mishandles the freeing of the vector that arguments_list references, leading to a use-after-free, and al...**
- **Signals:** CVSS
- **Attack:** Use-After-Free
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-820
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-05-01)

> LibJS in Ladybird before f5a6704 mishandles the freeing of the vector that arguments_list references, leading to a use-after-free, and allowing remote attackers to execute arbitrary code via a crafted .js file. NOTE: the GitHub README says "Ladybird is in a pre-alpha state, and o…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-01*
