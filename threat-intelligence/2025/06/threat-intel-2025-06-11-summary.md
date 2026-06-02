# Daily Threat Intelligence — June 11, 2025

**Digest window (UTC):** 2025-06-11
**Generated:** 2026-06-02T07:32:52Z

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

### CVE-2025-49709
**mozilla firefox Memory Corruption**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:16:58.937
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-11)

> Certain canvas operations could have lead to memory corruption. This vulnerability was fixed in Firefox 139.0.4.

### CVE-2025-49710
**mozilla firefox**
- **Signals:** CVSS
- **Asset:** mozilla firefox
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-13T15:16:59.113
- **CWE:** CWE-190
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-11)

> An integer overflow was present in `OrderedHashTable` used by the JavaScript engine. This vulnerability was fixed in Firefox 139.0.4.

### CVE-2025-41663
**For u-link Management API an unauthenticated remote attacker in a man-in-the-middle position can inject arbitrary commands in responses r...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-11)

> For u-link Management API an unauthenticated remote attacker in a man-in-the-middle position can inject arbitrary commands in responses returned by WWH servers, which are then executed with elevated privileges. To get into such a position, clients would need to use insecure proxy…

### CVE-2024-1243
**wazuh wazuh RCE**
- **Signals:** CVSS
- **Asset:** wazuh wazuh
- **Attack:** RCE
- **CVSS max:** 9.5
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-01T15:01:48.570
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-06-11)

> Improper input validation in the Wazuh agent for Windows prior to version 4.8.0 allows an attacker with control over the Wazuh server or agent key to configure the agent to connect to a malicious UNC path. This results in the leakage of the machine account NetNTLMv2 hash, which c…

### CVE-2024-1244
**Improper input validation in the OSSEC HIDS agent for Windows prior to version 3.8.0 allows an attacker in with control over the OSSEC se...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2025-06-11)

> Improper input validation in the OSSEC HIDS agent for Windows prior to version 3.8.0 allows an attacker in with control over the OSSEC server or in possession of the agent's key to configure the agent to connect to a malicious UNC path. This results in the leakage of the machine …

### CVE-2025-30085
**Remote code execution vulnerability in RSForm!pro component 3.0.0 - 3.3.14 for Joomla was discovered.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-06-11)

> Remote code execution vulnerability in RSForm!pro component 3.0.0 - 3.3.14 for Joomla was discovered. The issue occurs within the submission export feature and requires administrative access to the export feature.

### CVE-2025-32711
**microsoft 365_copilot Command Injection**
- **Signals:** CVSS
- **Asset:** microsoft 365_copilot
- **Attack:** Command Injection
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-02-20T17:25:10.630
- **CWE:** CWE-74
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-06-11)

> Ai command injection in M365 Copilot allows an unauthorized attacker to disclose information over a network.

### CVE-2025-40912
**CryptX for Perl before version 0.065 contains a dependency that may be susceptible to malformed unicode.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-11)

> CryptX for Perl before version 0.065 contains a dependency that may be susceptible to malformed unicode.

CryptX embeds the tomcrypt library. The versions of that library in CryptX before 0.065 may be susceptible to CVE-2019-17362.

### CVE-2025-40914
**Perl CryptX before version 0.087 contains a dependency that may be susceptible to an integer overflow.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-06-11)

> Perl CryptX before version 0.087 contains a dependency that may be susceptible to an integer overflow.

CryptX embeds a version of the libtommath library that is susceptible to an integer overflow associated with CVE-2023-36328.

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-06-11*
