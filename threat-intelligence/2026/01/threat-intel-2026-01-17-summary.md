# Daily Threat Intelligence — January 17, 2026

**Digest window (UTC):** 2026-01-17
**Generated:** 2026-06-02T07:34:12Z

## Threat brief

Sourcefabric Rpi-jukebox-rfid: public exploit or PoC linked (Command Injection) · WordPress plugin RCE/exploit activity: 2 CVEs flagged today. · Tricerasoft Swift Ultralite — exploitation likelihood rose sharply (EPSS 5.8% → 19% · rising (+14%)).

## Executive summary

- Sourcefabric Rpi-jukebox-rfid: public exploit or PoC linked (Command Injection)
- WordPress plugin RCE/exploit activity: 2 CVEs flagged today.
- Tricerasoft Swift Ultralite — exploitation likelihood rose sharply (EPSS 5.8% → 19% · rising (+14%)).

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 3 |
| EPSS rise | 2 |
| CVSS critical disclosure | 2 |
| Patch status change | 0 |
| **Total** | **7** |


## CVEs

### CVE-2025-10327
**sourcefabric rpi-jukebox-rfid Command Injection**
- **Signals:** EXP
- **Asset:** sourcefabric rpi-jukebox-rfid
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2026-04-29T01:00:01.613
- **CWE:** CWE-77
- **CWE:** CWE-78
- **Risk score:** 78
- **EXP:** ref published 2026-01-17

> A weakness has been identified in MiczFlor RPi-Jukebox-RFID up to 2.8.0. Affected by this vulnerability is an unknown functionality of the file /htdocs/api/playlist/shuffle.php. Executing manipulation of the argument playlist can lead to os command injection. The attack can be la…

### CVE-2025-57174
**An issue was discovered in Siklu Communications Etherhaul 8010TX and 1200FX devices, Firmware 7.4.0 through 10.7.3 and possibly other pre...**
- **Signals:** EXP
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-321
- **Risk score:** 78
- **EXP:** ref published 2026-01-17

> An issue was discovered in Siklu Communications Etherhaul 8010TX and 1200FX devices, Firmware 7.4.0 through 10.7.3 and possibly other previous versions. The rfpiped service listening on TCP port 555 which uses static AES encryption keys hardcoded in the binary. These keys are ide…

### CVE-2009-3253
**tricerasoft swift_ultralite Buffer Overflow**
- **Signals:** EPSS
- **Asset:** tricerasoft swift_ultralite
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 5.8% (2025-03-30) → 19.5% (2026-01-17), Δ +13.7%**

> Stack-based buffer overflow in TriceraSoft Swift Ultralite 1.032 allows remote attackers to cause a denial of service (crash) or execute arbitrary code via a long string in a .M3U playlist file.

### CVE-2009-3254
**ultimatevideosite ultimate_player Buffer Overflow**
- **Signals:** EPSS
- **Asset:** ultimatevideosite ultimate_player
- **Attack:** Buffer Overflow
- **CVSS max:** 9.3
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-119
- **Risk score:** 85
- **EPSS 5.1% (2025-03-30) → 18.7% (2026-01-17), Δ +13.6%**

> Multiple stack-based buffer overflows in Ultimate Player 1.56 beta allow remote attackers to execute arbitrary code via a long string in a (1) .m3u or (2) .upl playlist file.

### CVE-2025-10484
**The Registration & Login with Mobile Phone Number for WooCommerce plugin for WordPress is vulnerable to Authentication Bypass in all vers...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-288
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-17)

> The Registration & Login with Mobile Phone Number for WooCommerce plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 1.3.1. This is due to the plugin not properly verifying a users identity prior to authenticating them via the fma_lw…

### CVE-2025-15403
**The RegistrationMagic plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 6.0.7.1.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-269
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-01-17)

> The RegistrationMagic plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 6.0.7.1. This is due to the 'add_menu' function is accessible via the 'rm_user_exists' AJAX action and allows arbitrary updates to the 'admin_order' setting. Thi…

### CVE-2025-57176
**On Ceragon Networks / Siklu Communication EtherHaul and MultiHaul Series microwave antennas before 2026-03-10, the rfpiped service on TCP...**
- **Signals:** EXP
- **CVSS max:** 6.5
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-434
- **CWE:** CWE-434
- **Risk score:** 78
- **EXP:** ref published 2026-01-17

> On Ceragon Networks / Siklu Communication EtherHaul and MultiHaul Series microwave antennas before 2026-03-10, the rfpiped service on TCP port 555 allows unauthenticated file uploads to any writable location on the device. File upload packets use weak encryption (metadata only) w…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-01-17*
