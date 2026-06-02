# Daily Threat Intelligence — October 01, 2025

**Digest window (UTC):** 2025-10-01
**Generated:** 2026-06-02T07:33:31Z

## Threat brief

5 new critical disclosures — review patch status on exposed services.

## Executive summary

- 5 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 5 |
| Patch status change | 0 |
| **Total** | **5** |


## CVEs

### CVE-2025-61044
**totolink x18_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** totolink x18_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-10-16T20:15:34.650
- **CWE:** CWE-77
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-01)

> TOTOLINK X18 V9.1.0cu.2053_B20230309 was discovered to contain a command injection vulnerability via the agentName parameter in the setEasyMeshAgentCfg function.

### CVE-2025-61045
**totolink x18_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** totolink x18_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-10-21T20:20:50.870
- **CWE:** CWE-77
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-01)

> TOTOLINK X18 V9.1.0cu.2053_B20230309 was discovered to contain a command injection vulnerability via the mac parameter in the setEasyMeshAgentCfg function.

### CVE-2025-61622
**apache fory RCE**
- **Signals:** CVSS
- **Asset:** apache fory
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-03T21:52:30.080
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-10-01)

> Deserialization of untrusted data in python in pyfory versions 0.12.0 through 0.12.2, or the legacy pyfury versions from 0.1.0 through 0.10.3: allows arbitrary code execution. An application is vulnerable if it reads pyfory serialized data from untrusted sources. An attacker can …

### CVE-2020-36852
**The Custom Searchable Data Entry System plugin for WordPress is vulnerable to unauthenticated database wiping in versions up to, and incl...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-10-01)

> The Custom Searchable Data Entry System plugin for WordPress is vulnerable to unauthenticated database wiping in versions up to, and including 1.7.1, due to a missing capability check and lack of sufficient validation on the ghazale_sds_delete_entries_table_row() function. This m…

### CVE-2025-59951
**termix termix**
- **Signals:** CVSS
- **Asset:** termix termix
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-20T18:37:31.173
- **CWE:** CWE-284
- **CWE:** CWE-345
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2025-10-01)

> Termix is a web-based server management platform with SSH terminal, tunneling, and file editing capabilities. The official Docker image  for Termix versions 1.5.0 and below, due to being configured with an Nginx reverse proxy, causes the backend to retrieve the proxy's IP instead…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-10-01*
