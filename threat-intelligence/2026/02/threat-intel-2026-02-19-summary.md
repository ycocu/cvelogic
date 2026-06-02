# Daily Threat Intelligence — February 19, 2026

**Digest window (UTC):** 2026-02-19
**Generated:** 2026-06-02T07:34:28Z

## Threat brief

Senkas Kolibri — exploitation likelihood rose sharply (EPSS 33% → 51% · rising (+19%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Senkas Kolibri — exploitation likelihood rose sharply (EPSS 33% → 51% · rising (+19%)).
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

### CVE-2014-4158
**senkas kolibri Buffer Overflow**
- **Signals:** EPSS
- **Asset:** senkas kolibri
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 32.5% (2026-01-27) → 51.2% (2026-02-19), Δ +18.7%**

> Stack-based buffer overflow in Kolibri 2.0 allows remote attackers to execute arbitrary code via a long URI in a GET request.

### CVE-2005-4714
**openvmps openvmps**
- **Signals:** EPSS
- **Asset:** openvmps openvmps
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 80
- **EPSS 6.5% (2025-03-30) → 17.2% (2026-02-19), Δ +10.6%**

> Format string vulnerability in the vmps_log function in OpenVMPS (VLAN Management Policy Server) 1.3 allows remote attackers to execute arbitrary code via unknown vectors.

### CVE-2026-26030
**microsoft semantic_kernel RCE**
- **Signals:** CVSS
- **Asset:** microsoft semantic_kernel
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-03T16:32:10.810
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-02-19)

> Semantic Kernel, Microsoft's semantic kernel Python SDK, has a remote code execution vulnerability in versions prior to 1.39.4, specifically within the `InMemoryVectorStore` filter functionality. The problem has been fixed in version `python-1.39.4`. Users should upgrade this ver…

### CVE-2025-67304
**commscope ruckus_network_director**
- **Signals:** CVSS
- **Asset:** commscope ruckus_network_director
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T11:33:50.483
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-19)

> In Ruckus Network Director (RND) < 4.5.0.54, the OVA appliance contains hardcoded credentials for the ruckus PostgreSQL database user. In the default configuration, the PostgreSQL service is accessible over the network on TCP port 5432. An attacker can use the hardcoded credentia…

### CVE-2025-67305
**commscope ruckus_network_director privilege escalation**
- **Signals:** CVSS
- **Asset:** commscope ruckus_network_director
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T11:34:06.950
- **CWE:** CWE-321
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-19)

> In RUCKUS Network Director (RND) < 4.5.0.56, the OVA appliance contains hardcoded SSH keys for the postgres user. These keys are identical across all deployments, allowing an attacker with network access to authenticate via SSH without a password. Once authenticated, the attacker…

### CVE-2025-71243
**spip saisies RCE**
- **Signals:** CVSS
- **Asset:** spip saisies
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T15:07:48.140
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-19)

> The 'Saisies pour formulaire' (Saisies) plugin for SPIP versions 5.4.0 through 5.11.0 contains a critical Remote Code Execution (RCE) vulnerability. An attacker can exploit this vulnerability to execute arbitrary code on the server. Users should immediately update to version 5.11…

### CVE-2026-2409
**Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Delinea Cloud Suite allows Argument...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-19)

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Delinea Cloud Suite allows Argument Injection.This issue affects Cloud Suite: before 25.2 HF1.

### CVE-2026-24834
**katacontainers kata_containers RCE**
- **Signals:** CVSS
- **Asset:** katacontainers kata_containers
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T20:15:54.893
- **CWE:** CWE-732
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-19)

> Kata Containers is an open source project focusing on a standard implementation of lightweight Virtual Machines (VMs) that perform like containers. In versions prior to 3.27.0, an issue in Kata with Cloud Hypervisor allows a user of the container to modify the file system used by…

### CVE-2026-26016
**pterodactyl panel privilege escalation**
- **Signals:** CVSS
- **Asset:** pterodactyl panel
- **Attack:** privilege escalation
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T19:08:53.683
- **CWE:** CWE-283
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-19)

> Wings is the server control plane for Pterodactyl, a free, open-source game server management panel. Prior to version 1.12.1, a missing authorization check in multiple controllers allows any user with access to a node secret token to fetch information about any server on a Pterod…

### CVE-2026-26339
**hyland alfresco_transform_core RCE**
- **Signals:** CVSS
- **Asset:** hyland alfresco_transform_service
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-02T22:07:07.077
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-19)

> Hyland Alfresco Transformation Service allows unauthenticated attackers to achieve remote code execution through the argument injection vulnerability, which exists in the document processing functionality.

### CVE-2026-27475
**spip spip Code Execution**
- **Signals:** CVSS
- **Asset:** spip spip
- **Attack:** Code Execution
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-24T19:37:54.003
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-19)

> SPIP before 4.4.9 allows Insecure Deserialization in the public area through the table_valeur filter and the DATA iterator, which accept serialized data. An attacker who can place malicious serialized content (a pre-condition requiring prior access or another vulnerability) can t…

### CVE-2026-27476
**RustFly 2.0.0 contains a command injection vulnerability in its remote UI control mechanism that accepts hex-encoded instructions over UD...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-19)

> RustFly 2.0.0 contains a command injection vulnerability in its remote UI control mechanism that accepts hex-encoded instructions over UDP port 5005 without proper sanitization. Attackers can send crafted hex-encoded payloads containing system commands to execute arbitrary operat…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-19*
