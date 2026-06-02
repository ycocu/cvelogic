# Daily Threat Intelligence — September 17, 2025

**Digest window (UTC):** 2025-09-17
**Generated:** 2026-06-02T07:33:26Z

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

### CVE-2025-23316
**nvidia triton_inference_server RCE**
- **Signals:** CVSS
- **Asset:** nvidia triton_inference_server
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-25T20:20:35.247
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-17)

> NVIDIA Triton Inference Server for Windows and Linux contains a vulnerability in the Python backend, where an attacker could cause a remote code execution by manipulating the model name parameter in the model control APIs. A successful exploit of this vulnerability might lead to …

### CVE-2025-59304
**swetrix swetrix RCE**
- **Signals:** CVSS
- **Asset:** swetrix swetrix
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-08T18:28:20.703
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-17)

> A directory traversal issue in Swetrix Web Analytics API 3.1.1 before 7d8b972 allows a remote attacker to achieve Remote Code Execution via a crafted HTTP request.

### CVE-2025-59340
**hubspot jinjava unsafe deserialization**
- **Signals:** CVSS
- **Asset:** hubspot jinjava
- **Attack:** unsafe deserialization
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-26T13:11:40.227
- **CWE:** CWE-1336
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-17)

> jinjava is a Java-based template engine based on django template syntax, adapted to render jinja templates. Priori to 2.8.1, by using mapper.getTypeFactory().constructFromCanonical(), it is possible to instruct the underlying ObjectMapper to deserialize attacker-controlled input …

### CVE-2025-10156
**mmaitre314 picklescan**
- **Signals:** CVSS
- **Asset:** mmaitre314 picklescan
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-02T19:04:56.000
- **CWE:** CWE-755
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-17)

> An Improper Handling of Exceptional Conditions vulnerability in the ZIP archive scanning component of mmaitre314 picklescan allows a remote attacker to bypass security scans. This is achieved by crafting a ZIP archive containing a file with a bad Cyclic Redundancy Check (CRC), wh…

### CVE-2025-10157
**mmaitre314 picklescan**
- **Signals:** CVSS
- **Asset:** mmaitre314 picklescan
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-13T17:02:36.447
- **CWE:** CWE-693
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-17)

> A Protection Mechanism Failure vulnerability in mmaitre314 picklescan versions up to and including 0.0.30 allows a remote attacker to bypass the unsafe globals check. This is possible because the scanner performs an exact match for module names, allowing malicious payloads to be …

### CVE-2025-10439
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Yordam Informatics Yordam Library A...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-17)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Yordam Informatics Yordam Library Automation System allows SQL Injection.This issue affects Yordam Library Automation System: from 21.5 & 21.6 before 21.7.

### CVE-2025-10643
**wondershare repairit Auth Bypass**
- **Signals:** CVSS
- **Asset:** wondershare repairit
- **Attack:** Auth Bypass
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-19T12:59:05.550
- **CWE:** CWE-732
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-17)

> Wondershare Repairit Incorrect Permission Assignment Authentication Bypass Vulnerability. This vulnerability allows remote attackers to bypass authentication on affected installations of Wondershare Repairit. Authentication is not required to exploit this vulnerability.

The spec…

### CVE-2025-10644
**wondershare repairit Auth Bypass**
- **Signals:** CVSS
- **Asset:** wondershare repairit
- **Attack:** Auth Bypass
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-19T12:58:57.850
- **CWE:** CWE-266
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-09-17)

> Wondershare Repairit SAS Token Incorrect Permission Assignment Authentication Bypass Vulnerability. This vulnerability allows remote attackers to bypass authentication on Wondershare Repairit. Authentication is not required to exploit this vulnerability.

The specific flaw exists…

### CVE-2025-58766
**Dyad is a local AI app builder.**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-09-17)

> Dyad is a local AI app builder. A critical security vulnerability has been discovered that affected Dyad v0.19.0 and earlier versions that allows attackers to execute arbitrary code on users' systems. The vulnerability affects the application's preview window functionality and ca…

### CVE-2025-8077
**A vulnerability exists in NeuVector versions up to and including 5.4.5, where a fixed string is used as the default password for the buil...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1393
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-17)

> A vulnerability exists in NeuVector versions up to and including 5.4.5, where a fixed string is used as the default password for the built-in `admin` account. If this password is not changed immediately after deployment, any workload with network access within the cluster could u…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-17*
