# Daily Threat Intelligence — March 10, 2026

**Digest window (UTC):** 2026-03-10
**Generated:** 2026-06-02T07:34:36Z

## Threat brief

Swim Team Project Swim Team — exploitation likelihood rose sharply (EPSS 38% → 54% · rising (+16%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Swim Team Project Swim Team — exploitation likelihood rose sharply (EPSS 38% → 54% · rising (+16%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2015-5471
**swim_team_project swim_team Path Traversal**
- **Signals:** EPSS
- **Asset:** swim_team_project swim_team
- **Attack:** Path Traversal
- **CVSS max:** 5.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-22
- **Risk score:** 79
- **EPSS 38.2% (2026-01-21) → 54.0% (2026-03-10), Δ +15.8%**

> Absolute path traversal vulnerability in include/user/download.php in the Swim Team plugin 1.44.10777 for WordPress allows remote attackers to read arbitrary files via a full pathname in the file parameter.

### CVE-2015-5688
**geddyjs geddy Directory Traversal**
- **Signals:** EPSS
- **Asset:** geddyjs geddy
- **Attack:** Directory Traversal
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-22
- **Risk score:** 78
- **EPSS 69.4% (2026-03-04) → 81.1% (2026-03-10), Δ +11.7%**

> Directory traversal vulnerability in lib/app/index.js in Geddy before 13.0.8 for Node.js allows remote attackers to read arbitrary files via a ..%2f (dot dot encoded slash) in the PATH_INFO to the default URI.

### CVE-2026-0124
**google android memory safety**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** memory safety
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T17:13:25.993
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-03-10)

> There is a possible out of bounds write due to a missing bounds check. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2026-0110
**google android Memory Corruption**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T17:14:10.313
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-10)

> In MM_DATA_IND of cn_NrSmMsgHdlrFromMM.cpp, there is a possible EoP due to memory corruption. This could lead to remote escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2026-0111
**google android memory safety**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** memory safety
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T17:14:06.340
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-10)

> In ns_GetUserData of ns_SmscbUtilities.c, there is a possible out of bounds write due to an incorrect bounds check. This could lead to remote escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2026-0113
**google android memory safety**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** memory safety
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T17:13:57.523
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-10)

> In ns_GetUserData of ns_SmscbUtilities.c, there is a possible out of bounds write due to an incorrect bounds check. This could lead to remote escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2026-0114
**google android RCE**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T17:13:53.773
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-10)

> In Modem, there is a possible out of bounds write due to an incorrect bounds check. This could lead to remote code execution with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2026-0116
**google android RCE**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T17:13:42.907
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-10)

> In __mfc_handle_released_buf of mfc_core_isr.c, there is a possible out of bounds write due to a missing bounds check. This could lead to remote code execution with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2026-0120
**google android RCE**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T16:47:39.150
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-10)

> In modem, there is a possible out of bounds write due to an incorrect bounds check. This could lead to remote code execution with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2026-28806
**nerves-hub nerveshub privilege escalation**
- **Signals:** CVSS
- **Asset:** nerves-hub nerveshub
- **Attack:** privilege escalation
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T13:47:15.800
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-10)

> Improper Authorization vulnerability in nerves-hub nerves_hub_web allows cross-organization device control via device bulk actions and device update API.

Missing authorization checks in the device bulk actions and device update API endpoints allow authenticated users to target d…

### CVE-2026-30965
**parseplatform parse-server**
- **Signals:** CVSS
- **Asset:** parseplatform parse-server
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T15:31:39.400
- **CWE:** CWE-863
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-10)

> Parse Server is an open source backend that can be deployed to any infrastructure that can run Node.js. Prior to 9.5.2-alpha.8 and 8.6.21, a vulnerability in Parse Server's query handling allows an authenticated or unauthenticated attacker to exfiltrate session tokens of other us…

### CVE-2026-30966
**parseplatform parse-server**
- **Signals:** CVSS
- **Asset:** parseplatform parse-server
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T19:50:29.950
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-03-10)

> Parse Server is an open source backend that can be deployed to any infrastructure that can run Node.js. Prior to 9.5.2-alpha.7 and 8.6.20, Parse Server's internal tables, which store Relation field mappings such as role memberships, can be directly accessed via the REST API or Gr…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-10*
