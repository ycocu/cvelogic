# Daily Threat Intelligence — May 25, 2025

**Digest window (UTC):** 2025-05-25
**Generated:** 2026-06-02T07:32:46Z

## Threat brief

Microsoft Win32k: public exploit or PoC linked (Privilege Escalation)

## Executive summary

- Microsoft Win32k: public exploit or PoC linked (Privilege Escalation)

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 5 |
| EPSS rise | 0 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2023-29336
**Microsoft Win32K Privilege Escalation Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **Attack:** Privilege Escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T14:09:32.467
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 78
- **EXP:** ref published 2025-05-25

> Win32k Elevation of Privilege Vulnerability

### CVE-2022-2070
**grandstream gds3710_firmware**
- **Signals:** EXP
- **Asset:** grandstream gds3710_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:00:16.297
- **CWE:** CWE-121
- **CWE:** CWE-787
- **Risk score:** 78
- **EXP:** ref published 2025-05-25

> In Grandstream GSD3710 in its 1.0.11.13 version, it's possible to overflow the stack since it doesn't check the param length before using the sscanf instruction. Because of that, an attacker could create a socket and connect with a remote IP:port by opening a shell and getting fu…

### CVE-2025-2594
**wpeverest user_registration_\&_membership**
- **Signals:** EXP
- **Asset:** wpeverest user_registration_\&_membership
- **CVSS max:** 8.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-30T18:14:15.800
- **Risk score:** 78
- **EXP:** ref published 2025-05-25

> The User Registration & Membership WordPress plugin before 4.1.3 does not properly validate data in an AJAX action when the Membership Addon is enabled, allowing attackers to authenticate as any user, including administrators, by simply using the target account's user ID.

### CVE-2024-13946
**DLL's are not digitally signed when loaded in ASPECT's configuration toolset exposing the application to binary planting during device co...**
- **Signals:** EXP
- **CVSS max:** 7.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-427
- **Risk score:** 78
- **EXP:** ref published 2025-05-25

> DLL's are not digitally signed when loaded in ASPECT's configuration toolset exposing the application to binary planting during device commissioning.This issue affects ASPECT-Enterprise: through 3.*; NEXUS Series: through 3.*; MATRIX Series: through 3.*.

### CVE-2025-46822
**OsamaTaher/Java-springboot-codebase is a collection of Java and Spring Boot code snippets, applications, and projects.**
- **Signals:** EXP
- **Attack:** Path Traversal
- **CVSS max:** 7.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-36
- **Risk score:** 78
- **EXP:** ref published 2025-05-25

> OsamaTaher/Java-springboot-codebase is a collection of Java and Spring Boot code snippets, applications, and projects. Prior to commit c835c6f7799eacada4c0fc77e0816f250af01ad2, insufficient path traversal mechanisms make absolute path traversal possible. This vulnerability allows…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-25*
