# Daily Threat Intelligence — June 23, 2026

**Digest window (US Eastern, NVD):** 2026-06-23
**Generated:** 2026-06-29T10:33:10Z

## Threat brief

Ubiquiti UniFi OS: 3 CVEs added to CISA KEV today. · Oracle PeopleSoft Enterprise PeopleTools — exploitation likelihood rose sharply (EPSS 7.5% → 90% · rising (+82%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Ubiquiti UniFi OS: 3 CVEs added to CISA KEV today.
- Oracle PeopleSoft Enterprise PeopleTools — exploitation likelihood rose sharply (EPSS 7.5% → 90% · rising (+82%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 4 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **24** |


## CVEs

### CVE-2025-67038
**Lantronix EDS5000 Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** lantronix eds5032_firmware
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-03-11
- **NVD modified:** 2026-06-24
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2026-06-23

> An issue was discovered in Lantronix EDS5000 2.1.0.0R3. The HTTP RPC module executes a shell command to write logs when user's authantication fails. The username is directly concatenated with the command without any sanitization. This allow attackers to inject arbitrary OS comman…

### CVE-2026-35273
**Oracle PeopleSoft Enterprise PeopleTools Missing Authentication for Critical Function Vulnerability**
- **Signals:** EPSS
- **Asset:** oracle peoplesoft_enterprise_peopletools
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-06-11
- **NVD modified:** 2026-06-17
- **CWE:** CWE-306
- **Risk score:** 86
- **EPSS 7.5% (2026-06-19) → 89.8% (2026-06-23), Δ +82.3%**

> Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Updates Environment Management). Supported versions that are affected are 8.61 and 8.62. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP t…

### CVE-2026-55255
**langflow langflow**
- **Signals:** CVSS
- **Asset:** langflow langflow
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD published:** 2026-06-23
- **NVD modified:** 2026-06-24
- **CWE:** CWE-639
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-23)

> Langflow is a tool for building and deploying AI-powered agents and workflows. Prior to 1.9.2, an Insecure Direct Object Reference (IDOR) vulnerability in /api/v1/responses endpoint allows an authenticated attacker to execute any flow belonging to another user by specifying the v…

### CVE-2025-34291
**Langflow Origin Validation Error Vulnerability**
- **Signals:** EPSS
- **Asset:** langflow langflow
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD published:** 2025-12-05
- **NVD modified:** 2026-06-17
- **CWE:** CWE-346
- **Risk score:** 85
- **EPSS 25.2% (2026-06-15) → 78.9% (2026-06-23), Δ +53.7%**

> Langflow versions up to and including 1.6.9 contain a chained vulnerability that enables account takeover and remote code execution. An overly permissive CORS configuration (allow_origins='*' with allow_credentials=True) combined with a refresh token cookie configured as SameSite…

### CVE-2026-0257
**Palo Alto Networks PAN-OS Authentication Bypass Vulnerability**
- **Signals:** EPSS
- **Asset:** paloaltonetworks pan-os
- **Attack:** Auth Bypass
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD published:** 2026-05-13
- **NVD modified:** 2026-06-17
- **CWE:** CWE-565
- **Risk score:** 83
- **EPSS 18.6% (2026-06-15) → 86.7% (2026-06-23), Δ +68.1%**

> Authentication bypass vulnerabilities in the GlobalProtect portal and gateway of Palo Alto Networks PAN-OS® software allows the attacker to bypass security restrictions and establish an unauthorized VPN connection.

Panorama and Cloud NGFW are not impacted by these issues.

### CVE-2026-11807
**A missing authorization vulnerability was found in the Event-Driven Ansible (EDA) websocket API.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Awaiting Analysis
- **NVD published:** 2026-06-23
- **NVD modified:** 2026-06-27
- **CWE:** CWE-862
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-23)

> A missing authorization vulnerability was found in the Event-Driven Ansible (EDA) websocket API. The /api/eda/ws/ansible-rulebook endpoint does not verify user permissions when processing Worker messages. Any authenticated user can send a forged message with an arbitrary activati…

### CVE-2026-2041
**nagios nagios_xi RCE**
- **Signals:** EPSS
- **Asset:** nagios nagios_xi
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD published:** 2026-02-20
- **NVD modified:** 2026-06-17
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 5.5% (2026-06-15) → 74.6% (2026-06-23), Δ +69.1%**

> Nagios Host zabbixagent_configwizard_func Command Injection Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of Nagios Host. Authentication is required to exploit this vulnerability.

The specific …

### CVE-2026-26980
**ghost ghost**
- **Signals:** EPSS
- **Asset:** ghost ghost
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD published:** 2026-02-19
- **NVD modified:** 2026-06-17
- **CWE:** CWE-89
- **Risk score:** 85
- **EPSS 16.5% (2026-06-15) → 70.0% (2026-06-23), Δ +53.5%**

> Ghost is a Node.js content management system. Versions 3.24.0 through 6.19.0 allow unauthenticated attackers to perform arbitrary reads from the database. This issue has been fixed in version 6.19.1.

### CVE-2026-32202
**Microsoft Windows Protection Mechanism Failure Vulnerability**
- **Signals:** EPSS
- **Asset:** microsoft windows_10_1607
- **CVSS max:** 4.3
- **NVD status:** Analyzed
- **NVD published:** 2026-04-14
- **NVD modified:** 2026-06-17
- **CWE:** CWE-693
- **Risk score:** 77
- **EPSS 20.0% (2026-06-15) → 64.1% (2026-06-23), Δ +44.1%**

> Protection mechanism failure in Windows Shell allows an unauthorized attacker to perform spoofing over a network.

### CVE-2026-34908
**Ubiquiti UniFi OS Improper Access Control Vulnerability**
- **Signals:** KEV
- **Asset:** ui unifi_os_server
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD published:** 2026-05-21
- **NVD modified:** 2026-06-24
- **CWE:** CWE-284
- **Risk score:** 88
- **KEV:** added 2026-06-23

> A malicious actor with access to the network could exploit an Improper Access Control vulnerability found in UniFi OS devices to make unauthorized changes to the system.

### CVE-2026-34909
**Ubiquiti UniFi OS Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** ui unifi_os_server
- **Attack:** Path Traversal
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD published:** 2026-05-21
- **NVD modified:** 2026-06-24
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2026-06-23

> A malicious actor with access to the network could exploit a Path Traversal vulnerability found in UniFi OS devices to access files on the underlying system that could be manipulated to access an underlying account.

### CVE-2026-34910
**Ubiquiti UniFi OS Improper Input Validation Vulnerability**
- **Signals:** KEV
- **Asset:** ui unifi_os_server
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD published:** 2026-05-21
- **NVD modified:** 2026-06-24
- **CWE:** CWE-20
- **Risk score:** 88
- **KEV:** added 2026-06-23

> A malicious actor with access to the network could exploit an Improper Input Validation vulnerability found in UniFi OS devices to execute a Command Injection.

### CVE-2026-45498
**Microsoft Defender Denial of Service Vulnerability**
- **Signals:** EPSS
- **Asset:** microsoft defender_antimalware_platform
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD published:** 2026-05-20
- **NVD modified:** 2026-06-17
- **CWE:** CWE-400
- **Risk score:** 77
- **EPSS 2.5% (2026-06-15) → 63.1% (2026-06-23), Δ +60.6%**

> Microsoft Defender Denial of Service Vulnerability

### CVE-2026-48519
**langflow langflow RCE**
- **Signals:** CVSS
- **Asset:** langflow langflow
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD published:** 2026-06-23
- **NVD modified:** 2026-06-26
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-23)

> Langflow is a tool for building and deploying AI-powered agents and workflows. Prior to 1.9.2, the "Shareable Playground" (or "Public Flows" in code) contains a critical RCE vulnerability. Shareable Playground feature works by enabling the execution of workflows by unauthenticate…

### CVE-2026-48907
**Widget Factory Joomla Content Editor Improper Access Control Vulnerability**
- **Signals:** EPSS
- **Asset:** widgetfactorylimited jce
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD published:** 2026-06-05
- **NVD modified:** 2026-06-17
- **CWE:** CWE-284
- **Risk score:** 86
- **EPSS 6.9% (2026-06-18) → 80.4% (2026-06-23), Δ +73.6%**

> A vulnerability in the JCE editor extension for Joomla allows the creation of new editor profiles for unauthenticated users, ultimately resulting in PHP code upload and execution.

### CVE-2026-49160
**microsoft windows_10_1607**
- **Signals:** EPSS
- **Asset:** microsoft windows_10_1607
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD published:** 2026-06-09
- **NVD modified:** 2026-06-17
- **CWE:** CWE-400
- **Risk score:** 82
- **EPSS 1.0% (2026-06-15) → 48.4% (2026-06-23), Δ +47.5%**

> Uncontrolled resource consumption in HTTP/2 allows an unauthorized attacker to deny service over a network.

### CVE-2026-53662
**immich is a high performance self-hosted photo and video management solution.**
- **Signals:** CVSS
- **Attack:** XSS
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD published:** 2026-06-23
- **NVD modified:** 2026-06-25
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-23)

> immich is a high performance self-hosted photo and video management solution. From commit 4ffa26c9 until 4eb1003, a reflected cross-site scripting (XSS) vulnerability on the /auth/login page allows an attacker to fully compromise any authenticated user's account with a single lin…

### CVE-2026-53753
**Crawl4AI is an open-source LLM friendly web crawler & scraper.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD published:** 2026-06-23
- **NVD modified:** 2026-06-23
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-23)

> Crawl4AI is an open-source LLM friendly web crawler & scraper. Prior to 0.8.7, the _safe_eval_expression() function in the computed fields feature uses an AST validator that only blocks attributes starting with underscore. Python generator and frame object attributes (gi_frame, f…

### CVE-2026-54157
**LobeHub is a work-and-lifestyle space to find, build, and collaborate with agent teammates that grow with you.**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Deferred
- **NVD published:** 2026-06-23
- **NVD modified:** 2026-06-25
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-06-23)

> LobeHub is a work-and-lifestyle space to find, build, and collaborate with agent teammates that grow with you. Prior to 2.1.57, the /webapi/proxy endpoint on app.lobehub.com accepts a URL in the POST body and fetches it server-side without any authentication. An attacker can use …

### CVE-2026-54257
**Electron is a framework for writing cross-platform desktop applications using JavaScript, HTML and CSS.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD published:** 2026-06-23
- **NVD modified:** 2026-06-25
- **CWE:** CWE-120
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-23)

> Electron is a framework for writing cross-platform desktop applications using JavaScript, HTML and CSS. From 42.3.1 until 42.3.3, Buffer performs incorrect byte length calculations resulting in heap buffer under/overflow. Most apps will crash and some may perform incorrect buffer…

### CVE-2026-54588
**Poweradmin is a web-based DNS administration tool for PowerDNS server.**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD published:** 2026-06-23
- **NVD modified:** 2026-06-25
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-23)

> Poweradmin is a web-based DNS administration tool for PowerDNS server. Versions prior to 4.2.4 and 4.3.3 use the attacker-controlled `HTTP_HOST` request header as the authoritative source for building callback URLs in its OIDC, SAML, and logout authentication flows without any va…

### CVE-2026-55447
**langflow langflow**
- **Signals:** CVSS
- **Asset:** langflow langflow
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD published:** 2026-06-23
- **NVD modified:** 2026-06-24
- **CWE:** CWE-61
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-23)

> Langflow is a tool for building and deploying AI-powered agents and workflows. Prior to 1.9.2, by controlling a files that are digested into the RAG, an attacker can direct the node to read any file on the file-system by absolute path. All components based on BaseFileComponent ar…

### CVE-2026-55450
**langflow langflow**
- **Signals:** CVSS
- **Asset:** langflow langflow
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD published:** 2026-06-23
- **NVD modified:** 2026-06-24
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-23)

> Langflow is a tool for building and deploying AI-powered agents and workflows. Prior to 1.9.1, unauthenticated users can upload any amount of data to the server without any limitations. No need for any prior knowledge, only network access to Langflow. This can lead to space exhau…

### CVE-2026-9082
**Drupal Core SQL Injection Vulnerability**
- **Signals:** EPSS
- **Asset:** drupal drupal
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-05-20
- **NVD modified:** 2026-06-17
- **CWE:** CWE-89
- **Risk score:** 86
- **EPSS 33.7% (2026-06-15) → 84.6% (2026-06-23), Δ +51.0%**

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Drupal Drupal core allows SQL Injection.

This issue affects Drupal core: from 8.9.0 before 10.4.10, from 10.5.0 before 10.5.10, from 10.6.0 before 10.6.9, from 11.0.0 before 11.…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-23*
