# Daily Threat Intelligence — December 31, 2025

**Digest window (UTC):** 2025-12-31
**Generated:** 2026-06-02T07:34:05Z

## Threat brief

Adobe Flash Player — exploitation likelihood rose sharply (EPSS 17% → 29% · rising (+11%)). · 3 new critical disclosures — review patch status on exposed services.

## Executive summary

- Adobe Flash Player — exploitation likelihood rose sharply (EPSS 17% → 29% · rising (+11%)).
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

### CVE-2008-4819
**adobe flash_player**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 80
- **EPSS 17.0% (2025-07-26) → 28.5% (2025-12-31), Δ +11.5%**

> Unspecified vulnerability in Adobe Flash Player 9.0.124.0 and earlier makes it easier for remote attackers to conduct DNS rebinding attacks via unknown vectors.

### CVE-2021-42372
**xorux lpar2rrd Command Injection**
- **Signals:** EPSS
- **Asset:** xorux lpar2rrd
- **Attack:** Command Injection
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:27:40.980
- **CWE:** CWE-78
- **Risk score:** 83
- **EPSS 11.8% (2025-11-21) → 23.0% (2025-12-31), Δ +11.2%**

> A shell command injection in the HW Events SNMP community in XoruX LPAR2RRD and STOR2RRD before 7.30 allows authenticated remote attackers to execute arbitrary shell commands as the user running the service.

### CVE-2020-36904
**Selea CarPlateServer 4.0.1.6 contains a remote program execution vulnerability that allows attackers to execute arbitrary Windows binarie...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-31)

> Selea CarPlateServer 4.0.1.6 contains a remote program execution vulnerability that allows attackers to execute arbitrary Windows binaries by manipulating the NO_LIST_EXE_PATH configuration parameter. Attackers can bypass authentication through the /cps/ endpoint and modify serve…

### CVE-2003-0282
**info-zip openlinux_server Directory Traversal**
- **Signals:** EPSS
- **Asset:** info-zip unzip
- **Attack:** Directory Traversal
- **CVSS max:** 2.6
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 74
- **EPSS 10.7% (2025-09-28) → 21.1% (2025-12-31), Δ +10.4%**

> Directory traversal vulnerability in UnZip 5.50 allows attackers to overwrite arbitrary files via invalid characters between two . (dot) characters, which are filtered and result in a ".." sequence.

### CVE-2021-47744
**Cypress Solutions CTM-200/CTM-ONE 1.3.6 contains hard-coded credentials vulnerability in Linux distribution that exposes root access.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-31)

> Cypress Solutions CTM-200/CTM-ONE 1.3.6 contains hard-coded credentials vulnerability in Linux distribution that exposes root access. Attackers can exploit the static 'Chameleon' password to gain remote root access via Telnet or SSH on affected devices.

### CVE-2025-69288
**kromit titra RCE**
- **Signals:** CVSS
- **Asset:** kromit titra
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-13T15:25:44.200
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-31)

> Titra is open source project time tracking software. Prior to version 0.99.49, Titra allows any authenticated Admin user to modify the timeEntryRule in the database. The value is then passed to a NodeVM value to execute as code. Without sanitization, it leads to a Remote Code Exe…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-31*
