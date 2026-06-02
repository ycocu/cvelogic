# Daily Threat Intelligence — February 14, 2026

**Digest window (UTC):** 2026-02-14
**Generated:** 2026-06-02T07:34:25Z

## Threat brief

WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Ipswitch Imail — exploitation likelihood rose sharply (EPSS 6.3% → 17% · rising (+10%)).

## Executive summary

- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Ipswitch Imail — exploitation likelihood rose sharply (EPSS 6.3% → 17% · rising (+10%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **3** |


## CVEs

### CVE-2005-1255
**ipswitch imail Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ipswitch imail
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 84
- **EPSS 6.3% (2025-06-23) → 16.8% (2026-02-14), Δ +10.5%**

> Multiple stack-based buffer overflows in the IMAP server in IMail 8.12 and 8.13 in Ipswitch Collaboration Suite (ICS), and other versions before IMail Server 8.2 Hotfix 2, allow remote attackers to execute arbitrary code via a LOGIN command with (1) a long username argument or (2…

### CVE-2025-8572
**The Truelysell Core plugin for WordPress is vulnerable to privilege escalation in versions less than, or equal to, 1.8.7.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-14)

> The Truelysell Core plugin for WordPress is vulnerable to privilege escalation in versions less than, or equal to, 1.8.7. This is due to insufficient validation of the user_role parameter during user registration. This makes it possible for unauthenticated attackers to create acc…

### CVE-2026-1306
**The midi-Synth plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type and file extension validation in the...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-14)

> The midi-Synth plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type and file extension validation in the 'export' AJAX action in all versions up to, and including, 1.1.0. This makes it possible for unauthenticated attackers to upload arbitrary fil…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-14*
