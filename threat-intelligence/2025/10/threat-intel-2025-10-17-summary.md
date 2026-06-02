# Daily Threat Intelligence — October 17, 2025

**Digest window (UTC):** 2025-10-17
**Generated:** 2026-06-02T07:33:36Z

## Threat brief

10 new critical disclosures — review patch status on exposed services.

## Executive summary

- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-62168
**squid-cache squid Info Disclosure**
- **Signals:** CVSS
- **Asset:** squid-cache squid
- **Attack:** Info Disclosure
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2025-11-05T17:15:45.087
- **CWE:** CWE-209
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-17)

> Squid is a caching proxy for the Web. In Squid versions prior to 7.2, a failure to redact HTTP authentication credentials in error handling allows information disclosure. The vulnerability allows a script to bypass browser security protections and learn the credentials a trusted …

### CVE-2025-11925
**azure-access blu-ic2_firmware**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T17:14:51.093
- **CWE:** CWE-754
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-17)

> Incorrect Content-Type header in one of the APIs (`text/html` instead of `application/json`) replies may potentially allow injection of HTML/JavaScript into reply.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5.

### CVE-2025-62645
**rbi restaurant_brands_international_assistant privilege escalation**
- **Signals:** CVSS
- **Asset:** rbi restaurant_brands_international_assistant
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-04T15:13:52.277
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-10-17)

> The Restaurant Brands International (RBI) assistant platform through 2025-09-06 allows a remote authenticated attacker to obtain a token with administrative privileges for the entire platform via the createToken GraphQL mutation.

### CVE-2025-56218
**ascertia signinghub**
- **Signals:** CVSS
- **Asset:** ascertia signinghub
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T14:28:09.213
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-17)

> An arbitrary file upload vulnerability in SigningHub v8.6.8 allows attackers to execute arbitrary code via uploading a crafted PDF file.

### CVE-2025-56221
**ascertia signinghub**
- **Signals:** CVSS
- **Asset:** ascertia signinghub
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T14:16:15.763
- **CWE:** CWE-307
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-17)

> A lack of rate limiting in the login mechanism of SigningHub v8.6.8 allows attackers to bypass authentication via a brute force attack.

### CVE-2025-56316
**mingsoft mcms SQL Injection**
- **Signals:** CVSS
- **Asset:** mingsoft mcms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T16:44:48.133
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-17)

> A SQL injection vulnerability in the content_title parameter of the /cms/content/list endpoint in MCMS 5.5.0 allows remote attackers to execute arbitrary SQL queries via unsanitized input in the FreeMarker template rendering.

### CVE-2025-60279
**A server-side request forgery (SSRF) vulnerability in Illia Cloud illia-Builder before v4.8.5 allows authenticated users to send arbitrar...**
- **Signals:** CVSS
- **Attack:** SSRF
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-10-17)

> A server-side request forgery (SSRF) vulnerability in Illia Cloud illia-Builder before v4.8.5 allows authenticated users to send arbitrary requests to internal services via the API. An attacker can leverage this to enumerate open ports based on response discrepancies and interact…

### CVE-2025-62353
**A path traversal vulnerability in all versions of the Windsurf IDE enables a threat actor to read and write arbitrary local files in and...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-17)

> A path traversal vulnerability in all versions of the Windsurf IDE enables a threat actor to read and write arbitrary local files in and outside of current projects on an end user’s system. The vulnerability can be reached directly and through indirect prompt injection.

### CVE-2025-62515
**pyquokka is a framework for making data lakes work for time series.**
- **Signals:** CVSS
- **Attack:** unsafe deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-17)

> pyquokka is a framework for making data lakes work for time series. In versions 0.3.1 and prior, the FlightServer class directly uses pickle.loads() to deserialize action bodies received from Flight clients without any sanitization or validation in the do_action() method. The vul…

### CVE-2025-8414
**Due to improper input validation, a buffer overflow vulnerability is present in Zigbee EZSP Host Applications.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-17)

> Due to improper input validation, a buffer overflow vulnerability is present in 

Zigbee EZSP Host Applications. If the buffer overflows, stack corruption is possible. In certain

conditions, this could lead to arbitrary code execution. Access to a network key is required to expl…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-17*
