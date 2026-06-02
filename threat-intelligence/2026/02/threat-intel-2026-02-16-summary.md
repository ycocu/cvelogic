# Daily Threat Intelligence — February 16, 2026

**Digest window (UTC):** 2026-02-16
**Generated:** 2026-06-02T07:34:26Z

## Threat brief

4 new critical disclosures — review patch status on exposed services.

## Executive summary

- 4 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 4 |
| Patch status change | 0 |
| **Total** | **4** |


## CVEs

### CVE-2026-2577
**The WhatsApp bridge component in Nanobot binds the WebSocket server to all network interfaces (0.0.0.0) on port 3001 by default and does...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-306
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-02-16)

> The WhatsApp bridge component in Nanobot binds the WebSocket server to all network interfaces (0.0.0.0) on port 3001 by default and does not require authentication for incoming connections. An unauthenticated remote attacker with network access to the bridge can connect to the We…

### CVE-2025-15578
**teejay maypole**
- **Signals:** CVSS
- **Asset:** teejay maypole
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T15:07:31.793
- **CWE:** CWE-338
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-16)

> Maypole versions from 2.10 through 2.13 for Perl generates session ids insecurely. The session id is seeded with the system time (which is available from HTTP response headers), a call to the built-in rand() function, and the PID.

### CVE-2026-2439
**bva concierge::sessions**
- **Signals:** CVSS
- **Asset:** bva concierge\
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-10T18:12:46.927
- **CWE:** CWE-338
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-02-16)

> Concierge::Sessions versions from 0.8.1 before 0.8.5 for Perl generate insecure session ids. The generate_session_id function in Concierge::Sessions::Base defaults to using the uuidgen command to generate a UUID, with a fallback to using Perl's built-in rand function. Neither of …

### CVE-2026-2564
**A security flaw has been discovered in Intelbras VIP 3260 Z IA 2.840.00IB005.0.T.**
- **Signals:** CVSS
- **CVSS max:** 9.2
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-640
- **Risk score:** 66
- **CVSS critical:** 9.2 (disclosed 2026-02-16)

> A security flaw has been discovered in Intelbras VIP 3260 Z IA 2.840.00IB005.0.T. Affected by this vulnerability is an unknown functionality of the file /OutsideCmd. The manipulation results in weak password recovery. It is possible to launch the attack remotely. Attacks of this …

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-02-16*
