# Daily Threat Intelligence — May 02, 2026

**Digest window (UTC):** 2026-05-02
**Generated:** 2026-06-02T07:03:55Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Ninjaforms Ninja Forms — exploitation likelihood rose sharply (EPSS 24% → 45% · rising (+21%)).

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Ninjaforms Ninja Forms — exploitation likelihood rose sharply (EPSS 24% → 45% · rising (+21%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **8** |


## CVEs

### CVE-2023-37979
**ninjaforms ninja_forms XSS**
- **Signals:** EPSS
- **Asset:** ninjaforms ninja_forms
- **Attack:** XSS
- **CVSS max:** 7.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:12:37.883
- **CWE:** CWE-79
- **Risk score:** 82
- **EPSS 24.0% (2026-03-04) → 45.0% (2026-05-02), Δ +21.0%**

> Unauth. Reflected Cross-Site Scripting (XSS) vulnerability in Saturday Drive Ninja Forms Contact Form plugin <= 3.6.25 versions.

### CVE-2003-1378
**microsoft outlook**
- **Signals:** EPSS
- **Asset:** microsoft outlook
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-264
- **Risk score:** 84
- **EPSS 26.8% (2026-03-16) → 42.3% (2026-05-02), Δ +15.5%**

> Microsoft Outlook Express 6.0 and Outlook 2000, with the security zone set to Internet Zone, allows remote attackers to execute arbitrary programs via an HTML email with the CODEBASE parameter set to the program, a vulnerability similar to CAN-2002-0077.

### CVE-2026-4882
**The User Registration Advanced Fields plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T19:17:22.860
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-02)

> The User Registration Advanced Fields plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'URAF_AJAX::method_upload' function in all versions up to, and including, 1.6.20. This makes it possible for unauthenticated attackers to …

### CVE-2007-2930
**isc bind**
- **Signals:** EPSS
- **Asset:** isc bind
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 76
- **EPSS 18.2% (2026-05-01) → 29.9% (2026-05-02), Δ +11.7%**

> The (1) NSID_SHUFFLE_ONLY and (2) NSID_USE_POOL PRNG algorithms in ISC BIND 8 before 8.4.7-P1 generate predictable DNS query identifiers when sending outgoing queries such as NOTIFY messages when answering questions as a resolver, which allows remote attackers to poison DNS cache…

### CVE-2017-18377
**goahead wireless_ip_camera_wificam_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** goahead wireless_ip_camera_wificam_firmware
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:19:58.317
- **CWE:** CWE-77
- **Risk score:** 83
- **EPSS 9.2% (2026-04-28) → 19.9% (2026-05-02), Δ +10.6%**

> An issue was discovered on Wireless IP Camera (P2P) WIFICAM cameras. There is Command Injection in the set_ftp.cgi script via shell metacharacters in the pwd variable, as demonstrated by a set_ftp.cgi?svr=192.168.1.1&port=21&user=ftp URI.

### CVE-2020-24312
**filemanagerpro file_manager**
- **Signals:** EPSS
- **Asset:** filemanagerpro file_manager
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2025-03-24T14:32:35.300
- **CWE:** CWE-552
- **Risk score:** 82
- **EPSS 51.6% (2025-11-21) → 65.0% (2026-05-02), Δ +13.4%**

> mndpsingh287 WP File Manager v6.4 and lower fails to restrict external access to the fm_backups directory with a .htaccess file. This results in the ability for unauthenticated users to browse and download any site backups, which sometimes include full database backups, that the …

### CVE-2021-21514
**dell openmanage_server_administrator Path Traversal**
- **Signals:** EPSS
- **Asset:** dell openmanage_server_administrator
- **Attack:** Path Traversal
- **CVSS max:** 4.9
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:48:30.713
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 78
- **EPSS 12.8% (2026-03-03) → 28.1% (2026-05-02), Δ +15.2%**

> Dell EMC OpenManage Server Administrator (OMSA) versions 9.5 and prior contain a path traversal vulnerability. A remote user with admin privileges could potentially exploit this vulnerability to view arbitrary files on the target system by sending a specially crafted URL request.

### CVE-2026-7458
**The User Verification by PickPlugins plugin for WordPress is vulnerable to authentication bypass in all versions up to, and including, 2....**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T19:17:22.860
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-02)

> The User Verification by PickPlugins plugin for WordPress is vulnerable to authentication bypass in all versions up to, and including, 2.0.46. This is due to the use of a loose PHP comparison operator to validate OTP codes in the "user_verification_form_wrap_process_otpLogin" fun…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-02*
