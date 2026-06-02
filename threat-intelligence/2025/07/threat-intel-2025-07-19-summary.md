# Daily Threat Intelligence — July 19, 2025

**Digest window (UTC):** 2025-07-19
**Generated:** 2026-06-02T07:33:05Z

## Threat brief

WordPress plugin RCE/exploit activity: 6 CVEs flagged today. · 7 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 6 CVEs flagged today.
- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2012-10019
**scribu front-end_editor RCE**
- **Signals:** CVSS
- **Asset:** scribu front-end_editor
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T18:53:35.477
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-19)

> The Front End Editor plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation via the upload.php file in versions before 2.3. This makes it possible for unauthenticated attackers to upload arbitrary files on the affected sites server which …

### CVE-2015-10135
**eoxia wpshop_2 RCE**
- **Signals:** CVSS
- **Asset:** eoxia wpshop_2
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T16:49:54.610
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-19)

> The WPshop 2 – E-Commerce plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the ajaxUpload function in versions before 1.3.9.6. This makes it possible for unauthenticated attackers to upload arbitrary files on the affected sites s…

### CVE-2015-10138
**lynton_reed work_the_flow_file_upload RCE**
- **Signals:** CVSS
- **Asset:** lynton_reed work_the_flow_file_upload
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T16:01:48.673
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-19)

> The Work The Flow File Upload plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the jQuery-File-Upload-9.5.0 server and test files in versions up to, and including, 2.5.2. This makes it possible for unauthenticated attackers to up…

### CVE-2016-15043
**wp_mobile_detector_project wp_mobile_detector RCE**
- **Signals:** CVSS
- **Asset:** wp_mobile_detector_project wp_mobile_detector
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T16:36:44.470
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-19)

> The WP Mobile Detector plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in resize.php file in versions up to, and including, 3.5. This makes it possible for unauthenticated attackers to upload arbitrary files on the affected sites s…

### CVE-2025-29757
**An incorrect authorisation check in the the 'plant transfer' function of the Growatt cloud service allowed a malicous attacker with a val...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-19)

> An incorrect authorisation check in the the 'plant transfer' function of the Growatt cloud service allowed a malicous attacker with a valid account to transfer any plant into his/her account.

### CVE-2025-7696
**The Integration for Pipedrive and Contact Form 7, WPForms, Elementor, Ninja Forms plugin for WordPress is vulnerable to PHP Object Inject...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-19)

> The Integration for Pipedrive and Contact Form 7, WPForms, Elementor, Ninja Forms plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 1.2.3 via deserialization of untrusted input within the verify_field_val() function. This makes it po…

### CVE-2025-7697
**The Integration for Google Sheets and Contact Form 7, WPForms, Elementor, Ninja Forms plugin for WordPress is vulnerable to PHP Object In...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-19)

> The Integration for Google Sheets and Contact Form 7, WPForms, Elementor, Ninja Forms plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 1.1.1 via deserialization of untrusted input within the verify_field_val() function. This makes i…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-19*
