# Daily Threat Intelligence — July 23, 2025

**Digest window (UTC):** 2025-07-23
**Generated:** 2026-06-02T07:33:06Z

## Threat brief

Open-emr Openemr — exploitation likelihood rose sharply (EPSS 2.4% → 18% · rising (+15%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Open-emr Openemr — exploitation likelihood rose sharply (EPSS 2.4% → 18% · rising (+15%)).
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

### CVE-2022-2494
**open-emr openemr XSS**
- **Signals:** EPSS
- **Asset:** open-emr openemr
- **Attack:** XSS
- **CVSS max:** 6.3
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:01:06.830
- **CWE:** CWE-79
- **Risk score:** 79
- **EPSS 2.4% (2025-04-16) → 17.9% (2025-07-23), Δ +15.4%**

> Cross-site Scripting (XSS) - Stored in GitHub repository openemr/openemr prior to 7.0.0.

### CVE-2025-41687
**An unauthenticated remote attacker may use a stack based buffer overflow in the u-link Management API to gain full access on the affected...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-23)

> An unauthenticated remote attacker may use a stack based buffer overflow in the u-link Management API to gain full access on the affected devices.

### CVE-2015-10141
**An unauthenticated OS command injection vulnerability exists within Xdebug versions 2.5.5 and earlier, a PHP debugging extension develope...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-23)

> An unauthenticated OS command injection vulnerability exists within Xdebug versions 2.5.5 and earlier, a PHP debugging extension developed by Derick Rethans. When remote debugging is enabled, Xdebug listens on port 9000 and accepts debugger protocol commands without authenticatio…

### CVE-2016-15044
**A remote code execution vulnerability exists in Kaltura versions prior to 11.1.0-2 due to unsafe deserialization of user-controlled data...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-23)

> A remote code execution vulnerability exists in Kaltura versions prior to 11.1.0-2 due to unsafe deserialization of user-controlled data within the keditorservices module. An unauthenticated remote attacker can exploit this issue by sending a specially crafted serialized PHP obje…

### CVE-2017-20198
**The Marathon UI in DC/OS < 1.9.0 allows unauthenticated users to deploy arbitrary Docker containers.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-732
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-23)

> The Marathon UI in DC/OS < 1.9.0 allows unauthenticated users to deploy arbitrary Docker containers. Due to improper restriction of volume mount configurations, attackers can deploy a container that mounts the host's root filesystem (/) with read/write privileges. When using a ma…

### CVE-2018-25114
**A remote code execution vulnerability exists within osCommerce Online Merchant version 2.3.4.1 due to insecure default configuration and...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-23)

> A remote code execution vulnerability exists within osCommerce Online Merchant version 2.3.4.1 due to insecure default configuration and missing authentication in the installer workflow. By default, the /install/ directory remains accessible after installation. An unauthenticated…

### CVE-2022-4978
**Remote Control Server, maintained by Steppschuh, 3.1.1.12 allows unauthenticated remote code execution when authentication is disabled, w...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-23)

> Remote Control Server, maintained by Steppschuh, 3.1.1.12 allows unauthenticated remote code execution when authentication is disabled, which is the default configuration. The server exposes a custom UDP-based control protocol that accepts remote keyboard input events without ver…

### CVE-2025-40599
**sonicwall sma_210_firmware RCE**
- **Signals:** CVSS
- **Asset:** sonicwall sma_210_firmware
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T16:41:11.763
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-23)

> An authenticated arbitrary file upload vulnerability exists in the SMA 100 series web management interface. A remote attacker with administrative privileges can exploit this flaw to upload arbitrary files to the system, potentially leading to remote code execution.

### CVE-2025-54294
**A SQLi vulnerability in Komento component 4.0.0-4.0.7for Joomla was discovered.**
- **Signals:** CVSS
- **Attack:** SQL injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-23)

> A SQLi vulnerability in Komento component 4.0.0-4.0.7for Joomla was discovered. The issue allows unprivileged users to execute arbitrary SQL commands.

### CVE-2025-54455
**samsung magicinfo_9_server Auth Bypass**
- **Signals:** CVSS
- **Asset:** samsung magicinfo_9_server
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-28T17:25:40.427
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-23)

> Use of Hard-coded Credentials vulnerability in Samsung Electronics MagicINFO 9 Server allows Authentication Bypass.This issue affects MagicINFO 9 Server: less than 21.1080.0.

### CVE-2025-8070
**The Windows service configuration of ABP and AES contains an unquoted ImagePath registry value vulnerability.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-428
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-07-23)

> The Windows service configuration of ABP and AES contains an unquoted ImagePath registry value vulnerability. This allows a local attacker to execute arbitrary code by placing a malicious executable in a predictable location such as C:\Program.exe. If the service runs with elevat…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-23*
