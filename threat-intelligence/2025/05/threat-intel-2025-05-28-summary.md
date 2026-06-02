# Daily Threat Intelligence — May 28, 2025

**Digest window (UTC):** 2025-05-28
**Generated:** 2026-06-02T07:32:47Z

## Threat brief

Digium Asterisk — exploitation likelihood rose sharply (EPSS 10.0% → 31% · rising (+21%)). · 7 new critical disclosures — review patch status on exposed services.

## Executive summary

- Digium Asterisk — exploitation likelihood rose sharply (EPSS 10.0% → 31% · rising (+21%)).
- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **8** |


## CVEs

### CVE-2009-2726
**digium asterisk**
- **Signals:** EPSS
- **Asset:** digium asterisk
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-770
- **Risk score:** 83
- **EPSS 10.0% (2025-03-30) → 30.7% (2025-05-28), Δ +20.7%**

> The SIP channel driver in Asterisk Open Source 1.2.x before 1.2.34, 1.4.x before 1.4.26.1, 1.6.0.x before 1.6.0.12, and 1.6.1.x before 1.6.1.4; Asterisk Business Edition A.x.x, B.x.x before B.2.5.9, C.2.x before C.2.4.1, and C.3.x before C.3.1; and Asterisk Appliance s800i 1.2.x …

### CVE-2025-22252
**fortinet fortios Auth Bypass**
- **Signals:** CVSS
- **Asset:** fortinet fortiproxy
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-04T14:35:38.543
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-28)

> A missing authentication for critical function in Fortinet FortiProxy versions 7.6.0 through 7.6.1, FortiSwitchManager version 7.2.5, and FortiOS versions 7.4.4 through 7.4.6 and version 7.6.0 may allow an attacker with knowledge of an existing admin account to access the device …

### CVE-2025-3357
**ibm tivoli_monitoring**
- **Signals:** CVSS
- **Asset:** ibm tivoli_monitoring
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-09T18:56:33.710
- **CWE:** CWE-1285
- **CWE:** CWE-129
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-28)

> IBM Tivoli Monitoring 6.3.0.7 through 6.3.0.7 Service Pack 19 could allow a remote attacker to execute arbitrary code due to improper validation of an index value of a dynamically allocated array.

### CVE-2025-27528
**apache inlong Deserialization**
- **Signals:** CVSS
- **Asset:** apache inlong
- **Attack:** Deserialization
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-03T15:36:47.120
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-28)

> Deserialization of Untrusted Data vulnerability in Apache InLong.

This issue affects Apache InLong: from 1.13.0 through 2.1.0. 

This
vulnerability allows attackers to bypass the security mechanisms of InLong
JDBC and leads to arbitrary file reading. Users are advised to upgrade…

### CVE-2025-4009
**The Evertz SDVN 3080ipx-10G is a High Bandwidth Ethernet Switching Fabric for Video Application.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-28)

> The Evertz SDVN 3080ipx-10G is a High Bandwidth Ethernet Switching Fabric for Video Application. This device exposes a web management interface on port 80. This web management interface can be used by administrators to control product
features, setup network switching, and regist…

### CVE-2025-45343
**tenda w18e_firmware**
- **Signals:** CVSS
- **Asset:** tenda w18e_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-03T15:36:32.347
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-28)

> An issue in Tenda W18E v.2.0 v.16.01.0.11 allows an attacker to execute arbitrary code via the editing functionality of the account module in the goform/setmodules route.

### CVE-2025-48749
**netwrix directory_manager**
- **Signals:** CVSS
- **Asset:** netwrix directory_manager
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-18T23:59:44.600
- **CWE:** CWE-201
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-28)

> Netwrix Directory Manager (formerly Imanami GroupID) v11.0.0.0 and before & after v.11.1.25134.03 inserts Sensitive Information into Sent Data.

### CVE-2025-5277
**aws-mcp-server MCP server is vulnerable to command injection.**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-05-28)

> aws-mcp-server MCP server is vulnerable to command injection. An attacker can craft a prompt that once accessed by the MCP client will run arbitrary commands on the host system.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-28*
