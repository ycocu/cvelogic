# Daily Threat Intelligence — December 11, 2025

**Digest window (UTC):** 2025-12-11
**Generated:** 2026-06-02T07:33:57Z

## Threat brief

OSGeo GeoServer added to CISA KEV — confirmed in-the-wild exploitation. · Tenda W6-s Firmware — exploitation likelihood rose sharply (EPSS 6.6% → 18% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- OSGeo GeoServer added to CISA KEV — confirmed in-the-wild exploitation.
- Tenda W6-s Firmware — exploitation likelihood rose sharply (EPSS 6.6% → 18% · rising (+12%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2025-58360
**OSGeo GeoServer Improper Restriction of XML External Entity Reference Vulnerability**
- **Signals:** KEV
- **Asset:** geoserver geoserver
- **Attack:** XXE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-12T13:54:01.187
- **CWE:** CWE-611
- **Risk score:** 88
- **KEV:** added 2025-12-11

> GeoServer is an open source server that allows users to share and edit geospatial data. From version 2.26.0 to before 2.26.2 and before 2.25.6, an XML External Entity (XXE) vulnerability was identified. The application accepts XML input through a specific endpoint /geoserver/wms …

### CVE-2022-45497
**tenda w6-s_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** tenda w6-s_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-04-23T15:15:53.980
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 6.6% (2025-12-10) → 18.4% (2025-12-11), Δ +11.8%**

> Tenda W6-S v1.0.0.4(510) was discovered to contain a command injection vulnerability in the tpi_get_ping_output function at /goform/exeCommand.

### CVE-2025-64721
**sandboxie-plus sandboxie**
- **Signals:** CVSS
- **Asset:** sandboxie-plus sandboxie
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-22T18:44:17.920
- **CWE:** CWE-190
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-11)

> Sandboxie is a sandbox-based isolation software for 32-bit and 64-bit Windows NT-based operating systems. In versions 1.16.6 and below, the SYSTEM-level service SbieSvc.exe exposes SbieIniServer::RC4Crypt to sandboxed processes. The handler adds a fixed header size to a caller-co…

### CVE-2024-58286
**dizqueTV 1.5.3 contains a remote code execution vulnerability that allows attackers to inject arbitrary commands through the FFMPEG Execu...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-11)

> dizqueTV 1.5.3 contains a remote code execution vulnerability that allows attackers to inject arbitrary commands through the FFMPEG Executable Path settings. Attackers can modify the executable path with shell commands to read system files like /etc/passwd by exploiting improper …

### CVE-2024-58290
**Xhibiter NFT Marketplace 1.10.2 contains a SQL injection vulnerability in the collections endpoint that allows attackers to manipulate da...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-11)

> Xhibiter NFT Marketplace 1.10.2 contains a SQL injection vulnerability in the collections endpoint that allows attackers to manipulate database queries through the 'id' parameter. Attackers can exploit boolean-based, time-based, and UNION-based SQL injection techniques to potenti…

### CVE-2024-58298
**Compuware iStrobe Web 20.13 contains a pre-authentication remote code execution vulnerability that allows unauthenticated attackers to up...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-12-11)

> Compuware iStrobe Web 20.13 contains a pre-authentication remote code execution vulnerability that allows unauthenticated attackers to upload malicious JSP files through a path traversal in the file upload form. Attackers can exploit the 'fileName' parameter to upload a web shell…

### CVE-2024-58301
**Purei CMS 1.0 contains a time-based blind SQL injection vulnerability that allows attackers to manipulate database queries through unfilt...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-11)

> Purei CMS 1.0 contains a time-based blind SQL injection vulnerability that allows attackers to manipulate database queries through unfiltered user input parameters. Attackers can exploit vulnerable endpoints like getAllParks.php and events-ajax.php by injecting crafted SQL payloa…

### CVE-2024-58307
**cszcms csz_cms SQL Injection**
- **Signals:** CVSS
- **Asset:** cszcms csz_cms
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-22T18:40:40.883
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-11)

> CSZCMS 1.3.0 contains an authenticated SQL injection vulnerability in the members view functionality that allows authenticated attackers to manipulate database queries. Attackers can inject malicious SQL code through the view parameter to potentially execute time-based blind SQL …

### CVE-2024-58308
**opensolution quick_cms SQL Injection**
- **Signals:** CVSS
- **Asset:** opensolution quick_cms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-31T18:30:13.567
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-11)

> Quick.CMS 6.7 contains a SQL injection vulnerability that allows unauthenticated attackers to bypass login authentication by manipulating the login form. Attackers can inject specific SQL payloads like ' or '1'='1 to gain unauthorized administrative access to the system.

### CVE-2025-13780
**pgadmin pgadmin_4 RCE**
- **Signals:** CVSS
- **Asset:** pgadmin pgadmin_4
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T19:51:13.657
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-11)

> pgAdmin versions up to 9.10 are affected by a Remote Code Execution (RCE) vulnerability that occurs when running in server mode and performing restores from PLAIN-format dump files. This issue allows attackers to inject and execute arbitrary commands on the server hosting pgAdmin…

### CVE-2025-36937
**google android RCE**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-05T21:16:10.410
- **CWE:** CWE-787
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-11)

> In AudioDecoder::HandleProduceRequest of audio_decoder.cc, there is a possible out of bounds write due to an incorrect bounds check. This could lead to remote code execution with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2025-66048
**libbiosig_project libbiosig RCE**
- **Signals:** CVSS
- **Asset:** libbiosig_project libbiosig
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-17T20:23:57.247
- **CWE:** CWE-121
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-11)

> Several stack-based buffer overflow vulnerabilities exists in the MFER parsing functionality of The Biosig Project libbiosig 3.9.1. A specially crafted MFER file can lead to arbitrary code execution. An attacker can provide a malicious file to trigger these vulnerabilities.When T…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-11*
