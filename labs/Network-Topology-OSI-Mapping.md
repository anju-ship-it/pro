# Lab: Network Topology Design (Star / Hub-and-Spoke)
# Lab: Network Topology Design (Star / Hub-and-Spoke)
![Network Diagram](topology_network.jpg)
4. Save
## 🎯 Overview
For this lab, I designed a star topology using a central switch and multiple end devices. A star topology connects each device to a single central forwarding appliance, making it easy to manage and troubleshoot.

## 🏗️ Topology Components
* **1 Central Switch:** (Mktg_Switch)
* **5 End Devices:** (Mktg1–Mktg5)
* **Media:** Ethernet connections from each device to the switch

## 📝 Topology Description
Each Marketing workstation (Mktg1–Mktg5) is connected directly to the central switch using Ethernet cables. No devices are connected to each other directly. This forms a classic **hub-and-spoke** layout.

### Why this is a star topology:
* **Centralization:** All devices connect to one central switch.
* **Dedicated Links:** Each device has its own dedicated physical link.
* **Fault Tolerance:** Removing or damaging one cable affects only that specific device, not the entire network.

---

## 📊 OSI Layer Reference Chart
| OSI Layer | Common Devices | Protocols |
| :--- | :--- | :--- |
| **7: Application** | Gateway, PC Workstation | HTTP, DNS |
| **6: Presentation** | Gateway, PC Workstation | SSL/TLS, JPEG |
| **5: Session** | Gateway, Server | NetBIOS, RPC |
| **4: Transport** | Firewall, Load Balancer | TCP, UDP |
| **3: Network** | Router, Layer 3 Switch | IPv4, IPv6, ICMP |
| **2: Data Link** | Switch, Bridge | Ethernet, ARP |
| **1: Physical** | Hub, Modem | 1000Base-T, Fiber |
