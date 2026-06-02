# Daily Threat Intelligence — March 08, 2026

**Digest window (UTC):** 2026-03-08
**Generated:** 2026-06-02T07:34:36Z

## Threat brief

Apache Http Server — exploitation likelihood rose sharply (EPSS 20% → 42% · rising (+22%)).

## Executive summary

- Apache Http Server — exploitation likelihood rose sharply (EPSS 20% → 42% · rising (+22%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 1 |
| Patch status change | 0 |
| **Total** | **2** |


## CVEs

### CVE-2014-3583
**apache http_server DoS**
- **Signals:** EPSS
- **Asset:** apple mac_os_x
- **Attack:** DoS
- **CVSS max:** 5.0
- **NVD status:** Modified
- **NVD modified:** 2026-05-06T22:30:45.220
- **CWE:** CWE-119
- **Risk score:** 78
- **EPSS 19.8% (2026-03-04) → 41.8% (2026-03-08), Δ +22.0%**

> The handle_headers function in mod_proxy_fcgi.c in the mod_proxy_fcgi module in the Apache HTTP Server 2.4.10 allows remote FastCGI servers to cause a denial of service (buffer over-read and daemon crash) via long response headers.

### CVE-2026-30909
**timlegge crypt::nacl::sodium**
- **Signals:** CVSS
- **Asset:** timlegge crypt\
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-18T13:02:17.657
- **CWE:** CWE-190
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-08)

> Crypt::NaCl::Sodium versions through 2.002 for Perl has potential integer overflows.

bin2hex, encrypt, aes256gcm_encrypt_afternm and seal functions do not check that output size will be less than SIZE_MAX, which could lead to integer wraparound causing an undersized output buffe…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-08*
