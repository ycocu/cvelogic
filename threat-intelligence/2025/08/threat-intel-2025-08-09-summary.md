# Daily Threat Intelligence — August 09, 2025

**Digest window (UTC):** 2025-08-09
**Generated:** 2026-06-02T07:33:12Z

## Threat brief

Advantech Adamview — exploitation likelihood rose sharply (EPSS 11% → 28% · rising (+17%)).

## Executive summary

- Advantech Adamview — exploitation likelihood rose sharply (EPSS 11% → 28% · rising (+17%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **3** |


## CVEs

### CVE-2014-8386
**advantech adamview Buffer Overflow**
- **Signals:** EPSS
- **Asset:** advantech adamview
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 10.7% (2025-03-30) → 27.9% (2025-08-09), Δ +17.2%**

> Multiple stack-based buffer overflows in Advantech AdamView 4.3 and earlier allow remote attackers to execute arbitrary code via a crafted (1) display properties or (2) conditional bitmap parameter in a GNI file.

### CVE-2025-6573
**Kernel software installed and running inside an untrusted/rich execution environment (REE) could leak information from the trusted execut...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-280
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-09)

> Kernel software installed and running inside an untrusted/rich execution environment (REE) could leak information from the trusted execution environment (TEE).

### CVE-2025-54997
**openbao openbao privilege escalation**
- **Signals:** CVSS
- **Asset:** openbao openbao
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-13T18:23:12.113
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-09)

> OpenBao exists to provide a software solution to manage, store, and distribute sensitive data including secrets, certificates, and keys. In versions 2.3.1 and below, some OpenBao deployments intentionally limit privileged API operators from executing system code or making network…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-09*
