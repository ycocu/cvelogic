# Daily Threat Intelligence — July 12, 2025

**Digest window (UTC):** 2025-07-12
**Generated:** 2026-06-02T07:33:02Z

## Threat brief

WordPress plugin RCE/exploit activity: 3 CVEs flagged today. · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- WordPress plugin RCE/exploit activity: 3 CVEs flagged today.
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

### CVE-2020-36847
**simplefilelist simple_file_list RCE**
- **Signals:** CVSS
- **Asset:** simplefilelist simple_file_list
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-29T20:37:27.933
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-12)

> The Simple-File-List Plugin for WordPress is vulnerable to Remote Code Execution in versions up to, and including, 4.2.2 via the rename function which can be used to rename uploaded PHP code with a png extension to use a php extension. This allows unauthenticated attackers to exe…

### CVE-2020-36849
**ait-themes csv_import_\/_export RCE**
- **Signals:** CVSS
- **Asset:** ait-themes csv_import_\/_export
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-04T16:55:06.207
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-12)

> The AIT CSV import/export plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the /wp-content/plugins/ait-csv-import-export/admin/upload-handler.php file in versions up to, and including, 3.0.3. This makes it possible for unauthoriz…

### CVE-2023-38036
**ivanti avalanche RCE**
- **Signals:** CVSS
- **Asset:** ivanti avalanche
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-17T13:45:21.650
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-12)

> A security vulnerability within Ivanti Avalanche Manager before version 6.4.1 may allow an unauthenticated attacker to create a buffer overflow that could result in service disruption or arbitrary code execution.

### CVE-2025-6058
**iqonic wpbookit RCE**
- **Signals:** CVSS
- **Asset:** iqonic wpbookit
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-16T14:57:37.827
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-12)

> The WPBookit plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the image_upload_handle() function hooked via the 'add_booking_type' route in all versions up to, and including, 1.0.4. This makes it possible for unauthenticated atta…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-12*
