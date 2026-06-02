# Daily Threat Intelligence — August 14, 2025

**Digest window (UTC):** 2025-08-14
**Generated:** 2026-06-02T07:33:14Z

## Threat brief

An-httpd — exploitation likelihood rose sharply (EPSS 11% → 23% · rising (+13%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- An-httpd — exploitation likelihood rose sharply (EPSS 11% → 23% · rising (+13%)).
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

### CVE-2002-1930
**an an-httpd Buffer Overflow**
- **Signals:** EPSS
- **Asset:** an an-httpd
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 10.9% (2025-03-30) → 23.5% (2025-08-14), Δ +12.5%**

> Buffer overflow in AN HTTPd 1.38 through 1.4.1c allows remote attackers to execute arbitrary code via a SOCKS4 request with a long username.

### CVE-2025-20265
**cisco secure_firewall_management_center**
- **Signals:** CVSS
- **Asset:** cisco secure_firewall_management_center
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2025-08-16T01:15:27.227
- **CWE:** CWE-74
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-14)

> A vulnerability in the RADIUS subsystem implementation of Cisco Secure Firewall Management Center (FMC) Software could allow an unauthenticated, remote attacker to inject arbitrary shell commands that are executed by the device.&nbsp;

This vulnerability is due to a lack of pro…

### CVE-2025-43984
**An issue was discovered on KuWFi GC111 devices (Hardware Version: CPE-LM321_V3.2, Software Version: GC111-GL-LM321_V3.0_20191211).**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-14)

> An issue was discovered on KuWFi GC111 devices (Hardware Version: CPE-LM321_V3.2, Software Version: GC111-GL-LM321_V3.0_20191211). They are vulnerable to unauthenticated /goform/goform_set_cmd_process requests. A crafted POST request, using the SSID parameter, allows remote attac…

### CVE-2025-27845
**In ESPEC North America Web Controller 3 before 3.3.4, /api/v4/auth/ with any invalid authentication request results in exposing a JWT sec...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-14)

> In ESPEC North America Web Controller 3 before 3.3.4, /api/v4/auth/ with any invalid authentication request results in exposing a JWT secret. This allows for elevated permissions to the UI.

### CVE-2025-43983
**KuWFi CPF908-CP5 WEB5.0_LCD_20210125 devices have multiple unauthenticated access control vulnerabilities within goform/goform_set_cmd_pr...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-14)

> KuWFi CPF908-CP5 WEB5.0_LCD_20210125 devices have multiple unauthenticated access control vulnerabilities within goform/goform_set_cmd_process and goform/goform_get_cmd_process. These allow an unauthenticated attacker to retrieve sensitive information (including the device admin …

### CVE-2025-50518
**A use-after-free vulnerability exists in the coap_delete_pdu_lkd function within coap_pdu.c of the libcoap library.**
- **Signals:** CVSS
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-14)

> A use-after-free vulnerability exists in the coap_delete_pdu_lkd function within coap_pdu.c of the libcoap library. This issue occurs due to improper handling of memory after the freeing of a PDU object, leading to potential memory corruption or the possibility of executing arbit…

### CVE-2025-54693
**Unrestricted Upload of File with Dangerous Type vulnerability in epiphyt Form Block form-block allows Upload a Web Shell to a Web Server....**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:32:50.210
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-08-14)

> Unrestricted Upload of File with Dangerous Type vulnerability in epiphyt Form Block form-block allows Upload a Web Shell to a Web Server.This issue affects Form Block: from n/a through <= 1.5.5.

### CVE-2025-54707
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in RealMag777 MDTF wp-meta-data-filter...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:32:51.837
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-14)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in RealMag777 MDTF wp-meta-data-filter-and-taxonomy-filter allows SQL Injection.This issue affects MDTF: from n/a through <= 1.3.3.7.

### CVE-2025-7353
**A security issue exists due to the web-based debugger agent enabled on Rockwell Automation ControlLogix® Ethernet Modules.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1188
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-14)

> A security issue exists due to the web-based debugger agent enabled on Rockwell Automation ControlLogix® Ethernet Modules. If a specific IP address is used to connect to the WDB agent, it can allow remote attackers to perform memory dumps, modify memory, and control execution flo…

### CVE-2025-8875
**N-able N-Central Insecure Deserialization Vulnerability**
- **Signals:** CVSS
- **Asset:** n-able n-central
- **Attack:** Deserialization
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T14:58:50.500
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-14)

> Deserialization of Untrusted Data vulnerability in N-able N-central allows Local Execution of Code.This issue affects N-central: before 2025.3.1.

### CVE-2025-8876
**N-able N-Central Command Injection Vulnerability**
- **Signals:** CVSS
- **Asset:** n-able n-central
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T14:58:04.440
- **CWE:** CWE-20
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-08-14)

> Improper Input Validation vulnerability in N-able N-central allows OS Command Injection.This issue affects N-central: before 2025.3.1.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-14*
