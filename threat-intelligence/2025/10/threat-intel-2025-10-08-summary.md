# Daily Threat Intelligence — October 08, 2025

**Digest window (UTC):** 2025-10-08
**Generated:** 2026-06-02T07:33:33Z

## Threat brief

Projectsend — exploitation likelihood rose sharply (EPSS 8.9% → 83% · rising (+74%)). · 7 new critical disclosures — review patch status on exposed services.

## Executive summary

- Projectsend — exploitation likelihood rose sharply (EPSS 8.9% → 83% · rising (+74%)).
- 7 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 10 |
| CVSS critical disclosure | 7 |
| Patch status change | 0 |
| **Total** | **17** |


## CVEs

### CVE-2014-9567
**projectsend projectsend**
- **Signals:** EPSS
- **Asset:** projectsend projectsend
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-94
- **Risk score:** 82
- **EPSS 8.9% (2025-09-22) → 82.9% (2025-10-08), Δ +74.0%**

> Unrestricted file upload vulnerability in process-upload.php in ProjectSend (formerly cFTP) r100 through r561 allows remote attackers to execute arbitrary PHP code by uploading a file with a PHP extension, then accessing it via a direct request to the file in the upload/files/ or…

### CVE-2009-0182
**vuplayer vuplayer Buffer Overflow**
- **Signals:** EPSS
- **Asset:** vuplayer vuplayer
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-120
- **Risk score:** 84
- **EPSS 5.7% (2025-03-30) → 79.0% (2025-10-08), Δ +73.3%**

> Buffer overflow in VUPlayer 2.49 and earlier allows user-assisted attackers to execute arbitrary code via a long URL in a File line in a .pls file, as demonstrated by an http URL on a File1 line.

### CVE-2025-61913
**flowiseai flowise**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-20T15:23:05.060
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-10-08)

> Flowise is a drag & drop user interface to build a customized large language model flow. In versions prior to 3.0.8, WriteFileTool and ReadFileTool in Flowise do not restrict file path access, allowing authenticated attackers to exploit this vulnerability to read and write arbitr…

### CVE-1999-0920
**university_of_washington imap Buffer Overflow**
- **Signals:** EPSS
- **Asset:** university_of_washington imap
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 86
- **EPSS 3.5% (2025-03-30) → 73.5% (2025-10-08), Δ +70.0%**

> Buffer overflow in the pop-2d POP daemon in the IMAP package allows remote attackers to gain privileges via the FOLD command.

### CVE-2010-5333
**integard_home_project integard_home RCE**
- **Signals:** EPSS
- **Asset:** integard_home_project integard_home
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T01:23:04.287
- **CWE:** CWE-120
- **Risk score:** 86
- **EPSS 7.2% (2025-03-30) → 77.0% (2025-10-08), Δ +69.8%**

> The web server in Integard Pro and Home before 2.0.0.9037 and 2.2.x before 2.2.0.9037 has a buffer overflow via a long password in an administration login POST request, leading to arbitrary code execution. An SEH-overwrite buffer overflow already existed for the vulnerable softwa…

### CVE-2013-4557
**spip spip**
- **Signals:** EPSS
- **Asset:** spip spip
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-94
- **Risk score:** 82
- **EPSS 2.3% (2025-08-12) → 69.5% (2025-10-08), Δ +67.2%**

> The Security Screen (_core_/securite/ecran_securite.php) before 1.1.8 for SPIP, as used in SPIP 3.0.x before 3.0.12, allows remote attackers to execute arbitrary PHP via the connect parameter.

### CVE-2014-8420
**sonicwall analyzer**
- **Signals:** EPSS
- **Asset:** sonicwall analyzer
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-20
- **Risk score:** 84
- **EPSS 4.1% (2025-04-18) → 73.8% (2025-10-08), Δ +69.7%**

> The ViewPoint web application in Dell SonicWALL Global Management System (GMS) before 7.2 SP2, SonicWALL Analyzer before 7.2 SP2, and SonicWALL UMA before 7.2 SP2 allows remote authenticated users to execute arbitrary code via unspecified vectors.

### CVE-2015-1930
**ibm tivoli_storage_manager_fastback Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ibm tivoli_storage_manager_fastback
- **Attack:** Buffer Overflow
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 83
- **EPSS 1.4% (2025-05-23) → 70.0% (2025-10-08), Δ +68.6%**

> Stack-based buffer overflow in the server in IBM Tivoli Storage Manager FastBack 6.1 before 6.1.12 allows remote attackers to cause a denial of service (daemon crash) via unspecified vectors, a different vulnerability than CVE-2015-1924, CVE-2015-1925, CVE-2015-1929, CVE-2015-194…

### CVE-2016-10542
**ws_project ws**
- **Signals:** EPSS
- **Asset:** ws_project ws
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T02:44:13.973
- **CWE:** CWE-400
- **CWE:** CWE-20
- **Risk score:** 82
- **EPSS 0.3% (2025-06-20) → 66.1% (2025-10-08), Δ +65.8%**

> ws is a "simple to use, blazing fast and thoroughly tested websocket client, server and console for node.js, up-to-date against RFC-6455". By sending an overly long websocket payload to a `ws` server, it is possible to crash the node process. This affects ws 1.1.0 and earlier.

### CVE-2017-11391
**trendmicro interscan_messaging_security_virtual_appliance Command Injection**
- **Signals:** EPSS
- **Asset:** trendmicro interscan_messaging_security_virtual_appliance
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-77
- **Risk score:** 84
- **EPSS 12.6% (2025-03-30) → 81.4% (2025-10-08), Δ +68.8%**

> Proxy command injection vulnerability in Trend Micro InterScan Messaging Virtual Appliance 9.0 and 9.1 allows remote attackers to execute arbitrary code on vulnerable installations. The specific flaw can be exploited by parsing the "t" parameter within modTMCSS Proxy. Formerly ZD…

### CVE-2017-11392
**trendmicro interscan_messaging_security_virtual_appliance Command Injection**
- **Signals:** EPSS
- **Asset:** trendmicro interscan_messaging_security_virtual_appliance
- **Attack:** Command Injection
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-77
- **Risk score:** 84
- **EPSS 6.8% (2025-03-30) → 73.9% (2025-10-08), Δ +67.2%**

> Proxy command injection vulnerability in Trend Micro InterScan Messaging Virtual Appliance 9.0 and 9.1 allows remote attackers to execute arbitrary code on vulnerable installations. The specific flaw can be exploited by parsing the "T" parameter within modTMCSS Proxy. Formerly ZD…

### CVE-2017-20201
**CCleaner v5.33.6162 and CCleaner Cloud v1.07.3191 (32-bit builds) contained a malicious pre-entry-point loader that diverts execution fro...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-506
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-08)

> CCleaner v5.33.6162 and CCleaner Cloud v1.07.3191 (32-bit builds) contained a malicious pre-entry-point loader that diverts execution from __scrt_common_main_seh into a custom loader. That loader decodes an embedded blob into shellcode, allocates executable heap memory, resolves …

### CVE-2017-20202
**Web Developer for Chrome v0.4.9 contained malicious code that generated a domain via a DGA and fetched a remote script.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-506
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-08)

> Web Developer for Chrome v0.4.9 contained malicious code that generated a domain via a DGA and fetched a remote script. The fetched script conditionally loaded follow-on modules that performed extensive ad substitution and malvertising, displayed fake “repair” alerts that redirec…

### CVE-2025-10351
**SQL injection vulnerability based on the melis-cms module of the Melis platform from Melis Technology.**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-08)

> SQL injection vulnerability based on the melis-cms module of the Melis platform from Melis Technology. This vulnerability allows an attacker to retrieve, create, update, and delete databases through the 'idPage' parameter in the '/melis/MelisCms/PageEdition/getTinyTemplates' endp…

### CVE-2025-10352
**Vulnerability in the melis-core module of Melis Technology's Melis Platform, which, if exploited, allows an unauthenticated attacker to c...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-08)

> Vulnerability in the melis-core module of Melis Technology's Melis Platform, which, if exploited, allows an unauthenticated attacker to create an administrator account via a request to '/melis/MelisCore/ToolUser/addNewUser'.

### CVE-2025-10353
**File upload leading to remote code execution (RCE) in the “melis-cms-slider” module of Melis Technology's Melis Platform.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-43
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-10-08)

> File upload leading to remote code execution (RCE) in the “melis-cms-slider” module of Melis Technology's Melis Platform. This vulnerability allows an attacker to upload a malicious file via a POST request to '/melis/MelisCmsSlider/MelisCmsSliderDetails/saveDetailsForm' using the…

### CVE-2025-10587
**The Community Events plugin for WordPress is vulnerable to SQL Injection via the event_category parameter in all versions up to, and incl...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-08)

> The Community Events plugin for WordPress is vulnerable to SQL Injection via the event_category parameter in all versions up to, and including, 1.5.1 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This ma…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-08*
