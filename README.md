# Network Infrastructure Design for Sadakada Micro Finance Office

## 📌 Project Overview
This project demonstrates the design and implementation of a local area network (LAN) for **Sadakada Micro Finance Office**. It features a hybrid connectivity model combining wired and wireless solutions to ensure a reliable and secure networking environment for microfinance operations.

## 🖼️ Network Topology
![Network Topology Screenshot](Screenshot%202026-03-16%20010800.png)

## 🛠️ Technology Stack & Tools
* **Simulation Tool:** Cisco Packet Tracer 8.2
* **Network Topology:** Star Topology (Centralized Switch)
* **Addressing:** Static IPv4 Configuration

## 💻 Network Components
| Device | Role | IP Address |
| :--- | :--- | :--- |
| **Router (PT8200)** | Default Gateway | 192.168.1.1 |
| **Switch (2960-24TT)** | Central Connectivity | N/A |
| **Printer** | Network Resource | 192.168.1.10 |
| **Wireless Laptop** | Mobile Workstation | 192.168.1.5 |
| **Desktop PCs** | Workstations | 192.168.1.2, 1.3, 1.4 |

## ✅ Testing & Validation
Connectivity was successfully verified using **ICMP (Ping)** and PDU simulations.
* **Result:** Successful communication between Wireless Laptop and Network Printer.
* **Gateway Check:** All devices verified to reach the Default Gateway (192.168.1.1).
