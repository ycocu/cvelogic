# Daily Threat Intelligence — February 24, 2026

**Digest window (UTC):** 2026-02-24
**Generated:** 2026-06-02T07:34:30Z

## Threat brief

Soliton Systems K.K FileZen added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Soliton Systems K.K FileZen added to CISA KEV — confirmed in-the-wild exploitation.
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

### CVE-2026-25108
**Soliton Systems K.K FileZen OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** soliton filezen
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-24T21:38:18.607
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2026-02-24

> FileZen contains an OS command injection vulnerability. When FileZen Antivirus Check Option is enabled, a logged-in user may send a specially crafted HTTP request to execute an arbitrary OS command.

### CVE-2026-26222
**beyond altec_doclink**
- **Signals:** CVSS
- **Asset:** beyond altec_doclink
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T20:05:06.970
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-24)

> Altec DocLink (now maintained by Beyond Limits Inc.) version 4.0.336.0 exposes insecure .NET Remoting endpoints over TCP and HTTP/SOAP via Altec.RDCHostService.exe using the ObjectURI "doclinkServer.soap". The service does not require authentication and is vulnerable to unsafe ob…

### CVE-2025-69985
**frangoteam fuxa RCE**
- **Signals:** CVSS
- **Asset:** frangoteam fuxa
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T19:39:20.677
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-24)

> FUXA 1.2.8 and prior contains an Authentication Bypass vulnerability leading to Remote Code Execution (RCE). The vulnerability exists in the server/api/jwt-helper.js middleware, which improperly trusts the HTTP "Referer" header to validate internal requests. A remote unauthentica…

### CVE-2026-21410
**insat masterscada RCE**
- **Signals:** CVSS
- **Asset:** insat masterscada
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T03:13:28.340
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-24)

> InSAT MasterSCADA BUK-TS is susceptible to SQL Injection through its main web interface. Malicious users that use the vulnerable endpoint are potentially able to cause remote code execution.

### CVE-2026-22553
**insat masterscada RCE**
- **Signals:** CVSS
- **Asset:** insat masterscada
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T03:15:54.487
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-24)

> All versions of InSAT MasterSCADA BUK-TS are susceptible to OS command injection through a field in its MMadmServ web interface. Malicious users that use the vulnerable endpoint are potentially able to cause remote code execution.

### CVE-2026-26341
**tattile anpr_mobile_firmware**
- **Signals:** CVSS
- **Asset:** tattile smart\+_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T17:31:23.003
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-24)

> Tattile Smart+, Vega, and Basic device families firmware versions 1.181.5 and prior ship with default credentials that are not forced to be changed during installation or commissioning. An attacker who can reach the management interface can authenticate using the default credenti…

### CVE-2026-27208
**bleon-ethical api-gateway-deploy Privilege Escalation**
- **Signals:** CVSS
- **Asset:** bleon-ethical api-gateway-deploy
- **Attack:** Privilege Escalation
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T20:11:29.340
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-24)

> bleon-ethical/api-gateway-deploy provides API gateway deployment. Version 1.0.0 is vulnerable to an attack chain involving OS Command Injection and Privilege Escalation. This allows an attacker to execute arbitrary commands with root privileges within the container, potentially l…

### CVE-2026-27507
**binardat 10g08-0800gsm_firmware**
- **Signals:** CVSS
- **Asset:** binardat 10g08-0800gsm_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-25T17:05:34.330
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-24)

> Binardat 10G08-0800GSM network switch firmware version V300SP10260209 and prior contain hard-coded administrative credentials that cannot be changed by users. Knowledge of these credentials allows full administrative access to the device.

### CVE-2026-27515
**binardat 10g08-0800gsm_firmware**
- **Signals:** CVSS
- **Asset:** binardat 10g08-0800gsm_firmware
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-25T17:25:03.020
- **CWE:** CWE-330
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-24)

> Binardat 10G08-0800GSM network switch firmware versions prior to V300SP10260209 generate predictable numeric session identifiers in the web management interface. An attacker can guess valid session IDs and hijack authenticated sessions.

### CVE-2026-27584
**actualbudget actual**
- **Signals:** CVSS
- **Asset:** actualbudget actual
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T19:46:14.007
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-24)

> Actual is a local-first personal finance tool. Prior to version 26.2.1, missing authentication middleware in the ActualBudget server component allows any unauthenticated user to query the SimpleFIN and Pluggy.ai integration endpoints and read sensitive bank account balance and tr…

### CVE-2026-27593
**statamic statamic**
- **Signals:** CVSS
- **Asset:** statamic statamic
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-25T20:27:52.497
- **CWE:** CWE-640
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-24)

> Statmatic is a Laravel and Git powered content management system (CMS). Prior to versions 6.3.3 and 5.73.10, an attacker may leverage a vulnerability in the password reset feature to capture a user's token and reset the password on their behalf. The attacker must know the email a…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-24*
