# Daily Threat Intelligence — December 10, 2025

**Digest window (UTC):** 2025-12-10
**Generated:** 2026-06-02T07:33:57Z

## Threat brief

10 new critical disclosures — review patch status on exposed services.

## Executive summary

- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-65294
**aqara camera_hub_g3_firmware**
- **Signals:** CVSS
- **Asset:** aqara hub_m2_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-17T19:51:48.547
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-10)

> Aqara Hub devices including Camera Hub G3 4.1.9_0027, Hub M2 4.3.6_0027, and Hub M3 4.3.6_0025 contain an undocumented remote access mechanism enabling unrestricted remote command execution.

### CVE-2025-65820
**meatmeet meatmeet**
- **Signals:** CVSS
- **Asset:** meatmeet meatmeet
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-17T20:03:27.400
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-10)

> An issue was discovered in Meatmeet Android Mobile Application 1.1.2.0. An exported activity can be spawned with the mobile application which opens a hidden page. This page, which is not available through the normal flows of the application, contains several devices which can be …

### CVE-2025-65823
**meatmeet meatmeet_pro_wifi_\&_bluetooth_meat_thermometer_firmware**
- **Signals:** CVSS
- **Asset:** meatmeet meatmeet_pro_wifi_\&_bluetooth_meat_thermometer_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-21T19:06:43.440
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-10)

> The Meatmeet Pro was found to be shipped with hardcoded Wi-Fi credentials in the firmware, for the test network it was developed on. If an attacker retrieved this, and found the physical location of the Wi-Fi network, they could gain unauthorized access to the Wi-Fi network of th…

### CVE-2020-36897
**howfor qihang_media_web_digital_signage RCE**
- **Signals:** CVSS
- **Asset:** howfor qihang_media_web_digital_signage
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-17T19:17:14.927
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-10)

> QiHang Media Web Digital Signage 3.0.9 contains an unauthenticated remote code execution vulnerability in the QH.aspx file that allows attackers to upload malicious ASPX scripts. Attackers can exploit the file upload functionality by using the 'remotePath' and 'fileToUpload' para…

### CVE-2020-36902
**medivision medivision_digital_signage_firmware privilege escalation**
- **Signals:** CVSS
- **Asset:** medivision medivision_digital_signage_firmware
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-30T20:31:06.793
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-10)

> UBICOD Medivision Digital Signage 1.5.1 contains an authorization bypass vulnerability that allows normal users to escalate privileges by manipulating the 'ft[grp]' parameter. Attackers can send a GET request to /html/user with 'ft[grp]' set to integer value '3' to gain super adm…

### CVE-2025-65826
**meatmeet meatmeet**
- **Signals:** CVSS
- **Asset:** meatmeet meatmeet
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-30T19:14:23.113
- **CWE:** CWE-312
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-10)

> The mobile application was found to contain stored credentials for the network it was developed on. If an attacker retrieved this, and found the physical location of the Wi-Fi network, they could gain unauthorized access to the Wi-Fi network of the vendor. Additionally, if an att…

### CVE-2025-65827
**meatmeet meatmeet**
- **Signals:** CVSS
- **Asset:** meatmeet meatmeet
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-30T19:09:32.150
- **CWE:** CWE-319
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-10)

> The mobile application is configured to allow clear text traffic to all domains and communicates with an API server over HTTP. As a result, an adversary located "upstream" can intercept the traffic, inspect its contents, and modify the requests in transit. TThis may result in a t…

### CVE-2025-65830
**meatmeet meatmeet**
- **Signals:** CVSS
- **Asset:** meatmeet meatmeet
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-30T18:46:13.740
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-10)

> Due to a lack of certificate validation, all traffic from the mobile application can be intercepted. As a result, an adversary located "upstream" can decrypt the TLS traffic, inspect its contents, and modify the requests in transit. This may result in a total compromise of the us…

### CVE-2025-65950
**wbce wbce_cms SQL injection**
- **Signals:** CVSS
- **Asset:** wbce wbce_cms
- **Attack:** SQL injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T15:10:47.943
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-12-10)

> WBCE CMS is a content management system. In versions 1.6.4 and below, the user management module allows a low-privileged authenticated user with permissions to modify users to execute arbitrary SQL queries. This can be escalated to a full database compromise, data exfiltration, e…

### CVE-2025-67510
**neuron-ai neuron SQL injection**
- **Signals:** CVSS
- **Asset:** neuron-ai neuron
- **Attack:** SQL injection
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-06T19:28:43.897
- **CWE:** CWE-250
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-12-10)

> Neuron is a PHP framework for creating and orchestrating AI Agents. In versions 2.8.11 and below, the MySQLWriteTool executes arbitrary SQL provided by the caller using PDO::prepare() + execute() without semantic restrictions. This is consistent with the name (“write tool”), but …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-10*
