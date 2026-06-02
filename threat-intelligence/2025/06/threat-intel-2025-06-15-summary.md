# Daily Threat Intelligence — June 15, 2025

**Digest window (UTC):** 2025-06-15
**Generated:** 2026-06-02T07:32:53Z

## Threat brief

Microsoft Windows: public exploit or PoC linked (privilege escalation) · Synology Video Station — exploitation likelihood rose sharply (EPSS 17% → 30% · rising (+12%)).

## Executive summary

- Microsoft Windows: public exploit or PoC linked (privilege escalation)
- Synology Video Station — exploitation likelihood rose sharply (EPSS 17% → 30% · rising (+12%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 8 |
| EPSS rise | 1 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **9** |


## CVEs

### CVE-2024-28000
**litespeedtech litespeed_cache privilege escalation**
- **Signals:** EXP
- **Asset:** litespeedtech litespeed_cache
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T10:16:32.067
- **CWE:** CWE-266
- **Risk score:** 78
- **EXP:** ref published 2025-06-15

> Incorrect Privilege Assignment vulnerability in LiteSpeed Technologies LiteSpeed Cache litespeed-cache.This issue affects LiteSpeed Cache: from n/a through <= 6.3.0.1.

### CVE-2024-4577
**PHP-CGI OS Command Injection Vulnerability**
- **Signals:** EXP
- **Asset:** php php
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-03T19:23:39.437
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 78
- **EXP:** ref published 2025-06-15

> In PHP versions 8.1.* before 8.1.29, 8.2.* before 8.2.20, 8.3.* before 8.3.8, when using Apache and PHP-CGI on Windows, if the system is set up to use certain code pages, Windows may use "Best-Fit" behavior to replace characters in command line given to Win32 API functions. PHP C…

### CVE-2015-6912
**synology video_station**
- **Signals:** EPSS
- **Asset:** synology video_station
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-77
- **Risk score:** 86
- **EPSS 17.2% (2025-03-30) → 29.7% (2025-06-15), Δ +12.5%**

> Synology Video Station before 1.5-0763 allows remote attackers to execute arbitrary shell commands via shell metacharacters in the subtitle_codepage parameter to subtitle.cgi.

### CVE-2025-27751
**microsoft 365_apps**
- **Signals:** EXP
- **Asset:** microsoft 365_apps
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-09T16:57:48.960
- **CWE:** CWE-416
- **Risk score:** 78
- **EXP:** ref published 2025-06-15

> Use after free in Microsoft Office Excel allows an unauthorized attacker to execute code locally.

### CVE-2025-33073
**Microsoft Windows SMB Client Improper Access Control Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **Attack:** privilege escalation
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:12:42.667
- **CWE:** CWE-284
- **Risk score:** 78
- **EXP:** ref published 2025-06-15

> Improper access control in Windows SMB allows an authorized attacker to elevate privileges over a network.

### CVE-2025-37928
**debian debian_linux**
- **Signals:** EXP
- **Asset:** linux linux_kernel
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-10T20:32:41.360
- **Risk score:** 78
- **EXP:** ref published 2025-06-15

> In the Linux kernel, the following vulnerability has been resolved:

dm-bufio: don't schedule in atomic context

A BUG was reported as below when CONFIG_DEBUG_ATOMIC_SLEEP and
try_verify_in_tasklet are enabled.
[  129.444685][  T934] BUG: sleeping function called from invalid con…

### CVE-2025-4255
**pcman ftp_server Buffer Overflow**
- **Signals:** EXP
- **Asset:** pcman ftp_server
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-16T17:43:08.997
- **CWE:** CWE-119
- **CWE:** CWE-120
- **Risk score:** 78
- **EXP:** ref published 2025-06-15

> A vulnerability classified as critical has been found in PCMan FTP Server 2.0.7. This affects an unknown part of the component RMD Command Handler. The manipulation leads to buffer overflow. It is possible to initiate the attack remotely. The exploit has been disclosed to the pub…

### CVE-2025-46041
**anchorcms anchor_cms XSS**
- **Signals:** EXP
- **Asset:** anchorcms anchor_cms
- **Attack:** XSS
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-25T19:39:06.127
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-06-15

> A stored cross-site scripting (XSS) vulnerability in Anchor CMS v0.12.7 allows attackers to inject malicious JavaScript via the page description field in the page creation interface (/admin/pages/add).

### CVE-2025-49619
**Skyvern through 0.1.85 is vulnerable to server-side template injection (SSTI) in the Prompt field of workflow blocks such as the Navigati...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 8.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1336
- **Risk score:** 78
- **EXP:** ref published 2025-06-15

> Skyvern through 0.1.85 is vulnerable to server-side template injection (SSTI) in the Prompt field of workflow blocks such as the Navigation v2 Block. Improper sanitization of Jinja2 template input allows authenticated users to inject crafted expressions that are evaluated on the …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-15*
