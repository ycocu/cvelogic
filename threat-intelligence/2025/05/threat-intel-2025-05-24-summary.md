# Daily Threat Intelligence — May 24, 2025

**Digest window (UTC):** 2025-05-24
**Generated:** 2026-06-02T07:32:46Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Open-emr Openemr — exploitation likelihood rose sharply (EPSS 29% → 41% · rising (+12%)). · 3 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Open-emr Openemr — exploitation likelihood rose sharply (EPSS 29% → 41% · rising (+12%)).
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

### CVE-2015-4453
**open-emr openemr**
- **Signals:** EPSS
- **Asset:** open-emr openemr
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-287
- **Risk score:** 78
- **EPSS 29.1% (2025-03-30) → 40.9% (2025-05-24), Δ +11.8%**

> interface/globals.php in OpenEMR 2.x, 3.x, and 4.x before 4.2.0 patch 2 allows remote attackers to bypass authentication and obtain sensitive information via an ignoreAuth=1 value to certain scripts, as demonstrated by (1) interface/fax/fax_dispatch_newpid.php and (2) interface/b…

### CVE-2025-5058
**emagicone emagicone_store_manager_for_woocommerce RCE**
- **Signals:** CVSS
- **Asset:** emagicone emagicone_store_manager_for_woocommerce
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-08T18:24:51.830
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-24)

> The eMagicOne Store Manager for WooCommerce plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the set_image() function in all versions up to, and including, 1.2.5. This makes it possible for unauthenticated attackers to upload arb…

### CVE-2025-5124
**A vulnerability classified as critical has been found in Sony SNC-M1, SNC-M3, SNC-RZ25N, SNC-RZ30N, SNC-DS10, SNC-CS3N and SNC-RX570N up...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-05-24)

> A vulnerability classified as critical has been found in Sony SNC-M1, SNC-M3, SNC-RZ25N, SNC-RZ30N, SNC-DS10, SNC-CS3N and SNC-RX570N up to 1.30. This affects an unknown part of the component Administrative Interface. The manipulation leads to use of default credentials. It is po…

### CVE-2025-4603
**emagicone emagicone_store_manager_for_woocommerce RCE**
- **Signals:** CVSS
- **Asset:** emagicone emagicone_store_manager_for_woocommerce
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-08T17:20:45.730
- **CWE:** CWE-73
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-24)

> The eMagicOne Store Manager for WooCommerce plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the delete_file() function in all versions up to, and including, 1.2.5. This makes it possible for unauthenticated attackers to de…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-24*
