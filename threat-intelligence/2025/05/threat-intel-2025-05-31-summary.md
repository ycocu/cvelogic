# Daily Threat Intelligence — May 31, 2025

**Digest window (UTC):** 2025-05-31
**Generated:** 2026-06-02T07:32:48Z

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

### CVE-2025-4607
**The PSW Front-end Login & Registration plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-330
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-31)

> The PSW Front-end Login & Registration plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.12 via the customer_registration() function. This is due to the use of a weak, low-entropy OTP mechanism in the forget() function. This makes …

### CVE-2025-4631
**The Profitori plugin for WordPress is vulnerable to Privilege Escalation due to a missing capability check on the stocktend_object endpoi...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-31)

> The Profitori plugin for WordPress is vulnerable to Privilege Escalation due to a missing capability check on the stocktend_object endpoint in versions 2.0.6.0 to 2.1.1.3. This makes it possible to trigger the save_object_as_user() function for objects whose '_datatype' is set to…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-31*
