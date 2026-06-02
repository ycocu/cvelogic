# Daily Threat Intelligence — September 12, 2025

**Digest window (UTC):** 2025-09-12
**Generated:** 2026-06-02T07:33:24Z

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

### CVE-2025-10264
**Certain models of NVR developed by Digiever has an Exposure of Sensitive Information vulnerability, allowing unauthenticated remoter atta...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-497
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-09-12)

> Certain models of NVR developed by Digiever has an Exposure of Sensitive Information vulnerability, allowing unauthenticated remoter attackers to access the system configuration file and obtain plaintext credentials of the NVR and its connected cameras.

### CVE-2024-45434
**opensynergy blue_sdk RCE**
- **Signals:** CVSS
- **Asset:** opensynergy blue_sdk
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-02T20:00:43.860
- **CWE:** CWE-416
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-12)

> OpenSynergy BlueSDK (aka Blue SDK) through 6.x has a Use-After-Free. The specific flaw exists within the BlueSDK Bluetooth stack. The issue results from the lack of validating the existence of an object before performing operations on the object (aka use after free). An attacker …

### CVE-2025-55835
**sueamcms_project sueamcms**
- **Signals:** CVSS
- **Asset:** sueamcms_project sueamcms
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-16T15:47:50.040
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-12)

> File Upload vulnerability in SueamCMS v.0.1.2 allows a remote attacker to execute arbitrary code via the lack of filtering.

### CVE-2025-10266
**NUP Pro developed by NewType Infortech has a SQL Injection vulnerability, allowing unauthenticated remote attackers to inject arbitrary S...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-12)

> NUP Pro developed by NewType Infortech has a SQL Injection vulnerability, allowing unauthenticated remote attackers to inject arbitrary SQL commands to read, modify, and delete database contents.

### CVE-2025-10364
**The Evertz SDVN 3080ipx-10G is a High Bandwidth Ethernet Switching Fabric for Video Application.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-12)

> The Evertz SDVN 3080ipx-10G is a High Bandwidth Ethernet Switching Fabric for Video Application. This device exposes a web management interface on port 80. This web management interface can be used by administrators to control product
features, setup network switching, and regist…

### CVE-2025-10365
**The Evertz SDVN 3080ipx-10G is a High Bandwidth Ethernet Switching Fabric for Video Application.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-12)

> The Evertz SDVN 3080ipx-10G is a High Bandwidth Ethernet Switching Fabric for Video Application. This device exposes a web management interface on port 80. This web management interface can be used by administrators to control product
features, setup network switching, and regist…

### CVE-2025-45583
**audi universal_traffic_recorder_firmware**
- **Signals:** CVSS
- **Asset:** audi universal_traffic_recorder_firmware
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-16T15:39:07.447
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-12)

> Incorrect access control in the FTP protocol of Audi UTR 2.0 Universal Traffic Recorder 2.0 allows attackers to authenticate into the service using any combination of username and password.

### CVE-2025-58434
**flowiseai flowise**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-20T02:54:59.667
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-12)

> Flowise is a drag & drop user interface to build a customized large language model flow. In version 3.0.5 and earlier, the `forgot-password` endpoint in Flowise returns sensitive information including a valid password reset `tempToken` without authentication or verification. This…

### CVE-2025-8699
**Some "Stored Value" Unattended Payment Solutions of KioSoft use vulnerable NFC cards.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-922
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-12)

> Some "Stored Value" Unattended Payment Solutions of KioSoft use vulnerable NFC cards. Attackers could potentially use this vulnerability to change the balance on the cards and generate money. The account balance is stored on an insecure MiFare Classic NFC card and can be read and…

### CVE-2025-9556
**Langchaingo supports the use of jinja2 syntax when parsing prompts, which is in turn parsed using the gonja library v1.5.3.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-12)

> Langchaingo supports the use of jinja2 syntax when parsing prompts, which is in turn parsed using the gonja library v1.5.3.
Gonja supports include and extends syntax to read files, which leads to a server side template injection vulnerability within langchaingo, allowing an atta…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-12*
