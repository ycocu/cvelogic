# Daily Threat Intelligence — January 26, 2026

**Digest window (UTC):** 2026-01-26
**Generated:** 2026-06-02T07:34:17Z

## Threat brief

SmarterTools SmarterMail: 2 CVEs added to CISA KEV today. · Xorux Lpar2rrd — exploitation likelihood rose sharply (EPSS 3.4% → 23% · rising (+19%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- SmarterTools SmarterMail: 2 CVEs added to CISA KEV today.
- Xorux Lpar2rrd — exploitation likelihood rose sharply (EPSS 3.4% → 23% · rising (+19%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 5 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2018-14634
**Linux Kernel Integer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** paloaltonetworks pan-os
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-27T15:55:15.890
- **CWE:** CWE-190
- **CWE:** CWE-190
- **Risk score:** 88
- **KEV:** added 2026-01-26

> An integer overflow flaw was found in the Linux kernel's create_elf_tables() function. An unprivileged local user with access to SUID (or otherwise privileged) binary could use this flaw to escalate their privileges on the system. Kernel versions 2.6.x, 3.10.x and 4.14.x are beli…

### CVE-2014-4982
**xorux lpar2rrd Command Injection**
- **Signals:** EPSS
- **Asset:** xorux lpar2rrd
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T02:11:13.223
- **CWE:** CWE-77
- **Risk score:** 86
- **EPSS 3.4% (2025-05-17) → 22.8% (2026-01-26), Δ +19.3%**

> LPAR2RRD ≤ 4.53 and ≤ 3.5 has arbitrary command injection on the application server.

### CVE-2016-15057
**apache continuum Command Injection**
- **Signals:** CVSS
- **Asset:** apache continuum
- **Attack:** Command Injection
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-27T20:29:50.263
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-26)

> ** UNSUPPORTED WHEN ASSIGNED ** Improper Neutralization of Special Elements used in a Command ('Command Injection') vulnerability in Apache Continuum.

This issue affects Apache Continuum: all versions.

Attackers with access to the installations REST API can use this to invoke a…

### CVE-2022-29775
**ispyconnect ispy**
- **Signals:** EPSS
- **Asset:** ispyconnect ispy
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:59:40.123
- **CWE:** CWE-287
- **Risk score:** 84
- **EPSS 52.8% (2025-11-21) → 63.9% (2026-01-26), Δ +11.1%**

> iSpyConnect iSpy v7.2.2.0 allows attackers to bypass authentication via a crafted URL.

### CVE-2022-35741
**apache cloudstack XXE**
- **Signals:** EPSS
- **Asset:** apache cloudstack
- **Attack:** XXE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:11:34.990
- **CWE:** CWE-611
- **Risk score:** 86
- **EPSS 19.4% (2025-11-21) → 34.4% (2026-01-26), Δ +15.0%**

> Apache CloudStack version 4.5.0 and later has a SAML 2.0 authentication Service Provider plugin which is found to be vulnerable to XML external entity (XXE) injection. This plugin is not enabled by default and the attacker would require that this plugin be enabled to exploit the …

### CVE-2025-52691
**SmarterTools SmarterMail Unrestricted Upload of File with Dangerous Type Vulnerability**
- **Signals:** KEV
- **Asset:** smartertools smartermail
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-27T15:28:07.247
- **CWE:** CWE-434
- **Risk score:** 88
- **KEV:** added 2026-01-26

> Successful exploitation of the vulnerability could allow an unauthenticated attacker to upload arbitrary files to any location on the mail server, potentially enabling remote code execution.

### CVE-2025-59091
**Multiple hardcoded credentials have been identified, which are allowed to sign-in to the exos 9300 datapoint server running on port 1004...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-26)

> Multiple hardcoded credentials have been identified, which are allowed to sign-in to the exos 9300 datapoint server running on port 1004 and 1005. This server is used for relaying status information from and to the Access Managers. This information, among other things, is used to…

### CVE-2025-59097
**The exos 9300 application can be used to configure Access Managers (e.g.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-26)

> The exos 9300 application can be used to configure Access Managers (e.g. 92xx, 9230 and 9290). The configuration is done in a graphical user interface on the dormakaba exos server. As soon as the save button is clicked in exos 9300, the whole configuration is sent to the selected…

### CVE-2025-59103
**The Access Manager 92xx in hardware revision K7 is based on Linux instead of Windows CE embedded in older hardware revisions.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1391
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-26)

> The Access Manager 92xx in hardware revision K7 is based on Linux instead of Windows CE embedded in older hardware revisions. In this new hardware revision it was noticed that an SSH service is exposed on port 22. By analyzing the firmware of the devices, it was noticed that ther…

### CVE-2025-59108
**By default, the password for the Access Manager's web interface, is set to 'admin'.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-26)

> By default, the password for the Access Manager's web interface, is set to 'admin'. In the tested version changing the password was not enforced.

### CVE-2025-70982
**bladex springblade privilege escalation**
- **Signals:** CVSS
- **Asset:** bladex springblade
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-12T15:43:24.207
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-26)

> Incorrect access control in the importUser function of SpringBlade v4.5.0 allows attackers with low-level privileges to arbitrarily import sensitive user data.

### CVE-2026-21509
**Microsoft Office Security Feature Bypass Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft 365_apps
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T15:40:33.473
- **CWE:** CWE-807
- **Risk score:** 88
- **KEV:** added 2026-01-26

> Reliance on untrusted inputs in a security decision in Microsoft Office allows an unauthorized attacker to bypass a security feature locally.

### CVE-2026-22696
**dcap-qvl implements the quote verification logic for DCAP (Data Center Attestation Primitives).**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-26)

> dcap-qvl implements the quote verification logic for DCAP (Data Center Attestation Primitives). A vulnerability present in versions prior to 0.3.9 involves a critical gap in the cryptographic verification process within the dcap-qvl. The library fetches QE Identity collateral (in…

### CVE-2026-22709
**vm2_project vm2**
- **Signals:** CVSS
- **Asset:** vm2_project vm2
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-17T20:59:29.590
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-26)

> vm2 is an open source vm/sandbox for Node.js. In vm2 prior to version 3.10.2, `Promise.prototype.then` `Promise.prototype.catch` callback sanitization can be bypassed. This allows attackers to escape the sandbox and run arbitrary code. In lib/setup-sandbox.js, the callback functi…

### CVE-2026-23760
**SmarterTools SmarterMail Authentication Bypass Using an Alternate Path or Channel Vulnerability**
- **Signals:** KEV
- **Asset:** smartertools smartermail
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-27T16:16:55.327
- **CWE:** CWE-288
- **Risk score:** 88
- **KEV:** added 2026-01-26

> SmarterTools SmarterMail versions prior to build 9511 contain an authentication bypass vulnerability in the password reset API. The force-reset-password endpoint permits anonymous requests and fails to verify the existing password or a reset token when resetting system administra…

### CVE-2026-24061
**GNU InetUtils Argument Injection Vulnerability**
- **Signals:** KEV
- **Asset:** gnu inetutils
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-11T15:40:42.937
- **CWE:** CWE-88
- **Risk score:** 88
- **KEV:** added 2026-01-26

> telnetd in GNU Inetutils through 2.7 allows remote authentication bypass via a "-f root" value for the USER environment variable.

### CVE-2026-24429
**tenda w30e_firmware**
- **Signals:** CVSS
- **Asset:** tenda w30e_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T13:01:22.300
- **CWE:** CWE-1393
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-26)

> Shenzhen Tenda W30E V2 firmware versions up to and including V16.01.0.19(5037) ship with a predefined default password for a built-in authentication account that is not required to be changed during initial configuration. An attacker can leverage these default credentials to gain…

### CVE-2026-24436
**tenda w30e_firmware**
- **Signals:** CVSS
- **Asset:** tenda w30e_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-28T19:57:17.200
- **CWE:** CWE-307
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-26)

> Shenzhen Tenda W30E V2 firmware versions up to and including V16.01.0.19(5037) do not enforce rate limiting or account lockout mechanisms on authentication endpoints. This allows attackers to perform unrestricted brute-force attempts against administrative credentials.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-26*
