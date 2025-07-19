# 📡 Design and Simulation of Hierarchical Enterprise Network

A comprehensive enterprise network designed and simulated using Cisco Packet Tracer, implementing a scalable hierarchical architecture with OSPF routing and efficient IP addressing to ensure robust connectivity and optimized data flow.

---

## 📘 Project Overview

This project presents the complete design, configuration, and validation of a hierarchical enterprise network topology. It uses **Class A IP addressing** and **Open Shortest Path First (OSPF)** as the dynamic routing protocol to establish seamless communication between multiple segments. All configurations are performed in **Cisco Packet Tracer** with a focus on modularity, performance, and scalability.

---

## ⚙️ Technologies Used

- Cisco Packet Tracer
- Cisco 2620XM Routers / 2960-24TT Switch
- Fast Ethernet Interfaces
- IPv4 Addressing (Class A)
- OSPF (Routing Protocol)

---

## 🧩 Network Features

- Core-Distribution-Access Layer Architecture
- 20+ Network Segments
- /30 Subnetting for Point-to-Point Links
- /24 Subnetting for LANs
- OSPF Area 0 Configuration
- Full end-to-end connectivity verified using Ping tests

---

## 🖧 Network Topology Summary

| Device Role        | Device Name       |
|--------------------|------------------|
| Edge Router        | Router0          |
| Access Routers     | access router 1–4 |
| Distribution Routers| dist router 1–4  |
| Core Routers       | core router 1–2  |
| End Devices        | PC0 – PC9         |
| VLAN-aware Switch  | Switch0          |

---



## 🏗️ Installation & Usage

1. **Install Cisco Packet Tracer**
   - [Download from Cisco](https://www.netacad.com/courses/packet-tracer)
   - Ensure you're logged in to your Cisco Networking Academy account

2. **Open the `.pkt` File**
   - Clone this repository or download the project files
   - Open the network simulation file in Cisco Packet Tracer

3. **Run the Simulation**
   - Observe connectivity
   - Verify configuration
   - Test ping between devices

---

## 📈 Ping Results

- All devices configured successfully
- Bidirectional communication verified
- OSPF routing confirmed active across all routers

---

## ✅ Conclusion

This project demonstrates the end-to-end deployment of a complex enterprise network with dynamic routing, structured addressing, and hierarchical design. By combining efficient subnetting and the OSPF protocol, we achieved a scalable and highly connected network suitable for real-world enterprise environments.

---

## 🔮 Future Improvements

- Implement redundancy using HSRP/VRRP
- Add wireless and cloud services
- Introduce ACLs and VLAN segmentation
- Simulate network security and monitoring tools

---
