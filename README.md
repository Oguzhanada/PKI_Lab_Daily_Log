# 🔐 PKI & Active Directory Lab — Daily Log

This repository documents my day-to-day progress while building and troubleshooting a **PowerShell-driven PKI (Public Key Infrastructure) and Active Directory lab** using VMware Workstation.

The goal is to recreate enterprise-level scenarios (Domain Controller, Enterprise CA, and domain-joined clients), automate administrative tasks, and improve technical troubleshooting and documentation skills.

---

## 🧩 Lab Topology
| Role | Hostname | OS | Description |
|------|-----------|----|-------------|
| **DC01** | dc01.lab.local | Windows Server 2022 | Domain Controller (AD DS + DNS) |
| **CA01** | ca01.lab.local | Windows Server 2019 | Enterprise Root Certification Authority |
| **CLIENT01** | client01.lab.local | Windows 11 Pro | Domain-joined client |

**Network:** VMware Workstation (NAT)  
**Domain:** `lab.local`

---

## 🧠 Purpose
- Track my progress and lessons learned during the lab setup  
- Document real troubleshooting steps and fixes  
- Build a consistent, transparent learning record  
- Improve PowerShell scripting, AD management, and PKI understanding  

---

## ⚙️ Tools Used
- VMware Workstation Pro  
- Windows Server 2019 / 2022  
- Windows 11 Pro  
- PowerShell 7  
- Active Directory Certificate Services (ADCS)

---

## 📋 Daily Log Format
Each log file (`logs/YYYY-MM-DD.md`) includes:
- What I did today  
- Issues encountered  
- Root cause analysis  
- Fix / Resolution  
- Verification steps  
- Next planned actions  

---

## Screenshots

Here is the screenshot of the domain join error I encountered:

`images/2025-10-27/example.png`

And this one shows the Group Policy configuration for auto-enrollment:

 `images/2025-10-27/GroupPolicyExample.png`

