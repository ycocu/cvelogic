# Daily Threat Intelligence — June 07, 2026

**Digest window (UTC):** 2026-06-07
**Generated:** 2026-06-09T12:39:21Z

## Threat brief

Foscam Fi8620 Firmware — exploitation likelihood rose sharply (EPSS 31% → 53% · rising (+22%)).

## Executive summary

- Foscam Fi8620 Firmware — exploitation likelihood rose sharply (EPSS 31% → 53% · rising (+22%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 7 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2013-2574
**foscam fi8620_firmware**
- **Signals:** EPSS
- **Asset:** foscam fi8620_firmware
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T01:51:58.920
- **CWE:** CWE-863
- **Risk score:** 82
- **EPSS 30.5% (2025-03-30) → 52.6% (2026-06-07), Δ +22.0%**

> An Access vulnerability exists in FOSCAM IP Camera FI8620 due to insufficient access restrictions in the /tmpfs/ and /log/ directories, which could let a malicious user obtain sensitive information.

### CVE-2012-10039
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 47.8% (2026-04-27) → 67.2% (2026-06-07), Δ +19.3%**

> ZEN Load Balancer versions 2.0 and 3.0-rc1 contain a command injection vulnerability in content2-2.cgi. The filelog parameter is passed directly into a backtick-delimited exec() call without sanitation. An authenticated attacker can inject arbitrary shell commands, resulting in r…

### CVE-2012-10040
**Command Injection · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 56.3% (2026-04-27) → 73.3% (2026-06-07), Δ +17.0%**

> Openfiler v2.x contains a command injection vulnerability in the system.html page. The device parameter is used to instantiate a NetworkCard object, whose constructor in network.inc calls exec() with unsanitized input. An authenticated attacker can exploit this to execute arbitra…

### CVE-2012-10037
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 62.6% (2026-01-08) → 75.1% (2026-06-07), Δ +12.6%**

> PhpTax version 0.8 contains a remote code execution vulnerability in drawimage.php. The pfilez GET parameter is unsafely passed to the exec() function without sanitization. A remote attacker can inject arbitrary shell commands, leading to code execution under the web server's con…

### CVE-2015-4748
**oracle jdk**
- **Signals:** EPSS
- **Asset:** oracle jrockit
- **CVSS max:** 7.6
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 82
- **EPSS 7.8% (2026-05-13) → 24.2% (2026-06-07), Δ +16.4%**

> Unspecified vulnerability in Oracle Java SE 6u95, 7u80, and 8u45; JRockit R28.3.6; and Java SE Embedded 7u75 and Embedded 8u33 allows remote attackers to affect confidentiality, integrity, and availability via unknown vectors related to Security.

### CVE-2021-36958
**microsoft windows RCE**
- **Signals:** EPSS
- **Asset:** microsoft windows
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-02-24T18:20:47.393
- **Risk score:** 82
- **EPSS 8.3% (2026-05-12) → 19.9% (2026-06-07), Δ +11.7%**

> <p>A remote code execution vulnerability exists when the Windows Print Spooler service improperly performs privileged file operations. An attacker who successfully exploited this vulnerability could run arbitrary code with SYSTEM privileges. An attacker could then install program…

### CVE-2022-37451
**exim exim**
- **Signals:** EPSS
- **Asset:** exim exim
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:15:00.393
- **CWE:** CWE-763
- **Risk score:** 82
- **EPSS 6.7% (2026-05-28) → 19.3% (2026-06-07), Δ +12.6%**

> Exim before 4.96 has an invalid free in pam_converse in auths/call_pam.c because store_free is not used after store_malloc.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-07*
