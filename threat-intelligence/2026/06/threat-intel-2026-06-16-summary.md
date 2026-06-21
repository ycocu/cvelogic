# Daily Threat Intelligence — June 16, 2026

**Digest window (US Eastern, NVD):** 2026-06-16
**Generated:** 2026-06-21T09:42:45Z

## Threat brief

Widget Factory Joomla Content Editor added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Widget Factory Joomla Content Editor added to CISA KEV — confirmed in-the-wild exploitation.
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

### CVE-2026-48907
**Widget Factory Joomla Content Editor Improper Access Control Vulnerability**
- **Signals:** KEV
- **Asset:** widgetfactorylimited jce
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD published:** 2026-06-05
- **NVD modified:** 2026-06-17
- **CWE:** CWE-284
- **Risk score:** 88
- **KEV:** added 2026-06-16

> A vulnerability in the JCE editor extension for Joomla allows the creation of new editor profiles for unauthenticated users, ultimately resulting in PHP code upload and execution.

### CVE-2026-12295
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD published:** 2026-06-16
- **NVD modified:** 2026-06-18
- **CWE:** CWE-693
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-16)

> Sandbox escape in the DOM: Navigation component. This vulnerability was fixed in Firefox 152, Firefox ESR 140.12, Firefox ESR 115.37, Thunderbird 152, and Thunderbird 140.12.

### CVE-2026-12296
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD published:** 2026-06-16
- **NVD modified:** 2026-06-18
- **CWE:** CWE-693
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-16)

> Sandbox escape in the Security: Process Sandboxing component. This vulnerability was fixed in Firefox 152, Firefox ESR 140.12, Thunderbird 152, and Thunderbird 140.12.

### CVE-2025-13036
**An authentication bypass security issue exists within FactoryTalk Historian Site Edition.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.2
- **NVD status:** Awaiting Analysis
- **NVD published:** 2026-06-16
- **NVD modified:** 2026-06-17
- **CWE:** CWE-362
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-16)

> An authentication
bypass security issue exists within FactoryTalk Historian Site Edition. By
continually sending requests to the login endpoint, an attacker may obtain a
valid authentication token.

### CVE-2026-12297
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD published:** 2026-06-16
- **NVD modified:** 2026-06-18
- **CWE:** CWE-119
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-16)

> Sandbox escape due to incorrect boundary conditions in the Networking component. This vulnerability was fixed in Firefox 152, Firefox ESR 140.12, Firefox ESR 115.37, Thunderbird 152, and Thunderbird 140.12.

### CVE-2026-12304
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD published:** 2026-06-16
- **NVD modified:** 2026-06-17
- **CWE:** CWE-346
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-16)

> Same-origin policy bypass in the Networking: Cookies component. This vulnerability was fixed in Firefox 152, Firefox ESR 140.12, Thunderbird 152, and Thunderbird 140.12.

### CVE-2026-12315
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD published:** 2026-06-16
- **NVD modified:** 2026-06-17
- **CWE:** CWE-693
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-16)

> Mitigation bypass in the DOM: Security component. This vulnerability was fixed in Firefox 152, Firefox ESR 140.12, Thunderbird 152, and Thunderbird 140.12.

### CVE-2026-12316
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD published:** 2026-06-16
- **NVD modified:** 2026-06-17
- **CWE:** CWE-693
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-16)

> Mitigation bypass in the DOM: Security component. This vulnerability was fixed in Firefox 152 and Thunderbird 152.

### CVE-2026-22313
**The device has a webserver that exposes a REST API authenticated with a token on the management network.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD published:** 2026-06-16
- **NVD modified:** 2026-06-17
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-16)

> The device has a webserver that exposes a REST API authenticated with a token on the management network. By exploiting an OS command injection vulnerability an authenticated attacker can send
arbitrary commands to the device that are executed with administrative permissions by th…

### CVE-2026-48777
**FileBrowser Quantum is a free, self-hosted, web-based file manager.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD published:** 2026-06-16
- **NVD modified:** 2026-06-17
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-16)

> FileBrowser Quantum is a free, self-hosted, web-based file manager. Versions prior to 1.3.2-stable, 1.4.0-beta and 1.4.1-beta are vulnerable to Path Traversal through the publicPatchHandler in backend/http/public.go which joins user-controlled fromPath and toPath body fields with…

### CVE-2026-53776
**Perry before 0.5.1166 contains a JWT validation vulnerability that allows remote attackers to bypass token expiration by exploiting the u...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD published:** 2026-06-16
- **NVD modified:** 2026-06-17
- **CWE:** CWE-613
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-16)

> Perry before 0.5.1166 contains a JWT validation vulnerability that allows remote attackers to bypass token expiration by exploiting the unconditional setting of validate_exp = false in the verify_decode helper within the stdlib JWT verification path. Attackers in possession of a …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-16*
