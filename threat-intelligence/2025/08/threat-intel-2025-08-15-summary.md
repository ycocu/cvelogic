# Daily Threat Intelligence — August 15, 2025

**Digest window (UTC):** 2025-08-15
**Generated:** 2026-06-02T07:33:14Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Debian Linux — exploitation likelihood rose sharply (EPSS 6.0% → 18% · rising (+11%)). · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Debian Linux — exploitation likelihood rose sharply (EPSS 6.0% → 18% · rising (+11%)).
- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2004-0994
**debian debian_linux Buffer Overflow**
- **Signals:** EPSS
- **Asset:** zgv xzgv_image_viewer
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 85
- **EPSS 6.0% (2025-03-30) → 17.5% (2025-08-15), Δ +11.5%**

> Multiple integer overflows in xzgv 0.8 and earlier allow remote attackers to execute arbitrary code via images with large width and height values, which trigger a heap-based buffer overflow, as demonstrated in the read_prf_file function in readprf.c.  NOTE: CVE-2004-0994 and CVE-…

### CVE-2025-54466
**apache ofbiz RCE**
- **Signals:** CVSS
- **Asset:** apache ofbiz
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T22:16:28.177
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-15)

> Improper Control of Generation of Code ('Code Injection') vulnerability leading to a possible RCE in Apache OFBiz scrum plugin.

This issue affects Apache OFBiz: before 24.09.02 only when the scrum plugin is used.

Even unauthenticated attackers can exploit this vulnerability.


…

### CVE-2025-8995
**authenticator_login_project authenticator_login Auth Bypass**
- **Signals:** CVSS
- **Asset:** authenticator_login_project authenticator_login
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-21T19:58:03.550
- **CWE:** CWE-288
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-15)

> Authentication Bypass Using an Alternate Path or Channel vulnerability in Drupal Authenticator Login allows Authentication Bypass.This issue affects Authenticator Login: from 0.0.0 before 2.1.4.

### CVE-2025-54473
**An authenticated RCE vulnerability in Phoca Commander component 1.0.0-4.0.0 and 5.0.0-5.0.1 for Joomla was discovered.**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-08-15)

> An authenticated RCE vulnerability in Phoca Commander component 1.0.0-4.0.0 and 5.0.0-5.0.1 for Joomla was discovered. The issue allows code execution via the unzip feature.

### CVE-2025-6679
**The Bit Form builder plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in all versions up...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-15)

> The Bit Form builder plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in all versions up to, and including, 2.20.4. This makes it possible for unauthenticated attackers to upload arbitrary files on the affected site's server which m…

### CVE-2025-7778
**The Icons Factory plugin for WordPress is vulnerable to Arbitrary File Deletion due to insufficient authorization and improper path valid...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-15)

> The Icons Factory plugin for WordPress is vulnerable to Arbitrary File Deletion due to insufficient authorization and improper path validation within the delete_files() function in all versions up to, and including, 1.6.12. This makes it possible for unauthenticated attackers to …

### CVE-2025-9060
**A vulnerability has been found in the MSoft MFlash application that allows execution of arbitrary code on the server.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-15)

> A vulnerability has been found in the  MSoft MFlash

 application that allows 
execution of arbitrary code on the server. The issue occurs in the 
integration configuration functionality that is only available to 
MFlash


 administrators. The vulnerability is related to insuffic…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-15*
