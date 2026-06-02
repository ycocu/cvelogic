# Daily Threat Intelligence — January 15, 2026

**Digest window (UTC):** 2026-01-15
**Generated:** 2026-06-02T07:34:11Z

## Threat brief

Kde Kmplayer — exploitation likelihood rose sharply (EPSS 6.6% → 21% · rising (+14%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Kde Kmplayer — exploitation likelihood rose sharply (EPSS 6.6% → 21% · rising (+14%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2009-2896
**kde kmplayer Buffer Overflow**
- **Signals:** EPSS
- **Asset:** kde kmplayer
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 6.6% (2026-01-09) → 20.9% (2026-01-15), Δ +14.4%**

> Buffer overflow in KMplayer 2.9.4.1433 and earlier allows remote attackers to cause a denial of service (application crash) or execute arbitrary code via a long string in a subtitle (.srt) playlist file. NOTE: some of these details are obtained from third party information.

### CVE-2025-70892
**phpgurukul cyber_cafe_management_system SQL Injection**
- **Signals:** CVSS
- **Asset:** phpgurukul cyber_cafe_management_system
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-22T16:00:53.547
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-15)

> Phpgurukul Cyber Cafe Management System v1.0 contains a SQL Injection vulnerability in the user management module. The application fails to properly validate user-supplied input in the username parameter of the add-users.php endpoint.

### CVE-2025-67079
**agora-project agora-project**
- **Signals:** CVSS
- **Asset:** agora-project agora-project
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-21T14:42:07.337
- **CWE:** CWE-434
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-15)

> File upload vulnerability in Omnispace Agora Project before 25.10 allowing attackers to execute code through the MSL engine of the Imagick library via crafted PDF file to the file upload and thumbnail functions.

### CVE-2011-10041
**Uploadify WordPress plugin versions up to and including 1.0 contain an arbitrary file upload vulnerability in process_upload.php due to m...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-15)

> Uploadify WordPress plugin versions up to and including 1.0 contain an arbitrary file upload vulnerability in process_upload.php due to missing file type validation. An unauthenticated remote attacker can upload arbitrary files to the affected WordPress site, which may allow remo…

### CVE-2023-7334
**chanjetvip t\+ RCE**
- **Signals:** CVSS
- **Asset:** chanjetvip t\+
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-23T19:51:22.190
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-15)

> Changjetong T+ versions up to and including 16.x contain a .NET deserialization vulnerability in an AjaxPro endpoint that can lead to remote code execution. A remote attacker can send a crafted request to /tplus/ajaxpro/Ufida.T.CodeBehind._PriorityLevel,App_Code.ashx?method=GetSt…

### CVE-2025-62193
**Sites running NOAA PMEL Live Access Server (LAS) are vulnerable to remote code execution via specially crafted requests that include PyFe...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-15)

> Sites running NOAA PMEL Live Access Server (LAS) are vulnerable to remote code execution via specially crafted requests that include PyFerret expressions. By leveraging a SPAWN command, a remote, unauthenticated attacker can execute arbitrary OS commands. Fixed in a version of 'g…

### CVE-2025-67822
**mitel mivoice_mx-one Auth Bypass**
- **Signals:** CVSS
- **Asset:** mitel mivoice_mx-one
- **Attack:** Auth Bypass
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-21T21:06:06.810
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-01-15)

> A vulnerability in the Provisioning Manager component of Mitel MiVoice MX-ONE 7.3 (7.3.0.0.50) through 7.8 SP1 (7.8.1.0.14) could allow an unauthenticated attacker to conduct an authentication bypass attack due to improper authentication mechanisms. A successful exploit could all…

### CVE-2026-1009
**altium altium_live XSS**
- **Signals:** CVSS
- **Asset:** altium altium_live
- **Attack:** XSS
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-23T19:32:23.350
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-01-15)

> A stored cross-site scripting (XSS) vulnerability exists in the Altium Forum due to missing server-side input sanitization in forum post content. An authenticated attacker can inject arbitrary JavaScript into forum posts, which is stored and executed when other users view the aff…

### CVE-2026-22863
**deno deno**
- **Signals:** CVSS
- **Asset:** deno deno
- **CVSS max:** 9.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-21T14:35:52.730
- **CWE:** CWE-325
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-01-15)

> Deno is a JavaScript, TypeScript, and WebAssembly runtime. Before 2.6.0, node:crypto doesn't finalize cipher. The vulnerability allows an attacker to have infinite encryptions. This can lead to naive attempts at brute forcing, as well as more refined attacks with the goal to lear…

### CVE-2026-23520
**arcane arcane Command Injection**
- **Signals:** CVSS
- **Asset:** arcane arcane
- **Attack:** Command Injection
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-05T21:37:01.000
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-01-15)

> Arcane provides modern docker management. Prior to 1.13.0, Arcane has a command injection in the updater service. Arcane’s updater service supported lifecycle labels com.getarcaneapp.arcane.lifecycle.pre-update and com.getarcaneapp.arcane.lifecycle.post-update that allowed defini…

### CVE-2026-23746
**Entrust Instant Financial Issuance (IFI) On Premise software (formerly referred to as CardWizard) versions 5.x, prior to 6.10.5, and prio...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-01-15)

> Entrust Instant Financial Issuance (IFI) On Premise software (formerly referred to as CardWizard) versions 5.x, prior to 6.10.5, and prior to 6.11.1 contain an insecure .NET Remoting exposure in the SmartCardController service (DCG.SmartCardControllerService.exe). The service reg…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-15*
