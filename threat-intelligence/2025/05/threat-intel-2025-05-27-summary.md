# Daily Threat Intelligence — May 27, 2025

**Digest window (UTC):** 2025-05-27
**Generated:** 2026-06-02T07:32:47Z

## Threat brief

7 new critical disclosures — review patch status on exposed services.

## Executive summary

- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2025-32440
**netalertx netalertx**
- **Signals:** CVSS
- **Asset:** netalertx netalertx
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-11T18:58:26.233
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-27)

> NetAlertX is a network, presence scanner and alert framework. Prior to version 25.4.14, it is possible to bypass the authentication mechanism of NetAlertX to update settings without authentication. An attacker can trigger sensitive functions within util.php by sending crafted req…

### CVE-2025-48827
**vbulletin vbulletin**
- **Signals:** CVSS
- **Asset:** vbulletin vbulletin
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-25T16:46:46.703
- **CWE:** CWE-424
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-05-27)

> vBulletin 5.0.0 through 5.7.5 and 6.0.0 through 6.0.3 allows unauthenticated users to invoke protected API controllers' methods when running on PHP 8.1 or later, as demonstrated by the /api.php?method=protectedMethod pattern, as exploited in the wild in May 2025.

### CVE-2025-41652
**The devices are vulnerable to an authentication bypass due to flaws in the authorization mechanism.**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-328
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-27)

> The devices are vulnerable to an authentication bypass due to flaws in the authorization mechanism. An unauthenticated remote attacker could exploit this weakness by performing brute-force attacks to guess valid credentials or by using MD5 collision techniques to forge authentica…

### CVE-2025-2407
**Missing Authentication & Authorization in Web-API in Mobatime AMX MTAPI v6 on IIS allows adversaries to unrestricted access via the network.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-27)

> Missing Authentication & Authorization in Web-API in Mobatime AMX MTAPI v6 on IIS allows adversaries to unrestricted access via the network. The vulnerability is fixed in Version 1.5.

### CVE-2025-41651
**Due to missing authentication on a critical function of the devices an unauthenticated remote attacker can execute arbitrary commands, po...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-27)

> Due to missing authentication on a critical function of the devices an unauthenticated remote attacker can execute arbitrary commands, potentially enabling unauthorized upload or download of configuration files and leading to full system compromise.

### CVE-2025-48057
**icinga icinga**
- **Signals:** CVSS
- **Asset:** icinga icinga
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-05T00:12:22.747
- **CWE:** CWE-296
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-27)

> Icinga 2 is a monitoring system which checks the availability of network resources, notifies users of outages, and generates performance data for reporting. Prior to versions 2.12.12, 2.13.12, and 2.14.6, the VerifyCertificate() function can be tricked into incorrectly treating c…

### CVE-2025-48828
**vbulletin vbulletin**
- **Signals:** CVSS
- **Asset:** vbulletin vbulletin
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-25T16:32:38.947
- **CWE:** CWE-424
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-05-27)

> Certain vBulletin versions might allow attackers to execute arbitrary PHP code by abusing Template Conditionals in the template engine. By crafting template code in an alternative PHP function invocation syntax, such as the "var_dump"("test") syntax, attackers can bypass security…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-27*
