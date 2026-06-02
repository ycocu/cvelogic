# Daily Threat Intelligence — November 30, 2025

**Digest window (UTC):** 2025-11-30
**Generated:** 2026-06-02T07:33:53Z

## Threat brief

Ettercap — exploitation likelihood rose sharply (EPSS 5.7% → 17% · rising (+12%)).

## Executive summary

- Ettercap — exploitation likelihood rose sharply (EPSS 5.7% → 17% · rising (+12%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2002-0276
**ettercap ettercap Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ettercap ettercap
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 81
- **EPSS 5.7% (2025-03-30) → 17.3% (2025-11-30), Δ +11.6%**

> Buffer overflow in various decoders in Ettercap 0.6.3.1 and earlier, when running on networks with an MTU greater than 2000, allows remote attackers to execute arbitrary code via large packets.

### CVE-2022-44808
**dlink dir-823g_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** dlink dir-823g_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-25T21:15:35.360
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 8.7% (2025-11-24) → 19.8% (2025-11-30), Δ +11.0%**

> A command injection vulnerability has been found on D-Link DIR-823G devices with firmware version 1.02B03 that allows an attacker to execute arbitrary operating system commands through well-designed /HNAP1 requests. Before the HNAP API function can process the request, the system…

### CVE-2025-13615
**The StreamTube Core plugin for WordPress is vulnerable to Arbitrary User Password Change in versions up to, and including, 4.78.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-639
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-30)

> The StreamTube Core plugin for WordPress is vulnerable to Arbitrary User Password Change in versions up to, and including, 4.78. This is due to the plugin providing user-controlled access to objects, letting a user bypass authorization and access system resources. This makes it p…

### CVE-2025-35028
**By providing a command-line argument starting with a semi-colon ; to an API endpoint created by the EnhancedCommandExecutor class of the...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-30)

> By providing a command-line argument starting with a semi-colon ; to an API endpoint created by the EnhancedCommandExecutor class of the HexStrike AI MCP server, the resultant composed command is executed directly in the context of the MCP server’s normal privilege; typically, th…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-30*
