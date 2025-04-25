# 🏭 Industrial Network Infrastructure: Resilient Multi-Building Factory Network

This project showcases the design and implementation of a **robust industrial network infrastructure** using Cisco Packet Tracer. Built with a focus on **high availability**, **security**, and **performance optimization**, the network simulates a multi-building factory setup with departmental segmentation and enterprise-grade redundancy.

---

## 📌 Project Overview

The network topology connects several factory departments through a **diamond-shaped core design** with redundant links for fault tolerance and load balancing. Each department is isolated using VLANs and subnetting to ensure efficient traffic management and security.

### 🏢 Departmental Segmentation
- 🔵 **Quality Control Department**
- 🔴 **Main Production Floor**
- 🔧 **Maintenance and Technical Support**
- 🟠 **Management and Planning Department**

---

## ⚙️ Technical Highlights

### 🔹 Network Foundation
- **Subnetting**: Logical IP segmentation for clean traffic separation
- **VLANs**: Dedicated VLANs per department
- **VTP**: Centralized VLAN management across the switch network

### 🔹 High Availability & Redundancy
- **PVST+ / Rapid-PVST+**: Per-VLAN Spanning Tree for optimal path convergence
- **Link Aggregation (LACP/PAgP)**: EtherChannels for increased bandwidth and failover
- **Loop Prevention**: BPDU Guard, BPDU Filter, and Loop Guard for STP protection
- **Root Guard**: Prevents unauthorized STP topology changes

### 🔹 Network Security
- **Port Security**: Limits MAC addresses per port to prevent rogue device access
- **Storm Control**: Protects against broadcast and multicast storms
- **UDLD**: Detects unidirectional link failures before they cause problems

### 🔹 Network Optimization
- **PortFast**: Accelerates workstation recovery
- **LLDP/CDP**: Neighbor discovery for easier troubleshooting
- **NTP**: Ensures time sync across all devices for accurate logging
- **Syslog**: Centralized logging for network event tracking

---

## 🗂️ Files Included

- `Resilient_Industrial_Network_Implementation.pkt` – Cisco Packet Tracer project file  
- `README.md` – Project documentation and technical overview

---

## 🎯 Key Takeaways

This project is ideal for understanding how to:
- Design scalable, secure industrial networks
- Apply real-world Cisco technologies in simulated environments
- Build high-performance Layer 2 topologies for critical infrastructure

---


---

## 📫 Contact

If you’re hiring for roles in **network engineering**, **infrastructure design**, or **industrial IT**, feel free to connect!

📧 onemanvan41@gmail.com 
💼 [[LinkedIn Profile Link]  ](https://www.linkedin.com/in/abdallah-mohamed-67a639265/)
