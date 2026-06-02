# Daily Threat Intelligence — June 04, 2025

**Digest window (UTC):** 2025-06-04
**Generated:** 2026-06-02T07:32:49Z

## Threat brief

Mailenable Enterprise — exploitation likelihood rose sharply (EPSS 9.7% → 27% · rising (+17%)). · 7 new critical disclosures — review patch status on exposed services.

## Executive summary

- Mailenable Enterprise — exploitation likelihood rose sharply (EPSS 9.7% → 27% · rising (+17%)).
- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **9** |


## CVEs

### CVE-2005-1013
**mailenable mailenable_enterprise DoS**
- **Signals:** EPSS
- **Asset:** mailenable mailenable_enterprise
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 9.7% (2025-03-30) → 27.2% (2025-06-04), Δ +17.4%**

> The SMTP service in MailEnable Enterprise 1.04 and earlier and Professional 1.54 and earlier allows remote attackers to cause a denial of service (server crash) via an EHLO command with a Unicode string.

### CVE-2021-42884
**totolink ex1200t_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** totolink ex1200t_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:28:16.100
- **CWE:** CWE-78
- **Risk score:** 86
- **EPSS 6.4% (2025-03-30) → 21.8% (2025-06-04), Δ +15.4%**

> TOTOLINK EX1200T V4.1.2cu.5215 contains a remote command injection vulnerability in function setDeviceName of the file global.so which can control thedeviceName to attack.

### CVE-2025-5597
**Improper Authentication vulnerability in WF Steuerungstechnik GmbH airleader MASTER allows Authentication Bypass.This issue affects airle...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-04)

> Improper Authentication vulnerability in WF Steuerungstechnik GmbH airleader MASTER allows Authentication Bypass.This issue affects airleader MASTER: 3.00571.

### CVE-2024-13967
**This vulnerability allows the successful attacker to gain unauthorized access to a configuration web page delivered by the integrated web...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-384
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-06-04)

> This vulnerability allows the successful attacker to gain unauthorized access to a 
configuration web page delivered by the integrated web Server of EIBPORT.

This issue affects EIBPORT V3 KNX: through 3.9.8; EIBPORT V3 KNX GSM: through 3.9.8.

### CVE-2025-20286
**cisco identity_services_engine**
- **Signals:** CVSS
- **Asset:** cisco identity_services_engine
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-15T17:58:47.640
- **CWE:** CWE-259
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-06-04)

> A vulnerability in Amazon Web Services (AWS), Microsoft Azure, and Oracle Cloud Infrastructure (OCI) cloud deployments of Cisco Identity Services Engine (ISE) could allow an unauthenticated, remote attacker to access sensitive data, execute limited administrative operations, modi…

### CVE-2025-4578
**dimdavid file_provider SQL Injection**
- **Signals:** CVSS
- **Asset:** dimdavid file_provider
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-04T20:07:45.857
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-04)

> The File Provider WordPress plugin through 1.2.3 does not properly sanitise and escape a parameter before using it in a SQL statement via an AJAX action available to unauthenticated users, leading to a SQL injection

### CVE-2025-49223
**naver billboard.js DoS**
- **Signals:** CVSS
- **Asset:** naver billboard.js
- **Attack:** DoS
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-06T19:30:16.060
- **CWE:** CWE-1321
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-04)

> billboard.js before 3.15.1 was discovered to contain a prototype pollution via the function generate, which could allow attackers to execute arbitrary code or cause a Denial of Service (DoS) via injecting arbitrary properties.

### CVE-2025-5598
**Path Traversal vulnerability in WF Steuerungstechnik GmbH airleader MASTER allows Retrieve Embedded Sensitive Data.This issue affects air...**
- **Signals:** CVSS
- **Attack:** Path Traversal
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-35
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-06-04)

> Path Traversal vulnerability in WF Steuerungstechnik GmbH airleader MASTER allows Retrieve Embedded Sensitive Data.This issue affects airleader MASTER: 3.0046.

### CVE-2025-5600
**totolink ex1200t_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** totolink ex1200t_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-10T15:09:46.277
- **CWE:** CWE-119
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-04)

> A vulnerability, which was classified as critical, has been found in TOTOLINK EX1200T 4.1.2cu.5232_B20210713. This issue affects the function setLanguageCfg of the file /cgi-bin/cstecgi.cgi. The manipulation of the argument LangType leads to stack-based buffer overflow. The attac…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-04*
