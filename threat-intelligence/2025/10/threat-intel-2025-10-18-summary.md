# Daily Threat Intelligence — October 18, 2025

**Digest window (UTC):** 2025-10-18
**Generated:** 2026-06-02T07:33:37Z

## Threat brief

WordPress plugin RCE/exploit activity: 4 CVEs flagged today. · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 4 CVEs flagged today.
- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2017-20206
**wpmudev appointments Deserialization**
- **Signals:** CVSS
- **Asset:** wpmudev appointments
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-23T17:06:57.133
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-18)

> The Appointments plugin for WordPress is vulnerable to PHP Object Injection in versions up to, and including, 2.2.1 via deserialization of untrusted input from the `wpmudev_appointments` cookie. This allows unauthenticated attackers to inject a PHP Object. Attackers were actively…

### CVE-2017-20207
**dancoulter flickr_gallery Deserialization**
- **Signals:** CVSS
- **Asset:** dancoulter flickr_gallery
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-05T19:27:18.650
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-18)

> The Flickr Gallery plugin for WordPress is vulnerable to PHP Object Injection in versions up to, and including, 1.5.2 via deserialization of untrusted input from the `pager ` parameter. This allows unauthenticated attackers to inject a PHP Object. Attackers were actively exploiti…

### CVE-2017-20208
**metagauss registrationmagic Deserialization**
- **Signals:** CVSS
- **Asset:** metagauss registrationmagic
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T22:15:11.043
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-18)

> The RegistrationMagic – Custom Registration Forms, User Registration, Payment, and User Login plugin for WordPress is vulnerable to PHP Object Injection in all versions up to 3.7.9.3 (exclusive) via deserialization of untrusted input from the is_expired_by_date() function. This m…

### CVE-2025-11391
**The PPOM – Product Addons & Custom Fields for WooCommerce plugin for WordPress is vulnerable to arbitrary file uploads due to missing fil...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-18)

> The PPOM – Product Addons & Custom Fields for WooCommerce plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the image cropper functionality in all versions up to, and including, 33.0.15. This makes it possible for unauthenticated …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-18*
