# Daily Threat Intelligence — March 09, 2026

**Digest window (UTC):** 2026-03-09
**Generated:** 2026-06-02T07:34:36Z

## Threat brief

Ivanti Endpoint Manager (EPM) added to CISA KEV — confirmed in-the-wild exploitation. · Zyxel DSL CPE Devices — exploitation likelihood rose sharply (EPSS 21% → 46% · rising (+25%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Ivanti Endpoint Manager (EPM) added to CISA KEV — confirmed in-the-wild exploitation.
- Zyxel DSL CPE Devices — exploitation likelihood rose sharply (EPSS 21% → 46% · rising (+25%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 3 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2021-22054
**Omnissa Workspace ONE Server-Side Request Forgery**
- **Signals:** KEV
- **Asset:** vmware workspace_one_uem_console
- **Attack:** SSRF
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T13:11:06.340
- **CWE:** CWE-918
- **CWE:** CWE-918
- **Risk score:** 88
- **KEV:** added 2026-03-09

> VMware Workspace ONE UEM console 20.0.8 prior to 20.0.8.37, 20.11.0 prior to 20.11.0.40, 21.2.0 prior to 21.2.0.27, and 21.5.0 prior to 21.5.0.37 contain an SSRF vulnerability. This issue may allow a malicious actor with network access to UEM to send their requests without authen…

### CVE-2024-40890
**Zyxel DSL CPE OS Command Injection Vulnerability**
- **Signals:** EPSS
- **Asset:** zyxel vmg1312-b10a_firmware
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:04:41.637
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 21.3% (2026-03-08) → 45.9% (2026-03-09), Δ +24.6%**

> **UNSUPPORTED WHEN ASSIGNED**
A post-authentication command injection vulnerability in the CGI program of the legacy DSL CPE Zyxel VMG4325-B10A firmware version 1.00(AAFR.4)C0_20170615 could allow an authenticated attacker to execute operating system (OS) commands on an affected …

### CVE-2025-70039
**linagora twake**
- **Signals:** CVSS
- **Asset:** linagora twake
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T16:44:56.027
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-09)

> An issue pertaining to CWE-78: Improper Neutralization of Special Elements used in an OS Command was discovered in linagora Twake v2023.Q1.1223.

### CVE-2021-38146
**wipro holmes Path Traversal**
- **Signals:** EPSS
- **Asset:** wipro holmes
- **Attack:** Path Traversal
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:16:28.900
- **CWE:** CWE-22
- **Risk score:** 80
- **EPSS 37.0% (2026-01-18) → 47.5% (2026-03-09), Δ +10.5%**

> The File Download API in Wipro Holmes Orchestrator 20.4.1 (20.4.1_02_11_2020) allows remote attackers to read arbitrary files via absolute path traversal in the SearchString JSON field in /home/download POST data.

### CVE-2025-26399
**SolarWinds Web Help Desk Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** solarwinds web_help_desk
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T13:11:15.553
- **CWE:** CWE-502
- **CWE:** CWE-502
- **Risk score:** 88
- **KEV:** added 2026-03-09

> SolarWinds Web Help Desk was found to be susceptible to an unauthenticated AjaxProxy deserialization remote code execution vulnerability that, if exploited, would allow an attacker to run commands on the host machine. This vulnerability is a patch bypass of CVE-2024-28988, which …

### CVE-2025-41764
**mbs-solutions universal_bacnet_router_firmware privilege escalation**
- **Signals:** CVSS
- **Asset:** mbs-solutions universal_bacnet_router_firmware
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T18:27:27.697
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-09)

> Due to insufficient authorization enforcement, an unauthorized remote attacker can exploit the wwwupdate.cgi endpoint to upload and apply arbitrary updates.

### CVE-2025-41765
**mbs-solutions universal_bacnet_router_firmware privilege escalation**
- **Signals:** CVSS
- **Asset:** mbs-solutions universal_bacnet_router_firmware
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-11T18:27:29.820
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-09)

> Due to insufficient authorization enforcement, an unauthorized remote attacker can exploit the wwwupload.cgi endpoint to upload and apply arbitrary data. This includes, but is not limited to, contact images, HTTPS certificates, system backups for restoration, server peer configur…

### CVE-2025-70042
**opensourcelabs thermakube**
- **Signals:** CVSS
- **Asset:** opensourcelabs thermakube
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-18T18:37:49.577
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-09)

> An issue pertaining to CWE-918: Server-Side Request Forgery was discovered in oslabs-beta ThermaKube master.

### CVE-2025-70046
**miazzy oa-font-service**
- **Signals:** CVSS
- **Asset:** miazzy oa-font-service
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T20:02:51.930
- **CWE:** CWE-829
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-09)

> An issue pertaining to CWE-829: Inclusion of Functionality from Untrusted Control Sphere was discovered in Miazzy oa-front-service master.

### CVE-2026-1603
**Ivanti Endpoint Manager (EPM) Authentication Bypass Vulnerability**
- **Signals:** KEV
- **Asset:** ivanti endpoint_manager
- **Attack:** Auth Bypass
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T13:11:30.467
- **CWE:** CWE-288
- **CWE:** CWE-306
- **Risk score:** 88
- **KEV:** added 2026-03-09

> An authentication bypass in Ivanti Endpoint Manager before version 2024 SU5 allows a remote unauthenticated attacker to leak specific stored credential data.

### CVE-2026-24015
**apache iotdb**
- **Signals:** CVSS
- **Asset:** apache iotdb
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T18:56:56.850
- **CWE:** CWE-1327
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-09)

> A vulnerability in Apache IoTDB.

This issue affects Apache IoTDB: from 1.0.0 before 1.3.7, from 2.0.0 before 2.0.7.

Users are recommended to upgrade to version 1.3.7 or 2.0.7, which fixes the issue.

### CVE-2026-24713
**apache iotdb**
- **Signals:** CVSS
- **Asset:** apache iotdb
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T18:57:14.640
- **CWE:** CWE-20
- **CWE:** CWE-917
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-09)

> Improper Input Validation vulnerability in Apache IoTDB.

This issue affects Apache IoTDB: from 1.0.0 before 1.3.7, from 2.0.0 before 2.0.7.

Users are recommended to upgrade to version 1.3.7 or 2.0.7, which fixes the issue.

### CVE-2026-30240
**budibase budibase Path Traversal**
- **Signals:** CVSS
- **Asset:** budibase budibase
- **Attack:** Path Traversal
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T17:46:41.427
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-03-09)

> Budibase is a low code platform for creating internal tools, workflows, and admin panels. In 3.31.5 and earlier, a path traversal vulnerability in the PWA (Progressive Web App) ZIP processing endpoint (POST /api/pwa/process-zip) allows an authenticated user with builder privilege…

### CVE-2026-31816
**budibase budibase**
- **Signals:** CVSS
- **Asset:** budibase budibase
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-13T17:33:41.703
- **CWE:** CWE-74
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-09)

> Budibase is a low code platform for creating internal tools, workflows, and admin panels. In 3.31.4 and earlier, the Budibase server's authorized() middleware that protects every server-side API endpoint can be completely bypassed by appending a webhook path pattern to the query …

### CVE-2026-3823
**blackbeartechhive atop_ehg2408-2sfp_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** blackbeartechhive atop_ehg2408_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T18:46:53.270
- **CWE:** CWE-121
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-09)

> EHG2408 series switch developed by Atop Technologies has a Stack-based Buffer Overflow vulnerability, allowing unauthenticated remote attackers to control the program's execution flow and execute arbitrary code.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-09*
