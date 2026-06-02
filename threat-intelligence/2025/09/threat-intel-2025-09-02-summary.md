# Daily Threat Intelligence — September 02, 2025

**Digest window (UTC):** 2025-09-02
**Generated:** 2026-06-02T07:33:20Z

## Threat brief

Meta Platforms WhatsApp added to CISA KEV — confirmed in-the-wild exploitation. · Joshua Muheim Phpmywebmin — exploitation likelihood rose sharply (EPSS 13% → 25% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Meta Platforms WhatsApp added to CISA KEV — confirmed in-the-wild exploitation.
- Joshua Muheim Phpmywebmin — exploitation likelihood rose sharply (EPSS 13% → 25% · rising (+12%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2025-55177
**Meta Platforms WhatsApp Incorrect Authorization Vulnerability**
- **Signals:** KEV
- **Asset:** whatsapp whatsapp
- **Attack:** privilege escalation
- **CVSS max:** 5.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T14:14:08.077
- **CWE:** CWE-863
- **Risk score:** 88
- **KEV:** added 2025-09-02

> Incomplete authorization of linked device synchronization messages in WhatsApp for iOS prior to v2.25.21.73, WhatsApp Business for iOS v2.25.21.78, and WhatsApp for Mac v2.25.21.78 could have allowed an unrelated user to trigger processing of content from an arbitrary URL on a ta…

### CVE-2006-5125
**joshua_muheim phpmywebmin Directory Traversal**
- **Signals:** EPSS
- **Asset:** joshua_muheim phpmywebmin
- **Attack:** Directory Traversal
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **Risk score:** 78
- **EPSS 12.8% (2025-07-13) → 25.0% (2025-09-02), Δ +12.2%**

> Directory traversal vulnerability in window.php, possibly used by home.php, in Joshua Muheim phpMyWebmin 1.0 allows remote attackers to obtain sensitive information via a directory name in the target parameter, which triggers a directory listing through the opendir function.

### CVE-2025-22429
**google android privilege escalation**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-04T16:39:18.600
- **CWE:** CWE-693
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-02)

> In multiple locations, there is a possible way to execute arbitrary code due to a logic error in the code. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2020-24363
**TP-link TL-WA855RE Missing Authentication for Critical Function Vulnerability**
- **Signals:** KEV
- **Asset:** tp-link tl-wa855re_firmware
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-07T22:02:12.810
- **CWE:** CWE-306
- **CWE:** CWE-306
- **Risk score:** 88
- **KEV:** added 2025-09-02

> TP-Link TL-WA855RE V5 20200415-rel37464 devices allow an unauthenticated attacker (on the same network) to submit a TDDP_RESET POST request for a factory reset and reboot. The attacker can then obtain incorrect access control by setting a new administrative password.

### CVE-2025-22435
**google android Memory Corruption**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-04T16:38:05.697
- **CWE:** CWE-843
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-02)

> In avdt_msg_ind of avdt_msg.cc, there is a possible memory corruption due to type confusion. This could lead to paired device escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2025-26416
**google android Buffer Overflow**
- **Signals:** CVSS
- **Asset:** google android
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-04T16:37:27.790
- **CWE:** CWE-122
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-02)

> In initializeSwizzler of SkBmpStandardCodec.cpp, there is a possible out of bounds write due to a heap buffer overflow. This could lead to remote escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2025-52549
**copeland e3_supervisory_controller_firmware**
- **Signals:** CVSS
- **Asset:** copeland e3_supervisory_controller_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-01T18:23:48.017
- **CWE:** CWE-522
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-09-02)

> E3 Site Supervisor Control (firmware version < 2.31F01) generates the root linux password on each boot. An attacker can generate the root linux password for a vulnerable device based on known or easy to fetch parameters.

### CVE-2025-52551
**E2 Facility Management Systems use a proprietary protocol that allows for unauthenticated file operations on any file in the file system.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-02)

> E2 Facility Management Systems use a proprietary protocol that allows for unauthenticated file operations on any file in the file system.

### CVE-2025-5662
**A deserialization vulnerability exists in the H2O-3 REST API (POST /99/ImportSQLTable) that affects all versions up to 3.46.0.7.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-02)

> A deserialization vulnerability exists in the H2O-3 REST API (POST /99/ImportSQLTable) that affects all versions up to 3.46.0.7. This vulnerability allows remote code execution (RCE) due to improper validation of JDBC connection parameters when using a Key-Value format. The vulne…

### CVE-2025-57140
**ruisitech ruisibi SQL Injection**
- **Signals:** CVSS
- **Asset:** ruisitech ruisibi
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-04T17:46:32.590
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-02)

> rsbi-pom 4.7 is vulnerable to SQL Injection in the /bi/service/model/DatasetService path.

### CVE-2025-6519
**copeland e3_supervisory_controller_firmware**
- **Signals:** CVSS
- **Asset:** copeland e3_supervisory_controller_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-10T14:18:29.190
- **CWE:** CWE-522
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-02)

> E3 Site Supervisor (firmware version < 2.31F01) has a default admin user "ONEDAY" with a daily generated password. An attacker can predictably generate the password for ONEDAY. The oneday user cannot be deleted or modified by any user.

### CVE-2025-9276
**cockroachlabs cockroach-k8s-request-cert Auth Bypass**
- **Signals:** CVSS
- **Asset:** cockroachlabs cockroach-k8s-request-cert
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-30T20:27:48.443
- **CWE:** CWE-258
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-02)

> Cockroach Labs cockroach-k8s-request-cert Empty Root Password Authentication Bypass Vulnerability. This vulnerability could allow remote attackers to bypass authentication on systems that use the affected version of the Cockroach Labs cockroach-k8s-request-cert container image.

…

### CVE-2025-9696
**The SunPower PVS6's BluetoothLE interface is vulnerable due to its use of hardcoded encryption parameters and publicly accessible protoco...**
- **Signals:** CVSS
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-09-02)

> The SunPower PVS6's BluetoothLE interface is vulnerable due to its use of hardcoded encryption parameters and publicly accessible protocol details. An attacker within Bluetooth range could exploit this vulnerability to gain full access to the device's servicing interface. This ac…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-02*
