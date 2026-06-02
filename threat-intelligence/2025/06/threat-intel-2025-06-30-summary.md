# Daily Threat Intelligence — June 30, 2025

**Digest window (UTC):** 2025-06-30
**Generated:** 2026-06-02T07:32:58Z

## Threat brief

Citrix NetScaler ADC And Gateway added to CISA KEV — confirmed in-the-wild exploitation. · Adobe Bridge — exploitation likelihood rose sharply (EPSS 3.1% → 22% · rising (+19%)). · 3 new critical disclosures — review patch status on exposed services.

## Executive summary

- Citrix NetScaler ADC And Gateway added to CISA KEV — confirmed in-the-wild exploitation.
- Adobe Bridge — exploitation likelihood rose sharply (EPSS 3.1% → 22% · rising (+19%)).
- 3 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 3 |
| Patch status change | 0 |
| **Total** | **6** |


## CVEs

### CVE-2025-6543
**Citrix NetScaler ADC and Gateway Buffer Overflow Vulnerability**
- **Signals:** KEV
- **Asset:** citrix netscaler_application_delivery_controller
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-24T13:42:21.210
- **CWE:** CWE-119
- **Risk score:** 88
- **KEV:** added 2025-06-30

> Memory overflow vulnerability leading to unintended control flow and Denial of Service in NetScaler ADC and NetScaler Gateway when configured as Gateway (VPN virtual server, ICA Proxy, CVPN, RDP Proxy) OR AAA virtual server

### CVE-2022-28849
**adobe bridge RCE**
- **Signals:** EPSS
- **Asset:** adobe bridge
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:58:03.343
- **CWE:** CWE-416
- **Risk score:** 83
- **EPSS 3.1% (2025-06-25) → 22.5% (2025-06-30), Δ +19.4%**

> Adobe Bridge version 12.0.1 (and earlier versions) is affected by a Use-After-Free vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user interaction in that a victim must open a malicious file.

### CVE-2025-45931
**dlink dir-816_firmware**
- **Signals:** CVSS
- **Asset:** dlink dir-816_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-08T14:13:39.897
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-30)

> An issue D-Link DIR-816-A2 DIR-816A2_FWv1.10CNB05_R1B011D88210 allows a remote attacker to execute arbitrary code via system() function in the bin/goahead file

### CVE-2015-6125
**microsoft windows_server_2008 Use-After-Free**
- **Signals:** EPSS
- **Asset:** microsoft windows_server_2008
- **Attack:** Use-After-Free
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **Risk score:** 85
- **EPSS 44.5% (2025-03-30) → 59.2% (2025-06-30), Δ +14.7%**

> Use-after-free vulnerability in the DNS server in Microsoft Windows Server 2008 SP2 and R2 SP1 and Server 2012 Gold and R2 allows remote attackers to execute arbitrary code via crafted requests, aka "Windows DNS Use After Free Vulnerability."

### CVE-2025-26074
**Orkes Conductor v3.21.11 allows remote attackers to execute arbitrary OS commands through unrestricted access to Java classes.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-30)

> Orkes Conductor v3.21.11 allows remote attackers to execute arbitrary OS commands through unrestricted access to Java classes.

### CVE-2025-32463
**Sudo Inclusion of Functionality from Untrusted Control Sphere Vulnerability**
- **Signals:** CVSS
- **Asset:** sudo_project sudo
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-05T19:26:48.393
- **CWE:** CWE-829
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-30)

> Sudo before 1.9.17p1 allows local users to obtain root access because /etc/nsswitch.conf from a user-controlled directory is used with the --chroot option.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-30*
