# Daily Threat Intelligence — December 30, 2025

**Digest window (UTC):** 2025-12-30
**Generated:** 2026-06-02T07:34:05Z

## Threat brief

Pnphpbb2 — exploitation likelihood rose sharply (EPSS 6.2% → 49% · rising (+43%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Pnphpbb2 — exploitation likelihood rose sharply (EPSS 6.2% → 49% · rising (+43%)).
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

### CVE-2009-0592
**pnphpbb pnphpbb2 Directory Traversal**
- **Signals:** EPSS
- **Asset:** pnphpbb pnphpbb2
- **Attack:** Directory Traversal
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-22
- **Risk score:** 82
- **EPSS 6.2% (2025-09-04) → 49.1% (2025-12-30), Δ +42.9%**

> Multiple directory traversal vulnerabilities in PNphpBB2 1.2i and earlier allow remote attackers to include and execute arbitrary local files via a .. (dot dot) in the ModName parameter to (1) admin_words.php, (2) admin_groups_reapir.php, (3) admin_smilies.php, (4) admin_ranks.ph…

### CVE-2004-1390
**qnx rtos Buffer Overflow**
- **Signals:** EPSS
- **Asset:** qnx rtos
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-16T00:27:16.627
- **Risk score:** 86
- **EPSS 9.6% (2025-04-19) → 25.6% (2025-12-30), Δ +16.0%**

> Multiple buffer overflows in the PPPoE daemon (PPPoEd) in QNX RTP 6.1 allow remote attackers to execute arbitrary code via a long argument to the (1) -F, (2) name, (3) en, (4) upscript, (5) downscript, (6) retries, (7) timeout, (8) scriptdetach, (9) noscript, (10) nodetach, (11) …

### CVE-2022-50794
**sound4 big_voice2_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** sound4 impact_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-01-13T14:34:19.790
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-30)

> SOUND4 IMPACT/FIRST/PULSE/Eco versions 2.x and below contain an unauthenticated command injection vulnerability in the username parameter. Attackers can exploit index.php and login.php scripts by injecting arbitrary shell commands through the HTTP POST 'username' parameter to exe…

### CVE-2022-50691
**minidvblinux minidvblinux**
- **Signals:** CVSS
- **Asset:** minidvblinux minidvblinux
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-12T14:16:00.837
- **CWE:** CWE-78
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-30)

> MiniDVBLinux 5.4 contains a remote command execution vulnerability that allows unauthenticated attackers to execute arbitrary commands as root through the 'command' GET parameter. Attackers can exploit the /tpl/commands.sh endpoint by sending malicious command values to gain root…

### CVE-2022-50696
**sound4 big_voice2_firmware**
- **Signals:** CVSS
- **Asset:** sound4 first_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-16T19:16:11.050
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-30)

> SOUND4 IMPACT/FIRST/PULSE/Eco versions 2.x and below contain hardcoded credentials embedded in server binaries that cannot be modified through normal device operations. Attackers can leverage these static credentials to gain unauthorized access to the device across Linux and Wind…

### CVE-2022-50796
**sound4 big_voice2_firmware RCE**
- **Signals:** CVSS
- **Asset:** sound4 impact_firmware
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-16T19:16:12.300
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-30)

> SOUND4 IMPACT/FIRST/PULSE/Eco <=2.x contains an unauthenticated remote code execution vulnerability in the firmware upload functionality with path traversal flaw. Attackers can exploit the upload.cgi script to write malicious files to the system with www-data permissions, enablin…

### CVE-2022-50803
**JM-DATA ONU JF511-TV version 1.0.67 uses default credentials that allow attackers to gain unauthorized access to the device with administ...**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-1392
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-30)

> JM-DATA ONU JF511-TV version 1.0.67 uses default credentials that allow attackers to gain unauthorized access to the device with administrative privileges.

### CVE-2023-53983
**ateme flamingo_xl_firmware**
- **Signals:** CVSS
- **Asset:** ateme flamingo_xl_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-16T19:16:14.653
- **CWE:** CWE-798
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-30)

> Anevia Flamingo XL/XS 3.6.20 contains a critical vulnerability with weak default administrative credentials that can be easily guessed. Attackers can leverage these hard-coded credentials to gain full remote system control without complex authentication mechanisms.

### CVE-2023-54327
**tinycontrol lan_controller_firmware Auth Bypass**
- **Signals:** CVSS
- **Asset:** tinycontrol lan_controller_firmware
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-01-16T19:16:15.010
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-30)

> Tinycontrol LAN Controller 1.58a contains an authentication bypass vulnerability that allows unauthenticated attackers to change admin passwords through a crafted API request. Attackers can exploit the /stm.cgi endpoint with a specially crafted authentication parameter to disable…

### CVE-2025-15111
**kseniasecurity lares_firmware**
- **Signals:** CVSS
- **Asset:** kseniasecurity lares_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-11T20:16:12.513
- **CWE:** CWE-259
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-30)

> Ksenia Security lares (legacy model) version 1.6 contains a default credentials vulnerability that allows unauthorized attackers to gain administrative access. Attackers can exploit the weak default administrative credentials to obtain full control of the home automation system.

### CVE-2025-15113
**kseniasecurity lares_firmware**
- **Signals:** CVSS
- **Asset:** kseniasecurity lares_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-11T20:16:13.410
- **CWE:** CWE-256
- **CWE:** CWE-522
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-30)

> Ksenia Security lares (legacy model) Home Automation version 1.6 contains an unprotected endpoint vulnerability that allows authenticated attackers to upload MPFS File System binary images. Attackers can exploit this vulnerability to overwrite flash program memory and potentially…

### CVE-2025-15114
**kseniasecurity lares_firmware**
- **Signals:** CVSS
- **Asset:** kseniasecurity lares_firmware
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-03-11T20:16:13.593
- **CWE:** CWE-403
- **CWE:** CWE-668
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-30)

> Ksenia Security lares (legacy model) Home Automation version 1.6 contains a critical security flaw that exposes the alarm system PIN in the 'basisInfo' XML file after authentication. Attackers can retrieve the PIN from the server response to bypass security measures and disable t…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-30*
