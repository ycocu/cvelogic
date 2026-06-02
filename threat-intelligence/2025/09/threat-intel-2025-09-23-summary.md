# Daily Threat Intelligence — September 23, 2025

**Digest window (UTC):** 2025-09-23
**Generated:** 2026-06-02T07:33:28Z

## Threat brief

Google Chromium V8 added to CISA KEV — confirmed in-the-wild exploitation. · WordPress plugin RCE/exploit activity: 3 CVEs flagged today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Google Chromium V8 added to CISA KEV — confirmed in-the-wild exploitation.
- WordPress plugin RCE/exploit activity: 3 CVEs flagged today.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2025-10585
**Google Chromium V8 Type Confusion Vulnerability**
- **Signals:** KEV
- **Asset:** google chrome
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T15:55:01.903
- **CWE:** CWE-843
- **CWE:** CWE-843
- **Risk score:** 88
- **KEV:** added 2025-09-23

> Type confusion in V8 in Google Chrome prior to 140.0.7339.185 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page. (Chromium security severity: High)

### CVE-2025-9588
**ironmountain envision Command Injection**
- **Signals:** CVSS
- **Asset:** ironmountain envision
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-02T14:24:13.747
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-23)

> Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in Iron Mountain Archiving Services Inc. EnVision allows Command Injection.This issue affects enVision: before 250563.

### CVE-2025-9846
**Unrestricted Upload of File with Dangerous Type vulnerability in TalentSys Consulting Information Technology Industry Inc.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-23)

> Unrestricted Upload of File with Dangerous Type vulnerability in TalentSys Consulting Information Technology Industry Inc. Inka.Net allows Command Injection.This issue affects Inka.Net: before 6.7.1.

### CVE-2025-10147
**The Podlove Podcast Publisher plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'mo...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-23)

> The Podlove Podcast Publisher plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'move_as_original_file' function in all versions up to, and including, 4.2.6. This makes it possible for unauthenticated attackers to upload arbit…

### CVE-2025-10412
**The Product Options and Price Calculation Formulas for WooCommerce – Uni CPO (Premium) plugin for WordPress is vulnerable to arbitrary fi...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-23)

> The Product Options and Price Calculation Formulas for WooCommerce – Uni CPO (Premium) plugin for WordPress is vulnerable to arbitrary file uploads due to misconfigured file type validation in the 'uni_cpo_upload_file' function in all versions up to, and including, 4.9.55. This m…

### CVE-2025-26399
**SolarWinds Web Help Desk Deserialization of Untrusted Data Vulnerability**
- **Signals:** CVSS
- **Asset:** solarwinds web_help_desk
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T13:11:15.553
- **CWE:** CWE-502
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-23)

> SolarWinds Web Help Desk was found to be susceptible to an unauthenticated AjaxProxy deserialization remote code execution vulnerability that, if exploited, would allow an attacker to run commands on the host machine. This vulnerability is a patch bypass of CVE-2024-28988, which …

### CVE-2025-59545
**dnnsoftware dotnetnuke cross-site scripting**
- **Signals:** CVSS
- **Asset:** dnnsoftware dotnetnuke
- **Attack:** cross-site scripting
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-29T12:56:04.663
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-09-23)

> DNN (formerly DotNetNuke) is an open-source web content management platform (CMS) in the Microsoft ecosystem. Prior to version 10.1.0, the Prompt module allows execution of commands that can return raw HTML. Malicious input, even if sanitized for display elsewhere, can be execute…

### CVE-2025-9321
**The WPCasa plugin for WordPress is vulnerable to Code Injection in all versions up to, and including, 1.4.1.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-23)

> The WPCasa plugin for WordPress is vulnerable to Code Injection in all versions up to, and including, 1.4.1. This is due to insufficient input validation and restriction on the 'api_requests' function. This makes it possible for unauthenticated attackers to call arbitrary functio…

### CVE-2025-9962
**A buffer overflow vulnerability in Novakon P series allows attackers to gain root permission without prior authentication.This issue affe...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-23)

> A buffer overflow vulnerability in Novakon P series allows attackers to gain root permission without prior authentication.This issue affects P series: P – V2001.A.C518o2 until P-2.0.05 Build
                      2026.02.06 (commit d0f97fd9).

### CVE-2025-9963
**A path traversal vulnerability in Novakon P series allows to expose the root file system "/" and modify all files with root permissions.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-09-23)

> A path traversal vulnerability in Novakon P series allows to expose the root file system "/" and modify all files with root permissions. This way the system can also be compromized.This issue affects P series: P – V2001.A.C518o2 until P-2.0.05 Build
                      2026.02.…

### CVE-2025-9965
**Improper authentication vulnerability in Novakon P series allows unauthenticated attackers to upload and download any application from/to...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-23)

> Improper authentication vulnerability in Novakon P series allows unauthenticated attackers to upload and download any application from/to the device.This issue affects P series: P – V2001.A.C518o2 until P-2.0.05 Build
                      2026.02.06 (commit d0f97fd9).

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-23*
