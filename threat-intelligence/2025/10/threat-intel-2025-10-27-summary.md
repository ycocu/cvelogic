# Daily Threat Intelligence — October 27, 2025

**Digest window (UTC):** 2025-10-27
**Generated:** 2026-06-02T07:33:40Z

## Threat brief

Hp Jetdirect — exploitation likelihood rose sharply (EPSS 16% → 31% · rising (+15%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Hp Jetdirect — exploitation likelihood rose sharply (EPSS 16% → 31% · rising (+15%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2000-0636
**hp jetdirect DoS**
- **Signals:** EPSS
- **Asset:** hp jetdirect
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 16.0% (2025-03-30) → 31.2% (2025-10-27), Δ +15.1%**

> HP JetDirect printers versions G.08.20 and H.08.20 and earlier allow remote attackers to cause a denial of service via a malformed FTP quote command.

### CVE-2025-12363
**azure-access blu-ic2_firmware**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-10T14:54:57.490
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-27)

> Email Password Disclosure.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5.

### CVE-2025-12364
**azure-access blu-ic2_firmware**
- **Signals:** CVSS
- **Asset:** azure-access blu-ic2_firmware
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-10T14:54:46.497
- **CWE:** CWE-521
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-27)

> Weak Password Policy.This issue affects BLU-IC2: through 1.19.5; BLU-IC4: through 1.19.5.

### CVE-2025-27224
**rocketsoftware trufusion_enterprise Path Traversal**
- **Signals:** CVSS
- **Asset:** rocketsoftware trufusion_enterprise
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T20:34:32.483
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-27)

> TRUfusion Enterprise through 7.10.4.0 uses the /trufusionPortal/fileupload endpoint to upload files. However, the application doesn't properly sanitize the input to this endpoint, ultimately allowing path traversal sequences to be included. This can be used to write to any filena…

### CVE-2025-34292
**Rox, the software running BeWelcome, contains a PHP object injection vulnerability resulting from deserialization of untrusted data.**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-10-27)

> Rox, the software running BeWelcome, contains a PHP object injection vulnerability resulting from deserialization of untrusted data. User-controlled input is passed to PHP's unserialize(): the POST parameter `formkit_memory_recovery` in \\RoxPostHandler::getCallbackAction and the…

### CVE-2025-41009
**SQL injection vulnerability in the DRED virtual campus platform.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-27)

> SQL injection vulnerability in the DRED virtual campus platform. This vulnerability allows an attacker to retrieve, create, update, and delete data from the database by sending a POST request using the ‘buscame’ parameter in ‘/catalogo_c/catalogo.php’.

### CVE-2025-55754
**apache tomcat**
- **Signals:** CVSS
- **Asset:** apache tomcat
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD modified:** 2026-05-12T13:17:22.457
- **CWE:** CWE-150
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-10-27)

> Improper Neutralization of Escape, Meta, or Control Sequences vulnerability in Apache Tomcat.

Tomcat did not escape ANSI escape sequences in log messages. If Tomcat was running in a console on a Windows operating system, and the console supported ANSI escape sequences, it was po…

### CVE-2025-60291
**An issue was discovered in eTimeTrackLite Web thru 12.0 (20250704).**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-27)

> An issue was discovered in eTimeTrackLite Web thru 12.0 (20250704). There is a permission control flaw that allows unauthorized attackers to access specific routes and modify database connection configurations.

### CVE-2025-61385
**SQL injection vulnerability in tlocke pg8000 1.31.4 allows remote attackers to execute arbitrary SQL commands via a specially crafted Pyt...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-10-27)

> SQL injection vulnerability in tlocke pg8000 1.31.4 allows remote attackers to execute arbitrary SQL commands via a specially crafted Python list input to function pg8000.native.literal.

### CVE-2025-61481
**An issue in MikroTik RouterOS v.7.14.2 and SwOS v.2.18 exposes the WebFig management interface over cleartext HTTP by default, allowing a...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-10-27)

> An issue in MikroTik RouterOS v.7.14.2 and SwOS v.2.18 exposes the WebFig management interface over cleartext HTTP by default, allowing an on-path attacker to execute injected JavaScript in the administrator’s browser and intercept credentials.

### CVE-2025-62959
**Improper Control of Generation of Code ('Code Injection') vulnerability in videowhisper Paid Videochat Turnkey Site ppv-live-webcams allo...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-27)

> Improper Control of Generation of Code ('Code Injection') vulnerability in videowhisper Paid Videochat Turnkey Site ppv-live-webcams allows Remote Code Inclusion.This issue affects Paid Videochat Turnkey Site: from n/a through <= 7.3.23.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-27*
