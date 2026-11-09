# Michael Adeboye
**Information Systems & Technology + Cybersecurity @ UTSA** · USAA Ascent Scholar

I build labs on my Mac and in Azure, run attacks against them, write detections, and document everything. Looking for **Summer 2027 internships** in cyber analysis, security engineering, IT/infrastructure, and network/systems engineering.

### 🔭 Projects
- **[Azure AD Lab](https://github.com/michaeladeboye/azure-ad-lab)**: Active Directory domain in Azure with a Server Core domain controller and an admin workstation, reached only through Bastion so neither VM has a public IP. Set up OUs, department security groups, and GPOs for account lockout and workstation logging, then brute-forced a test account to prove the lockout works and unlocked it like a help desk ticket. Includes a PowerShell script that provisions users from a CSV and skips accounts that already exist.
- **[Detection Home Lab](https://github.com/michaeladeboye/security-writeups/tree/main/home-lab)**: Kali, Windows 11 with Sysmon, and Wazuh on Ubuntu Server, isolated on a host-only network in UTM
- **[Detection Writeups](https://github.com/michaeladeboye/security-writeups/tree/main/detection-rules)**: Four attack-and-detect cycles run in the lab (brute-force login, suspicious PowerShell, new local admin account, scheduled-task persistence), each with a custom Wazuh rule mapped to MITRE ATT&CK
- **[CyberDefenders: Web Investigation](https://github.com/michaeladeboye/security-writeups/blob/main/cyberdefenders/web-investigation.md)**: PCAP analysis in Wireshark tracing a SQL injection to an admin login and web shell upload, with IOCs, ATT&CK mapping, and detection ideas
- **[PortSwigger Web Security Academy](https://github.com/michaeladeboye/security-writeups/tree/main/webacademy)**: SQL injection, XSS, and clickjacking labs worked in Burp Suite, each covering the exploit, root cause, and fix
- **[Domain-Scanner](https://github.com/michaeladeboye/domain-scanner)**: Python tool that checks domains for security headers (HSTS, CSP, X-Frame-Options), TLS cert expiry, and TLS 1.2+ support, with optional JSON/CSV output. I used it to find and fix missing headers on my client sites. The repo runs CodeQL, Dependabot, and secret scanning, and I patched a high-severity CodeQL finding (CWE-327) by enforcing a TLS 1.2 minimum.
- **[OverTheWire Bandit](https://github.com/michaeladeboye/security-writeups/tree/main/bandit)**: Completed all levels (0–33), with level-by-level writeups
- **[Incident Handler's Journal](https://github.com/michaeladeboye/security-writeups/blob/main/incident-handler-journal.md)**: Incident documentation from the Google Cybersecurity cert, including Wireshark and tcpdump analysis

### 🔨 Currently
- Building a Java detection engine that flags attacks in event logs exported from my home lab
- picoCTF forensics and web exploitation
- More CyberDefenders blue-team labs

### 🛠️ Tools
- **Languages:** Python · Bash · PowerShell · Java
- **Security:** Wazuh · Sysmon · Wireshark · tcpdump · Nmap · Burp Suite · Hydra · CyberChef · Kali · MITRE ATT&CK
- **IT & Cloud:** Active Directory · Group Policy · Windows Server · RSAT · Azure (VMs, VNet, Bastion)
- **Platform:** Linux · UTM · Git · GitHub security (CodeQL, Dependabot)

### 📜 Certifications
- Google Cybersecurity Professional
- Google IT Support Professional

### 📫 Contact
[Email](mailto:madeboye77.2@gmail.com) · [LinkedIn](https://www.linkedin.com/in/michaeladeboye)
