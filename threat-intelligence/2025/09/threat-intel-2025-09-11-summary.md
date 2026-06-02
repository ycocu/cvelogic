# Daily Threat Intelligence — September 11, 2025

**Digest window (UTC):** 2025-09-11
**Generated:** 2026-06-02T07:33:24Z

## Threat brief

Dassault Systèmes DELMIA Apriso added to CISA KEV — confirmed in-the-wild exploitation. · Videolan Vlc Media Player — exploitation likelihood rose sharply (EPSS 62% → 73% · rising (+11%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Dassault Systèmes DELMIA Apriso added to CISA KEV — confirmed in-the-wild exploitation.
- Videolan Vlc Media Player — exploitation likelihood rose sharply (EPSS 62% → 73% · rising (+11%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2025-5086
**Dassault Systèmes DELMIA Apriso Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** 3ds delmia_apriso
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-29T13:50:15.843
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2025-09-11

> A deserialization of untrusted data vulnerability affecting DELMIA Apriso from Release 2020 through Release 2025 could lead to a remote code execution.

### CVE-2012-1775
**videolan vlc_media_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** videolan vlc_media_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 62.3% (2025-03-30) → 72.9% (2025-09-11), Δ +10.6%**

> Stack-based buffer overflow in VideoLAN VLC media player before 2.0.1 allows remote attackers to execute arbitrary code via a crafted MMS:// stream.

### CVE-2025-58321
**deltaww dialink Directory Traversal**
- **Signals:** CVSS
- **Asset:** deltaww dialink
- **Attack:** Directory Traversal
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-26T14:43:15.530
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-11)

> Delta Electronics DIALink has an Directory Traversal Authentication Bypass Vulnerability.

### CVE-2025-27466
**xen xen**
- **Signals:** CVSS
- **Asset:** xen xen
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T22:16:08.697
- **CWE:** CWE-395
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-11)

> [This CNA information record relates to multiple CVEs; the
text explains which aspects/vulnerabilities correspond to which CVE.]

There are multiple issues related to the handling and accessing of guest
memory pages in the viridian code:

 1. A NULL pointer dereference in the upd…

### CVE-2025-40687
**phpgurukul online_fire_reporting_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul online_fire_reporting_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T15:32:29.880
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-11)

> SQL Injection in Online Fire Reporting System v1.2 by PHPGurukul. This vulnerability allows an attacker to retrieve, create, update and delete database via 

'mobilenumber', 'teamleadname' and 'teammember' parameters in the endpoint '/ofrs/admin/add-team.php'.

### CVE-2025-40689
**phpgurukul online_fire_reporting_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul online_fire_reporting_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T15:32:20.270
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-11)

> SQL Injection in Online Fire Reporting System v1.2 by PHPGurukul. This vulnerability allows an attacker to retrieve, create, update and delete database via 

'remark', 'status' and 'requestid' parameters in the endpoint '/ofrs/admin/request-details.php'.

### CVE-2025-40690
**phpgurukul online_fire_reporting_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul online_fire_reporting_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T15:32:04.580
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-11)

> SQL Injection in Online Fire Reporting System v1.2 by PHPGurukul. This vulnerability allows an attacker to retrieve, create, update and delete database via 'teamid' parameter in the endpoint '/ofrs/admin/edit-team.php'.

### CVE-2025-40691
**phpgurukul online_fire_reporting_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul online_fire_reporting_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T15:31:54.967
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-11)

> SQL Injection in Online Fire Reporting System v1.2 by PHPGurukul. This vulnerability allows an attacker to retrieve, create, update and delete database via 

'todate' parameter in the endpoint '/ofrs/admin/bwdates-report-result.php'.

### CVE-2025-40692
**phpgurukul online_fire_reporting_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul online_fire_reporting_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T15:31:47.440
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-11)

> SQL Injection in Online Fire Reporting System v1.2 by PHPGurukul. This vulnerability allows an attacker to retrieve, create, update and delete database via 

'requestid' parameter in the endpoint '/ofrs/details.php'.

### CVE-2025-58142
**xen xen**
- **Signals:** CVSS
- **Asset:** xen xen
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T22:16:32.257
- **CWE:** CWE-395
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-11)

> [This CNA information record relates to multiple CVEs; the
text explains which aspects/vulnerabilities correspond to which CVE.]

There are multiple issues related to the handling and accessing of guest
memory pages in the viridian code:

 1. A NULL pointer dereference in the upd…

### CVE-2025-58143
**xen xen**
- **Signals:** CVSS
- **Asset:** xen xen
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T22:16:32.393
- **CWE:** CWE-366
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-11)

> [This CNA information record relates to multiple CVEs; the
text explains which aspects/vulnerabilities correspond to which CVE.]

There are multiple issues related to the handling and accessing of guest
memory pages in the viridian code:

 1. A NULL pointer dereference in the upd…

### CVE-2025-59053
**AIRI is a self-hosted, artificial intelligence based Grok Companion.**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-09-11)

> AIRI is a self-hosted, artificial intelligence based Grok Companion. In v0.7.2-beta.2 in the `packages/stage-ui/src/components/MarkdownRenderer.vue` path, the Markdown content is processed using the useMarkdown composable, and the processed HTML is rendered directly into the DOM …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-11*
