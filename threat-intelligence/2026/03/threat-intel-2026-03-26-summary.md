# Daily Threat Intelligence — March 26, 2026

**Digest window (UTC):** 2026-03-26
**Generated:** 2026-06-02T07:34:45Z

## Threat brief

Aquasecurity Trivy added to CISA KEV — confirmed in-the-wild exploitation. · Darkwet Webcam Xp — exploitation likelihood rose sharply (EPSS 22% → 35% · rising (+13%)). · 10 new critical disclosures — review patch status on exposed services.

## Executive summary

- Aquasecurity Trivy added to CISA KEV — confirmed in-the-wild exploitation.
- Darkwet Webcam Xp — exploitation likelihood rose sharply (EPSS 22% → 35% · rising (+13%)).
- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 1 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 1 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **12** |


## CVEs

### CVE-2026-33634
**Aquasecurity Trivy Embedded Malicious Code Vulnerability**
- **Signals:** KEV
- **Asset:** aquasec setup-trivy
- **CVSS max:** 9.4
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T18:50:38.270
- **CWE:** CWE-506
- **Risk score:** 88
- **KEV:** added 2026-03-26

> Trivy is a security scanner. On March 19, 2026, a threat actor used compromised credentials to publish a malicious Trivy v0.69.4 release, force-push 76 of 77 version tags in `aquasecurity/trivy-action` to credential-stealing malware, and replace all 7 tags in `aquasecurity/setup-…

### CVE-2008-5674
**darkwet webcam_xp DoS**
- **Signals:** EPSS
- **Asset:** darkwet webcam_xp
- **Attack:** DoS
- **CVSS max:** 9.4
- **NVD status:** Modified
- **NVD modified:** 2026-04-23T00:35:47.467
- **CWE:** CWE-20
- **Risk score:** 85
- **EPSS 22.1% (2026-02-07) → 35.2% (2026-03-26), Δ +13.1%**

> Multiple array index errors in the HTTP server in Darkwet Network webcamXP 3.72.440.0 and earlier and beta 4.05.280 and earlier allow remote attackers to cause a denial of service (device crash) and read portions of memory via (1) an invalid camnum parameter to the pocketpc compo…

### CVE-2026-33494
**ory oathkeeper Path Traversal**
- **Signals:** CVSS
- **Asset:** ory oathkeeper
- **Attack:** Path Traversal
- **CVSS max:** 10.0
- **NVD status:** Analyzed
- **NVD modified:** 2026-04-07T21:15:14.387
- **CWE:** CWE-23
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-03-26)

> ORY Oathkeeper is an Identity & Access Proxy (IAP) and Access Control Decision API that authorizes HTTP requests based on sets of Access Rules. Versions prior to 26.2.0 are vulnerable to an authorization bypass via HTTP path traversal. An attacker can craft a URL containing path …

### CVE-2026-30457
**thedaylightstudio dwoo**
- **Signals:** CVSS
- **Asset:** thedaylightstudio dwoo
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T14:11:06.703
- **CWE:** CWE-94
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-26)

> An issue in the /parser/dwoo component of Daylight Studio FuelCMS v1.5.2 allows attackers to execute arbitrary code via crafted PHP code.

### CVE-2026-30458
**thedaylightstudio fuel_cms**
- **Signals:** CVSS
- **Asset:** thedaylightstudio fuel_cms
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T14:11:49.907
- **CWE:** CWE-620
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-26)

> An issue in Daylight Studio FuelCMS v1.5.2 allows attackers to exfiltrate users' password reset tokens via a mail splitting attack.

### CVE-2026-33152
**tandoor recipes**
- **Signals:** CVSS
- **Asset:** tandoor recipes
- **CVSS max:** 9.1
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T19:18:18.253
- **CWE:** CWE-307
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-26)

> Tandoor Recipes is an application for managing recipes, planning meals, and building shopping lists. In versions prior to 2.6.0, Tandoor Recipes configures Django REST Framework with BasicAuthentication as one of the default authentication backends. The AllAuth rate limiting conf…

### CVE-2026-33396
**hackerbay oneuptime privilege escalation**
- **Signals:** CVSS
- **Asset:** hackerbay oneuptime
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-26T20:40:52.840
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-26)

> OneUptime is an open-source monitoring and observability platform. Prior to version 10.0.35, a low-privileged authenticated user (ProjectMember) can achieve remote command execution on the Probe container/host by abusing Synthetic Monitor Playwright script execution. Synthetic mo…

### CVE-2026-33640
**getoutline outline**
- **Signals:** CVSS
- **Asset:** getoutline outline
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-31T01:42:34.940
- **CWE:** CWE-307
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2026-03-26)

> Outline is a service that allows for collaborative documentation. Outline implements an Email OTP login flow for users not associated with an Identity Provider. Starting in version 0.86.0 and prior to version 1.6.0, Outline does not invalidate OTP codes based on amount or frequen…

### CVE-2026-33669
**b3log siyuan**
- **Signals:** CVSS
- **Asset:** b3log siyuan
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T17:03:33.350
- **CWE:** CWE-125
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-26)

> SiYuan is a personal knowledge management system. Prior to version 3.6.2, document IDs were retrieved via the /api/file/readDir interface, and then the /api/block/getChildBlocks interface was used to view the content of all documents. Version 3.6.2 patches the issue.

### CVE-2026-33670
**b3log siyuan**
- **Signals:** CVSS
- **Asset:** b3log siyuan
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T17:02:13.797
- **CWE:** CWE-22
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-03-26)

> SiYuan is a personal knowledge management system. Prior to version 3.6.2, the /api/file/readDir interface was used to traverse and retrieve the file names of all documents under a notebook. Version 3.6.2 patches the issue.

### CVE-2026-33897
**linuxcontainers incus**
- **Signals:** CVSS
- **Asset:** linuxcontainers incus
- **CVSS max:** 9.9
- **NVD status:** Analyzed
- **NVD modified:** 2026-03-30T18:55:33.887
- **CWE:** CWE-1336
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-03-26)

> Incus is a system container and virtual machine manager. Prior to version 6.23.0, instance template files can be used to cause arbitrary read or writes as root on the host server. Incus allows for pongo2 templates within instances which can be used at various times in the instanc…

### CVE-2026-4809
**plank/laravel-mediable through version 6.4.0 can allow upload of a dangerous file type when an application using the package accepts or p...**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-05-19T15:50:41.340
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-03-26)

> plank/laravel-mediable through version 6.4.0 can allow upload of a dangerous file type when an application using the package accepts or prefers a client-supplied MIME type during file upload handling. In that configuration, a remote attacker can submit a file containing executabl…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-03-26*
