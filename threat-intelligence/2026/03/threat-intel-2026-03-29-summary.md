# Daily Threat Intelligence — March 29, 2026

**Digest window (UTC):** 2026-03-29
**Generated:** 2026-06-02T07:34:47Z

## Threat brief

Sas\/intrnet — exploitation likelihood rose sharply (EPSS 55% → 74% · rising (+19%)). · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- Sas\/intrnet — exploitation likelihood rose sharply (EPSS 55% → 74% · rising (+19%)).
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2021-41569
**sas sas\/intrnet**
- **Signals:** EPSS
- **Asset:** sas sas\/intrnet
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:26:26.863
- **CWE:** CWE-829
- **Risk score:** 82
- **EPSS 54.8% (2025-11-21) → 73.8% (2026-03-29), Δ +19.0%**

> SAS/Intrnet 9.4 build 1520 and earlier allows Local File Inclusion. The samples library (included by default) in the appstart.sas file, allows end-users of the application to access the sample.webcsf1.sas program, which contains user-controlled macro variables that are passed to …

### CVE-2021-41460
**shopex ecshop SQL Injection**
- **Signals:** EPSS
- **Asset:** shopex ecshop
- **Attack:** SQL Injection
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:26:17.100
- **CWE:** CWE-89
- **Risk score:** 82
- **EPSS 28.3% (2025-11-21) → 44.7% (2026-03-29), Δ +16.4%**

> ECShop 4.1.0 has SQL injection vulnerability, which can be exploited by attackers to obtain sensitive information.

### CVE-2026-0558
**lollms lollms DoS**
- **Signals:** CVSS
- **Asset:** lollms lollms
- **Attack:** DoS
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T19:45:54.220
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-29)

> A vulnerability in parisneo/lollms, up to and including version 2.2.0, allows unauthenticated users to upload and process files through the `/api/files/extract-text` endpoint. This endpoint does not enforce authentication, unlike other file-related endpoints, and lacks the `Depen…

### CVE-2020-25206
**mimosa b5_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** mimosa b5_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:17:38.813
- **CWE:** CWE-78
- **Risk score:** 79
- **EPSS 19.3% (2026-02-25) → 29.6% (2026-03-29), Δ +10.2%**

> The web console for Mimosa B5, B5c, and C5x firmware through 2.8.0.2 allows authenticated command injection in the Throughput, WANStats, PhyStats, and QosStats API classes. An attacker with access to a web console account may execute operating system commands on affected devices …

### CVE-2022-24082
**pega infinity**
- **Signals:** EPSS
- **Asset:** pega infinity
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:49:46.687
- **CWE:** CWE-502
- **CWE:** CWE-502
- **Risk score:** 86
- **EPSS 31.5% (2025-11-21) → 45.6% (2026-03-29), Δ +14.1%**

> If an on-premise installation of the Pega Platform is configured with the port for the JMX interface exposed to the Internet and port filtering is not properly configured, then it may be possible to upload serialized payloads to attack the underlying system. This does not affect …

### CVE-2026-32915
**openclaw openclaw privilege escalation**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T18:10:23.680
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-29)

> OpenClaw before 2026.3.11 contains a sandbox boundary bypass vulnerability allowing leaf subagents to access the subagents control surface and resolve against parent requester scope instead of their own session tree. A low-privilege sandboxed leaf worker can steer or kill sibling…

### CVE-2026-32918
**openclaw openclaw**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T18:09:19.123
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-03-29)

> OpenClaw before 2026.3.11 contains a session sandbox escape vulnerability in the session_status tool that allows sandboxed subagents to access parent or sibling session state. Attackers can supply arbitrary sessionKey values to read or modify session data outside their sandbox sc…

### CVE-2026-32922
**openclaw openclaw RCE**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T18:02:26.860
- **CWE:** CWE-266
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-29)

> OpenClaw before 2026.3.11 contains a privilege escalation vulnerability in device.token.rotate that allows callers with operator.pairing scope to mint tokens with broader scopes by failing to constrain newly minted scopes to the caller's current scope set. Attackers can obtain op…

### CVE-2026-32978
**openclaw openclaw**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T17:15:43.657
- **CWE:** CWE-863
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-03-29)

> OpenClaw before 2026.3.11 contains an approval integrity vulnerability where system.run approvals fail to bind mutable file operands for certain script runners like tsx and jiti. Attackers can obtain approval for benign script commands, rewrite referenced scripts on disk, and exe…

### CVE-2026-32987
**openclaw openclaw Privilege Escalation**
- **Signals:** CVSS
- **Asset:** openclaw openclaw
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T17:53:28.313
- **CWE:** CWE-294
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-29)

> OpenClaw before 2026.3.13 allows bootstrap setup codes to be replayed during device pairing verification in src/infra/device-bootstrap.ts. Attackers can verify a valid bootstrap code multiple times before approval to escalate pending pairing scopes, including privilege escalation…

### CVE-2026-4176
**perl perl**
- **Signals:** CVSS
- **Asset:** perl perl
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T17:31:45.770
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-29)

> Perl versions from 5.9.4 before 5.40.4-RC1, from 5.41.0 before 5.42.2-RC1, from 5.43.0 before 5.43.9 contain a vulnerable version of Compress::Raw::Zlib.

Compress::Raw::Zlib is included in the Perl package as a dual-life core module, and is vulnerable to CVE-2026-3381 due to a v…

### CVE-2026-4851
**casiano grid::machine RCE**
- **Signals:** CVSS
- **Asset:** casiano grid\
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-01T15:23:23.980
- **CWE:** CWE-95
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-29)

> GRID::Machine versions through 0.127 for Perl allows arbitrary code execution via unsafe deserialization.

GRID::Machine provides Remote Procedure Calls (RPC) over SSH for Perl. The client connects to remote hosts to execute code on them. A compromised or malicious remote host ca…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-29*
