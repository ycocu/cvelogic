# Daily Threat Intelligence — May 16, 2026

**Digest window (UTC):** 2026-05-16
**Generated:** 2026-06-02T07:04:02Z

## Threat brief

Ansi Up Project Ansi Up — exploitation likelihood rose sharply (EPSS 37% → 59% · rising (+22%)). · 3 new critical disclosures — review patch status on exposed services.

## Executive summary

- Ansi Up Project Ansi Up — exploitation likelihood rose sharply (EPSS 37% → 59% · rising (+22%)).
- 3 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 3 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2021-3377
**ansi_up_project ansi_up XSS**
- **Signals:** EPSS
- **Asset:** ansi_up_project ansi_up
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T22:15:50.327
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 36.9% (2026-03-03) → 59.2% (2026-05-16), Δ +22.4%**

> The npm package ansi_up converts ANSI escape codes into HTML. In ansi_up v4, ANSI escape codes can be used to create HTML hyperlinks. Due to insufficient URL sanitization, this feature is affected by a cross-site scripting (XSS) vulnerability. This issue is fixed in v5.0.0.

### CVE-2021-20150
**trendnet tew-827dru_firmware**
- **Signals:** EPSS
- **Asset:** trendnet tew-827dru_firmware
- **CVSS max:** 5.3
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:46:01.117
- **CWE:** CWE-306
- **Risk score:** 79
- **EPSS 35.2% (2026-02-11) → 56.6% (2026-05-16), Δ +21.4%**

> Trendnet AC2600 TEW-827DRU version 2.08B01 improperly discloses information via redirection from the setup wizard. Authentication can be bypassed and a user may view information as Admin by manually browsing to the setup wizard and forcing it to redirect to the desired page.

### CVE-2020-37239
**libbabl 0.1.62 contains a broken double free detection vulnerability that allows attackers to bypass memory safety checks by exploiting s...**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T20:16:36.607
- **CWE:** CWE-415
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-16)

> libbabl 0.1.62 contains a broken double free detection vulnerability that allows attackers to bypass memory safety checks by exploiting signature overwriting in freed chunks. Attackers can call babl_free() twice on the same pointer without triggering detection, as libc's malloc m…

### CVE-2015-8420
**adobe air Use-After-Free**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** Use-After-Free
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 86
- **EPSS 62.8% (2026-05-13) → 77.9% (2026-05-16), Δ +15.1%**

> Use-after-free vulnerability in Adobe Flash Player before 18.0.0.268 and 19.x and 20.x before 20.0.0.228 on Windows and OS X and before 11.2.202.554 on Linux, Adobe AIR before 20.0.0.204, Adobe AIR SDK before 20.0.0.204, and Adobe AIR SDK & Compiler before 20.0.0.204 allows attac…

### CVE-2015-8421
**adobe air Use-After-Free**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** Use-After-Free
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 86
- **EPSS 62.8% (2026-05-13) → 77.9% (2026-05-16), Δ +15.1%**

> Use-after-free vulnerability in Adobe Flash Player before 18.0.0.268 and 19.x and 20.x before 20.0.0.228 on Windows and OS X and before 11.2.202.554 on Linux, Adobe AIR before 20.0.0.204, Adobe AIR SDK before 20.0.0.204, and Adobe AIR SDK & Compiler before 20.0.0.204 allows attac…

### CVE-2015-8422
**adobe air Use-After-Free**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** Use-After-Free
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 86
- **EPSS 62.8% (2026-05-13) → 77.9% (2026-05-16), Δ +15.1%**

> Use-after-free vulnerability in Adobe Flash Player before 18.0.0.268 and 19.x and 20.x before 20.0.0.228 on Windows and OS X and before 11.2.202.554 on Linux, Adobe AIR before 20.0.0.204, Adobe AIR SDK before 20.0.0.204, and Adobe AIR SDK & Compiler before 20.0.0.204 allows attac…

### CVE-2015-8423
**adobe air Use-After-Free**
- **Signals:** EPSS
- **Asset:** adobe air_sdk
- **Attack:** Use-After-Free
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 86
- **EPSS 62.8% (2026-05-13) → 77.9% (2026-05-16), Δ +15.1%**

> Use-after-free vulnerability in Adobe Flash Player before 18.0.0.268 and 19.x and 20.x before 20.0.0.228 on Windows and OS X and before 11.2.202.554 on Linux, Adobe AIR before 20.0.0.204, Adobe AIR SDK before 20.0.0.204, and Adobe AIR SDK & Compiler before 20.0.0.204 allows attac…

### CVE-2015-8424
**adobe air Use-After-Free**
- **Signals:** EPSS
- **Asset:** adobe flash_player
- **Attack:** Use-After-Free
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 86
- **EPSS 62.8% (2026-05-13) → 77.9% (2026-05-16), Δ +15.1%**

> Use-after-free vulnerability in Adobe Flash Player before 18.0.0.268 and 19.x and 20.x before 20.0.0.228 on Windows and OS X and before 11.2.202.554 on Linux, Adobe AIR before 20.0.0.204, Adobe AIR SDK before 20.0.0.204, and Adobe AIR SDK & Compiler before 20.0.0.204 allows attac…

### CVE-2015-8425
**adobe air Use-After-Free**
- **Signals:** EPSS
- **Asset:** adobe air
- **Attack:** Use-After-Free
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 86
- **EPSS 62.8% (2026-05-13) → 77.9% (2026-05-16), Δ +15.1%**

> Use-after-free vulnerability in Adobe Flash Player before 18.0.0.268 and 19.x and 20.x before 20.0.0.228 on Windows and OS X and before 11.2.202.554 on Linux, Adobe AIR before 20.0.0.204, Adobe AIR SDK before 20.0.0.204, and Adobe AIR SDK & Compiler before 20.0.0.204 allows attac…

### CVE-2020-37228
**iDS6 DSSPro Digital Signage System 6.2 contains a CAPTCHA security bypass vulnerability that allows attackers to bypass authentication by...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-18T20:16:36.607
- **CWE:** CWE-307
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-16)

> iDS6 DSSPro Digital Signage System 6.2 contains a CAPTCHA security bypass vulnerability that allows attackers to bypass authentication by requesting the autoLoginVerifyCode object. Attackers can retrieve valid CAPTCHA codes via the login endpoint and use them to perform brute-for…

### CVE-2021-47952
**python jsonpickle 2.0.0 contains a remote code execution vulnerability that allows attackers to execute arbitrary Python commands by dese...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T14:16:25.463
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-16)

> python jsonpickle 2.0.0 contains a remote code execution vulnerability that allows attackers to execute arbitrary Python commands by deserializing malicious JSON payloads containing py/repr objects. Attackers can craft JSON strings with py/repr directives that invoke the eval fun…

### CVE-2024-43807
**jetbrains teamcity cross-site scripting**
- **Signals:** EPSS
- **Asset:** jetbrains teamcity
- **Attack:** cross-site scripting
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2024-08-19T21:09:42.313
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EPSS 25.0% (2026-01-05) → 42.6% (2026-05-16), Δ +17.7%**

> In JetBrains TeamCity before 2024.07.1 multiple stored XSS was possible on Clouds page

### CVE-2024-43810
**jetbrains teamcity cross-site scripting**
- **Signals:** EPSS
- **Asset:** jetbrains teamcity
- **Attack:** cross-site scripting
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2024-08-19T21:11:45.823
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EPSS 29.2% (2026-01-05) → 47.6% (2026-05-16), Δ +18.4%**

> In JetBrains TeamCity before 2024.07.1 reflected XSS was possible in the AWS Core plugin

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-16*
