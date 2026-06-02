# Daily Threat Intelligence — April 21, 2026

**Digest window (UTC):** 2026-04-21
**Generated:** 2026-06-02T07:34:58Z

## Threat brief

Jetbrains Teamcity — exploitation likelihood rose sharply (EPSS 37% → 56% · rising (+19%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Jetbrains Teamcity — exploitation likelihood rose sharply (EPSS 37% → 56% · rising (+19%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 9 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **19** |


## CVEs

### CVE-2024-41825
**jetbrains teamcity cross-site scripting**
- **Signals:** EPSS
- **Asset:** jetbrains teamcity
- **Attack:** cross-site scripting
- **CVSS max:** 5.4
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T09:33:08.613
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EPSS 37.5% (2025-12-28) → 56.2% (2026-04-21), Δ +18.8%**

> In JetBrains TeamCity before 2024.07 stored XSS was possible on the Code Inspection tab

### CVE-2018-10054
**cognitect datomic RCE**
- **Signals:** EPSS
- **Asset:** cognitect datomic
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:40:43.880
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 53.3% (2026-03-04) → 71.6% (2026-04-21), Δ +18.3%**

> H2 1.4.197, as used in Datomic before 0.9.5697 and other products, allows remote code execution because CREATE ALIAS can execute arbitrary Java code. NOTE: the vendor's position is "h2 is not designed to be run outside of a secure environment."

### CVE-2026-40911
**wwbn avideo**
- **Signals:** CVSS
- **Asset:** wwbn avideo
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T15:12:57.673
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-04-21)

> WWBN AVideo is an open source video platform. In versions 29.0 and prior, the YPTSocket plugin's WebSocket server relays attacker-supplied JSON message bodies to every connected client without sanitizing the `msg` or `callback` fields. On the client side, `plugin/YPTSocket/script…

### CVE-2009-2188
**apple mac_os_x Buffer Overflow**
- **Signals:** EPSS
- **Asset:** apple mac_os_x
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 24.8% (2026-02-22) → 35.2% (2026-04-21), Δ +10.5%**

> Buffer overflow in ImageIO in Apple Mac OS X 10.5 before 10.5.8, and Safari before 4.0.3, allows remote attackers to execute arbitrary code or cause a denial of service (application crash) via an image with crafted EXIF metadata.

### CVE-2009-2193
**apple mac_os_x Buffer Overflow**
- **Signals:** EPSS
- **Asset:** apple mac_os_x
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 23.9% (2026-02-22) → 34.2% (2026-04-21), Δ +10.3%**

> Buffer overflow in the kernel in Apple Mac OS X 10.5 before 10.5.8 allows remote attackers to execute arbitrary code or cause a denial of service (system crash) via a crafted AppleTalk response packet.

### CVE-2014-7858
**d-link dnr-326_firmware**
- **Signals:** EPSS
- **Asset:** d-link dnr-326_firmware
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-287
- **Risk score:** 85
- **EPSS 1.8% (2025-06-23) → 14.0% (2026-04-21), Δ +12.2%**

> The check_login function in D-Link DNR-326 before 2.10 build 03 allows remote attackers to bypass authentication and log in by setting the username cookie parameter to an arbitrary string.

### CVE-2017-12785
**noviflow noviware Code Execution**
- **Signals:** EPSS
- **Asset:** noviflow noviware
- **Attack:** Code Execution
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 11.6% (2026-03-15) → 24.1% (2026-04-21), Δ +12.5%**

> The novish command-line interface, included in the NoviWare software distribution through NW400.2.6 and deployed on NoviSwitch devices, is prone to a buffer overflow in the "show log cli" command. This could be used by a read-only user (monitor role) to gain privileged (root) cod…

### CVE-2020-11579
**chadhaajay phpkb**
- **Signals:** EPSS
- **Asset:** chadhaajay phpkb
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:58:09.920
- **CWE:** CWE-306
- **Risk score:** 82
- **EPSS 36.7% (2025-12-28) → 51.4% (2026-04-21), Δ +14.7%**

> An issue was discovered in Chadha PHPKB 9.0 Enterprise Edition. installer/test-connection.php (part of the installation process) allows a remote unauthenticated attacker to disclose local files on hosts running PHP before 7.2.16, or on hosts where the MySQL ALLOW LOCAL DATA INFIL…

### CVE-2022-0949
**stopbadbots block_and_stop_bad_bots SQL Injection**
- **Signals:** EPSS
- **Asset:** stopbadbots block_and_stop_bad_bots
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:39:43.623
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 83
- **EPSS 51.8% (2026-03-11) → 62.5% (2026-04-21), Δ +10.6%**

> The Block Bad Bots and Stop Bad Bots Crawlers and Spiders and Anti Spam Protection WordPress plugin before 6.930 does not properly sanitise and escape the fingerprint parameter before using it in a SQL statement via the stopbadbots_grava_fingerprint AJAX action, available to unau…

### CVE-2022-28365
**reprisesoftware reprise_license_manager Info Disclosure**
- **Signals:** EPSS
- **Asset:** reprisesoftware reprise_license_manager
- **Attack:** Info Disclosure
- **CVSS max:** 5.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-04-30T21:00:47.660
- **CWE:** CWE-425
- **Risk score:** 79
- **EPSS 40.6% (2025-11-21) → 56.2% (2026-04-21), Δ +15.6%**

> Reprise License Manager 14.2 is affected by an Information Disclosure vulnerability via a GET request to /goforms/rlminfo. No authentication is required. The information disclosed is associated with software versions, process IDs, network configuration, hostname(s), system archit…

### CVE-2026-33519
**esri portal_for_arcgis privilege escalation**
- **Signals:** CVSS
- **Asset:** esri portal_for_arcgis
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-18T18:19:36.637
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-21)

> An incorrect authorization vulnerability exists in Esri Portal for ArcGIS 11.4, 11.5 and 12.0 on Windows, Linux and Kubernetes that did not correctly check permissions assigned to developer credentials.

### CVE-2026-34275
**oracle advanced_inbound_telephony**
- **Signals:** CVSS
- **Asset:** oracle advanced_inbound_telephony
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T13:09:40.663
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-21)

> Vulnerability in the Oracle Advanced Inbound Telephony product of Oracle E-Business Suite (component: Setup and Administration).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP…

### CVE-2026-34279
**oracle enterprise_manager_base_platform privilege escalation**
- **Signals:** CVSS
- **Asset:** oracle enterprise_manager_base_platform
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T16:43:19.373
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-21)

> Vulnerability in the Oracle Enterprise Manager Base Platform product of Oracle Enterprise Manager (component: Event Management).  Supported versions that are affected are 13.5 and  24.1. Easily exploitable vulnerability allows high privileged attacker with network access via HTTP…

### CVE-2026-34285
**oracle identity_manager_connector**
- **Signals:** CVSS
- **Asset:** oracle identity_manager_connector
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T12:08:08.803
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-21)

> Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: Core).   The supported version that is affected is 12.2.1.4.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTPS to compromise Oracl…

### CVE-2026-34286
**oracle identity_manager_connector**
- **Signals:** CVSS
- **Asset:** oracle identity_manager_connector
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T12:07:46.893
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-21)

> Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: Core).   The supported version that is affected is 12.2.1.4.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTPS to compromise Oracl…

### CVE-2026-34287
**oracle identity_manager_connector**
- **Signals:** CVSS
- **Asset:** oracle identity_manager_connector
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T12:07:28.307
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-21)

> Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: Core).   The supported version that is affected is 12.2.1.4.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTPS to compromise Oracl…

### CVE-2026-40906
**electric sync-service SQL Injection**
- **Signals:** CVSS
- **Asset:** electric sync-service
- **Attack:** SQL Injection
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-13T15:47:04.403
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-21)

> Electric is a Postgres sync engine. From 1.1.12 to before 1.5.0, the order_by parameter in the ElectricSQL /v1/shape API is vulnerable to error-based SQL injection, allowing any authenticated user to read, write, and destroy the full contents of the underlying PostgreSQL database…

### CVE-2026-40933
**flowiseai flowise**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T15:40:22.850
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-21)

> Flowise is a drag & drop user interface to build a customized large language model flow. Prior to 3.1.0, due to unsafe serialization of stdio commands in the MCP adapter, an authenticated attacker can add an MCP stdio server with an arbitrary command, achieving command execution.…

### CVE-2026-40946
**Oxia is a metadata store and coordination system.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-22T20:28:12.780
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-04-21)

> Oxia is a metadata store and coordination system. Prior to 0.16.2, the OIDC authentication provider unconditionally sets SkipClientIDCheck: true in the go-oidc verifier configuration, disabling the standard audience (aud) claim validation at the library level. This allows tokens …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-21*
