# Daily Threat Intelligence — May 12, 2025

**Digest window (UTC):** 2025-05-12
**Generated:** 2026-06-02T07:32:42Z

## Threat brief

TeleMessage TM SGNL added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- TeleMessage TM SGNL added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2025-47729
**TeleMessage TM SGNL Hidden Functionality Vulnerability**
- **Signals:** KEV
- **Asset:** telemessage text_message_archiver
- **CVSS max:** 4.9
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:26:39.130
- **CWE:** CWE-912
- **Risk score:** 88
- **KEV:** added 2025-05-12

> The TeleMessage archiving backend through 2025-05-05 holds cleartext copies of messages from TM SGNL (aka Archive Signal) app users, which is different functionality than described in the TeleMessage "End-to-End encryption from the mobile phone through to the corporate archive" d…

### CVE-2025-44830
**engineercms_project engineercms SQL Injection**
- **Signals:** CVSS
- **Asset:** engineercms_project engineercms
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-13T13:49:14.850
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-12)

> EngineerCMS v1.02 through v.2.0.5 has a SQL injection vulnerability in the /project/addprojtemplet interface.

### CVE-2025-45779
**tenda ac10_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** tenda ac10_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-13T13:40:52.883
- **CWE:** CWE-120
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-12)

> Tenda AC10 V1.0re_V15.03.06.46 is vulnerable to Buffer Overflow in the formSetPPTPUserList handler via the list POST parameter.

### CVE-2024-56523
**radware cloud_waf**
- **Signals:** CVSS
- **Asset:** radware cloud_waf
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-01T20:03:38.823
- **CWE:** CWE-444
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-12)

> Radware Cloud Web Application Firewall (WAF) before 2025-05-07 allows remote attackers to bypass firewall filters by placing random data in the HTTP request body when using the HTTP GET method.

### CVE-2024-56524
**radware cloud_waf**
- **Signals:** CVSS
- **Asset:** radware cloud_waf
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-01T19:51:36.820
- **CWE:** CWE-116
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-12)

> Radware Cloud Web Application Firewall (WAF) before 2025-05-07 allows remote attackers to bypass firewall filters by adding a special character to the request.

### CVE-2025-26846
**znuny znuny**
- **Signals:** CVSS
- **Asset:** znuny znuny
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-13T13:51:43.497
- **CWE:** CWE-862
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-12)

> An issue was discovered in Znuny before 7.1.4. Permissions are not checked properly when using the Generic Interface to update ticket metadata.

### CVE-2025-30436
**apple ipados**
- **Signals:** CVSS
- **Asset:** apple ipados
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-05-27T13:58:06.607
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-12)

> This issue was addressed by restricting options offered on a locked device. This issue is fixed in iOS 18.4 and iPadOS 18.4. An attacker may be able to use Siri to enable Auto-Answer Calls.

### CVE-2025-30448
**apple ipados**
- **Signals:** CVSS
- **Asset:** apple ipados
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-04-02T19:19:38.797
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-05-12)

> This issue was addressed with additional entitlement checks. This issue is fixed in iOS 18.5 and iPadOS 18.5, iPadOS 17.7.7, macOS Sequoia 15.4, macOS Sonoma 14.7.6, macOS Ventura 13.7.6, visionOS 2.5. An attacker may be able to turn on sharing of an iCloud folder without authent…

### CVE-2025-3659
**Improper authentication handling was identified in a set of HTTP POST requests affecting the following product families: * Digi PortServe...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-05-12)

> Improper authentication handling was identified in a set of HTTP POST requests affecting the following product families: 

  *  Digi PortServer TS - prior to and including 82000747_AA, build date 06/17/2022


  *  Digi One SP/Digi One SP IA/Digi One IA - prior to and including 82…

### CVE-2025-44022
**vvveb vvveb**
- **Signals:** CVSS
- **Asset:** vvveb vvveb
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-23T19:15:17.153
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-05-12)

> An issue in vvveb CMS v.1.0.6 allows a remote attacker to execute arbitrary code via the Plugin mechanism.

### CVE-2025-47682
**cozyvision sms_alert_order_notifications SQL Injection**
- **Signals:** CVSS
- **Asset:** cozyvision sms_alert_order_notifications
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T10:16:48.010
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-05-12)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Cozy Vision SMS Alert Order Notifications sms-alert allows SQL Injection.This issue affects SMS Alert Order Notifications: from n/a through <= 3.8.1.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-05-12*
