# Daily Threat Intelligence — February 13, 2026

**Digest window (UTC):** 2026-02-13
**Generated:** 2026-06-02T07:34:25Z

## Threat brief

BeyondTrust Remote Support (RS) And Privileged Remote Access (PRA) added to CISA KEV — confirmed in-the-wild exploitation. · 7t Igss — exploitation likelihood rose sharply (EPSS 2.4% → 20% · rising (+18%)). · 8 new critical disclosures — review patch status on exposed services.

## Executive summary

- BeyondTrust Remote Support (RS) And Privileged Remote Access (PRA) added to CISA KEV — confirmed in-the-wild exploitation.
- 7t Igss — exploitation likelihood rose sharply (EPSS 2.4% → 20% · rising (+18%)).
- 8 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 8 |
| Patch status change | 0 |
| **Total** | **11** |


## CVEs

### CVE-2026-1731
**BeyondTrust Remote Support (RS) and Privileged Remote Access (PRA) OS Command Injection Vulnerability**
- **Signals:** KEV
- **Asset:** beyondtrust privileged_remote_access
- **Attack:** RCE
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-17T13:40:10.320
- **CWE:** CWE-78
- **Risk score:** 88
- **KEV:** added 2026-02-13

> BeyondTrust Remote Support (RS) and certain older versions of Privileged Remote Access (PRA) contain a critical pre-authentication remote code execution vulnerability. By sending specially crafted requests, an unauthenticated remote attacker may be able to execute operating syste…

### CVE-2011-4537
**7t igss Buffer Overflow**
- **Signals:** EPSS
- **Asset:** 7t igss
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 82
- **EPSS 2.4% (2025-11-17) → 20.2% (2026-02-13), Δ +17.8%**

> Multiple buffer overflows in 7-Technologies (7T) Interactive Graphical SCADA System (IGSS) 9.0.0.11355 and earlier allow remote attackers to execute arbitrary code or cause a denial of service via a crafted packet to TCP port (1) 12397 or (2) 12399.

### CVE-2026-26333
**calero verasmart**
- **Signals:** CVSS
- **Asset:** calero verasmart
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T22:46:30.153
- **CWE:** CWE-306
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-13)

> Calero VeraSMART versions prior to 2022 R1 expose an unauthenticated .NET Remoting HTTP service on TCP port 8001. The service publishes default ObjectURIs (including EndeavorServer.rem and RemoteFileReceiver.rem) and permits the use of SOAP and binary formatters with TypeFilterLe…

### CVE-2005-0416
**microsoft windows_2000 Buffer Overflow**
- **Signals:** EPSS
- **Asset:** microsoft windows_2000
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 80
- **EPSS 56.1% (2025-12-28) → 66.6% (2026-02-13), Δ +10.5%**

> The Windows Animated Cursor (ANI) capability in Windows NT, Windows 2000 through SP4, Windows XP through SP1, and Windows 2003 allows remote attackers to execute arbitrary code via the AnimationHeaderBlock length field, which leads to a stack-based buffer overflow.

### CVE-2025-69633
**A SQL Injection vulnerability in the Advanced Popup Creator (advancedpopupcreator) module for PrestaShop 1.1.26 through 1.2.6 (Fixed in v...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-13)

> A SQL Injection vulnerability in the Advanced Popup Creator (advancedpopupcreator) module for PrestaShop 1.1.26 through 1.2.6 (Fixed in version 1.2.7) allows remote unauthenticated attackers to execute arbitrary SQL queries via the fromController parameter in the popup controller…

### CVE-2025-69770
**A zip slip vulnerability in the /DesignTools/SkinList.aspx endpoint of MojoPortal CMS v2.9.0.1 allows attackers to execute arbitrary comm...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-13)

> A zip slip vulnerability in the /DesignTools/SkinList.aspx endpoint of MojoPortal CMS v2.9.0.1 allows attackers to execute arbitrary commands via uploading a crafted zip file.

### CVE-2026-23112
**linux linux_kernel**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-04T09:16:00.390
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-13)

> In the Linux kernel, the following vulnerability has been resolved:

nvmet-tcp: add bounds checks in nvmet_tcp_build_pdu_iovec

nvmet_tcp_build_pdu_iovec() could walk past cmd->req.sg when a PDU
length or offset exceeds sg_cnt and then use bogus sg->length/offset
values, leading …

### CVE-2026-26190
**milvus milvus Auth Bypass**
- **Signals:** CVSS
- **Asset:** milvus milvus
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T19:11:12.333
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-13)

> Milvus is an open-source vector database built for generative AI applications. Prior to 2.5.27 and 2.6.10, Milvus exposes TCP port 9091 by default, which enables authentication bypasses. The /expr debug endpoint uses a weak, predictable default authentication token derived from e…

### CVE-2026-26221
**Hyland OnBase contains an unauthenticated .NET Remoting exposure in the OnBase Workflow Timer Service (Hyland.Core.Workflow.NTService.exe).**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-13)

> Hyland OnBase contains an unauthenticated .NET Remoting exposure in the OnBase Workflow Timer Service (Hyland.Core.Workflow.NTService.exe). An attacker who can reach the service can send crafted .NET Remoting requests to default HTTP channel endpoints on TCP/8900 (e.g., TimerServ…

### CVE-2026-26273
**withknown known**
- **Signals:** CVSS
- **Asset:** withknown known
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T21:01:56.787
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-13)

> Known is a social publishing platform. Prior to 1.6.3, a Critical Broken Authentication vulnerability exists in Known 1.6.2 and earlier. The application leaks the password reset token within a hidden HTML input field on the password reset page. This allows any unauthenticated att…

### CVE-2026-26335
**calero verasmart Deserialization**
- **Signals:** CVSS
- **Asset:** calero verasmart
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T22:45:37.080
- **CWE:** CWE-321
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-13)

> Calero VeraSMART versions prior to 2022 R1 use static ASP.NET/IIS machineKey values configured for the VeraSMART web application and stored in C:\\Program Files (x86)\\Veramark\\VeraSMART\\WebRoot\\web.config. An attacker who obtains these keys can craft a valid ASP.NET ViewState…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-13*
