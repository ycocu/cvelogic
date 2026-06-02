# Daily Threat Intelligence — July 03, 2025

**Digest window (UTC):** 2025-07-03
**Generated:** 2026-06-02T07:32:59Z

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

### CVE-2025-34061
**A backdoor in PHPStudy versions 2016 through 2018 allows unauthenticated remote attackers to execute arbitrary PHP code on affected insta...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-03)

> A backdoor in PHPStudy versions 2016 through 2018 allows unauthenticated remote attackers to execute arbitrary PHP code on affected installations. The backdoor listens for base64-encoded PHP payloads in the Accept-Charset HTTP header of incoming requests, decodes and executes the…

### CVE-2025-34082
**A command injection vulnerability exists in IGEL OS versions prior to 11.04.270 within the Secure Terminal and Secure Shadow services.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-03)

> A command injection vulnerability exists in IGEL OS versions prior to 11.04.270 within the Secure Terminal and Secure Shadow services. The flaw arises due to improper input sanitization in the handling of specially crafted PROXYCMD commands on TCP ports 30022 and 5900. An unauthe…

### CVE-2025-34089
**An unauthenticated remote code execution vulnerability exists in Remote for Mac, a macOS remote control utility developed by Aexol Studio...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-03)

> An unauthenticated remote code execution vulnerability exists in Remote for Mac, a macOS remote control utility developed by Aexol Studio, in versions up to and including 2025.7. When the application is configured with authentication disabled (i.e., the "Allow unknown devices" op…

### CVE-2025-23968
**Unrestricted Upload of File with Dangerous Type vulnerability in WebFactory AiBud WP aibuddy-openai-chatgpt allows Upload a Web Shell to...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:24:52.840
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-03)

> Unrestricted Upload of File with Dangerous Type vulnerability in WebFactory AiBud WP aibuddy-openai-chatgpt allows Upload a Web Shell to a Web Server.This issue affects AiBud WP: from n/a through <= 1.9.

### CVE-2025-34087
**pi-hole pi-hole Command Injection**
- **Signals:** CVSS
- **Asset:** pi-hole pi-hole
- **Attack:** Command Injection
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-01T14:08:35.893
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-07-03)

> An authenticated command injection vulnerability exists in Pi-hole versions up to 3.3. When adding a domain to the allowlist via the web interface, the domain parameter is not properly sanitized, allowing an attacker to append OS commands to the domain string. These commands are …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-03*
