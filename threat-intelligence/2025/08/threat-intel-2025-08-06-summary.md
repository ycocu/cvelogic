# Daily Threat Intelligence — August 06, 2025

**Digest window (UTC):** 2025-08-06
**Generated:** 2026-06-02T07:33:11Z

## Threat brief

9 new critical disclosures — review patch status on exposed services.

## Executive summary

- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **9** |


## CVEs

### CVE-2025-23310
**nvidia triton_inference_server RCE**
- **Signals:** CVSS
- **Asset:** nvidia triton_inference_server
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-12T16:34:02.277
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-06)

> NVIDIA Triton Inference Server for Windows and Linux contains a vulnerability where an attacker could cause stack buffer overflow by specially crafted inputs. A successful exploit of this vulnerability might lead to remote code execution, denial of service, information disclosure…

### CVE-2025-23311
**nvidia triton_inference_server RCE**
- **Signals:** CVSS
- **Asset:** nvidia triton_inference_server
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-12T16:34:15.230
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-06)

> NVIDIA Triton Inference Server contains a vulnerability where an attacker could cause a stack overflow through specially crafted HTTP requests. A successful exploit of this vulnerability might lead to remote code execution, denial of service, information disclosure, or data tampe…

### CVE-2025-6994
**The Reveal Listing plugin by smartdatasoft for WordPress is vulnerable to privilege escalation in versions up to, and including, 3.3.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-06)

> The Reveal Listing plugin by smartdatasoft for WordPress is vulnerable to privilege escalation in versions up to, and including, 3.3. This is due to the plugin allowing users who are registering new accounts to set their own role or by supplying 'listing_user_role' field. This ma…

### CVE-2025-22470
**CL4/6NX Plus and CL4/6NX-J Plus (Japan model) with the firmware versions prior to 1.15.5-r1 allow crafted dangerous files to be uploaded.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-06)

> CL4/6NX Plus and CL4/6NX-J Plus (Japan model) with the firmware versions prior to 1.15.5-r1 allow crafted dangerous files to be uploaded. An arbitrary Lua script may be executed on the system with the root privilege.

### CVE-2025-23317
**nvidia triton_inference_server RCE**
- **Signals:** CVSS
- **Asset:** nvidia triton_inference_server
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-12T16:34:24.833
- **CWE:** CWE-122
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-06)

> NVIDIA Triton Inference Server contains a vulnerability in the HTTP server, where an attacker could start a reverse shell by sending a specially crafted HTTP request. A successful exploit of this vulnerability might lead to remote code execution, denial of service, data tampering…

### CVE-2025-30127
**An issue was discovered on Marbella KR8s Dashcam FF 2.0.8 devices.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-08-06)

> An issue was discovered on Marbella KR8s Dashcam FF 2.0.8 devices. Once access is gained either by default, common, or cracked passwords, the video recordings (containing sensitive routes, conversations, and footage) are open for downloading by creating a socket to command port 7…

### CVE-2025-54594
**react-native-bottom-tabs is a library of Native Bottom Tabs for React Native.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-08-06)

> react-native-bottom-tabs is a library of Native Bottom Tabs for React Native. In versions 0.9.2 and below, the github/workflows/release-canary.yml GitHub Actions repository workflow improperly used the pull_request_target event trigger, which allowed for untrusted code from a for…

### CVE-2025-54883
**Vision UI is a collection of enterprise-grade, dependency-free modules for modern web projects.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-338
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-06)

> Vision UI is a collection of enterprise-grade, dependency-free modules for modern web projects. In versions 1.4.0 and below, the getSecureRandomInt function in security-kit versions prior to 3.5.0 (packaged in Vision-ui <= 1.4.0) contains a critical cryptographic weakness. Due to…

### CVE-2025-7768
**Tigo Energy's Cloud Connect Advanced (CCA) device contains hard-coded credentials that allow unauthorized users to gain administrative ac...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-08-06)

> Tigo Energy's Cloud Connect Advanced (CCA) device contains hard-coded credentials that allow unauthorized users to gain administrative access. This vulnerability enables attackers to escalate privileges and take full control of the device, potentially modifying system settings, d…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-08-06*
