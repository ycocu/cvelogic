# Daily Threat Intelligence — August 02, 2025

**Digest window (UTC):** 2025-08-02
**Generated:** 2026-06-02T07:33:10Z

## Threat brief

Sielcosistemi Winlog Lite — exploitation likelihood rose sharply (EPSS 54% → 81% · rising (+27%)). · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- Sielcosistemi Winlog Lite — exploitation likelihood rose sharply (EPSS 54% → 81% · rising (+27%)).
- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2012-3815
**sielcosistemi winlog_lite Buffer Overflow**
- **Signals:** EPSS
- **Asset:** sielcosistemi winlog_lite
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 53.5% (2025-03-30) → 80.8% (2025-08-02), Δ +27.3%**

> Buffer overflow in RunTime.exe in Sielco Sistemi Winlog Pro SCADA before 2.07.18 and Winlog Lite SCADA before 2.07.18 allows remote attackers to execute arbitrary code via a crafted packet to TCP port 46824.  NOTE: some of these details are obtained from third party information.

### CVE-2025-7710
**The Brave Conversion Engine (PRO) plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 0.7.7.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-02)

> The Brave Conversion Engine (PRO) plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 0.7.7. This is due to the plugin not properly restricting a claimed identity while authenticating with Facebook. This makes it possible for unauthen…

### CVE-2025-6077
**Partner Software's Partner Software Product and corresponding Partner Web application use the same default username and password for the...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1391
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-02)

> Partner Software's Partner Software Product and corresponding Partner Web application use the same default username and password for the administrator account across all versions.

### CVE-2025-54782
**nestjs devtools-integration RCE**
- **Signals:** CVSS
- **Asset:** nestjs devtools-integration
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T17:31:16.827
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-02)

> Nest is a framework for building scalable Node.js server-side applications. In versions 0.2.0 and below, a critical Remote Code Execution (RCE) vulnerability was discovered in the @nestjs/devtools-integration package. When enabled, the package exposes a local development HTTP ser…

### CVE-2025-54790
**humhub files SQL injection**
- **Signals:** CVSS
- **Asset:** humhub files
- **Attack:** SQL injection
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T16:32:36.493
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-08-02)

> Files is a module for managing files inside spaces and user profiles. In versions 0.16.9 and below, Files does not have logic to prevent the exploitation of backend SQL queries without direct output, potentially allowing unauthorized data access. This is fixed in version 0.16.10.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-02*
