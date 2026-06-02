# Daily Threat Intelligence — May 22, 2026

**Digest window (UTC):** 2026-05-22
**Generated:** 2026-06-02T07:04:05Z

## Threat brief

Drupal Core added to CISA KEV — confirmed in-the-wild exploitation. · Grafana — exploitation likelihood rose sharply (EPSS 17% → 51% · rising (+34%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Drupal Core added to CISA KEV — confirmed in-the-wild exploitation.
- Grafana — exploitation likelihood rose sharply (EPSS 17% → 51% · rising (+34%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **21** |


## CVEs

### CVE-2026-9082
**Drupal Core SQL Injection Vulnerability**
- **Signals:** KEV
- **Asset:** Drupal Core
- **Attack:** SQL Injection
- **CVSS max:** 6.5
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T15:24:25.330
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 88
- **KEV:** added 2026-05-22

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Drupal Drupal core allows SQL Injection.

This issue affects Drupal core: from 8.9.0 before 10.4.10, from 10.5.0 before 10.5.10, from 10.6.0 before 10.6.9, from 11.0.0 before 11.…

### CVE-2022-32276
**grafana grafana**
- **Signals:** EPSS
- **Asset:** grafana grafana
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:06:05.250
- **CWE:** CWE-287
- **Risk score:** 82
- **EPSS 17.0% (2026-05-02) → 50.8% (2026-05-22), Δ +33.8%**

> Grafana 8.4.3 allows unauthenticated access via (for example) a /dashboard/snapshot/*?orgId=0 URI. NOTE: the vendor considers this a UI bug, not a vulnerability

### CVE-2026-23652
**microsoft power_pages Command Injection**
- **Signals:** CVSS
- **Asset:** microsoft power_pages
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T17:01:18.480
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-22)

> Improper neutralization of special elements used in a command ('command injection') in Microsoft Power Pages allows an unauthorized attacker to execute code over a network.

### CVE-2006-5526
**fully_modded_phpbb fully_modded_phpbb**
- **Signals:** EPSS
- **Asset:** fully_modded_phpbb fully_modded_phpbb
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 80
- **EPSS 8.3% (2026-03-08) → 19.3% (2026-05-22), Δ +11.0%**

> Multiple PHP remote file inclusion vulnerabilities in Teake Nutma Foing, as modified in Fully Modded phpBB (phpbbfm) 2021.4.40 and earlier, allow remote attackers to execute arbitrary PHP code via a URL in the foing_root_path parameter in (a) faq.php, (b) index.php, (c) list.php,…

### CVE-2006-5527
**intelimen intelieditor**
- **Signals:** EPSS
- **Asset:** intelimen intelieditor
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 82
- **EPSS 20.8% (2025-09-09) → 34.0% (2026-05-22), Δ +13.1%**

> PHP remote file inclusion vulnerability in lib.editor.inc.php in Intelimen InteliEditor 1.2.x allows remote attackers to execute arbitrary PHP code via a URL in the sys_path parameter.

### CVE-2006-5647
**sophos anti-virus DoS**
- **Signals:** EPSS
- **Asset:** sophos anti-virus
- **Attack:** DoS
- **CVSS max:** 6.4
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 79
- **EPSS 17.3% (2026-05-16) → 28.5% (2026-05-22), Δ +11.2%**

> Sophos Anti-Virus and Endpoint Security before 6.0.5, Anti-Virus for Linux before 5.0.10, and other platforms before 4.11 allows remote attackers to cause a denial of service (memory corruption) and possibly execute arbitrary code via a malformed CHM file with a large name length…

### CVE-2017-9417
**broadcom bcm43xx_wi-fi_chipset_firmware**
- **Signals:** EPSS
- **Asset:** broadcom bcm43xx_wi-fi_chipset_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **Risk score:** 84
- **EPSS 31.4% (2026-02-26) → 42.6% (2026-05-22), Δ +11.2%**

> Broadcom BCM43xx Wi-Fi chips allow remote attackers to execute arbitrary code via unspecified vectors, aka the "Broadpwn" issue.

### CVE-2019-10744
**f5 active_iq_unified_manager**
- **Signals:** EPSS
- **Asset:** lodash lodash
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:19:50.123
- **CWE:** CWE-1321
- **Risk score:** 84
- **EPSS 3.2% (2026-05-10) → 14.8% (2026-05-22), Δ +11.7%**

> Versions of lodash lower than 4.17.12 are vulnerable to Prototype Pollution. The function defaultsDeep could be tricked into adding or modifying properties of Object.prototype using a constructor payload.

### CVE-2021-24916
**themeum qubely**
- **Signals:** EPSS
- **Asset:** themeum qubely
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:54:00.430
- **Risk score:** 82
- **EPSS 29.5% (2026-05-21) → 43.7% (2026-05-22), Δ +14.1%**

> The Qubely WordPress plugin before 1.8.6 allows unauthenticated user to send arbitrary e-mails to arbitrary addresses via the qubely_send_form_data AJAX action.

### CVE-2022-0735
**gitlab gitlab Info Disclosure**
- **Signals:** EPSS
- **Asset:** gitlab gitlab
- **Attack:** Info Disclosure
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:39:17.353
- **Risk score:** 86
- **EPSS 57.4% (2026-03-04) → 71.3% (2026-05-22), Δ +14.0%**

> An issue has been discovered in GitLab CE/EE affecting all versions starting from 12.10 before 14.6.5, all versions starting from 14.7 before 14.7.4, all versions starting from 14.8 before 14.8.2. An unauthorised user was able to steal runner registration tokens through an inform…

### CVE-2025-1361
**ip2location country_blocker**
- **Signals:** EPSS
- **Asset:** ip2location country_blocker
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-03-06T19:02:18.897
- **CWE:** CWE-285
- **CWE:** CWE-862
- **Risk score:** 80
- **EPSS 8.3% (2026-04-23) → 19.1% (2026-05-22), Δ +10.9%**

> The IP2Location Country Blocker plugin for WordPress is vulnerable to Regular Information Exposure in all versions up to, and including, 2.38.8 due to missing capability checks on the admin_init() function. This makes it possible for unauthenticated attackers to view the plugin's…

### CVE-2026-32253
**lizardbyte sunshine**
- **Signals:** CVSS
- **Asset:** lizardbyte sunshine
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-26T14:43:27.510
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-22)

> Sunshine is a self-hosted game stream host for Moonlight. In versions prior to 2026.516.143833, the client-certificate authentication can be bypassed because of how OpenSSL verification results are handled. In src/crypto.cpp, the custom verify callback treats X509_V_ERR_UNABLE_TO…

### CVE-2026-33843
**microsoft entra_id Auth Bypass**
- **Signals:** CVSS
- **Asset:** microsoft entra_id
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T16:50:43.063
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-05-22)

> Authentication bypass using an alternate path or channel in Microsoft Azure Active Directory B2C allows an unauthorized attacker to elevate privileges over a network.

### CVE-2026-40411
**microsoft azure_virtual_network_gateway**
- **Signals:** CVSS
- **Asset:** microsoft azure_virtual_network_gateway
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T16:47:30.840
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-05-22)

> Improper input validation in Azure Virtual Network Gateway allows an authorized attacker to execute code over a network.

### CVE-2026-40412
**microsoft azure_orbital_spatio**
- **Signals:** CVSS
- **Asset:** microsoft azure_orbital_spatio
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T16:37:15.763
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-22)

> Unrestricted upload of file with dangerous type in Azure Orbital Spatio allows an unauthorized attacker to execute code over a network.

### CVE-2026-41090
**microsoft 365_copilot Command Injection**
- **Signals:** CVSS
- **Asset:** microsoft 365_copilot
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T18:23:00.457
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-22)

> Improper neutralization of special elements used in a command ('command injection') in Microsoft Copilot allows an unauthorized attacker to perform tampering over a network.

### CVE-2026-41104
**microsoft planetary_computer Deserialization**
- **Signals:** CVSS
- **Asset:** microsoft planetary_computer
- **Attack:** Deserialization
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-29T19:46:59.147
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-22)

> Deserialization of untrusted data in Microsoft Planetary Computer Pro allows an unauthorized attacker to disclose information over a network.

### CVE-2026-42208
**BerriAI LiteLLM SQL Injection Vulnerability**
- **Signals:** EPSS
- **Asset:** litellm litellm
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T19:19:34.537
- **CWE:** CWE-89
- **Risk score:** 83
- **EPSS 43.2% (2026-05-14) → 54.3% (2026-05-22), Δ +11.1%**

> LiteLLM is a proxy server (AI Gateway) to call LLM APIs in OpenAI (or native) format. From version 1.81.16 to before version 1.83.7, a database query used during proxy API key checks mixed the caller-supplied key value into the query text instead of passing it as a separate param…

### CVE-2026-42901
**microsoft entra_id privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft entra_id
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T12:13:01.730
- **CWE:** CWE-346
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-22)

> Origin validation error in Microsoft Entra ID allows an unauthorized attacker to elevate privileges over a network.

### CVE-2026-47280
**microsoft azure_resource_manager privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft azure_resource_manager
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T16:14:33.873
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-22)

> Improper authentication in Azure Resource Manager (ARM) allows an unauthorized attacker to elevate privileges over a network.

### CVE-2026-48700
**An issue was discovered in all versions of PCManFM-Qt starting from 1.1.0.**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-24T20:16:43.040
- **CWE:** CWE-913
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-22)

> An issue was discovered in all versions of PCManFM-Qt starting from 1.1.0. When a regular file's path is passed as a URI in an org.freedesktop.FileManager1.ShowFolders D-Bus method call, PCManFM-Qt delegates to a different program (based on the file type) without user confirmatio…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-22*
