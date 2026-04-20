# active-directory-lab
This project is a hands-on Active Directory home lab designed to simulate a real-world enterprise network. It includes a Domain Controller, centralized logging with Splunk, and attacker/target machines to generate and monitor security events.

## 🛠️ Technologies Used
- Windows Server
- Active Directory
- Splunk
- Sysmon
- VirtualBox
- Cisco Packet Tracer
- Kali Linux
- Windows 10

## 🚀 Features
- Active Directory Domain setup
- Centralized logging using Splunk SIEM
- Sysmon integration for advanced event logging
- Simulated attacker machine (Kali Linux)
- Target machine with Atomic Red Team testing
- Network topology design (router, switch, subnet)


## ⚙️ Process
### Part 1: Network Design
- Built network topology in Packet Tracer
- Configured subnet: 192.168.10.0/24
- Connected:
  - 2 Servers (AD + Splunk)
  - 2 PCs (Target + Attacker)
  - Switch, Router, and Cloud
- Assigned static IPs to servers:
  - AD Server: 192.168.10.7
  - Splunk Server: 192.168.10.10
- Configured attacker and target environments
### Part 2: Virtual Machine Configuration
- Using VirtualBox, set up and installed four virtual machines.
- Windows 10 (target computer)
- Kali Linux (attacker computer)
- Windows Server 2022 (Active Directory)
Ubuntu Server (Splunk)
- Assigned system resources according to machine functions.
- Obtained Kali Linux prebuilt image
- Configured Windows Server 2022 (Desktop Experience)
- Set up Ubuntu Server for Splunk deployment
- ubuntu installation problem produced by faulty iso was fixed.
- Renovated Ubuntu system packages

## 📚 Things I Discovered
- How can I utilize Cisco Packet Tracer to create and simulate a network?
- How to set up many virtual machines for a lab environment
- Centralized identity management: The function of Active Directory
- How SIEM systems such as Splunk gather and examine logs
- Basic troubleshooting methods for problems with installing VMs and operating systems

## 🔧 Improvements
- Add firewall setup
- Simulate outside attacks more properly
- Increase network with more endpoint
- Use intrusion detection software


## ▶️ Running Instructions
1. Download VirtualBox
2. Get the necessary ISO files:
- Windows 10
- Windows Server 2022
- Ubuntu Server
3. Import Kali Linux VirtualBox picture
4. Design virtual machines with certain settings.
5. Stick to the setup procedures given in the Process part.
(Note: The entire setup will be updated as the lab advances)



## 📸 Demo
<img width="1911" height="1074" alt="1 AD“Network devices”" src="https://github.com/user-attachments/assets/58a02c07-26b5-4e8b-b08d-ab37d8c9c359" />
<img width="1919" height="1079" alt="2 AD“Network Topology”" src="https://github.com/user-attachments/assets/c57f7d62-285d-4424-ba76-1fdd080a1db9" />
<img width="1919" height="1079" alt="3 AD“Network configs”" src="https://github.com/user-attachments/assets/7a8375dd-0150-43db-880a-6d97025a3b1e" />
<img width="1916" height="1027" alt="Screenshot 2026-04-17 064349" src="https://github.com/user-attachments/assets/99a30c1f-de23-4419-a349-7ba22f337771" />
<img width="959" height="1023" alt="Screenshot 2026-04-17 064608" src="https://github.com/user-attachments/assets/66ca48b3-300e-4d85-8715-d6c5c4e04afc" />
<img width="956" height="1032" alt="Screenshot 2026-04-17 064808" src="https://github.com/user-attachments/assets/03b20d0d-00d1-46c3-b054-931def5a3bf0" />
<img width="1837" height="1003" alt="Screenshot 2026-04-17 070048" src="https://github.com/user-attachments/assets/0a54153b-1c35-4297-a5a8-69226a17dbde" />
<img width="1898" height="903" alt="Screenshot 2026-04-17 070635" src="https://github.com/user-attachments/assets/43ea448e-b93f-4acd-85f0-3fc91f25f6af" />
<img width="1814" height="1025" alt="Screenshot 2026-04-17 081658" src="https://github.com/user-attachments/assets/8cc78138-67eb-4095-a6ef-b92c5ffd9607" />
<img width="1181" height="846" alt="Screenshot 2026-04-17 082058" src="https://github.com/user-attachments/assets/c9d185d4-83cb-470e-a0cc-5312c847ceee" />
<img width="1614" height="961" alt="Screenshot 2026-04-17 090821" src="https://github.com/user-attachments/assets/8a30d67a-cf10-4cbd-92c4-5c9dcd768e21" />
<img width="1329" height="917" alt="Screenshot 2026-04-20 092447" src="https://github.com/user-attachments/assets/917c23ca-e873-4e14-bd8f-77b5f8f8a440" />
<img width="936" height="862" alt="Screenshot 2026-04-20 093127" src="https://github.com/user-attachments/assets/109f5ecf-7058-438f-ae99-e3c04ef7f39b" />

