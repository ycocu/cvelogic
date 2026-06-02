# Daily Threat Intelligence — March 06, 2026

**Digest window (UTC):** 2026-03-06
**Generated:** 2026-06-02T07:34:35Z

## Threat brief

Electronic Arts Battlefield 1942 — exploitation likelihood rose sharply (EPSS 5.2% → 28% · rising (+23%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Electronic Arts Battlefield 1942 — exploitation likelihood rose sharply (EPSS 5.2% → 28% · rising (+23%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 8 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2003-1355
**electronic_arts battlefield_1942 Buffer Overflow**
- **Signals:** EPSS
- **Asset:** electronic_arts battlefield_1942
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 5.2% (2025-11-08) → 28.0% (2026-03-06), Δ +22.9%**

> Buffer overflow in the remote console (rcon) in Battlefield 1942 1.2 and 1.3 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a long user name and password.

### CVE-2003-1369
**save_it_software_pty bytecatcherftp Buffer Overflow**
- **Signals:** EPSS
- **Asset:** save_it_software_pty bytecatcherftp
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-119
- **Risk score:** 81
- **EPSS 5.2% (2025-11-11) → 25.1% (2026-03-06), Δ +19.9%**

> Buffer overflow in ByteCatcher FTP client 1.04b allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a long FTP server banner.

### CVE-2026-29789
**vitodeploy vito privilege escalation**
- **Signals:** CVSS
- **Asset:** vitodeploy vito
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T18:42:39.790
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-06)

> Vito is a self-hosted web application that helps manage servers and deploy PHP applications into production servers. Prior to version 3.20.3, a missing authorization check in workflow site-creation actions allows an authenticated attacker with workflow write access in one project…

### CVE-2003-1368
**electrasoft ftp_client Buffer Overflow**
- **Signals:** EPSS
- **Asset:** electrasoft ftp_client
- **Attack:** Buffer Overflow
- **CVSS max:** 6.4
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-119
- **Risk score:** 81
- **EPSS 4.9% (2025-11-11) → 17.6% (2026-03-06), Δ +12.7%**

> Buffer overflow in the 32bit FTP client 9.49.1 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a long FTP server banner.

### CVE-2004-1301
**xlreader xlreader Buffer Overflow**
- **Signals:** EPSS
- **Asset:** xlreader xlreader
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 86
- **EPSS 5.0% (2025-03-30) → 20.6% (2026-03-06), Δ +15.6%**

> Buffer overflow in the book_format_sql function in format.c for xlreader 0.9.0 allows remote attackers to execute arbitrary code via a crafted Excel (XLS) file.

### CVE-2007-6041
**rigs_of_rogs rigs_of_rogs Buffer Overflow**
- **Signals:** EPSS
- **Asset:** rigs_of_rogs rigs_of_rogs
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 12.6% (2026-02-04) → 24.9% (2026-03-06), Δ +12.3%**

> Buffer overflow in the Sequencer::queueMessage function in sequencer.cpp in the server in Rigs of Rods (RoR) before 0.33d SP1 allows remote attackers to cause a denial of service (daemon crash) and possibly execute arbitrary code by sending a nickname, then a vehicle name in a MS…

### CVE-2019-5917
**microsoft azure-umqtt-c DoS**
- **Signals:** EPSS
- **Asset:** microsoft azure-umqtt-c
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:45:44.577
- **Risk score:** 80
- **EPSS 20.6% (2026-02-10) → 31.2% (2026-03-06), Δ +10.6%**

> azure-umqtt-c (available through GitHub prior to 2017 October 6) allows remote attackers to cause a denial of service via unspecified vectors.

### CVE-2021-37589
**virtuasoftware cobranca SQL Injection**
- **Signals:** EPSS
- **Asset:** virtuasoftware cobranca
- **Attack:** SQL Injection
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:15:28.840
- **CWE:** CWE-89
- **Risk score:** 82
- **EPSS 63.0% (2026-01-09) → 77.7% (2026-03-06), Δ +14.7%**

> Virtua Cobranca before 12R allows SQL Injection on the login page.

### CVE-2022-37122
**carel applica**
- **Signals:** EPSS
- **Asset:** carel pcoweb_card_firmware
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:14:29.000
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 58.5% (2025-12-27) → 70.9% (2026-03-06), Δ +12.4%**

> Carel pCOWeb HVAC BACnet Gateway 2.1.0, Firmware: A2.1.0 - B2.1.0, Application Software: 2.15.4A Software v16 13020200 suffers from an unauthenticated arbitrary file disclosure vulnerability. Input passed through the 'file' GET parameter through the 'logdownload.cgi' Bash script …

### CVE-2026-2330
**An attacker may access restricted filesystem areas on the device via the CROWN REST interface due to incomplete whitelist enforcement.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-09T13:35:34.633
- **CWE:** CWE-552
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-06)

> An attacker may access restricted filesystem areas on the device via the CROWN REST interface due to incomplete whitelist enforcement. Certain directories intended for internal testing were not covered by the whitelist and are accessible without authentication. An unauthenticated…

### CVE-2026-2331
**An attacker may perform unauthenticated read and write operations on sensitive filesystem areas via the AppEngine Fileaccess over HTTP du...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-09T13:35:34.633
- **CWE:** CWE-552
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-06)

> An attacker may perform unauthenticated read and write operations on sensitive filesystem areas via the AppEngine Fileaccess over HTTP due to improper access restrictions. A critical filesystem directory was unintentionally exposed through the HTTP-based file access feature, allo…

### CVE-2026-26051
**mvm mobiliti_e-mobi.hu**
- **Signals:** CVSS
- **Asset:** mvm mobiliti_e-mobi.hu
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-05T18:59:55.843
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-06)

> WebSocket endpoints lack proper authentication mechanisms, enabling attackers to perform unauthorized station impersonation and manipulate data sent to the backend. An unauthenticated attacker can connect to the OCPP WebSocket endpoint using a known or discovered charging station…

### CVE-2026-26288
**everon api.everon.io**
- **Signals:** CVSS
- **Asset:** everon api.everon.io
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-06T14:33:58.350
- **CWE:** CWE-306
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-06)

> WebSocket endpoints lack proper authentication mechanisms, enabling attackers to perform unauthorized station impersonation and manipulate data sent to the backend. An unauthenticated attacker can connect to the OCPP WebSocket endpoint using a known or discovered charging station…

### CVE-2026-28514
**rocket.chat rocket.chat Auth Bypass**
- **Signals:** CVSS
- **Asset:** rocket.chat rocket.chat
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-18T16:10:07.460
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-06)

> Rocket.Chat is an open-source, secure, fully customizable communications platform. Prior to versions 7.8.6, 7.9.8, 7.10.7, 7.11.4, 7.12.4, 7.13.3, and 8.0.0, a critical authentication bypass vulnerability exists in Rocket.Chat's account service used in the ddp-streamer micro serv…

### CVE-2026-29183
**b3log siyuan cross-site scripting**
- **Signals:** CVSS
- **Asset:** b3log siyuan
- **Attack:** cross-site scripting
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T19:02:31.160
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-06)

> SiYuan is a personal knowledge management system. Prior to version 3.5.9, an unauthenticated reflected XSS vulnerability exists in the dynamic icon API endpoint "GET /api/icon/getDynamicIcon" when type=8, attacker-controlled content is embedded into SVG output without escaping. B…

### CVE-2026-30843
**wekan_project wekan**
- **Signals:** CVSS
- **Asset:** wekan_project wekan
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T15:49:35.097
- **CWE:** CWE-639
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-06)

> Wekan is an open source kanban tool built with Meteor. Versions 8.32 and 8.33 have a critical Insecure Direct Object Reference (IDOR) issue which could allow unauthorized users to modify custom fields across boards through its custom fields update endpoints, potentially leading t…

### CVE-2026-30844
**wekan_project wekan SSRF**
- **Signals:** CVSS
- **Asset:** wekan_project wekan
- **Attack:** SSRF
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T14:56:52.180
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-06)

> Wekan is an open source kanban tool built with Meteor. Versions 8.32 and 8.33 are vulnerable to Server-Side Request Forgery (SSRF) via attachment URL loading. During board import in Wekan, attachment URLs from user-supplied JSON data are fetched directly by the server without any…

### CVE-2026-30847
**wekan_project wekan**
- **Signals:** CVSS
- **Asset:** wekan_project wekan
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T14:22:57.470
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-06)

> Wekan is an open source kanban tool built with Meteor. In versions 8.31.0 through 8.33, the notificationUsers publication in Wekan publishes user documents with no field filtering, causing the ReactiveCache.getUsers() call to return all fields including highly sensitive data such…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-06*
