# Daily Threat Intelligence — January 12, 2026

**Digest window (UTC):** 2026-01-12
**Generated:** 2026-06-02T07:34:10Z

## Threat brief

Gogs added to CISA KEV — confirmed in-the-wild exploitation. · Assistanttools Music Tag Editor — exploitation likelihood rose sharply (EPSS 8.0% → 23% · rising (+15%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Gogs added to CISA KEV — confirmed in-the-wild exploitation.
- Assistanttools Music Tag Editor — exploitation likelihood rose sharply (EPSS 8.0% → 23% · rising (+15%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2025-8110
**Gogs Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** gogs gogs
- **Attack:** Path Traversal
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-20T13:47:34.450
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2026-01-12

> Improper Symbolic link handling in the PutContents API in Gogs allows Local Execution of Code.

### CVE-2009-3811
**assistanttools music_tag_editor Buffer Overflow**
- **Signals:** EPSS
- **Asset:** assistanttools music_tag_editor
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 8.0% (2025-03-30) → 23.2% (2026-01-12), Δ +15.2%**

> Stack-based buffer overflow in Music Tag Editor 1.61 build 212 allows remote attackers to execute arbitrary code via an MP3 file with a long ID3 tag.  NOTE: some of these details are obtained from third party information.

### CVE-2025-29329
**sagemcom f\@st_3686_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** sagemcom f\@st_3686_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-22T18:46:41.067
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-12)

> Buffer Overflow in the ippprint (Internet Printing Protocol) service in Sagemcom F@st 3686 MAGYAR_4.121.0 allows remote attacker to execute arbitrary code by sending a crafted HTTP request.

### CVE-2022-31269
**nortekcontrol emerge_e3_firmware**
- **Signals:** EPSS
- **Asset:** nortekcontrol emerge_e3_firmware
- **CVSS max:** 8.2
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:04:16.123
- **CWE:** CWE-798
- **Risk score:** 83
- **EPSS 68.2% (2025-11-21) → 81.0% (2026-01-12), Δ +12.9%**

> Nortek Linear eMerge E3-Series devices through 0.32-09c place admin credentials in /test.txt that allow an attacker to open a building's doors. (This occurs in situations where the CVE-2019-7271 default credentials have been changed.)

### CVE-2025-12420
**servicenow now_assist_ai_agents**
- **Signals:** CVSS
- **Asset:** servicenow now_assist_ai_agents
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-27T20:25:54.110
- **CWE:** CWE-250
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-12)

> A vulnerability has been identified in the ServiceNow AI Platform that could enable an unauthenticated user to impersonate another user and perform the operations that the impersonated user is entitled to perform.

ServiceNow has addressed this vulnerability by deploying a releva…

### CVE-2025-51567
**jayesh online_exam_system SQL Injection**
- **Signals:** CVSS
- **Asset:** jayesh online_exam_system
- **Attack:** SQL Injection
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-16T17:31:06.853
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-12)

> A SQL Injection was found in the /exam/user/profile.php page of kashipara Online Exam System V1.0, which allows remote attackers to execute arbitrary SQL command to get unauthorized database access via the rname, rcollage, rnumber, rgender and rpassword parameters in a POST HTTP …

### CVE-2025-66802
**covid-19_contact_tracing_system_project covid-19_contact_tracing_system RCE**
- **Signals:** CVSS
- **Asset:** covid-19_contact_tracing_system_project covid-19_contact_tracing_system
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-22T15:56:20.700
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-12)

> Sourcecodester Covid-19 Contact Tracing System 1.0 is vulnerable to RCE (Remote Code Execution). The application receives a reverse shell (php) into imagem of the user enabling RCE.

### CVE-2025-67146
**abhishekmali21 gym_management_system Auth Bypass**
- **Signals:** CVSS
- **Asset:** abhishekmali21 gym_management_system
- **Attack:** Auth Bypass
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-27T20:22:14.793
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-12)

> Multiple SQL Injection vulnerabilities exist in AbhishekMali21 GYM-MANAGEMENT-SYSTEM 1.0 via the 'name' parameter in (1) member_search.php, (2) trainer_search.php, and (3) gym_search.php, and via the 'id' parameter in (4) payment_search.php. An unauthenticated remote attacker can…

### CVE-2025-67147
**Multiple SQL Injection vulnerabilities exist in amansuryawanshi Gym-Management-System-PHP 1.0 via the 'name', 'email', and 'comment' para...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-12)

> Multiple SQL Injection vulnerabilities exist in amansuryawanshi Gym-Management-System-PHP 1.0 via the 'name', 'email', and 'comment' parameters in (1) submit_contact.php, the 'username' and 'pass_key' parameters in (2) secure_login.php, and the 'login_id', 'pwfield', and 'login_k…

### CVE-2026-22785
**orval orval**
- **Signals:** CVSS
- **Asset:** orval orval
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T20:00:15.910
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-12)

> orval generates type-safe JS clients (TypeScript) from any valid OpenAPI v3 or Swagger v2 specification. Prior to 7.18.0, the MCP server generation logic relies on string manipulation that incorporates the summary field from the OpenAPI specification without proper validation or …

### CVE-2026-22794
**appsmith appsmith**
- **Signals:** CVSS
- **Asset:** appsmith appsmith
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-21T19:14:17.880
- **CWE:** CWE-346
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-01-12)

> Appsmith is a platform to build admin panels, internal tools, and dashboards. Prior to 1.93, the server uses the Origin value from the request headers as the email link baseUrl without validation. If an attacker controls the Origin, password reset / email verification links in em…

### CVE-2026-22799
**emlog emlog**
- **Signals:** CVSS
- **Asset:** emlog emlog
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-21T19:13:49.570
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-12)

> Emlog is an open source website building system. emlog v2.6.1 and earlier exposes a REST API endpoint (/index.php?rest-api=upload) for media file uploads. The endpoint fails to implement proper validation of file types, extensions, and content, allowing authenticated attackers (w…

### CVE-2026-22813
**anoma opencode**
- **Signals:** CVSS
- **Asset:** anoma opencode
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-21T15:15:35.597
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-12)

> OpenCode is an open source AI coding agent. The markdown renderer used for LLM responses will insert arbitrary HTML into the DOM. There is no sanitization with DOMPurify or even a CSP on the web interface to prevent JavaScript execution via HTML injection. This means controlling …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-12*
