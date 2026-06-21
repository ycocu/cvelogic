# Daily Threat Intelligence — June 19, 2026

**Digest window (US Eastern, NVD):** 2026-06-19
**Generated:** 2026-06-21T09:42:47Z

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

### CVE-2026-45480
**Improper authentication in Azure Active Directory allows an unauthorized attacker to elevate privileges over a network.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD published:** 2026-06-19
- **NVD modified:** 2026-06-19
- **CWE:** CWE-287
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-19)

> Improper authentication in Azure Active Directory allows an unauthorized attacker to elevate privileges over a network.

### CVE-2026-48772
**ProxySQL is a proxy for MySQL and its forks, as well as PostgreSQL.**
- **Signals:** CVSS
- **CVSS max:** 10.0
- **NVD status:** Received
- **NVD published:** 2026-06-19
- **NVD modified:** 2026-06-19
- **CWE:** CWE-348
- **Risk score:** 67
- **CVSS critical:** 10.0 (disclosed 2026-06-19)

> ProxySQL is a proxy for MySQL and its forks, as well as PostgreSQL. In versions 2.0.0 through 3.0.8, the ProxySQL MySQL frontend accepts the `PROXY UNKNOWN <addr> <addr> <port> <port>\r\n` PP1 frame as a well-formed PROXY protocol header. The HAProxy PROXY protocol v1 specificati…

### CVE-2026-48584
**Execution with unnecessary privileges in Azure Synapse allows an authorized attacker to elevate privileges over a network.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.9
- **NVD status:** Received
- **NVD published:** 2026-06-19
- **NVD modified:** 2026-06-19
- **CWE:** CWE-250
- **Risk score:** 67
- **CVSS critical:** 9.9 (disclosed 2026-06-19)

> Execution with unnecessary privileges in Azure Synapse allows an authorized attacker to elevate privileges over a network.

### CVE-2026-11551
**The Branda plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 3.4.29.**
- **Signals:** CVSS
- **Attack:** Privilege Escalation
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-19
- **NVD modified:** 2026-06-19
- **CWE:** CWE-640
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-19)

> The Branda plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 3.4.29. This is due to the plugin not properly validating a user's identity prior to updating their password. This makes it possible for unauthenticate…

### CVE-2026-48137
**There is an untrusted pointer dereference vulnerability in the NI grpc-device sideband streaming API that may allow an attacker to cause...**
- **Signals:** CVSS
- **Attack:** RCE
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD published:** 2026-06-19
- **NVD modified:** 2026-06-19
- **CWE:** CWE-822
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-19)

> There is an untrusted pointer dereference vulnerability in the NI grpc-device sideband streaming API that may allow an attacker to cause an arbitrary memory dereference, potentially resulting in remote code execution.  Successful exploitation requires an attacker  to supply a spe…

### CVE-2026-48582
**Missing authorization in Microsoft Exchange Online allows an authorized attacker to elevate privileges over a network.**
- **Signals:** CVSS
- **Attack:** privilege escalation
- **CVSS max:** 9.6
- **NVD status:** Received
- **NVD published:** 2026-06-19
- **NVD modified:** 2026-06-19
- **CWE:** CWE-862
- **Risk score:** 66
- **CVSS critical:** 9.6 (disclosed 2026-06-19)

> Missing authorization in Microsoft Exchange Online allows an authorized attacker to elevate privileges over a network.

### CVE-2026-48773
**ProxySQL is a proxy for MySQL and its forks, as well as PostgreSQL.**
- **Signals:** CVSS
- **Attack:** Memory Corruption
- **CVSS max:** 9.8
- **NVD status:** Received
- **NVD published:** 2026-06-19
- **NVD modified:** 2026-06-19
- **CWE:** CWE-787
- **Risk score:** 67
- **CVSS critical:** 9.8 (disclosed 2026-06-19)

> ProxySQL is a proxy for MySQL and its forks, as well as PostgreSQL. Versions 2.0.18 through 3.0.8 have a pre-authentication heap memory corruption vulnerability in the MySQL and PostgreSQL protocol first-read paths. A remote unauthenticated client can declare an oversized first p…

### CVE-2026-56073
**Cap-go before 12.128.2 contains an authentication bypass vulnerability in OTP verification that allows attackers to bypass email verifica...**
- **Signals:** CVSS
- **Attack:** Auth Bypass
- **CVSS max:** 9.4
- **NVD status:** Received
- **NVD published:** 2026-06-19
- **NVD modified:** 2026-06-19
- **CWE:** CWE-345
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-19)

> Cap-go before 12.128.2 contains an authentication bypass vulnerability in OTP verification that allows attackers to bypass email verification by modifying server responses. Attackers can intercept OTP verification requests and manipulate HTTP responses to falsely mark verificatio…

### CVE-2026-56081
**Cap-go before 12.128.2 contains an authentication logic flaw that lets an attacker register and control an account bound to a victim's em...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD published:** 2026-06-19
- **NVD modified:** 2026-06-19
- **CWE:** CWE-640
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-19)

> Cap-go before 12.128.2 contains an authentication logic flaw that lets an attacker register and control an account bound to a victim's email address before that email is verified. By enabling two-factor authentication on the pre-registered account, the attacker gains control over…

### CVE-2026-9142
**There is an insecure default credentials vulnerability in NI grpc-device when TLS configuration is not present and the server is bound be...**
- **Signals:** CVSS
- **CVSS max:** 9.3
- **NVD status:** Received
- **NVD published:** 2026-06-19
- **NVD modified:** 2026-06-19
- **CWE:** CWE-306
- **Risk score:** 66
- **CVSS critical:** 9.3 (disclosed 2026-06-19)

> There is an insecure default credentials vulnerability in NI grpc-device when TLS configuration is not present and the server is bound beyond loopback.  This may allow an unauthenticated user access to the server on the local network.  This affects NI grpc-device 2.17.0 and prior…

---

*Source: https://www.cvelogic.com/threat-intelligence/2026-06-19*
