# Daily Threat Intelligence — February 21, 2026

**Digest window (UTC):** 2026-02-21
**Generated:** 2026-06-02T07:34:29Z

## Threat brief

Metersphere — exploitation likelihood rose sharply (EPSS 8.0% → 24% · rising (+16%)). · 6 new critical disclosures — review patch status on exposed services.

## Executive summary

- Metersphere — exploitation likelihood rose sharply (EPSS 8.0% → 24% · rising (+16%)).
- 6 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 6 |
| Patch status change | 0 |
| **Total** | **9** |


## CVEs

### CVE-2022-23544
**metersphere metersphere XSS**
- **Signals:** EPSS
- **Asset:** metersphere metersphere
- **Attack:** XSS
- **CVSS max:** 7.2
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:48:47.020
- **CWE:** CWE-79
- **CWE:** CWE-918
- **Risk score:** 82
- **EPSS 8.0% (2026-01-27) → 23.6% (2026-02-21), Δ +15.6%**

> MeterSphere is a one-stop open source continuous testing platform, covering test management, interface testing, UI testing and performance testing. Versions prior to 2.5.0 are subject to a Server-Side Request Forgery that leads to Cross-Site Scripting. A Server-Side request forge…

### CVE-2005-1110
**sumus sumus Buffer Overflow**
- **Signals:** EPSS
- **Asset:** sumus sumus
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 5.2% (2025-03-30) → 17.3% (2026-02-21), Δ +12.2%**

> Stack-based buffer overflow in the RespondeHTTPPendiente function in the HTTP server for SUMUS 0.2.2 allows remote attackers to execute arbitrary code via a large packet sent to TCP port 81.

### CVE-2026-27574
**hackerbay oneuptime**
- **Signals:** CVSS
- **Asset:** hackerbay oneuptime
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T20:36:09.117
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-02-21)

> OneUptime is a solution for monitoring and managing online services. In versions 9.5.13 and below, custom JavaScript monitor feature uses Node.js's node:vm module (explicitly documented as not a security mechanism) to execute user-supplied code, allowing trivial sandbox escape vi…

### CVE-2023-43323
**moosocial moosocial**
- **Signals:** EPSS
- **Asset:** moosocial moosocial
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:23:59.837
- **CWE:** CWE-15
- **Risk score:** 80
- **EPSS 68.7% (2025-11-30) → 80.8% (2026-02-21), Δ +12.1%**

> mooSocial 3.1.8 is vulnerable to external service interaction on post function. When executed, the server sends a HTTP and DNS request to external server. The Parameters effected are multiple - messageText, data[wall_photo], data[userShareVideo] and data[userShareLink].

### CVE-2026-27197
**sentry sentry**
- **Signals:** CVSS
- **Asset:** sentry sentry
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T20:45:01.957
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-21)

> Sentry is a developer-first error tracking and performance monitoring tool. Versions 21.12.0 through 26.1.0 have a critical vulnerability in its SAML SSO implementation  which allows an attacker to take over any user account by using a malicious SAML Identity Provider and another…

### CVE-2026-27211
**cloudhypervisor cloud_hypervisor privilege escalation**
- **Signals:** CVSS
- **Asset:** cloudhypervisor cloud_hypervisor
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-24T17:08:14.463
- **CWE:** CWE-73
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-21)

> Cloud Hypervisor is a Virtual Machine Monitor for Cloud workloads. Versions 34.0 through 50.0 arevulnerable to arbitrary host file exfiltration (constrained by process privileges) when using virtio-block devices backed by raw images. A malicious guest can overwrite its disk heade…

### CVE-2026-27212
**swiperjs swiper**
- **Signals:** CVSS
- **Asset:** swiperjs swiper
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-24T15:16:56.670
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-21)

> Swiper is a free and mobile touch slider with hardware accelerated transitions and native behavior. Versions 6.5.1 through 12.1.1 have a Prototype pollution vulnerability. The vulnerability resides in line 94 of shared/utils.mjs, where the indexOf() function is used to check whet…

### CVE-2026-27452
**jonathanwilbur asn1-ts**
- **Signals:** CVSS
- **Asset:** jonathanwilbur asn1-ts
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-03T17:28:50.777
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-21)

> ASN.1 TypeScript ESM library, including codecs for Basic Encoding Rules (BER) and Distinguished Encoding Rules (DER). In versions 11.0.5 and below, in some cases, decoding an INTEGER could leak the underlying ArrayBuffer. This issue is expected to be fixed in version 11.0.6.

### CVE-2026-27471
**frappe erpnext**
- **Signals:** CVSS
- **Asset:** frappe erpnext
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-24T14:52:50.073
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-21)

> ERP is a free and open source Enterprise Resource Planning tool. In versions up to 15.98.0 and 16.0.0-rc.1 and through 16.6.0, certain endpoints lacked access validation which allowed for unauthorized document access. This issue has been fixed in versions 15.98.1 and 16.6.1.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-21*
