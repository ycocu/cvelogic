# Daily Threat Intelligence — August 26, 2025

**Digest window (UTC):** 2025-08-26
**Generated:** 2026-06-02T07:33:18Z

## Threat brief

Citrix NetScaler added to CISA KEV — confirmed in-the-wild exploitation. · 51mis Lingdang Crm: public exploit or PoC linked (SQL Injection) · WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Citrix NetScaler added to CISA KEV — confirmed in-the-wild exploitation.
- 51mis Lingdang Crm: public exploit or PoC linked (SQL Injection)
- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 6 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2025-7775
**Citrix NetScaler Memory Overflow Vulnerability**
- **Signals:** KEV, CVSS
- **Asset:** citrix netscaler_application_delivery_controller
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:42:16.660
- **CWE:** CWE-119
- **Risk score:** 96
- **KEV:** added 2025-08-26
- **CVSS critical:** 9.2 (disclosed 2025-08-26)

> Memory overflow vulnerability leading to Remote Code Execution and/or Denial of Service in NetScaler ADC and NetScaler Gateway when NetScaler is configured as Gateway (VPN virtual server, ICA Proxy, CVPN, RDP Proxy) or AAA virtual server

(OR)

NetScaler ADC and NetScaler Gateway…

### CVE-2025-4427
**Ivanti Endpoint Manager Mobile (EPMM) Authentication Bypass Vulnerability**
- **Signals:** EXP
- **Asset:** ivanti endpoint_manager_mobile
- **Attack:** Auth Bypass
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:55:27.977
- **CWE:** CWE-288
- **Risk score:** 78
- **EXP:** ref published 2025-08-26

> An authentication bypass in the API component of Ivanti Endpoint Manager Mobile 12.5.0.0 and prior allows attackers to access protected resources without proper credentials via the API.

### CVE-2025-0074
**google android RCE**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-02T18:08:37.580
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-26)

> In process_service_attr_rsp of sdp_discovery.cc, there is a possible way to execute arbitrary code due to a use after free. This could lead to remote code execution with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2024-39335
**mahara mahara**
- **Signals:** CVSS
- **Asset:** mahara mahara
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-05T17:00:50.507
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-26)

> Supported versions of Mahara 24.04 before 24.04.1 and 23.04 before 23.04.6 are vulnerable to information being disclosed to an institution administrator under certain conditions via the 'Current submissions' page: Administration -> Groups -> Submissions.

### CVE-2025-0075
**google android RCE**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-02T18:08:32.940
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-26)

> In process_service_search_attr_req of sdp_server.cc, there is a possible way to execute arbitrary code due to a use after free. This could lead to remote code execution with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2025-22403
**google android RCE**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-02T18:02:01.240
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-26)

> In sdp_snd_service_search_req of sdp_discovery.cc, there is a possible way to execute arbitrary code due to a use after free. This could lead to remote code execution with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2025-22408
**google android RCE**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-02T18:01:02.413
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-26)

> In rfc_check_send_cmd of rfc_utils.cc, there is a possible way to execute arbitrary code due to a use after free. This could lead to remote code execution with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2025-26263
**GeoVision ASManager Windows desktop application with the version 6.1.2.0 or less (fixed in 6.2.0), is vulnerable to credentials disclosur...**
- **Signals:** EXP
- **CVSS max:** 5.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2025-08-26

> GeoVision ASManager Windows desktop application with the version 6.1.2.0 or less (fixed in 6.2.0), is vulnerable to credentials disclosure due to improper memory handling in the ASManagerService.exe process.

### CVE-2025-26264
**GeoVision GV-ASWeb with the version 6.1.2.0 or less (fixed in 6.2.0), contains a Remote Code Execution (RCE) vulnerability within its Not...**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-08-26

> GeoVision GV-ASWeb with the version 6.1.2.0 or less (fixed in 6.2.0), contains a Remote Code Execution (RCE) vulnerability within its Notification Settings feature. An authenticated attacker with "System Settings" privileges in ASWeb can exploit this flaw to execute arbitrary com…

### CVE-2025-35115
**atlassian agiloft**
- **Signals:** CVSS
- **Asset:** atlassian agiloft
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-02T17:57:25.583
- **CWE:** CWE-494
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-08-26)

> Agiloft Release 28 downloads critical system packages over an insecure HTTP connection. An attacker in a Man-In-the-Middle position could replace or modify the contents of the download URL. Users should upgrade to Agiloft Release 30.

### CVE-2025-52353
**uatech badaso RCE**
- **Signals:** CVSS
- **Asset:** uatech badaso
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-09T18:55:07.583
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-26)

> An arbitrary code execution vulnerability in Badaso CMS 2.9.11. The Media Manager allows authenticated users to upload files containing embedded PHP code via the file-upload endpoint, bypassing content-type validation. When such a file is accessed via its URL, the server executes…

### CVE-2025-55443
**telpo telpo_mdm**
- **Signals:** CVSS
- **Asset:** telpo telpo_mdm
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-09T18:54:53.273
- **CWE:** CWE-312
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-26)

> Telpo MDM 1.4.6 thru 1.4.9 for Android contains sensitive administrator credentials and MQTT server connection details (IP/port) that are stored in plaintext within log files on the device's external storage. This allows attackers with access to these logs to: 1. Authenticate to …

### CVE-2025-55526
**n8n fastapi Directory Traversal**
- **Signals:** CVSS
- **Asset:** n8n fastapi
- **Attack:** Directory Traversal
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-15T19:38:14.897
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-26)

> n8n-workflows Main Commit ee25413 allows attackers to execute a directory traversal via the download_workflow function within api_server.py

### CVE-2025-6082
**The Birth Chart Compatibility plugin for WordPress is vulnerable to Full Path Disclosure in all versions up to, and including, 2.0.**
- **Signals:** EXP
- **CVSS max:** 5.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2025-08-26

> The Birth Chart Compatibility plugin for WordPress is vulnerable to Full Path Disclosure in all versions up to, and including, 2.0. This is due to insufficient protection against directly accessing the plugin's index.php file, which causes an error exposing the full path. This ma…

### CVE-2025-7441
**The StoryChief plugin for WordPress is vulnerable to arbitrary file uploads in all versions up to, and including, 1.0.42.**
- **Signals:** EXP
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 78
- **EXP:** ref published 2025-08-26

> The StoryChief plugin for WordPress is vulnerable to arbitrary file uploads in all versions up to, and including, 1.0.42. This vulnerability occurs through the /wp-json/storychief/webhook REST-API endpoint that does not have sufficient filetype validation. This makes it possible …

### CVE-2025-9140
**51mis lingdang_crm SQL Injection**
- **Signals:** EXP
- **Asset:** 51mis lingdang_crm
- **Attack:** SQL Injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:00:01.613
- **CWE:** CWE-74
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-08-26

> A vulnerability was identified in Shanghai Lingdang Information Technology Lingdang CRM up to 8.6.4.7. Affected by this issue is some unknown functionality of the file /crm/crmapi/erp/tabdetail_moduleSave.php. The manipulation of the argument getvaluestring leads to sql injection…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-26*
