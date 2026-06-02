# Daily Threat Intelligence — April 23, 2026

**Digest window (UTC):** 2026-04-23
**Generated:** 2026-06-02T07:34:59Z

## Threat brief

Marimo added to CISA KEV — confirmed in-the-wild exploitation. · Microsoft Win32k — exploitation likelihood rose sharply (EPSS 12% → 52% · rising (+41%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Marimo added to CISA KEV — confirmed in-the-wild exploitation.
- Microsoft Win32k — exploitation likelihood rose sharply (EPSS 12% → 52% · rising (+41%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2026-39987
**Marimo Remote Code Execution Vulnerability**
- **Signals:** KEV
- **Asset:** coreweave marimo
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-23T20:15:29.690
- **CWE:** CWE-306
- **Risk score:** 88
- **KEV:** added 2026-04-23

> marimo is a reactive Python notebook. Prior to 0.23.0, Marimo has a Pre-Auth RCE vulnerability. The terminal WebSocket endpoint /terminal/ws lacks authentication validation, allowing an unauthenticated attacker to obtain a full PTY shell and execute arbitrary system commands. Unl…

### CVE-2015-2360
**Microsoft Win32k Privilege Escalation Vulnerability**
- **Signals:** EPSS
- **Asset:** microsoft windows_7
- **Attack:** Privilege Escalation
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:43:23.577
- **CWE:** CWE-119
- **CWE:** CWE-416
- **Risk score:** 84
- **EPSS 11.6% (2026-04-01) → 52.4% (2026-04-23), Δ +40.8%**

> win32k.sys in the kernel-mode drivers in Microsoft Windows Server 2003 SP2 and R2 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allows local users to gain privileges …

### CVE-2026-33819
**microsoft bing Deserialization**
- **Signals:** CVSS
- **Asset:** microsoft bing
- **Attack:** Deserialization
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-05T14:15:20.343
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-04-23)

> Deserialization of untrusted data in Microsoft Bing allows an unauthorized attacker to execute code over a network.

### CVE-2015-1769
**Microsoft Windows Mount Manager Privilege Escalation Vulnerability**
- **Signals:** EPSS
- **Asset:** microsoft windows_10
- **Attack:** Privilege Escalation
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T16:31:00.867
- **CWE:** CWE-264
- **Risk score:** 81
- **EPSS 31.8% (2026-02-07) → 57.4% (2026-04-23), Δ +25.6%**

> Mount Manager in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT Gold and 8.1, and Windows 10 mishandles symlinks, which allows physically proximate attackers to execute arbitrary …

### CVE-2017-0001
**Microsoft Graphics Device Interface (GDI) Privilege Escalation Vulnerability**
- **Signals:** EPSS
- **Asset:** microsoft windows_10_1507
- **Attack:** Privilege Escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T13:49:47.060
- **Risk score:** 83
- **EPSS 25.4% (2025-10-22) → 47.8% (2026-04-23), Δ +22.4%**

> The Graphics Device Interface (GDI) in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607 allows local users to gain privileges via a crafted application…

### CVE-2026-24303
**Improper access control in Microsoft Partner Center allows an authorized attacker to elevate privileges over a network.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-24T14:41:16.553
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-04-23)

> Improper access control in Microsoft Partner Center allows an authorized attacker to elevate privileges over a network.

### CVE-2026-26210
**kvcache-ai ktransformers Deserialization**
- **Signals:** CVSS
- **Asset:** kvcache-ai ktransformers
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-05T14:43:28.873
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-23)

> KTransformers through 0.5.3 contains an unsafe deserialization vulnerability in the balance_serve backend mode where the scheduler RPC server binds a ZMQ ROUTER socket to all interfaces with no authentication and deserializes incoming messages using pickle.loads() without validat…

### CVE-2026-32210
**microsoft dynamics_365 SSRF**
- **Signals:** CVSS
- **Asset:** microsoft dynamics_365
- **Attack:** SSRF
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-05T14:10:29.540
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-23)

> Server-side request forgery (ssrf) in Microsoft Dynamics 365 (Online) allows an unauthorized attacker to perform spoofing over a network.

### CVE-2026-33102
**microsoft 365_copilot open redirect**
- **Signals:** CVSS
- **Asset:** microsoft 365_copilot
- **Attack:** open redirect
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-29T19:04:21.620
- **CWE:** CWE-601
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-23)

> Url redirection to untrusted site ('open redirect') in M365 Copilot allows an unauthorized attacker to elevate privileges over a network.

### CVE-2026-35431
**Server-side request forgery (ssrf) in Microsoft Entra ID Entitlement Management allows an unauthorized attacker to perform spoofing over...**
- **Signals:** CVSS
- **Attack:** SSRF
- **CVSS max:** 10.0
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-24T14:41:16.553
- **CWE:** CWE-918
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-04-23)

> Server-side request forgery (ssrf) in Microsoft Entra ID Entitlement Management allows an unauthorized attacker to perform spoofing over a network.

### CVE-2026-41265
**flowiseai flowise**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T15:15:09.260
- **CWE:** CWE-77
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-04-23)

> Flowise is a drag & drop user interface to build a customized large language model flow. Prior to 3.1.0, the specific flaw exists within the run method of the Airtable_Agents class. The issue results from the lack of proper sandboxing when evaluating an LLM generated python scrip…

### CVE-2026-41268
**flowiseai flowise RCE**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-24T15:14:39.110
- **CWE:** CWE-20
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-23)

> Flowise is a drag & drop user interface to build a customized large language model flow. Prior to 3.1.0, Flowise is vulnerable to a critical unauthenticated remote command execution (RCE) vulnerability. It can be exploited via a parameter override bypass using the FILE-STORAGE:: …

### CVE-2026-41274
**flowiseai flowise**
- **Signals:** CVSS
- **Asset:** flowiseai flowise
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-04T18:33:02.967
- **CWE:** CWE-943
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-23)

> Flowise is a drag & drop user interface to build a customized large language model flow. Prior to 3.1.0, the GraphCypherQAChain node forwards user-provided input directly into the Cypher query execution pipeline without proper sanitization. An attacker can inject arbitrary Cypher…

### CVE-2026-6942
**radare2-mcp version 1.6.0 and earlier contains an os command injection vulnerability that allows remote attackers to execute arbitrary co...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-29T20:16:31.187
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-23)

> radare2-mcp version 1.6.0 and earlier contains an os command injection vulnerability that allows remote attackers to execute arbitrary commands by bypassing the command filter through shell metacharacters in user-controlled input passed to r2_cmd_str(). Attackers can inject shell…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-23*
