# Daily Threat Intelligence — June 17, 2026

**Digest window (US Eastern, NVD):** 2026-06-17
**Generated:** 2026-06-21T09:42:46Z

## Threat brief

Check Point Security Gateway — exploitation likelihood rose sharply (EPSS 6.2% → 41% · rising (+35%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Check Point Security Gateway — exploitation likelihood rose sharply (EPSS 6.2% → 41% · rising (+35%)).
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

### CVE-2026-50751
**Check Point Security Gateway Improper Authentication Vulnerability**
- **Signals:** EPSS
- **Asset:** checkpoint gaia_os
- **CVSS max:** 9.3
- **NVD status:** Analyzed
- **NVD published:** 2026-06-08
- **NVD modified:** 2026-06-17
- **CWE:** CWE-287
- **Risk score:** 85
- **EPSS 6.2% (2026-06-15) → 41.2% (2026-06-17), Δ +34.9%**

> A logic flow weakness in Remote Access and Mobile Access certificate validation in deprecated IKEv1 key exchange allows an unauthenticated remote attacker to bypass user authentication and establish a remote access VPN connection without a valid user password.

### CVE-2016-2148
**busybox busybox Buffer Overflow**
- **Signals:** EPSS
- **Asset:** busybox busybox
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD published:** 2017-02-09
- **NVD modified:** 2026-06-16
- **CWE:** CWE-119
- **Risk score:** 86
- **EPSS 14.6% (2026-06-15) → 28.4% (2026-06-17), Δ +13.8%**

> Heap-based buffer overflow in the DHCP client (udhcpc) in BusyBox before 1.25.0 allows remote attackers to have unspecified impact via vectors involving OPTION_6RD parsing.

### CVE-2026-12569
**A critical remote code execution (RCE) vulnerability has been reported in PTC Windchill PDMlink and PTC FlexPLM.**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD published:** 2026-06-17
- **NVD modified:** 2026-06-18
- **CWE:** CWE-20
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-17)

> A critical remote code execution (RCE) vulnerability has been reported in PTC Windchill PDMlink and PTC FlexPLM. The vulnerability may be exploited through the deserialization of untrusted data.   *  This advisory also applies to all CPS versions
  *  The identified vulnerability…

### CVE-2026-2467
**Heap-based Buffer Overflow vulnerability in RTI Connext Professional (Core Libraries) allows Overflow Variables and Tags.This issue affec...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.2
- **NVD status:** Undergoing Analysis
- **NVD published:** 2026-06-17
- **NVD modified:** 2026-06-17
- **CWE:** CWE-122
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-17)

> Heap-based Buffer Overflow vulnerability in RTI Connext Professional (Core Libraries) allows Overflow Variables and Tags.This issue affects Connext Professional: from 7.4.0 before 7.7.0, from 7.0.0 before 7.3.1.3, from 6.1.0 before 6.1.*, from 6.0.0 before 6.0.*, from 5.3.0 befor…

### CVE-2026-3894
**Out-of-bounds Read vulnerability in RTI Connext Professional (Core Libraries) allows Overread Buffers.This issue affects Connext Professi...**
- **Signals:** CVSS
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.2
- **NVD status:** Undergoing Analysis
- **NVD published:** 2026-06-17
- **NVD modified:** 2026-06-17
- **CWE:** CWE-125
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-17)

> Out-of-bounds Read vulnerability in RTI Connext Professional (Core Libraries) allows Overread Buffers.This issue affects Connext Professional: from 7.4.0 before 7.7.0, from 7.0.0 before 7.3.1.3, from 6.1.0 before 6.1.*, from 6.0.0 before 6.0.*, from 5.3.0 before 5.3.*, from 5.0.0…

### CVE-2026-48768
**TypeBot is a chatbot builder tool.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD published:** 2026-06-17
- **NVD modified:** 2026-06-18
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-17)

> TypeBot is a chatbot builder tool. In versions 3.16.1 and earlier, POST /api/blocks/file-input/v3/generate-upload-url is unauthenticated and uses unsanitized fileName input to construct public/ S3 object keys, while issuing presigned PUT URLs that do not bind Content-Type. As a r…

### CVE-2026-48814
**Network-AI is a TypeScript/Node.js multi-agent orchestrator.**
- **Signals:** CVSS
- **CVSS max:** 9.1
- **NVD status:** Received
- **NVD published:** 2026-06-17
- **NVD modified:** 2026-06-18
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-17)

> Network-AI is a TypeScript/Node.js multi-agent orchestrator. In versions 5.7.1 and earlier, the MCP SSE server allows unauthenticated cross-origin MCP tool invocation due to an empty default secret. This issue was partially addressed by CVE-2026-46701 in version 5.4.5 by closing …

### CVE-2026-53805
**NVIDIA Spatial Intelligence Lab's (SIL) GEN3C contains an unauthenticated remote code execution vulnerability in the inference API server...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-17
- **NVD modified:** 2026-06-17
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-17)

> NVIDIA Spatial Intelligence Lab's (SIL) GEN3C contains an unauthenticated remote code execution vulnerability in the inference API server where the /request-inference and /seed-model endpoints deserialize raw HTTP request bodies using Python's pickle.loads() without authenticatio…

### CVE-2026-54387
**Tinyproxy through 1.11.3, fixed in commit ff45d3b, fails to reconcile conflicting Content-Length and Transfer-Encoding: chunked headers,...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD published:** 2026-06-17
- **NVD modified:** 2026-06-18
- **CWE:** CWE-444
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-17)

> Tinyproxy through 1.11.3, fixed in commit ff45d3b, fails to reconcile conflicting Content-Length and Transfer-Encoding: chunked headers, forwarding both verbatim to the backend while using Content-Length to determine how many request body bytes to consume. Remote attackers can de…

### CVE-2026-54388
**Tinyproxy through 1.11.3, fixed in commit 364cdb6, fails to reject requests containing multiple Content-Length headers with differing val...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD published:** 2026-06-17
- **NVD modified:** 2026-06-18
- **CWE:** CWE-444
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-17)

> Tinyproxy through 1.11.3, fixed in commit 364cdb6, fails to reject requests containing multiple Content-Length headers with differing values, forwarding all duplicate headers to the backend while using the first value to determine how many request body bytes to consume. Remote at…

### CVE-2026-55196
**Hermes WebUI before 0.51.409 contains an authentication bypass vulnerability in passkey registration endpoints that allows unauthenticate...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.1
- **NVD status:** Deferred
- **NVD published:** 2026-06-17
- **NVD modified:** 2026-06-17
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-06-17)

> Hermes WebUI before 0.51.409 contains an authentication bypass vulnerability in passkey registration endpoints that allows unauthenticated remote attackers to register arbitrary passkeys. When HERMES_WEBUI_PASSKEY=1 is enabled with no existing credentials, POST /api/auth/passkey/…

### CVE-2026-55200
**libssh2 through 1.11.1, fixed in commit 7acf3df contains an out-of-bounds write vulnerability in ssh2_transport_read() that fails to enfo...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.2
- **NVD status:** Received
- **NVD published:** 2026-06-17
- **NVD modified:** 2026-06-18
- **CWE:** CWE-680
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-06-17)

> libssh2 through 1.11.1, fixed in commit 7acf3df contains an out-of-bounds write vulnerability in ssh2_transport_read() that fails to enforce upper bounds on packet_length field. Remote attackers can send crafted SSH packets with excessively large packet_length values to corrupt h…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-17*
