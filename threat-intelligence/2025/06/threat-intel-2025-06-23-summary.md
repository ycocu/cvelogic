# Daily Threat Intelligence — June 23, 2025

**Digest window (UTC):** 2025-06-23
**Generated:** 2026-06-02T07:32:56Z

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

### CVE-2025-2828
**langchain langchain SSRF**
- **Signals:** CVSS
- **Asset:** langchain langchain
- **Attack:** SSRF
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-16T19:46:41.933
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-23)

> A Server-Side Request Forgery (SSRF) vulnerability exists in the RequestsToolkit component of the langchain-community package (specifically, langchain_community.agent_toolkits.openapi.toolkit.RequestsToolkit) in langchain-ai/langchain version 0.0.27. This vulnerability occurs bec…

### CVE-2025-52562
**Convoy is a KVM server management panel for hosting businesses.**
- **Signals:** CVSS
- **Attack:** Directory Traversal
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-23)

> Convoy is a KVM server management panel for hosting businesses. In versions 3.9.0-rc3 to before 4.4.1, there is a directory traversal vulnerability in the LocaleController component of Performave Convoy. An unauthenticated remote attacker can exploit this vulnerability by sending…

### CVE-2023-47031
**ncr terminal_handler privilege escalation**
- **Signals:** CVSS
- **Asset:** ncr terminal_handler
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-25T13:13:50.157
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-23)

> An issue in NCR Terminal Handler v.1.5.1 allows a remote attacker to escalate privileges via a crafted POST request to the grantRolesToUsers, grantRolesToGroups, and grantRolesToOrganization SOAP API component.

### CVE-2023-47029
**ncr terminal_handler**
- **Signals:** CVSS
- **Asset:** ncr terminal_handler
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-02T19:06:22.507
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-23)

> An issue in NCR Terminal Handler v.1.5.1 allows a remote attacker to execute arbitrary code and obtain sensitive information via a crafted POST request to the UserService component

### CVE-2023-47030
**ncr terminal_handler**
- **Signals:** CVSS
- **Asset:** ncr terminal_handler
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-25T12:50:37.217
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-23)

> An issue in NCR Terminal Handler v.1.5.1 allows a remote attacker to execute arbitrary code and obtain sensitive information via a GET request to a UserService SOAP API endpoint to validate if a user exists.

### CVE-2023-47032
**ncr terminal_handler**
- **Signals:** CVSS
- **Asset:** ncr terminal_handler
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-25T13:32:01.277
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-23)

> Password Vulnerability in NCR Terminal Handler v.1.5.1 allows a remote attacker to execute arbitrary code via a crafted script to the UserService SOAP API function.

### CVE-2023-47295
**ncr terminal_handler**
- **Signals:** CVSS
- **Asset:** ncr terminal_handler
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-25T13:30:08.523
- **CWE:** CWE-1236
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-23)

> A CSV injection vulnerability in NCR Terminal Handler v1.5.1 allows attackers to execute arbitrary commands via injecting a crafted payload into any text field that accepts strings.

### CVE-2025-46101
**beakon learning_management_system_sharable_content_object_reference_model SQL Injection**
- **Signals:** CVSS
- **Asset:** beakon learning_management_system_sharable_content_object_reference_model
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-16T20:58:56.213
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-23)

> SQL Injection vulnerability in Beakon Software Beakon Learning Management System Sharable Content Object Reference Model (SCORM) version before 5.4.3 allows a remote attacker to obtain sensitive information via the ks parameter in json_scorm.php file

### CVE-2025-6545
**Improper Input Validation vulnerability in pbkdf2 allows Signature Spoofing by Improper Validation.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-23)

> Improper Input Validation vulnerability in pbkdf2 allows Signature Spoofing by Improper Validation. This vulnerability is associated with program files lib/to-buffer.Js.

This issue affects pbkdf2: from 3.0.10 through 3.1.2.

### CVE-2025-6547
**Improper Input Validation vulnerability in pbkdf2 allows Signature Spoofing by Improper Validation.This issue affects pbkdf2: <=3.1.2.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-23)

> Improper Input Validation vulnerability in pbkdf2 allows Signature Spoofing by Improper Validation.This issue affects pbkdf2: <=3.1.2.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-23*
