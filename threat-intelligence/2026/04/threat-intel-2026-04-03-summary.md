# Daily Threat Intelligence — April 03, 2026

**Digest window (UTC):** 2026-04-03
**Generated:** 2026-06-02T07:34:50Z

## Threat brief

Microsoft Office — exploitation likelihood rose sharply (EPSS 24% → 35% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Office — exploitation likelihood rose sharply (EPSS 24% → 35% · rising (+12%)).
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

### CVE-2021-42292
**Microsoft Excel Security Feature Bypass**
- **Signals:** EPSS
- **Asset:** microsoft 365_apps
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-30T19:17:40.080
- **Risk score:** 82
- **EPSS 23.9% (2026-03-20) → 35.5% (2026-04-03), Δ +11.6%**

> Microsoft Excel Security Feature Bypass Vulnerability

### CVE-2021-38666
**microsoft windows_10 RCE**
- **Signals:** EPSS
- **Asset:** microsoft windows_10
- **Attack:** RCE
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:17:51.500
- **Risk score:** 82
- **EPSS 21.6% (2026-02-28) → 31.9% (2026-04-03), Δ +10.3%**

> Remote Desktop Client Remote Code Execution Vulnerability

### CVE-2026-34938
**praison praisonaiagents**
- **Signals:** CVSS
- **Asset:** praison praisonaiagents
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T18:07:19.827
- **CWE:** CWE-693
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-04-03)

> PraisonAI is a multi-agent teams system. Prior to version 1.5.90, execute_code() in praisonai-agents runs attacker-controlled Python inside a three-layer sandbox that can be fully bypassed by passing a str subclass with an overridden startswith() method to the _safe_getattr wrapp…

### CVE-2017-20235
**prosoft-technology icx35-hwc_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** prosoft-technology icx35-hwc_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T15:13:25.223
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-03)

> ProSoft Technology ICX35-HWC version 1.3 and prior cellular gateways contain an authentication bypass vulnerability in the web user interface that allows unauthenticated attackers to gain access to administrative functions without valid credentials. Attackers can bypass the authe…

### CVE-2017-20236
**prosoft-technology icx35-hwc_firmware privilege escalation**
- **Signals:** CVSS
- **Asset:** prosoft-technology icx35-hwc_firmware
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T15:12:31.160
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-03)

> ProSoft Technology ICX35-HWC versions 1.3 and prior cellular gateways contain an input validation vulnerability in the web user interface that allows remote attackers to inject and execute system commands by submitting malicious input through unvalidated fields. Attackers can exp…

### CVE-2018-25236
**Hirschmann HiOS and HiSecOS products RSP, RSPE, RSPS, RSPL, MSP, EES, EESX, GRS, OS, RED, EAGLE contain an authentication bypass vulnerab...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-07T13:20:55.200
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-03)

> Hirschmann HiOS and HiSecOS products RSP, RSPE, RSPS, RSPL, MSP, EES, EESX, GRS, OS, RED, EAGLE contain an authentication bypass vulnerability in the HTTP(S) management module that allows unauthenticated remote attackers to gain administrative access by crafting specially formed …

### CVE-2021-4477
**Hirschmann HiLCOS OpenBAT and BAT450 products contain a firewall bypass vulnerability in IPv6 IPsec deployments that allows traffic from...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-04-07T13:20:55.200
- **CWE:** CWE-284
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-04-03)

> Hirschmann HiLCOS OpenBAT and BAT450 products contain a firewall bypass vulnerability in IPv6 IPsec deployments that allows traffic from VPN connections to bypass configured firewall rules. Attackers can exploit this vulnerability by establishing IPv6 IPsec connections (IKEv1 or …

### CVE-2026-34612
**kestra kestra RCE**
- **Signals:** CVSS
- **Asset:** kestra kestra
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-13T17:36:59.393
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-04-03)

> Kestra is an open-source, event-driven orchestration platform. Prior to version 1.3.7, Kestra (default docker-compose deployment) contains a SQL Injection vulnerability that leads to Remote Code Execution (RCE) in the following endpoint "GET /api/v1/main/flows/search". Once a use…

### CVE-2026-34934
**praison praisonai SQL injection**
- **Signals:** CVSS
- **Asset:** praison praisonai
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T18:15:14.820
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-03)

> PraisonAI is a multi-agent teams system. Prior to version 4.5.90, the get_all_user_threads function constructs raw SQL queries using f-strings with unescaped thread IDs fetched from the database. An attacker stores a malicious thread ID via update_thread. When the application loa…

### CVE-2026-34935
**praison praisonai**
- **Signals:** CVSS
- **Asset:** praison praisonai
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-14T18:14:51.930
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-04-03)

> PraisonAI is a multi-agent teams system. From version 4.5.15 to before version 4.5.69, the --mcp CLI argument is passed directly to shlex.split() and forwarded through the call chain to anyio.open_process() with no validation, allowlist check, or sanitization at any hop, allowing…

### CVE-2026-34952
**praison praisonai**
- **Signals:** CVSS
- **Asset:** praison praisonai
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-09T16:55:59.233
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-03)

> PraisonAI is a multi-agent teams system. Prior to version 4.5.97, the PraisonAI Gateway server accepts WebSocket connections at /ws and serves agent topology at /info with no authentication. Any network client can connect, enumerate registered agents, and send arbitrary messages …

### CVE-2026-34953
**praison praisonai**
- **Signals:** CVSS
- **Asset:** praison praisonai
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-09T16:52:58.253
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-03)

> PraisonAI is a multi-agent teams system. Prior to version 4.5.97, OAuthManager.validate_token() returns True for any token not found in its internal store, which is empty by default. Any HTTP request to the MCP server with an arbitrary Bearer token is treated as authenticated, gr…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-03*
