# Daily Threat Intelligence — November 29, 2025

**Digest window (UTC):** 2025-11-29
**Generated:** 2026-06-02T07:33:52Z

## Threat brief

Cisco Catalyst 6000 Intrusion Detection System Module — exploitation likelihood rose sharply (EPSS 15% → 41% · rising (+27%)). · 3 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cisco Catalyst 6000 Intrusion Detection System Module — exploitation likelihood rose sharply (EPSS 15% → 41% · rising (+27%)).
- 3 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 3 |
| Patch status change | 0 |
| **Total** | **6** |


## CVEs

### CVE-2001-0669
**cisco catalyst_6000_intrusion_detection_system_module**
- **Signals:** EPSS
- **Asset:** cisco catalyst_6000_intrusion_detection_system_module
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 14.8% (2025-03-30) → 41.5% (2025-11-29), Δ +26.7%**

> Various Intrusion Detection Systems (IDS) including (1) Cisco Secure Intrusion Detection System, (2) Cisco Catalyst 6000 Intrusion Detection System Module, (3) Dragon Sensor 4.x, (4) Snort before 1.8.1, (5) ISS RealSecure Network Sensor 5.x and 6.x before XPU 3.2, and (6) ISS Rea…

### CVE-2017-8625
**microsoft internet_explorer**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-276
- **Risk score:** 84
- **EPSS 47.6% (2025-11-21) → 69.8% (2025-11-29), Δ +22.2%**

> Internet Explorer in Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to bypass Device Guard User Mode Code Integrity (UMCI) policies due to Internet Explorer failing to validate UMCI policies, aka "Internet Explorer Security Feature Bypass Vulnerabil…

### CVE-2025-65112
**ricardoboss pubnet Privilege Escalation**
- **Signals:** CVSS
- **Asset:** ricardoboss pubnet
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-03T21:51:39.093
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-11-29)

> PubNet is a self-hosted Dart & Flutter package service. Prior to version 1.1.3, the /api/storage/upload endpoint in PubNet allows unauthenticated users to upload packages as any user by providing arbitrary author-id values. This enables identity spoofing, privilege escalation, an…

### CVE-2002-0048
**andrew_tridgell rsync DoS**
- **Signals:** EPSS
- **Asset:** andrew_tridgell rsync
- **Attack:** DoS
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 86
- **EPSS 69.5% (2025-03-30) → 81.8% (2025-11-29), Δ +12.3%**

> Multiple signedness errors (mixed signed and unsigned numbers) in the I/O functions of rsync 2.4.6, 2.3.2, and other versions allow remote attackers to cause a denial of service and execute arbitrary code in the rsync client or server.

### CVE-2025-66216
**aiscatcher ais-catcher Buffer Overflow**
- **Signals:** CVSS
- **Asset:** aiscatcher ais-catcher
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-23T16:13:40.410
- **CWE:** CWE-131
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-29)

> AIS-catcher is a multi-platform AIS receiver. Prior to version 0.64, a heap buffer overflow vulnerability has been identified in the AIS::Message class of AIS-catcher. This vulnerability allows an attacker to write approximately 1KB of arbitrary data into a 128-byte buffer. This …

### CVE-2025-66224
**orangehrm orangehrm**
- **Signals:** CVSS
- **Asset:** orangehrm orangehrm
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-03T16:55:22.137
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-11-29)

> OrangeHRM is a comprehensive human resource management (HRM) system. From version 5.0 to 5.7, the application contains an input-neutralization flaw in its mail configuration and delivery workflow that allows user-controlled values to flow directly into the system’s sendmail comma…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-29*
