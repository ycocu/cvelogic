# Daily Threat Intelligence — December 04, 2025

**Digest window (UTC):** 2025-12-04
**Generated:** 2026-06-02T07:33:54Z

## Threat brief

Brim-project Brim — exploitation likelihood rose sharply (EPSS 5.0% → 29% · rising (+24%)). · 9 new critical disclosures — review patch status on exposed services.

## Executive summary

- Brim-project Brim — exploitation likelihood rose sharply (EPSS 5.0% → 29% · rising (+24%)).
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

### CVE-2008-2645
**brim-project brim**
- **Signals:** EPSS
- **Asset:** brim-project brim
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-94
- **Risk score:** 82
- **EPSS 5.0% (2025-11-04) → 28.7% (2025-12-04), Δ +23.7%**

> Multiple PHP remote file inclusion vulnerabilities in Brim (formerly Booby) 1.0.1 allow remote attackers to execute arbitrary PHP code via a URL in the renderer parameter to template.tpl.php in (1) barrel/, (2) barry/, (3) mylook/, (4) oerdec/, (5) penguin/, (6) sidebar/, (7) sla…

### CVE-2025-29269
**allnet all-rut22gw_firmware Command Injection**
- **Signals:** CVSS
- **Asset:** allnet all-rut22gw_firmware
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T15:57:03.583
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-04)

> ALLNET ALL-RUT22GW v3.3.8 was discovered to contain an OS command injection vulnerability via the command parameter in the popen.cgi endpoint.

### CVE-2025-53963
**thermofisher ion_torrent_onetouch_2_firmware Code Execution**
- **Signals:** CVSS
- **Asset:** thermofisher ion_torrent_onetouch_2_firmware
- **Attack:** Code Execution
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T21:01:55.370
- **CWE:** CWE-521
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-04)

> An issue was discovered on Thermo Fisher Ion Torrent OneTouch 2 INS1005527 devices. They run an SSH server accessible over the default port 22. The root account has a weak default password of ionadmin, and a password change policy for the root account is not enforced. Thus, an at…

### CVE-2024-45538
**synology diskstation_manager CSRF**
- **Signals:** CVSS
- **Asset:** synology diskstation_manager
- **Attack:** CSRF
- **CVSS max:** 9.6
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-05T21:44:21.507
- **CWE:** CWE-352
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2025-12-04)

> Cross-Site Request Forgery (CSRF) vulnerability in WebAPI Framework in Synology DiskStation Manager (DSM) before 7.2.1-69057-2 and 7.2.2-72806 and Synology Unified Controller (DSMUC) before 3.1.4-23079 allows remote attackers to execute arbitrary code via unspecified vectors.

### CVE-2025-29268
**allnet all-rut22gw_firmware**
- **Signals:** CVSS
- **Asset:** allnet all-rut22gw_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T15:56:56.927
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-04)

> ALLNET ALL-RUT22GW v3.3.8 was discovered to store hardcoded credentials in the libicos.so library.

### CVE-2025-54303
**thermofisher torrent_suite_software**
- **Signals:** CVSS
- **Asset:** thermofisher torrent_suite_software
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T21:00:13.787
- **CWE:** CWE-1392
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-04)

> The Thermo Fisher Torrent Suite Django application 5.18.1 has weak default credentials, which are stored as fixtures for the Django ORM API. The ionadmin user account can be used to authenticate to default deployments with the password ionadmin. The user guide recommends changing…

### CVE-2025-54304
**thermofisher ion_torrent_onetouch_2_firmware**
- **Signals:** CVSS
- **Asset:** thermofisher ion_torrent_onetouch_2_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T18:54:15.217
- **CWE:** CWE-200
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-04)

> An issue was discovered on Thermo Fisher Ion Torrent OneTouch 2 INS1005527 devices. When they are powered on, an X11 display server is started. The display server listens on all network interfaces and is accessible over port 6000. The X11 access control list, by default, allows c…

### CVE-2025-63362
**waveshare rs232\/485_to_wifi_eth_\(b\)_firmware**
- **Signals:** CVSS
- **Asset:** waveshare rs232\/485_to_wifi_eth_\(b\)_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-15T15:37:07.627
- **CWE:** CWE-620
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-12-04)

> Waveshare RS232/485 TO WIFI ETH (B) Serial to Ethernet/Wi-Fi Gateway Firmware V3.1.1.0: HW 4.3.2.1: Webpage V7.04T.07.002880.0301 allows attackers to set the Administrator password and username as blank values, allowing attackers to bypass authentication.

### CVE-2025-65346
**alexusmai laravel_file_manager Directory Traversal**
- **Signals:** CVSS
- **Asset:** alexusmai laravel_file_manager
- **Attack:** Directory Traversal
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2025-12-16T18:04:39.370
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-12-04)

> alexusmai laravel-file-manager 3.3.1 and below is vulnerable to Directory Traversal. The unzip/extraction functionality improperly allows archive contents to be written to arbitrary locations on the filesystem due to insufficient validation of extraction paths.

### CVE-2025-66571
**UNA CMS versions 9.0.0-RC1 - 14.0.0-RC4 contain a PHP object injection vulnerability in BxBaseMenuSetAclLevel.php where the profile_id PO...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-502
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-12-04)

> UNA CMS versions 9.0.0-RC1 - 14.0.0-RC4 contain a PHP object injection vulnerability in BxBaseMenuSetAclLevel.php where the profile_id POST parameter is passed to PHP unserialize() without proper handling, allowing remote, unauthenticated attackers to inject arbitrary PHP objects…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-12-04*
