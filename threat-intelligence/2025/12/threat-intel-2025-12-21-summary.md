# Daily Threat Intelligence — December 21, 2025

**Digest window (UTC):** 2025-12-21
**Generated:** 2026-06-02T07:34:01Z

## Threat brief

Microsoft Windows Server 2012 — exploitation likelihood rose sharply (EPSS 26% → 52% · rising (+25%)).

## Executive summary

- Microsoft Windows Server 2012 — exploitation likelihood rose sharply (EPSS 26% → 52% · rising (+25%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2019-0785
**microsoft windows_server_2012 RCE**
- **Signals:** EPSS
- **Asset:** microsoft windows_server_2012
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:17:16.787
- **CWE:** CWE-787
- **Risk score:** 86
- **EPSS 26.2% (2025-03-17) → 51.5% (2025-12-21), Δ +25.3%**

> A memory corruption vulnerability exists in the Windows Server DHCP service when an attacker sends specially crafted packets to a DHCP failover server, aka 'Windows DHCP Server Remote Code Execution Vulnerability'.

### CVE-1999-1576
**adobe acrobat_reader Buffer Overflow**
- **Signals:** EPSS
- **Asset:** adobe acrobat_reader
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 25.9% (2025-03-30) → 44.7% (2025-12-21), Δ +18.7%**

> Buffer overflow in Adobe Acrobat ActiveX control (pdf.ocx, PDF.PdfCtrl.1) 1.3.188 for Acrobat Reader 4.0 allows remote attackers to execute arbitrary code via the pdf.setview method.

### CVE-2007-6432
**adobe pagemaker Buffer Overflow**
- **Signals:** EPSS
- **Asset:** adobe pagemaker
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 22.5% (2025-03-30) → 34.9% (2025-12-21), Δ +12.4%**

> Stack-based buffer overflow in AldFs32.dll in Adobe PageMaker 7.0.1 and 7.0.2 allows user-assisted remote attackers to execute arbitrary code via a malformed .PMD file, related to "Key Strings," a different vulnerability than CVE-2007-5169 and CVE-2007-5394.

### CVE-1999-1581
**microsoft windows_nt DoS**
- **Signals:** EPSS
- **Asset:** microsoft windows_nt
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 16.5% (2025-03-30) → 29.4% (2025-12-21), Δ +12.9%**

> Memory leak in Simple Network Management Protocol (SNMP) agent (snmp.exe) for Windows NT 4.0 before Service Pack 4 allows remote attackers to cause a denial of service (memory consumption) via a large number of SNMP packets with Object Identifiers (OIDs) that cannot be decoded.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-21*
