# Daily Threat Intelligence — May 09, 2026

**Digest window (UTC):** 2026-05-09
**Generated:** 2026-06-02T07:03:58Z

## Threat brief

SonicWall Email Security — exploitation likelihood rose sharply (EPSS 43% → 55% · rising (+13%)). · 5 new critical disclosures — review patch status on exposed services.

## Executive summary

- SonicWall Email Security — exploitation likelihood rose sharply (EPSS 43% → 55% · rising (+13%)).
- 5 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 5 |
| Patch status change | 0 |
| **Total** | **8** |


## CVEs

### CVE-2021-20023
**SonicWall Email Security Path Traversal Vulnerability**
- **Signals:** EPSS
- **Asset:** sonicwall email_security
- **Attack:** Path Traversal
- **CVSS max:** 4.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-12T14:32:02.917
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 78
- **EPSS 42.7% (2026-03-17) → 55.4% (2026-05-09), Δ +12.7%**

> SonicWall Email Security version 10.0.9.x contains a vulnerability that allows a post-authenticated attacker to read an arbitrary file on the remote host.

### CVE-2021-20022
**SonicWall Email Security Unrestricted Upload of File Vulnerability**
- **Signals:** EPSS
- **Asset:** sonicwall email_security
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-10T19:07:07.287
- **CWE:** CWE-434
- **CWE:** CWE-434
- **Risk score:** 82
- **EPSS 20.0% (2026-02-21) → 32.6% (2026-05-09), Δ +12.6%**

> SonicWall Email Security version 10.0.9.x contains a vulnerability that allows a post-authenticated attacker to upload an arbitrary file to the remote host.

### CVE-2026-42569
**phpVMS is a PHP application to run and simulate an airline.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T14:54:50.290
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-05-09)

> phpVMS is a PHP application to run and simulate an airline. Prior to version 7.0.6, a critical vulnerability in phpVMS allowed unauthenticated access to a legacy import feature. This issue has been patched in version 7.0.6.

### CVE-2023-2256
**themeisle product_addons_\&_fields_for_woocommerce XSS**
- **Signals:** EPSS
- **Asset:** themeisle product_addons_\&_fields_for_woocommerce
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2025-01-10T18:15:18.907
- **CWE:** CWE-79
- **Risk score:** 79
- **EPSS 9.5% (2026-02-22) → 21.2% (2026-05-09), Δ +11.7%**

> The Product Addons & Fields for WooCommerce WordPress plugin before 32.0.7 does not sanitize and escape some URL parameters, leading to Reflected Cross-Site Scripting.

### CVE-2026-42560
**auth provides authentication via oauth2, direct and email.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T16:58:09.717
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-09)

> auth provides authentication via oauth2, direct and email. From versions 1.18.0 to before 1.25.2 and 2.0.0 to before 2.1.2, the Patreon OAuth provider maps every authenticated Patreon account to the same local user.ID, instead of deriving a unique ID from the Patreon account retu…

### CVE-2026-42571
**Pelican is a platform for creating data federations.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-13T15:23:57.230
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-05-09)

> Pelican is a platform for creating data federations. From versions 7.21.0 to before 7.21.5, 7.22.0 to before 7.22.3, 7.23.0 to before 7.23.3, and 7.24.0 to before 7.24.2, there is a a privilege escalation vulnerability affecting Pelican's Web User Interface (WebUI). This attack a…

### CVE-2026-42601
**archivebox archivebox RCE**
- **Signals:** CVSS
- **Asset:** archivebox archivebox
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-14T17:36:36.583
- **CWE:** CWE-88
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-09)

> ArchiveBox is an open source self-hosted web archiving system. In versions 0.8.6rc0 and prior, the /add/ endpoint (AddView in core/views.py) accepts a config JSON field that gets merged into the crawl config without validation. This config is exported as environment variables whe…

### CVE-2026-44313
**Linkwarden is a self-hosted, open-source collaborative bookmark manager to collect, organize and archive webpages.**
- **Signals:** CVSS
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-05-12T16:39:33.760
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-09)

> Linkwarden is a self-hosted, open-source collaborative bookmark manager to collect, organize and archive webpages. Prior to version 2.13.0, a Server-Side Request Forgery (SSRF) vulnerability in the fetchTitleAndHeaders function allows authenticated users to make arbitrary HTTP re…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-09*
