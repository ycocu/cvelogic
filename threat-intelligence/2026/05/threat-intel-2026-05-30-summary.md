# Daily Threat Intelligence — May 30, 2026

**Digest window (UTC):** 2026-05-30
**Generated:** 2026-06-02T07:04:09Z

## Threat brief

Powerdns Recursor — exploitation likelihood rose sharply (EPSS 20% → 71% · rising (+51%)).

## Executive summary

- Powerdns Recursor — exploitation likelihood rose sharply (EPSS 20% → 71% · rising (+51%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 7 |
| CVSS critical disclosure | 1 |
| Patch status change | 0 |
| **Total** | **8** |


## CVEs

### CVE-2018-16855
**powerdns recursor Out-of-Bounds Write**
- **Signals:** EPSS
- **Asset:** powerdns recursor
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T03:53:27.307
- **CWE:** CWE-125
- **CWE:** CWE-125
- **Risk score:** 82
- **EPSS 19.8% (2025-11-21) → 70.8% (2026-05-30), Δ +51.0%**

> An issue has been found in PowerDNS Recursor before version 4.1.8 where a remote attacker sending a DNS query can trigger an out-of-bounds memory read while computing the hash of the query for a packet cache lookup, possibly leading to a crash.

### CVE-2026-32202
**Microsoft Windows Protection Mechanism Failure Vulnerability**
- **Signals:** EPSS
- **Asset:** microsoft windows_10_1607
- **CVSS max:** 4.3
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-26T20:00:21.270
- **CWE:** CWE-693
- **Risk score:** 77
- **EPSS 10.8% (2026-05-27) → 56.8% (2026-05-30), Δ +46.1%**

> Protection mechanism failure in Windows Shell allows an unauthorized attacker to perform spoofing over a network.

### CVE-2018-25412
**Delta Sql 1.8.2 contains an arbitrary file upload vulnerability that allows unauthenticated attackers to upload malicious files by sendin...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Undergoing Analysis
- **NVD modified:** 2026-06-01T16:52:20.117
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-05-30)

> Delta Sql 1.8.2 contains an arbitrary file upload vulnerability that allows unauthenticated attackers to upload malicious files by sending POST requests to docs_upload.php with crafted multipart form data. Attackers can upload PHP files with arbitrary content to the upload direct…

### CVE-2019-11831
**debian debian_linux Directory Traversal**
- **Signals:** EPSS
- **Asset:** typo3 pharstreamwrapper
- **Attack:** Directory Traversal
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T04:21:50.990
- **CWE:** CWE-22
- **Risk score:** 86
- **EPSS 9.5% (2026-05-03) → 28.6% (2026-05-30), Δ +19.1%**

> The PharStreamWrapper (aka phar-stream-wrapper) package 2.x before 2.1.1 and 3.x before 3.1.1 for TYPO3 does not prevent directory traversal, which allows attackers to bypass a deserialization protection mechanism, as demonstrated by a phar:///path/bad.phar/../good.phar URL.

### CVE-2022-28005
**3cx 3cx Directory Traversal**
- **Signals:** EPSS
- **Asset:** 3cx 3cx
- **Attack:** Directory Traversal
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T06:56:35.623
- **CWE:** CWE-522
- **Risk score:** 86
- **EPSS 22.2% (2026-05-23) → 35.3% (2026-05-30), Δ +13.1%**

> An issue was discovered in the 3CX Phone System Management Console prior to version 18 Update 3 FINAL. An unauthenticated attacker could abuse improperly secured access to arbitrary files on the server (via /Electron/download directory traversal in conjunction with a path compone…

### CVE-2026-0257
**Palo Alto Networks PAN-OS Authentication Bypass Vulnerability**
- **Signals:** EPSS
- **Asset:** paloaltonetworks pan-os
- **Attack:** Auth Bypass
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-06-01T12:33:52.710
- **CWE:** CWE-565
- **Risk score:** 83
- **EPSS 0.1% (2026-05-14) → 41.5% (2026-05-30), Δ +41.5%**

> Authentication bypass vulnerabilities in the GlobalProtect portal and gateway of Palo Alto Networks PAN-OS® software allows the attacker to bypass security restrictions and establish an unauthorized VPN connection.

Panorama and Cloud NGFW are not impacted by these issues.

### CVE-2026-43284
**linux linux_kernel**
- **Signals:** EPSS
- **Asset:** linux linux_kernel
- **CVSS max:** 8.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-26T18:16:49.533
- **CWE:** CWE-123
- **Risk score:** 84
- **EPSS 25.6% (2026-05-28) → 38.5% (2026-05-30), Δ +12.9%**

> In the Linux kernel, the following vulnerability has been resolved:

xfrm: esp: avoid in-place decrypt on shared skb frags

MSG_SPLICE_PAGES can attach pages from a pipe directly to an skb. TCP
marks such skbs with SKBFL_SHARED_FRAG after skb_splice_from_iter(),
so later paths th…

### CVE-2026-43500
**linux linux_kernel**
- **Signals:** EPSS
- **Asset:** linux linux_kernel
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2026-05-17T16:16:16.740
- **CWE:** CWE-787
- **CWE:** CWE-787
- **Risk score:** 83
- **EPSS 27.0% (2026-05-28) → 40.3% (2026-05-30), Δ +13.3%**

> In the Linux kernel, the following vulnerability has been resolved:

rxrpc: Also unshare DATA/RESPONSE packets when paged frags are present

The DATA-packet handler in rxrpc_input_call_event() and the RESPONSE
handler in rxrpc_verify_response() copy the skb to a linear one before…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-30*
