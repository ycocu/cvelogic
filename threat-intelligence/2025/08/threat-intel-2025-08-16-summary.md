# Daily Threat Intelligence — August 16, 2025

**Digest window (UTC):** 2025-08-16
**Generated:** 2026-06-02T07:33:14Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today.

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **2** |


## CVEs

### CVE-2025-7441
**The StoryChief plugin for WordPress is vulnerable to arbitrary file uploads in all versions up to, and including, 1.0.42.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-16)

> The StoryChief plugin for WordPress is vulnerable to arbitrary file uploads in all versions up to, and including, 1.0.42. This vulnerability occurs through the /wp-json/storychief/webhook REST-API endpoint that does not have sufficient filetype validation. This makes it possible …

### CVE-2025-8898
**The Taxi Booking Manager for Woocommerce | E-cab plugin for WordPress is vulnerable to privilege escalation via account takeover in all v...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-16)

> The Taxi Booking Manager for Woocommerce | E-cab plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 1.3.0. This is due to the plugin not properly validating a user's capabilities prior to updating a plugin setting…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-16*
