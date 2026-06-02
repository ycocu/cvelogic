# Daily Threat Intelligence — November 24, 2025

**Digest window (UTC):** 2025-11-24
**Generated:** 2026-06-02T07:33:51Z

## Threat brief

Novell Iprint Client — exploitation likelihood rose sharply (EPSS 60% → 70% · rising (+11%)). · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- Novell Iprint Client — exploitation likelihood rose sharply (EPSS 60% → 70% · rising (+11%)).
- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2008-2908
**novell iprint_client Buffer Overflow**
- **Signals:** EPSS
- **Asset:** novell iprint_client
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 59.5% (2025-08-20) → 70.3% (2025-11-24), Δ +10.7%**

> Multiple stack-based buffer overflows in a certain ActiveX control in ienipp.ocx in Novell iPrint Client for Windows before 4.36 allow remote attackers to execute arbitrary code via a long value of the (1) operation, (2) printer-url, or (3) target-frame parameter.  NOTE: some of …

### CVE-2025-54347
**desktopalert pingalert_application_server Directory Traversal**
- **Signals:** CVSS
- **Asset:** desktopalert pingalert_application_server
- **Attack:** Directory Traversal
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-05T20:28:19.223
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-11-24)

> A Directory Traversal vulnerability was found in the Application Server of Desktop Alert PingAlert version 6.1.0.11 to 6.1.1.2 which allows an attacker to write arbitrary files under certain conditions.

### CVE-2024-47856
**rsa authentication_agent_for_windows**
- **Signals:** CVSS
- **Asset:** rsa authentication_agent_for_windows
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-30T17:25:32.607
- **CWE:** CWE-23
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-24)

> In RSA Authentication Agent before 7.4.7, service paths and shortcut paths may be vulnerable to path interception if the path has one or more spaces and is not surrounded by quotation marks. An adversary can place an executable in a higher-level directory of the path, and Windows…

### CVE-2018-25126
**Shenzhen TVT Digital Technology Co., Ltd.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-24)

> Shenzhen TVT Digital Technology Co., Ltd. NVMS-9000 firmware (used by many white-labeled DVR/NVR/IPC products) contains hardcoded API credentials and an OS command injection flaw in its configuration services. The web/API interface accepts HTTP/XML requests authenticated with a f…

### CVE-2023-7330
**Ruijie NBR series routers contain an unauthenticated arbitrary file upload vulnerability via /ddi/server/fileupload.php.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-24)

> Ruijie NBR series routers contain an unauthenticated arbitrary file upload vulnerability via /ddi/server/fileupload.php. The endpoint accepts attacker-supplied values in the name and uploadDir parameters and saves the provided multipart file content without adequate validation or…

### CVE-2025-12977
**treasuredata fluent_bit**
- **Signals:** CVSS
- **Asset:** treasuredata fluent_bit
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2025-11-28T18:15:46.550
- **CWE:** CWE-1287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-24)

> Fluent Bit in_http, in_splunk, and in_elasticsearch input plugins fail to sanitize tag_key inputs. An attacker with network access or the ability to write records into Splunk or Elasticsearch can supply tag_key values containing special characters such as newlines or ../ that are…

### CVE-2025-63958
**millensys vision_tools_workspace**
- **Signals:** CVSS
- **Asset:** millensys vision_tools_workspace
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-30T17:53:54.407
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-24)

> MILLENSYS Vision Tools Workspace 6.5.0.2585 exposes a sensitive configuration endpoint (/MILLENSYS/settings) that is accessible without authentication. This page leaks plaintext database credentials, file share paths, internal license server configuration, and software update par…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-24*
