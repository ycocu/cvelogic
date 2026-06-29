# Daily Threat Intelligence — June 21, 2026

**Digest window (US Eastern, NVD):** 2026-06-21
**Generated:** 2026-06-29T10:33:09Z

## Threat brief

Exploitation likelihood rose sharply (EPSS 38% → 50% · rising (+12%)). · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- Exploitation likelihood rose sharply (EPSS 38% → 50% · rising (+12%)).
- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **6** |


## CVEs

### CVE-2025-27007
**Privilege Escalation · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD published:** 2025-05-01
- **NVD modified:** 2026-06-17
- **CWE:** CWE-266
- **Risk score:** 85
- **EPSS 38.2% (2026-06-18) → 50.2% (2026-06-21), Δ +12.0%**

> Incorrect Privilege Assignment vulnerability in Brainstorm Force OttoKit suretriggers allows Privilege Escalation.This issue affects OttoKit: from n/a through <= 1.0.82.

### CVE-1999-0009
**bsdi aix Buffer Overflow**
- **Signals:** EPSS
- **Asset:** data_general dg_ux
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD published:** 1998-04-08
- **NVD modified:** 2026-06-16
- **Risk score:** 84
- **EPSS 18.3% (2026-06-15) → 29.0% (2026-06-21), Δ +10.7%**

> Inverse query buffer overflow in BIND 4.9 and BIND 8 Releases.

### CVE-2026-56395
**b3log siyuan RCE**
- **Signals:** CVSS
- **Asset:** b3log siyuan
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD published:** 2026-06-21
- **NVD modified:** 2026-06-22
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-21)

> SiYuan before v3.6.1 fails to sanitize package metadata and README content in the Bazaar marketplace, allowing malicious package authors to inject arbitrary HTML and JavaScript. Attackers can achieve remote code execution on any user browsing the Bazaar by embedding XSS payloads …

### CVE-2026-11746
**A vulnerability has been identified in centraldogma-server versions prior to 0.84.0, where enabling ZooKeeper replication without setting...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD published:** 2026-06-21
- **NVD modified:** 2026-06-22
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-21)

> A vulnerability has been identified in centraldogma-server versions prior to 0.84.0, where enabling ZooKeeper replication without setting replication.secret causes the server to silently fall back to a hard-coded, publicly known secret. This default credential authenticates the e…

### CVE-2026-56265
**kidocode crawl4ai Auth Bypass**
- **Signals:** CVSS
- **Asset:** kidocode crawl4ai
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-06-21
- **NVD modified:** 2026-06-26
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-21)

> Crawl4AI before 0.8.7 contains an authentication bypass vulnerability due to a hardcoded default JWT signing key in the Docker API server. Attackers who know the default key can forge valid authentication tokens for any user, bypassing authentication and gaining full access to pr…

### CVE-2026-56397
**b3log siyuan RCE**
- **Signals:** CVSS
- **Asset:** b3log siyuan
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD published:** 2026-06-21
- **NVD modified:** 2026-06-24
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-21)

> SiYuan before v3.6.1 fails to sanitize package metadata and README content in the Bazaar marketplace, allowing malicious package authors to inject arbitrary HTML and JavaScript. Attackers can achieve remote code execution on any user browsing the Bazaar by embedding XSS payloads …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-21*
