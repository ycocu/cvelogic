# Daily Threat Intelligence — June 01, 2026

**Digest window (UTC):** 2026-06-01
**Generated:** 2026-06-02T07:52:55Z

## Threat brief

Oracle WebLogic Server added to CISA KEV — confirmed in-the-wild exploitation. · Drupal Core: public exploit or PoC linked (SQL Injection) · Backbox Linux — exploitation likelihood rose sharply (EPSS 20% → 51% · rising (+31%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Oracle WebLogic Server added to CISA KEV — confirmed in-the-wild exploitation.
- Drupal Core: public exploit or PoC linked (SQL Injection)
- Backbox Linux — exploitation likelihood rose sharply (EPSS 20% → 51% · rising (+31%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 2 |
| EPSS rise | 10 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **23** |


## CVEs

### CVE-2024-21182
**Oracle WebLogic Server Unspecified Vulnerability**
- **Signals:** KEV
- **Asset:** oracle weblogic_server
- **CVSS max:** 7.5
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-01T19:32:02.173
- **Risk score:** 88
- **KEV:** added 2026-06-01

> Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0 and  14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3, IIOP to compromise…

### CVE-2026-9082
**Drupal Core SQL Injection Vulnerability**
- **Signals:** EXP
- **Asset:** Drupal Core
- **Attack:** SQL Injection
- **CVSS max:** 6.5
- **NVD status:** Deferred
- **NVD modified:** 2026-05-21T15:24:25.330
- **CWE:** CWE-89
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2026-06-01

> Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Drupal Drupal core allows SQL Injection.

This issue affects Drupal core: from 8.9.0 before 10.4.10, from 10.5.0 before 10.5.10, from 10.6.0 before 10.6.9, from 11.0.0 before 11.…

### CVE-2017-7397
**backbox backbox_linux DoS**
- **Signals:** EPSS
- **Asset:** backbox backbox_linux
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-400
- **Risk score:** 82
- **EPSS 19.9% (2026-01-27) → 51.4% (2026-06-01), Δ +31.5%**

> BackBox Linux 4.6 allows remote attackers to cause a denial of service (ksoftirqd CPU consumption) via a flood of packets with Martian source IP addresses (as defined in RFC 1812 section 5.3.7). This product enables net.ipv4.conf.all.log_martians by default.  NOTE: the vendor rep…

### CVE-2012-10028
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 8.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 57.7% (2026-04-21) → 74.3% (2026-06-01), Δ +16.6%**

> Netwin SurgeFTP version 23c8 and prior contains a vulnerability in its web-based administrative console that allows authenticated users to execute arbitrary system commands via crafted POST requests to `surgeftpmgr.cgi`. This can lead to full remote code execution on the underlyi…

### CVE-2012-10029
**RCE · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** RCE
- **CVSS max:** 8.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 84
- **EPSS 50.8% (2026-04-21) → 69.4% (2026-06-01), Δ +18.6%**

> Nagios XI Network Monitor prior to Graph Explorer component version 1.3 contains a command injection vulnerability in `visApi.php`. An authenticated user can inject system commands via unsanitized parameters such as `host`, resulting in remote code execution.

### CVE-2012-10031
**Buffer Overflow · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** Buffer Overflow
- **CVSS max:** 8.6
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-121
- **Risk score:** 84
- **EPSS 57.0% (2026-04-21) → 73.8% (2026-06-01), Δ +16.8%**

> BlazeVideo HDTV Player Pro v6.6.0.3 is vulnerable to a stack-based buffer overflow due to improper handling of user-supplied input embedded in .plf playlist files. When parsing a crafted .plf file, the MediaPlayerCtrl.dll component invokes PathFindFileNameA() to extract a filenam…

### CVE-2012-10032
**privilege escalation · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** privilege escalation
- **CVSS max:** 8.7
- **NVD status:** Deferred
- **NVD modified:** 2026-05-26T00:16:42.270
- **CWE:** CWE-79
- **Risk score:** 84
- **EPSS 53.6% (2026-05-29) → 71.4% (2026-06-01), Δ +17.9%**

> Maxthon3 version 3.2.2 build 1000 and prior are vulnerable to cross context scripting (XCS) via the about:history page. The browser’s trusted zone improperly handles injected script content, allowing attackers to execute arbitrary JavaScript in a privileged context. This flaw ena…

### CVE-2012-10034
**csphere clansphere**
- **Signals:** EPSS
- **Asset:** csphere clansphere
- **CVSS max:** 8.7
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-23T18:46:19.117
- **CWE:** CWE-22
- **Risk score:** 84
- **EPSS 23.2% (2026-04-21) → 42.6% (2026-06-01), Δ +19.4%**

> ClanSphere 2011.3 is vulnerable to a local file inclusion (LFI) flaw due to improper handling of the cs_lang cookie parameter. The application fails to sanitize user-supplied input, allowing attackers to traverse directories and read arbitrary files outside the web root. The vuln…

### CVE-2012-3259
**hp sitescope**
- **Signals:** EPSS
- **Asset:** hp sitescope
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **Risk score:** 86
- **EPSS 23.7% (2026-05-27) → 46.0% (2026-06-01), Δ +22.2%**

> Unspecified vulnerability in a SOAP feature in HP SiteScope 11.10 through 11.12 allows remote attackers to execute arbitrary code via unknown vectors, aka ZDI-CAN-1461.

### CVE-2013-10065
**sysax multi_server**
- **Signals:** EPSS
- **Asset:** sysax multi_server
- **CVSS max:** 8.7
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-02T17:32:44.593
- **CWE:** CWE-248
- **Risk score:** 84
- **EPSS 53.1% (2026-04-21) → 71.1% (2026-06-01), Δ +18.0%**

> A denial-of-service vulnerability exists in Sysax Multi-Server version 6.10 via its SSH daemon. A specially crafted SSH key exchange packet can trigger a crash in the service, resulting in loss of availability. The flaw is triggered during the handling of malformed key exchange d…

### CVE-2013-10067
**privilege escalation · EPSS dynamics**
- **Signals:** EPSS
- **Attack:** privilege escalation
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **Risk score:** 85
- **EPSS 32.1% (2026-04-21) → 53.0% (2026-06-01), Δ +20.9%**

> Glossword versions 1.8.8 through 1.8.12 contain an authenticated arbitrary file upload vulnerability. When deployed as a standalone application, the administrative interface (gw_admin.php) allows users with administrator privileges to upload files to the gw_temp/a/ directory. Due…

### CVE-2014-125113
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 85
- **EPSS 56.5% (2026-04-21) → 76.6% (2026-06-01), Δ +20.1%**

> An unrestricted file upload vulnerability exists in Dell (acquired by Quest) KACE K1000 System Management Appliance version 5.0 - 5.3, 5.4 prior to 5.4.76849, and 5.5 prior to 5.5.90547 in the download_agent.php endpoint. An attacker can upload arbitrary PHP files to a temporary …

### CVE-2018-25427
**Arm Whois 3.11 contains a stack-based buffer overflow vulnerability that allows remote attackers to execute arbitrary code by supplying o...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-01T22:16:14.693
- **CWE:** CWE-121
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-01)

> Arm Whois 3.11 contains a stack-based buffer overflow vulnerability that allows remote attackers to execute arbitrary code by supplying oversized input to the IP address or domain field. Attackers can craft malicious input exceeding 658 bytes with shellcode to overwrite the struc…

### CVE-2025-10162
**The Admin and Customer Messages After Order for WooCommerce: OrderConvo WordPress plugin before 14 does not validate the path of files to...**
- **Signals:** EXP
- **Attack:** Path Traversal
- **CVSS max:** 7.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **Risk score:** 78
- **EXP:** ref published 2026-06-01

> The Admin and Customer Messages After Order for WooCommerce: OrderConvo WordPress plugin before 14 does not validate the path of files to be downloaded, which could allow unauthenticated attacker to read/download arbitrary files via a path traversal attack

### CVE-2026-0072
**In addInputMethodListener of com.android.server.inputmethod.InputMethodManagerService, there is a missing permission check.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD modified:** 2026-06-01T19:16:19.337
- **CWE:** CWE-285
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-01)

> In addInputMethodListener of com.android.server.inputmethod.InputMethodManagerService, there is a missing permission check. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

### CVE-2026-25879
**Langroid is a framework for building large-language-model-powered applications.**
- **Signals:** CVSS
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD modified:** 2026-06-01T23:16:21.930
- **CWE:** CWE-89
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-01)

> Langroid is a framework for building large-language-model-powered applications. Prior to version 0.63.0, SQLChatAgent executes SQL produced by an LLM, which is influenceable by prompt injection. When configured with a database role that has privileges enabling code execution or f…

### CVE-2026-40965
**Cloud Foundry UAA versions v76.12.0 through v78.12.0 are vulnerable to a private key exposure.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD modified:** 2026-06-01T22:16:25.600
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-01)

> Cloud Foundry UAA versions v76.12.0 through v78.12.0 are vulnerable to a private key exposure. The server contains a vulnerability where EC (Elliptic Curve) private keys are inadvertently exposed through the public /token_keys endpoint. This endpoint is designed to provide public…

### CVE-2026-45131
**CloudPirates Open Source Helm Charts is a collection of Helm charts.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-06-01T18:14:29.087
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-01)

> CloudPirates Open Source Helm Charts is a collection of Helm charts. Prior to commit fcf9302, a GitHub Actions workflow (pull-request.yaml) executes attacker-controlled code from fork pull requests in a privileged context, exposing repository secrets including Docker Hub credenti…

### CVE-2026-45132
**CloudPirates Open Source Helm Charts is a collection of Helm charts.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-06-01T18:14:29.087
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-01)

> CloudPirates Open Source Helm Charts is a collection of Helm charts. Prior to commit fcf9302, a GitHub Actions workflow (generate-schema.yaml) exposes sensitive credentials (Personal Access Token and SSH signing key) to fork-controlled code due to unsafe checkout and credential h…

### CVE-2026-49121
**AI Tensor Engine for ROCm (AITER) through 0.1.14 contains an unauthenticated remote code execution vulnerability in the MessageQueue.recv...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.2
- **NVD status:** Received
- **NVD modified:** 2026-06-01T19:16:54.180
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-01)

> AI Tensor Engine for ROCm (AITER) through 0.1.14 contains an unauthenticated remote code execution vulnerability in the MessageQueue.recv() function within shm_broadcast.py that allows unauthenticated remote attackers to execute arbitrary code by sending a malicious pickle payloa…

### CVE-2026-8644
**IBM WebSphere Application Server 9.0, and 8.5 is vulnerable to identity spoofing.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Received
- **NVD modified:** 2026-06-01T19:16:55.097
- **CWE:** CWE-290
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-01)

> IBM WebSphere Application Server 9.0, and 8.5 is vulnerable to identity spoofing.

### CVE-2026-9311
**IBM WebSphere Application Server 9.0, and 8.5 is vulnerable to remote code execution caused by the bypass of security controls.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Received
- **NVD modified:** 2026-06-01T19:16:55.537
- **CWE:** CWE-94
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-06-01)

> IBM WebSphere Application Server 9.0, and 8.5 is vulnerable to remote code execution caused by the bypass of security controls.

### CVE-2026-9319
**IBM WebSphere Application Server 9.0, and 8.5 is vulnerable to potential remote code execution due to deserialization of untrusted data v...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.0
- **NVD status:** Received
- **NVD modified:** 2026-06-01T19:16:55.680
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2026-06-01)

> IBM WebSphere Application Server 9.0, and 8.5 is vulnerable to potential remote code execution due to deserialization of untrusted data via JAX-WS endpoints with WS-Security.

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-01*
