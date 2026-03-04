\# SOC Home Lab using VirtualBox



\## Project Overview

This project demonstrates how to build a SOC home lab using VirtualBox. 

The lab consists of three virtual machines connected through NAT and Internal Network.



\## Machines Used

\- Kali Linux (Attacker Machine)

\- Windows VM (Target Machine)

\- Ubuntu Server (Server Machine)



\## Network Configuration



Adapter 1: NAT  

Used for internet access and downloading tools.



Adapter 2: Internal Network  

Used for communication between virtual machines.



\## Internal Network IP Addresses



Windows VM : 192.168.1.10  

Kali Linux : 192.168.1.20  

Ubuntu VM : 192.168.1.30  



\## Lab Architecture



The lab environment consists of three virtual machines connected through an internal network. 

Kali Linux acts as the attacker machine, Windows acts as the target machine, and Ubuntu Server can be used for monitoring or server practice.



\## Testing Connectivity



Example ping commands used to verify connectivity:



Kali Linux

ping 192.168.1.10



Windows

ping 192.168.1.20



Ubuntu

ping 192.168.1.10



\## Skills Practiced

\- Virtual Machine Setup

\- Network Configuration

\- Linux and Windows Administration

\- Basic Network Troubleshooting

