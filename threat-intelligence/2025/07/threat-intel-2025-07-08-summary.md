# Daily Threat Intelligence — July 08, 2025

**Digest window (UTC):** 2025-07-08
**Generated:** 2026-06-02T07:33:01Z

## Threat brief

Microsoft Defender For Endpoint: public exploit or PoC linked (privilege escalation) · Microsoft Internet Explorer — exploitation likelihood rose sharply (EPSS 22% → 35% · rising (+13%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Defender For Endpoint: public exploit or PoC linked (privilege escalation)
- Microsoft Internet Explorer — exploitation likelihood rose sharply (EPSS 22% → 35% · rising (+13%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 8 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **20** |


## CVEs

### CVE-2024-50477
**stacksmarket stacks_mobile_app_builder Auth Bypass**
- **Signals:** EXP
- **Asset:** stacksmarket stacks_mobile_app_builder
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T15:20:01.450
- **CWE:** CWE-288
- **CWE:** CWE-306
- **Risk score:** 78
- **EXP:** ref published 2025-07-08

> Authentication Bypass Using an Alternate Path or Channel vulnerability in Stacks Stacks Mobile App Builder stacks-mobile-app-builder allows Authentication Bypass.This issue affects Stacks Mobile App Builder: from n/a through <= 5.2.3.

### CVE-2025-47161
**microsoft defender_for_endpoint privilege escalation**
- **Signals:** EXP
- **Asset:** microsoft defender_for_endpoint
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2025-07-08T16:15:57.937
- **CWE:** CWE-284
- **Risk score:** 78
- **EXP:** ref published 2025-07-08

> Improper access control in Microsoft Defender for Endpoint allows an authorized attacker to elevate privileges locally.

### CVE-2016-0068
**microsoft internet_explorer privilege escalation**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-264
- **Risk score:** 84
- **EPSS 21.5% (2025-03-30) → 35.0% (2025-07-08), Δ +13.5%**

> Microsoft Internet Explorer 9 through 11 allows remote attackers to bypass the Same Origin Policy via unspecified vectors, aka "Internet Explorer Elevation of Privilege Vulnerability," a different vulnerability than CVE-2016-0069.

### CVE-2016-0069
**microsoft internet_explorer privilege escalation**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-264
- **Risk score:** 84
- **EPSS 25.8% (2025-03-30) → 38.0% (2025-07-08), Δ +12.2%**

> Microsoft Internet Explorer 9 through 11 allows remote attackers to bypass the Same Origin Policy via unspecified vectors, aka "Internet Explorer Elevation of Privilege Vulnerability," a different vulnerability than CVE-2016-0068.

### CVE-2024-47773
**discourse discourse**
- **Signals:** EXP
- **Asset:** discourse discourse
- **CVSS max:** 8.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-26T16:58:28.737
- **CWE:** CWE-610
- **Risk score:** 78
- **EXP:** ref published 2025-07-08

> Discourse is an open source platform for community discussion. An attacker can make several XHR requests until the cache is poisoned with a response without any preloaded data. This issue only affects anonymous visitors of the site. This problem has been patched in the latest ver…

### CVE-2025-21450
**qualcomm ar8035_firmware**
- **Signals:** CVSS
- **Asset:** qualcomm ar8035_firmware
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-11T15:06:17.607
- **CWE:** CWE-287
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-08)

> Cryptographic issue occurs due to use of insecure connection method while downloading.

### CVE-2025-27203
**adobe connect_desktop_application RCE**
- **Signals:** CVSS
- **Asset:** adobe connect_desktop_application
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T19:12:44.310
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-07-08)

> Adobe Connect versions 24.0 and earlier are affected by a Deserialization of Untrusted Data vulnerability that could lead to arbitrary code execution by an attacker. Exploitation of this issue does require user interaction and scope is changed.

### CVE-2025-32462
**sudo_project sudo**
- **Signals:** EXP
- **Asset:** sudo_project sudo
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:18:27.727
- **CWE:** CWE-863
- **Risk score:** 78
- **EXP:** ref published 2025-07-08

> Sudo before 1.9.17p1, when used with a sudoers file that specifies a host that is neither the current host nor ALL, allows listed users to execute commands on unintended machines.

### CVE-2025-32463
**Sudo Inclusion of Functionality from Untrusted Control Sphere Vulnerability**
- **Signals:** EXP
- **Asset:** sudo_project sudo
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:26:48.393
- **CWE:** CWE-829
- **Risk score:** 78
- **EXP:** ref published 2025-07-08

> Sudo before 1.9.17p1 allows local users to obtain root access because /etc/nsswitch.conf from a user-controlled directory is used with the --chroot option.

### CVE-2025-37103
**Hard-coded login credentials were found in HPE Networking Instant On Access Points, allowing anyone with knowledge of it to bypass normal...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-08)

> Hard-coded login credentials were found in HPE Networking Instant On  Access Points, allowing anyone with knowledge of it to bypass normal  device authentication. Successful exploitation could allow a remote  attacker to gain administrative access to the system.

### CVE-2025-40714
**quiter quiter_gateway SQL Injection**
- **Signals:** CVSS
- **Asset:** quiter quiter_gateway
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-15T19:20:03.270
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-08)

> SQL injection vulnerability in versions prior to 4.7.0 of Quiter Gateway by Quiter. This vulnerability allows an attacker to retrieve, create, update and delete databases through the campo id_factura in /<Client>FacturaE/listado_facturas_ficha.jsp.

### CVE-2025-40715
**quiter quiter_gateway SQL Injection**
- **Signals:** CVSS
- **Asset:** quiter quiter_gateway
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-18T01:39:23.210
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-08)

> SQL injection vulnerability in versions prior to 4.7.0 of Quiter Gateway by Quiter. This vulnerability allows an attacker to retrieve, create, update and delete databases through the campo mensaje in /QISClient/api/v1/sucesospaginas.

### CVE-2025-40716
**quiter quiter_gateway SQL Injection**
- **Signals:** CVSS
- **Asset:** quiter quiter_gateway
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-18T01:38:12.793
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-08)

> SQL injection vulnerability in versions prior to 4.7.0 of Quiter Gateway by Quiter. This vulnerability allows an attacker to retrieve, create, update and delete databases through the suceso.contenido mensaje in /QMSCliente/Sucesos.action.

### CVE-2025-40717
**quiter quiter_gateway SQL Injection**
- **Signals:** CVSS
- **Asset:** quiter quiter_gateway
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-18T01:37:55.827
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-08)

> SQL injection vulnerability in versions prior to 4.7.0 of Quiter Gateway by Quiter. This vulnerability allows an attacker to retrieve, create, update and delete databases through the pagina.filter.categoria mensaje in /QuiterGatewayWeb/api/v1/sucesospagina.

### CVE-2025-47171
**microsoft 365_apps**
- **Signals:** EXP
- **Asset:** microsoft 365_apps
- **CVSS max:** 6.7
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-09T13:24:21.797
- **CWE:** CWE-20
- **Risk score:** 78
- **EXP:** ref published 2025-07-08

> Improper input validation in Microsoft Office Outlook allows an authorized attacker to execute code locally.

### CVE-2025-47175
**microsoft 365_apps**
- **Signals:** EXP
- **Asset:** microsoft 365_apps
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-09T13:27:42.433
- **CWE:** CWE-416
- **Risk score:** 78
- **EXP:** ref published 2025-07-08

> Use after free in Microsoft Office PowerPoint allows an unauthorized attacker to execute code locally.

### CVE-2025-47228
**In the Production Environment extension in Netmake ScriptCase through 9.12.006 (23), shell injection in the SSH connection settings allow...**
- **Signals:** EXP
- **Attack:** command injection
- **CVSS max:** 6.7
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 78
- **EXP:** ref published 2025-07-08

> In the Production Environment extension in Netmake ScriptCase through 9.12.006 (23), shell injection in the SSH connection settings allows authenticated attackers to execute system commands via crafted HTTP requests.

### CVE-2025-47981
**microsoft windows_10_1507 Buffer Overflow**
- **Signals:** CVSS
- **Asset:** microsoft windows_10_1507
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-26T17:24:13.330
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-08)

> Heap-based buffer overflow in Windows SPNEGO Extended Negotiation allows an unauthorized attacker to execute code over a network.

### CVE-2025-49533
**adobe experience_manager RCE**
- **Signals:** CVSS
- **Asset:** adobe experience_manager
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-18T14:49:00.017
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-08)

> Adobe Experience Manager (MS) versions 6.5.23.0 and earlier are affected by a Deserialization of Untrusted Data vulnerability that could lead to arbitrary code execution by an attacker. Exploitation of this issue does not require user interaction. Scope is unchanged.

### CVE-2025-49535
**adobe coldfusion DoS**
- **Signals:** CVSS
- **Asset:** adobe coldfusion
- **Attack:** DoS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-11T16:46:44.470
- **CWE:** CWE-611
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-08)

> ColdFusion versions 2025.2, 2023.14, 2021.20 and earlier are affected by an Improper Restriction of XML External Entity Reference ('XXE') vulnerability that could result in a Security feature bypass. An attacker could exploit this vulnerability to access sensitive information or …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-08*
