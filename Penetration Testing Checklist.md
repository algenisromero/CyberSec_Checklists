# Penetration Testing Checklist

### 1. Planning and Preparation:

- [ ] Define the scope and objectives of the penetration test.
- [ ] Obtain proper authorization and legal agreements.
- [ ] Gather relevant information about the target system or network.

### 2. Reconnaissance:

- [ ] Perform passive information gathering:
  - **_Tools:_** WHOIS, DNS lookups, search engines.
- [ ] Conduct active information gathering:
  - **_Tools:_** Nmap, Recon-ng, Shodan.
- [ ] Document gathered information.

### 3. Scanning:

- [ ] Utilize vulnerability scanners:
  - **_Tools:_** Nessus, OpenVAS, Nexpose.
- [ ] Conduct port scanning:
  - **_Tools:_** Nmap, Masscan.
- [ ] Perform network mapping and diagramming:
  - **_Tools:_** NetDiscover, Draw.io.
- [ ] Document scanning results.

### 4. Enumeration:

- [ ] Enumerate user accounts, network resources, and system details:
  - **_Tools:_** enum4linux, enum.exe, SNMPWalk.
- [ ] Enumerate DNS records and zone transfers:
  - **_Tools:_** dnsrecon, dnsenum.
- [ ] Extract useful information from network services:
  - **_Tools:_** BannerGrabber, SNMPGet, SMTP User Enumeration.
- [ ] Document enumeration results.

### 5. Vulnerability Exploitation:

- [ ] Exploit identified vulnerabilities:
  - **_Tools:_** Metasploit Framework, Core Impact, Cobalt Strike.
- [ ] Utilize web application vulnerability scanners for targeted testing:
  - **_Tools:_** OWASP ZAP, Burp Suite.
- [ ] Conduct brute force attacks:
  - **_Tools:_** Hydra, Medusa, John the Ripper.
- [ ] Document successful exploitations.

### 6. Post-Exploitation:

- [ ] Maintain access to compromised systems:
  - **_Tools:_** Netcat, Meterpreter, PowerShell Empire.
- [ ] Extract sensitive data:
  - **_Tools:_** Mimikatz, Responder.
- [ ] Perform privilege escalation:
  - **_Tools:_** Kernel exploits, misconfigured permissions.
- [ ] Document post-exploitation activities.

### 7. Reporting and Documentation:

- [ ] Document all findings, vulnerabilities, and recommendations.
- [ ] Prepare a comprehensive report outlining the testing methodology, risks, and mitigation steps.
- [ ] Present findings to relevant stakeholders.
- [ ] Finalize and submit the assessment report.

Remember to adapt the checklist to your specific needs and consider using additional tools that align with your assessment objectives and target environment.
