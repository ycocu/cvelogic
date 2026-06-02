# Daily Threat Intelligence — October 22, 2025

**Digest window (UTC):** 2025-10-22
**Generated:** 2026-06-02T07:33:38Z

## Threat brief

Motex LANSCOPE Endpoint Manager added to CISA KEV — confirmed in-the-wild exploitation. · Zohocorp Manageengine Adselfservice Plus — exploitation likelihood rose sharply (EPSS 2.5% → 21% · rising (+19%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Motex LANSCOPE Endpoint Manager added to CISA KEV — confirmed in-the-wild exploitation.
- Zohocorp Manageengine Adselfservice Plus — exploitation likelihood rose sharply (EPSS 2.5% → 21% · rising (+19%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2025-61932
**Motex LANSCOPE Endpoint Manager Improper Verification of Source of a Communication Channel Vulnerability**
- **Signals:** KEV
- **Asset:** motex lanscope_endpoint_manager
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-23T13:00:14.270
- **CWE:** CWE-940
- **Risk score:** 88
- **KEV:** added 2025-10-22

> Lanscope Endpoint Manager (On-Premises) (Client program (MR) and Detection agent (DA)) improperly verifies the origin of incoming requests, allowing an attacker to execute arbitrary code by sending specially crafted packets.

### CVE-2021-37423
**zohocorp manageengine_adselfservice_plus**
- **Signals:** EPSS
- **Asset:** zohocorp manageengine_adselfservice_plus
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:15:08.117
- **Risk score:** 86
- **EPSS 2.5% (2025-03-30) → 21.2% (2025-10-22), Δ +18.8%**

> Zoho ManageEngine ADSelfService Plus 6111 and prior is vulnerable to linked applications takeover.

### CVE-2025-60226
**axiomthemes white_rabbit Deserialization**
- **Signals:** CVSS
- **Asset:** axiomthemes white_rabbit
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-20T15:17:35.367
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-22)

> Deserialization of Untrusted Data vulnerability in axiomthemes White Rabbit whiterabbit allows Object Injection.This issue affects White Rabbit: from n/a through <= 1.5.2.

### CVE-2021-20147
**zohocorp manageengine_adselfservice_plus**
- **Signals:** EPSS
- **Asset:** zohocorp manageengine_adselfservice_plus
- **CVSS max:** 5.3
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:46:00.767
- **CWE:** CWE-203
- **Risk score:** 77
- **EPSS 6.9% (2025-03-30) → 18.0% (2025-10-22), Δ +11.2%**

> ManageEngine ADSelfService Plus below build 6116 contains an observable response discrepancy in the UMCP operation of the ChangePasswordAPI. This allows an unauthenticated remote attacker to determine whether a Windows domain user exists.

### CVE-2025-11957
**devolutions devolutions_server privilege escalation**
- **Signals:** CVSS
- **Asset:** devolutions devolutions_server
- **Attack:** privilege escalation
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2025-11-25T18:15:49.353
- **CWE:** CWE-639
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-10-22)

> Improper authorization in the temporary access workflow of Devolutions Server 2025.2.12.0 and earlier allows an authenticated basic user to self-approve or approve the temporary access requests of other users and gain unauthorized access to vaults and entries via crafted API requ…

### CVE-2025-60220
**Incorrect Privilege Assignment vulnerability in pebas CouponXxL couponxxl allows Privilege Escalation.This issue affects CouponXxL: from...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-22)

> Incorrect Privilege Assignment vulnerability in pebas CouponXxL couponxxl allows Privilege Escalation.This issue affects CouponXxL: from n/a through <= 3.0.0.

### CVE-2025-60221
**Deserialization of Untrusted Data vulnerability in captivateaudio Captivate Sync captivatesync-trade allows Object Injection.This issue a...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-22)

> Deserialization of Untrusted Data vulnerability in captivateaudio Captivate Sync captivatesync-trade allows Object Injection.This issue affects Captivate Sync: from n/a through <= 3.0.3.

### CVE-2025-60224
**Deserialization of Untrusted Data vulnerability in wpshuffle Subscribe to Download subscribe-to-download allows Object Injection.This iss...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-22)

> Deserialization of Untrusted Data vulnerability in wpshuffle Subscribe to Download subscribe-to-download allows Object Injection.This issue affects Subscribe to Download: from n/a through <= 2.0.9.

### CVE-2025-60225
**Deserialization of Untrusted Data vulnerability in AncoraThemes BugsPatrol bugspatrol allows Object Injection.This issue affects BugsPatr...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-22)

> Deserialization of Untrusted Data vulnerability in AncoraThemes BugsPatrol bugspatrol allows Object Injection.This issue affects BugsPatrol: from n/a through <= 1.5.0.

### CVE-2025-60232
**Deserialization of Untrusted Data vulnerability in quantumcloud KBx Pro Ultimate knowledgebase-helpdesk-pro allows Object Injection.This...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-22)

> Deserialization of Untrusted Data vulnerability in quantumcloud KBx Pro Ultimate knowledgebase-helpdesk-pro allows Object Injection.This issue affects KBx Pro Ultimate: from n/a through <= 8.0.5.

### CVE-2025-60238
**Deserialization of Untrusted Data vulnerability in universam UNIVERSAM universam-demo allows Object Injection.This issue affects UNIVERSA...**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:34:24.780
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-22)

> Deserialization of Untrusted Data vulnerability in universam UNIVERSAM universam-demo allows Object Injection.This issue affects UNIVERSAM: from n/a through <= 9.04.02.

### CVE-2025-62023
**Improper Control of Generation of Code ('Code Injection') vulnerability in Cristián Lávaque s2Member s2member.This issue affects s2Member...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:34:26.803
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-10-22)

> Improper Control of Generation of Code ('Code Injection') vulnerability in Cristián Lávaque s2Member s2member.This issue affects s2Member: from n/a through <= 250905.

### CVE-2025-62025
**Deserialization of Untrusted Data vulnerability in eyecix JobSearch wp-jobsearch.This issue affects JobSearch: from n/a through < 3.0.8.**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-22)

> Deserialization of Untrusted Data vulnerability in eyecix JobSearch wp-jobsearch.This issue affects JobSearch: from n/a through < 3.0.8.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-22*
