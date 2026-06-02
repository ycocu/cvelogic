# Daily Threat Intelligence — May 18, 2025

**Digest window (UTC):** 2025-05-18
**Generated:** 2026-06-02T07:32:44Z

## Threat brief

Invisioncommunity: public exploit or PoC linked (RCE) · Simple Ads Manager Project Simple Ads Manager — exploitation likelihood rose sharply (EPSS 29% → 43% · rising (+14%)).

## Executive summary

- Invisioncommunity: public exploit or PoC linked (RCE)
- Simple Ads Manager Project Simple Ads Manager — exploitation likelihood rose sharply (EPSS 29% → 43% · rising (+14%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 3 |
| EPSS rise | 1 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2025-1731
**zyxel uos privilege escalation**
- **Signals:** EXP
- **Asset:** zyxel uos
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T17:55:46.857
- **CWE:** CWE-732
- **Risk score:** 78
- **EXP:** ref published 2025-05-18

> An incorrect permission assignment vulnerability in the PostgreSQL commands of the Zyxel USG FLEX H series uOS firmware versions from V1.20 through V1.31 could allow an authenticated local attacker with low privileges to gain access to the Linux shell and escalate their privilege…

### CVE-2025-31161
**CrushFTP Authentication Bypass Vulnerability**
- **Signals:** EXP
- **Asset:** crushftp crushftp
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T22:04:34.230
- **CWE:** CWE-305
- **Risk score:** 78
- **EXP:** ref published 2025-05-18

> CrushFTP 10 before 10.8.4 and 11 before 11.3.1 allows authentication bypass and takeover of the crushadmin account (unless a DMZ proxy instance is used), as exploited in the wild in March and April 2025, aka "Unauthenticated HTTP(S) port access." A race condition exists in the AW…

### CVE-2015-2826
**simple_ads_manager_project simple_ads_manager**
- **Signals:** EPSS
- **Asset:** simple_ads_manager_project simple_ads_manager
- **CVSS max:** 5.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-200
- **Risk score:** 79
- **EPSS 28.9% (2025-04-06) → 43.2% (2025-05-18), Δ +14.3%**

> WordPress Simple Ads Manager plugin 2.5.94 and 2.5.96 allows remote attackers to obtain sensitive information.

### CVE-2025-47916
**invisioncommunity invisioncommunity RCE**
- **Signals:** EXP
- **Asset:** invisioncommunity invisioncommunity
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-20T17:42:15.083
- **CWE:** CWE-1336
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-05-18

> Invision Community 5.0.0 before 5.0.7 allows remote code execution via crafted template strings to themeeditor.php. The issue lies within the themeeditor controller (file: /applications/core/modules/front/system/themeeditor.php), where a protected method named customCss can be in…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-18*
