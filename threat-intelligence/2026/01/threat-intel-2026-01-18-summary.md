# Daily Threat Intelligence — January 18, 2026

**Digest window (UTC):** 2026-01-18
**Generated:** 2026-06-02T07:34:13Z

## Threat brief

Wavlink Wn530h4 Firmware — exploitation likelihood rose sharply (EPSS 0.9% → 33% · rising (+32%)).

## Executive summary

- Wavlink Wn530h4 Firmware — exploitation likelihood rose sharply (EPSS 0.9% → 33% · rising (+32%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 8 |
| CVSS critical disclosure | 0 |
| Patch status change | 0 |
| **Total** | **8** |


## CVEs

### CVE-2024-10429
**wavlink wn530h4_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** wavlink wn530h4_firmware
- **Attack:** Command Injection
- **CVSS max:** 8.6
- **NVD status:** Analyzed
- **NVD modified:** 2024-11-13T17:58:18.040
- **CWE:** CWE-77
- **Risk score:** 84
- **EPSS 0.9% (2025-12-22) → 32.9% (2026-01-18), Δ +31.9%**

> A vulnerability classified as critical has been found in WAVLINK WN530H4, WN530HG4 and WN572HG3 up to 20221028. Affected is the function set_ipv6 of the file internet.cgi. The manipulation of the argument IPv6OpMode/IPv6IPAddr/IPv6WANIPAddr/IPv6GWAddr leads to command injection. …

### CVE-2024-48286
**linksys e3000_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** linksys e3000_firmware
- **Attack:** Command Injection
- **CVSS max:** 8.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-30T15:15:59.560
- **CWE:** CWE-77
- **Risk score:** 83
- **EPSS 0.4% (2026-01-05) → 24.1% (2026-01-18), Δ +23.7%**

> Linksys E3000 1.0.06.002_US is vulnerable to command injection via the diag_ping_start function.

### CVE-2024-37642
**trendnet tew-814dap_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** trendnet tew-814dap_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-27T16:23:11.683
- **CWE:** CWE-77
- **Risk score:** 85
- **EPSS 2.1% (2025-11-21) → 17.8% (2026-01-18), Δ +15.7%**

> TRENDnet TEW-814DAP v1_(FW1.01B01) was discovered to contain a command injection vulnerability via the ipv4_ping, ipv6_ping parameter at /formSystemCheck .

### CVE-2001-0042
**apache http_server**
- **Signals:** EPSS
- **Asset:** apache http_server
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 22.5% (2025-12-28) → 42.0% (2026-01-18), Δ +19.4%**

> PHP 3.x (PHP3) on Apache 1.3.6 allows remote attackers to read arbitrary files via a modified .. (dot dot) attack containing "%5c" (encoded backslash) sequences.

### CVE-2008-1996
**licq licq DoS**
- **Signals:** EPSS
- **Asset:** licq licq
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-399
- **Risk score:** 78
- **EPSS 20.3% (2025-06-18) → 43.6% (2026-01-18), Δ +23.3%**

> licq before 1.3.6 allows remote attackers to cause a denial of service (file-descriptor exhaustion and application crash) via a large number of connections.

### CVE-2017-11785
**microsoft windows_10 Info Disclosure**
- **Signals:** EPSS
- **Asset:** microsoft windows_10
- **Attack:** Info Disclosure
- **CVSS max:** 5.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-200
- **Risk score:** 79
- **EPSS 7.3% (2025-03-30) → 22.7% (2026-01-18), Δ +15.4%**

> The Microsoft Windows Kernel component on Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016, allows an information disclosure vulnerability when…

### CVE-2019-14312
**aptana jaxer**
- **Signals:** EPSS
- **Asset:** aptana jaxer
- **CVSS max:** 6.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:26:28.333
- **CWE:** CWE-22
- **Risk score:** 81
- **EPSS 39.8% (2025-11-21) → 55.6% (2026-01-18), Δ +15.9%**

> Aptana Jaxer 1.0.3.4547 is vulnerable to a local file inclusion vulnerability in the wikilite source code viewer. This vulnerability allows a remote attacker to read internal files on the server via a tools/sourceViewer/index.html?filename=../ URI.

### CVE-2024-48288
**tp-link tl-ipc42c_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** tp-link tl-ipc42c_firmware
- **Attack:** Command Injection
- **CVSS max:** 8.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-15T20:38:43.900
- **CWE:** CWE-77
- **Risk score:** 82
- **EPSS 0.2% (2025-12-31) → 12.0% (2026-01-18), Δ +11.8%**

> TP-Link TL-IPC42C V4.0_20211227_1.0.16 is vulnerable to command injection due to the lack of malicious code verification on both the frontend and backend.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-18*
