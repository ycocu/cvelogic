# Daily Threat Intelligence — April 17, 2026

**Digest window (UTC):** 2026-04-17
**Generated:** 2026-06-02T07:34:56Z

## Threat brief

Canonical Debian Linux — exploitation likelihood rose sharply (EPSS 45% → 56% · rising (+11%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Canonical Debian Linux — exploitation likelihood rose sharply (EPSS 45% → 56% · rising (+11%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2018-5146
**canonical debian_linux memory safety**
- **Signals:** EPSS
- **Asset:** redhat enterprise_linux_desktop
- **Attack:** memory safety
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-25T17:50:16.803
- **CWE:** CWE-787
- **Risk score:** 82
- **EPSS 44.8% (2026-04-13) → 55.6% (2026-04-17), Δ +10.8%**

> An out of bounds memory write while processing Vorbis audio data was reported through the Pwn2Own contest. This vulnerability affects Firefox < 59.0.1, Firefox ESR < 52.7.2, and Thunderbird < 52.7.

### CVE-2026-40342
**firebirdsql firebird privilege escalation**
- **Signals:** CVSS
- **Asset:** firebirdsql firebird
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T14:28:24.923
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-17)

> Firebird is an open-source relational database management system. In versions prior to 5.0.4, 4.0.7 and 3.0.14, the external engine plugin loader concatenates a user-supplied engine name into a filesystem path without filtering path separators or .. components. An authenticated u…

### CVE-2026-40351
**fastgpt fastgpt SQL Injection**
- **Signals:** CVSS
- **Asset:** fastgpt fastgpt
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T19:39:32.913
- **CWE:** CWE-943
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-17)

> FastGPT is an AI Agent building platform. In versions prior to 4.14.9.5, the password-based login endpoint uses TypeScript type assertion without runtime validation, allowing an unauthenticated attacker to pass a MongoDB query operator object (e.g., {"$ne": ""}) as the password f…

### CVE-2026-23500
**dolibarr dolibarr_erp\/crm**
- **Signals:** CVSS
- **Asset:** dolibarr dolibarr_erp\/crm
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-01T18:28:29.613
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-17)

> Dolibarr is an enterprise resource planning (ERP) and customer relationship management (CRM) software package. In versions prior to 23.0.0 , the ODT to PDF conversion process in odf.php concatenates the MAIN_ODT_AS_PDF configuration constant directly into a shell command passed t…

### CVE-2026-32105
**neutrinolabs xrdp**
- **Signals:** CVSS
- **Asset:** neutrinolabs xrdp
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T14:20:36.877
- **CWE:** CWE-354
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-17)

> xrdp is an open source RDP server. In versions through 0.10.5, xrdp does not implement verification for the Message Authentication Code (MAC) signature of encrypted RDP packets when using the "Classic RDP Security" layer. While the sender correctly generates signatures, the recei…

### CVE-2026-35546
**anviz cx2_lite_firmware**
- **Signals:** CVSS
- **Asset:** anviz cx7_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-04T14:31:19.317
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-17)

> Anviz CX2 Lite and CX7 are vulnerable to unauthenticated firmware uploads. This causes crafted 
archives to be accepted, enabling attackers to plant and execute code 
and obtain a reverse shell.

### CVE-2026-40258
**The Gramps Web API is a Python REST API for the genealogical research software Gramps.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-29T21:04:10.060
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-17)

> The Gramps Web API is a Python REST API for the genealogical research software Gramps. Versions 1.6.0 through 3.11.0 have a path traversal vulnerability (Zip Slip) in the media archive import feature. An authenticated user with owner-level privileges can craft a malicious ZIP fil…

### CVE-2026-40477
**thymeleaf thymeleaf**
- **Signals:** CVSS
- **Asset:** thymeleaf thymeleaf
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T16:58:57.837
- **CWE:** CWE-917
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-04-17)

> Thymeleaf is a server-side Java template engine for web and standalone environments. Versions 3.1.3.RELEASE and prior contain a security bypass vulnerability in the expression execution mechanisms. Although the library provides mechanisms to prevent expression injection, it fails…

### CVE-2026-40478
**thymeleaf thymeleaf**
- **Signals:** CVSS
- **Asset:** thymeleaf thymeleaf
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T16:58:33.957
- **CWE:** CWE-917
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-04-17)

> Thymeleaf is a server-side Java template engine for web and standalone environments. Versions 3.1.3.RELEASE and prior contain a security bypass vulnerability in the the expression execution mechanisms. Although the library provides mechanisms to prevent expression injection, it f…

### CVE-2026-40525
**volcengine openviking Auth Bypass**
- **Signals:** CVSS
- **Asset:** volcengine openviking
- **Attack:** Auth Bypass
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-05T18:06:02.667
- **CWE:** CWE-636
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-17)

> OpenViking prior to version 0.3.9 contains an authentication bypass vulnerability in the VikingBot OpenAPI HTTP route surface where the authentication check fails open when the api_key configuration value is unset or empty. Remote attackers with network access to the exposed serv…

### CVE-2026-6284
**An attacker with network access to the PLC is able to brute force discover passwords to gain unauthorized access to systems and services.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-20T16:16:50.357
- **CWE:** CWE-521
- **CWE:** CWE-521
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-17)

> An attacker with network access to the PLC is able to brute force discover passwords to gain unauthorized access to systems and services. The limited password complexity and no password input limiters makes brute force password enumeration possible.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-17*
