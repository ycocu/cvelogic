# Daily Threat Intelligence — October 11, 2025

**Digest window (UTC):** 2025-10-11
**Generated:** 2026-06-02T07:33:34Z

## Threat brief

WordPress plugin RCE/exploit activity: 3 CVEs flagged today. · 3 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 3 CVEs flagged today.
- 3 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 3 |
| Patch status change | 0 |
| **Total** | **3** |


## CVEs

### CVE-2025-11533
**The WP Freeio plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.2.21.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-11)

> The WP Freeio plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.2.21. This is due to the process_register() function not restricting what user roles a user can register with. This makes it possible for unauthenticated attackers to …

### CVE-2025-6553
**The Ovatheme Events Manager plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the proce...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-11)

> The Ovatheme Events Manager plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the process_checkout() function in all versions up to, and including, 1.8.5. This makes it possible for unauthenticated attackers to upload arbitrary fi…

### CVE-2025-6439
**The WooCommerce Designer Pro plugin for WordPress, used by the Pricom - Printing Company & Design Services WordPress theme, is vulnerable...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-11)

> The WooCommerce Designer Pro plugin for WordPress, used by the Pricom - Printing Company & Design Services WordPress theme, is vulnerable to arbitrary file deletion due to insufficient file path validation in the 'wcdp_save_canvas_design_ajax' function in all versions up to, and …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-11*
