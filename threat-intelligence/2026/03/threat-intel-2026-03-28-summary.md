# Daily Threat Intelligence — March 28, 2026

**Digest window (UTC):** 2026-03-28
**Generated:** 2026-06-02T07:34:47Z

## Threat brief

Cogentdatahub Cogent Datahub — exploitation likelihood rose sharply (EPSS 6.8% → 28% · rising (+22%)). · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cogentdatahub Cogent Datahub — exploitation likelihood rose sharply (EPSS 6.8% → 28% · rising (+22%)).
- 9 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 9 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2011-3493
**cogentdatahub cogent_datahub Buffer Overflow**
- **Signals:** EPSS
- **Asset:** cogentdatahub cogent_datahub
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:13:23.040
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 6.8% (2025-10-24) → 28.3% (2026-03-28), Δ +21.5%**

> Multiple stack-based buffer overflows in the DH_OneSecondTick function in Cogent DataHub 7.1.1.63 and earlier allow remote attackers to cause a denial of service (crash) and possibly execute arbitrary code via long (1) domain, (2) report_domain, (3) register_datahub, or (4) slave…

### CVE-2025-15604
**tokuhirom amon2**
- **Signals:** CVSS
- **Asset:** tokuhirom amon2
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-01T15:16:23.170
- **CWE:** CWE-338
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-28)

> Amon2 versions before 6.17 for Perl use an insecure random_string implementation for security functions.

In versions 6.06 through 6.16, the random_string function will attempt to read bytes from the /dev/urandom device, but if that is unavailable then it generates bytes by conca…

### CVE-2026-3256
**ktat http::session**
- **Signals:** CVSS
- **Asset:** ktat http\
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-01T15:23:23.523
- **CWE:** CWE-338
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-28)

> HTTP::Session versions through 0.53 for Perl defaults to using insecurely generated session ids.

HTTP::Session defaults to using HTTP::Session::ID::SHA1 to generate session ids using a SHA-1 hash seeded with the built-in rand function, the high resolution epoch time, and the PID…

### CVE-2016-20049
**varaneckas jad_java_decompiler Buffer Overflow**
- **Signals:** CVSS
- **Asset:** varaneckas jad_java_decompiler
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-22T13:58:46.537
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-28)

> JAD 1.5.8e-1kali1 and prior contains a stack-based buffer overflow vulnerability that allows attackers to execute arbitrary code by supplying oversized input that exceeds buffer boundaries. Attackers can craft malicious input strings exceeding 8150 bytes to overflow the stack, ov…

### CVE-2017-20225
**ticalc tiemu Buffer Overflow**
- **Signals:** CVSS
- **Asset:** ticalc tiemu
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-08T19:49:58.627
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-28)

> TiEmu 2.08 and prior contains a stack-based buffer overflow vulnerability that allows attackers to execute arbitrary code by exploiting inadequate boundary checks on user-supplied input. Attackers can trigger the overflow through command-line arguments passed to the application, …

### CVE-2017-20227
**varaneckas jad_java_decompiler Buffer Overflow**
- **Signals:** CVSS
- **Asset:** varaneckas jad_java_decompiler
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-08T19:37:26.690
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-28)

> JAD Java Decompiler 1.5.8e-1kali1 and prior contains a stack-based buffer overflow vulnerability that allows attackers to execute arbitrary code by supplying overly long input that exceeds buffer boundaries. Attackers can craft malicious input passed to the jad command to overflo…

### CVE-2017-20229
**invisible-island mawk Buffer Overflow**
- **Signals:** CVSS
- **Asset:** invisible-island mawk
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-02T19:19:06.537
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-28)

> MAWK 1.3.3-17 and prior contains a stack-based buffer overflow vulnerability that allows attackers to execute arbitrary code by exploiting inadequate boundary checks on user-supplied input. Attackers can craft malicious input that overflows the stack buffer and execute a return-o…

### CVE-2018-25220
**bochs_project bochs Buffer Overflow**
- **Signals:** CVSS
- **Asset:** bochs_project bochs
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-02T19:18:20.330
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-28)

> Bochs 2.6-5 contains a stack-based buffer overflow vulnerability that allows attackers to execute arbitrary code by supplying an oversized input string to the application. Attackers can craft a malicious payload with 1200 bytes of padding followed by a return-oriented programming…

### CVE-2018-25221
**echatserver easy_chat_server Code Execution**
- **Signals:** CVSS
- **Asset:** echatserver easy_chat_server
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-02T19:15:19.013
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-28)

> EChat Server 3.1 contains a buffer overflow vulnerability in the chat.ghp endpoint that allows remote attackers to execute arbitrary code by supplying an oversized username parameter. Attackers can send a GET request to chat.ghp with a malicious username value containing shellcod…

### CVE-2018-25223
**ftnapps crashmail_ii Code Execution**
- **Signals:** CVSS
- **Asset:** ftnapps crashmail_ii
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-02T19:10:16.517
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-28)

> Crashmail 1.6 contains a stack-based buffer overflow vulnerability that allows remote attackers to execute arbitrary code by sending malicious input to the application. Attackers can craft payloads with ROP chains to achieve code execution in the application context, with failed …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-28*
