# Daily Threat Intelligence — September 10, 2025

**Digest window (UTC):** 2025-09-10
**Generated:** 2026-06-02T07:33:23Z

## Threat brief

Nagios Xi — exploitation likelihood rose sharply (EPSS 12% → 34% · rising (+22%)). · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- Nagios Xi — exploitation likelihood rose sharply (EPSS 12% → 34% · rising (+22%)).
- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2022-38254
**nagios nagios_xi XSS**
- **Signals:** EPSS
- **Asset:** nagios nagios_xi
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:16:07.833
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 12.0% (2025-09-09) → 33.5% (2025-09-10), Δ +21.6%**

> Nagios XI before v5.8.7 was discovered to contain a cross-site scripting (XSS) vulnerability via the ajax.php script in CCM 3.1.5.

### CVE-2010-4557
**invensys foxboro_i\/a_series_batch Buffer Overflow**
- **Signals:** EPSS
- **Asset:** invensys wonderware_inbatch
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 30.0% (2025-08-26) → 45.1% (2025-09-10), Δ +15.0%**

> Buffer overflow in the lm_tcp service in Invensys Wonderware InBatch 8.1 and 9.0, as used in Invensys Foxboro I/A Series Batch 8.1 and possibly other products, allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a crafted request t…

### CVE-2025-54123
**hoverfly hoverfly Command Injection**
- **Signals:** CVSS
- **Asset:** hoverfly hoverfly
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-17T21:17:53.460
- **CWE:** CWE-20
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-10)

> Hoverfly is an open source API simulation tool. In versions 1.11.3 and prior, the middleware functionality in Hoverfly is vulnerable to command injection vulnerability at `/api/v2/hoverfly/middleware` endpoint due to insufficient validation and sanitization in user input. The vul…

### CVE-2016-5743
**siemens simatic_batch**
- **Signals:** EPSS
- **Asset:** siemens simatic_batch
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-20
- **Risk score:** 85
- **EPSS 5.6% (2025-04-24) → 17.8% (2025-09-10), Δ +12.1%**

> Siemens SIMATIC WinCC before 7.3 Update 10 and 7.4 before Update 1, SIMATIC BATCH before 8.1 SP1 Update 9 as distributed in SIMATIC PCS 7 through 8.1 SP1, SIMATIC OpenPCS 7 before 8.1 Update 3 as distributed in SIMATIC PCS 7 through 8.1 SP1, SIMATIC OpenPCS 7 before 8.2 Update 1 …

### CVE-2025-10220
**axxonsoft axxon_one**
- **Signals:** CVSS
- **Asset:** axxonsoft axxon_one
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T14:34:29.803
- **CWE:** CWE-1104
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-10)

> Use of Unmaintained Third Party Components (CWE-1104) in the NuGet dependency components in AxxonSoft Axxon One VMS 2.0.0 through 2.0.4 on Windows allows a remote attacker to execute arbitrary code or bypass security features via exploitation of vulnerable third-party packages su…

### CVE-2025-10226
**axxonsoft axxon_one privilege escalation**
- **Signals:** CVSS
- **Asset:** axxonsoft axxon_one
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T13:54:04.383
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-10)

> Dependency on Vulnerable Third-Party Component (CWE-1395) in the PostgreSQL backend in AxxonSoft Axxon One (C-Werk) 2.0.8 and earlier on Windows and Linux allows a remote attacker to escalate privileges, execute arbitrary code, or cause denial-of-service via exploitation of multi…

### CVE-2025-9943
**An SQL injection vulnerability has been identified in the "ID" attribute of the SAML response when the replay cache of the Shibboleth Ser...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-10)

> An SQL injection vulnerability has been identified in the "ID" attribute of the SAML response when the replay cache of the Shibboleth Service Provider (SP) is configured to use an SQL database as storage service. An unauthenticated attacker can exploit this issue via blind SQL in…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-10*
