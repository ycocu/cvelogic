# Daily Threat Intelligence — January 02, 2026

**Digest window (UTC):** 2026-01-02
**Generated:** 2026-06-02T07:34:06Z

## Threat brief

Beerwin Phplinkadmin — exploitation likelihood rose sharply (EPSS 41% → 76% · rising (+35%)). · 7 new critical disclosures — review patch status on exposed services.

## Executive summary

- Beerwin Phplinkadmin — exploitation likelihood rose sharply (EPSS 41% → 76% · rising (+35%)).
- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **9** |


## CVEs

### CVE-2009-1025
**beerwin phplinkadmin**
- **Signals:** EPSS
- **Asset:** beerwin phplinkadmin
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-94
- **Risk score:** 82
- **EPSS 41.0% (2025-10-06) → 75.8% (2026-01-02), Δ +34.7%**

> PHP remote file inclusion vulnerability in linkadmin.php in Beerwin PHPLinkAdmin 1.0 allows remote attackers to execute arbitrary PHP code via a URL in the page parameter.

### CVE-2006-1470
**apple mac_os_x DoS**
- **Signals:** EPSS
- **Asset:** apple mac_os_x
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-399
- **Risk score:** 77
- **EPSS 12.9% (2025-11-07) → 24.4% (2026-01-02), Δ +11.5%**

> OpenLDAP in Apple Mac OS X 10.4 up to 10.4.6 allows remote attackers to cause a denial of service (crash) via an invalid LDAP request that triggers an assert error.

### CVE-2025-64121
**nuvationenergy nplatform Auth Bypass**
- **Signals:** CVSS
- **Asset:** nuvationenergy nplatform
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T19:58:29.730
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-02)

> Authentication Bypass Using an Alternate Path or Channel vulnerability in Nuvation Energy Multi-Stack Controller (MSC) allows Authentication Bypass.This issue affects Multi-Stack Controller (MSC): from 2.3.8 before 2.5.1.

### CVE-2025-14998
**The Branda plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 3.4.24.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-639
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-02)

> The Branda plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 3.4.24. This is due to the plugin not properly validating a user's identity prior to updating their password. This makes it possible for unauthenticate…

### CVE-2025-64119
**Auth Bypass**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-603
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-02)

> A vulnerability in Nuvation Battery Management System allows Authentication Bypass.This issue affects Battery Management System: through 2.3.9.

### CVE-2025-64120
**nuvationenergy nplatform Command Injection**
- **Signals:** CVSS
- **Asset:** nuvationenergy nplatform
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T19:58:19.450
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-02)

> Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in Nuvation Energy Multi-Stack Controller (MSC) allows OS Command Injection.This issue affects Multi-Stack Controller (MSC): from 2.3.8 before 2.5.1.

### CVE-2025-65125
**gosaliajainam online-movie-booking SQL Injection**
- **Signals:** CVSS
- **Asset:** gosaliajainam online-movie-booking
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-12T15:16:24.087
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-02)

> SQL injection in gosaliajainam/online-movie-booking 5.5 in movie_details.php allows attackers to gain sensitive information.

### CVE-2025-67268
**gpsd_project gpsd Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** gpsd_project gpsd
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-12T15:33:45.577
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-02)

> gpsd before commit dc966aa contains a heap-based out-of-bounds write vulnerability in the drivers/driver_nmea2000.c file. The hnd_129540 function, which handles NMEA2000 PGN 129540 (GNSS Satellites in View) packets, fails to validate the user-supplied satellite count against the …

### CVE-2026-21440
**AdonisJS is a TypeScript-first web framework.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-02)

> AdonisJS is a TypeScript-first web framework. A Path Traversal vulnerability in AdonisJS multipart file handling may allow a remote attacker to write arbitrary files to arbitrary locations on the server filesystem. This impacts @adonisjs/bodyparser through version 10.1.1 and 11.x…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-02*
