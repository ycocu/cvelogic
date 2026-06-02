# Daily Threat Intelligence — February 06, 2026

**Digest window (UTC):** 2026-02-06
**Generated:** 2026-06-02T07:34:22Z

## Threat brief

Emc Informix Dynamic Server — exploitation likelihood rose sharply (EPSS 35% → 55% · rising (+20%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Emc Informix Dynamic Server — exploitation likelihood rose sharply (EPSS 35% → 55% · rising (+20%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 5 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2009-2754
**emc informix_dynamic_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ibm informix_dynamic_server
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-189
- **Risk score:** 86
- **EPSS 34.7% (2026-01-18) → 54.9% (2026-02-06), Δ +20.2%**

> Integer signedness error in the authentication functionality in librpc.dll in the Informix Storage Manager (ISM) Portmapper service (aka portmap.exe), as used in IBM Informix Dynamic Server (IDS) 10.x before 10.00.TC9 and 11.x before 11.10.TC3 and EMC Legato NetWorker, allows rem…

### CVE-2012-5002
**ricoh dl-10 Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ricoh dl-10
- **Attack:** Buffer Overflow
- **CVSS max:** 6.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 81
- **EPSS 33.5% (2026-01-12) → 49.9% (2026-02-06), Δ +16.3%**

> Stack-based buffer overflow in SR10 FTP server (SR10.exe) 1.1.0.6 in Ricoh DC Software DL-10 4.5.0.1, when the Log file name option is enabled, allows remote attackers to execute arbitrary code via a long USER FTP command.

### CVE-2026-25632
**waterfutures epyt-flow unsafe deserialization**
- **Signals:** CVSS
- **Asset:** waterfutures epyt-flow
- **Attack:** unsafe deserialization
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-18T15:14:50.900
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-06)

> EPyT-Flow is a Python package designed for the easy generation of hydraulic and water quality scenario data of water distribution networks. Prior to 0.16.1, EPyT-Flow’s REST API parses attacker-controlled JSON request bodies using a custom deserializer (my_load_from_json) that su…

### CVE-2009-2753
**ibm informix_dynamic_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ibm informix_dynamic_server
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 16.8% (2026-01-18) → 30.5% (2026-02-06), Δ +13.7%**

> Multiple buffer overflows in the authentication functionality in librpc.dll in the Informix Storage Manager (ISM) Portmapper service (aka portmap.exe), as used in IBM Informix Dynamic Server (IDS) 10.x before 10.00.TC9 and 11.x before 11.10.TC3, allow remote attackers to execute …

### CVE-2010-1909
**consona consona_dynamic_agent Buffer Overflow**
- **Signals:** EPSS
- **Asset:** consona consona_dynamic_agent
- **Attack:** Buffer Overflow
- **CVSS max:** 7.6
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 81
- **EPSS 11.1% (2025-10-02) → 22.8% (2026-02-06), Δ +11.7%**

> Buffer overflow in the RunCmd method in the SdcUser.TgConCtl ActiveX control in tgctlcm.dll in Consona Live Assistance, Dynamic Agent, and Subscriber Assistance allows remote attackers to execute arbitrary code via vectors involving "CreateProcess params." NOTE: some of these det…

### CVE-2022-0437
**karma_project karma XSS**
- **Signals:** EPSS
- **Asset:** karma_project karma
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:38:37.607
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 12.1% (2025-11-21) → 24.6% (2026-02-06), Δ +12.6%**

> Cross-site Scripting (XSS) - DOM in NPM karma prior to 6.3.14.

### CVE-2026-1727
**The Agentspace service was affected by a vulnerability that exposed sensitive information due to the use of predictable Google Cloud Stor...**
- **Signals:** CVSS
- **Attack:** SQL injection
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-06)

> The Agentspace service was affected by a vulnerability that exposed sensitive information due to the use of predictable Google Cloud Storage bucket names. These names were utilized for error logs and temporary staging during data imports from GCS and Cloud SQL. This predictabilit…

### CVE-2026-1731
**BeyondTrust Remote Support (RS) and Privileged Remote Access (PRA) OS Command Injection Vulnerability**
- **Signals:** CVSS
- **Asset:** beyondtrust privileged_remote_access
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-17T13:40:10.320
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-02-06)

> BeyondTrust Remote Support (RS) and certain older versions of Privileged Remote Access (PRA) contain a critical pre-authentication remote code execution vulnerability. By sending specially crafted requests, an unauthenticated remote attacker may be able to execute operating syste…

### CVE-2026-25544
**payloadcms payload SQL Injection**
- **Signals:** CVSS
- **Asset:** payloadcms payload
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T20:14:42.860
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-06)

> Payload is a free and open source headless content management system. Prior to 3.73.0, when querying JSON or richText fields, user input was directly embedded into SQL without escaping, enabling blind SQL injection attacks. An unauthenticated attacker could extract sensitive data…

### CVE-2026-25587
**nyariv sandboxjs**
- **Signals:** CVSS
- **Asset:** nyariv sandboxjs
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T14:31:17.337
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-06)

> SandboxJS is a JavaScript sandboxing library. Prior to 0.8.29, as Map is in SAFE_PROTOYPES, it's prototype can be obtained via Map.prototype. By overwriting Map.prototype.has the sandbox can be escaped. This vulnerability is fixed in 0.8.29.

### CVE-2026-25592
**Semantic Kernel is an SDK used to build, orchestrate, and deploy AI agents and multi-agent systems.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-02-06)

> Semantic Kernel is an SDK used to build, orchestrate, and deploy AI agents and multi-agent systems. Prior to 1.71.0, an Arbitrary File Write vulnerability has been identified in Microsoft's Semantic Kernel .NET SDK, specifically within the SessionsPythonPlugin. The problem has be…

### CVE-2026-25641
**nyariv sandboxjs**
- **Signals:** CVSS
- **Asset:** nyariv sandboxjs
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T14:01:02.337
- **CWE:** CWE-367
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-06)

> SandboxJS is a JavaScript sandboxing library. Prior to 0.8.29, there is a sandbox escape vulnerability due to a mismatch between the key on which the validation is performed and the key used for accessing properties. Even though the key used in property accesses is annotated as s…

### CVE-2026-25643
**frigate frigate RCE**
- **Signals:** CVSS
- **Asset:** frigate frigate
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T19:00:39.877
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-06)

> Frigate is a network video recorder (NVR) with realtime local object detection for IP cameras. Prior to 0.16.4, a critical Remote Command Execution (RCE) vulnerability has been identified in the Frigate integration with go2rtc. The application does not sanitize user input in the …

### CVE-2026-25763
**openproject openproject**
- **Signals:** CVSS
- **Asset:** openproject openproject
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T19:07:56.520
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-06)

> OpenProject is an open-source, web-based project management software. Prior to versions 16.6.7 and 17.0.3, an arbitrary file write vulnerability exists in OpenProject’s repository changes endpoint (/projects/:project_id/repository/changes) when rendering the “latest changes” view…

### CVE-2026-25803
**denpiligrim 3dp-manager**
- **Signals:** CVSS
- **Asset:** denpiligrim 3dp-manager
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-17T20:43:52.930
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-06)

> 3DP-MANAGER is an inbound generator for 3x-ui. In version 2.0.1 and prior, the application automatically creates an administrative account with known default credentials (admin/admin) upon the first initialization. Attackers with network access to the application's login interfac…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-06*
