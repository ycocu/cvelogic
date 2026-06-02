# Daily Threat Intelligence — April 05, 2026

**Digest window (UTC):** 2026-04-05
**Generated:** 2026-06-02T07:34:51Z

## Threat brief

Citrix Xenserver — exploitation likelihood rose sharply (EPSS 5.0% → 38% · rising (+33%)).

## Executive summary

- Citrix Xenserver — exploitation likelihood rose sharply (EPSS 5.0% → 38% · rising (+33%)).

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

### CVE-2018-14007
**citrix xenserver Directory Traversal**
- **Signals:** EPSS
- **Asset:** citrix xenserver
- **Attack:** Directory Traversal
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:48:26.033
- **CWE:** CWE-22
- **Risk score:** 86
- **EPSS 5.0% (2026-03-03) → 38.0% (2026-04-05), Δ +33.0%**

> Citrix XenServer 7.1 and newer allows Directory Traversal.

### CVE-2025-49136
**nadh listmonk**
- **Signals:** EPSS
- **Asset:** nadh listmonk
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-11T17:23:30.110
- **CWE:** CWE-1336
- **Risk score:** 84
- **EPSS 41.3% (2026-02-23) → 61.8% (2026-04-05), Δ +20.5%**

> listmonk is a standalone, self-hosted, newsletter and mailing list manager. Starting in version 4.0.0 and prior to version 5.0.2, the `env` and `expandenv` template functions which is enabled by default in Sprig enables capturing of env variables on host. While this may not be a …

### CVE-2019-25687
**wisdom pegasus_cms RCE**
- **Signals:** CVSS
- **Asset:** wisdom pegasus_cms
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T15:42:55.380
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-05)

> Pegasus CMS 1.0 contains a remote code execution vulnerability in the extra_fields.php plugin that allows unauthenticated attackers to execute arbitrary commands by exploiting unsafe eval functionality. Attackers can send POST requests to the submit.php endpoint with malicious PH…

### CVE-2014-9463
**vbseo vbseo**
- **Signals:** EPSS
- **Asset:** vbseo vbseo
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-94
- **Risk score:** 84
- **EPSS 10.7% (2026-03-04) → 26.6% (2026-04-05), Δ +15.9%**

> functions_vbseo_hook.php in the VBSEO module for vBulletin allows remote authenticated users to execute arbitrary code via the HTTP Referer header to visitormessage.php.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-05*
