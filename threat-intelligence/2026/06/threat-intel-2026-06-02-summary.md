# Daily Threat Intelligence — June 02, 2026

**Digest window (UTC):** 2026-06-02
**Generated:** 2026-06-03T08:30:11Z

## Threat brief

Android Framework added to CISA KEV — confirmed in-the-wild exploitation. · Schneider-electric Modicon M340 Firmware — exploitation likelihood rose sharply (EPSS 34% → 63% · rising (+30%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Android Framework added to CISA KEV — confirmed in-the-wild exploitation.
- Schneider-electric Modicon M340 Firmware — exploitation likelihood rose sharply (EPSS 34% → 63% · rising (+30%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **16** |


## CVEs

### CVE-2022-0492
**Linux Kernel Improper Authentication Vulnerability**
- **Signals:** KEV
- **Asset:** netapp h300s_firmware
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-06-02T21:16:24.997
- **CWE:** CWE-287
- **CWE:** CWE-862
- **Risk score:** 88
- **KEV:** added 2026-06-02

> A vulnerability was found in the Linux kernel’s cgroup_release_agent_write in the kernel/cgroup/cgroup-v1.c function. This flaw, under certain circumstances, allows the use of the cgroups v1 release_agent feature to escalate privileges and bypass the namespace isolation unexpecte…

### CVE-2018-7846
**schneider-electric modicon_m340_firmware**
- **Signals:** EPSS
- **Asset:** schneider-electric modicon_m580_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:12:52.140
- **CWE:** CWE-668
- **Risk score:** 86
- **EPSS 33.6% (2026-05-11) → 63.2% (2026-06-02), Δ +29.6%**

> A CWE-501: Trust Boundary Violation vulnerability on connection to the Controller exists in all versions of the Modicon M580, Modicon M340, Modicon Quantum and Modicon Premium which could cause unauthorized access by conducting a brute force attack on Modbus protocol to the contr…

### CVE-2026-7312
**CWE‑522: Insufficiently Protected Credentials in web services in Progress Sitefinity version from 14.0.7700 to 14.4.8152, and 15.0.8200 t...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-06-02T14:37:13.613
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-02)

> CWE‑522: Insufficiently Protected Credentials in web services in Progress Sitefinity version from 14.0.7700 to 14.4.8152, and 15.0.8200 to 15.0.8234, and 15.1.8300 to 15.1.8335, 15.2.8400 to 15.2.8441, 15.3.8500 to 15.3.8531, and 15.4.8600 to 15.4.8630 allows a remote unauthentic…

### CVE-2011-5002
**finaldraft finaldraft Buffer Overflow**
- **Signals:** EPSS
- **Asset:** finaldraft finaldraft
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 9.7% (2026-04-13) → 33.5% (2026-06-02), Δ +23.8%**

> Multiple stack-based buffer overflows in Final Draft 8 before 8.02 allow remote attackers to execute arbitrary code via a .fdx or .fdxt file with long (1) Word, (2) Transition, (3) Location, (4) Extension, (5) SceneIntro, (6) TimeOfDay, and (7) Character elements.

### CVE-2023-2947
**open-emr openemr XSS**
- **Signals:** EPSS
- **Asset:** open-emr openemr
- **Attack:** XSS
- **CVSS max:** 4.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:59:37.553
- **CWE:** CWE-79
- **Risk score:** 78
- **EPSS 35.2% (2026-05-29) → 52.5% (2026-06-02), Δ +17.3%**

> Cross-site Scripting (XSS) - Stored in GitHub repository openemr/openemr prior to 7.0.1.

### CVE-2025-31324
**SAP NetWeaver Unrestricted File Upload Vulnerability**
- **Signals:** EPSS
- **Asset:** sap netweaver
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-31T21:56:14.103
- **CWE:** CWE-434
- **Risk score:** 86
- **EPSS 31.5% (2026-05-25) → 43.7% (2026-06-02), Δ +12.2%**

> SAP NetWeaver Visual Composer Metadata Uploader is not protected with a proper authorization, allowing unauthenticated agent to upload potentially malicious executable binaries that could severely harm the host system. This could significantly affect the confidentiality, integrit…

### CVE-2025-48595
**Android Framework Integer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** google android
- **Attack:** Code Execution
- **CVSS max:** 8.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-02T20:19:29.653
- **CWE:** CWE-190
- **Risk score:** 88
- **KEV:** added 2026-06-02

> In multiple locations, there is a possible way to achieve code execution due to an integer overflow. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2026-0611
**Spacelabs Healthcare Sentinel versions 10.5.x and higher and 11.x.x before 11.6.0 contain an unauthenticated remote code execution vulner...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-02T20:16:31.633
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-02)

> Spacelabs Healthcare Sentinel versions 10.5.x and higher and 11.x.x before 11.6.0 contain an unauthenticated remote code execution vulnerability through a deprecated .NET Remoting HTTP channel exposed on port 8989 that allows attackers to perform arbitrary file read and write ope…

### CVE-2026-10629
**SIP signaling stack in Verizon IMS (unspecified version) implements SIP signaling without IPsec integrity protection (missing Security-Cl...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-06-02T20:16:33.080
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-02)

> SIP signaling stack in Verizon IMS (unspecified version) implements SIP signaling without IPsec integrity protection (missing Security-Client/Security-Server headers and ESP traffic), which allows an on-path attacker to compromise confidentiality, integrity, and authenticity of V…

### CVE-2026-32625
**LibreChat is an enhanced ChatGPT clone that supports multiple AI providers.**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Received
- **NVD modified:** 2026-06-02T23:16:35.947
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-02)

> LibreChat is an enhanced ChatGPT clone that supports multiple AI providers. In versions up to and including 0.8.3, the Model Context Protocol (MCP) server integration resolves ${VAR} placeholders against the server's process.env during Zod schema validation of user-supplied MCP s…

### CVE-2026-42074
**OpenClaude is an open-source coding-agent command line interface for cloud and local model providers.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-06-02T20:16:36.413
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-02)

> OpenClaude is an open-source coding-agent command line interface for cloud and local model providers. Prior to version 0.5.1, the dangerouslyDisableSandbox parameter is exposed as part of the BashTool input schema, meaning the LLM (an untrusted principal per the project's own thr…

### CVE-2026-42849
**authentik is an open-source identity provider.**
- **Signals:** CVSS
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD modified:** 2026-06-02T21:16:27.670
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-02)

> authentik is an open-source identity provider. Prior to versions 2025.12.5 and 2026.2.3, due to the implementation of stages in the SFE (Simple Flow Executor) in order to make the interface more compatible with legacy browsers, it was possible to use an XSS exploit in the Autosub…

### CVE-2026-47117
**OpenMed before 1.5.2 contains a remote code execution vulnerability in the PII privacy-filter model loading path.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-02T17:18:19.573
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-02)

> OpenMed before 1.5.2 contains a remote code execution vulnerability in the PII privacy-filter model loading path. The privacy-filter dispatcher used broad substring matching on the user-supplied model_name parameter, allowing a value such as attacker/foo-privacy-filter-bar to rou…

### CVE-2026-49448
**authentik is an open-source identity provider.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-02T21:16:28.490
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-02)

> authentik is an open-source identity provider. Prior to versions 2025.12.6, 2026.2.4, and 2026.5.1, the Source stage can be bypassed by sending an empty POST. This issue has been patched in versions 2025.12.6, 2026.2.4, and 2026.5.1.

### CVE-2026-5076
**The ARMember Premium plugin for WordPress is vulnerable to an insecure password reset mechanism in all versions up to, and including, 7.3.1.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-06-02T20:56:20.057
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-02)

> The ARMember Premium plugin for WordPress is vulnerable to an insecure password reset mechanism in all versions up to, and including, 7.3.1. The plugin stores a plaintext copy of the password reset key in the `arm_reset_password_key` user meta field when a user requests a passwor…

### CVE-2026-7198
**CWE-284: Improper Access Control in web services in Progress Sitefinity 15.4.8623 before 15.4.8630 allows a remote unauthenticated attack...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-06-02T14:37:13.613
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-02)

> CWE-284: Improper Access Control in web services in Progress Sitefinity 15.4.8623 before 15.4.8630 allows a remote unauthenticated attacker to access content that should be restricted, resulting in full compromise of confidentiality, integrity, and availability of affected instal…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-02*
