# Daily Threat Intelligence — May 31, 2026

**Digest window (UTC):** 2026-05-31
**Generated:** 2026-06-02T07:04:09Z

## Threat brief

Totolink N600r Firmware — exploitation likelihood rose sharply (EPSS 21% → 43% · rising (+22%)).

## Executive summary

- Totolink N600r Firmware — exploitation likelihood rose sharply (EPSS 21% → 43% · rising (+22%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **6** |


## CVEs

### CVE-2022-26187
**totolink n600r_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** totolink n600r_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:53:34.300
- **CWE:** CWE-77
- **Risk score:** 86
- **EPSS 21.2% (2026-05-30) → 42.8% (2026-05-31), Δ +21.6%**

> TOTOLINK N600R V4.3.0cu.7570_B20200620 was discovered to contain a command injection vulnerability via the pingCheck function.

### CVE-2025-8518
**vvveb vvveb**
- **Signals:** EPSS
- **Asset:** vvveb vvveb
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-29T01:00:01.613
- **CWE:** CWE-74
- **Risk score:** 77
- **EPSS 19.7% (2026-04-20) → 37.9% (2026-05-31), Δ +18.2%**

> A vulnerability was found in givanz Vvveb 1.0.5. It has been rated as critical. Affected by this issue is the function Save of the file admin/controller/editor/code.php of the component Code Editor. The manipulation leads to code injection. The attack may be launched remotely. Th…

### CVE-2011-3478
**symantec pcanywhere**
- **Signals:** EPSS
- **Asset:** symantec pcanywhere
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-287
- **Risk score:** 83
- **EPSS 46.9% (2026-05-14) → 57.0% (2026-05-31), Δ +10.1%**

> The host-services component in Symantec pcAnywhere 12.5.x through 12.5.3, and IT Management Suite pcAnywhere Solution 7.0 (aka 12.5.x) and 7.1 (aka 12.6.x), does not properly filter login and authentication data, which allows remote attackers to execute arbitrary code via a craft…

### CVE-2018-11652
**cirt.net nikto**
- **Signals:** EPSS
- **Asset:** cirt.net nikto
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:43:46.660
- **CWE:** CWE-1236
- **Risk score:** 85
- **EPSS 21.7% (2025-12-16) → 33.6% (2026-05-31), Δ +11.9%**

> CSV Injection vulnerability in Nikto 2.1.6 and earlier allows remote attackers to inject arbitrary OS commands via the Server field in an HTTP response header, which is directly injected into a CSV report.

### CVE-2025-2594
**wpeverest user_registration_\&_membership**
- **Signals:** EPSS
- **Asset:** wpeverest user_registration_\&_membership
- **CVSS max:** 8.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-30T18:14:15.800
- **Risk score:** 83
- **EPSS 16.3% (2026-05-11) → 28.4% (2026-05-31), Δ +12.1%**

> The User Registration & Membership WordPress plugin before 4.1.3 does not properly validate data in an AJAX action when the Membership Addon is enabled, allowing attackers to authenticate as any user, including administrators, by simply using the target account's user ID.

### CVE-2025-34028
**Commvault Command Center Path Traversal Vulnerability**
- **Signals:** EPSS
- **Asset:** commvault commvault
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T13:57:56.350
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 85
- **EPSS 49.2% (2026-05-23) → 65.3% (2026-05-31), Δ +16.1%**

> The Commvault Command Center Innovation Release allows an unauthenticated actor to upload ZIP files that represent install packages that, when expanded by the target server, are vulnerable to path traversal vulnerability that can result in Remote Code Execution via malicious JSP.…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-31*
