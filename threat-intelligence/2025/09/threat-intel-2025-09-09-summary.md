# Daily Threat Intelligence — September 09, 2025

**Digest window (UTC):** 2025-09-09
**Generated:** 2026-06-02T07:33:23Z

## Threat brief

Dlink Dir-816 Firmware — exploitation likelihood rose sharply (EPSS 9.9% → 22% · rising (+12%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Dlink Dir-816 Firmware — exploitation likelihood rose sharply (EPSS 9.9% → 22% · rising (+12%)).
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

### CVE-2022-37125
**dlink dir-816_firmware Command Injection**
- **Signals:** EPSS
- **Asset:** dlink dir-816_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:14:29.310
- **CWE:** CWE-77
- **Risk score:** 85
- **EPSS 9.9% (2025-09-02) → 21.9% (2025-09-09), Δ +12.0%**

> D-link DIR-816 A2_v1.10CNB04.img is vulnerable to Command injection via /goform/NTPSyncWithHost.

### CVE-2021-42133
**ivanti avalanche**
- **Signals:** EPSS
- **Asset:** ivanti avalanche
- **CVSS max:** 8.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:27:19.740
- **CWE:** CWE-434
- **CWE:** CWE-829
- **Risk score:** 81
- **EPSS 3.6% (2025-05-16) → 14.4% (2025-09-09), Δ +10.8%**

> An exposed dangerous function vulnerability exists in Ivanti Avalanche before 6.3.3 allows an attacker with access to the Inforail Service to perform an arbitrary file write.

### CVE-2025-58447
**rathena rathena Buffer Overflow**
- **Signals:** CVSS
- **Asset:** rathena rathena
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-17T20:53:21.610
- **CWE:** CWE-122
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-09)

> rAthena is an open-source cross-platform massively multiplayer online role playing game (MMORPG) server. Versions prior to commit 2f5248b have a heap-based buffer overflow in the login server, remote attacker to overwrite adjacent session fields by sending a crafted `CA_SSO_LOGIN…

### CVE-2025-10159
**An authentication bypass vulnerability allows remote attackers to gain administrative privileges on Sophos AP6 Series Wireless Access Poi...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-620
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-09)

> An authentication bypass vulnerability allows remote attackers to gain administrative privileges on Sophos AP6 Series Wireless Access Points older than firmware version 1.7.2563 (MR7).

### CVE-2025-44594
**halo halo SSRF**
- **Signals:** CVSS
- **Asset:** halo halo
- **Attack:** SSRF
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-17T19:34:21.873
- **CWE:** CWE-918
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-09)

> halo v2.20.17 and before is vulnerable to server-side request forgery (SSRF) in /apis/uc.api.storage.halo.run/v1alpha1/attachments/-/upload-from-url.

### CVE-2025-57633
**A command injection vulnerability in FTP-Flask-python through 5173b68 allows unauthenticated remote attackers to execute arbitrary OS com...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-09)

> A command injection vulnerability in FTP-Flask-python through 5173b68 allows unauthenticated remote attackers to execute arbitrary OS commands. The /ftp.html endpoint's "Upload File" action constructs a shell command from the ftp_file parameter and executes it using os.system() w…

### CVE-2025-58448
**rathena rathena SQL Injection**
- **Signals:** CVSS
- **Asset:** rathena rathena
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-17T20:36:12.373
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-09)

> rAthena is an open-source cross-platform massively multiplayer online role playing game (MMORPG) server. Versions prior to commit 0d89ae0 have a SQL Injection in the PartyBooking component via `WorldName` parameter. Commit 0d89ae0 fixes the issue.

### CVE-2025-58462
**opexustech foiaxpress_public_access_link SQL Injection**
- **Signals:** CVSS
- **Asset:** opexustech foiaxpress_public_access_link
- **Attack:** SQL Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-26T13:39:18.220
- **CWE:** CWE-89
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-09)

> OPEXUS FOIAXpress Public Access Link (PAL) before version 11.13.1.0 allows SQL injection via SearchPopularDocs.aspx. A remote, unauthenticated attacker could read, write, or delete any content in the underlying database.

### CVE-2025-58762
**tautulli tautulli RCE**
- **Signals:** CVSS
- **Asset:** tautulli tautulli
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-18T16:57:38.987
- **CWE:** CWE-73
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-09-09)

> Tautulli is a Python based monitoring and tracking tool for Plex Media Server. In Tautulli v2.15.3 and earlier, an attacker with administrative access can use the `pms_image_proxy` endpoint to write arbitrary python scripts into the application filesystem. This leads to remote co…

### CVE-2025-58768
**thinkinai deepchat**
- **Signals:** CVSS
- **Asset:** thinkinai deepchat
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-18T20:26:13.443
- **CWE:** CWE-94
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-09-09)

> DeepChat is a smart assistant uses artificial intelligence. Prior to version 0.3.5, in the Mermaid chart rendering component, there is a risky operation of directly using `innerHTML` to set user content. Therefore, any malicious content rendered via Mermaid will directly trigger …

### CVE-2025-59039
**Prebid Universal Creative (PUC) is a JavaScript API to render multiple formats.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-506
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-09-09)

> Prebid Universal Creative (PUC) is a JavaScript API to render multiple formats. Npm users of PUC 1.17.3 or PUC latest were briefly affected by crypto-related malware. This includes the extremely popular jsdelivr hosting of this file. The maintainers of PUC unpublished version 1.1…

### CVE-2025-59046
**The npm package `interactive-git-checkout` is an interactive command-line tool that allows users to checkout a git branch while it prompt...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-77
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-09-09)

> The npm package `interactive-git-checkout` is an interactive command-line tool that allows users to checkout a git branch while it prompts for the branch name on the command-line. It is available as an npm package and can be installed via `npm install -g interactive-git-checkout`…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-09-09*
