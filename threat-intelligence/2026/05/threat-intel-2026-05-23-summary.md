# Daily Threat Intelligence — May 23, 2026

**Digest window (UTC):** 2026-05-23
**Generated:** 2026-06-02T07:04:06Z

## Threat brief

Tenda Ac23 Firmware — exploitation likelihood rose sharply (EPSS 6.3% → 18% · rising (+12%)).

## Executive summary

- Tenda Ac23 Firmware — exploitation likelihood rose sharply (EPSS 6.3% → 18% · rising (+12%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2023-2649
**tenda ac23_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** tenda ac23_firmware
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:59:00.223
- **CWE:** CWE-77
- **Risk score:** 81
- **EPSS 6.3% (2026-05-21) → 17.8% (2026-05-23), Δ +11.5%**

> A vulnerability was found in Tenda AC23 16.03.07.45_cn. It has been declared as critical. This vulnerability affects unknown code of the file /bin/ate of the component Service Port 7329. The manipulation of the argument v2 leads to command injection. The attack can be initiated r…

### CVE-2002-1932
**microsoft windows_2000**
- **Signals:** EPSS
- **Asset:** microsoft windows_2000
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 80
- **EPSS 23.6% (2025-12-28) → 34.5% (2026-05-23), Δ +10.8%**

> Microsoft Windows XP and Windows 2000, when configured to send administrative alerts and the "Do not overwrite events (clear log manually)" option is set, does not notify the administrator when the log reaches its maximum size, which allows local users and remote attackers to avo…

### CVE-2018-25357
**dolibarr dolibarr_erp\/crm RCE**
- **Signals:** CVSS
- **Asset:** dolibarr dolibarr_erp\/crm
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-27T15:56:19.693
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-23)

> Dolibarr ERP CRM 7.0.3 contains a remote code execution vulnerability that allows unauthenticated attackers to execute arbitrary code by injecting PHP code through the db_name parameter. Attackers can send a POST request to install/step1.php with malicious PHP code in the db_name…

### CVE-2014-3513
**openssl openssl DoS**
- **Signals:** EPSS
- **Asset:** openssl openssl
- **Attack:** DoS
- **CVSS max:** 7.1
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-20
- **Risk score:** 79
- **EPSS 25.7% (2026-04-15) → 35.7% (2026-05-23), Δ +10.0%**

> Memory leak in d1_srtp.c in the DTLS SRTP extension in OpenSSL 1.0.1 before 1.0.1j allows remote attackers to cause a denial of service (memory consumption) via a crafted handshake message.

### CVE-2018-25350
**userSpice 4.3.24 contains a username enumeration vulnerability that allows unauthenticated attackers to discover valid usernames by sendi...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T19:37:32.587
- **CWE:** CWE-204
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-23)

> userSpice 4.3.24 contains a username enumeration vulnerability that allows unauthenticated attackers to discover valid usernames by sending POST requests to the existingUsernameCheck.php endpoint. Attackers can submit usernames and analyze response text for the 'taken' string to …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-23*
