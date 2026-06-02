# Daily Threat Intelligence — September 25, 2025

**Digest window (UTC):** 2025-09-25
**Generated:** 2026-06-02T07:33:29Z

## Threat brief

Cisco Secure Firewall Adaptive Security Appliance And Secure Firewall Threat Defense: 2 CVEs added to CISA KEV today. · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cisco Secure Firewall Adaptive Security Appliance And Secure Firewall Threat Defense: 2 CVEs added to CISA KEV today.
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-20333
**Cisco Secure Firewall Adaptive Security Appliance (ASA) and Secure Firewall Threat Defense (FTD) Buffer Overflow Vulnerability**
- **Signals:** KEV, CVSS
- **Asset:** cisco adaptive_security_appliance_software
- **Attack:** Buffer Overflow
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T13:58:58.610
- **CWE:** CWE-120
- **Risk score:** 97
- **KEV:** added 2025-09-25
- **CVSS critical:** 9.9 (disclosed 2025-09-25)

> A vulnerability in the VPN web server of Cisco Secure Firewall Adaptive Security Appliance (ASA) Software and Cisco Secure Firewall Threat Defense (FTD) Software could allow an authenticated, remote attacker to execute arbitrary code on an affected device.
 This vulnerability i…

### CVE-2025-59832
**horilla horilla cross-site scripting**
- **Signals:** CVSS
- **Asset:** horilla horilla
- **Attack:** cross-site scripting
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-29T14:03:20.917
- **CWE:** CWE-79
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-09-25)

> Horilla is a free and open source Human Resource Management System (HRMS). Prior to version 1.4.0, there is a stored XSS vulnerability in the ticket comment editor. A low-privilege authenticated user could run arbitrary JavaScript in an admin’s browser, exfiltrate the admin’s coo…

### CVE-2025-59823
**Project Gardener implements the automated management and operation of Kubernetes clusters as a service.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-09-25)

> Project Gardener implements the automated management and operation of Kubernetes clusters as a service. Code injection may be possible in Gardener Extensions for AWS providers prior to version 1.64.0, Azure providers prior to version 1.55.0, OpenStack providers prior to version 1…

### CVE-2020-36851
**Rob--W cors-anywhere instances configured as an open proxy allow unauthenticated external users to induce the server to make HTTP request...**
- **Signals:** CVSS
- **Attack:** SSRF
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T14:16:24.590
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-09-25)

> Rob--W cors-anywhere instances configured as an open proxy allow unauthenticated external users to induce the server to make HTTP requests to arbitrary targets (SSRF). Because the proxy forwards requests and headers, an attacker can reach internal-only endpoints and link-local me…

### CVE-2025-10542
**iMonitor EAM 9.6394 ships with default administrative credentials that are also displayed within the management client’s connection dialog.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1392
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-25)

> iMonitor EAM 9.6394 ships with default administrative credentials that are also displayed within the management client’s connection dialog. If the administrator does not change these defaults, a remote attacker can authenticate to the EAM server and gain full control over monitor…

### CVE-2025-11005
**totolink x6000r_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** totolink x6000r_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-16T15:45:04.160
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-25)

> Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in TOTOLINK X6000R allows OS Command Injection.This issue affects X6000R: through V9.4.0cu.1458_B20250708.

### CVE-2025-20362
**Cisco Secure Firewall Adaptive Security (ASA) Appliance and Secure Firewall Threat Defense (FTD) Missing Authorization Vulnerability**
- **Signals:** KEV
- **Asset:** cisco adaptive_security_appliance_software
- **Attack:** DoS
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T14:51:19.950
- **CWE:** CWE-862
- **Risk score:** 88
- **KEV:** added 2025-09-25

> Update: On November 5, 2025, Cisco became aware of a new attack variant against devices running Cisco Secure ASA Software or Cisco Secure FTD Software releases that are affected by CVE-2025-20333 and CVE-2025-20362. This attack can cause unpatched devices to unexpectedly reload, …

### CVE-2025-20363
**cisco adaptive_security_appliance_software**
- **Signals:** CVSS
- **Asset:** cisco ios_xr
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-10T17:12:01.947
- **CWE:** CWE-122
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-09-25)

> A vulnerability in the web services of Cisco Secure Firewall Adaptive Security Appliance (ASA) Software, Cisco Secure Firewall Threat Defense (FTD) Software, Cisco IOS Software, Cisco IOS XE Software, and Cisco IOS XR Software could allow an unauthenticated, remote attacker (Cisc…

### CVE-2025-59834
**srmorete adb_mcp_server Command Injection**
- **Signals:** CVSS
- **Asset:** srmorete adb_mcp_server
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-14T20:05:46.243
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-25)

> ADB MCP Server is a MCP (Model Context Protocol) server for interacting with Android devices through ADB. In versions 0.1.0 and prior, the MCP Server is written in a way that is vulnerable to command injection vulnerability attacks as part of some of its MCP Server tool definitio…

### CVE-2025-59841
**flagforge flagforge CSRF**
- **Signals:** CVSS
- **Asset:** flagforge flagforge
- **Attack:** CSRF
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-08T16:31:08.920
- **CWE:** CWE-384
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-25)

> Flag Forge is a Capture The Flag (CTF) platform. In versions from 2.2.0 to before 2.3.1, the FlagForge web application improperly handles session invalidation. Authenticated users can continue to access protected endpoints, such as /api/profile, even after logging out. CSRF token…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-25*
