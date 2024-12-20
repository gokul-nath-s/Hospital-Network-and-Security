# 🚀 Advanced Network Infrastructure Design for Melbourne Health Services 🌐 

![Project Banner](https://github.com/gokul-nath-s/Hospital-Network-and-Security/blob/7c10268040c85ffcf3a5af646ddca46455290a11/1.png)  
*A secure and scalable network design for a leading healthcare provider in Australia.*

This repository showcases a comprehensive network infrastructure design for **Melbourne Health Services**, a leading healthcare provider in Australia. The project aimed to design and implement a **secure, scalable, and cost-effective network** across two locations: the main headquarters and a branch hospital.

---

## 🏥 **Project Overview**
Melbourne Health Services decided to transition from third-party IT services to an **in-house network infrastructure** to better manage operations, enhance security, and ensure seamless communication between its departments and locations. This project adheres to the **CIA triad principles** (Confidentiality, Integrity, Availability) to protect sensitive healthcare data.

---

## 🎯 **Key Objectives**
- Establish **Local Area Networks (LANs)** for departmental operations.
- Implement a **Wide Area Network (WAN)** connecting headquarters and the branch hospital.
- Deploy a **dedicated server-side site** hosting DHCP, DNS, Web, and Email services.
- Ensure **secure communication** between sites using VPNs and Access Control Lists (ACLs).

---

## 📌 **Design Highlights**
- **Hierarchical Network Design**: Implemented a three-layer architecture (Core, Distribution, Access) for redundancy and scalability.
- **VLAN Configuration & Subnetting**: Created isolated VLANs and subnetworks for each department to optimize traffic and enhance security.
- **Dynamic & Static IP Addressing**: Configured DHCP servers for dynamic IP management and assigned static IPs to critical servers.
- **Wireless Networking**: Set up wireless networks for user mobility across all departments.
- **Inter-VLAN Routing**: Enabled inter-department communication via multilayer switches.
- **Secure Communication**: Established **IPSec VPN tunnels** for encrypted data transmission between sites.
- **Routing Protocols**: Configured **OSPF** for dynamic routing and **static routing** for efficient traffic flow.
- **Access Control & Port Security**: Applied extended ACLs and configured port security to restrict unauthorized access.
- **PAT Configuration**: Implemented Port Address Translation to optimize external traffic routing.

---

## 🛠️ **Tools & Technologies**
- **Cisco Packet Tracer**: Used for designing, configuring, and simulating the network infrastructure.
- **Routing and Switching**: Multilayer switches for inter-VLAN routing and routers for WAN connectivity.
- **Security Features**: SSH, ACLs, and port security for secure device management and access.

---

## 💡 **Key Outcomes**
- **Operational Efficiency**: Improved inter-departmental and inter-location communication.
- **Enhanced Security**: Ensured data protection and strict access control.
- **Scalability**: Designed a network ready to scale with organizational growth.
- **Skill Development**: Strengthened expertise in advanced networking, security, and performance optimization.

---

## 📊 **Network Requirements**
- **IP Addressing**: Subnetted the base network `192.168.100.0/24` to allocate IPs for all departments.
- **Hardware**: Core routers, multilayer switches, and access switches per location.
- **Security**: Extended ACLs, SSH for secure remote access, and port security using the sticky method.
- **Connectivity**: Serial connections between HQ and Branch, and PAT for ISP connections.
- **Dynamic Routing**: OSPF protocol for optimal routing and performance.

---

## 🔍 **Project Testing**
- Ensured all devices in the network communicated effectively.
- Verified VPN tunnels and encrypted communication.
- Tested IP allocation via DHCP and static IPs for servers.
- Validated routing tables for OSPF and static routing configurations.
- Checked access restrictions with ACLs and port security.

---

## 📥 **Get Started**
1. Clone the repository.
2. Open the `.pkt` file in **Cisco Packet Tracer**.
3. Explore configurations, test network connectivity, or make modifications to simulate various scenarios.

---

## 🤝 **Connect**
🌟 Check out my [LinkedIn Profile](https://www.linkedin.com/in/gokulnath-s2004/) for more details about my work and other exciting projects!  

---

**Tags**: `Networking`, `Cisco Packet Tracer`, `VLAN`, `OSPF`, `Access Control Lists`, `VPN`, `Port Security`, `Healthcare IT`

