# Daily Threat Intelligence — August 20, 2025

**Digest window (UTC):** 2025-08-20
**Generated:** 2026-06-02T07:33:16Z

## Threat brief

Adobe Edge — exploitation likelihood rose sharply (EPSS 45% → 66% · rising (+20%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Adobe Edge — exploitation likelihood rose sharply (EPSS 45% → 66% · rising (+20%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 7 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **17** |


## CVEs

### CVE-2016-4108
**adobe edge**
- **Signals:** EPSS
- **Asset:** microsoft edge
- **CVSS max:** 7.6
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 82
- **EPSS 45.3% (2025-03-30) → 65.6% (2025-08-20), Δ +20.3%**

> Unspecified vulnerability in Adobe Flash Player 21.0.0.213 and earlier, as used in the Adobe Flash libraries in Microsoft Internet Explorer 10 and 11 and Microsoft Edge, has unknown impact and attack vectors, a different vulnerability than other CVEs listed in MS16-064.

### CVE-2015-2098
**webgateinc edvr_manager Buffer Overflow**
- **Signals:** EPSS
- **Asset:** webgateinc edvr_manager
- **Attack:** Buffer Overflow
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T02:26:47.513
- **CWE:** CWE-120
- **Risk score:** 84
- **EPSS 25.6% (2025-08-02) → 41.5% (2025-08-20), Δ +15.9%**

> Multiple stack-based buffer overflows in WebGate eDVR Manager allow remote attackers to execute arbitrary code via unspecified vectors to the (1) Connect, (2) ConnectEx, or (3) ConnectEx2 function in the WESPEvent.WESPEventCtrl.1 control; (4) AudioOnlySiteChannel function in the …

### CVE-2025-50901
**jeewms jeewms Auth Bypass**
- **Signals:** CVSS
- **Asset:** jeewms jeewms
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-11T19:18:46.033
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-20)

> JeeWMS 771e4f5d0c01ffdeae1671be4cf102b73a3fe644 (2025-05-19) contains incorrect authentication bypass vulnerability, which can lead to arbitrary file reading.

### CVE-2002-2195
**nullsoft winamp Buffer Overflow**
- **Signals:** EPSS
- **Asset:** nullsoft winamp
- **Attack:** Buffer Overflow
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 5.4% (2025-03-30) → 20.6% (2025-08-20), Δ +15.2%**

> Buffer overflow in the version update check for Winamp 2.80 and earlier allows remote attackers who can spoof www.winamp.com to execute arbitrary code via a long server response.

### CVE-2002-2232
**mollensoft_software enceladus_server_suite Buffer Overflow**
- **Signals:** EPSS
- **Asset:** mollensoft_software enceladus_server_suite
- **Attack:** Buffer Overflow
- **CVSS max:** 8.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-119
- **Risk score:** 84
- **EPSS 6.4% (2025-08-02) → 21.6% (2025-08-20), Δ +15.2%**

> Buffer overflow in Enceladus Server Suite 3.9 allows remote attackers to execute arbitrary code via a long CD (CWD) command.

### CVE-2005-2968
**mozilla firefox**
- **Signals:** EPSS
- **Asset:** mozilla firefox
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 32.8% (2025-03-30) → 45.9% (2025-08-20), Δ +13.1%**

> Firefox 1.0.6 and Mozilla 1.7.10 allows attackers to execute arbitrary commands via shell metacharacters in a URL that is provided to the browser on the command line, which is sent unfiltered to bash.

### CVE-2006-4455
**xchat xchat DoS**
- **Signals:** EPSS
- **Asset:** xchat xchat
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 35.3% (2025-06-10) → 47.5% (2025-08-20), Δ +12.2%**

> Unspecified vulnerability in Xchat 2.6.7 and earlier allows remote attackers to cause a denial of service (crash) via unspecified vectors involving the PRIVMSG command.  NOTE: the vendor has disputed this vulnerability, stating that it does not affect 2.6.7 "or any recent version…

### CVE-2008-5359
**sun jdk Buffer Overflow**
- **Signals:** EPSS
- **Asset:** sun jre
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 24.8% (2025-07-01) → 35.1% (2025-08-20), Δ +10.3%**

> Buffer overflow in Java Runtime Environment (JRE) for Sun JDK and JRE 6 Update 10 and earlier; JDK and JRE 5.0 Update 16 and earlier; SDK and JRE 1.4.2_18 and earlier; and SDK and JRE 1.3.1_23 and earlier might allow remote attackers to execute arbitrary code, related to a Convol…

### CVE-2024-57154
**Incorrect access control in dts-shop v0.0.1-SNAPSHOT allows attackers to bypass authentication via sending a crafted payload to /admin/au...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-20)

> Incorrect access control in dts-shop v0.0.1-SNAPSHOT allows attackers to bypass authentication via sending a crafted payload to /admin/auth/index.

### CVE-2024-57155
**Incorrect access control in radar v1.0.8 allows attackers to bypass authentication and access sensitive APIs without a token.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-20)

> Incorrect access control in radar v1.0.8 allows attackers to bypass authentication and access sensitive APIs without a token.

### CVE-2025-50904
**winterchens my-site Auth Bypass**
- **Signals:** CVSS
- **Asset:** winterchens my-site
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-11T19:17:48.867
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-20)

> There is an authentication bypass vulnerability in WinterChenS my-site thru commit 6c79286 (2025-06-11). An attacker can exploit this vulnerability to access /admin/ API without any token.

### CVE-2025-55444
**vishalmathur online_artwork_and_fine_arts_project RCE**
- **Signals:** CVSS
- **Asset:** vishalmathur online_artwork_and_fine_arts_project
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-11T19:16:58.240
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-20)

> A SQL injection vulnerability exists in the id2 parameter of the cancel_booking.php page in Online Artwork and Fine Arts MCA Project 1.0. A remote attacker can inject arbitrary SQL queries, leading to database enumeration and potential remote code execution.

### CVE-2025-55746
**monospace directus SQL injection**
- **Signals:** CVSS
- **Asset:** monospace directus
- **Attack:** SQL injection
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-13T18:29:53.387
- **CWE:** CWE-73
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-20)

> Directus is a real-time API and App dashboard for managing SQL database content. From 10.8.0 to before 11.9.3, a vulnerability exists in the file update mechanism which allows an unauthenticated actor to modify existing files with arbitrary contents (without changes being applied…

### CVE-2025-8610
**aomei cyber_backup RCE**
- **Signals:** CVSS
- **Asset:** aomei cyber_backup
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-25T01:57:35.273
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-20)

> AOMEI Cyber Backup Missing Authentication for Critical Function Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of AOMEI Cyber Backup. Authentication is not required to exploit this vulnerability.…

### CVE-2025-8611
**aomeitech cyber_backup RCE**
- **Signals:** CVSS
- **Asset:** aomeitech cyber_backup
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-22T21:49:07.970
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-20)

> AOMEI Cyber Backup Missing Authentication for Critical Function Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of AOMEI Cyber Backup. Authentication is not required to exploit this vulnerability.…

### CVE-2025-9287
**browserify cipher-base**
- **Signals:** CVSS
- **Asset:** browserify cipher-base
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T19:16:17.187
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-20)

> Improper Input Validation vulnerability in cipher-base allows Input Data Manipulation.This issue affects cipher-base: through 1.0.4.

### CVE-2025-9288
**browserify sha.js**
- **Signals:** CVSS
- **Asset:** browserify sha.js
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T19:16:17.300
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-20)

> Improper Input Validation vulnerability in sha.js allows Input Data Manipulation.This issue affects sha.js: through 2.4.11.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-20*
