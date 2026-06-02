# Daily Threat Intelligence — November 21, 2025

**Digest window (UTC):** 2025-11-21
**Generated:** 2026-06-02T07:33:49Z

## Threat brief

Oracle Fusion Middleware added to CISA KEV — confirmed in-the-wild exploitation. · WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Get-simple Getsimplecms — exploitation likelihood rose sharply (EPSS 7.7% → 68% · rising (+61%)). · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- Oracle Fusion Middleware added to CISA KEV — confirmed in-the-wild exploitation.
- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Get-simple Getsimplecms — exploitation likelihood rose sharply (EPSS 7.7% → 68% · rising (+61%)).
- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **17** |


## CVEs

### CVE-2025-61757
**Oracle Fusion Middleware Missing Authentication for Critical Function Vulnerability**
- **Signals:** KEV
- **Asset:** oracle identity_manager
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-24T13:38:20.900
- **CWE:** CWE-306
- **Risk score:** 88
- **KEV:** added 2025-11-21

> Vulnerability in the Identity Manager product of Oracle Fusion Middleware (component: REST WebServices).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromi…

### CVE-2023-46042
**get-simple getsimplecms**
- **Signals:** EPSS
- **Asset:** get-simple getsimplecms
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:27:47.787
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 7.7% (2025-11-18) → 68.2% (2025-11-21), Δ +60.5%**

> An issue in GetSimpleCMS v.3.4.0a allows a remote attacker to execute arbitrary code via a crafted payload to the phpinfo().

### CVE-2025-41115
**grafana grafana**
- **Signals:** CVSS
- **Asset:** grafana grafana
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-08T16:39:45.290
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-21)

> SCIM provisioning was introduced in Grafana Enterprise and Grafana Cloud in April to improve how organizations manage users and teams in Grafana by introducing automated user lifecycle management.

In Grafana versions 12.x where SCIM provisioning is enabled and configured, a vuln…

### CVE-2023-38124
**inductiveautomation ignition RCE**
- **Signals:** EPSS
- **Asset:** inductiveautomation ignition
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-03-13T21:45:10.853
- **CWE:** CWE-749
- **Risk score:** 84
- **EPSS 2.8% (2025-11-18) → 53.8% (2025-11-21), Δ +51.0%**

> Inductive Automation Ignition OPC UA Quick Client Task Scheduling Exposed Dangerous Function Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of Inductive Automation Ignition. Authentication is req…

### CVE-2023-39141
**ziahamza webui-aria2 Path Traversal**
- **Signals:** EPSS
- **Asset:** ziahamza webui-aria2
- **Attack:** Path Traversal
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:14:47.597
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 31.4% (2025-11-18) → 85.6% (2025-11-21), Δ +54.2%**

> webui-aria2 commit 4fe2e was discovered to contain a path traversal vulnerability.

### CVE-2023-41474
**ivanti avalanche Directory Traversal**
- **Signals:** EPSS
- **Asset:** ivanti avalanche
- **Attack:** Directory Traversal
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2025-06-12T15:15:32.130
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 81
- **EPSS 28.7% (2025-11-18) → 74.9% (2025-11-21), Δ +46.2%**

> Directory Traversal vulnerability in Ivanti Avalanche 6.3.4.153 allows a remote authenticated attacker to obtain sensitive information via the javax.faces.resource component.

### CVE-2023-44959
**dlink dsl-3782_firmware**
- **Signals:** EPSS
- **Asset:** dlink dsl-3782_firmware
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:26:09.550
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 84
- **EPSS 2.1% (2025-11-18) → 47.1% (2025-11-21), Δ +45.0%**

> An issue found in D-Link DSL-3782 v.1.03 and before allows remote authenticated users to execute arbitrary code as root via the Router IP Address fields of the network settings page.

### CVE-2023-46474
**sigb pmb privilege escalation**
- **Signals:** EPSS
- **Asset:** sigb pmb
- **Attack:** privilege escalation
- **CVSS max:** 7.2
- **NVD status:** Modified
- **NVD modified:** 2025-06-03T15:15:42.350
- **CWE:** CWE-434
- **CWE:** CWE-434
- **Risk score:** 82
- **EPSS 16.9% (2025-11-18) → 72.7% (2025-11-21), Δ +55.8%**

> File Upload vulnerability PMB v.7.4.8 allows a remote attacker to execute arbitrary code and escalate privileges via a crafted PHP file uploaded to the start_import.php file.

### CVE-2023-48085
**nagios nagios_xi RCE**
- **Signals:** EPSS
- **Asset:** nagios nagios_xi
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-05-22T18:15:29.367
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 13.2% (2025-11-18) → 62.4% (2025-11-21), Δ +49.2%**

> Nagios XI before version 5.11.3 was discovered to contain a remote code execution (RCE) vulnerability via the component command_test.php.

### CVE-2023-6016
**h2o h2o RCE**
- **Signals:** EPSS
- **Asset:** h2o h2o
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:42:59.160
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 8.6% (2025-11-18) → 68.2% (2025-11-21), Δ +59.6%**

> An attacker is able to gain remote code execution on a server hosting the H2O dashboard through it's POJO model import feature.

### CVE-2024-25869
**codeastro membership_management_system**
- **Signals:** EPSS
- **Asset:** codeastro membership_management_system
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-04-01T15:26:52.227
- **CWE:** CWE-434
- **Risk score:** 84
- **EPSS 5.6% (2025-11-18) → 56.0% (2025-11-21), Δ +50.5%**

> An Unrestricted File Upload vulnerability in CodeAstro Membership Management System in PHP v.1.0 allows a remote attacker to execute arbitrary code via upload of a crafted php file in the settings.php component.

### CVE-2024-5247
**netgear prosafe_network_management_system RCE**
- **Signals:** EPSS
- **Asset:** netgear prosafe_network_management_system
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-02-11T17:29:12.660
- **CWE:** CWE-434
- **CWE:** CWE-434
- **Risk score:** 84
- **EPSS 5.4% (2025-11-18) → 58.1% (2025-11-21), Δ +52.8%**

> NETGEAR ProSAFE Network Management System UpLoadServlet Unrestricted File Upload Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of NETGEAR ProSAFE Network Management System. Authentication is req…

### CVE-2025-11127
**The Mstoreapp Mobile App WordPress plugin through 2.08 and Mstoreapp Mobile Multivendor through 9.0.1 do not properly verify users identi...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-21)

> The Mstoreapp Mobile App WordPress plugin through 2.08 and Mstoreapp Mobile Multivendor through 9.0.1 do not properly verify users identify when using an AJAX action, allowing unauthenticated users to retrieve a valid session for arbitrary users by knowing their email address.

### CVE-2025-11456
**elula wsdesk RCE**
- **Signals:** CVSS
- **Asset:** elula wsdesk
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-26T16:51:45.093
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-11-21)

> The ELEX WordPress HelpDesk & Customer Ticketing System plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the eh_crm_new_ticket_post() function in all versions up to, and including, 3.3.1. This makes it possible for unauthenticate…

### CVE-2025-64310
**EPSON WebConfig and Epson Web Control for SEIKO EPSON Projector Products do not restrict excessive authentication attempts.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-307
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-11-21)

> EPSON WebConfig and Epson Web Control for SEIKO EPSON Projector Products do not restrict excessive authentication attempts. An administrative user's password may be identified through a brute force attack.

### CVE-2025-64767
**hpke-js is a Hybrid Public Key Encryption (HPKE) module built on top of Web Cryptography API.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-323
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-11-21)

> hpke-js is a Hybrid Public Key Encryption (HPKE) module built on top of Web Cryptography API. Prior to version 1.7.5, the public SenderContext Seal() API has a race condition which allows for the same AEAD nonce to be re-used for multiple Seal() calls. This can lead to complete l…

### CVE-2025-65108
**md-to-pdf is a CLI tool for converting Markdown files to PDF using Node.js and headless Chrome.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-11-21)

> md-to-pdf is a CLI tool for converting Markdown files to PDF using Node.js and headless Chrome. Prior to version 5.2.5, a Markdown front-matter block that contains JavaScript delimiter causes the JS engine in gray-matter library to execute arbitrary code in the Markdown to PDF co…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-11-21*
