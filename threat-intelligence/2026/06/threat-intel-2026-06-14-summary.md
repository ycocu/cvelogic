# Daily Threat Intelligence — June 14, 2026

**Digest window (UTC):** 2026-06-14
**Generated:** 2026-06-15T14:09:48Z

## Threat brief

Artifex Ghostscript — exploitation likelihood rose sharply (EPSS 47% → 68% · rising (+21%)).

## Executive summary

- Artifex Ghostscript — exploitation likelihood rose sharply (EPSS 47% → 68% · rising (+21%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2016-7976
**artifex ghostscript**
- **Signals:** EPSS
- **Asset:** artifex ghostscript
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 46.8% (2026-03-15) → 68.1% (2026-06-14), Δ +21.2%**

> The PS Interpreter in Ghostscript 9.18 and 9.20 allows remote attackers to execute arbitrary code via crafted userparams.

### CVE-2020-36730
**niteothemes cmp privilege escalation**
- **Signals:** EPSS
- **Asset:** niteothemes cmp
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-08T19:17:36.903
- **CWE:** CWE-862
- **CWE:** CWE-862
- **Risk score:** 83
- **EPSS 52.1% (2026-06-08) → 69.9% (2026-06-14), Δ +17.8%**

> The CMP for WordPress is vulnerable to authorization bypass due to a missing capability check on the cmp_get_post_detail(), niteo_export_csv(), and cmp_disable_comingsoon_ajax() functions in versions up to, and including, 3.8.1. This makes it possible for unauthenticated attacker…

### CVE-2025-20124
**cisco identity_services_engine Deserialization**
- **Signals:** EPSS
- **Asset:** cisco identity_services_engine
- **Attack:** Deserialization
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-03-28T13:22:42.077
- **CWE:** CWE-502
- **Risk score:** 86
- **EPSS 9.5% (2026-05-21) → 22.5% (2026-06-14), Δ +13.0%**

> A vulnerability in an API of Cisco ISE could allow an authenticated, remote attacker to execute arbitrary commands as the root user on an affected device.

This vulnerability is due to insecure deserialization of user-supplied Java byte streams by the affected software. An atta…

### CVE-1999-0107
**apache http_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** apache http_server
- **Attack:** Buffer Overflow
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 35.6% (2026-06-10) → 51.6% (2026-06-14), Δ +16.0%**

> Buffer overflow in Apache 1.2.5 and earlier allows a remote attacker to cause a denial of service with a large number of GET requests containing a large number of / characters.

### CVE-2018-11221
**artica pandora_fms**
- **Signals:** EPSS
- **Asset:** artica pandora_fms
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:42:55.893
- **CWE:** CWE-434
- **Risk score:** 85
- **EPSS 3.8% (2026-01-31) → 16.0% (2026-06-14), Δ +12.1%**

> Unauthenticated untrusted file upload in Artica Pandora FMS through version 7.23 allows an attacker to upload an arbitrary plugin via include/ajax/update_manager.ajax in the update system.

### CVE-2019-11447
**cutephp cutenews Code Execution**
- **Signals:** EPSS
- **Asset:** cutephp cutenews
- **Attack:** Code Execution
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:21:05.840
- **CWE:** CWE-434
- **Risk score:** 84
- **EPSS 73.7% (2026-02-05) → 87.9% (2026-06-14), Δ +14.2%**

> An issue was discovered in CutePHP CuteNews 2.1.2. An attacker can infiltrate the server through the avatar upload process in the profile area via the avatar_file field to index.php?mod=main&opt=personal. There is no effective control of $imgsize in /core/modules/dashboard.php. T…

### CVE-2022-35744
**microsoft windows_10_1507 RCE**
- **Signals:** EPSS
- **Asset:** microsoft windows_10_1507
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:11:35.413
- **Risk score:** 84
- **EPSS 14.8% (2026-06-12) → 25.7% (2026-06-14), Δ +10.8%**

> Windows Point-to-Point Protocol (PPP) Remote Code Execution Vulnerability

### CVE-2024-12008
**boldgrid w3_total_cache CSRF**
- **Signals:** EPSS
- **Asset:** boldgrid w3_total_cache
- **Attack:** CSRF
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-01-16T21:30:41.017
- **CWE:** CWE-200
- **Risk score:** 79
- **EPSS 39.8% (2026-06-05) → 56.2% (2026-06-14), Δ +16.3%**

> The W3 Total Cache plugin for WordPress is vulnerable to Information Exposure in all versions up to, and including, 2.8.1 through the publicly exposed debug log file. This makes it possible for unauthenticated attackers to view potentially sensitive information in the exposed log…

### CVE-2025-45488
**linksys e5600_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** linksys e5600_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-13T20:19:15.500
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 86
- **EPSS 10.7% (2026-04-19) → 23.7% (2026-06-14), Δ +13.0%**

> Linksys E5600 v1.1.0.26 was discovered to contain a command injection vulnerability in the runtime.ddnsStatus DynDNS function via the mailex parameter.

### CVE-2025-55591
**totolink a3002r_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** totolink a3002r_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-21T14:11:06.290
- **CWE:** CWE-77
- **Risk score:** 83
- **EPSS 8.7% (2026-06-04) → 19.1% (2026-06-14), Δ +10.5%**

> TOTOLINK-A3002R v4.0.0-B20230531.1404 was discovered to contain a command injection vulnerability in the devicemac parameter in the formMapDel endpoint.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-14*
