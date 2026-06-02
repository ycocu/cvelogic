# Daily Threat Intelligence — June 25, 2025

**Digest window (UTC):** 2025-06-25
**Generated:** 2026-06-02T07:32:56Z

## Threat brief

AMI MegaRAC SPx added to CISA KEV — confirmed in-the-wild exploitation. · Adobe Illustrator — exploitation likelihood rose sharply (EPSS 5.5% → 22% · rising (+17%)). · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- AMI MegaRAC SPx added to CISA KEV — confirmed in-the-wild exploitation.
- Adobe Illustrator — exploitation likelihood rose sharply (EPSS 5.5% → 22% · rising (+17%)).
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 3 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2024-0769
**D-Link DIR-859 Router Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** dlink dir-859_firmware
- **Attack:** Path Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T19:53:14.770
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2025-06-25

> ** UNSUPPORTED WHEN ASSIGNED ** A vulnerability was found in D-Link DIR-859 1.06B01. It has been rated as critical. Affected by this issue is some unknown functionality of the file /hedwig.cgi of the component HTTP POST Request Handler. The manipulation of the argument service wi…

### CVE-2022-30647
**adobe illustrator RCE**
- **Signals:** EPSS
- **Asset:** adobe illustrator
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:03:05.880
- **CWE:** CWE-416
- **Risk score:** 83
- **EPSS 5.5% (2025-06-22) → 22.5% (2025-06-25), Δ +17.0%**

> Adobe Illustrator versions 26.0.2 (and earlier) and 25.4.5 (and earlier) are affected by a Use-After-Free vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user interaction in that a victim must ope…

### CVE-2025-20282
**cisco identity_services_engine privilege escalation**
- **Signals:** CVSS
- **Asset:** cisco identity_services_engine
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-06-26T20:35:33.577
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-25)

> A vulnerability in an internal API of Cisco ISE and Cisco ISE-PIC could allow an unauthenticated, remote attacker to upload arbitrary files to an affected device and then execute those files on the underlying operating system as root.

This vulnerability is due a lack of file v…

### CVE-2019-6693
**Fortinet FortiOS Use of Hard-Coded Credentials Vulnerability**
- **Signals:** KEV
- **Asset:** fortinet fortios
- **CVSS max:** 6.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T12:53:56.343
- **CWE:** CWE-798
- **CWE:** CWE-798
- **Risk score:** 88
- **KEV:** added 2025-06-25

> Use of a hard-coded cryptographic key to cipher sensitive data in FortiOS configuration backup file may allow an attacker with access to the backup file to decipher the sensitive data, via knowledge of the hard-coded key. The aforementioned sensitive data includes users' password…

### CVE-2021-4457
**digitalzoomstudio zoomsounds**
- **Signals:** CVSS
- **Asset:** digitalzoomstudio zoomsounds
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-07T17:40:37.030
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-06-25)

> The ZoomSounds plugin before 6.05 contains a PHP file allowing unauthenticated users to upload an arbitrary file anywhere on the web server.

### CVE-2022-30648
**adobe illustrator RCE**
- **Signals:** EPSS
- **Asset:** adobe illustrator
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:03:05.990
- **CWE:** CWE-416
- **Risk score:** 83
- **EPSS 5.5% (2025-06-22) → 22.5% (2025-06-25), Δ +17.0%**

> Adobe Illustrator versions 26.0.2 (and earlier) and 25.4.5 (and earlier) are affected by a Use-After-Free vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user interaction in that a victim must ope…

### CVE-2024-51978
**An unauthenticated attacker who knows the target device's serial number, can generate the default administrator password for the device.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1391
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-25)

> An unauthenticated attacker who knows the target device's serial number, can generate the default administrator password for the device. An unauthenticated attacker can first discover the target device's serial number via CVE-2024-51977 over HTTP/HTTPS/IPP, or via a PJL request, …

### CVE-2024-54085
**AMI MegaRAC SPx Authentication Bypass by Spoofing Vulnerability**
- **Signals:** KEV
- **Asset:** ami megarac_sp-x
- **Attack:** Auth Bypass
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:30:12.310
- **CWE:** CWE-290
- **Risk score:** 88
- **KEV:** added 2025-06-25

> AMI’s SPx contains
a vulnerability in the BMC where an Attacker may bypass authentication remotely through the Redfish Host Interface. A successful exploitation
of this vulnerability may lead to a loss of confidentiality, integrity, and/or
availability.

### CVE-2025-20281
**Cisco Identity Services Engine Injection Vulnerability**
- **Signals:** CVSS
- **Asset:** cisco identity_services_engine
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T13:59:08.700
- **CWE:** CWE-74
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-06-25)

> A vulnerability in a specific API of Cisco ISE and Cisco ISE-PIC could allow an unauthenticated, remote attacker to execute arbitrary code on the underlying operating system as root. The attacker does not require any valid credentials to exploit this vulnerability.

This vulner…

### CVE-2025-36038
**ibm websphere_application_server**
- **Signals:** CVSS
- **Asset:** ibm websphere_application_server
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-18T18:11:33.440
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-06-25)

> IBM WebSphere Application Server 8.5 and 9.0 could allow a remote attacker to execute arbitrary code on the system with a specially crafted sequence of serialized objects.

### CVE-2025-49151
**The affected products could allow an unauthenticated attacker to generate forged JSON Web Tokens (JWT) to bypass authentication.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-547
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-25)

> The affected products could allow an unauthenticated attacker to generate forged JSON Web Tokens (JWT) to bypass authentication.

### CVE-2025-49153
**The affected products could allow an unauthenticated attacker to overwrite files and execute arbitrary code.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-25)

> The affected products could allow an unauthenticated attacker to overwrite files and execute arbitrary code.

### CVE-2025-6543
**Citrix NetScaler ADC and Gateway Buffer Overflow Vulnerability**
- **Signals:** CVSS
- **Asset:** citrix netscaler_application_delivery_controller
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:42:21.210
- **CWE:** CWE-119
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-06-25)

> Memory overflow vulnerability leading to unintended control flow and Denial of Service in NetScaler ADC and NetScaler Gateway when configured as Gateway (VPN virtual server, ICA Proxy, CVPN, RDP Proxy) OR AAA virtual server

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-25*
