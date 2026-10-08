# Tahmid Abtahee
Cybersecurity senior at the University of South Florida | CompTIA Security+ | Tampa, FL

I identify security risks, prioritize them, and build the plan to reduce them. My labs cover risk-based vulnerability triage, cloud identity and Zero Trust design, and the detection engineering that proves controls actually work.

📌 [LinkedIn](https://www.linkedin.com/in/tahmidabtahee/) · [tahmid.abt@gmail.com](mailto:tahmid.abt@gmail.com)
## Projects
### 📡 [Packet Detection Lab](https://github.com/tahosprojects/Packet-Detection-Lab/)
Segmented OPNsense lab isolating attacker and victim networks. Wireshark for byte-level analysis of ARP spoofing, DNS tunneling, and C2 beaconing, standalone Suricata for custom alert-only detection rules, mitmproxy for a TLS interception demo.
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

## Skills
`Splunk (SPL)` `Sigma` `YARA` `Ghidra` `dnSpy` `Sysmon` `Velociraptor (VQL)` `Wireshark` `Nmap` `Atomic Red Team` `Stratus Red Team` `Terraform` `MITRE ATT&CK` `Active Directory` `AWS` `Python` `Bash` `T-Pot` `Canarytokens` `Docker`

## Currently Working On

### 🔐 [Cloud Identity & Zero Trust Architecture (Azure)](https://github.com/tahosprojects/Cloud-Identity-Zero-Trust-Architecture-Azure)
Multi-subscription Azure environment under one Entra ID tenant, secured with Management Groups, Azure Policy, and least-privilege RBAC. Identity federation via Entra ID app registrations (SAML/OIDC), enforced with Conditional Access and PIM for just-in-time admin access. NSG Flow Logs, Defender for Cloud, and Access Reviews provide visibility and catch excess permissions. Includes a deliberate misconfiguration exercise and a formal evaluation against NIST 800-207 and the CISA Zero Trust Maturity Model.
