# Part 1 - Configuration of the Network

## Devices Added
- Two servers (Splunk Server, Active Directory Server)
- Two computers (Target Machine, Attacker Machine)
- 1 Switch
- 1 Router
- 1 Cloud

## Connections
- Every device linked to the switch over Ethernet
- Switch linked to router
- Router linked to cloud (internet access)

## Network Settings
- Subnet: 192.168.10.0/24

## Assigning IPs
- Splunk Server: 192.168.10.10
- Server Active Directory: 192.168.10.7
- Attacker Machine (Kali Linux): 192.168.10.250
- Target Machine (Windows 10): DHCP

## Host Config
- AD Server:
- Role: Domain Controller (planned)
- Tools: Sysmon, Splunk Forwarder

Splunk Server:
- Role: SIEM (collecting logs)

- Target Machine:
- OS: Windows 10
- Tools: Sysmon, Splunk Forwarder, Atomic Red Team

- Attacker Machine:
- Kali Linux is the OS.
