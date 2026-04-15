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

## 📚 What I Learned
- How to make a simple business network Topologies
- Importance of static IPs for infrastructure systems
- Identity management roles played by Active Directory
- How SIEM tools like Splunk gather and examine logs

## 🔧 Improvements
- Add firewall setup
- Simulate outside attacks more properly
- Increase network with more endpoint
- Use intrusion detection software


## ▶️ How to Run



## 📸 Demo
<img width="1911" height="1074" alt="1 AD“Network devices”" src="https://github.com/user-attachments/assets/58a02c07-26b5-4e8b-b08d-ab37d8c9c359" />
<img width="1919" height="1079" alt="2 AD“Network Topology”" src="https://github.com/user-attachments/assets/c57f7d62-285d-4424-ba76-1fdd080a1db9" />
<img width="1919" height="1079" alt="3 AD“Network configs”" src="https://github.com/user-attachments/assets/7a8375dd-0150-43db-880a-6d97025a3b1e" />

