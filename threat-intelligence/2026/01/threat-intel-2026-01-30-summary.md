# Daily Threat Intelligence — January 30, 2026

**Digest window (UTC):** 2026-01-30
**Generated:** 2026-06-02T07:34:19Z

## Threat brief

Gv — exploitation likelihood rose sharply (EPSS 9.4% → 25% · rising (+16%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Gv — exploitation likelihood rose sharply (EPSS 9.4% → 25% · rising (+16%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2004-1717
**gv gv Buffer Overflow**
- **Signals:** EPSS
- **Asset:** gv gv
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 9.4% (2025-03-30) → 25.3% (2026-01-30), Δ +15.9%**

> Multiple buffer overflows in the psscan function in ps.c for gv (ghostview) allow remote attackers to execute arbitrary code via a Postscript file with a long (1) BoundingBox, (2) comment, (3) Orientation, (4) PageOrder, or (5) Pages value.

### CVE-2002-0559
**oracle application_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** oracle application_server
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 26.4% (2025-03-30) → 38.7% (2026-01-30), Δ +12.3%**

> Buffer overflows in PL/SQL module 3.0.9.8.2 in Oracle 9i Application Server 1.0.2.x allow remote attackers to cause a denial of service or execute arbitrary code via (1) a long help page request without a dadname, which overflows the resulting HTTP Location header, (2) a long HTT…

### CVE-2026-1699
**eclipse theia_website**
- **Signals:** CVSS
- **Asset:** eclipse theia_website
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T18:23:17.930
- **CWE:** CWE-829
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-30)

> In the Eclipse Theia Website repository, the GitHub Actions workflow .github/workflows/preview.yml used pull_request_target trigger while checking out and executing untrusted pull request code. This allowed any GitHub user to execute arbitrary code in the repository's CI environm…

### CVE-2015-7805
**mega-nerd libsndfile Buffer Overflow**
- **Signals:** EPSS
- **Asset:** opensuse opensuse
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 47.7% (2026-01-08) → 58.5% (2026-01-30), Δ +10.9%**

> Heap-based buffer overflow in libsndfile 1.0.25 allows remote attackers to have unspecified impact via the headindex value in the header in an AIFF file.

### CVE-2020-37027
**Sickbeard alpha contains a remote command injection vulnerability that allows unauthenticated attackers to execute arbitrary commands thr...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-30)

> Sickbeard alpha contains a remote command injection vulnerability that allows unauthenticated attackers to execute arbitrary commands through the extra scripts configuration. Attackers can set malicious commands in the extra scripts field and trigger processing to execute remote …

### CVE-2020-37052
**AirControl 1.4.2 contains a pre-authentication remote code execution vulnerability that allows unauthenticated attackers to execute arbit...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-30)

> AirControl 1.4.2 contains a pre-authentication remote code execution vulnerability that allows unauthenticated attackers to execute arbitrary system commands through malicious Java expression injection. Attackers can exploit the /.seam endpoint by crafting a specially constructed…

### CVE-2023-50564
**pluck-cms pluck**
- **Signals:** EPSS
- **Asset:** pluck-cms pluck
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:37:04.857
- **CWE:** CWE-434
- **CWE:** CWE-434
- **Risk score:** 82
- **EPSS 24.9% (2026-01-01) → 35.2% (2026-01-30), Δ +10.3%**

> An arbitrary file upload vulnerability in the component /inc/modules_install.php of Pluck-CMS v4.7.18 allows attackers to execute arbitrary code via uploading a crafted ZIP file.

### CVE-2025-24293
**# Active Storage allowed transformation methods potentially unsafe Active Storage attempts to prevent the use of potentially unsafe image...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-30)

> # Active Storage allowed transformation methods potentially unsafe

Active Storage attempts to prevent the use of potentially unsafe image
transformation methods and parameters by default.

The default allowed list contains three methods allow for the circumvention
of the s…

### CVE-2025-26385
**Johnson Controls Metasys component listed below have Improper Neutralization of Special Elements used in a Command (Command Injection) Vu...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-01-30)

> Johnson Controls Metasys component listed below have  Improper Neutralization of Special Elements used in a Command (Command Injection) Vulnerability . Successful exploitation of this vulnerability could allow remote SQL execution This issue affects 



  *  Metasys: Application …

### CVE-2025-51958
**aelsantex runcommand**
- **Signals:** CVSS
- **Asset:** aelsantex runcommand
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T18:01:46.323
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-30)

> aelsantex runcommand 2014-04-01, a plugin for DokuWiki, allows unauthenticated attackers to execute arbitrary system commands via lib/plugins/runcommand/postaction.php.

### CVE-2025-7964
**After receiving a malformed 802.15.4 MAC Data Request the Zigbee Coordinator sends a ‘network leave’ request to Zigbee router resulting i...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-229
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-30)

> After receiving a 

malformed 802.15.4 MAC Data Request

 the Zigbee Coordinator sends a ‘network leave’ request to Zigbee router resulting in the Zigbee Router getting stuck in a non-rejoinable state. If a suitable parent is not available, the end devices will be unable to rejoi…

### CVE-2026-1723
**Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in TOTOLINK X6000R allows OS Com...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-30)

> Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in TOTOLINK X6000R allows OS Command Injection.This issue affects X6000R: through V9.4.0cu.1498_B20250826.

### CVE-2026-25130
**Cybersecurity AI (CAI) is a framework for AI Security.**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-01-30)

> Cybersecurity AI (CAI) is a framework for AI Security. In versions up to and including 0.5.10, the CAI (Cybersecurity AI) framework contains multiple argument injection vulnerabilities in its function tools. User-controlled input is passed directly to shell commands via `subproce…

### CVE-2026-25141
**orval orval**
- **Signals:** CVSS
- **Asset:** orval orval
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T18:21:56.603
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-30)

> Orval generates type-safe JS clients (TypeScript) from any valid OpenAPI v3 or Swagger v2 specification. Versions starting with 7.19.0 and prior to 7.21.0 and 8.2.0 have an incomplete fix for CVE-2026-23947. While the jsStringEscape function properly handles single quotes ('), do…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-30*
