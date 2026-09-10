# Tahmid Abtahee
Cybersecurity senior at the University of South Florida | CompTIA Security+ | Tampa, FL
I build hands-on security labs focused on SOC operations and detection engineering: cloud-native pipelines, endpoint forensics, adversary emulation, and vulnerability management.
📌 [LinkedIn](https://www.linkedin.com/in/tahmidabtahee/) · [tahmidabtahee@usf.edu](mailto:tahmidabtahee@usf.edu)
## Projects
### 🦠 [Malware RE](https://github.com/tahosprojects/Malware-RE)
Static and dynamic analysis of live njRAT and GhostRAT samples in an isolated VirtualBox lab. Ghidra/dnSpy for reverse engineering, Sysmon/SystemInformer/FakeNet-NG for detonation, Splunk for telemetry, custom YARA for detection.
### 🍯 [Honeypot TI LLM Splunk](https://github.com/tahosprojects/Honeypot-TI-LLM-Splunk)
Public-facing T-Pot honeypot with a Canarytokens deception layer, centralizing real attacker telemetry in a self-hosted Splunk SIEM. Python pipeline via the Anthropic API auto-classifies attacks to MITRE ATT&CK.
### 🚀 [Hybrid Detection Engineering Lab](https://github.com/tahosprojects/detection-engineering-lab)
End-to-end AWS detection pipeline: Terraform for IaC, Stratus Red Team for adversary emulation, custom Sigma/SPL detections, Python-based threat intel enrichment for triage.
### 🛡️ [SOC Detection Home Lab](https://github.com/tahosprojects/soc-home-lab)
4-VM AD environment with Splunk SIEM and Sysmon telemetry. Executed Atomic Red Team techniques, wrote SPL detections, published a formal incident report (INC-2026-001) mapped to MITRE ATT&CK and NIST SP 800-61.
### 🔍 [Endpoint Forensics & Threat Hunting](https://github.com/tahosprojects/endpoint-forensics-splunk-threat-hunting)
Live forensics on AWS EC2, hunting PowerShell and process-creation events with Velociraptor (VQL) and Splunk.
### 📊 [Enterprise Vulnerability Management](https://github.com/tahosprojects/enterprise-vulnerability-management-triage)
Risk-based triage across a 30-endpoint environment using EPSS and CISA KEV to prioritize EOL software and high-risk exposures.
### 🌐 [NSA Manageable Network Security Plan](https://github.com/tahosprojects/NSA-Manageable-Network-Security-Plan-MNSP)
Defense-in-depth plan across all eight MNSP milestones: segmentation, access control, patching, baselines, monitoring, and IR procedures aligned with NIST SP 800-41, 800-34, and 800-61.

## Skills
`Splunk (SPL)` `Sigma` `YARA` `Ghidra` `dnSpy` `Sysmon` `Velociraptor (VQL)` `Wireshark` `Nmap` `Atomic Red Team` `Stratus Red Team` `Terraform` `MITRE ATT&CK` `Active Directory` `AWS` `Python` `Bash` `T-Pot` `Canarytokens` `Docker`

## Currently Working On

### 🔐 [Cloud Identity & Zero Trust Architecture (AWS)](https://github.com/tahosprojects/Cloud-Identity-Zero-Trust-Architecture-AWS)
Multi-account AWS Organization with least-privilege IAM, SCPs, cross-account roles, and identity federation via SSO/SAML/OIDC. VPC Flow Logs analyzed serverlessly with Athena, GuardDuty for threat detection, and IAM Access Analyzer to catch excess permissions. Includes a deliberate misconfiguration exercise (introduce and then detect/fix a real mistake) and a formal evaluation against NIST 800-207 and the CISA Zero Trust Maturity Model.

### 📡 [Packet Detection Lab](https://github.com/tahosprojects/Packet-Detection-Lab/)
Segmented OPNsense lab isolating an attacker and victim network. Captured and manually reverse-engineered ARP spoofing, DNS tunneling, and C2 beaconing at the packet level in Wireshark, then built Suricata detection rules enforced inline via OPNsense IPS, plus a TLS interception demo and a SOC-style capstone incident report mapped to MITRE ATT&CK.
