# Daily Threat Intelligence — June 20, 2026

**Digest window (US Eastern, NVD):** 2026-06-20
**Generated:** 2026-06-21T09:42:47Z

## Threat brief

Microsoft Windows 2000 — exploitation likelihood rose sharply (EPSS 31% → 52% · rising (+21%)). · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows 2000 — exploitation likelihood rose sharply (EPSS 31% → 52% · rising (+21%)).
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 7 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2002-0693
**microsoft windows_2000 Buffer Overflow**
- **Signals:** EPSS
- **Asset:** microsoft windows_2000
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD published:** 2002-10-10
- **NVD modified:** 2026-06-16
- **Risk score:** 82
- **EPSS 31.3% (2026-06-15) → 52.4% (2026-06-20), Δ +21.1%**

> Buffer overflow in the HTML Help ActiveX Control (hhctrl.ocx) in Microsoft Windows 98, 98 Second Edition, Millennium Edition, NT 4.0, NT 4.0 Terminal Server Edition, Windows 2000, and Windows XP allows remote attackers to execute code via (1) a long parameter to the Alink functio…

### CVE-2002-0823
**microsoft windows_2000 Buffer Overflow**
- **Signals:** EPSS
- **Asset:** microsoft windows_help
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD published:** 2002-08-12
- **NVD modified:** 2026-06-16
- **Risk score:** 82
- **EPSS 26.2% (2026-06-15) → 44.4% (2026-06-20), Δ +18.2%**

> Buffer overflow in Winhlp32.exe allows remote attackers to execute arbitrary code via an HTML document that calls the HTML Help ActiveX control (HHCtrl.ocx) with a long pathname in the Item parameter.

### CVE-2026-48908
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD published:** 2026-06-20
- **NVD modified:** 2026-06-20
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-20)

> A vulnerability in the SP Page Builder for Joomla allows the upload of arbitrary files for unauthenticated users, ultimately resulting in PHP code upload and execution.

### CVE-2001-0341
**microsoft frontpage_server_extensions Buffer Overflow**
- **Signals:** EPSS
- **Asset:** microsoft frontpage_server_extensions
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD published:** 2001-07-21
- **NVD modified:** 2026-06-16
- **Risk score:** 82
- **EPSS 27.9% (2026-06-15) → 45.1% (2026-06-20), Δ +17.2%**

> Buffer overflow in Microsoft Visual Studio RAD Support sub-component of FrontPage Server Extensions allows remote attackers to execute arbitrary commands via a long registration request (URL) to fp30reg.dll.

### CVE-2001-0348
**microsoft windows_2000 DoS**
- **Signals:** EPSS
- **Asset:** microsoft windows_2000
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD published:** 2001-07-21
- **NVD modified:** 2026-06-16
- **Risk score:** 78
- **EPSS 17.2% (2026-06-15) → 29.7% (2026-06-20), Δ +12.5%**

> Microsoft Windows 2000 telnet service allows attackers to cause a denial of service (crash) via a long logon command that contains a backspace.

### CVE-2001-0951
**microsoft windows_2000 DoS**
- **Signals:** EPSS
- **Asset:** microsoft windows_2000
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD published:** 2001-12-07
- **NVD modified:** 2026-06-16
- **Risk score:** 78
- **EPSS 25.2% (2026-06-15) → 40.8% (2026-06-20), Δ +15.6%**

> Windows 2000 allows remote attackers to cause a denial of service (CPU consumption) by flooding Internet Key Exchange (IKE) UDP port 500 with packets that contain a large number of dot characters.

### CVE-2001-1244
**freebsd freebsd DoS**
- **Signals:** EPSS
- **Asset:** freebsd freebsd
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD published:** 2001-07-07
- **NVD modified:** 2026-06-16
- **Risk score:** 78
- **EPSS 20.7% (2026-06-15) → 35.3% (2026-06-20), Δ +14.6%**

> Multiple TCP implementations could allow remote attackers to cause a denial of service (bandwidth and CPU exhaustion) by setting the maximum segment size (MSS) to a very small number and requesting large amounts of data, which generates more packets with less TCP-level data that …

### CVE-2004-1306
**microsoft windows_2000 Buffer Overflow**
- **Signals:** EPSS
- **Asset:** microsoft windows_2000
- **Attack:** Buffer Overflow
- **CVSS max:** 5.1
- **NVD status:** Modified
- **NVD published:** 2004-12-31
- **NVD modified:** 2026-06-16
- **Risk score:** 79
- **EPSS 19.6% (2026-06-15) → 34.5% (2026-06-20), Δ +14.9%**

> Heap-based buffer overflow in winhlp32.exe in Windows NT, Windows 2000 through SP4, Windows XP through SP2, and Windows 2003 allows remote attackers to execute arbitrary code via a crafted .hlp file.

### CVE-2019-25763
**WordPress Ultimate Addons for Beaver Builder 1.2.4.1 contains an authentication bypass vulnerability that allows attackers to gain unauth...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-20
- **NVD modified:** 2026-06-20
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-20)

> WordPress Ultimate Addons for Beaver Builder 1.2.4.1 contains an authentication bypass vulnerability that allows attackers to gain unauthorized access by exploiting the social media login form functionality. Attackers can submit a POST request to the admin-ajax.php endpoint with …

### CVE-2022-50972
**WooCommerce 7.1.0 contains a remote code execution vulnerability that allows attackers to execute arbitrary PHP code by injecting shell c...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-20
- **NVD modified:** 2026-06-20
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-20)

> WooCommerce 7.1.0 contains a remote code execution vulnerability that allows attackers to execute arbitrary PHP code by injecting shell commands through the product-type parameter. Attackers can send requests to the class-wc-meta-box-product-images.php endpoint with unsanitized p…

### CVE-2024-58351
**Flowise before 2.1.4 allows configuration to be injected into the Chainflow during execution via the overrideConfig option, supported in...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-20
- **NVD modified:** 2026-06-20
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-20)

> Flowise before 2.1.4 allows configuration to be injected into the Chainflow during execution via the overrideConfig option, supported in both the frontend web integration and the backend Prediction API. Because this feature is enabled by default with no allow-list of permitted va…

### CVE-2026-48909
**SP LMS (com_splms) < 4.1.4 by JoomShaper deserializes user-controlled cookie data without validation, enabling an unauthenticated remote...**
- **Signals:** CVSS
- **Attack:** unsafe deserialization
- **CVSS max:** 9.5
- **NVD status:** Received
- **NVD published:** 2026-06-20
- **NVD modified:** 2026-06-20
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-06-20)

> SP LMS (com_splms) < 4.1.4 by JoomShaper deserializes user-controlled cookie data without validation, enabling an unauthenticated remote attacker to execute arbitrary code on the server.

### CVE-2026-48939
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD published:** 2026-06-20
- **NVD modified:** 2026-06-20
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-20)

> A vulnerability in the iCagenda extension for Joomla allows the upload of arbitrary files in the file attachment feature, ultimately resulting in PHP code upload and execution.

### CVE-2026-5366
**Prefect version 3.6.23 is vulnerable to remote code execution due to improper handling of user-controlled input in the `GitRepository` st...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Received
- **NVD published:** 2026-06-20
- **NVD modified:** 2026-06-20
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-20)

> Prefect version 3.6.23 is vulnerable to remote code execution due to improper handling of user-controlled input in the `GitRepository` storage class. The `commit_sha` parameter, which is passed to git commands, lacks validation and does not include a `--` separator to distinguish…

### CVE-2026-56345
**AVideo through 29.0 contains an authorization bypass vulnerability in the Meet plugin's uploadRecordedVideo.json.php endpoint that derive...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.2
- **NVD status:** Received
- **NVD published:** 2026-06-20
- **NVD modified:** 2026-06-20
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-20)

> AVideo through 29.0 contains an authorization bypass vulnerability in the Meet plugin's uploadRecordedVideo.json.php endpoint that derives the target users_id from the uploaded filename without verification. An attacker with knowledge of the Meet shared secret can craft a malicio…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-20*
