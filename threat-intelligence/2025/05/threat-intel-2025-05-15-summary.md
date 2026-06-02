# Daily Threat Intelligence — May 15, 2025

**Digest window (UTC):** 2025-05-15
**Generated:** 2026-06-02T07:32:43Z

## Threat brief

SAP NetWeaver added to CISA KEV — confirmed in-the-wild exploitation. · WordPress plugin RCE/exploit activity: 4 CVEs flagged today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- SAP NetWeaver added to CISA KEV — confirmed in-the-wild exploitation.
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

### CVE-2024-12987
**DrayTek Vigor Routers OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** draytek vigor300b_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T19:53:36.050
- **CWE:** CWE-77
- **Risk score:** 88
- **KEV:** added 2025-05-15

> A vulnerability, which was classified as critical, was found in DrayTek Vigor2960 and Vigor300B 1.5.1.4. Affected is an unknown function of the file /cgi-bin/mainfunction.cgi/apmcfgupload of the component Web Management Interface. The manipulation of the argument session leads to…

### CVE-2024-6159
**pnfpb push_notification_for_post_and_buddypress SQL Injection**
- **Signals:** CVSS
- **Asset:** pnfpb push_notification_for_post_and_buddypress
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-11T16:03:08.150
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-15)

> The Push Notification for Post and BuddyPress WordPress plugin before 1.9.4 does not properly sanitise and escape a parameter before using it in a SQL statement via an AJAX action available to unauthenticated users, leading to a SQL injection

### CVE-2024-6809
**quantumcloud simple_video_directory SQL Injection**
- **Signals:** CVSS
- **Asset:** quantumcloud simple_video_directory
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-05T14:21:45.653
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-15)

> The Simple Video Directory WordPress plugin before 1.4.3 does not properly sanitise and escape a parameter before using it in a SQL statement via an AJAX action available to unauthenticated users, leading to a SQL injection.

### CVE-2024-6584
**automattic jetpack_boost**
- **Signals:** CVSS
- **Asset:** automattic jetpack_boost
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-11T17:13:03.797
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-15)

> The 'wp_ajax_boost_proxy_ig' action allows administrators to make GET requests to arbitrary URLs.

### CVE-2024-8673
**urbanbase z-downloads**
- **Signals:** CVSS
- **Asset:** urbanbase z-downloads
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-28T15:42:17.150
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-15)

> The Z-Downloads WordPress plugin before 1.11.7 does not properly validate uploaded files allowing for the uploading of SVGs containing malicious JavaScript.

### CVE-2025-32002
**Improper neutralization of special elements used in an OS command ('OS Command Injection') issue exists in I-O DATA network attached hard...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-15)

> Improper neutralization of special elements used in an OS command ('OS Command Injection') issue exists in I-O DATA network attached hard disk 'HDL-T Series' firmware Ver.1.21 and earlier when 'Remote Link3 function' is enabled. If exploited, a remote unauthenticated attacker may…

### CVE-2025-42999
**SAP NetWeaver Deserialization Vulnerability**
- **Signals:** KEV
- **Asset:** sap netweaver
- **Attack:** Deserialization
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T21:58:56.343
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2025-05-15

> SAP NetWeaver Visual Composer Metadata Uploader is vulnerable when a privileged user can upload untrusted or malicious content which, when deserialized, could potentially lead to a compromise of confidentiality, integrity, and availability of the host system.

### CVE-2025-4564
**The TicketBAI Facturas para WooCommerce plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path valid...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-15)

> The TicketBAI Facturas para WooCommerce plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation via the 'delpdf' action in all versions up to, and including, 3.18. This makes it possible for unauthenticated attackers to delete arbitr…

### CVE-2025-46052
**weberp weberp SQL Injection**
- **Signals:** CVSS
- **Asset:** weberp weberp
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-12T13:19:06.093
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-15)

> An error-based SQL Injection (SQLi) vulnerability in WebERP v4.15.2 allows attackers to execute arbitrary SQL command and extract sensitive data by injecting a crafted payload into the DEL form field in a POST request to /StockCounts.php

### CVE-2025-47275
**Auth0-PHP provides the PHP SDK for Auth0 Authentication and Management APIs.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-15)

> Auth0-PHP provides the PHP SDK for Auth0 Authentication and Management APIs. Starting in version 8.0.0-BETA1 and prior to version 8.14.0, session cookies of applications using the Auth0-PHP SDK configured with CookieStore have authentication tags that can be brute forced, which m…

### CVE-2025-47788
**Atheos is a self-hosted browser-based cloud IDE.**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-05-15)

> Atheos is a self-hosted browser-based cloud IDE. Prior to v602, similar to GHSA-rgjm-6p59-537v/CVE-2025-22152, the `$target` parameter in `/controller.php` was not properly validated, which could allow an attacker to execute arbitrary files on the server via path traversal. v602 …

### CVE-2025-47928
**Spotipy is a Python library for the Spotify Web API.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-488
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-15)

> Spotipy is a Python library for the Spotify Web API. As of commit 4f5759dbfb4506c7b6280572a4db1aabc1ac778d, using `pull_request_target` on `.github/workflows/integration_tests.yml` followed by the checking out the head.sha of a forked PR can be exploited by attackers, since untru…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-15*
