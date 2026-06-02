# Daily Threat Intelligence — February 02, 2026

**Digest window (UTC):** 2026-02-02
**Generated:** 2026-06-02T07:34:20Z

## Threat brief

Dlink Dir-825 Firmware: public exploit or PoC linked (Buffer Overflow) · Foxitsoftware Phantompdf — exploitation likelihood rose sharply (EPSS 16% → 50% · rising (+34%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Dlink Dir-825 Firmware: public exploit or PoC linked (Buffer Overflow)
- Foxitsoftware Phantompdf — exploitation likelihood rose sharply (EPSS 16% → 50% · rising (+34%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 2 |
| EPSS rise | 3 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2025-10370
**sourcefabric rpi-jukebox-rfid cross-site scripting**
- **Signals:** EXP
- **Asset:** sourcefabric rpi-jukebox-rfid
- **Attack:** cross-site scripting
- **CVSS max:** 5.4
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:00:01.613
- **CWE:** CWE-79
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2026-02-02

> A vulnerability was identified in MiczFlor RPi-Jukebox-RFID up to 2.8.0. This vulnerability affects unknown code of the file /htdocs/userScripts.php. The manipulation of the argument Custom script leads to cross site scripting. The attack is possible to be carried out remotely. T…

### CVE-2025-10666
**dlink dir-825_firmware Buffer Overflow**
- **Signals:** EXP
- **Asset:** dlink dir-825_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-02-03T22:16:27.113
- **CWE:** CWE-119
- **CWE:** CWE-120
- **Risk score:** 78
- **EXP:** ref published 2026-02-02

> A security flaw has been discovered in D-Link DIR-825 up to 2.10. Affected by this vulnerability is the function sub_4106d4 of the file apply.cgi. The manipulation of the argument countdown_time results in buffer overflow. The attack can be executed remotely. The exploit has been…

### CVE-2018-3964
**foxitsoftware phantompdf RCE**
- **Signals:** EPSS
- **Asset:** foxitsoftware phantompdf
- **Attack:** RCE
- **CVSS max:** 8.0
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:06:23.783
- **CWE:** CWE-416
- **Risk score:** 83
- **EPSS 16.0% (2025-11-21) → 50.1% (2026-02-02), Δ +34.1%**

> An exploitable use-after-free vulnerability exists in the JavaScript engine of Foxit Software's Foxit PDF Reader version 9.1.0.5096. A specially crafted PDF document can trigger a previously freed object in memory to be reused, resulting in arbitrary code execution. An attacker n…

### CVE-2010-0387
**sun java_system_web_server Buffer Overflow**
- **Signals:** EPSS
- **Asset:** sun java_system_web_server
- **Attack:** Buffer Overflow
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 80
- **EPSS 8.3% (2025-03-30) → 18.7% (2026-02-02), Δ +10.3%**

> Multiple heap-based buffer overflows in (1) webservd and (2) the admin server in Sun Java System Web Server 7.0 Update 7 allow remote attackers to cause a denial of service (daemon crash) and possibly have unspecified other impact via a long string in an "Authorization: Digest" H…

### CVE-2013-4978
**aloaha aloaha_pdf_suite_free Buffer Overflow**
- **Signals:** EPSS
- **Asset:** aloaha aloaha_pdf_suite_free
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 33.1% (2025-09-21) → 50.3% (2026-02-02), Δ +17.1%**

> Stack-based buffer overflow in AloahaPDFViewer 5.0.0.7 and earlier in Aloaha PDF Suite FREE allows remote attackers to execute arbitrary code via a crafted PDF file.

### CVE-2022-50981
**An unauthenticated remote attacker can gain full access on the affected devices as they are shipped without a password by default and set...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-02)

> An unauthenticated remote attacker can gain full access on the affected devices as they are shipped without a password by default and setting one is not enforced.

### CVE-2024-2356
**A Local File Inclusion (LFI) vulnerability exists in the '/reinstall_extension' endpoint of the parisneo/lollms-webui application, specif...**
- **Signals:** CVSS
- **CVSS max:** 9.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T14:34:27.800
- **CWE:** CWE-29
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-02-02)

> A Local File Inclusion (LFI) vulnerability exists in the '/reinstall_extension' endpoint of the parisneo/lollms-webui application, specifically within the `name` parameter of the `@router.post("/reinstall_extension")` route. This vulnerability allows attackers to inject a malicio…

### CVE-2024-5986
**RCE**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T14:34:27.800
- **CWE:** CWE-73
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-02)

> A vulnerability in h2oai/h2o-3 version 3.46.0.1 allows remote attackers to write arbitrary data to any file on the server. This is achieved by exploiting the `/3/Parse` endpoint to inject attacker-controlled data as the header of an empty file, which is then exported using the `/…

### CVE-2025-66480
**wildfirechat im-server**
- **Signals:** CVSS
- **Asset:** wildfirechat im-server
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-03T01:01:32.913
- **CWE:** CWE-22
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-02)

> Wildfire IM is an instant messaging and real-time audio/video solution. Prior to 1.4.3, a critical vulnerability exists in the im-server component related to the file upload functionality found in com.xiaoleilu.loServer.action.UploadFileAction. The application exposes an endpoint…

### CVE-2026-22778
**vllm vllm**
- **Signals:** CVSS
- **Asset:** vllm vllm
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-23T18:19:12.450
- **CWE:** CWE-532
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-02)

> vLLM is an inference and serving engine for large language models (LLMs). From 0.8.3 to before 0.14.1, when an invalid image is sent to vLLM's multimodal endpoint, PIL throws an error. vLLM returns this error to the client, leaking a heap address. With this leak, we reduce ASLR f…

### CVE-2026-23515
**signalk signal_k_server Command Injection**
- **Signals:** CVSS
- **Asset:** signalk signal_k_server
- **Attack:** Command Injection
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-27T13:46:54.247
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-02-02)

> Signal K Server is a server application that runs on a central hub in a boat. Prior to 1.5.0, a command injection vulnerability allows authenticated users with write permissions to execute arbitrary shell commands on the Signal K server when the set-system-time plugin is enabled.…

### CVE-2026-24471
**continuwuity is a Matrix homeserver written in Rust.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-441
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-02-02)

> continuwuity is a Matrix homeserver written in Rust. This vulnerability allows an attacker with a malicious remote server to cause the local server to sign an arbitrary event upon user interaction. Upon a user account leaving a room (rejecting an invite), joining a room or knocki…

### CVE-2026-25134
**group-office group_office RCE**
- **Signals:** CVSS
- **Asset:** group-office group_office
- **Attack:** RCE
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T17:35:28.413
- **CWE:** CWE-88
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-02-02)

> Group-Office is an enterprise customer relationship management and groupware tool. Prior to 6.8.150, 25.0.82, and 26.0.5, the MaintenanceController exposes an action zipLanguage which takes a lang parameter and passes it directly to a system zip command via exec(). This can be co…

### CVE-2026-25137
**The NixOs Odoo package is an open source ERP and CRM system.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-02-02)

> The NixOs Odoo package is an open source ERP and CRM system. From 21.11 to before 25.11 and 26.05, every NixOS based Odoo setup publicly exposes the database manager without any authentication. This allows unauthorized actors to delete and download the entire database, including …

### CVE-2026-25142
**nyariv sandboxjs RCE**
- **Signals:** CVSS
- **Asset:** nyariv sandboxjs
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-18T14:34:30.523
- **CWE:** CWE-94
- **CWE:** CWE-1321
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-02)

> SandboxJS is a JavaScript sandboxing library. Prior to 0.8.27, SanboxJS does not properly restrict __lookupGetter__ which can be used to obtain prototypes, which can be used for escaping the sandbox / remote code execution. This vulnerability is fixed in 0.8.27.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-02*
