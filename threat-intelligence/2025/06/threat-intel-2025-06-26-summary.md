# Daily Threat Intelligence — June 26, 2025

**Digest window (UTC):** 2025-06-26
**Generated:** 2026-06-02T07:32:57Z

## Threat brief

Freesshd: public exploit or PoC linked (DoS) · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Freesshd: public exploit or PoC linked (DoS)
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 8 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2019-9978
**WordPress Social Warfare Plugin Cross-Site Scripting (XSS) Vulnerability**
- **Signals:** EXP
- **Asset:** warfareplugins social_warfare
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T19:33:51.637
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-06-26

> The social-warfare plugin before 3.5.3 for WordPress has stored XSS via the wp-admin/admin-post.php?swp_debug=load_options swp_url parameter, as exploited in the wild in March 2019. This affects Social Warfare and Social Warfare Pro.

### CVE-2024-0723
**freesshd freesshd DoS**
- **Signals:** EXP
- **Asset:** freesshd freesshd
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:47:13.300
- **CWE:** CWE-404
- **Risk score:** 78
- **EXP:** ref published 2025-06-26

> A vulnerability was found in freeSSHd 1.0.9 on Windows. It has been classified as problematic. This affects an unknown part. The manipulation leads to denial of service. It is possible to initiate the attack remotely. The exploit has been disclosed to the public and may be used. …

### CVE-2025-34046
**An unauthenticated file upload vulnerability exists in the Fanwei E-Office <= v9.4 web management interface.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-26)

> An unauthenticated file upload vulnerability exists in the Fanwei E-Office <= v9.4 web management interface. The vulnerability affects the /general/index/UploadFile.php endpoint, which improperly validates uploaded files when invoked with certain parameters (uploadType=eoffice_lo…

### CVE-2014-0468
**fusionforge fusionforge**
- **Signals:** CVSS
- **Asset:** fusionforge fusionforge
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-06T16:34:59.133
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-26)

> Vulnerability in fusionforge in the shipped Apache configuration, where the web server may execute scripts that 
the users would have uploaded in their raw SCM repositories (SVN, Git, 
Bzr...). This issue affects fusionforge: before 5.3+20140506.

### CVE-2014-7210
**debian debian_linux privilege escalation**
- **Signals:** CVSS
- **Asset:** debian pdns
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-06T16:38:04.910
- **CWE:** CWE-276
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-26)

> pdns specific as packaged in Debian in version before 3.3.1-1 creates a too privileged MySQL user. It was discovered that the maintainer scripts of pdns-backend-mysql grant too wide database permissions for the pdns user. Other backends
are not affected.

### CVE-2015-0842
**debian yubiserver Auth Bypass**
- **Signals:** CVSS
- **Asset:** debian yubiserver
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-06T15:38:05.563
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-26)

> yubiserver before 0.6 is prone to SQL injection issues, potentially leading to an authentication bypass.

### CVE-2015-0843
**debian yubiserver Buffer Overflow**
- **Signals:** CVSS
- **Asset:** debian yubiserver
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-06T15:39:51.850
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-26)

> yubiserver before 0.6 is prone to buffer overflows due to misuse of sprintf.

### CVE-2022-1257
**mcafee agent**
- **Signals:** EXP
- **Asset:** mcafee agent
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:40:21.407
- **CWE:** CWE-922
- **CWE:** CWE-922
- **Risk score:** 78
- **EXP:** ref published 2025-06-26

> Insecure storage of sensitive information vulnerability in MA for Linux, macOS, and Windows prior to 5.7.6 allows a local user to gain access to sensitive information through storage in ma.db. The sensitive information has been moved to encrypted database files.

### CVE-2024-52928
**thebrowser arc**
- **Signals:** CVSS
- **Asset:** thebrowser arc
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-10T00:59:09.070
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-06-26)

> Arc before 1.26.1 on Windows has a bypass issue in the site settings that allows websites (with previously granted permissions) to add new permissions when the user clicks anywhere on the website.

### CVE-2024-57708
**An issue in OneTrust SDK v.6.33.0 allows a local attacker to cause a denial of service via the Object.setPrototypeOf, __proto__, and Obje...**
- **Signals:** EXP
- **Attack:** DoS
- **CVSS max:** 5.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-400
- **Risk score:** 78
- **EXP:** ref published 2025-06-26

> An issue in OneTrust SDK v.6.33.0 allows a local attacker to cause a denial of service via the Object.setPrototypeOf, __proto__, and Object.assign components. NOTE: this is disputed by the Supplier who does not agree it is a prototype pollution vulnerability.

### CVE-2025-27218
**Sitecore Experience Manager (XM) and Experience Platform (XP) 10.4 before KB1002844 allow remote code execution through insecure deserial...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 5.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-06-26

> Sitecore Experience Manager (XM) and Experience Platform (XP) 10.4 before KB1002844 allow remote code execution through insecure deserialization.

### CVE-2025-30131
**iroadau fx2_firmware privilege escalation**
- **Signals:** CVSS
- **Asset:** iroadau fx2_firmware
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T20:24:24.220
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-26)

> An issue was discovered on IROAD Dashcam FX2 devices. An unauthenticated file upload endpoint can be leveraged to execute arbitrary commands by uploading a CGI-based webshell. Once a file is uploaded, the attacker can execute commands with root privileges, gaining full control ov…

### CVE-2025-34049
**An OS command injection vulnerability exists in the OptiLink ONT1GEW GPON router firmware version V2.1.11_X101 Build 1127.190306 and earl...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-06-26)

> An OS command injection vulnerability exists in the OptiLink ONT1GEW GPON router firmware version V2.1.11_X101 Build 1127.190306 and earlier. The router’s web management interface fails to properly sanitize user input in the target_addr parameter of the formTracert and formPing a…

### CVE-2025-3699
**Missing Authentication for Critical Function vulnerability in Mitsubishi Electric Corporation G-50 all versions, G-50-W all versions, G-5...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-26)

> Missing Authentication for Critical Function vulnerability in Mitsubishi Electric Corporation G-50 all versions, G-50-W all versions, G-50A all versions, GB-50 all versions, GB-50A all versions, GB-24A all versions, G-150AD all versions, AG-150A-A all versions, AG-150A-J all vers…

### CVE-2025-47165
**microsoft 365_apps**
- **Signals:** EXP
- **Asset:** microsoft 365_apps
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-09T14:02:09.283
- **CWE:** CWE-416
- **Risk score:** 78
- **EXP:** ref published 2025-06-26

> Use after free in Microsoft Office Excel allows an unauthorized attacker to execute code locally.

### CVE-2025-49132
**Pterodactyl is a free, open-source game server management panel.**
- **Signals:** EXP
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-06-26

> Pterodactyl is a free, open-source game server management panel. Prior to version 1.11.11, using the /locales/locale.json with the locale and namespace query parameters, a malicious actor is able to execute arbitrary code without being authenticated. With the ability to execute a…

### CVE-2025-49603
**Northern.tech Mender Server before 3.7.11 and 4.x before 4.0.1 has Incorrect Access Control.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-26)

> Northern.tech Mender Server before 3.7.11 and 4.x before 4.0.1 has Incorrect Access Control.

### CVE-2025-5640
**A vulnerability was found in PX4-Autopilot 1.12.3.**
- **Signals:** EXP
- **Attack:** Buffer Overflow
- **CVSS max:** 4.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-119
- **Risk score:** 78
- **EXP:** ref published 2025-06-26

> A vulnerability was found in PX4-Autopilot 1.12.3. It has been classified as problematic. This affects the function MavlinkReceiver::handle_message_trajectory_representation_waypoints of the file mavlink_receiver.cpp of the component TRAJECTORY_REPRESENTATION_WAYPOINTS Message Ha…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-26*
