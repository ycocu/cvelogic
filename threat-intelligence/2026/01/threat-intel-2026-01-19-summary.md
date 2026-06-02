# Daily Threat Intelligence — January 19, 2026

**Digest window (UTC):** 2026-01-19
**Generated:** 2026-06-02T07:34:13Z

## Threat brief

Melange Chat System — exploitation likelihood rose sharply (EPSS 8.4% → 29% · rising (+20%)). · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Melange Chat System — exploitation likelihood rose sharply (EPSS 8.4% → 29% · rising (+20%)).
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2002-1351
**melange melange_chat_system Buffer Overflow**
- **Signals:** EPSS
- **Asset:** melange melange_chat_system
- **Attack:** Buffer Overflow
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 8.4% (2025-05-13) → 28.8% (2026-01-19), Δ +20.3%**

> Buffer overflow in Melange Chat System 1.10 allows remote attackers to cause a denial of service (chat server crash) and possibly execute arbitrary code via the msgText buffer in the chat_InterpretData function, as demonstrated via a long Nick (nickname) request.

### CVE-2009-3670
**ksplayer ksp_sound_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ksplayer ksp_sound_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 5.8% (2025-03-19) → 23.5% (2026-01-19), Δ +17.7%**

> Stack-based buffer overflow in KSP Sound Player 2009 R2 and R2.1 allows remote attackers to execute arbitrary code via a long string in a .m3u playlist file.

### CVE-2026-23836
**hotcrp hotcrp**
- **Signals:** CVSS
- **Asset:** hotcrp hotcrp
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T16:01:00.990
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-19)

> HotCRP is conference review software. A problem introduced in April 2024 in version 3.1 led to inadequately sanitized code generation for HotCRP formulas which allowed users to trigger the execution of arbitrary PHP code. The problem is patched in release version 3.2.

### CVE-2013-2416
**oracle jdk**
- **Signals:** EPSS
- **Asset:** oracle jre
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **Risk score:** 76
- **EPSS 26.7% (2025-10-01) → 37.6% (2026-01-19), Δ +10.9%**

> Unspecified vulnerability in the Java Runtime Environment (JRE) component in Oracle Java SE 7 Update 17 and earlier allows remote attackers to affect integrity via unknown vectors related to Deployment.

### CVE-2025-11043
**An Improper Certificate Validation vulnerability in the OPC-UA client and ANSL over TLS client used in Automation Studio versions before...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-19)

> An Improper Certificate Validation vulnerability in the OPC-UA client and ANSL over TLS client used in Automation Studio versions before 6.5 could allow an unauthenticated attacker on the network to position themselves to intercept and interfere with data exchanges.

### CVE-2026-0610
**devolutions devolutions_server SQL Injection**
- **Signals:** CVSS
- **Asset:** devolutions devolutions_server
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-10T15:18:15.630
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-19)

> SQL Injection vulnerability in remote-sessions in Devolutions Server.This issue affects Devolutions Server 2025.3.1 through 2025.3.12

### CVE-2026-1181
**Altium 365 workspace endpoints were configured with an overly permissive Cross-Origin Resource Sharing (CORS) policy that allowed credent...**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-01-19)

> Altium 365 workspace endpoints were configured with an overly permissive Cross-Origin Resource Sharing (CORS) policy that allowed credentialed cross-origin requests from other Altium-controlled subdomains, including forum.live.altium.com. As a result, JavaScript executing on thos…

### CVE-2026-22797
**An issue was discovered in OpenStack keystonemiddleware 10.5 through 10.7 before 10.7.2, 10.8 and 10.9 before 10.9.1, and 10.10 through 1...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-290
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-19)

> An issue was discovered in OpenStack keystonemiddleware 10.5 through 10.7 before 10.7.2, 10.8 and 10.9 before 10.9.1, and 10.10 through 10.12 before 10.12.1. The external_oauth2_token middleware fails to sanitize incoming authentication headers before processing OAuth 2.0 tokens.…

### CVE-2026-23837
**franklioxygen mytube**
- **Signals:** CVSS
- **Asset:** franklioxygen mytube
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T13:24:34.437
- **CWE:** CWE-863
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-19)

> MyTube is a self-hosted downloader and player for several video websites. A vulnerability present in version 1.7.65 and poetntially earlier versions allows unauthenticated users to bypass the mandatory authentication check in the roleBasedAuthMiddleware. By simply not providing a…

### CVE-2026-23839
**leepeuker movary XSS**
- **Signals:** CVSS
- **Asset:** leepeuker movary
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T14:48:00.613
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-19)

> Movary is a web application to track, rate and explore your movie watch history. Due to insufficient input validation, attackers can trigger cross-site scripting payloads in versions prior to 0.70.0. The vulnerable parameter is `?categoryUpdated=`. Version 0.70.0 fixes the issue.

### CVE-2026-23840
**leepeuker movary XSS**
- **Signals:** CVSS
- **Asset:** leepeuker movary
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T14:47:15.050
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-19)

> Movary is a web application to track, rate and explore your movie watch history. Due to insufficient input validation, attackers can trigger cross-site scripting payloads in versions prior to 0.70.0. The vulnerable parameter is `?categoryDeleted=`. Version 0.70.0 fixes the issue.

### CVE-2026-23841
**leepeuker movary XSS**
- **Signals:** CVSS
- **Asset:** leepeuker movary
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T15:17:06.853
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-19)

> Movary is a web application to track, rate and explore your movie watch history. Due to insufficient input validation, attackers can trigger cross-site scripting payloads in versions prior to 0.70.0. The vulnerable parameter is `?categoryCreated=`. Version 0.70.0 fixes the issue.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-19*
