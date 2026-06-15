# Daily Threat Intelligence — June 13, 2026

**Digest window (UTC):** 2026-06-13
**Generated:** 2026-06-15T14:09:47Z

## Threat brief

Powerproduction Storyboard Quick — exploitation likelihood rose sharply (EPSS 30% → 51% · rising (+20%)).

## Executive summary

- Powerproduction Storyboard Quick — exploitation likelihood rose sharply (EPSS 30% → 51% · rising (+20%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **6** |


## CVEs

### CVE-2011-5172
**powerproduction storyboard_quick Buffer Overflow**
- **Signals:** EPSS
- **Asset:** powerproduction storyboard_quick
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 30.3% (2026-05-17) → 50.8% (2026-06-13), Δ +20.5%**

> Stack-based buffer overflow in StoryBoard Quick 6 Build 3786, and possibly StoryBoard Artist and StoryBoard Studio, allows remote attackers to execute arbitrary code via a long string in the string element field in a frame xml file.

### CVE-2023-30198
**webbax winbizpayment**
- **Signals:** EPSS
- **Asset:** webbax winbizpayment
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2025-01-06T18:15:14.143
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 5.7% (2026-03-07) → 20.7% (2026-06-13), Δ +15.0%**

> Prestashop winbizpayment <= 1.0.2 is vulnerable to Incorrect Access Control via modules/winbizpayment/downloads/download.php.

### CVE-2026-11624
**The Model Context Protocol has a security warning advising servers to validate the "Origin" header on all incoming connections to prevent...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Received
- **NVD modified:** 2026-06-13T10:16:17.700
- **CWE:** CWE-346
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-06-13)

> The Model Context Protocol has a security warning advising servers to validate the "Origin" header on all incoming connections to prevent DNS rebinding attacks. Prior to the v0.25.0 release, users had no way to validate the origin's host. In v0.25.0, a new "--allowed-hosts" flag …

### CVE-2016-8706
**memcached memcached RCE**
- **Signals:** EPSS
- **Asset:** memcached memcached
- **Attack:** RCE
- **CVSS max:** 8.1
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-190
- **Risk score:** 83
- **EPSS 60.3% (2026-06-04) → 73.7% (2026-06-13), Δ +13.4%**

> An integer overflow in process_bin_sasl_auth function in Memcached, which is responsible for authentication commands of Memcached binary protocol, can be abused to cause heap overflow and lead to remote code execution.

### CVE-2018-8284
**microsoft .net_framework RCE**
- **Signals:** EPSS
- **Asset:** microsoft .net_framework
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:13:32.907
- **CWE:** CWE-94
- **Risk score:** 83
- **EPSS 22.1% (2026-04-27) → 35.1% (2026-06-13), Δ +13.0%**

> A remote code execution vulnerability exists when the Microsoft .NET Framework fails to validate input properly, aka ".NET Framework Remote Code Injection Vulnerability." This affects Microsoft .NET Framework 2.0, Microsoft .NET Framework 3.0, Microsoft .NET Framework 4.6.2/4.7/4…

### CVE-2026-12183
**Nefteprodukttekhnika BUK TS-G Gas Station Automation System 2.9.1 through 2.10.2 on Linux contains an Improper Authentication vulnerabili...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-13T18:16:22.310
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-13)

> Nefteprodukttekhnika BUK TS-G Gas Station Automation System 2.9.1 through 2.10.2 on Linux contains an Improper Authentication vulnerability (CWE-287) in the system configuration module. The /php/ajax-login.php endpoint returns userid=1 (administrator) in response to any HTTP POST…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-13*
