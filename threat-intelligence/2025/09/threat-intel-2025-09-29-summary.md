# Daily Threat Intelligence — September 29, 2025

**Digest window (UTC):** 2025-09-29
**Generated:** 2026-06-02T07:33:30Z

## Threat brief

Cisco IOS And IOS XE added to CISA KEV — confirmed in-the-wild exploitation. · Flipsource Flip — exploitation likelihood rose sharply (EPSS 33% → 79% · rising (+46%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cisco IOS And IOS XE added to CISA KEV — confirmed in-the-wild exploitation.
- Flipsource Flip — exploitation likelihood rose sharply (EPSS 33% → 79% · rising (+46%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 5 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2025-10035
**Fortra GoAnywhere MFT Deserialization of Untrusted Data Vulnerability**
- **Signals:** KEV
- **Asset:** fortra goanywhere_managed_file_transfer
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:44:10.740
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 88
- **KEV:** added 2025-09-29

> A deserialization vulnerability in the License Servlet of Fortra's GoAnywhere MFT allows an actor with a validly forged license response signature to deserialize an arbitrary actor-controlled object, possibly leading to command injection.

### CVE-2007-0785
**flipsource flip**
- **Signals:** EPSS
- **Asset:** flipsource flip
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 82
- **EPSS 32.9% (2025-09-25) → 79.2% (2025-09-29), Δ +46.3%**

> PHP remote file inclusion vulnerability in previewtheme.php in Flipsource Flip 2.01-final 1.0 and earlier allows remote attackers to execute arbitrary PHP code via a URL in the inc_path parameter.

### CVE-2025-34216
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T18:04:23.007
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-29)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host prior to version 22.0.1026 and Application prior to version 20.0.2702 (VA deployments only) expose a set of unauthenticated REST API endpoints that return configuration files and clear‑text passwords. The same endpoints …

### CVE-2007-0766
**remotesoft .net_explorer Buffer Overflow**
- **Signals:** EPSS
- **Asset:** remotesoft .net_explorer
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 85
- **EPSS 6.6% (2025-09-25) → 23.0% (2025-09-29), Δ +16.5%**

> Stack-based buffer overflow in Remotesoft .NET Explorer 2.0.1 allows user-assisted remote attackers to cause a denial of service (application crash) and possibly execute arbitrary code via a long line in a .cpp file.

### CVE-2008-4255
**microsoft office_frontpage Buffer Overflow**
- **Signals:** EPSS
- **Asset:** microsoft office_frontpage
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 53.4% (2025-03-30) → 65.7% (2025-09-29), Δ +12.3%**

> Heap-based buffer overflow in mscomct2.ocx (aka Windows Common ActiveX control or Microsoft Animation ActiveX control) in Microsoft Visual Basic 6.0, Visual Studio .NET 2002 SP1 and 2003 SP1, Visual FoxPro 8.0 SP1 and 9.0 SP1 and SP2, and Office Project 2003 SP3 and 2007 Gold and…

### CVE-2021-21311
**Adminer Server-Side Request Forgery Vulnerability**
- **Signals:** KEV
- **Asset:** adminer adminer
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T14:48:35.890
- **CWE:** CWE-918
- **Risk score:** 88
- **KEV:** added 2025-09-29

> Adminer is an open-source database management in a single PHP file. In adminer from version 4.0.0 and before 4.7.9 there is a server-side request forgery vulnerability. Users of Adminer versions bundling all drivers (e.g. `adminer.php`) are affected. This is fixed in version 4.7.…

### CVE-2025-20352
**Cisco IOS and IOS XE Software SNMP Denial of Service and Remote Code Execution Vulnerability**
- **Signals:** KEV
- **Asset:** cisco ios_xe_sd-wan
- **Attack:** RCE
- **CVSS max:** 7.7
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T13:58:42.437
- **CWE:** CWE-121
- **Risk score:** 88
- **KEV:** added 2025-09-29

> A vulnerability in the Simple Network Management Protocol (SNMP) subsystem of Cisco IOS Software and Cisco IOS XE Software could allow the following:
  An authenticated, remote attacker with low privileges could cause a denial of service (DoS) condition on an affected device t…

### CVE-2025-32463
**Sudo Inclusion of Functionality from Untrusted Control Sphere Vulnerability**
- **Signals:** KEV
- **Asset:** sudo_project sudo
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:26:48.393
- **CWE:** CWE-829
- **Risk score:** 88
- **KEV:** added 2025-09-29

> Sudo before 1.9.17p1 allows local users to obtain root access because /etc/nsswitch.conf from a user-controlled directory is used with the --chroot option.

### CVE-2025-34218
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T18:04:33.063
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-29)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host prior to version 22.0.1049 and Application prior to version 20.0.2786 (VA/SaaS deployments) expose internal Docker containers through the gw Docker instance.  The gateway publishes a /meta endpoint which lists every micr…

### CVE-2025-34221
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T18:11:54.903
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-29)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host prior to version 25.2.169 and Application prior to version 25.2.1518 (VA/SaaS deployments) expose every internal Docker container to the network because firewall rules allow unrestricted traffic to the Docker bridge netw…

### CVE-2025-34222
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T18:13:17.547
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-29)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host prior to version 22.0.1049 and Application prior to version 20.0.2786 (VA/SaaS deployments) expose four admin routes – /admin/hp/cert_upload, /admin/hp/cert_delete, /admin/certs/ca, and /admin/certs/serviceclients/{scid}…

### CVE-2025-34223
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T18:13:32.420
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-29)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host prior to version 22.0.1049 and Application prior to version 20.0.2786 (VA/SaaS deployments) contain a default admin account and an installation‑time endpoint at `/admin/query/update_database.php` that can be accessed wit…

### CVE-2025-34224
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T18:23:34.493
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-29)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host prior to version 22.0.1049 and Application prior to version 20.0.2786 (VA/SaaS deployments) expose a set of PHP scripts under the `console_release` directory without requiring authentication.  An unauthenticated remote a…

### CVE-2025-34234
**vasion virtual_appliance_application**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T17:55:04.450
- **CWE:** CWE-321
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-09-29)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host prior to version 25.1.102 and Application prior to version 25.1.1413 (VA/SaaS deployments) contain two hardcoded private keys that are shipped in the application containers (printerlogic/pi, printerlogic/printer-admin-ap…

### CVE-2025-34235
**vasion virtual_appliance_application RCE**
- **Signals:** CVSS
- **Asset:** vasion virtual_appliance_application
- **Attack:** RCE
- **CVSS max:** 9.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T17:55:21.890
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-09-29)

> Vasion Print (formerly PrinterLogic) Virtual Appliance Host prior to version 25.1.102 and Application prior to version 25.1.1413 (Windows client deployments) contain a registry key that can be enabled by administrators, causing the client to skip SSL/TLS certificate validation. A…

### CVE-2025-54875
**freshrss freshrss privilege escalation**
- **Signals:** CVSS
- **Asset:** freshrss freshrss
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-03T15:59:35.287
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-29)

> FreshRSS is a free, self-hostable RSS aggregator. In versions 1.16.0 and above through 1.26.3, an unprivileged attacker can create a new admin user when registration is enabled through the use of a hidden field used only in the user management admin page, new_user_is_admin. This …

### CVE-2025-57266
**An issue was discovered in file AssistantController.java in ThriveX Blogging Framework 2.5.9 thru 3.1.3 allowing unauthenticated attacker...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-29)

> An issue was discovered in file AssistantController.java in ThriveX Blogging Framework 2.5.9 thru 3.1.3 allowing unauthenticated attackers to gain sensitive information such as API Keys via the /api/assistant/list endpoint.

### CVE-2025-59689
**Libraesva Email Security Gateway Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** libraesva email_security_gateway
- **Attack:** Command Injection
- **CVSS max:** 6.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:25:35.093
- **CWE:** CWE-77
- **Risk score:** 88
- **KEV:** added 2025-09-29

> Libraesva ESG 4.5 through 5.5.x before 5.5.7 allows command injection via a compressed e-mail attachment. For ESG 5.0 a fix has been released in 5.0.31. For ESG 5.1 a fix has been released in 5.1.20. For ESG 5.2 a fix has been released in 5.2.31. For ESG 5.4 a fix has been releas…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-29*
