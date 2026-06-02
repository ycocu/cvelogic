# Daily Threat Intelligence — October 04, 2025

**Digest window (UTC):** 2025-10-04
**Generated:** 2026-06-02T07:33:32Z

## Threat brief

Zte Zxhn H108n R1a Firmware — exploitation likelihood rose sharply (EPSS 23% → 39% · rising (+16%)).

## Executive summary

- Zte Zxhn H108n R1a Firmware — exploitation likelihood rose sharply (EPSS 23% → 39% · rising (+16%)).

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

### CVE-2015-7251
**zte zxhn_h108n_r1a_firmware**
- **Signals:** EPSS
- **Asset:** zte zxhn_h108n_r1a_firmware
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-255
- **Risk score:** 86
- **EPSS 23.0% (2025-03-30) → 38.8% (2025-10-04), Δ +15.8%**

> ZTE ZXHN H108N R1A devices before ZTE.bhs.ZXHNH108NR1A.k_PE have a hardcoded password of root for the root account, which allows remote attackers to obtain administrative access via a TELNET session.

### CVE-2025-39946
**linux linux_kernel**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-06T13:30:51.763
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-04)

> In the Linux kernel, the following vulnerability has been resolved:

tls: make sure to abort the stream if headers are bogus

Normally we wait for the socket to buffer up the whole record
before we service it. If the socket has a tiny buffer, however,
we read out the data sooner,…

### CVE-2025-9485
**The OAuth Single Sign On – SSO (OAuth Client) plugin for WordPress is vulnerable to Improper Verification of Cryptographic Signature in v...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-347
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-04)

> The OAuth Single Sign On – SSO (OAuth Client) plugin for WordPress is vulnerable to Improper Verification of Cryptographic Signature in versions up to, and including, 6.26.12. This is due to the plugin performing unsafe JWT token processing without verification or validation in t…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-04*
