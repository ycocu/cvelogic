# Daily Threat Intelligence — January 28, 2026

**Digest window (UTC):** 2026-01-28
**Generated:** 2026-06-02T07:34:18Z

## Threat brief

Adobe Enterprise Linux — exploitation likelihood rose sharply (EPSS 35% → 68% · rising (+33%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Adobe Enterprise Linux — exploitation likelihood rose sharply (EPSS 35% → 68% · rising (+33%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2017-3068
**adobe enterprise_linux RCE**
- **Signals:** EPSS
- **Asset:** adobe flash_player_desktop_runtime
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-787
- **Risk score:** 84
- **EPSS 35.1% (2025-09-22) → 68.5% (2026-01-28), Δ +33.4%**

> Adobe Flash Player versions 25.0.0.148 and earlier have an exploitable memory corruption vulnerability in the Advanced Video Coding engine. Successful exploitation could lead to arbitrary code execution.

### CVE-2014-10031
**qualcomm eudora_worldmail Buffer Overflow**
- **Signals:** EPSS
- **Asset:** qualcomm eudora_worldmail
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 9.9% (2025-11-28) → 39.4% (2026-01-28), Δ +29.5%**

> Buffer overflow in the IMAPd service in Qualcomm Eudora WorldMail 9.0.333.0 allows remote attackers to execute arbitrary code via a long string in a UID command.

### CVE-2025-57792
**explorance blue SQL Injection**
- **Signals:** CVSS
- **Asset:** explorance blue
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-05T17:01:13.710
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-28)

> Explorance Blue versions prior to 8.14.9 contain a SQL injection vulnerability caused by insufficient validation of user input in a web application endpoint. An attacker can supply crafted input that is executed as part of backend database queries. The issue is exploitable withou…

### CVE-2022-35711
**adobe coldfusion RCE**
- **Signals:** EPSS
- **Asset:** adobe coldfusion
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:11:32.000
- **CWE:** CWE-122
- **CWE:** CWE-787
- **Risk score:** 86
- **EPSS 3.0% (2026-01-13) → 21.2% (2026-01-28), Δ +18.2%**

> Adobe ColdFusion versions Update 14 (and earlier) and Update 4 (and earlier) are affected by a Heap-based Buffer Overflow vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue does not require user interaction, …

### CVE-2025-40553
**solarwinds web_help_desk RCE**
- **Signals:** CVSS
- **Asset:** solarwinds web_help_desk
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-02-26T19:30:48.297
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-28)

> SolarWinds Web Help Desk was found to be susceptible to an untrusted data deserialization vulnerability that could lead to remote code execution, which would allow an attacker to run commands on the host machine. This could be exploited without authentication.

### CVE-2025-40554
**solarwinds web_help_desk Auth Bypass**
- **Signals:** CVSS
- **Asset:** solarwinds web_help_desk
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T21:08:32.487
- **CWE:** CWE-1390
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-28)

> SolarWinds Web Help Desk was found to be susceptible to an authentication bypass vulnerability that, if exploited, could allow an attacker to invoke specific actions within Web Help Desk.

### CVE-2025-57794
**explorance blue RCE**
- **Signals:** CVSS
- **Asset:** explorance blue
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-05T16:59:21.133
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-28)

> Explorance Blue versions prior to 8.14.9 contain an authenticated unrestricted file upload vulnerability in the administrative interface. The application does not adequately restrict uploaded file types, allowing malicious files to be uploaded and executed by the server. This con…

### CVE-2025-57795
**explorance blue RCE**
- **Signals:** CVSS
- **Asset:** explorance blue
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-05T16:58:25.813
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-28)

> Explorance Blue versions prior to 8.14.13 contain an authenticated remote file download vulnerability in a web service component. In default configurations, this flaw can be leveraged to achieve remote code execution.

### CVE-2025-61140
**dchester jsonpath**
- **Signals:** CVSS
- **Asset:** dchester jsonpath
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-09T19:06:19.203
- **CWE:** CWE-1321
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-28)

> The value function in jsonpath 1.1.1 lib/index.js is vulnerable to Prototype Pollution.

### CVE-2025-69602
**altumcode 66biolinks**
- **Signals:** CVSS
- **Asset:** altumcode 66biolinks
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-09T17:24:55.173
- **CWE:** CWE-384
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-28)

> A session fixation vulnerability exists in 66biolinks v62.0.0 by AltumCode, where the application does not regenerate the session identifier after successful authentication. As a result, the same session cookie value is reused for users logging in from the same browser, allowing …

### CVE-2026-1056
**The Snow Monkey Forms plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the 'gene...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-28)

> The Snow Monkey Forms plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the 'generate_user_dirpath' function in all versions up to, and including, 12.0.3. This makes it possible for unauthenticated attackers to delete arbitr…

### CVE-2026-24685
**openproject openproject**
- **Signals:** CVSS
- **Asset:** openproject openproject
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-09T18:24:51.600
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-28)

> OpenProject is an open-source, web-based project management software. Versions prior to 16.6.6 and 17.0.2 have an arbitrary file write vulnerability in OpenProject’s repository diff download endpoint (`/projects/:project_id/repository/diff.diff`) when rendering a single revision …

### CVE-2026-24897
**erugo erugo privilege escalation**
- **Signals:** CVSS
- **Asset:** erugo erugo
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-09T15:32:42.827
- **CWE:** CWE-22
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-28)

> Erugo is a self-hosted file-sharing platform. In versions up to and including 0.2.14, an authenticated low-privileged user can upload arbitrary files to any specified location due to insufficient validation of user‑supplied paths when creating shares.
By specifying a writable pat…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-28*
