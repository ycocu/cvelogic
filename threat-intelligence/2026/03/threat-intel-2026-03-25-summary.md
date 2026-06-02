# Daily Threat Intelligence — March 25, 2026

**Digest window (UTC):** 2026-03-25
**Generated:** 2026-06-02T07:34:45Z

## Threat brief

Langflow added to CISA KEV — confirmed in-the-wild exploitation. · Evilmartians Imgproxy — exploitation likelihood rose sharply (EPSS 24% → 40% · rising (+16%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Langflow added to CISA KEV — confirmed in-the-wild exploitation.
- Evilmartians Imgproxy — exploitation likelihood rose sharply (EPSS 24% → 40% · rising (+16%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2026-33017
**Langflow Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** langflow langflow
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-21T21:16:31.950
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2026-03-25

> Langflow is a tool for building and deploying AI-powered agents and workflows. In versions prior to 1.9.0, the POST /api/v1/build_public_tmp/{flow_id}/flow endpoint allows building public flows without requiring authentication. When the optional data parameter is supplied, the en…

### CVE-2023-1496
**evilmartians imgproxy XSS**
- **Signals:** EPSS
- **Asset:** evilmartians imgproxy
- **Attack:** XSS
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:39:18.763
- **CWE:** CWE-79
- **Risk score:** 79
- **EPSS 24.1% (2026-03-21) → 39.8% (2026-03-25), Δ +15.7%**

> Cross-site Scripting (XSS) - Reflected in GitHub repository imgproxy/imgproxy prior to 3.14.0.

### CVE-2026-32523
**Unrestricted Upload of File with Dangerous Type vulnerability in denishua WPJAM Basic wpjam-basic allows Using Malicious Files.This issue...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T16:35:20.070
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-25)

> Unrestricted Upload of File with Dangerous Type vulnerability in denishua WPJAM Basic wpjam-basic allows Using Malicious Files.This issue affects WPJAM Basic: from n/a through <= 6.9.2.

### CVE-2007-0297
**oracle enterpriseone**
- **Signals:** EPSS
- **Asset:** oracle enterpriseone
- **CVSS max:** 4.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 77
- **EPSS 14.6% (2025-12-20) → 27.7% (2026-03-25), Δ +13.0%**

> Unspecified vulnerability in Oracle PeopleSoft Enterprise and JD Edwards EnterpriseOne 8.47.11 and 8.48.06 has unknown impact and attack vectors in PeopleTools, aka PSE03.

### CVE-2022-35690
**adobe coldfusion RCE**
- **Signals:** EPSS
- **Asset:** adobe coldfusion
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:11:29.117
- **CWE:** CWE-121
- **CWE:** CWE-787
- **Risk score:** 86
- **EPSS 1.9% (2026-02-04) → 14.7% (2026-03-25), Δ +12.8%**

> Adobe ColdFusion versions Update 14 (and earlier) and Update 4 (and earlier) are affected by a Stack-based Buffer Overflow vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue does not require user interaction,…

### CVE-2025-70888
**osslsigncode_project osslsigncode privilege escalation**
- **Signals:** CVSS
- **Asset:** osslsigncode_project osslsigncode
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-02T17:13:18.527
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-25)

> An issue in mtrojnar Osslsigncode affected at v2.10 and before allows a remote attacker to escalate privileges via the osslsigncode.c component

### CVE-2026-32520
**Incorrect Privilege Assignment vulnerability in Andrew Munro / AffiliateWP RewardsWP rewardswp allows Privilege Escalation.This issue aff...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T16:35:20.070
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-25)

> Incorrect Privilege Assignment vulnerability in Andrew Munro / AffiliateWP RewardsWP rewardswp allows Privilege Escalation.This issue affects RewardsWP: from n/a through <= 1.0.4.

### CVE-2026-32524
**Unrestricted Upload of File with Dangerous Type vulnerability in Jordy Meow Photo Engine wplr-sync allows Upload a Web Shell to a Web Ser...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T16:35:20.070
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-25)

> Unrestricted Upload of File with Dangerous Type vulnerability in Jordy Meow Photo Engine wplr-sync allows Upload a Web Shell to a Web Server.This issue affects Photo Engine: from n/a through <= 6.4.9.

### CVE-2026-32525
**Improper Control of Generation of Code ('Code Injection') vulnerability in jetmonsters JetFormBuilder jetformbuilder allows Code Injectio...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T16:35:20.070
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-25)

> Improper Control of Generation of Code ('Code Injection') vulnerability in jetmonsters JetFormBuilder jetformbuilder allows Code Injection.This issue affects JetFormBuilder: from n/a through <= 3.5.6.1.

### CVE-2026-32536
**Unrestricted Upload of File with Dangerous Type vulnerability in halfdata Green Downloads halfdata-paypal-green-downloads allows Using Ma...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T16:35:20.070
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-25)

> Unrestricted Upload of File with Dangerous Type vulnerability in halfdata Green Downloads halfdata-paypal-green-downloads allows Using Malicious Files.This issue affects Green Downloads: from n/a through <= 2.08.

### CVE-2026-32539
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in PublishPress PublishPress Revisions...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T16:35:20.070
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-25)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in PublishPress PublishPress Revisions revisionary allows Blind SQL Injection.This issue affects PublishPress Revisions: from n/a through <= 3.7.23.

### CVE-2026-32573
**Improper Control of Generation of Code ('Code Injection') vulnerability in Nelio Software Nelio AB Testing nelio-ab-testing allows Code I...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-24T16:35:20.070
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-25)

> Improper Control of Generation of Code ('Code Injection') vulnerability in Nelio Software Nelio AB Testing nelio-ab-testing allows Code Injection.This issue affects Nelio AB Testing: from n/a through <= 8.2.7.

### CVE-2026-33660
**n8n n8n RCE**
- **Signals:** CVSS
- **Asset:** n8n n8n
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T14:54:07.600
- **CWE:** CWE-94
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-25)

> n8n is an open source workflow automation platform. Prior to versions 2.14.1, 2.13.3, and 1.123.26, an authenticated user with permission to create or modify workflows could use the Merge node's "Combine by SQL" mode to read local files on the n8n host and achieve remote code exe…

### CVE-2026-33696
**n8n n8n**
- **Signals:** CVSS
- **Asset:** n8n n8n
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-27T19:40:55.160
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-25)

> n8n is an open source workflow automation platform. Prior to versions 2.14.1, 2.13.3, and 1.123.27, an authenticated user with permission to create or modify workflows could exploit a prototype pollution vulnerability in the XML and the GSuiteAdmin nodes. By supplying a crafted p…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-25*
