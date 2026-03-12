# SSH-BRUTE-FORCE-DETECTION


SSH BRUTE-FORCE DETECTION USING SPLUNK SIEM
Simulated SSH brute-force attacks using Kali Linux and Metasploit Framework's auxiliary/scanner/ssh/ssh_login module against an Ubuntu target system

Ingested Linux authentication logs (/var/log/auth.log) into Splunk Enterprise using Universal Forwarder with real-time streaming via port 9997

Developed SPL queries using rex, stats, bucket, and timechart commands to detect credential abuse patterns and extract attacker IPs dynamically

Built multi-panel Splunk dashboards visualizing failed login spikes, top attacking IPs (bar chart), and targeted username distribution over time

Implemented threshold-based automated alerts (trigger: >20 failed attempts per IP in 5 min) with Slack and email notification actions

Created bonus detection rule to identify successful logins following brute-force attempts — flagging potential account compromise events

SKILLS DEMONSTRATED
SIEM Monitoring
Splunk Enterprise
SPL Querying
Log Analysis
Threat Detection
Security Alerting
Linux Security
Metasploit Framework
Nmap Scanning
Brute-Force Detection
Incident Response
SOC Operations
Blue Team Defense
Network Forensics
TOOLS USED
📊 SPLUNK ENTERPRISE
Industry-leading SIEM platform. Used for log ingestion, SPL querying, dashboard building, and automated alerting. Free trial available at splunk.com.
💻 KALI LINUX
Penetration testing distribution. Used as the attacker machine. Includes Metasploit, Nmap, Hydra, and 600+ security tools pre-installed.
⚔️ METASPLOIT FRAMEWORK
World's most widely used penetration testing framework. The ssh_login auxiliary module performs automated credential stuffing against SSH services.
