# Daily Threat Intelligence — February 12, 2026

**Digest window (UTC):** 2026-02-12
**Generated:** 2026-06-02T07:34:24Z

## Threat brief

Apple Multiple Products added to CISA KEV — confirmed in-the-wild exploitation. · Gpsdrive — exploitation likelihood rose sharply (EPSS 25% → 42% · rising (+17%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apple Multiple Products added to CISA KEV — confirmed in-the-wild exploitation.
- Gpsdrive — exploitation likelihood rose sharply (EPSS 25% → 42% · rising (+17%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 4 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 5 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **19** |


## CVEs

### CVE-2024-43468
**Microsoft Configuration Manager SQL Injection Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft configuration_manager_2403
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T14:04:05.243
- **CWE:** CWE-89
- **Risk score:** 88
- **KEV:** added 2026-02-12

> Microsoft Configuration Manager Remote Code Execution Vulnerability

### CVE-2005-3523
**gpsdrive gpsdrive**
- **Signals:** EPSS
- **Asset:** gpsdrive gpsdrive
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 24.8% (2025-06-02) → 42.1% (2026-02-12), Δ +17.3%**

> Format string vulnerability in friendsd2 in GpsDrive allows remote attackers to execute arbitrary code via the dir (direction) field.

### CVE-2025-70314
**ourway webfsd Buffer Overflow**
- **Signals:** CVSS
- **Asset:** ourway webfsd
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T19:53:35.620
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-12)

> webfsd 1.21 is vulnerable to a Buffer Overflow via a crafted request. This is due to the filename variable

### CVE-2000-0669
**novell netware DoS**
- **Signals:** EPSS
- **Asset:** novell netware
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 2.2% (2025-03-30) → 16.5% (2026-02-12), Δ +14.4%**

> Novell NetWare 5.0 allows remote attackers to cause a denial of service by flooding port 40193 with random data.

### CVE-2004-2375
**1st_class_internet_solutions 1st_class_mail_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** 1st_class_internet_solutions 1st_class_mail_server
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 79
- **EPSS 10.3% (2025-03-30) → 20.4% (2026-02-12), Δ +10.1%**

> Buffer overflow in the POP3 server in 1st Class Mail Server 4.0 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via an APOP USER command with a long second parameter (digest).

### CVE-2005-2128
**microsoft windows_media_player**
- **Signals:** EPSS
- **Asset:** microsoft windows_media_player
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 38.6% (2025-11-09) → 54.5% (2026-02-12), Δ +15.9%**

> QUARTZ.DLL in Microsoft Windows Media Player 9 allows remote attackers to write a null byte to arbitrary memory via an AVI file with a crafted strn element with a modified length value.

### CVE-2019-25322
**Heatmiser Netmonitor 3.03 contains a hardcoded credentials vulnerability in the networkSetup.htm page with predictable admin login creden...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-12)

> Heatmiser Netmonitor 3.03 contains a hardcoded credentials vulnerability in the networkSetup.htm page with predictable admin login credentials. Attackers can access the device by using the hard-coded username 'admin' and password 'admin' in the hidden form input fields.

### CVE-2021-24849
**wclovers frontend_manager_for_woocommerce_along_with_bookings_subscription_listings_compatible SQL Injection**
- **Signals:** EPSS
- **Asset:** wclovers frontend_manager_for_woocommerce_along_with_bookings_subscription_listings_compatible
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:53:53.050
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 62.0% (2025-11-21) → 74.6% (2026-02-12), Δ +12.7%**

> The wcfm_ajax_controller AJAX action of the WCFM Marketplace WordPress plugin before 3.4.12, available to unauthenticated and authenticated user, does not properly sanitise multiple parameters before using them in SQL statements, leading to SQL injections

### CVE-2025-15556
**Notepad++ Download of Code Without Integrity Check Vulnerability**
- **Signals:** KEV
- **Asset:** notepad-plus-plus notepad\+\+
- **Attack:** RCE
- **CVSS max:** 7.7
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T14:03:47.787
- **CWE:** CWE-494
- **Risk score:** 88
- **KEV:** added 2026-02-12

> Notepad++ versions prior to 8.8.9, when using the WinGUp updater, contain an update integrity verification vulnerability where downloaded update metadata and installers are not cryptographically verified. An attacker able to intercept or redirect update traffic can cause the upda…

### CVE-2025-40536
**SolarWinds Web Help Desk Security Control Bypass Vulnerability**
- **Signals:** KEV
- **Asset:** solarwinds web_help_desk
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T14:03:55.790
- **CWE:** CWE-693
- **Risk score:** 88
- **KEV:** added 2026-02-12

> SolarWinds Web Help Desk was found to be susceptible to a security control bypass vulnerability that if exploited, could allow an unauthenticated attacker to gain access to certain restricted functionality.

### CVE-2026-1358
**Airleader Master versions 6.381 and prior allow for file uploads without restriction to multiple webpages running maximum privileges.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-12)

> Airleader Master versions 6.381 and prior allow for file uploads without
 restriction to multiple webpages running maximum privileges. This could
 allow an unauthenticated user to potentially obtain remote code 
execution on the server.

### CVE-2026-20700
**Apple Multiple Buffer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** apple ipados
- **Attack:** Buffer Overflow
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-25T17:39:37.227
- **CWE:** CWE-119
- **Risk score:** 88
- **KEV:** added 2026-02-12

> A memory corruption issue was addressed with improved state management. This issue is fixed in iOS 26.3 and iPadOS 26.3, macOS Tahoe 26.3, tvOS 26.3, visionOS 26.3, watchOS 26.3. An attacker with memory write capability may be able to execute arbitrary code. Apple is aware of a r…

### CVE-2026-24044
**Element Server Suite Community Edition (ESS Community) deploys a Matrix stack using the provided Helm charts and Kubernetes distribution.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-336
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-12)

> Element Server Suite Community Edition (ESS Community) deploys a Matrix stack using the provided Helm charts and Kubernetes distribution. The ESS Community Helm Chart secrets initialization hook (using matrix-tools container before 0.5.7) is using an insecure Matrix server key ge…

### CVE-2026-25227
**goauthentik authentik**
- **Signals:** CVSS
- **Asset:** goauthentik authentik
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-19T15:25:12.283
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-12)

> authentik is an open-source identity provider. From 2021.3.1 to before 2025.8.6, 2025.10.4, and 2025.12.4, when using delegated permissions, a User that has the permission Can view * Property Mapping or Can view Expression Policy is able to execute arbitrary code within the authe…

### CVE-2026-26011
**opennav nav2 Out-of-Bounds Write**
- **Signals:** CVSS
- **Asset:** opennav nav2
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T17:00:05.130
- **CWE:** CWE-122
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-12)

> navigation2 is a ROS 2 Navigation Framework and System. In 1.3.11 and earlier, a critical heap out-of-bounds write vulnerability exists in Nav2 AMCL's particle filter clustering logic. By publishing a single crafted geometry_msgs/PoseWithCovarianceStamped message with extreme cov…

### CVE-2026-26020
**agpt autogpt_platform RCE**
- **Signals:** CVSS
- **Asset:** agpt autogpt_platform
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-17T20:10:42.077
- **CWE:** CWE-285
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-12)

> AutoGPT is a platform that allows users to create, deploy, and manage continuous artificial intelligence agents that automate complex workflows. Prior to 0.6.48, an authenticated user could achieve Remote Code Execution (RCE) on the backend server by embedding a disabled block in…

### CVE-2026-26068
**jm33-m0 emp3r0r RCE**
- **Signals:** CVSS
- **Asset:** jm33-m0 emp3r0r
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-25T15:47:26.743
- **CWE:** CWE-77
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-12)

> emp3r0r is a stealth-focused C2 designed by Linux users for Linux environments. Prior to 3.21.1, untrusted agent metadata (Transport, Hostname) is accepted during check-in and later interpolated into tmux shell command strings executed via /bin/sh -c. This enables command injecti…

### CVE-2026-26069
**thecfu scraparr**
- **Signals:** CVSS
- **Asset:** thecfu scraparr
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T16:58:36.867
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-12)

> Scraparr is a Prometheus Exporter for various components of the *arr Suite. From 3.0.0-beta to before 3.0.2, when the Readarr integration was enabled, the exporter exposed the configured Readarr API key as the alias metric label value. Users were affected only if all of the follo…

### CVE-2026-26219
**newbee-mall_project newbee-mall**
- **Signals:** CVSS
- **Asset:** newbee-mall_project newbee-mall
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-25T16:40:13.200
- **CWE:** CWE-327
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-12)

> newbee-mall stores and verifies user passwords using an unsalted MD5 hashing algorithm. The implementation does not incorporate per-user salts or computational cost controls, enabling attackers who obtain password hashes through database exposure, backup leakage, or other comprom…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-12*
