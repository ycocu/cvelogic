# Daily Threat Intelligence — August 22, 2025

**Digest window (UTC):** 2025-08-22
**Generated:** 2026-06-02T07:33:17Z

## Threat brief

Gnu Mailman — exploitation likelihood rose sharply (EPSS 20% → 41% · rising (+21%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Gnu Mailman — exploitation likelihood rose sharply (EPSS 20% → 41% · rising (+21%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2002-0855
**gnu mailman XSS**
- **Signals:** EPSS
- **Asset:** gnu mailman
- **Attack:** XSS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 82
- **EPSS 20.0% (2025-03-30) → 41.0% (2025-08-22), Δ +21.0%**

> Cross-site scripting vulnerability in Mailman before 2.0.12 allows remote attackers to execute script as other users via a subscriber's list subscription options in the (1) adminpw or (2) info parameters to the ml-name feature.

### CVE-2002-2385
**hotfoon_corporation hotfoon Buffer Overflow**
- **Signals:** EPSS
- **Asset:** hotfoon_corporation hotfoon
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 4.5% (2025-08-19) → 17.6% (2025-08-22), Δ +13.1%**

> Buffer overflow in hotfoon4.exe in Hotfoon 4.0 allows remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via a URL containing a long voice phone number.

### CVE-2022-31491
**Voltronic Power ViewPower through 1.04-24215, ViewPower Pro through 2.0-22165, and PowerShield Netguard before 1.04-23292 allows a remote...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-08-22)

> Voltronic Power ViewPower through 1.04-24215, ViewPower Pro through 2.0-22165, and PowerShield Netguard before 1.04-23292 allows a remote attacker to run arbitrary code via an unspecified web interface related to detection of a managed UPS shutting down. An unauthenticated attack…

### CVE-2022-43110
**Voltronic Power ViewPower through 1.04-21353 and PowerShield Netguard before 1.04-23292 allows a remote attacker to configure the system...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-22)

> Voltronic Power ViewPower through 1.04-21353 and PowerShield Netguard before 1.04-23292 allows a remote attacker to configure the system via an unspecified web interface. An unauthenticated remote attacker can make changes to the system including: changing the web interface admin…

### CVE-2022-45134
**mahara mahara Code Execution**
- **Signals:** CVSS
- **Asset:** mahara mahara
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-08T16:33:05.117
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-22)

> Mahara 21.10 before 21.10.6, 22.04 before 22.04.4, and 22.10 before 22.10.1 deserializes user input unsafely during skin import. A particularly structured XML file could cause code execution when being processed.

### CVE-2024-52786
**An authentication bypass vulnerability in anji-plus AJ-Report up to v1.4.2 allows unauthenticated attackers to execute arbitrary code via...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-22)

> An authentication bypass vulnerability in anji-plus AJ-Report up to v1.4.2 allows unauthenticated attackers to execute arbitrary code via a crafted URL.

### CVE-2024-53496
**winterchens my-site**
- **Signals:** CVSS
- **Asset:** winterchens my-site
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-12T19:39:33.820
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-22)

> Incorrect access control in the doFilter function of my-site v1.0.2.RELEASE allows attackers to access sensitive components without authentication.

### CVE-2024-53499
**jeewms jeewms SQL Injection**
- **Signals:** CVSS
- **Asset:** jeewms jeewms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-09T19:12:21.917
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-22)

> Jeewms v3.7 was discovered to contain a SQL injection vulnerability via the CgReportController API.

### CVE-2025-26496
**tableau tableau_server**
- **Signals:** CVSS
- **Asset:** tableau tableau_server
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-04T15:48:41.980
- **CWE:** CWE-843
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-22)

> Access of Resource Using Incompatible Type ('Type Confusion') vulnerability in Salesforce Tableau Server, Tableau Desktop on Windows, Linux (File Upload modules) allows Local Code Inclusion.This issue affects Tableau Server, Tableau Desktop: before 2025.1.3, before 2024.2.12, bef…

### CVE-2025-4609
**google chrome**
- **Signals:** CVSS
- **Asset:** google chrome
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-25T20:44:35.443
- **CWE:** CWE-732
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-08-22)

> Incorrect handle provided in unspecified circumstances in Mojo in Google Chrome on Windows prior to 136.0.7103.113 allowed a remote attacker to potentially perform a sandbox escape via a malicious file. (Chromium security severity: High)

### CVE-2025-51092
**vishnusivadas login-signup SQL Injection**
- **Signals:** CVSS
- **Asset:** vishnusivadas login-signup
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-09T18:00:31.943
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-22)

> The LogIn-SignUp project by VishnuSivadasVS is vulnerable to SQL Injection due to unsafe construction of SQL queries in DataBase.php. The functions logIn() and signUp() build queries by directly concatenating user input and unvalidated table names without using prepared statement…

### CVE-2025-55613
**tenda o3_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** tenda o3_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-03T14:47:54.063
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-22)

> Tenda O3V2 1.0.0.12(3880) is vulnerable to Buffer Overflow in the fromSafeSetMacFilter function via the mac parameter.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-22*
