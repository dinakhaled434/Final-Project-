# CCNA Final Project

# Topology Diagram
<img width="1518" height="700" alt="topology" src="https://github.com/user-attachments/assets/a811692c-32d3-440a-ac4b-f3e9f011df78" />

## 🧩 Overview

This project represents an enterprise-style network scenario designed to demonstrate core CCNA concepts in routing, switching, services, and security.

The network consists of multiple routers and switches connecting several VLANs and server segments. End devices are logically separated into VLANs based on function, while centralized services are provided through dedicated servers.

The overall scenario works as follows:
- End devices are placed in different VLANs and receive their network settings dynamically through DHCP.
- Inter-VLAN communication is enabled using routing, allowing controlled connectivity between VLANs.
- Dynamic routing (EIGRP) is used between routers to exchange routes efficiently, with default routing applied where required.
- Route redistribution is implemented to ensure full reachability between different routing domains.

From a services and access perspective:
- All users can access core network services such as DHCP.
- DNS services are restricted for specific hosts as part of access control policies.
- Certain VLANs or networks are restricted from accessing the Web Server.
- Mail services are controlled, preventing specific VLANs from accessing the Mail Server.

Security and management considerations include:
- Secure remote device management using SSH only.
- Centralized user authentication through a RADIUS server.
- Traffic control and service restrictions enforced using Access Control Lists (ACLs).

This scenario simulates a realistic enterprise environment where availability, segmentation, routing control, and security policies are all applied together.

## 🎯 Project Objectives

- Design an enterprise-style network topology
- Apply core CCNA routing and switching concepts
- Implement basic network services and security controls
- Gain hands-on experience with troubleshooting and logical network design

## 🖧 Network Components

### 📡 Network Devices
- Routers
- Layer 2 Switches
- Wireless Access Points
- End-user devices (wired and wireless clients)

### 🖥️ Servers
- DHCP Server
- DNS Server
- Web Server
- Mail Server
- RADIUS Server

### 🌐 Routing & Switching (R&S)
- VLAN creation and interface assignment
- Inter-VLAN routing concepts
- Rapid Spanning Tree Protocol (RSTP)
- Dynamic routing using EIGRP
- Default routing between routers
- Route Redistribution between routing domains

### 🔐 Security
- Secure device access using SSH (VTY only)
- Centralized authentication using RADIUS
- Password encryption and basic device hardening
- Access Control Lists (ACLs) for traffic filtering
- Service-based access restrictions (DNS, Web, Mail)

## ✅ What This Project Demonstrates

- Solid understanding of CCNA fundamentals
- Ability to design and explain network architectures
- Applying security and access control concepts
- Structured thinking and documentation skills

## 🛠️ Tools Used

- Cisco Packet Tracer

## 👤 Author

 Dina Khaled Mohamed 👩🏻‍💻
