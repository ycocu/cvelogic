# Daily Threat Intelligence — June 25, 2026

**Digest window (US Eastern, NVD):** 2026-06-25
**Generated:** 2026-06-29T10:33:11Z

## Threat brief

PTC Windchill And FlexPLM added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- PTC Windchill And FlexPLM added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2026-12569
**PTC Windchill and FlexPLM Improper Input Validation Vulnerability**
- **Signals:** KEV
- **Asset:** ptc flexplm
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-06-17
- **NVD modified:** 2026-06-26
- **CWE:** CWE-20
- **Risk score:** 88
- **KEV:** added 2026-06-25

> A critical remote code execution (RCE) vulnerability has been reported in PTC Windchill PDMlink and PTC FlexPLM. The vulnerability may be exploited through the deserialization of untrusted data.   *  This advisory also applies to all CPS versions
  *  The identified vulnerability…

### CVE-2025-71338
**flowiseai flowise RCE**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Undergoing Analysis
- **NVD published:** 2026-06-25
- **NVD modified:** 2026-06-26
- **CWE:** CWE-73
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-25)

> Flowise contains a path traversal vulnerability in the /api/v1/document-store/loader/process endpoint that allows unauthenticated attackers to write arbitrary files to the filesystem. Attackers can exploit unsanitized fileName parameters with ../ sequences to overwrite critical f…

### CVE-2026-57700
**Unrestricted Upload of File with Dangerous Type vulnerability in Daan.Dev OMGF Pro allows Using Malicious Files.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD published:** 2026-06-25
- **NVD modified:** 2026-06-25
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-25)

> Unrestricted Upload of File with Dangerous Type vulnerability in Daan.Dev OMGF Pro allows Using Malicious Files.

This issue affects OMGF Pro: from n/a through 5.2.6.

### CVE-2025-71327
**flowiseai flowise Auth Bypass**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **Attack:** Auth Bypass
- **CVSS max:** 9.3
- **NVD status:** Undergoing Analysis
- **NVD published:** 2026-06-25
- **NVD modified:** 2026-06-26
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-25)

> Flowise contains an authentication bypass vulnerability in the unprotected /api/v1/account/register endpoint that allows unauthenticated attackers to create user accounts. Remote attackers can exploit this endpoint to register arbitrary accounts and authenticate to the system, ga…

### CVE-2025-71333
**flowiseai flowise RCE**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Undergoing Analysis
- **NVD published:** 2026-06-25
- **NVD modified:** 2026-06-27
- **CWE:** CWE-73
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-25)

> Flowise through 2.2.4 contains an unauthenticated arbitrary file upload vulnerability in the /api/v1/attachments endpoint when storageType is set to local. Attackers can exploit path traversal in the chatId and chatflowId parameters to upload malicious files to arbitrary director…

### CVE-2025-71334
**flowiseai flowise**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD published:** 2026-06-25
- **NVD modified:** 2026-06-26
- **CWE:** CWE-73
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-25)

> Flowise before 3.0.6 (affected versions 2.2.8 and earlier) contains an arbitrary file access vulnerability due to missing validation that the chatflowId and chatId parameters are UUIDs or numbers in file handling operations. By supplying a path-traversal value (e.g., '../../../..…

### CVE-2025-71336
**flowiseai flowise RCE**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD published:** 2026-06-25
- **NVD modified:** 2026-06-26
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-25)

> Flowise before 3.0.6 (affected versions 2.2.7-patch.1 and earlier) contains an unsandboxed remote code execution vulnerability in the Custom MCP feature, which is designed to execute OS commands such as launching local MCP servers. Because Flowise's authentication and authorizati…

### CVE-2026-20230
**Cisco Unified Communications Manager Server-Side Request Forgery (SSRF) Vulnerability**
- **Signals:** KEV
- **Asset:** cisco unified_communications_manager
- **Attack:** SSRF
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD published:** 2026-06-03
- **NVD modified:** 2026-06-26
- **CWE:** CWE-918
- **Risk score:** 88
- **KEV:** added 2026-06-25

> A vulnerability in Cisco Unified Communications Manager (Unified CM) and Cisco Unified Communications Manager Session Management Edition (Unified CM SME) could allow an unauthenticated, remote attacker to conduct server-side request forgery (SSRF) attacks through an affected devi…

### CVE-2026-40702
**WebSocket endpoints lack proper authentication mechanisms, enabling attackers to impersonate charging stations.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD published:** 2026-06-25
- **NVD modified:** 2026-06-26
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-25)

> WebSocket endpoints lack proper authentication mechanisms, enabling attackers to impersonate charging stations. As a result, attackers can exploit this weakness to gain unauthorized access to sensitive data or perform unauthorized actions. Given that no authentication is required…

### CVE-2026-48930
**nodejs node.js**
- **Signals:** CVSS
- **Asset:** nodejs node.js
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-06-25
- **NVD modified:** 2026-06-26
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-25)

> A flaw in Node.js TLS hostname handling can cause Embedded-nul hostnames can lead to silent authority rebinding due to c-string truncation in resolver bindings.

This vulnerability affects all supported release lines: **Node.js 22**, **Node.js 24**, and **Node.js 26**.

### CVE-2026-56786
**rtklib rtklib Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** rtklib rtklib
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-06-25
- **NVD modified:** 2026-06-26
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-25)

> RTKLIB through 2.4.3 contains an out-of-bounds write vulnerability in decode_type1033 function that fails to clamp length counters to destination buffer size, allowing up to 191-byte overflow into fixed 64-byte descriptor fields. An attacker controlling an NTRIP or serial RTCM3 c…

### CVE-2026-9222
**Setracker2 Android Companion App com.tgelec.setracker versions 3.1.5 and prior only require the password hash when authenticating with ba...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD published:** 2026-06-25
- **NVD modified:** 2026-06-26
- **CWE:** CWE-836
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-25)

> Setracker2 Android Companion App com.tgelec.setracker versions 3.1.5 and prior only require the password hash when authenticating with backend services from the client. This could allow an attacker, who knows the hash, to authenticate and gain full access.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-25*
