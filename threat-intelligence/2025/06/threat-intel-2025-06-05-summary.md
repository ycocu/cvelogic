# Daily Threat Intelligence — June 05, 2025

**Digest window (UTC):** 2025-06-05
**Generated:** 2026-06-02T07:32:50Z

## Threat brief

Google Chromium V8 added to CISA KEV — confirmed in-the-wild exploitation. · Vishalmathur Cloudclassroom-php Project: public exploit or PoC linked (SQL Injection) · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- Google Chromium V8 added to CISA KEV — confirmed in-the-wild exploitation.
- Vishalmathur Cloudclassroom-php Project: public exploit or PoC linked (SQL Injection)
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 5 |
| EPSS rise | 0 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2025-5419
**Google Chromium V8 Out-of-Bounds Read and Write Vulnerability**
- **Signals:** KEV
- **Asset:** google chrome
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T14:06:46.073
- **CWE:** CWE-125
- **Risk score:** 88
- **KEV:** added 2025-06-05

> Out of bounds read and write in V8 in Google Chrome prior to 137.0.7151.68 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page. (Chromium security severity: High)

### CVE-2025-24085
**Apple Multiple Products Use-After-Free Vulnerability**
- **Signals:** EXP
- **Asset:** apple ipados
- **Attack:** Use-After-Free
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T11:44:05.880
- **CWE:** CWE-416
- **Risk score:** 78
- **EXP:** ref published 2025-06-05

> A use after free issue was addressed with improved memory management. This issue is fixed in iOS 18.3 and iPadOS 18.3, iPadOS 17.7.6, macOS Sequoia 15.3, macOS Sonoma 14.7.5, macOS Ventura 13.7.5, tvOS 18.3, visionOS 2.3, watchOS 11.3. A malicious application may be able to eleva…

### CVE-2025-1793
**llamaindex llamaindex SQL Injection**
- **Signals:** CVSS
- **Asset:** llamaindex llamaindex
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-30T21:29:25.527
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-05)

> Multiple vector store integrations in run-llama/llama_index version v0.12.21 have SQL injection vulnerabilities. These vulnerabilities allow an attacker to read and write data using SQL, potentially leading to unauthorized access to data of other users depending on the usage of t…

### CVE-2022-2025
**grandstream gds3710_firmware**
- **Signals:** EXP
- **Asset:** grandstream gds3710_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:00:11.640
- **CWE:** CWE-121
- **CWE:** CWE-787
- **Risk score:** 78
- **EXP:** ref published 2025-06-05

> an attacker with knowledge of user/pass of Grandstream GSD3710 in its 1.0.11.13 version, could overflow the stack since it doesn't check the param length before use the strcopy instruction. The explotation of this vulnerability may lead an attacker to execute a shell with full ac…

### CVE-2025-30397
**Microsoft Windows Scripting Engine Type Confusion Vulnerability**
- **Signals:** EXP
- **Asset:** microsoft windows_10_1507
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-27T17:13:37.647
- **CWE:** CWE-843
- **Risk score:** 78
- **EXP:** ref published 2025-06-05

> Access of resource using incompatible type ('type confusion') in Microsoft Scripting Engine allows an unauthorized attacker to execute code over a network.

### CVE-2025-31650
**apache tomcat DoS**
- **Signals:** EXP
- **Asset:** apache tomcat
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2025-11-03T20:18:25.740
- **CWE:** CWE-459
- **CWE:** CWE-459
- **Risk score:** 78
- **EXP:** ref published 2025-06-05

> Improper Input Validation vulnerability in Apache Tomcat. Incorrect error handling for some invalid HTTP priority headers resulted in incomplete clean-up of the failed request which created a memory leak. A large number of such requests could trigger an OutOfMemoryException resul…

### CVE-2025-45542
**vishalmathur cloudclassroom-php_project SQL Injection**
- **Signals:** EXP
- **Asset:** vishalmathur cloudclassroom-php_project
- **Attack:** SQL Injection
- **CVSS max:** 7.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-13T17:45:40.463
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-06-05

> SQL injection vulnerability in the registrationform endpoint of CloudClassroom-PHP-Project v1.0. The pass parameter is vulnerable due to improper input validation, allowing attackers to inject SQL queries.

### CVE-2025-4568
**Improper neutralization of input provided by an unauthorized user into changes__reference_id parameter in URL allows for boolean-based Bl...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-05)

> Improper neutralization of input provided by an unauthorized user into changes__reference_id parameter in URL allows for boolean-based Blind SQL Injection attacks.

### CVE-2025-47966
**microsoft power_automate_for_desktop privilege escalation**
- **Signals:** CVSS
- **Asset:** microsoft power_automate_for_desktop
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-08T16:26:34.813
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-05)

> Exposure of sensitive information to an unauthorized actor in Power Automate allows an unauthorized attacker to elevate privileges over a network.

### CVE-2025-49008
**Atheos is a self-hosted browser-based cloud integrated development environment.**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-06-05)

> Atheos is a self-hosted browser-based cloud integrated development environment. Prior to version 6.0.4, improper use of `escapeshellcmd()` in `/components/codegit/traits/execute.php` allows argument injection, leading to arbitrary command execution. Atheos administrators and user…

### CVE-2025-5622
**dlink dir-816_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-816_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-06T15:42:38.880
- **CWE:** CWE-119
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-05)

> A vulnerability was found in D-Link DIR-816 1.10CNB05 and classified as critical. Affected by this issue is the function wirelessApcli_5g of the file /goform/wirelessApcli_5g. The manipulation of the argument apcli_mode_5g/apcli_enc_5g/apcli_default_key_5g leads to stack-based bu…

### CVE-2025-5623
**dlink dir-816_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-816_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-06T15:42:32.547
- **CWE:** CWE-119
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-05)

> A vulnerability was found in D-Link DIR-816 1.10CNB05. It has been classified as critical. This affects the function qosClassifier of the file /goform/qosClassifier. The manipulation of the argument dip_address/sip_address leads to stack-based buffer overflow. It is possible to i…

### CVE-2025-5624
**dlink dir-816_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-816_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-06T15:42:51.960
- **CWE:** CWE-119
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-05)

> A vulnerability was found in D-Link DIR-816 1.10CNB05. It has been declared as critical. This vulnerability affects the function QoSPortSetup of the file /goform/QoSPortSetup. The manipulation of the argument port0_group/port0_remarker/ssid0_group/ssid0_remarker leads to stack-ba…

### CVE-2025-5630
**dlink dir-816_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** dlink dir-816_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-06T15:15:04.173
- **CWE:** CWE-119
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-05)

> A vulnerability has been found in D-Link DIR-816 1.10CNB05 and classified as critical. This vulnerability affects unknown code of the file /goform/form2lansetup.cgi. The manipulation of the argument ip leads to stack-based buffer overflow. The attack can be initiated remotely. Th…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-05*
