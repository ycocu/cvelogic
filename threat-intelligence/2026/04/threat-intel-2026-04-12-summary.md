# Daily Threat Intelligence — April 12, 2026

**Digest window (UTC):** 2026-04-12
**Generated:** 2026-06-02T07:34:54Z

## Threat brief

Novell Zenworks Configuration Manager — exploitation likelihood rose sharply (EPSS 37% → 52% · rising (+15%)).

## Executive summary

- Novell Zenworks Configuration Manager — exploitation likelihood rose sharply (EPSS 37% → 52% · rising (+15%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 1 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2010-4323
**novell zenworks_configuration_manager Buffer Overflow**
- **Signals:** EPSS
- **Asset:** novell zenworks_configuration_manager
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 37.2% (2025-10-28) → 51.9% (2026-04-12), Δ +14.8%**

> Heap-based buffer overflow in novell-tftp.exe in Novell ZENworks Configuration Manager (ZCM) 10.3.1, 10.3.2, and 11.0, and earlier versions, allows remote attackers to execute arbitrary code via a long TFTP request.

### CVE-2010-4328
**novell iprint_open_enterprise_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** novell iprint_open_enterprise_server
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 44.7% (2025-12-15) → 59.1% (2026-04-12), Δ +14.4%**

> Multiple stack-based buffer overflows in opt/novell/iprint/bin/ipsmd in Novell iPrint for Linux Open Enterprise Server 2 SP2 and SP3 allow remote attackers to execute arbitrary code via unspecified LPR opcodes.

### CVE-2019-25709
**codefuture image_hosting_script unsafe deserialization**
- **Signals:** CVSS
- **Asset:** codefuture image_hosting_script
- **Attack:** unsafe deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T20:22:37.493
- **CWE:** CWE-552
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-12)

> CF Image Hosting Script 1.6.5 allows unauthenticated attackers to download and decode the application database by accessing the imgdb.db file in the upload/data directory. Attackers can extract delete IDs stored in plaintext from the deserialized database and use them to delete a…

### CVE-2006-4336
**gzip gzip**
- **Signals:** EPSS
- **Asset:** gzip gzip
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 81
- **EPSS 2.6% (2026-03-02) → 13.8% (2026-04-12), Δ +11.3%**

> Buffer underflow in the build_tree function in unpack.c in gzip 1.3.5 allows context-dependent attackers to execute arbitrary code via a crafted leaf count table that causes a write to a negative index.

### CVE-2007-0653
**x_multimedia_system x_multimedia_system Memory Corruption**
- **Signals:** EPSS
- **Asset:** linux linux_kernel
- **Attack:** Memory Corruption
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 82
- **EPSS 10.0% (2025-11-07) → 20.1% (2026-04-12), Δ +10.1%**

> Integer overflow in X MultiMedia System (xmms) 1.2.10, and possibly other versions, allows user-assisted remote attackers to execute arbitrary code via crafted header information in a skin bitmap image, which triggers memory corruption.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-12*
