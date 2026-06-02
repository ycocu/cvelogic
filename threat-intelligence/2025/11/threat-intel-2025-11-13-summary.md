# Daily Threat Intelligence — November 13, 2025

**Digest window (UTC):** 2025-11-13
**Generated:** 2026-06-02T07:33:46Z

## Threat brief

6 new critical disclosures — review patch status on exposed services.

## Executive summary

- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **6** |


## CVEs

### CVE-2025-36250
**ibm aix**
- **Signals:** CVSS
- **Asset:** ibm vios
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-19T22:08:58.157
- **CWE:** CWE-114
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-13)

> IBM AIX 7.2, and 7.3 and IBM VIOS 3.1, and 4.1 NIM server (formerly known as NIM master) service (nimesis) could allow a remote attacker to execute arbitrary commands due to improper process controls.  This addresses additional attack vectors for a vulnerability that was previous…

### CVE-2025-64709
**typebot typebot SSRF**
- **Signals:** CVSS
- **Asset:** typebot typebot
- **Attack:** SSRF
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T14:23:42.560
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-11-13)

> Typebot is an open-source chatbot builder. In versions prior to 3.13.1, a Server-Side Request Forgery (SSRF) vulnerability in the Typebot webhook block (HTTP Request component) functionality allows authenticated users to make arbitrary HTTP requests from the server, including acc…

### CVE-2025-36251
**ibm aix**
- **Signals:** CVSS
- **Asset:** ibm vios
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-19T22:08:07.717
- **CWE:** CWE-114
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-11-13)

> IBM AIX 7.2, and 7.3 and IBM VIOS 3.1, and 4.1 nimsh service SSL/TLS implementations could allow a remote attacker to execute arbitrary commands due to improper process controls. This addresses additional attack vectors for a vulnerability that was previously addressed in CVE-202…

### CVE-2025-12762
**pgadmin pgadmin_4 RCE**
- **Signals:** CVSS
- **Asset:** pgadmin pgadmin_4
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-12-01T20:15:49.347
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-13)

> pgAdmin versions up to 9.9 are affected by a Remote Code Execution (RCE) vulnerability that occurs when running in server mode and performing restores from PLAIN-format dump files. This issue allows attackers to inject and execute arbitrary commands on the server hosting pgAdmin,…

### CVE-2025-36096
**ibm aix**
- **Signals:** CVSS
- **Asset:** ibm vios
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-19T22:11:50.723
- **CWE:** CWE-522
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-11-13)

> IBM AIX 7.2, and 7.3 and IBM VIOS 3.1, and 4.1 stores NIM private keys used in NIM environments in an insecure way which is susceptible to unauthorized access by an attacker using man in the middle techniques.

### CVE-2025-59367
**asus dsl-ac51_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** asus dsl-ac51_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-06T14:47:50.350
- **CWE:** CWE-288
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-13)

> An authentication bypass vulnerability has been identified in certain DSL series routers, may allow remote attackers to gain unauthorized access into the affected system. Refer to the 'Security Update for DSL Series Router' section on the ASUS Security Advisory for more informati…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-13*
