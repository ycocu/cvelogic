# Daily Threat Intelligence — August 23, 2025

**Digest window (UTC):** 2025-08-23
**Generated:** 2026-06-02T07:33:17Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Nuuo Nvrmini 2 — exploitation likelihood rose sharply (EPSS 20% → 38% · rising (+18%)). · 3 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Nuuo Nvrmini 2 — exploitation likelihood rose sharply (EPSS 20% → 38% · rising (+18%)).
- 3 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 3 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2016-5678
**nuuo nvrmini_2**
- **Signals:** EPSS
- **Asset:** nuuo nvrmini_2
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-798
- **Risk score:** 86
- **EPSS 19.7% (2025-03-30) → 38.2% (2025-08-23), Δ +18.5%**

> NUUO NVRmini 2 1.0.0 through 3.0.0 and NUUO NVRsolo 1.0.0 through 3.0.0 have hardcoded root credentials, which allows remote attackers to obtain administrative access via unspecified vectors.

### CVE-2025-5821
**The Case Theme User plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 1.0.3.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-23)

> The Case Theme User plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 1.0.3. This is due to the plugin not properly logging in a user with the data that was previously verified through the facebook_ajax_login_callback() function. Th…

### CVE-2025-7642
**The Simpler Checkout plugin for WordPress is vulnerable to Authentication Bypass in versions 0.7.0 to 1.1.9.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-23)

> The Simpler Checkout plugin for WordPress is vulnerable to Authentication Bypass in versions 0.7.0 to 1.1.9. This is due to the plugin not properly verifying a user's identity prior to logging them in as an admin through the simplerwc_woocommerce_order_created() function. This ma…

### CVE-2025-5352
**lunary lunary XSS**
- **Signals:** CVSS
- **Asset:** lunary lunary
- **Attack:** XSS
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-26T17:12:30.240
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-08-23)

> A critical stored Cross-Site Scripting (XSS) vulnerability exists in the Analytics component of lunary-ai/lunary versions up to 1.9.23, where the NEXT_PUBLIC_CUSTOM_SCRIPT environment variable is directly injected into the DOM using dangerouslySetInnerHTML without any sanitizatio…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-23*
