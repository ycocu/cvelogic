# Daily Threat Intelligence — January 21, 2026

**Digest window (UTC):** 2026-01-21
**Generated:** 2026-06-02T07:34:14Z

## Threat brief

Cisco Unified Communications Manager added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cisco Unified Communications Manager added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2026-20045
**Cisco Unified Communications Products Code Injection Vulnerability**
- **Signals:** KEV
- **Asset:** cisco unified_communications_manager
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-13T21:37:06.717
- **CWE:** CWE-94
- **Risk score:** 88
- **KEV:** added 2026-01-21

> A vulnerability in Cisco Unified Communications Manager (Unified CM), Cisco Unified Communications Manager Session Management Edition (Unified CM SME), Cisco Unified Communications Manager IM &amp; Presence Service (Unified CM IM&amp;P), Cisco Unity Connection, and Cisco Webex Ca…

### CVE-2025-69762
**tenda ax3_firmware RCE**
- **Signals:** CVSS
- **Asset:** tenda ax3_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-26T20:38:07.200
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-21)

> Tenda AX3 firmware v16.03.12.11 contains a stack overflow in formSetIptv via the list parameter, which can cause memory corruption and enable remote code execution.

### CVE-2025-69763
**tenda ax3_firmware RCE**
- **Signals:** CVSS
- **Asset:** tenda ax3_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-26T20:37:36.303
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-21)

> Tenda AX3 firmware v16.03.12.11 contains a stack overflow in formSetIptv via the vlanId parameter, which can cause memory corruption and enable remote code execution.

### CVE-2021-47748
**hasura graphql_engine RCE**
- **Signals:** CVSS
- **Asset:** hasura graphql_engine
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T18:11:25.673
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-21)

> Hasura GraphQL 1.3.3 contains a remote code execution vulnerability that allows attackers to execute arbitrary shell commands through SQL query manipulation. Attackers can inject commands into the run_sql endpoint by crafting malicious GraphQL queries that execute system commands…

### CVE-2021-47851
**yodinfo mini_mouse RCE**
- **Signals:** CVSS
- **Asset:** yodinfo mini_mouse
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T17:29:10.470
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-21)

> Mini Mouse 9.2.0 contains a remote code execution vulnerability that allows attackers to execute arbitrary commands through an unauthenticated HTTP endpoint. Attackers can leverage the /op=command endpoint to download and execute payloads by sending crafted JSON requests with mal…

### CVE-2025-69766
**tenda ax3_firmware RCE**
- **Signals:** CVSS
- **Asset:** tenda ax3_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-26T20:38:30.877
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-21)

> Tenda AX3 firmware v16.03.12.11 contains a stack-based buffer overflow in the formGetIptv function due to improper handling of the citytag stack buffer, which may result in memory corruption and remote code execution.

### CVE-2026-22792
**5ire 5ire**
- **Signals:** CVSS
- **Asset:** 5ire 5ire
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T19:46:50.240
- **CWE:** CWE-116
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-01-21)

> 5ire is a cross-platform desktop artificial intelligence assistant and model context protocol client. Prior to version 0.15.3, an unsafe HTML rendering permits untrusted HTML (including on* event attributes) to execute in the renderer context. An attacker can inject an `<img oner…

### CVE-2026-22793
**5ire 5ire RCE**
- **Signals:** CVSS
- **Asset:** 5ire 5ire
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T19:58:16.513
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-01-21)

> 5ire is a cross-platform desktop artificial intelligence assistant and model context protocol client. Prior to version 0.15.3, an unsafe option parsing vulnerability in the ECharts Markdown plugin allows any user able to submit ECharts code blocks to execute arbitrary JavaScript …

### CVE-2026-22822
**external-secrets external_secrets_operator**
- **Signals:** CVSS
- **Asset:** external-secrets external_secrets_operator
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T15:29:01.850
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-21)

> External Secrets Operator reads information from a third-party service and automatically injects the values as Kubernetes Secrets.  Starting in version 0.20.2 and prior to version 1.2.0, the `getSecretKey` template function, while introduced for senhasegura Devops Secrets Managem…

### CVE-2026-23518
**fleetdm fleet**
- **Signals:** CVSS
- **Asset:** fleetdm fleet
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T16:14:59.390
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-21)

> Fleet is open source device management software. In versions prior to 4.78.3, 4.77.1, 4.76.2, 4.75.2, and 4.53.3, a vulnerability in Fleet's Windows MDM enrollment flow could allow an attacker to submit forged authentication tokens that are not properly validated. Because JWT sig…

### CVE-2026-23524
**laravel reverb RCE**
- **Signals:** CVSS
- **Asset:** laravel reverb
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T20:02:37.250
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-21)

> Laravel Reverb provides a real-time WebSocket communication backend for Laravel applications. In versions 1.6.3 and below, Reverb passes data from the Redis channel directly into PHP’s unserialize() function without restricting which classes can be instantiated, which leaves user…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-21*
