# Daily Threat Intelligence — April 09, 2026

**Digest window (UTC):** 2026-04-09
**Generated:** 2026-06-02T07:34:53Z

## Threat brief

Meta React Server Components: public exploit or PoC linked (RCE) · Apache Tomcat — exploitation likelihood rose sharply (EPSS 22% → 48% · rising (+26%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Meta React Server Components: public exploit or PoC linked (RCE)
- Apache Tomcat — exploitation likelihood rose sharply (EPSS 22% → 48% · rising (+26%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 2 |
| EPSS rise | 2 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2025-55182
**Meta React Server Components Remote Code Execution Vulnerability**
- **Signals:** EXP
- **Asset:** facebook react
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T02:00:02.557
- **CWE:** CWE-502
- **Risk score:** 78
- **EXP:** ref published 2026-04-09

> A pre-authentication remote code execution vulnerability exists in React Server Components versions 19.0.0, 19.1.0, 19.1.1, and 19.2.0 including the following packages: react-server-dom-parcel, react-server-dom-turbopack, and react-server-dom-webpack. The vulnerable code unsafely…

### CVE-2025-65027
**romm.app romm XSS**
- **Signals:** EXP
- **Asset:** romm.app romm
- **Attack:** XSS
- **CVSS max:** 7.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-24T20:04:06.050
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2026-04-09

> RomM (ROM Manager) allows users to scan, enrich, browse and play their game collections with a clean and responsive interface. RomM contains multiple unrestricted file upload vulnerabilities that allow authenticated users to upload malicious SVG or HTML files. When these files ar…

### CVE-2001-0590
**apache tomcat**
- **Signals:** EPSS
- **Asset:** apache tomcat
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 78
- **EPSS 21.8% (2025-07-28) → 48.3% (2026-04-09), Δ +26.5%**

> Apache Software Foundation Tomcat Servlet prior to 3.2.2 allows a remote attacker to read the source code to arbitrary 'jsp' files via a malformed URL request which does not end with an HTTP protocol specification (i.e. HTTP/1.0).

### CVE-2011-4162
**hp protecttools_device_access_manager DoS**
- **Signals:** EPSS
- **Asset:** hp protecttools_device_access_manager
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 17.4% (2026-03-24) → 41.8% (2026-04-09), Δ +24.3%**

> The (1) AddUser, (2) AddUserEx, (3) RemoveUser, (4) RemoveUserByGuide, (5) RemoveUserEx, and (6) RemoveUserRegardless methods in HP Protect Tools Device Access Manager (PTDAM) before 6.1.0.1 allow remote attackers to execute arbitrary code or cause a denial of service (heap memor…

### CVE-2025-13926
**An attacker could use data obtained by sniffing the network traffic to forge packets in order to make arbitrary requests to Contemporary...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-13T15:02:27.760
- **CWE:** CWE-807
- **CWE:** CWE-807
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-09)

> An attacker could use data obtained by sniffing the network traffic to 
forge packets in order to make arbitrary requests to Contemporary 
Controls BASC 20T.

### CVE-2026-29145
**apache tomcat**
- **Signals:** CVSS
- **Asset:** apache tomcat
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T13:22:28.357
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-09)

> CLIENT_CERT authentication does not fail as expected for some scenarios when soft fail is disabled vulnerability in Apache Tomcat, Apache Tomcat Native.

This issue affects Apache Tomcat: from 11.0.0-M1 through 11.0.18, from 10.1.0-M7 through 10.1.52, from 9.0.83 through 9.0.115;…

### CVE-2026-33771
**A Weak Password Requirements vulnerability in the password management function of Juniper Networks CTP OS might allow an unauthenticated,...**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-13T15:02:27.760
- **CWE:** CWE-521
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-09)

> A Weak Password Requirements vulnerability in the password management function of Juniper Networks CTP OS might allow an unauthenticated, network-based attacker to exploit weak passwords of local accounts and potentially take full control of the device.

The password management m…

### CVE-2026-33784
**A Use of Default Password vulnerability in the Juniper Networks Support Insights (JSI) Virtual Lightweight Collector (vLWC) allows an una...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-13T15:02:27.760
- **CWE:** CWE-1393
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-09)

> A Use of Default Password vulnerability in the Juniper Networks 

Support Insights (JSI) 

Virtual Lightweight Collector (vLWC) allows an unauthenticated, network-based attacker to take full control of the device.

vLWC software images ship with an initial password for a high pri…

### CVE-2026-34424
**Smart Slider 3 Pro version 3.5.1.35 for WordPress and Joomla contains a multi-stage remote access toolkit injected through a compromised...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T15:00:32.790
- **CWE:** CWE-506
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-09)

> Smart Slider 3 Pro version 3.5.1.35 for WordPress and Joomla contains a multi-stage remote access toolkit injected through a compromised update system that allows unauthenticated attackers to execute arbitrary code and commands. Attackers can trigger pre-authentication remote she…

### CVE-2026-40088
**praison praisonai**
- **Signals:** CVSS
- **Asset:** praison praisonai
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-16T20:40:45.067
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-04-09)

> PraisonAI is a multi-agent teams system. Prior to 4.5.121, the execute_command function and workflow shell execution are exposed to user-controlled input via agent workflows, YAML definitions, and LLM-generated tool calls, allowing attackers to inject arbitrary shell commands thr…

### CVE-2026-40089
**Sonicverse is a Self-hosted Docker Compose stack for live radio streaming.**
- **Signals:** CVSS
- **Attack:** SSRF
- **CVSS max:** 9.9
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-13T15:02:27.760
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-09)

> Sonicverse is a Self-hosted Docker Compose stack for live radio streaming. The Sonicverse Radio Audio Streaming Stack dashboard contains a Server-Side Request Forgery (SSRF) vulnerability in its API client (apps/dashboard/lib/api.ts). Installations created using the provided inst…

### CVE-2026-40111
**praison praisonaiagents**
- **Signals:** CVSS
- **Asset:** praison praisonaiagents
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-17T19:40:24.213
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-09)

> PraisonAIAgents is a multi-agent teams system. Prior to 1.5.128, he memory hooks executor in praisonaiagents passes a user-controlled command string directly to subprocess.run() with shell=True at src/praisonai-agents/praisonaiagents/memory/hooks.py. No sanitization is performed …

### CVE-2026-40154
**praison praisonai**
- **Signals:** CVSS
- **Asset:** praison praisonai
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-15T18:56:45.710
- **CWE:** CWE-829
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-09)

> PraisonAI is a multi-agent teams system. Prior to 4.5.128, PraisonAI treats remotely fetched template files as trusted executable code without integrity verification, origin validation, or user confirmation, enabling supply chain attacks through malicious templates. This vulnerab…

### CVE-2026-5194
**wolfssl wolfssl**
- **Signals:** CVSS
- **Asset:** wolfssl wolfssl
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-16T20:37:11.433
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-09)

> Missing hash/digest size and OID checks allow digests smaller than allowed when verifying ECDSA certificates, or smaller than is appropriate for the relevant key type, to be accepted by signature verification functions. This could lead to reduced security of ECDSA certificate-bas…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-09*
