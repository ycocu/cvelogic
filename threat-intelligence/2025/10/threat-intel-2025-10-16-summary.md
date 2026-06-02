# Daily Threat Intelligence — October 16, 2025

**Digest window (UTC):** 2025-10-16
**Generated:** 2026-06-02T07:33:36Z

## Threat brief

Avtech Avn801 Dvr Firmware — exploitation likelihood rose sharply (EPSS 4.0% → 40% · rising (+36%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Avtech Avn801 Dvr Firmware — exploitation likelihood rose sharply (EPSS 4.0% → 40% · rising (+36%)).
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

### CVE-2013-4982
**avtech avn801_dvr_firmware**
- **Signals:** EPSS
- **Asset:** avtech avn801_dvr_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T01:56:50.597
- **CWE:** CWE-287
- **Risk score:** 86
- **EPSS 4.0% (2025-08-24) → 39.6% (2025-10-16), Δ +35.6%**

> AVTECH AVN801 DVR has a security bypass via the administration login captcha

### CVE-2025-10611
**wso2 api_control_plane privilege escalation**
- **Signals:** CVSS
- **Asset:** wso2 api_control_plane
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-21T21:38:23.433
- **CWE:** CWE-863
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-16)

> Due to an insufficient access control implementation in multiple WSO2 Products, authentication and authorization checks for certain REST APIs can be bypassed, allowing them to be invoked without proper validation.

Successful exploitation of this vulnerability could lead to a mal…

### CVE-2025-54539
**apache activemq_nms_amqp RCE**
- **Signals:** CVSS
- **Asset:** apache activemq_nms_amqp
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T22:16:28.940
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-16)

> A Deserialization of Untrusted Data vulnerability exists in the Apache ActiveMQ NMS AMQP Client.

This issue affects all versions of Apache ActiveMQ NMS AMQP up to and including 2.3.0, when establishing connections to untrusted AMQP servers. Malicious servers could exploit unboun…

### CVE-2025-11492
**connectwise automate**
- **Signals:** CVSS
- **Asset:** connectwise automate
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-29T19:33:29.790
- **CWE:** CWE-319
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-10-16)

> In the ConnectWise Automate Agent, communications could be configured to use HTTP instead of HTTPS. In such cases, an on-path threat actor with a man-in-the-middle network position could intercept, modify, or replay agent-server traffic. Additionally, the encryption method used t…

### CVE-2025-34513
**ilevia eve_x1_server_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** ilevia eve_x1_server_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-23T19:28:18.870
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-16)

> Ilevia EVE X1 Server firmware versions ≤ 4.7.18.0.eden contain an OS command injection vulnerability in mbus_build_from_csv.php that allows an unauthenticated attacker to execute arbitrary code. Ilevia has declined to service this vulnerability, and recommends that customers not …

### CVE-2025-34515
**ilevia eve_x1_server_firmware privilege escalation**
- **Signals:** CVSS
- **Asset:** ilevia eve_x1_server_firmware
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-06T19:15:41.510
- **CWE:** CWE-250
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-16)

> Ilevia EVE X1 Server firmware versions ≤ 4.7.18.0.eden contain an execution with unnecessary privileges vulnerability in sync_project.sh that allows an attacker to escalate privileges to root. Ilevia has declined to service this vulnerability, and recommends that customers not ex…

### CVE-2025-34516
**ilevia eve_x1_server_firmware**
- **Signals:** CVSS
- **Asset:** ilevia eve_x1_server_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T19:15:52.317
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-16)

> Ilevia EVE X1 Server firmware versions ≤ 4.7.18.0.eden contain a use of default credentials vulnerability that allows an unauthenticated attacker to obtain remote access. Ilevia has declined to service this vulnerability, and recommends that customers not expose port 8080 to the …

### CVE-2025-61922
**prestashop prestashop_checkout**
- **Signals:** CVSS
- **Asset:** prestashop prestashop_checkout
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-29T20:06:13.033
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-16)

> PrestaShop Checkout is the PrestaShop official payment module in partnership with PayPal. Starting in version 1.3.0 and prior to versions 4.4.1 and 5.0.5, missing validation on the Express Checkout feature allows silent login, enabling account takeover via email. The vulnerabilit…

### CVE-2025-6338
**There is an incomplete cleanup vulnerability in Qt Network's Schannel support on Windows which can lead to a Denial of Service over a lon...**
- **Signals:** CVSS
- **Attack:** DoS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-459
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-10-16)

> There is an incomplete cleanup vulnerability in Qt Network's Schannel support on Windows which can lead to a Denial of Service over a long period.This issue affects Qt from 5.15.0 through 6.8.3, from 6.9.0 before 6.9.2.

### CVE-2025-9152
**wso2 api_control_plane privilege escalation**
- **Signals:** CVSS
- **Asset:** wso2 api_control_plane
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-21T18:33:41.413
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-16)

> An improper privilege management vulnerability exists in WSO2 API Manager due to missing authentication and authorization checks in the keymanager-operations Dynamic Client Registration (DCR) endpoint.

A malicious user can exploit this flaw to generate access tokens with elevate…

### CVE-2025-9804
**wso2 api_control_plane privilege escalation**
- **Signals:** CVSS
- **Asset:** wso2 api_control_plane
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-21T21:40:09.890
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-10-16)

> An improper access control vulnerability exists in multiple WSO2 products due to insufficient permission enforcement in certain internal SOAP Admin Services and System REST APIs. A low-privileged user may exploit this flaw to perform unauthorized operations, including accessing s…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-16*
