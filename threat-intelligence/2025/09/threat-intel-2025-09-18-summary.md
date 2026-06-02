# Daily Threat Intelligence — September 18, 2025

**Digest window (UTC):** 2025-09-18
**Generated:** 2026-06-02T07:33:26Z

## Threat brief

WordPress plugin RCE/exploit activity: 3 CVEs flagged today. · Blazevideo Hdtv Player — exploitation likelihood rose sharply (EPSS 5.3% → 23% · rising (+18%)). · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 3 CVEs flagged today.
- Blazevideo Hdtv Player — exploitation likelihood rose sharply (EPSS 5.3% → 23% · rising (+18%)).
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2006-6396
**blazevideo hdtv_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** blazevideo hdtv_player
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 5.3% (2025-07-27) → 22.8% (2025-09-18), Δ +17.6%**

> Stack-based buffer overflow in BlazeVideo HDTV Player 2.1, and possibly earlier, allows remote attackers to execute arbitrary code via a long filename in a PLF playlist, a different product than CVE-2006-6199.  NOTE: it was later reported that 3.5 is also affected.

### CVE-2013-5912
**thomsonreuters velocity_analytics_vhayu_analytic_server**
- **Signals:** EPSS
- **Asset:** thomsonreuters velocity_analytics_vhayu_analytic_server
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-94
- **Risk score:** 83
- **EPSS 24.5% (2025-07-14) → 34.6% (2025-09-18), Δ +10.2%**

> VhttpdMgr in Thomson Reuters Velocity Analytics Vhayu Analytic Server 6.94 build 2995 allows remote attackers to execute arbitrary code via a URL in the fileName parameter during an importFile action.

### CVE-2025-10035
**Fortra GoAnywhere MFT Deserialization of Untrusted Data Vulnerability**
- **Signals:** CVSS
- **Asset:** fortra goanywhere_managed_file_transfer
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:44:10.740
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-18)

> A deserialization vulnerability in the License Servlet of Fortra's GoAnywhere MFT allows an actor with a validly forged license response signature to deserialize an arbitrary actor-controlled object, possibly leading to command injection.

### CVE-2024-13151
**CWE - 89 - Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in ESBI Information and Tel...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-01T13:16:27.857
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-18)

> CWE - 89 - Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in ESBI Information and Telecommunication Industry and Trade Limited Company Auto Service Software allows SQL Injection.

This issue affects Auto Service Software: before…

### CVE-2025-30519
**Dover Fueling Solutions ProGauge MagLink LX4 Devices have default root credentials that cannot be changed through standard administrative...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1391
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-18)

> Dover Fueling Solutions ProGauge MagLink LX4 Devices have default root credentials that cannot be changed through standard 
administrative means. An attacker with network access to the device can 
gain administrative access to the system.

### CVE-2025-5305
**The Password Reset with Code for WordPress REST API WordPress plugin before 0.0.17 does not use cryptographically sound algorithms to gen...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-18)

> The Password Reset with Code for WordPress REST API WordPress plugin before 0.0.17 does not use cryptographically sound algorithms to generate OTP codes, potentially leading to account takeovers.

### CVE-2025-54807
**The secret used for validating authentication tokens is hardcoded in device firmware for affected versions.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-321
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-18)

> The secret used for validating authentication tokens is hardcoded in 
device firmware for affected versions. An attacker who obtains the 
signing key can bypass authentication, gaining complete access to the 
system.

### CVE-2025-6237
**Path Traversal**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-73
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-18)

> A vulnerability in invokeai version v6.0.0a1 and below allows attackers to perform path traversal and arbitrary file deletion via the GET /api/v1/images/download/{bulk_download_item_name} endpoint. By manipulating the filename arguments, attackers can read and delete any files on…

### CVE-2025-8942
**The WP Hotel Booking WordPress plugin before 2.2.3 lacks proper server-side validation for review ratings, allowing an attacker to manipu...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-18)

> The WP Hotel Booking WordPress plugin before 2.2.3 lacks proper server-side validation for review ratings, allowing an attacker to manipulate the rating value (e.g., sending negative or out-of-range values) by intercepting and modifying requests.

### CVE-2025-9083
**ninjaforms ninja_forms**
- **Signals:** CVSS
- **Asset:** ninjaforms ninja_forms
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-23T18:59:02.377
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-18)

> The Ninja Forms  WordPress plugin before 3.11.1 unserializes user input via form field, which could allow Unauthenticated users to perform PHP Object Injection when a suitable gadget is present on the blog.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-18*
