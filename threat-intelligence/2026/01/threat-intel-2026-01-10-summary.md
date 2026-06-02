# Daily Threat Intelligence — January 10, 2026

**Digest window (UTC):** 2026-01-10
**Generated:** 2026-06-02T07:34:09Z

## Threat brief

Mathi Peamp — exploitation likelihood rose sharply (EPSS 6.9% → 23% · rising (+16%)). · 4 new critical disclosures — review patch status on exposed services.

## Executive summary

- Mathi Peamp — exploitation likelihood rose sharply (EPSS 6.9% → 23% · rising (+16%)).
- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 2 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **6** |


## CVEs

### CVE-2009-2384
**mathi peamp Buffer Overflow**
- **Signals:** EPSS
- **Asset:** mathi peamp
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 6.9% (2025-11-27) → 23.2% (2026-01-10), Δ +16.3%**

> Buffer overflow in amp.exe in Brothersoft PEamp 1.02b allows user-assisted remote attackers to execute arbitrary code via a long string in a .m3u playlist file.  NOTE: some of these details are obtained from third party information.

### CVE-2009-2363
**yukudr audioplus Buffer Overflow**
- **Signals:** EPSS
- **Asset:** yukudr audioplus
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 8.1% (2025-11-27) → 21.4% (2026-01-10), Δ +13.3%**

> Stack-based buffer overflow in KUDRSOFT AudioPLUS 2.00.215 allows remote attackers to execute arbitrary code via a .pls playlist file with a playlist entry containing a long File1 argument.

### CVE-2025-65091
**xwiki full_calendar_macro SQL Injection**
- **Signals:** CVSS
- **Asset:** xwiki full_calendar_macro
- **Attack:** SQL Injection
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-29T17:27:49.870
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-01-10)

> XWiki Full Calendar Macro displays objects from the wiki on the calendar. Prior to version 2.4.5, users with the right to view the Calendar.JSONService page (including guest users) can exploit a SQL injection vulnerability by accessing database info or starting a DoS attack. This…

### CVE-2025-61686
**shopify react-router\/node**
- **Signals:** CVSS
- **Asset:** shopify react-router\/node
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-04T14:52:53.283
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-10)

> React Router is a router for React. In @react-router/node versions 7.0.0 through 7.9.3, @remix-run/deno prior to version 2.17.2, and @remix-run/node prior to version 2.17.2, if createFileSessionStorage() is being used from @react-router/node (or @remix-run/node/@remix-run/deno in…

### CVE-2026-22600
**openproject openproject**
- **Signals:** CVSS
- **Asset:** openproject openproject
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-14T22:25:56.047
- **CWE:** CWE-200
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-01-10)

> OpenProject is an open-source, web-based project management software. A Local File Read (LFR) vulnerability exists in the work package PDF export functionality of OpenProject prior to version 16.6.4. By uploading a specially crafted SVG file (disguised as a PNG) as a work package…

### CVE-2026-22688
**tencent weknora Command Injection**
- **Signals:** CVSS
- **Asset:** tencent weknora
- **Attack:** Command Injection
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-22T14:39:17.193
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-01-10)

> WeKnora is an LLM-powered framework designed for deep document understanding and semantic retrieval. Prior to version 0.2.5, there is a command injection vulnerability that allows authenticated users to inject stdio_config.command/args into MCP stdio settings, causing the server …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-10*
