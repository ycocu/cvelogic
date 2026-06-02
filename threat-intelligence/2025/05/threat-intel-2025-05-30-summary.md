# Daily Threat Intelligence — May 30, 2025

**Digest window (UTC):** 2025-05-30
**Generated:** 2026-06-02T07:32:48Z

## Threat brief

Adobe Air — exploitation likelihood rose sharply (EPSS 52% → 66% · rising (+14%)). · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- Adobe Air — exploitation likelihood rose sharply (EPSS 52% → 66% · rising (+14%)).
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **9** |


## CVEs

### CVE-2007-6019
**adobe air**
- **Signals:** EPSS
- **Asset:** adobe air
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 85
- **EPSS 52.3% (2025-03-30) → 66.2% (2025-05-30), Δ +13.9%**

> Adobe Flash Player 9.0.115.0 and earlier, and 8.0.39.0 and earlier, allows remote attackers to execute arbitrary code via an SWF file with a modified DeclareFunction2 Actionscript tag, which prevents an object from being instantiated properly.

### CVE-2020-36846
**A buffer overflow, as described in CVE-2020-8927, exists in the embedded Brotli library.**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-30)

> A buffer overflow, as described in CVE-2020-8927, exists in the embedded Brotli library.  Versions of IO::Compress::Brotli prior to 0.007 included a version of the brotli library prior to version 1.0.8, where an attacker controlling the input length of a "one-shot" decompression …

### CVE-2025-1907
**Instantel Micromate lacks authentication on a configuration port which could allow an attacker to execute commands if connected.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-30)

> Instantel Micromate lacks authentication on a configuration port which could allow an attacker to execute commands if connected.

### CVE-2025-2500
**A vulnerability exists in the SOAP Web services of the Asset Suite versions listed below.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-256
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-30)

> A vulnerability exists in the SOAP Web services of the Asset 
Suite versions listed below. If successfully exploited, an attacker 
could gain unauthorized access to the product and the time window of a possible password attack could be expanded.

### CVE-2025-41438
**The CS5000 Fire Panel is vulnerable due to a default account that exists on the panel.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1188
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-30)

> The CS5000 Fire Panel is vulnerable due to a default account that exists
 on the panel. Even though it is possible to change this by SSHing into 
the device, it has remained unchanged on every installed system 
observed. This account is not root but holds high-level permissions t…

### CVE-2025-44619
**tinxy wifi_lock_controller_v1_rf_firmware**
- **Signals:** CVSS
- **Asset:** tinxy wifi_lock_controller_v1_rf_firmware
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-22T14:28:05.700
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-30)

> Tinxy WiFi Lock Controller v1 RF was discovered to be configured to transmit on an open Wi-Fi network, allowing attackers to join the network without authentication.

### CVE-2025-46352
**The CS5000 Fire Panel is vulnerable due to a hard-coded password that runs on a VNC server and is visible as a string in the binary respo...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-30)

> The CS5000 Fire Panel is vulnerable due to a hard-coded password that 
runs on a VNC server and is visible as a string in the binary 
responsible for running VNC. This password cannot be altered, allowing 
anyone with knowledge of it to gain remote access to the panel. Such 
acce…

### CVE-2025-48757
**An insufficient database Row-Level Security policy in Lovable through 2025-04-15 allows remote unauthenticated attackers to read or write...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-30)

> An insufficient database Row-Level Security policy in Lovable through 2025-04-15 allows remote unauthenticated attackers to read or write to arbitrary database tables of generated sites. NOTE: this is disputed by the Supplier because each individual customer of the Lovable platfo…

### CVE-2025-48865
**fabiolb fabio**
- **Signals:** CVSS
- **Asset:** fabiolb fabio
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-04T19:54:41.613
- **CWE:** CWE-345
- **CWE:** CWE-345
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-30)

> Fabio is an HTTP(S) and TCP router for deploying applications managed by consul. Prior to version 1.6.6, Fabio allows clients to remove X-Forwarded headers (except X-Forwarded-For) due to a vulnerability in how it processes hop-by-hop headers. Fabio adds HTTP headers like X-Forwa…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-30*
