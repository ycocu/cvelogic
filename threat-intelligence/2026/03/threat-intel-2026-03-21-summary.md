# Daily Threat Intelligence — March 21, 2026

**Digest window (UTC):** 2026-03-21
**Generated:** 2026-06-02T07:34:43Z

## Threat brief

Malsmith Serenity Audio Player — exploitation likelihood rose sharply (EPSS 8.0% → 23% · rising (+15%)).

## Executive summary

- Malsmith Serenity Audio Player — exploitation likelihood rose sharply (EPSS 8.0% → 23% · rising (+15%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2009-4097
**malsmith serenity_audio_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** malsmith serenity_audio_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 8.0% (2025-04-21) → 23.2% (2026-03-21), Δ +15.2%**

> Stack-based buffer overflow in the MplayInputFile function in Serenity Audio Player 3.2.3 and earlier allows remote attackers to execute arbitrary code via a long URL in an M3U file.  NOTE: some of these details are obtained from third party information.

### CVE-2020-7387
**sage adxadmin RCE**
- **Signals:** EPSS
- **Asset:** sage adxadmin
- **Attack:** RCE
- **CVSS max:** 5.3
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:37:08.930
- **CWE:** CWE-200
- **Risk score:** 79
- **EPSS 41.3% (2026-03-17) → 56.0% (2026-03-21), Δ +14.7%**

> Sage X3 Installation Pathname Disclosure. A specially crafted packet can elicit a response from the AdxDSrv.exe component that reveals the installation directory of the product. Note that this vulnerability can be combined with CVE-2020-7388 to achieve full RCE. This issue was fi…

### CVE-2019-25568
**microvirt memu privilege escalation**
- **Signals:** CVSS
- **Asset:** microvirt memu
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T16:48:38.030
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-21)

> Memu Play 6.0.7 contains an insecure file permissions vulnerability that allows low-privilege users to escalate privileges by replacing the MemuService.exe executable. Attackers can rename and overwrite MemuService.exe in the installation directory with a malicious executable, wh…

### CVE-2026-24060
**Service information is not encrypted when transmitted as BACnet packets over the wire, and can be sniffed, intercepted, and modified by a...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-03-23T16:16:43.553
- **CWE:** CWE-319
- **CWE:** CWE-319
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-21)

> Service information is not encrypted when transmitted as BACnet packets 
over the wire, and can be sniffed, intercepted, and modified by an 
attacker. Valuable information such as the File Start Position and File 
Data can be sniffed from network traffic using Wireshark's BACnet …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-21*
