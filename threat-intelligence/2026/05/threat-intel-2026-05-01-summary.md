# Daily Threat Intelligence — May 01, 2026

**Digest window (UTC):** 2026-05-01
**Generated:** 2026-06-02T07:03:54Z

## Threat brief

Linux Kernel added to CISA KEV — confirmed in-the-wild exploitation. · Exploitation likelihood rose sharply (EPSS 0.0% → 33% · rising (+33%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Linux Kernel added to CISA KEV — confirmed in-the-wild exploitation.
- Exploitation likelihood rose sharply (EPSS 0.0% → 33% · rising (+33%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 4 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **15** |


## CVEs

### CVE-2026-31431
**Linux Kernel Incorrect Resource Transfer Between Spheres Vulnerability**
- **Signals:** KEV
- **Asset:** linux linux_kernel
- **CVSS max:** 7.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-21T19:52:35.217
- **CWE:** CWE-669
- **Risk score:** 88
- **KEV:** added 2026-05-01

> In the Linux kernel, the following vulnerability has been resolved:

crypto: algif_aead - Revert to operating out-of-place

This mostly reverts commit 72548b093ee3 except for the copying of
the associated data.

There is no benefit in operating in-place in algif_aead since the
so…

### CVE-2026-1368
**EPSS dynamics**
- **Signals:** EPSS
- **CVSS max:** 7.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 82
- **EPSS 0.0% (2026-02-18) → 32.9% (2026-05-01), Δ +32.9%**

> The Video Conferencing with Zoom WordPress plugin before 4.6.6 contains an AJAX handler that has its nonce verification commented out, allowing unauthenticated attackers to generate valid Zoom SDK signatures for any meeting ID and retrieve the site's Zoom SDK key.

### CVE-2026-37541
**openvehicles open_vehicle_monitoring_system_firmware Buffer Overflow**
- **Signals:** CVSS
- **Asset:** openvehicles open_vehicle_monitoring_system_firmware
- **Attack:** Buffer Overflow
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-20T15:20:03.423
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-05-01)

> Buffer overflow vulnerability in Open Vehicle Monitoring System 3 (OVMS3) 3.3.005. In canformat_gvret.cpp, the length field in GVRET binary data is not properly validated, allowing remote attackers to cause a denial of service or possibly execute arbitrary code via crafted GVRET …

### CVE-2020-28351
**mitel shoretel_firmware XSS**
- **Signals:** EPSS
- **Asset:** mitel shoretel_firmware
- **Attack:** XSS
- **CVSS max:** 6.1
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:22:39.317
- **CWE:** CWE-79
- **Risk score:** 80
- **EPSS 9.3% (2026-03-04) → 25.7% (2026-05-01), Δ +16.4%**

> The conferencing component on Mitel ShoreTel 19.46.1802.0 devices could allow an unauthenticated attacker to conduct a reflected cross-site scripting (XSS) attack (via the PATH_INFO to index.php) due to insufficient validation for the time_zone object in the HOME_MEETING& page.

### CVE-2020-28976
**canto canto SSRF**
- **Signals:** EPSS
- **Asset:** canto canto
- **Attack:** SSRF
- **CVSS max:** 5.3
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T05:23:25.890
- **CWE:** CWE-918
- **Risk score:** 79
- **EPSS 25.8% (2025-11-21) → 42.2% (2026-05-01), Δ +16.4%**

> The Canto plugin 1.3.0 for WordPress contains a blind SSRF vulnerability. It allows an unauthenticated attacker can make a request to any internal and external server via /includes/lib/detail.php?subdomain=SSRF.

### CVE-2023-29209
**xwiki xwiki**
- **Signals:** EPSS
- **Asset:** xwiki xwiki
- **CVSS max:** 9.9
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T07:56:43.173
- **CWE:** CWE-95
- **CWE:** CWE-94
- **Risk score:** 83
- **EPSS 8.5% (2026-04-26) → 18.9% (2026-05-01), Δ +10.4%**

> XWiki Commons are technical libraries common to several other top level XWiki projects. Any user with view rights on commonly accessible documents including the legacy notification activity macro can execute arbitrary Groovy, Python or Velocity code in XWiki leading to full acces…

### CVE-2026-37531
**linuxfoundation automotive_grade_linux Directory Traversal**
- **Signals:** CVSS
- **Asset:** linuxfoundation automotive_grade_linux
- **Attack:** Directory Traversal
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-18T17:12:36.573
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-01)

> AGL app-framework-main thru 17.1.12 contains a Zip Slip path traversal vulnerability (CWE-22) combined with a TOCTOU race condition (CWE-367) in the widget installation flow. The is_valid_filename function in wgtpkg-zip.c validates ZIP entry names but does not check for dot notat…

### CVE-2026-37534
**Integer underflow vulnerability in Open-SAE-J1939 thru commit b6caf884df46435e539b1ecbf92b6c29b345bdfe (2025-11-30) in SAE_J1939_Read_Tra...**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Awaiting Analysis
- **NVD modified:** 2026-05-07T15:15:06.770
- **CWE:** CWE-191
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-01)

> Integer underflow vulnerability in Open-SAE-J1939 thru commit b6caf884df46435e539b1ecbf92b6c29b345bdfe (2025-11-30) in SAE_J1939_Read_Transport_Protocol_Data_Transfer,allows attackers to write to arbitrary memory via crafted sequence number from the CAN frame.

### CVE-2026-37539
**Buffer overflow vulnerability in cannelloni v2.0.0 in CAN frame parsing in parser.cpp in function parseCANFrame, and decoder.cpp in funct...**
- **Signals:** CVSS
- **Attack:** Buffer Overflow
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T20:24:04.853
- **CWE:** CWE-121
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-01)

> Buffer overflow vulnerability in cannelloni v2.0.0 in CAN frame parsing in parser.cpp in function parseCANFrame, and decoder.cpp in function decodeFrame allowing remote attackers to cause a denial of service (crash) or possibly execute arbitrary code via crafted CAN FD frames.

### CVE-2026-42472
**Unsafe deserialization vulnerability in MixPHP Framework 2.x thru 2.2.17.**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T19:39:58.510
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-01)

> Unsafe deserialization vulnerability in MixPHP Framework 2.x thru 2.2.17. The session and cache handlers use unserialize() on data from Redis in the RedisHandler object.

### CVE-2026-42473
**Unsafe deserialization vulnerability in MixPHP Framework 2.x thru 2.2.17.**
- **Signals:** CVSS
- **Attack:** Deserialization
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-05-05T19:39:58.510
- **CWE:** CWE-502
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-01)

> Unsafe deserialization vulnerability in MixPHP Framework 2.x thru 2.2.17. The session and cache handlers use unserialize() on data from the filesystem in the FileHandler object.

### CVE-2026-43011
**linux linux_kernel**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-07T20:26:58.903
- **CWE:** CWE-415
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-01)

> In the Linux kernel, the following vulnerability has been resolved:

net/x25: Fix potential double free of skb

When alloc_skb fails in x25_queue_rx_frame it calls kfree_skb(skb) at
line 48 and returns 1 (error).
This error propagates back through the call chain:

x25_queue_rx_fr…

### CVE-2026-43037
**linux linux_kernel**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-04T18:26:53.743
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-01)

> In the Linux kernel, the following vulnerability has been resolved:

ip6_tunnel: clear skb2->cb[] in ip4ip6_err()

Oskar Kjos reported the following problem.

ip4ip6_err() calls icmp_send() on a cloned skb whose cb[] was written
by the IPv6 receive path as struct inet6_skb_parm. …

### CVE-2026-43038
**linux linux_kernel**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T18:47:20.317
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-01)

> In the Linux kernel, the following vulnerability has been resolved:

ipv6: icmp: clear skb2->cb[] in ip6_err_gen_icmpv6_unreach()

Sashiko AI-review observed:

  In ip6_err_gen_icmpv6_unreach(), the skb is an outer IPv4 ICMP error packet
  where its cb contains an IPv4 inet_skb_p…

### CVE-2026-43039
**linux linux_kernel**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-08T18:48:10.430
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-05-01)

> In the Linux kernel, the following vulnerability has been resolved:

net: ti: icssg-prueth: fix missing data copy and wrong recycle in ZC RX dispatch

emac_dispatch_skb_zc() allocates a new skb via napi_alloc_skb() but
never copies the packet data from the XDP buffer into it. The…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-05-01*
