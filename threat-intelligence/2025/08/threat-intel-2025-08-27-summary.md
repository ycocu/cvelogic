# Daily Threat Intelligence — August 27, 2025

**Digest window (UTC):** 2025-08-27
**Generated:** 2026-06-02T07:33:18Z

## Threat brief

Futuresoft Tftp Server Multithreaded — exploitation likelihood rose sharply (EPSS 16% → 47% · rising (+32%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Futuresoft Tftp Server Multithreaded — exploitation likelihood rose sharply (EPSS 16% → 47% · rising (+32%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2006-4781
**futuresoft tftp_server_multithreaded Buffer Overflow**
- **Signals:** EPSS
- **Asset:** futuresoft tftp_server_multithreaded
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 15.5% (2025-05-03) → 47.3% (2025-08-27), Δ +31.8%**

> Heap-based buffer overflow in FutureSoft TFTP Server Multithreaded (MT) 1.1 allows remote attackers to cause a denial of service (crash) or possibly execute arbitrary code by sending a crafted packet to port 69/UDP, which triggers the overflow when constructing an absolute path n…

### CVE-2024-13981
**LiveBOS, an object-oriented business architecture middleware suite developed by Apex Software Co., Ltd., contains an arbitrary file uploa...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-27)

> LiveBOS, an object-oriented business architecture middleware suite developed by Apex Software Co., Ltd., contains an arbitrary file upload vulnerability in its UploadFile.do;.js.jsp endpoint. This flaw affects the LiveBOS Server component and allows unauthenticated remote attacke…

### CVE-2024-13984
**QiAnXin TianQing Management Center versions up to and including 6.7.0.4130 contain a path traversal vulnerability in the rptsvr component...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-27)

> QiAnXin TianQing Management Center versions up to and including 6.7.0.4130 contain a path traversal vulnerability in the rptsvr component that allows unauthenticated attackers to upload files to arbitrary locations on the server. The /rptsvr/upload endpoint fails to sanitize the …

### CVE-2024-13979
**st._joe_erp_system_project st._joe_erp_system SQL Injection**
- **Signals:** CVSS
- **Asset:** st._joe_erp_system_project st._joe_erp_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-09T18:44:14.520
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-27)

> A SQL injection vulnerability exists in the St. Joe ERP system ("圣乔ERP系统") that allows unauthenticated remote attackers to execute arbitrary SQL commands via crafted HTTP POST requests to the login endpoint. The application fails to properly sanitize user-supplied input before in…

### CVE-2024-13980
**H3C Intelligent Management Center (IMC) versions up to and including E0632H07 contains a remote command execution vulnerability in the /b...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-27)

> H3C Intelligent Management Center (IMC) versions up to and including E0632H07 contains a remote command execution vulnerability in the /byod/index.xhtml endpoint. Improper handling of JSF ViewState allows unauthenticated attackers to craft POST requests with forged javax.faces.Vi…

### CVE-2024-13985
**A command injection vulnerability in Dahua EIMS versions prior to 2240008 allows unauthenticated remote attackers to execute arbitrary sy...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-27)

> A command injection vulnerability in Dahua EIMS versions prior to 2240008 allows unauthenticated remote attackers to execute arbitrary system commands via the capture_handle.action interface. The flaw stems from improper input validation in the captureCommand parameter, which is …

### CVE-2025-34160
**AnyShare contains a critical unauthenticated remote code execution vulnerability in the ServiceAgent API exposed on port 10250.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-27)

> AnyShare contains a critical unauthenticated remote code execution vulnerability in the ServiceAgent API exposed on port 10250. The endpoint /api/ServiceAgent/start_service accepts user-supplied input via POST and fails to sanitize command-like payloads. An attacker can inject sh…

### CVE-2025-34162
**An unauthenticated SQL injection vulnerability exists in the GetLyfsByParams endpoint of Bian Que Feijiu Intelligent Emergency and Qualit...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T14:16:27.233
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-27)

> An unauthenticated SQL injection vulnerability exists in the GetLyfsByParams endpoint of Bian Que Feijiu Intelligent Emergency and Quality Control System, accessible via the /AppService/BQMedical/WebServiceForFirstaidApp.asmx interface. The backend fails to properly sanitize user…

### CVE-2025-34163
**Dongsheng Logistics Software exposes an unauthenticated endpoint at /CommMng/Print/UploadMailFile that fails to enforce proper file type...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T14:16:27.387
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-27)

> Dongsheng Logistics Software exposes an unauthenticated endpoint at /CommMng/Print/UploadMailFile that fails to enforce proper file type validation and access control. An attacker can upload arbitrary files, including executable scripts such as .ashx, via a crafted multipart/form…

### CVE-2025-34522
**arcserve udp RCE**
- **Signals:** CVSS
- **Asset:** arcserve udp
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-09T14:45:21.940
- **CWE:** CWE-122
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-08-27)

> A heap-based buffer overflow vulnerability exists in the input parsing logic of Arcserve Unified Data Protection (UDP). This flaw can be triggered without authentication by sending specially crafted input to the target system. Improper bounds checking allows an attacker to overwr…

### CVE-2025-34523
**arcserve udp Buffer Overflow**
- **Signals:** CVSS
- **Asset:** arcserve udp
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T14:16:27.903
- **CWE:** CWE-122
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-08-27)

> A heap-based buffer overflow vulnerability exists in the network-facing input handling routines of Arcserve Unified Data Protection (UDP). This flaw is reachable without authentication and results from improper bounds checking when processing attacker-controlled input. By sending…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-27*
