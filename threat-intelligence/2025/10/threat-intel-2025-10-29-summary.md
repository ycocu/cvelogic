# Daily Threat Intelligence — October 29, 2025

**Digest window (UTC):** 2025-10-29
**Generated:** 2026-06-02T07:33:41Z

## Threat brief

Casbin Casdoor: public exploit or PoC linked (CSRF) · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Casbin Casdoor: public exploit or PoC linked (CSRF)
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 1 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2023-34927
**casbin casdoor CSRF**
- **Signals:** EXP
- **Asset:** casbin casdoor
- **Attack:** CSRF
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:07:40.793
- **CWE:** CWE-352
- **Risk score:** 78
- **EXP:** ref published 2025-10-29

> Casdoor v1.331.0 and below was discovered to contain a Cross-Site Request Forgery (CSRF) in the endpoint /api/set-password. This vulnerability allows attackers to arbitrarily change the victim user's password via supplying a crafted URL.

### CVE-2025-12479
**azure-access blu-ic2_firmware CSRF**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **Attack:** CSRF
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T13:45:44.610
- **CWE:** CWE-352
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-29)

> Systemic Lack of Cross-Site Request Forgery (CSRF) Token Implementation.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5 .

### CVE-2025-12476
**azure-access blu-ic2_firmware**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T14:36:37.570
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-29)

> Resource Lacking AuthN.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5 .

### CVE-2018-25120
**dlink dns-343_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** dlink dns-343_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-28T17:01:33.170
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-29)

> D-Link DNS-343 ShareCenter devices running firmware versions up to and including 1.05 contain a command injection vulnerability in the Mail Test functionality. The web maintenance script posts to the internal goForm endpoint '/goform/Mail_Test' and uses several form parameters di…

### CVE-2024-45162
**A stack-based buffer overflow issue was discovered in the phddns client in Blu-Castle BCUM221E 1.0.0P220507 via the password field.**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-29)

> A stack-based buffer overflow issue was discovered in the phddns client in Blu-Castle BCUM221E 1.0.0P220507 via the password field.

### CVE-2025-11200
**lfprojects mlflow Auth Bypass**
- **Signals:** CVSS
- **Asset:** lfprojects mlflow
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T01:06:20.083
- **CWE:** CWE-521
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-29)

> MLflow Weak Password Requirements Authentication Bypass Vulnerability. This vulnerability allows remote attackers to bypass authentication on affected installations of MLflow. Authentication is not required to exploit this vulnerability.

The specific flaw exists within the handl…

### CVE-2025-11201
**lfprojects mlflow RCE**
- **Signals:** CVSS
- **Asset:** lfprojects mlflow
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-04T21:22:41.407
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-29)

> MLflow Tracking Server Model Creation Directory Traversal Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of MLflow Tracking Server. Authentication is not required to exploit this vulnerability.

…

### CVE-2025-11202
**win-cli-mcp-server resolveCommandPath Command Injection Remote Code Execution Vulnerability.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-29)

> win-cli-mcp-server resolveCommandPath Command Injection Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of win-cli-mcp-server. Authentication is not required to exploit this vulnerability.

The sp…

### CVE-2025-12477
**azure-access blu-ic2_firmware**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T14:34:09.533
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-29)

> Server Version Disclosure.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5 .

### CVE-2025-12478
**azure-access blu-ic2_firmware**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T13:51:33.857
- **CWE:** CWE-326
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-29)

> Non-Compliant TLS Configuration.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5 .

### CVE-2025-63622
**fabian online_complaint_site SQL Injection**
- **Signals:** CVSS
- **Asset:** fabian online_complaint_site
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-03T18:35:04.287
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-29)

> A vulnerability was found in code-projects Online Complaint Site 1.0. This issue affects some unknown processing of the file /cms/admin/subcategory.php. This manipulation of the argument category causes SQL injection.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-29*
