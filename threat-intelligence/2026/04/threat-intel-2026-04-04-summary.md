# Daily Threat Intelligence — April 04, 2026

**Digest window (UTC):** 2026-04-04
**Generated:** 2026-06-02T07:34:50Z

## Threat brief

Jzip — exploitation likelihood rose sharply (EPSS 14% → 28% · rising (+13%)). · 3 new critical disclosures — review patch status on exposed services.

## Executive summary

- Jzip — exploitation likelihood rose sharply (EPSS 14% → 28% · rising (+13%)).
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

### CVE-2010-5300
**jzip jzip Buffer Overflow**
- **Signals:** EPSS
- **Asset:** jzip jzip
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 81
- **EPSS 14.5% (2026-01-25) → 27.8% (2026-04-04), Δ +13.3%**

> Stack-based buffer overflow in Jzip 1.3 through 2.0.0.132900 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a long file name in a zip archive.

### CVE-2024-5651
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 82
- **EPSS 17.6% (2026-01-01) → 28.6% (2026-04-04), Δ +11.0%**

> A flaw was found in the Fence Agents Remediation operator. This vulnerability can allow a Remote Code Execution (RCE) primitive by supplying an arbitrary command to execute in the --ssh-path/--telnet-path arguments. A low-privilege user, for example, a user with developer access,…

### CVE-2026-35616
**Fortinet FortiClient EMS Improper Access Control Vulnerability**
- **Signals:** CVSS
- **Asset:** fortinet forticlientems
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T18:12:57.863
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-04)

> A improper access control vulnerability in Fortinet FortiClientEMS 7.4.5 through 7.4.6 may allow an unauthenticated attacker to execute unauthorized code or commands via crafted requests.

### CVE-2004-1848
**ipswitch ws_ftp_server DoS**
- **Signals:** EPSS
- **Asset:** ipswitch ws_ftp_server
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-399
- **Risk score:** 76
- **EPSS 3.4% (2025-06-08) → 13.5% (2026-04-04), Δ +10.2%**

> Ipswitch WS_FTP Server 4.0.2 allows remote attackers to cause a denial of service (disk consumption) and bypass file size restrictions via a REST command with a large size argument, followed by a STOR of a smaller file.

### CVE-2016-20052
**snewscms snews RCE**
- **Signals:** CVSS
- **Asset:** snewscms snews
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T19:05:45.853
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-04)

> Snews CMS 1.7 contains an unrestricted file upload vulnerability that allows unauthenticated attackers to upload arbitrary files including PHP executables to the snews_files directory. Attackers can upload malicious PHP files through the multipart form-data upload endpoint and ex…

### CVE-2018-25254
**nico-ftp_project nico-ftp Buffer Overflow**
- **Signals:** CVSS
- **Asset:** nico-ftp_project nico-ftp
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T13:26:40.773
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-04)

> NICO-FTP 3.0.1.19 contains a structured exception handler buffer overflow vulnerability that allows remote attackers to execute arbitrary code by sending crafted FTP commands. Attackers can connect to the FTP service and send oversized data in response handlers to overwrite SEH p…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-04*
