# Part 2: Configuring Virtual Machines
## Goal
Use VirtualBox to set up the lab environment:
- Windows 10 (Target Machine)
- Kali Linux (Attacker Machine)
- Windows Server 2022 (Active Directory)
- Ubuntu Server (Splunk)
---
## Windows 10 (Target Machine)
### Steps for configuration
- Made a new VM in VirtualBox
- Chose the Windows 10 ISO
- Selected "Skip Unattended Installation"
- Details:
- RAM: 4GB
- CPU: 1 Core
- Disk: 50GB
### Installation
- Decided "I lack a product key"
- Set up Windows 10 Pro.
- Finished installation using the default settings
---
## Kali Linux (Attacker Workstation)
### Steps for Setup
- Downloaded prebuilt VirtualBox picture found at kali.org
- Extracted with 7-Zip
- Imported straight into VirtualBox
### Outcome
- Machine started properly and ready for work
---
## Windows Server 2022 (Active Directory)
### Steps to Set Up
- Got ISO from Microsoft Evaluation Center
- Made a VM called: ADDC01.
- Selected "Skip Unattended Installation"
- Characteristics:
- RAM: 4GB (will decrease later)
- Disk: fifty gigabytes
### How to Install
- Chose Windows Server 2022 Standard (Desktop Experience)
- Create an administrator password.
- Installation accomplished
---
## Ubuntu Server (Splunk Server)
### Steps for setting up
- Downloaded Ubuntu Server ISO
- Made a VM called: splunk
- Specifications:
- RAM: 8GB
- CPU: Two Cores
- Disk: 100 gigabytes
### Problem Found
- The VM boots into a black screen several times.
### Troubleshooting
- Recreated the VM several times
- Erased earlier VM data
- Downloaded ISO again (suspected corrupted file)
### Resolution
- Fresh ISO corrected the problem
### After Configuration
- Updated system:
```bash
sudo apt-get update && sudo apt-get upgrade -y
