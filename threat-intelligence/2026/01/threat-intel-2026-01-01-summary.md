# Daily Threat Intelligence — January 01, 2026

**Digest window (UTC):** 2026-01-01
**Generated:** 2026-06-02T07:34:05Z

## Threat brief

Isc Bind — exploitation likelihood rose sharply (EPSS 45% → 82% · rising (+37%)).

## Executive summary

- Isc Bind — exploitation likelihood rose sharply (EPSS 45% → 82% · rising (+37%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 6 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **8** |


## CVEs

### CVE-2001-0010
**isc bind Buffer Overflow**
- **Signals:** EPSS
- **Asset:** isc bind
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 86
- **EPSS 45.4% (2025-04-21) → 82.1% (2026-01-01), Δ +36.7%**

> Buffer overflow in transaction signature (TSIG) handling code in BIND 8 allows remote attackers to gain root privileges.

### CVE-2009-0542
**proftpd_project proftpd SQL Injection**
- **Signals:** EPSS
- **Asset:** proftpd_project proftpd
- **Attack:** SQL Injection
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-89
- **Risk score:** 82
- **EPSS 29.7% (2025-05-01) → 58.5% (2026-01-01), Δ +28.8%**

> SQL injection vulnerability in ProFTPD Server 1.3.1 through 1.3.2rc2 allows remote attackers to execute arbitrary SQL commands via a "%" (percent) character in the username, which introduces a "'" (single quote) character during variable substitution by mod_sql.

### CVE-2025-66398
**signalk signal_k_server**
- **Signals:** CVSS
- **Asset:** signalk signal_k_server
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-06T18:34:31.007
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-01-01)

> Signal K Server is a server application that runs on a central hub in a boat. Prior to version 2.19.0, an unauthenticated attacker can pollute the internal state (`restoreFilePath`) of the server via the `/skServer/validateBackup` endpoint. This allows the attacker to hijack the …

### CVE-2002-0409
**microsoft .net_framework**
- **Signals:** EPSS
- **Asset:** microsoft .net_framework
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 34.2% (2025-04-23) → 52.9% (2026-01-01), Δ +18.7%**

> orderdetails.aspx, as made available to Microsoft .NET developers as example code and demonstrated on www.ibuyspystore.com, allows remote attackers to view the orders of other users by modifying the OrderID parameter.

### CVE-2005-4504
**apple mac_os_x DoS**
- **Signals:** EPSS
- **Asset:** apple safari
- **Attack:** DoS
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 83
- **EPSS 21.8% (2025-05-04) → 36.8% (2026-01-01), Δ +15.0%**

> The khtml::RenderTableSection::ensureRows function in KHTMLParser in Apple Mac OS X 10.4.3 and earlier, as used by Safari and TextEdit, allows remote attackers to cause a denial of service (memory consumption and application crash) via HTML files with a large ROWSPAN attribute in…

### CVE-2017-13258
**google android Info Disclosure**
- **Signals:** EPSS
- **Asset:** google android
- **Attack:** Info Disclosure
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:11:15.057
- **CWE:** CWE-125
- **Risk score:** 81
- **EPSS 16.3% (2025-10-19) → 27.6% (2026-01-01), Δ +11.3%**

> In bnep_data_ind of bnep_main.cc, there is a possible out of bounds read due to a missing bounds check. This could lead to remote information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android. Versions: 5.…

### CVE-2017-13261
**google android Info Disclosure**
- **Signals:** EPSS
- **Asset:** google android
- **Attack:** Info Disclosure
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:11:15.390
- **CWE:** CWE-125
- **Risk score:** 82
- **EPSS 20.7% (2025-10-19) → 33.6% (2026-01-01), Δ +12.9%**

> In bnep_process_control_packet of bnep_utils.cc, there is a possible out of bounds read due to a missing bounds check. This could lead to remote information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Androi…

### CVE-2025-68620
**signalk signal_k_server**
- **Signals:** CVSS
- **Asset:** signalk signal_k_server
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-06T17:56:51.767
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-01)

> Signal K Server is a server application that runs on a central hub in a boat. Versions prior to 2.19.0 expose two features that can be chained together to steal JWT authentication tokens without any prior authentication. The attack combines WebSocket-based request enumeration wit…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-01*
