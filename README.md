# 🌐 Multi-Floor Hotel Network Design (Cisco Packet Tracer)

## 📌 Overview

This project demonstrates the design and implementation of a **multi-floor hotel network** using Cisco Packet Tracer.
The network is segmented using VLANs and supports inter-VLAN communication, dynamic routing, wireless connectivity, and network security features.

A complete detailed report with configurations, outputs, and explanations is included in this repository.

---

## 🛠️ Technologies & Concepts Used

* VLAN (Virtual LAN)
* Inter-VLAN Routing (Router-on-a-Stick)
* DHCP (Dynamic Host Configuration Protocol)
* OSPF (Open Shortest Path First)
* SSH (Secure Remote Access)
* Port Security
* Wireless Networking (Access Points)
* Trunking (802.1Q)

---

## 🧱 Network Architecture

* 3 Floors (each with its own router and switch)
* Multiple departments per floor using VLAN segmentation
* Routers interconnected using serial links (/30 networks)
* Wireless access points for mobile connectivity
* Centralized routing using OSPF

---

## 🏢 VLAN & Department Mapping

### First Floor

* VLAN 80 → Reception → 192.168.8.0/24
* VLAN 70 → Store → 192.168.7.0/24
* VLAN 60 → Logistics → 192.168.6.0/24

### Second Floor

* VLAN 50 → Finance → 192.168.5.0/24
* VLAN 40 → HR → 192.168.4.0/24
* VLAN 30 → Sales → 192.168.3.0/24

### Third Floor

* VLAN 20 → Admin → 192.168.2.0/24
* VLAN 10 → IT → 192.168.1.0/24

---

## ⚙️ Features Implemented

### 🔹 VLAN Segmentation

Logical separation of departments for improved security and efficiency.

### 🔹 Inter-VLAN Routing

Router-on-a-stick configuration using subinterfaces for communication between VLANs.

### 🔹 DHCP

Automatic IP address assignment using separate DHCP pools for each VLAN.

### 🔹 OSPF Routing

Dynamic routing between routers using OSPF (Area 0).

### 🔹 SSH Access

Secure remote login to routers using encrypted communication.

### 🔹 Port Security

Restricts unauthorized devices using sticky MAC addresses.

### 🔹 Wireless Connectivity

Access Points configured with SSID and security for mobile devices.

---

## 📄 Detailed Report

A complete implementation report with configurations, screenshots, and verification steps is included:

👉 **[View Full Report](./Report.pdf)**

---

## 📁 Project Structure

```
multi-floor-network-design-vlan-ospf-dhcp/
│
├── Network-Design-Project.pkt
├── Report.pdf
├── README.md
```

---

## 🚀 How to Run

1. Open the `.pkt` file using Cisco Packet Tracer
2. Switch to simulation or real-time mode
3. Test connectivity using ping between devices
4. Verify routing:

   ```
   show ip route
   ```
5. Verify OSPF:

   ```
   show ip ospf neighbor
   ```

---

## 🧪 Verification

* ✅ Inter-VLAN communication successful
* ✅ Inter-floor communication via OSPF
* ✅ DHCP assigns correct IP addresses
* ✅ Routing tables populated with OSPF routes
* ✅ Wireless devices connected successfully
* ✅ SSH login working
* ✅ Port security enforced

---

## 🎯 Learning Outcomes

* Practical understanding of VLAN-based network segmentation
* Implementation of dynamic routing using OSPF
* Configuration of enterprise network services
* Hands-on experience with Cisco Packet Tracer

---

## 📌 Conclusion

A scalable and secure multi-floor network was successfully designed and implemented.
All devices across VLANs and floors can communicate efficiently, demonstrating real-world enterprise networking concepts.

---

## 👨‍💻 Author

**Aneesh Suvarna**
