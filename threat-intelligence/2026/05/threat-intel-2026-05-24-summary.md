# Daily Threat Intelligence — May 24, 2026

**Digest window (UTC):** 2026-05-24
**Generated:** 2026-06-02T07:04:06Z

## Threat brief

Tenda Ac18 Firmware — exploitation likelihood rose sharply (EPSS 7.1% → 26% · rising (+19%)).

## Executive summary

- Tenda Ac18 Firmware — exploitation likelihood rose sharply (EPSS 7.1% → 26% · rising (+19%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **6** |


## CVEs

### CVE-2023-30135
**tenda ac18_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** tenda ac18_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-01-29T17:15:24.527
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 86
- **EPSS 7.1% (2026-05-23) → 26.4% (2026-05-24), Δ +19.3%**

> Tenda AC18 v15.03.05.19(6318_)_cn was discovered to contain a command injection vulnerability via the deviceName parameter in the setUsbUnload function.

### CVE-2018-13109
**adbglobal dv2210_firmware privilege escalation**
- **Signals:** EPSS
- **Asset:** adbglobal dv2210_firmware
- **Attack:** privilege escalation
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:46:27.270
- **CWE:** CWE-863
- **Risk score:** 82
- **EPSS 5.5% (2025-12-22) → 22.4% (2026-05-24), Δ +16.8%**

> All ADB broadband gateways / routers based on the Epicentro platform are affected by an authorization bypass vulnerability where attackers are able to access and manipulate settings within the web interface that are forbidden to end users (e.g., by the ISP). An attacker would be …

### CVE-2018-6871
**canonical debian_linux**
- **Signals:** EPSS
- **Asset:** libreoffice libreoffice
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:11:20.230
- **Risk score:** 86
- **EPSS 30.1% (2026-04-07) → 46.2% (2026-05-24), Δ +16.1%**

> LibreOffice before 5.4.5 and 6.x before 6.0.1 allows remote attackers to read arbitrary files via =WEBSERVICE calls in a document, which use the COM.MICROSOFT.WEBSERVICE function.

### CVE-2014-3478
**christos_zoulas file Buffer Overflow**
- **Signals:** EPSS
- **Asset:** christos_zoulas file
- **Attack:** Buffer Overflow
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **CWE:** CWE-119
- **Risk score:** 80
- **EPSS 25.3% (2026-03-04) → 37.6% (2026-05-24), Δ +12.3%**

> Buffer overflow in the mconvert function in softmagic.c in file before 5.19, as used in the Fileinfo component in PHP before 5.4.30 and 5.5.x before 5.5.14, allows remote attackers to cause a denial of service (application crash) via a crafted Pascal string in a FILE_PSTRING conv…

### CVE-2014-3587
**christos_zoulas file DoS**
- **Signals:** EPSS
- **Asset:** christos_zoulas file
- **Attack:** DoS
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-189
- **Risk score:** 76
- **EPSS 19.1% (2026-03-04) → 30.2% (2026-05-24), Δ +11.1%**

> Integer overflow in the cdf_read_property_info function in cdf.c in file through 5.19, as used in the Fileinfo component in PHP before 5.4.32 and 5.5.x before 5.5.16, allows remote attackers to cause a denial of service (application crash) via a crafted CDF file.  NOTE: this vuln…

### CVE-2017-7413
**horde groupware Command Injection**
- **Signals:** EPSS
- **Asset:** horde groupware
- **Attack:** Command Injection
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-78
- **Risk score:** 83
- **EPSS 13.3% (2025-11-21) → 24.5% (2026-05-24), Δ +11.2%**

> In Horde_Crypt before 2.7.6, as used in Horde Groupware Webmail Edition through 5.2.17, OS Command Injection can occur if the attacker is an authenticated Horde Webmail user, has PGP features enabled in their preferences, and attempts to encrypt an email addressed to a maliciousl…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-24*
