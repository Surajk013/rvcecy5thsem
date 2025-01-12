
# QUIZ pov

1. **[Common Vulnerability Scoring System] CVSS** - is an industry-standard that vendors used to determine the severity
of a vulnerability.

2. **Human Psychology** - is the heart of every social engineering attack without which the
attacks will not work.

3. Handling zero day vulnerability
 - Immediate Detection and Assessment
 - Containment
 - Communication
 - Mitigation
 - Patching and Updates
 - Post-Incident Analysis
 - Preventive Measure for the future

 4. Zero day vulnerability workflow - Detect -> Contain ->  Mitigate -> Communicate

 5. Commonly targeted ports during pen-testing 
 TCP ports
  - 21 FTP
  - 22 SSH
  - 23 Telnet
  - 25 SMTP [Email]
  - 53 DNS
  - 80 HTTP
  - 110 POP3 [Email]
  - 143 IMAP [Email]
  - 443 HTTPS 
  - 445 SMB [Windows file sharing]
  - 3306 MySQL DB
  - 3389 RDP [Remote Desktop]
  - 5432 PostgreSQL DB
  - 5900 VNC [Virutal Network Computing]
  - 8080 HTTP Proxy 
  
UDP ports
  - 53 DNS
  - TFTP [Trivial FTP]
  - 123 NTP [Network Time protocol]
  - 161/162 SNMP [Simple Network Management Protocol]
  - 500 IPsec VPN

A **honeypot** is a decoy system designed to attract attackers and collect malicious
software for analysis.

The process of running malware in a controlled environment to observe its behavior
is called **Dynamic** analysis. 

A **Cross-Site Scripting [XSS]** attack involves injecting malicious scripts into web pages viewed by
users

> Differentiate between a black box, white box, and grey box penetration test.

 Mainly differs in the level of information the tester has before testing

**Black-Box**

 -  Tester's knowledge:  The tester has no prior knowledge of the internal structure, architecture or system details
 -  Approach: Simulates an external attacker who has no insider information.
 - Focus: Testing is conducted like an outsider is trying to break the system, focusing on externally visible vulnerabilities.

 ex: scanning ports, exploiting publicly available web service, or social engineering

*adv*
 1. Mimics real-world attack scenarios.
 2. Unbiased as the tester relies solely on what they discover during the test.
*dis*
 1. Time-consuming due to limited inital information.
 2. May miss internal vulnerabilities not visible externally.

**White box**

 - Tester's knowledge: The tester has comlete knowledge of the system iuncluding archietecture, source code, and configuration details.
 - Approach: Simulates an insider or someone with full access, such as a developer or administrator.
 - Focus - Comprehensive testing of internal and external vulnerabilities, including code review and logic flaws.

ex: reviewing source code for vulnerabilities [SQL injection], analyzing configuration of missteps, testing APIs with full documentation.

*adv*
 1. Provides detailed and comprehensive coverage of the system.
 2. Can identify vulnerabilities not easily discoverable externally, such as logic flaws or hardcoded credentails.

*dis*
 1. Time-intensive dur to dept of analysis.
 2. Requires testers to have expertise in the system's technologies.
 3. May not mimic real-world scenarios if attackers lack insider access.

**Grey Box**

  - Tester’s Knowledge: The tester has partial knowledge of the system, such as credentials, network diagrams, or application logic.
  - Approach: Simulates an attacker with some insider knowledge, such as a disgruntled employee or a user with limited access.
  - Focus: Combines aspects of black box and white box testing, targeting areas where insider knowledge might expose vulnerabilities.

Examples: Testing an application with limited user credentials to uncover privilege escalation flaws, assessing the effectiveness of access controls.

*Advantages:*
 1. Balances real-world scenarios with efficiency by leveraging known information.
 2. Faster than black box testing and more realistic than white box testing.

*Disadvantages:*
 1. Limited scope compared to white box testing.
 2. May not uncover all external-facing vulnerabilities.
<br><br>

[blackvwhitevgrey](pics/blackvwhitevgrey)


continue from 1.9 from the model paper
