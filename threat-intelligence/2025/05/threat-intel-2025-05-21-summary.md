# Daily Threat Intelligence — May 21, 2025

**Digest window (UTC):** 2025-05-21
**Generated:** 2026-06-02T07:32:45Z

## Threat brief

Adobe Air — exploitation likelihood rose sharply (EPSS 30% → 51% · rising (+21%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Adobe Air — exploitation likelihood rose sharply (EPSS 30% → 51% · rising (+21%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2015-3107
**adobe air Use-After-Free**
- **Signals:** EPSS
- **Asset:** adobe air
- **Attack:** Use-After-Free
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-416
- **Risk score:** 86
- **EPSS 29.5% (2025-03-30) → 50.8% (2025-05-21), Δ +21.3%**

> Use-after-free vulnerability in Adobe Flash Player before 13.0.0.292 and 14.x through 18.x before 18.0.0.160 on Windows and OS X and before 11.2.202.466 on Linux, Adobe AIR before 18.0.0.144 on Windows and before 18.0.0.143 on OS X and Android, Adobe AIR SDK before 18.0.0.144 on …

### CVE-2015-1756
**microsoft windows_7 Use-After-Free**
- **Signals:** EPSS
- **Asset:** microsoft windows_7
- **Attack:** Use-After-Free
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-416
- **Risk score:** 85
- **EPSS 29.3% (2025-03-30) → 44.3% (2025-05-21), Δ +15.0%**

> Use-after-free vulnerability in Microsoft Common Controls in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allows user-assisted remote attackers to execute arbit…

### CVE-2025-34027
**The Versa Concerto SD-WAN orchestration platform is vulnerable to an authentication bypass in the Traefik reverse proxy configuration, al...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-367
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-21)

> The Versa Concerto SD-WAN orchestration platform is vulnerable to an authentication bypass in the Traefik reverse proxy configuration, allowing at attacker to access administrative endpoints. The Spack upload endpoint can be leveraged for a Time-of-Check to Time-of-Use (TOCTOU) w…

### CVE-2025-27558
**IEEE P802.11-REVme D1.1 through D7.0 allows FragAttacks against mesh networks.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-345
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-21)

> IEEE P802.11-REVme D1.1 through D7.0 allows FragAttacks against mesh networks. In mesh networks using Wi-Fi Protected Access (WPA, WPA2, or WPA3) or Wired Equivalent Privacy (WEP), an adversary can exploit this vulnerability to inject arbitrary frames towards devices that support…

### CVE-2025-34026
**Versa Concerto Improper Authentication Vulnerability**
- **Signals:** CVSS
- **Asset:** versa-networks concerto
- **Attack:** Auth Bypass
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-23T18:39:24.063
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-05-21)

> The Versa Concerto SD-WAN orchestration platform is vulnerable to an authentication bypass in the Traefik reverse proxy configuration, allowing at attacker to access administrative endpoints. The internal Actuator endpoint can be leveraged for access to heap dumps and trace logs.…

### CVE-2025-36535
**The embedded web server lacks authentication and access controls, allowing unrestricted remote access.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-21)

> The embedded web server lacks authentication and access controls, allowing unrestricted remote access. This could lead to configuration changes, operational disruption, or arbitrary code execution depending on the environment and exposed functionality.

### CVE-2025-41232
**Spring Security Aspects may not correctly locate method security annotations on private methods.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-693
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-21)

> Spring Security Aspects may not correctly locate method security annotations on private methods. This can cause an authorization bypass.

Your application may be affected by this if the following are true:

  *  You are using @EnableMethodSecurity(mode=ASPECTJ) and spring-securit…

### CVE-2025-41426
**Affected Vertiv products contain a stack based buffer overflow vulnerability.**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-21)

> Affected Vertiv products contain a stack based buffer overflow vulnerability. An attacker could exploit this vulnerability to gain code execution on the device.

### CVE-2025-44083
**dlink di-8100_firmware**
- **Signals:** CVSS
- **Asset:** dlink di-8100_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-03T13:52:39.333
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-21)

> An issue in D-Link DI-8100 16.07.26A1 allows a remote attacker to bypass administrator login authentication

### CVE-2025-4524
**The Madara – Responsive and modern WordPress theme for manga sites theme for WordPress is vulnerable to Local File Inclusion in all versi...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-29T20:16:28.633
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-21)

> The Madara – Responsive and modern WordPress theme for manga sites theme for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 2.2.2 via the 'template' parameter. This makes it possible for unauthenticated attackers to include and execute arbit…

### CVE-2025-46412
**Affected Vertiv products do not properly protect webserver functions that could allow an attacker to bypass authentication.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-21)

> Affected Vertiv products do not properly protect webserver functions that could allow an attacker to bypass authentication.

### CVE-2025-48200
**The sr_feuser_register extension through 12.4.8 for TYPO3 allows Remote Code Execution.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-21)

> The sr_feuser_register extension through 12.4.8 for TYPO3 allows Remote Code Execution.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-21*
