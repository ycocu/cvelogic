# Daily Threat Intelligence — September 24, 2025

**Digest window (UTC):** 2025-09-24
**Generated:** 2026-06-02T07:33:28Z

## Threat brief

10 new critical disclosures — review patch status on exposed services.

## Executive summary

- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-21483
**qualcomm apq8017_firmware Memory Corruption**
- **Signals:** CVSS
- **Asset:** qualcomm apq8017_firmware
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-28T16:47:34.690
- **CWE:** CWE-119
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-24)

> Memory corruption when the UE receives an RTP packet from the network, during the reassembly of NALUs.

### CVE-2025-27034
**qualcomm 315_5g_iot_modem_firmware Memory Corruption**
- **Signals:** CVSS
- **Asset:** qualcomm fastconnect_6900_firmware
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-28T16:46:33.673
- **CWE:** CWE-129
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-24)

> Memory corruption while selecting the PLMN from SOR failed list.

### CVE-2025-57321
**magix-combine-ex_project magix-combine-ex DoS**
- **Signals:** CVSS
- **Asset:** magix-combine-ex_project magix-combine-ex
- **Attack:** DoS
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T13:24:09.090
- **CWE:** CWE-1321
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-24)

> A Prototype Pollution vulnerability in the util-deps.addFileDepend function of magix-combine-ex versions thru 1.2.10 allows attackers to inject properties on Object.prototype via supplying a crafted payload, causing denial of service (DoS) as the minimum consequence.

### CVE-2025-10585
**Google Chromium V8 Type Confusion Vulnerability**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T15:55:01.903
- **CWE:** CWE-843
- **CWE:** CWE-843
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-24)

> Type confusion in V8 in Google Chrome prior to 140.0.7339.185 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page. (Chromium security severity: High)

### CVE-2025-10890
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-25T15:56:42.057
- **CWE:** CWE-1300
- **CWE:** CWE-203
- **CWE:** CWE-203
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-24)

> Side-channel information leakage in V8 in Google Chrome prior to 140.0.7339.207 allowed a remote attacker to leak cross-origin data via a crafted HTML page. (Chromium security severity: High)

### CVE-2025-10894
**Malicious code was inserted into the Nx (build system) package and several related plugins.**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-506
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-09-24)

> Malicious code was inserted into the Nx (build system) package and several related plugins. The tampered package was published to the npm software registry, via a supply-chain attack. Affected versions contain code that scans the file system, collects credentials, and posts them …

### CVE-2025-52906
**totolink x6000r_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** totolink x6000r_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-14T19:45:06.873
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-24)

> Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in TOTOLINK X6000R allows OS Command Injection.This issue affects X6000R: through V9.4.0cu.1360_B20241207.

### CVE-2025-56819
**running-elephant datart**
- **Signals:** CVSS
- **Asset:** running-elephant datart
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-10T21:30:04.943
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-24)

> An issue in Datart v.1.0.0-rc.3 allows a remote attacker to execute arbitrary code via the INIT connection parameter.

### CVE-2025-57347
**tbo47 dagre-d3-es**
- **Signals:** CVSS
- **Asset:** tbo47 dagre-d3-es
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-17T14:53:19.667
- **CWE:** CWE-1321
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-24)

> A vulnerability exists in the 'dagre-d3-es' Node.js package version 7.0.9, specifically within the 'bk' module's addConflict function, which fails to properly sanitize user-supplied input during property assignment operations. This flaw allows attackers to exploit prototype pollu…

### CVE-2025-59827
**flagforge flagforge Privilege Escalation**
- **Signals:** CVSS
- **Asset:** flagforge flagforge
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-08T16:35:24.860
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-24)

> Flag Forge is a Capture The Flag (CTF) platform. In version 2.1.0, the /api/admin/assign-badge endpoint lacks proper access control, allowing any authenticated user to assign high-privilege badges (e.g., Staff) to themselves. This could lead to privilege escalation and impersonat…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-24*
