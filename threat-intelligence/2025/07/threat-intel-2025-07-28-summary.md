# Daily Threat Intelligence — July 28, 2025

**Digest window (UTC):** 2025-07-28
**Generated:** 2026-06-02T07:33:08Z

## Threat brief

Cisco Identity Services Engine: 2 CVEs added to CISA KEV today. · Xwiki: public exploit or PoC linked (SQL injection) · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Cisco Identity Services Engine: 2 CVEs added to CISA KEV today.
- Xwiki: public exploit or PoC linked (SQL injection)
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 3 |
| EXP (exploit / PoC) | 5 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **18** |


## CVEs

### CVE-2023-2533
**PaperCut NG/MF Cross-Site Request Forgery (CSRF) Vulnerability**
- **Signals:** KEV
- **Asset:** papercut papercut_mf
- **Attack:** CSRF
- **CVSS max:** 8.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-02-26T15:03:53.690
- **CWE:** CWE-352
- **CWE:** CWE-352
- **Risk score:** 88
- **KEV:** added 2025-07-28

> A Cross-Site Request Forgery (CSRF) vulnerability has been identified in
PaperCut NG/MF, which, under specific conditions, could potentially enable
an attacker to alter security settings or execute arbitrary code. This could
be exploited if the target is an admin with a current l…

### CVE-2024-0737
**xlightftpd xlight_ftp_server DoS**
- **Signals:** EXP
- **Asset:** xlightftpd xlight_ftp_server
- **Attack:** DoS
- **CVSS max:** 7.5
- **NVD status:** Modified
- **NVD modified:** 2024-11-21T08:47:15.143
- **CWE:** CWE-404
- **Risk score:** 78
- **EXP:** ref published 2025-07-28

> A vulnerability classified as problematic was found in Xlightftpd Xlight FTP Server 1.1. This vulnerability affects unknown code of the component Login. The manipulation of the argument user leads to denial of service. The attack can be initiated remotely. The exploit has been di…

### CVE-2025-54419
**A SAML library not dependent on any frameworks that runs in Node.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-28)

> A SAML library not dependent on any frameworks that runs in Node. In version 5.0.1, Node-SAML loads the assertion from the (unsigned) original response document. This is different than the parts that are verified when checking signature. This allows an attacker to modify authenti…

### CVE-2024-20767
**Adobe ColdFusion Improper Access Control Vulnerability**
- **Signals:** EXP
- **Asset:** adobe coldfusion
- **CVSS max:** 7.4
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-23T11:13:22.983
- **CWE:** CWE-284
- **Risk score:** 78
- **EXP:** ref published 2025-07-28

> ColdFusion versions 2023.6, 2021.12 and earlier are affected by an Improper Access Control vulnerability that could result in arbitrary file system read. An attacker could leverage this vulnerability to access or modify restricted files. Exploitation of this issue does not requir…

### CVE-2025-20281
**Cisco Identity Services Engine Injection Vulnerability**
- **Signals:** KEV
- **Asset:** cisco identity_services_engine
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T13:59:08.700
- **CWE:** CWE-74
- **Risk score:** 88
- **KEV:** added 2025-07-28

> A vulnerability in a specific API of Cisco ISE and Cisco ISE-PIC could allow an unauthenticated, remote attacker to execute arbitrary code on the underlying operating system as root. The attacker does not require any valid credentials to exploit this vulnerability.

This vulner…

### CVE-2025-20337
**Cisco Identity Services Engine Injection Vulnerability**
- **Signals:** KEV
- **Asset:** cisco identity_services_engine
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-28T13:58:55.447
- **CWE:** CWE-74
- **Risk score:** 88
- **KEV:** added 2025-07-28

> A vulnerability in a specific API of Cisco ISE and Cisco ISE-PIC could allow an unauthenticated, remote attacker to execute arbitrary code on the underlying operating system as root. The attacker does not require any valid credentials to exploit this vulnerability.

This vulner…

### CVE-2025-30125
**An issue was discovered on Marbella KR8s Dashcam FF 2.0.8 devices.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-798
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-28)

> An issue was discovered on Marbella KR8s Dashcam FF 2.0.8 devices. All dashcams were shipped with the same default credentials of 12345678, which creates an insecure-by-default condition. For users who change their passwords, it's limited to 8 characters. These short passwords ca…

### CVE-2025-30133
**iroadau fx2_firmware**
- **Signals:** CVSS
- **Asset:** iroadau fx2_firmware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-11-06T20:07:15.797
- **CWE:** CWE-284
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-28)

> An issue was discovered on IROAD Dashcam FX2 devices. Bypass of Device Pairing/Registration can occur. It requires device registration via the "IROAD X View" app for authentication, but its HTTP server lacks this restriction. Once connected to the dashcam's Wi-Fi network via the …

### CVE-2025-32429
**xwiki xwiki SQL injection**
- **Signals:** EXP
- **Asset:** xwiki xwiki
- **Attack:** SQL injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-09-03T17:43:28.937
- **CWE:** CWE-89
- **Risk score:** 78
- **EXP:** ref published 2025-07-28

> XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. In versions 9.4-rc-1 through 16.10.5 and 17.0.0-rc-1 through 17.2.2, it's possible for anyone to inject SQL using the parameter sort of the getdeleteddocuments.vm. It's inject…

### CVE-2025-50481
**jupo mezzanine XSS**
- **Signals:** EXP
- **Asset:** jupo mezzanine
- **Attack:** XSS
- **CVSS max:** 4.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-28T16:59:28.710
- **CWE:** CWE-79
- **Risk score:** 78
- **EXP:** ref published 2025-07-28

> A cross-site scripting (XSS) vulnerability in the component /blog/blogpost/add of Mezzanine CMS v6.1.0 allows attackers to execute arbitrary web scripts or HTML via injecting a crafted payload into a blog post.

### CVE-2025-53695
**OS Command Injection in iSTAR Ultra products web application allows an authenticated attacker to gain even more privileged access ('root'...**
- **Signals:** CVSS
- **Attack:** Command Injection
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-28)

> OS Command Injection in iSTAR Ultra products web application allows an authenticated attacker to gain even more privileged access ('root' user) to the device firmware.

### CVE-2025-53696
**iSTAR Ultra performs a firmware verification on boot, however the verification does not inspect certain portions of the firmware.**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-494
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-28)

> iSTAR Ultra performs a firmware verification on boot, however the verification does not inspect certain portions of the firmware. These firmware parts may contain malicious code. Tested up to firmware 6.9.2, later firmwares are also possibly affected.

### CVE-2025-54298
**A stored XSS vulnerability in CommentBox component 1.0.0-1.1.0 for Joomla was discovered.**
- **Signals:** CVSS
- **Attack:** cross-site scripting
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-28)

> A stored XSS vulnerability in CommentBox component 1.0.0-1.1.0 for Joomla was discovered.

### CVE-2025-54299
**A stored XSS vulnerability in No Boss Testimonials component 1.0.0-3.0.0 and 4.0.0-4.0.2 for Joomla was discovered.**
- **Signals:** CVSS
- **Attack:** cross-site scripting
- **CVSS max:** 9.4
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-79
- **Risk score:** 66
- **CVSS critical:** 9.4 (disclosed 2025-07-28)

> A stored XSS vulnerability in No Boss Testimonials component 1.0.0-3.0.0 and 4.0.0-4.0.2 for Joomla was discovered.

### CVE-2025-54418
**codeigniter codeigniter Command Injection**
- **Signals:** CVSS
- **Asset:** codeigniter codeigniter
- **Attack:** Command Injection
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-08-05T15:46:02.750
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-28)

> CodeIgniter is a PHP full-stack web framework. A command injection vulnerability present in versions prior to 4.6.2 affects applications that use the ImageMagick handler for image processing (`imagick` as the image library) and either allow file uploads with user-controlled filen…

### CVE-2025-54426
**Polkadot Frontier is an Ethereum and EVM compatibility layer for Polkadot and Substrate.**
- **Signals:** CVSS
- **CVSS max:** 9.9
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-327
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2025-07-28)

> Polkadot Frontier is an Ethereum and EVM compatibility layer for Polkadot and Substrate. In versions prior to commit 36f70d1, the Curve25519Add and Curve25519ScalarMul precompiles incorrectly handle invalid Ristretto point representations. Instead of returning an error, they sile…

### CVE-2025-54428
**RevelaCode is an AI-powered faith-tech project that decodes biblical verses, prophecies and global events into accessible language.**
- **Signals:** CVSS
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-522
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-28)

> RevelaCode is an AI-powered faith-tech project that decodes biblical verses, prophecies and global events into accessible language. In versions below 1.0.1, a valid MongoDB Atlas URI with embedded username and password was accidentally committed to the public repository. This cou…

### CVE-2025-6018
**suse pam-config Privilege Escalation**
- **Signals:** EXP
- **Asset:** suse pam-config
- **Attack:** Privilege Escalation
- **CVSS max:** 7.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T22:16:42.873
- **CWE:** CWE-863
- **Risk score:** 78
- **EXP:** ref published 2025-07-28

> A Local Privilege Escalation (LPE) vulnerability has been discovered in pam-config within Linux Pluggable Authentication Modules (PAM). This flaw allows an unprivileged local attacker (for example, a user logged in via SSH) to obtain the elevated privileges normally reserved for …

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-28*
