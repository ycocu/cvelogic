# Daily Threat Intelligence — February 01, 2026

**Digest window (UTC):** 2026-02-01
**Generated:** 2026-06-02T07:34:20Z

## Threat brief

Linpopup — exploitation likelihood rose sharply (EPSS 6.9% → 26% · rising (+19%)).

## Executive summary

- Linpopup — exploitation likelihood rose sharply (EPSS 6.9% → 26% · rising (+19%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 1 |
| Patch status change | 0 |
| **Total** | **3** |


## CVEs

### CVE-2004-1282
**linpopup linpopup Buffer Overflow**
- **Signals:** EPSS
- **Asset:** linpopup linpopup
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 86
- **EPSS 6.9% (2025-05-22) → 25.6% (2026-02-01), Δ +18.7%**

> Buffer overflow in the strexpand function in string.c for LinPopUp 1.2.0 allows remote attackers to execute arbitrary code via a crafted message that is not properly handled during a Reply operation.

### CVE-2024-12828
**webmin webmin RCE**
- **Signals:** EPSS
- **Asset:** webmin webmin
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-14T18:41:57.413
- **CWE:** CWE-78
- **Risk score:** 81
- **EPSS 11.6% (2026-01-29) → 21.7% (2026-02-01), Δ +10.1%**

> Webmin CGI Command Injection Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of Webmin. Authentication is required to exploit this vulnerability. 

The specific flaw exists within the handling of …

### CVE-2026-25069
**SunFounder Pironman Dashboard (pm_dashboard) version 1.3.13 and prior contain a path traversal vulnerability in the log file API endpoints.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-01)

> SunFounder Pironman Dashboard (pm_dashboard) version 1.3.13 and prior contain a path traversal vulnerability in the log file API endpoints. An unauthenticated remote attacker can supply traversal sequences via the filename parameter to read and delete arbitrary files. Successful …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-01*
