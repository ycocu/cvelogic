# Daily Threat Intelligence — June 09, 2025

**Digest window (UTC):** 2025-06-09
**Generated:** 2026-06-02T07:32:51Z

## Threat brief

Erlang/OTP added to CISA KEV — confirmed in-the-wild exploitation. · Microsoft Windows 11 22h2: public exploit or PoC linked (privilege escalation) · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Erlang/OTP added to CISA KEV — confirmed in-the-wild exploitation.
- Microsoft Windows 11 22h2: public exploit or PoC linked (privilege escalation)
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 4 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2024-42009
**RoundCube Webmail Cross-Site Scripting Vulnerability**
- **Signals:** KEV
- **Asset:** roundcube webmail
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-04T15:01:04.997
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 88
- **KEV:** added 2025-06-09

> A Cross-Site Scripting vulnerability in Roundcube through 1.5.7 and 1.6.x through 1.6.7 allows a remote attacker to steal and send emails of a victim via a crafted e-mail message that abuses a Desanitization issue in message_body() in program/actions/mail/show.php.

### CVE-2024-0725
**prosshd prosshd DoS**
- **Signals:** EXP
- **Asset:** prosshd prosshd
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:47:13.437
- **CWE:** CWE-404
- **Risk score:** 78
- **EXP:** ref published 2025-06-09

> A vulnerability was found in ProSSHD 1.2 on Windows. It has been declared as problematic. This vulnerability affects unknown code. The manipulation leads to denial of service. The attack can be initiated remotely. The exploit has been disclosed to the public and may be used. The …

### CVE-2025-48123
**Improper Control of Generation of Code ('Code Injection') vulnerability in Holest Engineering Spreadsheet Price Changer for WooCommerce a...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:30:50.233
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-09)

> Improper Control of Generation of Code ('Code Injection') vulnerability in Holest Engineering Spreadsheet Price Changer for WooCommerce and WP E-commerce – Light excel-like-price-change-for-woocommerce-and-wp-e-commerce-light allows Code Injection.This issue affects Spreadsheet P…

### CVE-2024-42049
**TightVNC (Server for Windows) before 2.8.84 allows attackers to connect to the control pipe via a network connection.**
- **Signals:** EXP
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 78
- **EXP:** ref published 2025-06-09

> TightVNC (Server for Windows) before 2.8.84 allows attackers to connect to the control pipe via a network connection.

### CVE-2024-55661
**laravel pulse RCE**
- **Signals:** EXP
- **Asset:** laravel pulse
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-25T18:30:20.253
- **CWE:** CWE-94
- **Risk score:** 78
- **EXP:** ref published 2025-06-09

> Laravel Pulse is a real-time application performance monitoring tool and dashboard for Laravel applications. A vulnerability has been discovered in Laravel Pulse prior to version 1.3.1 that could allow remote code execution through the public `remember()` method in the `Laravel\P…

### CVE-2025-24076
**microsoft windows_11_22h2 privilege escalation**
- **Signals:** EXP
- **Asset:** microsoft windows_11_22h2
- **Attack:** privilege escalation
- **CVSS max:** 7.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-07T17:24:22.777
- **CWE:** CWE-284
- **Risk score:** 78
- **EXP:** ref published 2025-06-09

> Improper access control in Windows Cross Device Service allows an authorized attacker to elevate privileges locally.

### CVE-2025-30184
**cyberdata 011209_sip_emergency_intercom_firmware**
- **Signals:** CVSS
- **Asset:** cyberdata 011209_sip_emergency_intercom_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-12T14:22:08.940
- **CWE:** CWE-288
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-09)

> CyberData 011209 Intercom could allow an unauthenticated user access to the Web Interface through an alternate path.

### CVE-2025-30515
**cyberdata 011209_sip_emergency_intercom_firmware**
- **Signals:** CVSS
- **Asset:** cyberdata 011209_sip_emergency_intercom_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-12T14:21:22.130
- **CWE:** CWE-35
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-09)

> CyberData 011209 Intercom
 
could allow an authenticated attacker to upload arbitrary files to multiple locations within the system.

### CVE-2025-32433
**Erlang Erlang/OTP SSH Server Missing Authentication for Critical Function Vulnerability**
- **Signals:** KEV
- **Asset:** erlang erlang\/otp
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-04T14:49:05.177
- **CWE:** CWE-306
- **Risk score:** 88
- **KEV:** added 2025-06-09

> Erlang/OTP is a set of libraries for the Erlang programming language. Prior to versions OTP-27.3.3, OTP-26.2.5.11, and OTP-25.3.2.20, a SSH server may allow an attacker to perform unauthenticated remote code execution (RCE). By exploiting a flaw in SSH protocol message handling, …

### CVE-2025-48122
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Holest Engineering Spreadsheet Pric...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:30:50.137
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-09)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Holest Engineering Spreadsheet Price Changer for WooCommerce and WP E-commerce – Light excel-like-price-change-for-woocommerce-and-wp-e-commerce-light allows SQL Injection.This i…

### CVE-2025-48129
**Incorrect Privilege Assignment vulnerability in Holest Engineering Spreadsheet Price Changer for WooCommerce and WP E-commerce – Light ex...**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:30:50.937
- **CWE:** CWE-266
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-09)

> Incorrect Privilege Assignment vulnerability in Holest Engineering Spreadsheet Price Changer for WooCommerce and WP E-commerce – Light excel-like-price-change-for-woocommerce-and-wp-e-commerce-light allows Privilege Escalation.This issue affects Spreadsheet Price Changer for WooC…

### CVE-2025-48140
**Improper Control of Generation of Code ('Code Injection') vulnerability in metalpriceapi MetalpriceAPI metalpriceapi allows Code Injectio...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:30:52.317
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-06-09)

> Improper Control of Generation of Code ('Code Injection') vulnerability in metalpriceapi MetalpriceAPI metalpriceapi allows Code Injection.This issue affects MetalpriceAPI: from n/a through <= 1.1.4.

### CVE-2025-48141
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Alex Zaytseff Multi CryptoCurrency...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:30:52.430
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-09)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Alex Zaytseff Multi CryptoCurrency Payments multi-crypto-currency-payment allows SQL Injection.This issue affects Multi CryptoCurrency Payments: from n/a through <= 2.0.7.

### CVE-2025-48281
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in mystyleplatform MyStyle Custom Prod...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-23T15:31:01.487
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-09)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in mystyleplatform MyStyle Custom Product Designer mystyle-custom-product-designer allows Blind SQL Injection.This issue affects MyStyle Custom Product Designer: from n/a through <=…

### CVE-2025-49136
**nadh listmonk**
- **Signals:** CVSS
- **Asset:** nadh listmonk
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-11T17:23:30.110
- **CWE:** CWE-1336
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-06-09)

> listmonk is a standalone, self-hosted, newsletter and mailing list manager. Starting in version 4.0.0 and prior to version 5.0.2, the `env` and `expandenv` template functions which is enabled by default in Sprig enables capturing of env variables on host. While this may not be a …

### CVE-2025-49652
**Missing Authentication in the registration feature of Lablup's BackendAI allows arbitrary users to create user accounts that can access p...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-09)

> Missing Authentication in the registration feature of Lablup's BackendAI allows arbitrary users to create user accounts that can access private data even when registration is disabled.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-09*
