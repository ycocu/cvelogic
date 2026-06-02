# Daily Threat Intelligence — February 17, 2026

**Digest window (UTC):** 2026-02-17
**Generated:** 2026-06-02T07:34:26Z

## Threat brief

Google Chromium added to CISA KEV — confirmed in-the-wild exploitation. · Apache Tomcat — exploitation likelihood rose sharply (EPSS 61% → 73% · rising (+12%)). · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- Google Chromium added to CISA KEV — confirmed in-the-wild exploitation.
- Apache Tomcat — exploitation likelihood rose sharply (EPSS 61% → 73% · rising (+12%)).
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 4 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **13** |


## CVEs

### CVE-2008-0015
**Microsoft Windows Video ActiveX Control Remote Code Execution Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_2003_server
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-21T18:41:48.590
- **CWE:** CWE-119
- **CWE:** CWE-121
- **Risk score:** 88
- **KEV:** added 2026-02-17

> Stack-based buffer overflow in the CComVariant::ReadFromStream function in the Active Template Library (ATL), as used in the MPEG2TuneRequest ActiveX control in msvidctl.dll in DirectShow, in Microsoft Windows 2000 SP4, XP SP2 and SP3, Server 2003 SP2, Vista Gold, SP1, and SP2, a…

### CVE-2008-5515
**apache tomcat Directory Traversal**
- **Signals:** EPSS
- **Asset:** apache tomcat
- **Attack:** Directory Traversal
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-22
- **Risk score:** 78
- **EPSS 60.7% (2025-10-18) → 72.9% (2026-02-17), Δ +12.2%**

> Apache Tomcat 4.1.0 through 4.1.39, 5.5.0 through 5.5.27, 6.0.0 through 6.0.18, and possibly earlier versions normalizes the target pathname before filtering the query string when using the RequestDispatcher method, which allows remote attackers to bypass intended access restrict…

### CVE-2026-22769
**Dell RecoverPoint for Virtual Machines (RP4VMs) Use of Hard-coded Credentials Vulnerability**
- **Signals:** CVSS
- **Asset:** dell recoverpoint_for_virtual_machines
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-20T02:00:02.830
- **CWE:** CWE-798
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-17)

> Dell RecoverPoint for Virtual Machines, versions prior to 6.0.3.1 HF1, contain a hardcoded credential vulnerability. This is considered critical as an unauthenticated remote attacker with knowledge of the hardcoded credential could potentially exploit this vulnerability leading t…

### CVE-2020-7796
**Synacor Zimbra Collaboration Suite (ZCS) Server-Side Request Forgery Vulnerability**
- **Signals:** KEV
- **Asset:** synacor zimbra_collaboration_suite
- **Attack:** SSRF
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T13:46:55.423
- **CWE:** CWE-918
- **CWE:** CWE-918
- **Risk score:** 88
- **KEV:** added 2026-02-17

> Zimbra Collaboration Suite (ZCS) before 8.8.15 Patch 7 allows SSRF when WebEx zimlet is installed and zimlet JSP is enabled.

### CVE-2024-7694
**TeamT5 ThreatSonar Anti-Ransomware Unrestricted Upload of File with Dangerous Type Vulnerability**
- **Signals:** KEV
- **Asset:** teamt5 threatsonar_anti-ransomware
- **Attack:** privilege escalation
- **CVSS max:** 7.2
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T13:46:48.840
- **CWE:** CWE-434
- **Risk score:** 88
- **KEV:** added 2026-02-17

> ThreatSonar Anti-Ransomware from TeamT5 does not properly validate the content of uploaded files. Remote attackers with  administrator privileges on the product platform can upload malicious files, which can be used to execute arbitrary system command on the server.

### CVE-2025-59793
**rocketsoftware trufusion_enterprise Path Traversal**
- **Signals:** CVSS
- **Asset:** rocketsoftware trufusion_enterprise
- **Attack:** Path Traversal
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-03T11:34:55.547
- **CWE:** CWE-35
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-17)

> Rocket TRUfusion Enterprise through 7.10.5 exposes the endpoint at /axis2/services/WsPortalV6UpDwAxis2Impl to authenticated users to be able to upload files. However, the application doesn't properly sanitize the jobDirectory parameter, which allows path traversal sequences to be…

### CVE-2025-66614
**apache tomcat**
- **Signals:** CVSS
- **Asset:** apache tomcat
- **CVSS max:** 9.1
- **NVD status:** Modified
- **NVD modified:** 2026-03-11T16:16:20.410
- **CWE:** CWE-20
- **CWE:** CWE-295
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-17)

> Improper Input Validation vulnerability.

This issue affects Apache Tomcat: from 11.0.0-M1 through 11.0.14, from 10.1.0-M1 through 10.1.49, from 9.0.0-M1 through 9.0.112.

The following versions were EOL at the time the CVE was created but are 
known to be affected: 8.5.0 through…

### CVE-2025-70830
**A Server-Side Template Injection (SSTI) vulnerability in the Freemarker template engine of Datart v1.0.0-rc.3 allows authenticated attack...**
- **Signals:** CVSS
- **Attack:** SQL injection
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-02-17)

> A Server-Side Template Injection (SSTI) vulnerability in the Freemarker template engine of Datart v1.0.0-rc.3 allows authenticated attackers to execute arbitrary code via injecting crafted Freemarker template syntax into the SQL script field.

### CVE-2026-1670
**The affected products are vulnerable to an unauthenticated API endpoint exposure, which may allow an attacker to remotely change the "for...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-17)

> The affected products are vulnerable to an unauthenticated API endpoint exposure, which may allow an attacker to remotely change the "forgot password" recovery email address.

### CVE-2026-22208
**OpenS100 (the reference implementation S-100 viewer) prior to commit 753cf29 contains a remote code execution vulnerability via an unrest...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T14:16:28.767
- **CWE:** CWE-749
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-17)

> OpenS100 (the reference implementation S-100 viewer) prior to commit 753cf29 contains a remote code execution vulnerability via an unrestricted Lua interpreter. The Portrayal Engine initializes Lua using luaL_openlibs() without sandboxing or capability restrictions, exposing stan…

### CVE-2026-23647
**Glory RBG-100 recycler systems using the ISPK-08 software component contain hard-coded operating system credentials that allow remote aut...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-17)

> Glory RBG-100 recycler systems using the ISPK-08 software component contain hard-coded operating system credentials that allow remote authentication to the underlying Linux system. Multiple local user accounts, including accounts with administrative privileges, were found to have…

### CVE-2026-2441
**Google Chromium CSS Use-After-Free Vulnerability**
- **Signals:** KEV
- **Asset:** google chrome
- **Attack:** Use-After-Free
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T13:24:55.920
- **CWE:** CWE-416
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2026-02-17

> Use after free in CSS in Google Chrome prior to 145.0.7632.75 allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page. (Chromium security severity: High)

### CVE-2026-26220
**LightLLM version 1.1.0 and prior contain an unauthenticated remote code execution vulnerability in PD (prefill-decode) disaggregation mode.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-17)

> LightLLM version 1.1.0 and prior contain an unauthenticated remote code execution vulnerability in PD (prefill-decode) disaggregation mode. The PD master node exposes WebSocket endpoints that receive binary frames and pass the data directly to pickle.loads() without authenticatio…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-17*
