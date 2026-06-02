# Daily Threat Intelligence — June 13, 2025

**Digest window (UTC):** 2025-06-13
**Generated:** 2026-06-02T07:32:52Z

## Threat brief

Freefloat Ftp Server: public exploit or PoC linked (Buffer Overflow) · Microsoft Windows 2003 Server — exploitation likelihood rose sharply (EPSS 8.0% → 31% · rising (+23%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Freefloat Ftp Server: public exploit or PoC linked (Buffer Overflow)
- Microsoft Windows 2003 Server — exploitation likelihood rose sharply (EPSS 8.0% → 31% · rising (+23%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 3 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2025-49113
**RoundCube Webmail Deserialization of Untrusted Data Vulnerability**
- **Signals:** EXP
- **Asset:** roundcube webmail
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T13:24:21.387
- **CWE:** CWE-502
- **CWE:** CWE-502
- **Risk score:** 78
- **EXP:** ref published 2025-06-13

> Roundcube Webmail before 1.5.10 and 1.6.x before 1.6.11 allows remote code execution by authenticated users because the _from parameter in a URL is not validated in program/actions/settings/upload.php, leading to PHP Object Deserialization.

### CVE-2025-5548
**freefloat freefloat_ftp_server Buffer Overflow**
- **Signals:** EXP
- **Asset:** freefloat freefloat_ftp_server
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-24T15:21:00.730
- **CWE:** CWE-119
- **Risk score:** 78
- **EXP:** ref published 2025-06-13

> A vulnerability, which was classified as critical, was found in FreeFloat FTP Server 1.0. Affected is an unknown function of the component NOOP Command Handler. The manipulation leads to buffer overflow. It is possible to launch the attack remotely. The exploit has been disclosed…

### CVE-2003-0839
**microsoft windows_2003_server Directory Traversal**
- **Signals:** EPSS
- **Asset:** microsoft windows_2003_server
- **Attack:** Directory Traversal
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 8.0% (2025-03-30) → 31.3% (2025-06-13), Δ +23.3%**

> Directory traversal vulnerability in the "Shell Folders" capability in Microsoft Windows Server 2003 allows remote attackers to read arbitrary files via .. (dot dot) sequences in a "shell:" link.

### CVE-2025-24071
**microsoft windows_10_1507**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-03T13:23:25.997
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2025-06-13

> Exposure of sensitive information to an unauthorized actor in Windows File Explorer allows an unauthorized attacker to perform spoofing over a network.

### CVE-2025-28384
**openc3 cosmos Directory Traversal**
- **Signals:** CVSS
- **Asset:** openc3 cosmos
- **Attack:** Directory Traversal
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2025-10-27T16:15:39.347
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-13)

> An issue in the /script-api/scripts/ endpoint of OpenC3 COSMOS before 6.1.0 allows attackers to execute a directory traversal.

### CVE-2025-28386
**openc3 cosmos RCE**
- **Signals:** CVSS
- **Asset:** openc3 cosmos
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-23T14:06:04.657
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-13)

> A remote code execution (RCE) vulnerability in the Plugin Management component of OpenC3 COSMOS v6.0.0 allows attackers to execute arbitrary code via uploading a crafted .txt file.

### CVE-2025-28388
**openc3 cosmos**
- **Signals:** CVSS
- **Asset:** openc3 cosmos
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-10-27T16:15:39.513
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-13)

> OpenC3 COSMOS before v6.0.2 was discovered to contain hardcoded credentials for the Service Account.

### CVE-2025-28389
**openc3 cosmos**
- **Signals:** CVSS
- **Asset:** openc3 cosmos
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-17T19:42:06.507
- **CWE:** CWE-521
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-13)

> Weak password requirements in OpenC3 COSMOS v6.0.0 allow attackers to bypass authentication via a brute force attack.

### CVE-2025-45987
**b-link bl-ac2100_az3_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** b-link bl-wr9000_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-10T12:16:05.020
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-13)

> Blink routers BL-WR9000 V2.4.9 , BL-AC2100_AZ3 V1.0.4, BL-X10_AC8 v1.0.5 , BL-LTE300 v1.2.3, BL-F1200_AT1 v1.0.0, BL-X26_AC8 v1.2.8, BLAC450M_AE4 v4.0.0 and BL-X26_DA3 v1.2.7 were discovered to contain multiple command injection vulnerabilities via the dns1 and dns2 parameters in…

### CVE-2025-45988
**b-link bl-ac1900_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** b-link bl-wr9000_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-10T12:16:15.107
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-13)

> Blink routers BL-WR9000 V2.4.9 , BL-AC2100_AZ3 V1.0.4, BL-X10_AC8 v1.0.5 , BL-LTE300 v1.2.3, BL-F1200_AT1 v1.0.0, BL-X26_AC8 v1.2.8, BLAC450M_AE4 v4.0.0 and BL-X26_DA3 v1.2.7 were discovered to contain multiple command injection vulnerabilities via the cmd parameter in the bs_Set…

### CVE-2025-46060
**totolink n600r_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** totolink n600r_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-16T14:58:41.900
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-13)

> Buffer Overflow vulnerability in TOTOLINK N600R v4.3.0cu.7866_B2022506 allows a remote attacker to execute arbitrary code via the UPLOAD_FILENAME component

### CVE-2025-49596
**The MCP inspector is a developer tool for testing and debugging MCP servers.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-06-13)

> The MCP inspector is a developer tool for testing and debugging MCP servers. Versions of MCP Inspector below 0.14.1 are vulnerable to remote code execution due to lack of authentication between the Inspector client and proxy, allowing unauthenticated requests to launch MCP comman…

### CVE-2025-6029
**Use of fixed learning codes, one code to lock the car and the other code to unlock it, the Key Fob Transmitter in KIA-branded Aftermarket...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-294
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-06-13)

> Use of fixed learning codes, one code to lock the car and the other code to unlock it, the Key Fob Transmitter in KIA-branded Aftermarket Generic Smart  Keyless Entry System, primarily distributed in Ecuador, which allows a replay attack.

Manufacture is unknown at the time of re…

### CVE-2025-6030
**Use of fixed learning codes, one code to lock the car and the other code to unlock it, in the Key Fob Transmitter in Cyclone Matrix TRF S...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-294
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-06-13)

> Use of fixed learning codes, one code to lock the car and the other code to unlock it, in the Key Fob Transmitter in Cyclone Matrix TRF Smart  Keyless Entry System, which allows a replay attack.

Research was completed on the 2024 KIA Soluto.  Attack confirmed on other KIA Models…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-13*
