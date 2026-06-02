# Daily Threat Intelligence — February 08, 2026

**Digest window (UTC):** 2026-02-08
**Generated:** 2026-06-02T07:34:22Z

## Threat brief

Novell Netware — exploitation likelihood rose sharply (EPSS 11% → 25% · rising (+14%)).

## Executive summary

- Novell Netware — exploitation likelihood rose sharply (EPSS 11% → 25% · rising (+14%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 1 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2010-2351
**novell netware Buffer Overflow**
- **Signals:** EPSS
- **Asset:** novell netware
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 11.3% (2025-11-12) → 25.0% (2026-02-08), Δ +13.7%**

> Stack-based buffer overflow in the CIFS.NLM driver in Netware SMB 1.0 for Novell Netware 6.5 SP8 and earlier allows remote attackers to execute arbitrary code via a Sessions Setup AndX packet with a long AccountName.

### CVE-2021-31181
**microsoft sharepoint_enterprise_server RCE**
- **Signals:** EPSS
- **Asset:** microsoft sharepoint_enterprise_server
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2025-02-28T21:15:17.397
- **CWE:** CWE-94
- **Risk score:** 84
- **EPSS 28.3% (2025-12-31) → 40.7% (2026-02-08), Δ +12.4%**

> Microsoft SharePoint Remote Code Execution Vulnerability

### CVE-2025-15027
**The JAY Login & Register plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 2.6.03.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-08)

> The JAY Login & Register plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 2.6.03. This is due to the plugin allowing a user to update arbitrary user meta through the 'jay_login_register_ajax_create_final_user' function. This makes i…

### CVE-2022-48107
**dlink dir_878_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** dlink dir_878_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-03-28T16:15:24.193
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 9.8% (2026-02-01) → 21.9% (2026-02-08), Δ +12.1%**

> D-Link DIR_878_FW1.30B08 was discovered to contain a command injection vulnerability via the component /setnetworksettings/IPAddress. This vulnerability allows attackers to escalate privileges to root via a crafted payload.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-08*
