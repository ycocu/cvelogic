# Daily Threat Intelligence — March 17, 2026

**Digest window (UTC):** 2026-03-17
**Generated:** 2026-06-02T07:34:40Z

## Threat brief

Solarwinds Patch Manager — exploitation likelihood rose sharply (EPSS 52% → 73% · rising (+22%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Solarwinds Patch Manager — exploitation likelihood rose sharply (EPSS 52% → 73% · rising (+22%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2021-35216
**solarwinds patch_manager RCE**
- **Signals:** EPSS
- **Asset:** solarwinds patch_manager
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:12:04.760
- **CWE:** CWE-502
- **CWE:** CWE-502
- **Risk score:** 84
- **EPSS 51.7% (2025-11-21) → 73.3% (2026-03-17), Δ +21.6%**

> Insecure Deserialization of untrusted data remote code execution vulnerability was discovered in Patch Manager Orion Platform Integration module. An Authenticated Attacker with network access via HTTP can compromise this vulnerability can result in Remote Code Execution.

### CVE-2020-1219
**microsoft chakracore RCE**
- **Signals:** EPSS
- **Asset:** microsoft internet_explorer
- **Attack:** RCE
- **CVSS max:** 7.6
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:10:00.473
- **CWE:** CWE-843
- **Risk score:** 82
- **EPSS 22.0% (2025-12-28) → 36.6% (2026-03-17), Δ +14.6%**

> A remote code execution vulnerability exists in the way that Microsoft browsers access objects in memory, aka 'Microsoft Browser Memory Corruption Vulnerability'.

### CVE-2026-21994
**oracle okit**
- **Signals:** CVSS
- **Asset:** oracle okit
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-02T12:27:23.640
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-17)

> Vulnerability in the Oracle Edge Cloud Infrastructure Designer and Visualisation Toolkit product of Oracle Open Source Projects (component: Desktop).   The supported version that is affected is 0.3.0. Easily exploitable vulnerability allows unauthenticated attacker with network a…

### CVE-2026-25534
**### Impact Spinnaker updated URL Validation logic on user input to provide sanitation on user inputted URLs for clouddriver.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-16T14:46:24.290
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-17)

> ### Impact
Spinnaker updated URL Validation logic on user input to provide sanitation on user inputted URLs for clouddriver.  However, they missed that Java URL objects do not correctly handle underscores on parsing.  This led to a bypass of the previous CVE (CVE-2025-61916) thro…

### CVE-2026-25769
**wazuh wazuh RCE**
- **Signals:** CVSS
- **Asset:** wazuh wazuh
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-19T17:18:30.560
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-17)

> Wazuh is a free and open source platform used for threat prevention, detection, and response. Versions 4.0.0 through 4.14.2 have a Remote Code Execution (RCE) vulnerability due to Deserialization of Untrusted Data). All Wazuh deployments using cluster mode (master/worker architec…

### CVE-2026-25770
**wazuh wazuh Privilege Escalation**
- **Signals:** CVSS
- **Asset:** wazuh wazuh
- **Attack:** Privilege Escalation
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-19T17:11:26.750
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-17)

> Wazuh is a free and open source platform used for threat prevention, detection, and response. Starting in version 3.9.0 and prior to version 4.14.3, a privilege escalation vulnerability exists in the Wazuh Manager's cluster synchronization protocol. The `wazuh-clusterd` service a…

### CVE-2026-32292
**gl-inet comet_gl-rm1_firmware**
- **Signals:** CVSS
- **Asset:** gl-inet comet_gl-rm1_firmware
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T12:39:01.693
- **CWE:** CWE-307
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-17)

> The GL-iNet Comet (GL-RM1) KVM web interface does not limit login requests, enabling brute-force attempts to guess credentials.

### CVE-2026-32295
**jetkvm kvm**
- **Signals:** CVSS
- **Asset:** jetkvm kvm
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-10T01:28:56.830
- **CWE:** CWE-307
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-17)

> JetKVM before 0.5.4 does not rate limit login requests, enabling brute-force attempts to guess credentials.

### CVE-2026-32297
**angeet es3_kvm_firmware**
- **Signals:** CVSS
- **Asset:** angeet es3_kvm_firmware
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-27T16:58:00.927
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-17)

> The Angeet ES3 KVM allows a remote, unauthenticated attacker to write arbitrary files, including configuration files or system binaries. Modified configuration files or system binaries could allow an attacker to take complete control of a vulnerable system.

### CVE-2026-32841
**edimax gs-5008pl_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** edimax gs-5008pl_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.2
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T14:16:32.863
- **CWE:** CWE-1108
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-03-17)

> Edimax GS-5008PL firmware versions 1.00.54 and prior contain an authentication bypass vulnerability that allows unauthenticated attackers to access the management interface. Attackers can exploit the global authentication flag mechanism to gain administrative access without crede…

### CVE-2026-3564
**A condition in ScreenConnect may allow an actor with access to server-level cryptographic material used for authentication to obtain unau...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-18T14:52:44.227
- **CWE:** CWE-347
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-03-17)

> A condition in ScreenConnect may allow an actor with access to server-level cryptographic material used for authentication to obtain unauthorized access, including elevated privileges, in certain scenarios.

### CVE-2026-4312
**GCB/FCB Audit Software developed by DrangSoft has a Missing Authentication vulnerability, allowing unauthenticated remote attackers to di...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-17T14:20:01.670
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-17)

> GCB/FCB Audit Software developed by DrangSoft has a Missing Authentication vulnerability, allowing unauthenticated remote attackers to directly access certain APIs to create a new administrative account.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-17*
