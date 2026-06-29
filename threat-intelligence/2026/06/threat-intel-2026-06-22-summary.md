# Daily Threat Intelligence — June 22, 2026

**Digest window (US Eastern, NVD):** 2026-06-22
**Generated:** 2026-06-29T10:33:09Z

## Threat brief

Avaya Definity One Media Server — exploitation likelihood rose sharply (EPSS 3.3% → 24% · rising (+21%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Avaya Definity One Media Server — exploitation likelihood rose sharply (EPSS 3.3% → 24% · rising (+21%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **14** |


## CVEs

### CVE-2004-0205
**avaya definity_one_media_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** avaya ip600_media_servers
- **Attack:** Buffer Overflow
- **CVSS max:** 7.2
- **NVD status:** Modified
- **NVD published:** 2004-08-06
- **NVD modified:** 2026-06-16
- **Risk score:** 82
- **EPSS 3.3% (2026-06-15) → 24.5% (2026-06-22), Δ +21.2%**

> Buffer overflow in Microsoft Internet Information Server (IIS) 4.0 allows local users to execute arbitrary code via the redirect function.

### CVE-2004-0213
**microsoft windows_2000 privilege escalation**
- **Signals:** EPSS
- **Asset:** microsoft windows_2000
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD published:** 2004-08-06
- **NVD modified:** 2026-06-16
- **CWE:** CWE-306
- **Risk score:** 83
- **EPSS 2.8% (2026-06-20) → 21.3% (2026-06-22), Δ +18.4%**

> Utility Manager in Windows 2000 launches winhlp32.exe while Utility Manager is running with raised privileges, which allows local users to gain system privileges via a "Shatter" style attack that sends a Windows message to cause Utility Manager to launch winhlp32 by directly acce…

### CVE-2026-7664
**langflow langflow privilege escalation**
- **Signals:** CVSS
- **Asset:** langflow langflow
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-06-22
- **NVD modified:** 2026-06-26
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-22)

> IBM Langflow OSS 1.0.0 through 1.8.4 could allow unauthenticated attackers to access protected MCP project resources and execute MCP operations due to improper authorization enforcement in the Streamable MCP transport endpoint.

### CVE-2008-5053
**joomla com_rssreader**
- **Signals:** EPSS
- **Asset:** joomla com_rssreader
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD published:** 2008-11-13
- **NVD modified:** 2026-06-16
- **CWE:** CWE-94
- **Risk score:** 86
- **EPSS 47.0% (2026-06-15) → 63.3% (2026-06-22), Δ +16.3%**

> PHP remote file inclusion vulnerability in admin.rssreader.php in the Simple RSS Reader (com_rssreader) 1.0 component for Joomla! allows remote attackers to execute arbitrary PHP code via a URL in the mosConfig_live_site parameter.

### CVE-2025-30349
**horde imp XSS**
- **Signals:** EPSS
- **Asset:** horde imp
- **Attack:** XSS
- **CVSS max:** 7.2
- **NVD status:** Deferred
- **NVD published:** 2025-03-21
- **NVD modified:** 2026-06-17
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 17.8% (2026-06-15) → 29.2% (2026-06-22), Δ +11.4%**

> Horde IMP through 6.2.27, as used with Horde Application Framework through 5.2.23, allows XSS that leads to account takeover via a crafted text/html e-mail message with an onerror attribute (that may use base64-encoded JavaScript code), as exploited in the wild in March 2025.

### CVE-2026-10789
**autodesk fusion RCE**
- **Signals:** CVSS
- **Asset:** autodesk fusion
- **Attack:** RCE
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD published:** 2026-06-22
- **NVD modified:** 2026-06-24
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-22)

> A maliciously crafted webpage, when visited by a user with Autodesk Fusion Desktop running and the MCP extension enabled, can trigger a vulnerability in the MCP extension that could allow arbitrary code execution. A successful exploit may allow code to execute with the privileges…

### CVE-2026-12249
**An issue was discovered in Canonical ADSys upstream versions through v0.16.2.**
- **Signals:** CVSS
- **CVSS max:** 9.0
- **NVD status:** Awaiting Analysis
- **NVD published:** 2026-06-22
- **NVD modified:** 2026-06-22
- **CWE:** CWE-348
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-06-22)

> An issue was discovered in Canonical ADSys upstream versions through v0.16.2. During Active Directory Certificate Services (AD CS) certificate auto-enrollment via the vendored Samba client script (internal/policies/certificate/python/vendor_samba/gp/gp_cert_auto_enroll_ext.py), A…

### CVE-2026-12628
**ibm storage_protect**
- **Signals:** CVSS
- **Asset:** ibm storage_protect
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD published:** 2026-06-22
- **NVD modified:** 2026-06-26
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-22)

> IBM Storage Protect Client 8.1.0.0 through 8.2.1.0 and IBM Storage Protect Snapshot For Windows 8.1.0.0 through 8.2.1.0 could allow a remote attacker to bypass authentication due to the use of a hardcoded credential in the FlashCopy Manager (FCM) authentication mechanism. The app…

### CVE-2026-44727
**jupyter jupyter_server XSS**
- **Signals:** CVSS
- **Asset:** jupyter jupyter_server
- **Attack:** XSS
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD published:** 2026-06-22
- **NVD modified:** 2026-06-26
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-22)

> Jupyter Server is the backend for Jupyter web applications. Prior to 2.20, the nbconvert HTTP handlers in jupyter_server render user-authored notebook HTML under the Jupyter origin without a sandbox directive in their Content-Security-Policy. Combined with nbconvert.HTMLExporter'…

### CVE-2026-45034
**PhpSpreadsheet is a pure PHP library for reading and writing spreadsheet files.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD published:** 2026-06-22
- **NVD modified:** 2026-06-23
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-22)

> PhpSpreadsheet is a pure PHP library for reading and writing spreadsheet files. Prior to 1.30.5, CVE-2026-34084 was patched by the helper File::prohibitWrappers. The helper calls parse_url($filename, PHP_URL_SCHEME) and then checks is_string($scheme) && strlen($scheme) > 1 to rej…

### CVE-2026-48746
**vllm vllm Auth Bypass**
- **Signals:** CVSS
- **Asset:** vllm vllm
- **Attack:** Auth Bypass
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD published:** 2026-06-22
- **NVD modified:** 2026-06-24
- **CWE:** CWE-444
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-22)

> vLLM is an inference and serving engine for large language models (LLMs). From 0.3.0 until 0.22.0, a vulnerability in ASGI web servers and starlette's trust on those web servers enables an authentication bypass of the OpenAI API AuthenticationMiddleware. It allows to use the API …

### CVE-2026-49468
**litellm litellm**
- **Signals:** CVSS
- **Asset:** litellm litellm
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD published:** 2026-06-22
- **NVD modified:** 2026-06-24
- **CWE:** CWE-290
- **Risk score:** 66
- **CVSS critical:** 9.5 (disclosed 2026-06-22)

> LiteLLM is a proxy server (AI Gateway) to call LLM APIs in OpenAI (or native) format. Prior to 1.84.0,  This vulnerability is fixed in 1.84.0.

### CVE-2026-56266
**Crawl4AI before 0.8.7 contains a server-side request forgery vulnerability in the /crawl, /crawl/stream, /md, and /llm endpoints that fet...**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Undergoing Analysis
- **NVD published:** 2026-06-22
- **NVD modified:** 2026-06-23
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-22)

> Crawl4AI before 0.8.7 contains a server-side request forgery vulnerability in the /crawl, /crawl/stream, /md, and /llm endpoints that fetch arbitrary user-supplied URLs without validation. Unauthenticated attackers can bypass the internal-address blocklist using IPv6-mapped IPv4 …

### CVE-2026-7166
**Vulnerability involving the exposure of sensitive data provided without adequate protection.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD published:** 2026-06-22
- **NVD modified:** 2026-06-22
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-22)

> Vulnerability involving the exposure of sensitive data provided without adequate protection. The API exposes email and phone number data from the ‘email’ and ‘telefon’ fields. This vulnerability is also present in the local database, as it contains accessible sensitive informatio…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-22*
