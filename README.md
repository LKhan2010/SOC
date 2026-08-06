# SOC Analyst Portfolio

Welcome to my cybersecurity portfolio.

I am developing practical skills for an entry-level SOC Analyst role through hands-on investigations using Wireshark, Splunk, Elastic and NetworkMiner.

This portfolio contains short investigation videos with captions and supporting written explanations. Each project follows a clear process:

- Review the alert or suspicious activity
- Search and filter the available evidence
- Identify key indicators
- Reach a conclusion
- Recommend further action

## Projects

### Wireshark – Log4j Investigation
Investigated suspicious HTTP traffic and identified a Log4j exploitation attempt in packet 444.

Key findings included:

- Suspicious JNDI activity
- External IP communication
- A decoded command used to download and execute `lh.sh`

[Open the Wireshark project](Wireshark-Log4j)

### Splunk – SSH Brute-Force Investigation
Investigated repeated SSH login attempts against a Linux host.

Key findings included:

- Source IP `10.10.242.248`
- More than 500 attempts against the `john.smith` account
- A successful login after repeated failed attempts

[Open the Splunk project](Splunk-Brute-Force)

### Elastic – ProxyLogon Investigation
Investigated suspicious web requests linked to a possible ProxyLogon attack.

Key findings included:

- Automated POST requests
- Requests to `/ecp/proxyLogon.ecp`
- Command execution through the `errorEE.aspx` web shell

[Open the Elastic project](Elastic-ProxyLogon)

### NetworkMiner – Network Artefact Analysis
Used NetworkMiner to extract files and device information from a packet capture.

Key findings included:

- ASIX USB product information
- Lumia 535 mobile-device information
- Recovery of `Crazy-Fishing.jpg`
- Source IP `50.22.95.9`

[Open the NetworkMiner project](NetworkMiner)

### Splunk – Suspicious Process Investigation
Investigated suspicious process activity linked to an HR user.

Key findings included:

- Abuse of `certutil.exe`
- Download of `benign.exe`
- Activity on workstation `HR_01`
- Windows Event ID 4688

[Open the Suspicious Process project](Splunk-Suspicious-Process)

### Boogeyman 2 – Phishing and Macro Analysis
Investigated a phishing email and analysed the malicious Word attachment.

Key findings included:

- A suspicious job-application email
- An embedded VBA macro
- Automatic execution through `AutoOpen`
- Download of `update.png`
- Saving and execution of `C:\ProgramData\update.js`

[Open the Boogeyman 2 project](Boogeyman-2-Phishing)

## Tools Used

- Wireshark
- Splunk
- Elastic
- NetworkMiner
- Olevba
- Windows Event Logs
- Linux authentication logs
- Packet-capture analysis

## Skills Demonstrated

- Alert investigation
- Log analysis
- Network-traffic analysis
- Brute-force detection
- Phishing analysis
- Malicious macro analysis
- Web-shell identification
- Process investigation
- Evidence gathering
- Incident escalation

## Training and Certification Evidence

My cybersecurity training includes Level 2 and Level 3 Cyber Security qualifications and completion of the TryHackMe SOC Level 1 learning path.

[View certificates, TryHackMe badges and completed room evidence](./TryHackMe-Evidence)


## Career Goal

I am working towards an entry-level SOC Analyst or Junior Cybersecurity Analyst position where I can continue developing my investigation, monitoring and incident-response skills.
