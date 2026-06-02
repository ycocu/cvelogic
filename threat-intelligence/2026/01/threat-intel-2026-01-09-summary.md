# Daily Threat Intelligence — January 09, 2026

**Digest window (UTC):** 2026-01-09
**Generated:** 2026-06-02T07:34:09Z

## Threat brief

Limbo Cms — exploitation likelihood rose sharply (EPSS 9.0% → 19% · rising (+10%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Limbo Cms — exploitation likelihood rose sharply (EPSS 9.0% → 19% · rising (+10%)).
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

### CVE-2006-1662
**limbo_cms limbo_cms**
- **Signals:** EPSS
- **Asset:** limbo_cms limbo_cms
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 80
- **EPSS 9.0% (2025-06-21) → 19.3% (2026-01-09), Δ +10.2%**

> The frontpage option in Limbo CMS 1.0.4.2 and 1.0.4.1 allows remote attackers to execute arbitrary PHP commands via the Itemid parameter in index.php.

### CVE-2025-64093
**zenitel icx500_firmware RCE**
- **Signals:** CVSS
- **Asset:** zenitel icx500_firmware
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-10T20:33:36.620
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-09)

> Remote Code Execution vulnerability that allows unauthenticated attackers to inject arbitrary commands into the hostname of the device.

### CVE-2025-69425
**The Ruckus vRIoT IoT Controller firmware versions prior to 3.0.0.0 (GA) expose a command execution service on TCP port 2004 running with...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T14:34:27.800
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-09)

> The Ruckus vRIoT IoT Controller firmware versions prior to 3.0.0.0 (GA) expose a command execution service on TCP port 2004 running with root privileges. Authentication to this service relies on a hardcoded Time-based One-Time Password (TOTP) secret and an embedded static token. …

### CVE-2020-36875
**AccessAlly WordPress plugin versions prior to 3.3.2 contain an unauthenticated arbitrary PHP code execution vulnerability in the Login Wi...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-09)

> AccessAlly WordPress plugin versions prior to 3.3.2 contain an unauthenticated arbitrary PHP code execution vulnerability in the Login Widget. The plugin processes the login_error parameter as PHP code, allowing an attacker to supply and execute arbitrary PHP in the context of th…

### CVE-2025-14598
**cloudilyaerp bet_e-portal SQL Injection**
- **Signals:** CVSS
- **Asset:** cloudilyaerp bet_e-portal
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-10T20:29:35.070
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-09)

> BeeS Software Solutions BET Portal contains an SQL injection vulnerability in the login functionality of affected sites. The vulnerability enables arbitrary SQL commands to be executed on the backend database.

### CVE-2025-66050
**vivotek ip7137_firmware**
- **Signals:** CVSS
- **Asset:** vivotek ip7137_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-14T17:48:29.730
- **CWE:** CWE-1393
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-09)

> Vivotek IP7137 camera with firmware version 0200a by default dos not require to provide any password when logging in as an administrator. While it is possible to set up such a password, a user is not informed about such a need.
The vendor has not replied to the CNA. Possibly all …

### CVE-2025-69426
**The Ruckus vRIoT IoT Controller firmware versions prior to 3.0.0.0 (GA) contain hardcoded credentials for an operating system user accoun...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T14:34:27.800
- **CWE:** CWE-732
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-09)

> The Ruckus vRIoT IoT Controller firmware versions prior to 3.0.0.0 (GA) contain hardcoded credentials for an operating system user account within an initialization script. The SSH service is network-accessible without IP-based restrictions. Although the configuration disables SCP…

### CVE-2025-69542
**dlink dir-895la1_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** dlink dir-895la1_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-10T19:48:29.113
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-09)

> A Command Injection Vulnerability has been discovered in the DHCP daemon service of D-Link DIR895LA1 v102b07. The vulnerability exists in the lease renewal processing logic where the DHCP hostname parameter is directly concatenated into a system command without proper sanitizatio…

### CVE-2025-70161
**edimax br-6208ac_firmware RCE**
- **Signals:** CVSS
- **Asset:** edimax br-6208ac_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-22T20:45:13.620
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-09)

> EDIMAX BR-6208AC V2_1.02 is vulnerable to Command Injection. This arises because the pppUserName field is directly passed to a shell command via the system() function without proper sanitization. An attacker can exploit this by injecting malicious commands into the pppUserName fi…

### CVE-2025-7072
**The firmware in KAON CG3000TC and CG3000T routers contains hard-coded credentials in clear text (shared across all routers of this model)...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-09)

> The firmware in KAON CG3000TC and CG3000T routers contains hard-coded credentials in clear text (shared across all routers of this model) that an unauthenticated remote attacker could use to execute commands with root privileges.
This vulnerability has been fixed in firmware vers…

### CVE-2026-22584
**salesforce uni2ts**
- **Signals:** CVSS
- **Asset:** salesforce uni2ts
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-22T21:48:05.130
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-09)

> Improper Control of Generation of Code ('Code Injection') vulnerability in Salesforce Uni2TS on MacOS, Windows, Linux allows Leverage Executable Code in Non-Executable Files.This issue affects Uni2TS: through 1.2.0.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-09*
