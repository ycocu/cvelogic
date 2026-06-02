# Daily Threat Intelligence — December 09, 2025

**Digest window (UTC):** 2025-12-09
**Generated:** 2026-06-02T07:33:56Z

## Threat brief

Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation. · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Microsoft Windows added to CISA KEV — confirmed in-the-wild exploitation.
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 2 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2025-6218
**RARLAB WinRAR Path Traversal Vulnerability**
- **Signals:** KEV
- **Asset:** rarlab winrar
- **Attack:** RCE
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T13:48:42.517
- **CWE:** CWE-22
- **Risk score:** 88
- **KEV:** added 2025-12-09

> RARLAB WinRAR Directory Traversal Remote Code Execution Vulnerability. This vulnerability allows remote attackers to execute arbitrary code on affected installations of RARLAB WinRAR. User interaction is required to exploit this vulnerability in that the target must visit a malic…

### CVE-2023-53739
**Tinycontrol LAN Controller v3 LK3 version 1.58a contains an unauthenticated vulnerability that allows remote attackers to download config...**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-260
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-12-09)

> Tinycontrol LAN Controller v3 LK3 version 1.58a contains an unauthenticated vulnerability that allows remote attackers to download configuration backup files containing sensitive credentials. Attackers can retrieve the lk3_settings.bin file and extract base64-encoded user and adm…

### CVE-2025-67489
**@vitejs/plugin-rs provides React Server Components (RSC) support for Vite.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-09)

> @vitejs/plugin-rs provides React Server Components (RSC) support for Vite. Versions 0.5.5 and below are vulnerable to arbitrary remote code execution on the development server through unsafe dynamic imports in server function APIs (loadServerAction, decodeReply, decodeAction) whe…

### CVE-2021-47707
**COMMAX CVD-Axx DVR 5.1.4 contains weak default administrative credentials that allow remote password attacks and disclose RTSP stream.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-09)

> COMMAX CVD-Axx DVR 5.1.4 contains weak default administrative credentials that allow remote password attacks and disclose RTSP stream. Attackers can exploit this by sending a POST request with the 'passkey' parameter set to '1234', allowing them to access the web control panel.

### CVE-2021-47708
**COMMAX Smart Home System CDP-1020n contains an SQL injection vulnerability that allows attackers to bypass authentication by injecting ar...**
- **Signals:** CVSS
- **Attack:** SQL Injection
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-09)

> COMMAX Smart Home System CDP-1020n contains an SQL injection vulnerability that allows attackers to bypass authentication by injecting arbitrary SQL code through the 'id' parameter in 'loginstart.asp'. Attackers can exploit this by sending a POST request with malicious 'id' value…

### CVE-2021-47728
**selea carplateserver Command Injection**
- **Signals:** CVSS
- **Asset:** selea izero_box_full_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T19:00:13.367
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-09)

> Selea Targa IP OCR-ANPR Camera contains an unauthenticated command injection vulnerability in utils.php that allows remote attackers to execute arbitrary shell commands. Attackers can exploit the 'addr' and 'port' parameters to inject commands and gain www-data user access throug…

### CVE-2021-47731
**selea carplateserver**
- **Signals:** CVSS
- **Asset:** selea izero_box_full_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T18:53:51.337
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-09)

> Selea Targa IP OCR-ANPR Camera contains a hard-coded developer password vulnerability that allows unauthorized configuration access through an undocumented page. Attackers can exploit the hidden endpoint by using the hard-coded password 'Selea781830' to enable configuration uploa…

### CVE-2023-53771
**minidvblinux minidvblinux Auth Bypass**
- **Signals:** CVSS
- **Asset:** minidvblinux minidvblinux
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T19:21:12.783
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-09)

> MiniDVBLinux 5.4 contains an authentication bypass vulnerability that allows remote attackers to change the root password without authentication. Attackers can send crafted POST requests to the system setup endpoint with modified SYSTEM_PASSWORD parameters to reset root credentia…

### CVE-2025-62221
**Microsoft Windows Use After Free Vulnerability**
- **Signals:** KEV
- **Asset:** microsoft windows_10_1809
- **Attack:** privilege escalation
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-10T13:48:09.333
- **CWE:** CWE-416
- **Risk score:** 88
- **KEV:** added 2025-12-09

> Use after free in Windows Cloud Files Mini Filter Driver allows an authorized attacker to elevate privileges locally.

### CVE-2025-66039
**sangoma freepbx Auth Bypass**
- **Signals:** CVSS
- **Asset:** sangoma freepbx
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-02T14:47:12.183
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-09)

> FreePBX Endpoint Manager is a module for managing telephony endpoints in FreePBX systems. Versions are vulnerable to authentication bypass when the authentication type is set to "webserver." When providing an Authorization header with an arbitrary value, a session is associated w…

### CVE-2025-66456
**elysiajs elysia**
- **Signals:** CVSS
- **Asset:** elysiajs elysia
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-17T14:30:08.047
- **CWE:** CWE-1321
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-09)

> Elysia is a Typescript framework for request validation, type inference, OpenAPI documentation and client-server communication. Versions 1.4.0 through 1.4.16 contain a prototype pollution vulnerability in `mergeDeep` after merging results of two standard schema validations with t…

### CVE-2025-67494
**zitadel zitadel SSRF**
- **Signals:** CVSS
- **Asset:** zitadel zitadel
- **Attack:** SSRF
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-19T18:53:34.883
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-09)

> ZITADEL is an open-source identity infrastructure tool. Versions 4.7.0 and below are vulnerable to an unauthenticated, full-read SSRF vulnerability. The ZITADEL Login UI (V2) treats the x-zitadel-forward-host header as a trusted fallback for all deployments, including self-hosted…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-09*
