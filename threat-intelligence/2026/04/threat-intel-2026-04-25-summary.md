# Daily Threat Intelligence — April 25, 2026

**Digest window (UTC):** 2026-04-25
**Generated:** 2026-06-02T07:35:00Z

## Threat brief

Microsoft Windows Server 2003 — exploitation likelihood rose sharply (EPSS 58% → 70% · rising (+12%)).

## Executive summary

- Microsoft Windows Server 2003 — exploitation likelihood rose sharply (EPSS 58% → 70% · rising (+12%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **3** |


## CVEs

### CVE-2017-0176
**microsoft windows_server_2003 Buffer Overflow**
- **Signals:** EPSS
- **Asset:** microsoft windows_server_2003
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-05-13T00:24:29.033
- **CWE:** CWE-120
- **Risk score:** 83
- **EPSS 57.8% (2026-04-24) → 70.2% (2026-04-25), Δ +12.3%**

> A buffer overflow in Smart Card authentication code in gpkcsp.dll in Microsoft Windows XP through SP3 and Server 2003 through SP2 allows a remote attacker to execute arbitrary code on the target computer, provided that the computer is joined in a Windows domain and has Remote Des…

### CVE-2026-31685
**linux linux_kernel**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2026-06-01T17:16:55.610
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2026-04-25)

> In the Linux kernel, the following vulnerability has been resolved:

netfilter: ip6t_eui64: reject invalid MAC header for all packets

`eui64_mt6()` derives a modified EUI-64 from the Ethernet source address
and compares it with the low 64 bits of the IPv6 source address.

The ex…

### CVE-2026-31682
**linux linux_kernel**
- **Signals:** CVSS
- **Asset:** linux linux_kernel
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-05-06T21:17:15.287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-04-25)

> In the Linux kernel, the following vulnerability has been resolved:

bridge: br_nd_send: linearize skb before parsing ND options

br_nd_send() parses neighbour discovery options from ns->opt[] and
assumes that these options are in the linear part of request.

Its callers only gua…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-04-25*
