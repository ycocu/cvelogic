# Daily Threat Intelligence — January 20, 2026

**Digest window (UTC):** 2026-01-20
**Generated:** 2026-06-02T07:34:14Z

## Threat brief

Apache Http Server — exploitation likelihood rose sharply (EPSS 70% → 85% · rising (+16%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Apache Http Server — exploitation likelihood rose sharply (EPSS 70% → 85% · rising (+16%)).
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

### CVE-1999-0070
**apache http_server**
- **Signals:** EPSS
- **Asset:** apache http_server
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 69.7% (2025-12-28) → 85.2% (2026-01-20), Δ +15.5%**

> test-cgi program allows an attacker to list files on the server.

### CVE-2026-21636
**nodejs node.js**
- **Signals:** CVSS
- **Asset:** nodejs node.js
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T20:20:56.843
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-20)

> A flaw in Node.js's permission model allows Unix Domain Socket (UDS) connections to bypass network restrictions when `--permission` is enabled. Even without `--allow-net`, attacker-controlled inputs (such as URLs or socketPath options) can connect to arbitrary local sockets via n…

### CVE-2026-21962
**oracle http_server**
- **Signals:** CVSS
- **Asset:** oracle http_server
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-02-03T00:16:10.653
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-20)

> Vulnerability in the Oracle HTTP Server, Oracle Weblogic Server Proxy Plug-in product of Oracle Fusion Middleware (component: Weblogic Server Proxy Plug-in for Apache HTTP Server, Weblogic Server Proxy Plug-in for IIS).  Supported versions that are affected are 12.2.1.4.0, 14.1.1…

### CVE-2025-53912
**meddream pacs_server**
- **Signals:** CVSS
- **Asset:** meddream pacs_server
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T15:26:24.213
- **CWE:** CWE-73
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-01-20)

> An arbitrary file read vulnerability exists in the encapsulatedDoc functionality of MedDream PACS Premium 7.3.6.870. A specially crafted HTTP request can lead to an arbitrary file read. An attacker can send http request to trigger this vulnerability.

### CVE-2025-55130
**nodejs node.js**
- **Signals:** CVSS
- **Asset:** nodejs node.js
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T21:29:50.967
- **CWE:** CWE-289
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-20)

> A flaw in Node.js’s Permissions model allows attackers to bypass `--allow-fs-read` and `--allow-fs-write` restrictions using crafted relative symlink paths. By chaining directories and symlinks, a script granted access only to the current directory can escape the allowed path and…

### CVE-2025-55423
**iptime a1004_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** iptime n104s-r1_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T20:07:11.633
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-20)

> A command injection vulnerability exists in the upnp_relay() function in multiple ipTIME router models because the controlURL value used to pass port-forwarding information to an upper router is passed to system() without proper validation or sanitization, allowing OS command inj…

### CVE-2025-56005
**dabeaz ply RCE**
- **Signals:** CVSS
- **Asset:** dabeaz ply
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-02-06T20:16:08.237
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-20)

> An undocumented and unsafe feature in the PLY (Python Lex-Yacc) library 3.11 allows Remote Code Execution (RCE) via the `picklefile` parameter in the `yacc()` function. This parameter accepts a `.pkl` file that is deserialized with `pickle.load()` without validation. Because `pic…

### CVE-2025-64087
**opensagres xdocreport**
- **Signals:** CVSS
- **Asset:** opensagres xdocreport
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T21:49:59.897
- **CWE:** CWE-1336
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-20)

> A Server-Side Template Injection (SSTI) vulnerability in the FreeMarker component of opensagres XDocReport v1.0.0 to v2.1.0 allows attackers to execute arbitrary code via injecting crafted template expressions.

### CVE-2025-65482
**opensagres xdocreport XXE**
- **Signals:** CVSS
- **Asset:** opensagres xdocreport
- **Attack:** XXE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-03T21:43:11.270
- **CWE:** CWE-611
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-20)

> An XML External Entity (XXE) vulnerability in opensagres XDocReport v0.9.2 to v2.0.3 allows attackers to execute arbitrary code via uploading a crafted .docx file.

### CVE-2026-21969
**oracle agile_product_lifecycle_management_for_process**
- **Signals:** CVSS
- **Asset:** oracle agile_product_lifecycle_management_for_process
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T14:48:11.893
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-20)

> Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Supplier Portal).   The supported version that is affected is 6.2.4. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP…

### CVE-2026-22844
**A Command Injection vulnerability in Zoom Node Multimedia Routers (MMRs) before version 5.2.1716.0 may allow a meeting participant to con...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-20)

> A Command Injection vulnerability in Zoom Node Multimedia Routers (MMRs) before version 5.2.1716.0 may allow a meeting participant to conduct remote code execution of the MMR via network access.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-20*
