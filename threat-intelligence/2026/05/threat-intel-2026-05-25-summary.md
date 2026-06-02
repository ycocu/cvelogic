# Daily Threat Intelligence — May 25, 2026

**Digest window (UTC):** 2026-05-25
**Generated:** 2026-06-02T07:04:07Z

## Threat brief

Eparks Fiberlink 210 Firmware — exploitation likelihood rose sharply (EPSS 48% → 70% · rising (+22%)). · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- Eparks Fiberlink 210 Firmware — exploitation likelihood rose sharply (EPSS 48% → 70% · rising (+22%)).
- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 5 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **9** |


## CVEs

### CVE-2023-33617
**eparks fiberlink_210_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** eparks fiberlink_210_firmware
- **Attack:** Command Injection
- **CVSS max:** 7.2
- **NVD status:** Modified
- **NVD modified:** 2025-01-31T18:15:33.513
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 82
- **EPSS 48.0% (2026-05-24) → 70.1% (2026-05-25), Δ +22.1%**

> An OS Command Injection vulnerability in Parks Fiberlink 210 firmware version V2.1.14_X000 was found via the /boaform/admin/formPing target_addr parameter.

### CVE-2021-31251
**chiyu-tech bf-430_firmware Auth Bypass**
- **Signals:** EPSS
- **Asset:** chiyu-tech bf-430_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:05:22.107
- **CWE:** CWE-287
- **Risk score:** 86
- **EPSS 10.8% (2026-04-25) → 27.5% (2026-05-25), Δ +16.7%**

> An authentication bypass in telnet server in BF-430 and BF431 232/422 TCP/IP Converter, BF-450M and SEMAC from CHIYU Technology Inc allows obtaining a privileged connection with the target device by supplying a specially malformed request and an attacker may force the remote teln…

### CVE-2026-42773
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in eMagicOne eMagicOne Store Manager a...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T19:31:20.323
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-25)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in eMagicOne eMagicOne Store Manager allows Blind SQL Injection.

This issue affects eMagicOne Store Manager: from n/a through 1.3.2.

### CVE-2019-13577
**computerlab maple_computer_wbt_snmp_administrator Buffer Overflow**
- **Signals:** EPSS
- **Asset:** computerlab maple_computer_wbt_snmp_administrator
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:25:13.890
- **CWE:** CWE-787
- **Risk score:** 84
- **EPSS 35.4% (2026-05-24) → 46.5% (2026-05-25), Δ +11.0%**

> SnmpAdm.exe in MAPLE WBT SNMP Administrator v2.0.195.15 has an Unauthenticated Remote Buffer Overflow via a long string to the CE Remote feature listening on Port 987.

### CVE-2019-25024
**alleghenycreative openrepeater Command Injection**
- **Signals:** EPSS
- **Asset:** alleghenycreative openrepeater
- **Attack:** Command Injection
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2025-04-16T15:15:45.070
- **CWE:** CWE-78
- **Risk score:** 85
- **EPSS 50.5% (2026-04-18) → 62.6% (2026-05-25), Δ +12.1%**

> OpenRepeater (ORP) before 2.2 allows unauthenticated command injection via shell metacharacters in the functions/ajax_system.php post_service parameter.

### CVE-2025-42999
**SAP NetWeaver Deserialization Vulnerability**
- **Signals:** EPSS
- **Asset:** sap netweaver
- **Attack:** Deserialization
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T21:58:56.343
- **CWE:** CWE-502
- **Risk score:** 85
- **EPSS 52.1% (2026-05-22) → 66.4% (2026-05-25), Δ +14.3%**

> SAP NetWeaver Visual Composer Metadata Uploader is vulnerable when a privileged user can upload untrusted or malicious content which, when deserialized, could potentially lead to a compromise of confidentiality, integrity, and availability of the host system.

### CVE-2026-2651
**privilege escalation**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-26T20:06:20.310
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-05-25)

> A vulnerability in MLflow versions <=3.10.1.dev0 allows unauthorized access to multipart upload (MPU) endpoints when the `--serve-artifacts` mode is enabled. The authorization logic does not enforce resource-level permission checks for `/mlflow-artifacts/mpu/*` endpoints, enablin…

### CVE-2026-42774
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Crocoblock JetEngine allows SQL Inj...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T19:31:20.323
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-25)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Crocoblock JetEngine allows SQL Injection.

This issue affects JetEngine: from n/a through 3.8.8.1.

### CVE-2026-9058
**Szafir SDK returns a success status code from the cryptographic digital signature verification process (i.e.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T19:59:22.323
- **CWE:** CWE-393
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-25)

> Szafir SDK returns a success status code from the cryptographic digital signature verification process (i.e. /VerifyingTaskItem/Signature/VerificationResult/Result/@code == 0, "Positively verified") even when the trust status of the signer's certificate could not be established (…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-25*
