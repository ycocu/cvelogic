# Daily Threat Intelligence — July 15, 2025

**Digest window (UTC):** 2025-07-15
**Generated:** 2026-06-02T07:33:03Z

## Threat brief

10 new critical disclosures — review patch status on exposed services.

## Executive summary

- 10 new critical disclosures — review patch status on exposed services.

## Signal counts

| Signal | CVEs |
| --- | ---: |
| KEV | 0 |
| EXP (exploit / PoC) | 0 |
| EPSS rise | 0 |
| CVSS critical disclosure | 10 |
| Patch status change | 0 |
| **Total** | **10** |


## CVEs

### CVE-2025-34112
**An authenticated multi-stage remote code execution vulnerability exists in Riverbed SteelCentral NetProfiler and NetExpress 10.8.7 virtua...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 10.0
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-78
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2025-07-15)

> An authenticated multi-stage remote code execution vulnerability exists in Riverbed SteelCentral NetProfiler and NetExpress 10.8.7 virtual appliances. A SQL injection vulnerability in the '/api/common/1.0/login' endpoint can be exploited to create a new user account in the applia…

### CVE-2025-52376
**An authentication bypass vulnerability in the /web/um_open_telnet.cgi endpoint in Nexxt Solutions NCM-X1800 Mesh Router firmware UV1.2.7...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.8
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2025-07-15)

> An authentication bypass vulnerability in the /web/um_open_telnet.cgi endpoint in Nexxt Solutions NCM-X1800 Mesh Router firmware UV1.2.7 and below, allowing an attacker to remotely enable the Telnet service without authentication, bypassing security controls. The Telnet server is…

### CVE-2025-34111
**tiki tikiwiki_cms\/groupware**
- **Signals:** CVSS
- **Asset:** tiki tikiwiki_cms\/groupware
- **CVSS max:** 9.8
- **NVD status:** Analyzed
- **NVD modified:** 2025-10-03T00:42:13.970
- **CWE:** CWE-20
- **CWE:** CWE-434
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-15)

> An unauthenticated arbitrary file upload vulnerability exists in Tiki Wiki CMS Groupware version 15.1 and earlier via the ELFinder component's default connector (connector.minimal.php), which allows remote attackers to upload and execute malicious PHP scripts in the context of th…

### CVE-2025-34110
**A directory traversal vulnerability exists in ColoradoFTP Server ≤ 1.3 Build 8 for Windows, allowing unauthenticated attackers to read or...**
- **Signals:** CVSS
- **Attack:** Directory Traversal
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-22
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-15)

> A directory traversal vulnerability exists in ColoradoFTP Server ≤ 1.3 Build 8 for Windows, allowing unauthenticated attackers to read or write arbitrary files outside the configured FTP root directory. The flaw is due to insufficient sanitation of user-supplied file paths in the…

### CVE-2025-41236
**VMware ESXi, Workstation, and Fusion contain an integer-overflow vulnerability in the VMXNET3 virtual network adapter.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-15)

> VMware ESXi, Workstation, and Fusion contain an integer-overflow vulnerability in the VMXNET3 virtual network adapter. A malicious actor with local administrative privileges on a virtual machine with VMXNET3 virtual network adapter may exploit this issue to execute code on the ho…

### CVE-2025-41237
**VMware ESXi, Workstation, and Fusion contain an integer-underflow in VMCI (Virtual Machine Communication Interface) that leads to an out-...**
- **Signals:** CVSS
- **Attack:** Out-of-Bounds Write
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-15)

> VMware ESXi, Workstation, and Fusion contain an integer-underflow in VMCI (Virtual Machine Communication Interface) that leads to an out-of-bounds write. A malicious actor with local administrative privileges on a virtual machine may exploit this issue to execute code as the virt…

### CVE-2025-41238
**VMware ESXi, Workstation, and Fusion contain a heap-overflow vulnerability in the PVSCSI (Paravirtualized SCSI) controller that leads to...**
- **Signals:** CVSS
- **Attack:** memory safety
- **CVSS max:** 9.3
- **NVD status:** Deferred
- **NVD modified:** 2026-04-15T00:35:42.020
- **CWE:** CWE-787
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2025-07-15)

> VMware ESXi, Workstation, and Fusion contain a heap-overflow vulnerability in the PVSCSI (Paravirtualized SCSI) controller that leads to an out of-bounds write. A malicious actor with local administrative privileges on a virtual machine may exploit this issue to execute code as t…

### CVE-2025-49827
**cyberark conjur**
- **Signals:** CVSS
- **Asset:** cyberark conjur
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T22:16:18.750
- **CWE:** CWE-807
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-15)

> Conjur provides secrets management and application identity for infrastructure. Conjur OSS versions 1.19.5 through 1.22.0 and Secrets Manager, Self-Hosted (formerly known as Conjur Enterprise) 13.1 through 13.5 and 13.6 are vulnerable to bypass of the IAM authenticator. An attack…

### CVE-2025-49831
**cyberark conjur**
- **Signals:** CVSS
- **Asset:** cyberark conjur
- **CVSS max:** 9.8
- **NVD status:** Modified
- **NVD modified:** 2025-11-04T22:16:19.260
- **CWE:** CWE-287
- **Risk score:** 66
- **CVSS critical:** 9.1 (disclosed 2025-07-15)

> An attacker of Secrets Manager, Self-Hosted installations that route traffic from Secrets Manager to AWS through a misconfigured network device can reroute authentication requests to a malicious server under the attacker’s control. CyberArk believes there to be very few installat…

### CVE-2025-50067
**oracle application_express privilege escalation**
- **Signals:** CVSS
- **Asset:** oracle application_express
- **Attack:** privilege escalation
- **CVSS max:** 9.0
- **NVD status:** Analyzed
- **NVD modified:** 2025-07-24T21:27:21.010
- **CWE:** CWE-601
- **Risk score:** 66
- **CVSS critical:** 9.0 (disclosed 2025-07-15)

> Vulnerability in Oracle Application Express (component: Strategic Planner Starter App).  Supported versions that are affected are 24.2.4 and  24.2.5. Easily exploitable vulnerability allows low privileged attacker with network access via HTTP to compromise Oracle Application Expr…

---

*Source: https://www.cvelogic.com/threat-intelligence/2025-07-15*
