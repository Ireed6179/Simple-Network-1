Overview
Designed and implemented a multi-segment network using Cisco Packet Tracer to simulate communication between multiple LANs. This project demonstrates core networking principles including routing between subnets, structured IP addressing, and scalable network design.

Objective
To build a network that allows multiple isolated subnets to communicate through a centralized routing device, simulating a real-world small enterprise environment.

Network Architecture
Based on your diagram:

1 Router (central device handling routing)

3 Switches (2960 series)

6 End Devices (PC0–PC5)

3 Separate LAN segments

Each switch connects to its own group of PCs, forming independent subnets that are routed through the central router.

🌐 IP Addressing & Subnets

192.168.1.0/24 (left side LAN)

192.168.2.0/24 (right side LAN)

192.168.1.x range also used in center LAN (based on PC labels)

Understanding of subnet separation

Ability to design multiple broadcast domains

Awareness of how routing enables cross-network communication

Key Configurations
Configured router interfaces (Fa0/0, Fa0/1, etc.) to connect multiple networks

Assigned IP addresses to each subnet

Configured default gateways on all PCs

Connected switches to router interfaces for traffic flow

Verified inter-network communication using ping tests

Technical Skills Demonstrated
Multi-network design

IP addressing and subnetting (/24 networks)

Router interface configuration

Switch-to-router connectivity

End-to-end connectivity validation

Practical application of CCNA fundamentals

Results
Devices within each LAN communicate successfully
Inter-network communication achieved through routing
Network design supports scalability and expansion
Clean hierarchical structure (access → distribution → routing)

Challenges & What I Learned
Learned how improper IP assignment can break communication between subnets
Gained experience configuring multiple router interfaces for different networks
Improved troubleshooting using ping and interface verification
Understood how routers enable communication between isolated LANs

Future Improvements
Here’s where you level this up (and you should):
Implement VLANs to segment traffic logically
Add DHCP to automate IP assignment
Introduce OSPF for dynamic routing
Apply ACLs for basic security control

How to Use This Project
Open the .pkt file in Cisco Packet Tracer
Review router interface configurations
Check IP addressing on each PC
Run ping tests across different networks
Modify configurations to test scalability

This shows:
segmentation
routing between networks

You’re starting to think like a network engineer
What’s missing (and what gets you hired):
VLANs
DHCP
One dynamic routing protocol

