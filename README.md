<h1 align="center">Hi, I'm James 👋</h1>

<p align="center">
IT professional building hands-on, portfolio-ready experience in IAM, vulnerability management, and security operations. I document everything I build — not just to show I did it, but to show how I think.
</p>

<p align="center">
<a href="https://www.linkedin.com/in/JamespennIV/">LinkedIn</a> ·
<a href="https://github.com/JamespennIV">GitHub</a>
</p>

---

## 🛠️ Projects

### Microsoft Entra ID IAM Lab
Built a hands-on IAM case study using Microsoft Entra ID in an Azure for Students environment, simulating a small organization's identity infrastructure end to end — identity lifecycle management, security groups, RBAC, least privilege, and administrative role delegation, all backed by clear documentation.

**Skills:** Microsoft Entra ID · IAM · RBAC · Least Privilege · User Provisioning · Group-Based Access Control · Administrative Separation · Security Documentation

[**View Project →**](https://github.com/JamespennIV/microsoft-entra-iam-lab)

### TryHackMe Lab Writeups
Portfolio-safe writeups covering completed TryHackMe rooms across investigation, OSINT, AI threat modeling, reverse engineering, and log analysis. Each writeup documents the methodology, tools used, lessons learned, and interview-relevant takeaways — without exposing flags or direct challenge answers.

**Skills:** OSINT · Investigation Methodology · Threat Modeling · AI Security Awareness · Log Analysis · Web Investigation · Reverse Engineering Fundamentals · Evidence Correlation · Technical Documentation

[**View Project →**](https://github.com/JamespennIV/tryhackme-lab-writeups)

### Active Directory on Azure Lab
Built and hardened a departmental Active Directory environment on an Azure-hosted Windows Server VM, simulating a small organization's on-prem-style identity infrastructure end to end — domain promotion, OU and security-group design, scripted user provisioning, and a baseline GPO enforcing password, session-lock, and removable-storage policy, all backed by clear documentation.

**Skills:** Active Directory Domain Services · Domain & Forest Promotion · Organizational Unit Design · Security Group Scoping · PowerShell Scripting · Group Policy Objects · Account Lifecycle Administration · Directory Auditing

[**View Project →**](https://github.com/JamespennIV/active-directory-azure-lab)

### ServiceNow ITSM Fundamentals Lab
Worked through the core ServiceNow ITSM lifecycle end to end in a personal developer instance — logging and resolving an incident with proper internal/external documentation separation, building a self-service catalog item with intake variables, and submitting a Normal change request through CAB approval with a documented test plan and backout plan, plus operational reporting on incident volume.

**Skills:** ServiceNow · Incident Management · ITIL · Service Catalog Design · Change Management · CAB Approval Workflow · Test & Backout Planning · Reporting & Data Visualization

[**View Project →**](https://github.com/JamespennIV/servicenow-itsm-lab)

### Vulnerability Management Lab
Ran a full vulnerability management lifecycle against an Azure-hosted VM using Tenable Nessus — stood up an isolated scanning environment, compared unauthenticated discovery scan results (3 findings) against a credentialed Windows scan (61 findings), remediated a HIGH-severity finding (CVE-2013-3900, CVSS 8.8) using its CVE reference and Nessus's guidance, and validated the fix with a follow-up scan (61 → 59 findings). When Nessus Essentials' free tier blocked native PDF report export, wrote a standalone executive/technical remediation summary in its place rather than treating the process as incomplete.

**Skills:** Tenable Nessus · Vulnerability Scanning (Authenticated & Unauthenticated) · CVE/CVSS Triage · Remediation & Validation · Azure VM Provisioning · Vulnerability Reporting

[**View Project →**](https://github.com/JamespennIV/vulnerability-management-lab)

### Splunk SIEM Log Pipeline Lab
Built a Windows Event Log → Splunk forwarding pipeline, diagnosed a real "zero events indexed" incident down to a silently misnamed config file using Splunk's `btool` CLI (ruling out audit policy, event generation, NSG rules, and receiving config along the way), then rebuilt the indexer from scratch on Ubuntu in Azure with least-privilege network rules, redeployed the forwarder, and turned validated log data into a Classic dashboard and a scheduled high-privileged-logon alert.

**Skills:** Splunk (Universal Forwarder, Indexer, `btool`) · Windows Event Log Forwarding · Azure NSG Least-Privilege Design · Log Pipeline Troubleshooting · Dashboard & Alert Creation · PowerShell Test Event Generation

[**View Project →**](https://github.com/JamespennIV/splunk-labs)

### Wireshark Network Traffic Analysis Lab
Captured and analyzed live network traffic with Wireshark — applied display filters to isolate DNS, TCP, and HTTP activity, verified a DNS lookup and a full TCP three-way handshake against terminal output, identified cleartext credential exposure on an HTTP login form, and used Follow TCP Stream to reconstruct a complete client-server conversation.

**Skills:** Wireshark · Packet Capture & Analysis · Display Filter Syntax · DNS Verification · TCP/TLS Handshake Analysis · Cleartext Credential Detection · Network Troubleshooting

[**View Project →**](https://github.com/JamespennIV/wireshark-lab)


### Azure Active Directory Domain Controller with Terraform
Built and validated an Azure Active Directory Domain Controller entirely through Terraform instead of the Azure Portal — wrote the resource group, network, NSG, VM, and CustomScriptExtension configuration by hand, then debugged real deployment errors as they surfaced: an NSG block name typo, a tfvars key mismatch that Terraform silently fell back around, a missing output value attribute, and VM extension escaping that needed terraform taint to recover from. Ran Checkov static analysis against the finished configuration, validated the deployed domain controller over RDP with PowerShell, then tore the entire environment down with terraform destroy.

**Skills:** Terraform (Infrastructure as Code) · Azure Resource Provisioning · CustomScriptExtension Bootstrapping · Active Directory Domain Services & Forest Promotion · Terraform Plan/Apply/Destroy Troubleshooting · Checkov Static Analysis · PowerShell Validation

[**View Project →**](https://github.com/JamespennIV/terraform/tree/main/Labs/Lab%2001%20AD)



---

## 📜 Certifications

- [**CompTIA A+**](https://www.credly.com/badges/f7215d70-1585-4dd2-9661-396d3e4fe7f3/public_url)
- [**CompTIA Network+**](https://www.credly.com/badges/7f10daa2-77a6-4165-b706-73a795f4b213/public_url)
- [**CompTIA Security+**](https://www.credly.com/badges/19abfa12-b1ae-4854-8a9e-d8af6b7751b3/public_url)
- [**Microsoft Certified: Azure Fundamentals (AZ-900)**](https://learn.microsoft.com/en-us/users/jamespenn-8889/credentials/98a472744a1eb778?ref=https%3A%2F%2Fwww.linkedin.com%2F)

---

<p align="center"><i>Always looking to learn, build, and connect — feel free to reach out.</i></p>
