# Daily Threat Intelligence — November 25, 2025

**Digest window (UTC):** 2025-11-25
**Generated:** 2026-06-02T07:33:51Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Microsoft Teams — exploitation likelihood rose sharply (EPSS 11% → 26% · rising (+15%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Microsoft Teams — exploitation likelihood rose sharply (EPSS 11% → 26% · rising (+15%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2021-24114
**microsoft teams Info Disclosure**
- **Signals:** EPSS
- **Asset:** microsoft teams
- **Attack:** Info Disclosure
- **CVSS max:** 5.7
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:52:23.107
- **Risk score:** 80
- **EPSS 10.7% (2025-07-22) → 25.9% (2025-11-25), Δ +15.2%**

> Microsoft Teams iOS Information Disclosure Vulnerability

### CVE-2025-51742
**jishenghua jsherp Deserialization**
- **Signals:** CVSS
- **Asset:** jishenghua jsherp
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-02T15:38:50.180
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-25)

> An issue was discovered in jishenghua JSH_ERP 2.3.1. The /material/getMaterialEnableSerialNumberList endpoint passes the search query parameter directly to parseObject(), introducing a Fastjson deserialization vulnerability that can lead to RCE via JDBC payloads.

### CVE-2025-51743
**jishenghua jsherp Deserialization**
- **Signals:** CVSS
- **Asset:** jishenghua jsherp
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-02T15:13:31.537
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-25)

> An issue was discovered in jishenghua JSH_ERP 2.3.1. The /materialCategory/addMaterialCategory endpoint is vulnerable to fastjson deserialization attacks.

### CVE-2025-13595
**The CIBELES AI plugin for WordPress is vulnerable to arbitrary file uploads due to missing capability check in the 'actualizador_git.php'...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-25)

> The CIBELES AI plugin for WordPress is vulnerable to arbitrary file uploads due to missing capability check in the 'actualizador_git.php' file in all versions up to, and including, 1.10.8. This makes it possible for unauthenticated attackers to download arbitrary GitHub repositor…

### CVE-2025-13597
**The AI Feeds plugin for WordPress is vulnerable to arbitrary file uploads due to missing capability check in the 'actualizador_git.php' f...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-25)

> The AI Feeds plugin for WordPress is vulnerable to arbitrary file uploads due to missing capability check in the 'actualizador_git.php' file in all versions up to, and including, 1.0.11. This makes it possible for unauthenticated attackers to download arbitrary GitHub repositorie…

### CVE-2025-51744
**jishenghua jsherp Deserialization**
- **Signals:** CVSS
- **Asset:** jishenghua jsherp
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-02T14:57:35.557
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-25)

> An issue was discovered in jishenghua JSH_ERP 2.3.1. The /user/addUser endpoint is vulnerable to fastjson deserialization attacks.

### CVE-2025-51745
**jishenghua jsherp Deserialization**
- **Signals:** CVSS
- **Asset:** jishenghua jsherp
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-02T14:56:09.757
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-25)

> An issue was discovered in jishenghua JSH_ERP 2.3.1. The /role/addcan endpoint is vulnerable to fastjson deserialization attacks.

### CVE-2025-51746
**jishenghua jsherp Deserialization**
- **Signals:** CVSS
- **Asset:** jishenghua jsherp
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-02T14:45:35.280
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-25)

> An issue was discovered in jishenghua JSH_ERP 2.3.1. The /serialNumber/addSerialNumber endpoint is vulnerable to fastjson deserialization attacks.

### CVE-2025-61168
**sigb pmb**
- **Signals:** CVSS
- **Asset:** sigb pmb
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-01T14:21:40.760
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-25)

> An issue in the cms_rest.php component of SIGB PMB v8.0.1.14 allows attackers to execute arbitrary code via unserializing an arbitrary file.

### CVE-2025-64063
**primakon project_contract_management privilege escalation**
- **Signals:** CVSS
- **Asset:** primakon project_contract_management
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-01T14:22:04.163
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-25)

> Primakon Pi Portal 1.0.18 API endpoints fail to enforce sufficient authorization checks when processing requests. Specifically, a standard user can exploit this flaw by sending direct HTTP requests to administrative endpoints, bypassing the UI restrictions. This allows the attack…

### CVE-2025-66016
**CGGMP24 is a state-of-art ECDSA TSS protocol that supports 1-round signing (requires 3 preprocessing rounds), identifiable abort, and a k...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-345
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-25)

> CGGMP24 is a state-of-art ECDSA TSS protocol that supports 1-round signing (requires 3 preprocessing rounds), identifiable abort, and a key refresh protocol. Prior to version 0.6.3, there is a missing check in the ZK proof that enables an attack in which single malicious signer c…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-25*
