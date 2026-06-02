# Daily Threat Intelligence — November 04, 2025

**Digest window (UTC):** 2025-11-04
**Generated:** 2026-06-02T07:33:43Z

## Threat brief

Gladinet CentreStack And Triofox added to CISA KEV — confirmed in-the-wild exploitation. · WordPress plugin RCE/exploit activity: 4 CVEs flagged today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Gladinet CentreStack And Triofox added to CISA KEV — confirmed in-the-wild exploitation.
- WordPress plugin RCE/exploit activity: 4 CVEs flagged today.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2025-48703
**CWP Control Web Panel OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** control-webpanel webpanel
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T14:07:33.610
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2025-11-04

> CWP (aka Control Web Panel or CentOS Web Panel) before 0.9.8.1205 allows unauthenticated remote code execution via shell metacharacters in the t_total parameter in a filemanager changePerm request. A valid non-root username must be known.

### CVE-2025-54863
**radiometrics vizair**
- **Signals:** CVSS
- **Asset:** radiometrics vizair
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-12T14:13:17.967
- **CWE:** CWE-522
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-04)

> Radiometrics VizAir is vulnerable to exposure of the system's REST API key through a publicly accessible configuration file. This allows attackers to remotely alter weather data and configurations, automate attacks against multiple instances, and extract sensitive meteorological …

### CVE-2025-61945
**radiometrics vizair**
- **Signals:** CVSS
- **Asset:** radiometrics vizair
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-12T13:43:42.207
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-04)

> Radiometrics VizAir is vulnerable to any remote attacker via access to the admin panel of the VizAir system without authentication. Once inside, the attacker can modify critical weather parameters such as wind shear alerts, inversion depth, and CAPE values, which are essential fo…

### CVE-2025-11007
**The CE21 Suite plugin for WordPress is vulnerable to unauthorized plugin settings update due to a missing capability check on the wp_ajax...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-04)

> The CE21 Suite plugin for WordPress is vulnerable to unauthorized plugin settings update due to a missing capability check on the wp_ajax_nopriv_ce21_single_sign_on_save_api_settings AJAX action in versions 2.2.1 to 2.3.1. This makes it possible for unauthenticated attackers to u…

### CVE-2025-11008
**The CE21 Suite plugin for WordPress is vulnerable to Sensitive Information Exposure in all versions up to, and including, 2.3.1 via the l...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-532
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-04)

> The CE21 Suite plugin for WordPress is vulnerable to Sensitive Information Exposure in all versions up to, and including, 2.3.1 via the log file. This makes it possible for unauthenticated attackers to extract sensitive data including authentication credentials, which can be used…

### CVE-2025-11371
**Gladinet CentreStack and Triofox Files or Directories Accessible to External Parties Vulnerability**
- **Signals:** KEV
- **Asset:** gladinet centrestack
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T14:32:00.610
- **CWE:** CWE-552
- **Risk score:** 88
- **KEV:** added 2025-11-04

> In the default installation and configuration of Gladinet CentreStack and TrioFox, there is an unauthenticated Local File Inclusion Flaw that allows unintended disclosure of system files. Exploitation of this vulnerability has been observed in the wild. 

This issue impacts Gladi…

### CVE-2025-12108
**The Survision LPR Camera system does not enforce password protection by default.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-04)

> The Survision LPR Camera system does not enforce password protection by default. This allows access to the configuration wizard immediately without a login prompt or credentials check.

### CVE-2025-12158
**The Simple User Capabilities plugin for WordPress is vulnerable to Privilege Escalation due to a missing capability check on the suc_subm...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-04)

> The Simple User Capabilities plugin for WordPress is vulnerable to Privilege Escalation due to a missing capability check on the suc_submit_capabilities() function in all versions up to, and including, 1.0. This makes it possible for unauthenticated attackers to elevate the role …

### CVE-2025-12493
**hasthemes shoplentor**
- **Signals:** CVSS
- **Asset:** hasthemes shoplentor
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-26T14:41:39.887
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-04)

> The ShopLentor – WooCommerce Builder for Elementor & Gutenberg +21 Modules – All in One Solution (formerly WooLentor) plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 3.2.5 via the 'load_template' function. This makes it possible fo…

### CVE-2025-12682
**The Easy Upload Files During Checkout plugin for WordPress is vulnerable to arbitrary JavaScript file uploads due to missing file type va...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-04)

> The Easy Upload Files During Checkout plugin for WordPress is vulnerable to arbitrary JavaScript file uploads due to missing file type validation in the 'file_during_checkout' function in all versions up to, and including, 2.9.8. This makes it possible for unauthenticated attacke…

### CVE-2025-52910
**samsung exynos_1280_firmware Privilege Escalation**
- **Signals:** CVSS
- **Asset:** samsung exynos_1280_firmware
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T13:00:22.963
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-04)

> An issue was discovered in the GPU in Samsung Mobile Processor and Wearable Processor Exynos 1280, 2200, 1330, 1380, 1480, 2400. A Use-After-Free leads to privilege escalation.

### CVE-2025-61956
**radiometrics vizair**
- **Signals:** CVSS
- **Asset:** radiometrics vizair
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-12T17:22:11.577
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-04)

> Radiometrics VizAir is vulnerable to a lack of authentication mechanisms for critical functions, such as admin access and API requests. Attackers can modify configurations without authentication, potentially manipulating active runway settings and misleading air traffic control (…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-04*
