# Daily Threat Intelligence — April 15, 2026

**Digest window (UTC):** 2026-04-15
**Generated:** 2026-06-02T07:34:56Z

## Threat brief

Siemens Simatic S7 Cpu-1211c — exploitation likelihood rose sharply (EPSS 39% → 68% · rising (+29%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Siemens Simatic S7 Cpu-1211c — exploitation likelihood rose sharply (EPSS 39% → 68% · rising (+29%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 5 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2014-2908
**siemens simatic_s7_cpu-1211c XSS**
- **Signals:** EPSS
- **Asset:** siemens simatic_s7_cpu_1200_firmware
- **Attack:** XSS
- **CVSS max:** 4.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-79
- **Risk score:** 77
- **EPSS 38.7% (2025-12-09) → 68.0% (2026-04-15), Δ +29.3%**

> Cross-site scripting (XSS) vulnerability in the integrated web server on Siemens SIMATIC S7-1200 CPU devices 2.x and 3.x allows remote attackers to inject arbitrary web script or HTML via unspecified vectors.

### CVE-2020-15609
**centos-webpanel centos_web_panel**
- **Signals:** EPSS
- **Asset:** centos-webpanel centos_web_panel
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:05:51.637
- **CWE:** CWE-78
- **Risk score:** 86
- **EPSS 6.6% (2025-11-21) → 33.7% (2026-04-15), Δ +27.1%**

> This vulnerability allows remote attackers to execute arbitrary code on affected installations of CentOS Web Panel cwp-e17.0.9.8.923. Authentication is not required to exploit this vulnerability. The specific flaw exists within ajax_dashboard.php. When parsing the service_stop pa…

### CVE-2026-20147
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-17T15:09:46.880
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-15)

> A vulnerability in Cisco ISE and Cisco ISE-PIC could allow an authenticated, remote attacker to execute arbitrary commands on the underlying operating system of an affected device. To exploit this vulnerability, the attacker must have valid administrative credentials.

This vul…

### CVE-2020-10924
**netgear r6700_firmware**
- **Signals:** EPSS
- **Asset:** netgear r6700_firmware
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:56:22.830
- **CWE:** CWE-121
- **Risk score:** 84
- **EPSS 48.7% (2026-03-02) → 66.8% (2026-04-15), Δ +18.1%**

> This vulnerability allows network-adjacent attackers to bypass authentication on affected installations of NETGEAR R6700 V1.0.4.84_10.0.58 routers. Although authentication is required to exploit this vulnerability, the existing authentication mechanism can be bypassed. The specif…

### CVE-2020-15416
**netgear r6700_firmware**
- **Signals:** EPSS
- **Asset:** netgear r6700_firmware
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:05:30.600
- **CWE:** CWE-121
- **Risk score:** 84
- **EPSS 2.1% (2026-03-02) → 16.3% (2026-04-15), Δ +14.2%**

> This vulnerability allows network-adjacent attackers to bypass authentication on affected installations of NETGEAR R6700 V1.0.4.84_10.0.58 routers. Authentication is not required to exploit this vulnerability. The specific flaw exists within the httpd service, which listens on TC…

### CVE-2025-27607
**nhairs python_json_logger RCE**
- **Signals:** EPSS
- **Asset:** nhairs python_json_logger
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-01T16:22:57.830
- **CWE:** CWE-829
- **Risk score:** 84
- **EPSS 9.3% (2026-01-01) → 21.8% (2026-04-15), Δ +12.5%**

> Python JSON Logger is a JSON Formatter for Python Logging. Between 30 December 2024 and 4 March 2025 Python JSON Logger was vulnerable to RCE through a missing dependency. This occurred because msgspec-python313-pre was deleted by the owner leaving the name open to being claimed …

### CVE-2025-41118
**grafana pyroscope**
- **Signals:** CVSS
- **Asset:** grafana pyroscope
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-20T20:10:46.013
- **CWE:** CWE-732
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-15)

> Pyroscope is an open-source continuous profiling database. The database supports various storage backends, including Tencent Cloud Object Storage (COS).

If the database is configured to use Tencent COS as the storage backend, an attacker could extract the secret_key configuratio…

### CVE-2026-20180
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-17T15:09:46.880
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-15)

> A vulnerability in Cisco Identity Services Engine (ISE) could allow an authenticated, remote attacker to execute arbitrary commands on the underlying operating system of an affected device. To exploit this vulnerability, the attacker must have at least Read Only Admin credentials…

### CVE-2026-20184
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-17T15:09:46.880
- **CWE:** CWE-295
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-15)

> A vulnerability in the integration of single sign-on (SSO) with Control Hub in Cisco Webex Services could have allowed an unauthenticated, remote attacker to impersonate any user within the service.

This vulnerability existed because of improper certificate validation. Prior t…

### CVE-2026-20186
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-17T15:09:46.880
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-15)

> A vulnerability in Cisco Identity Services Engine (ISE) could allow an authenticated, remote attacker to execute arbitrary commands on the underlying operating system of an affected device. To exploit this vulnerability, the attacker must have at least Read Only Admin credentials…

### CVE-2026-30993
**Slah CMS v1.5.0 and below was discovered to contain a remote code execution (RCE) vulnerability in the session() function at config.php.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-17T15:37:20.857
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-15)

> Slah CMS v1.5.0 and below was discovered to contain a remote code execution (RCE) vulnerability in the session() function at config.php. This vulnerability is exploitable via a crafted input.

### CVE-2026-40173
**dgraph dgraph**
- **Signals:** CVSS
- **Asset:** dgraph dgraph
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-25T18:27:50.240
- **CWE:** CWE-200
- **CWE:** CWE-522
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-15)

> Dgraph is an open source distributed GraphQL database. Versions 25.3.1 and prior contain an unauthenticated credential disclosure vulnerability where the /debug/pprof/cmdline endpoint is registered on the default mux and reachable without authentication, exposing the full process…

### CVE-2026-5189
**CWE-798: Use of Hard-coded Credentials in Sonatype Nexus Repository Manager versions 3.0.0 through 3.70.5 allows an unauthenticated attac...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-17T15:08:01.337
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-04-15)

> CWE-798: Use of Hard-coded Credentials in Sonatype Nexus Repository Manager versions 3.0.0 through 3.70.5 allows an unauthenticated attacker with network access to gain unauthorized read/write access to the internal database and execute arbitrary OS commands as the Nexus process …

### CVE-2026-6296
**google chrome Buffer Overflow**
- **Signals:** CVSS
- **Asset:** google chrome
- **Attack:** Buffer Overflow
- **CVSS max:** 9.6
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T18:16:53.850
- **CWE:** CWE-122
- **CWE:** CWE-122
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-04-15)

> Heap buffer overflow in ANGLE in Google Chrome prior to 147.0.7727.101 allowed a remote attacker to potentially perform a sandbox escape via a crafted HTML page. (Chromium security severity: Critical)

### CVE-2026-6388
**A flaw was found in ArgoCD Image Updater.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-17T15:38:09.243
- **CWE:** CWE-1220
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-15)

> A flaw was found in ArgoCD Image Updater. This vulnerability allows an attacker, with permissions to create or modify an ImageUpdater resource in a multi-tenant environment, to bypass namespace boundaries. By exploiting insufficient validation, the attacker can trigger unauthoriz…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-15*
