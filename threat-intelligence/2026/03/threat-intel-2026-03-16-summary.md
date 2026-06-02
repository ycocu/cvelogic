# Daily Threat Intelligence — March 16, 2026

**Digest window (UTC):** 2026-03-16
**Generated:** 2026-06-02T07:34:39Z

## Threat brief

Wing FTP Server added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Wing FTP Server added to CISA KEV — confirmed in-the-wild exploitation.
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

### CVE-2025-47813
**Wing FTP Server Information Disclosure Vulnerability**
- **Signals:** KEV
- **Asset:** wftpserver wing_ftp_server
- **Attack:** Info Disclosure
- **CVSS max:** 4.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-16T20:20:49.217
- **CWE:** CWE-209
- **Risk score:** 88
- **KEV:** added 2026-03-16

> loginok.html in Wing FTP Server before 7.4.4 discloses the full local installation path of the application when using a long value in the UID cookie.

### CVE-2026-32621
**Apollo Federation is an architecture for declaratively composing APIs into a unified graph.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-16T14:53:07.390
- **CWE:** CWE-1321
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-16)

> Apollo Federation is an architecture for declaratively composing APIs into a unified graph. Prior to 2.9.6, 2.10.5, 2.11.6, 2.12.3, and 2.13.2, a vulnerability exists in query plan execution within the gateway that may allow pollution of Object.prototype in certain scenarios. A m…

### CVE-2025-69809
**p2r3 bareiron RCE**
- **Signals:** CVSS
- **Asset:** p2r3 bareiron
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T18:41:17.600
- **CWE:** CWE-123
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-16)

> A write-what-where condition in p2r3 Bareiron commit 8e4d40 allows unauthenticated attackers to write arbitrary values to memory, enabling arbitrary code execution via a crafted packet.

### CVE-2025-62319
**Boolean-Based SQL Injection is a type of blind SQL injection where an attacker manipulates SQL queries by injecting Boolean conditions (T...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-17T14:20:01.670
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-16)

> Boolean-Based SQL Injection is a type of blind SQL injection where an attacker manipulates SQL queries by injecting Boolean conditions (TRUE or FALSE) into application input fields. Instead of returning database errors or visible data, the application responds differently dependi…

### CVE-2025-69808
**p2r3 bareiron DoS**
- **Signals:** CVSS
- **Asset:** p2r3 bareiron
- **Attack:** DoS
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T18:41:00.170
- **CWE:** CWE-125
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-16)

> An out-of-bounds memory access (OOB) in p2r3 Bareiron commit 8e4d40 allows unauthenticated attackers to access sensitive information and cause a Denial of Service (DoS) via supplying a crafted packet.

### CVE-2025-69902
**A command injection vulnerability in the minimal_wrapper.py component of kubectl-mcp-server v1.2.0 allows attackers to execute arbitrary...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-27T19:18:46.690
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-16)

> A command injection vulnerability in the minimal_wrapper.py component of kubectl-mcp-server v1.2.0 allows attackers to execute arbitrary commands via injecting arbitrary shell metacharacters.

### CVE-2026-23489
**teclib-edition fields**
- **Signals:** CVSS
- **Asset:** teclib-edition fields
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-18T13:57:05.093
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-16)

> Fields is a GLPI plugin that allows users to add custom fields on GLPI items forms. Prior to version 1.23.3, it is possible to execute arbitrary PHP code from users that are allowed to create dropdowns. This issue has been patched in version 1.23.3.

### CVE-2026-27962
**authlib authlib Deserialization**
- **Signals:** CVSS
- **Asset:** authlib authlib
- **Attack:** Deserialization
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-17T20:46:48.053
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-16)

> Authlib is a Python library which builds OAuth and OpenID Connect servers. Prior to version 1.6.9, a JWK Header Injection vulnerability in authlib's JWS implementation allows an unauthenticated attacker to forge arbitrary JWT tokens that pass signature verification. When key=None…

### CVE-2026-28430
**chamilo chamilo_lms SQL Injection**
- **Signals:** CVSS
- **Asset:** chamilo chamilo_lms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-17T18:53:49.153
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-16)

> Chamilo LMS is a learning management system. Prior to version 1.11.34, there is an unauthenticated SQL injection vulnerability which allows remote attackers to execute arbitrary SQL commands via the custom_dates parameter. By chaining this with a predictable legacy password reset…

### CVE-2026-32626
**mintplexlabs anythingllm RCE**
- **Signals:** CVSS
- **Asset:** mintplexlabs anythingllm
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-16T20:34:47.637
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-03-16)

> AnythingLLM is an application that turns pieces of content into context that any LLM can use as references during chatting. In 1.11.1 and earlier, AnythingLLM Desktop contains a Streaming Phase XSS vulnerability in the chat rendering pipeline that escalates to Remote Code Executi…

### CVE-2026-4177
**toddr yaml::syck Buffer Overflow**
- **Signals:** CVSS
- **Asset:** toddr yaml\
- **Attack:** Buffer Overflow
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-23T18:17:31.370
- **CWE:** CWE-122
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-16)

> YAML::Syck versions through 1.36 for Perl has several potential security vulnerabilities including a high-severity heap buffer overflow in the YAML emitter.

The heap overflow occurs when class names exceed the initial 512-byte allocation.

The base64 decoder could read past the …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-16*
