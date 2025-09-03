# Bank-Network-Infrastructure
## 📖 Overview
This project focuses on designing and implementing a *secure, scalable, and reliable enterprise network* for *Radeon Company Ltd., a US-owned Banking and Insurance firm expanding into the African market. The first branch in **Nairobi, Kenya* is hosted in a *four-story building*, where each floor houses multiple departments with specific networking requirements.

The goal was to design a *robust hierarchical network infrastructure* that supports wired and wireless connectivity, efficient routing, VLAN-based segmentation, IP subnetting, centralized server management, and network security.

## 🎯 Objectives
- Design and implement a *hierarchical network* (Core, Distribution, Access layers).
- Provide *VLAN segmentation* for each department to ensure security and traffic management.
- Implement *OSPF routing protocol* for dynamic routing between routers.
- Configure *DHCP, HTTP, and Email servers* for centralized services.
- Enable *wireless access* for each department alongside wired PCs.
- Secure the network with *SSH remote login, port-security, and VLAN separation*.
- Automate IPv4 allocation using a *dedicated DHCP server*.
- Ensure redundancy and fault tolerance in inter-router and inter-switch connections.
**
## 🏢 Network Architecture
- *4 Floors* with dedicated routers and switches.
- *Departments & Devices*:
  - PCs, Printers, Access Points for each department.
  - Server Room with DHCP, HTTP, and Email servers.
- *Connectivity*:
  - One router per floor, connected to floor switches.
  - OSPF for inter-router communication.
  - VLANs for department isolation.

---

## 🖥 Technologies & Tools Used
- *Modeling Tools:* MS Visio, Draw.io
- *Simulation Software:* Cisco Packet Tracer, GNS3
- *Protocols & Services:* OSPF, DHCP, HTTP, Email, SSH
- *Security Configurations:* VLANs, Port-Security, Passwords, Banner Messages

---

## 🔧 Key Configurations
- *Routers & Switches*
  - Hostnames, line console, VTY passwords
  - Domain lookup disabled
  - OSPF routing enabled
- *VLANs*
  - Each department in a separate VLAN
  - Subnetting done using base network 192.168.10.0/24
- *Servers*
  - DHCP for IP allocation
  - HTTP & Email for client communication
- *End Devices*
  - Configured for dynamic IP addressing
- *Security*
  - SSH enabled for remote router login
  - Sticky MAC + shutdown violation for port security

---

## 📊 Final Implementation Snapshot
The final implementation connects *all departments across 4 floors* with:
- *Redundant inter-router connections*
- *Hierarchical topology*
- *Department-wise VLAN segmentation*
- *Centralized server room*
<img width="1498" height="710" alt="Screenshot 2025-09-03 133010" src="https://github.com/user-attachments/assets/80613991-a7e3-4329-8659-57a9f2d8a211" />
## ✅ Verification & Testing
- Devices in the *same VLAN communicate* successfully.
- Devices in *different VLANs communicate* via routing.
- Automatic IP allocation verified.
- Remote access via SSH tested.
- Redundancy tested by shutting down links.

---

## 📂 Documentation
All configurations, IP addressing plans, and VLAN mappings are documented for deployment and maintenance.

---

## 👨‍💻 Author
*Sachin Rana*  
- Cloud & Network Engineering Enthusiast  
- Skilled in Networking, Cisco Packet Tracer, GNS3, and Enterprise IT Solutions  

---

