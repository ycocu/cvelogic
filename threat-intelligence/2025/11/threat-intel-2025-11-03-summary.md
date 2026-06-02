# Daily Threat Intelligence — November 03, 2025

**Digest window (UTC):** 2025-11-03
**Generated:** 2026-06-02T07:33:43Z

## Threat brief

8 new critical disclosures — review patch status on exposed services.

## Executive summary

- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **8** |


## CVEs

### CVE-2025-0987
**Authorization Bypass Through User-Controlled Key vulnerability in CB Project Ltd.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-639
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-11-03)

> Authorization Bypass Through User-Controlled Key vulnerability in CB Project Ltd. Co. CVLand allows Parameter Injection.This issue affects CVLand: from 2.1.0 through 20251103. NOTE: The vendor was contacted early about this disclosure but did not respond in any way.

### CVE-2025-11953
**React Native Community CLI OS Command Injection Vulnerability**
- **Signals:** CVSS
- **Asset:** react-native-community react_native_community_cli
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-06T19:43:47.703
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-03)

> The Metro Development Server, which is opened by the React Native Community CLI, binds to external interfaces by default. The server exposes an endpoint that is vulnerable to OS command injection. This allows unauthenticated network attackers to send a POST request to the server …

### CVE-2025-63451
**car-booking-system-php_project car-booking-system-php SQL Injection**
- **Signals:** CVSS
- **Asset:** car-booking-system-php_project car-booking-system-php
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T20:47:00.483
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-03)

> Car-Booking-System-PHP v.1.0 is vulnerable to SQL Injection in /carlux/sign-in.php.

### CVE-2024-13997
**nagios nagios_xi Privilege Escalation**
- **Signals:** CVSS
- **Asset:** nagios nagios_xi
- **Attack:** Privilege Escalation
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T16:24:49.683
- **CWE:** CWE-269
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-11-03)

> Nagios XI versions prior to 2024R1.1.3 contain a privilege escalation vulnerability in which an authenticated administrator could leverage the Migrate Server feature to obtain root privileges on the underlying XI host. By abusing the migration workflow, an admin-level attacker co…

### CVE-2025-12463
**An unauthenticated SQL Injection was discovered within the Geutebruck G-Cam E-Series Cameras through the `Group` parameter in the `/uapi-...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-03)

> An unauthenticated SQL Injection was discovered within the Geutebruck G-Cam E-Series Cameras through the `Group` parameter in the `/uapi-cgi/viewer/Param.cgi` script. This has been confirmed on the EFD-2130 camera running firmware version 1.12.0.19.

### CVE-2025-63452
**car-booking-system-php_project car-booking-system-php SQL Injection**
- **Signals:** CVSS
- **Asset:** car-booking-system-php_project car-booking-system-php
- **Attack:** SQL Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T20:46:42.993
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-11-03)

> Car-Booking-System-PHP v.1.0 is vulnerable to SQL Injection in /carlux/forgot-pass.php.

### CVE-2025-63453
**car-booking-system-php_project car-booking-system-php SQL Injection**
- **Signals:** CVSS
- **Asset:** car-booking-system-php_project car-booking-system-php
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T20:46:33.640
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-03)

> Car-Booking-System-PHP v.1.0 is vulnerable to SQL Injection in /carlux/contact.php.

### CVE-2025-8900
**The Doccure Core plugin for WordPress is vulnerable to privilege escalation in versions up to, and excluding, 1.5.4.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-03)

> The Doccure Core plugin for WordPress is vulnerable to privilege escalation in versions up to, and excluding, 1.5.4. This is due to the plugin allowing users who are registering new accounts to set their own role or by supplying 'user_type' field. This makes it possible for unaut…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-03*
