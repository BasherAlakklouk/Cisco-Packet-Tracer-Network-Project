# Cisco-Packet-Tracer-Network-Project
Cisco Packet Tracer Network Topology Project - UCAS University
# Complex Enterprise Network Topology & Subnetting 🌐

A multi-router enterprise network design and implementation developed as a **University Project** at the **University College of Applied Sciences (UCAS)** for the Computer Networking course.

---

## 📊 Network Topology Overview

![Enterprise Network Topology](Screenshot%202026-10-14%20144055.png)

The network is structured into 4 main operational zones:
1. **Dev Department**: Dedicated subnet for development workstations with DHCP and VLAN segmentations.
2. **Sales Department**: Dedicated subnet for sales teams.
3. **HR Department**: Secure subnet allocated for Human Resources.
4. **Core Router & Data Center**: Centralized region housing core enterprise servers:
   - **Web Server** (`Web-Server`)
   - **FTP File Server** (`FTP-Server`)
   - **DNS Server** (`DNS-Server`)

---

## 🛠️ Key Features & Configurations

- **IP Addressing & Subnetting**: Custom VLSM / Subnetting scheme designed to optimize address allocation across departments (documentation provided in Word format).
- **Inter-Department Routing**: Serial WAN links connecting department routers to `CORE-R1`.
- **Infrastructure Services**:
  - Centralized **DNS** resolution for internal servers.
  - **HTTP/Web** and **FTP** service setup.
  - Dynamic IP allocation via **DHCP**.
- **Network Security**: Configured Access Control Lists (ACLs) for traffic isolation between departments and secure access control to core servers.

---

## 📂 Included Artifacts

- `BasherAlakklouk_120251001.pkt` - Cisco Packet Tracer configuration file.
- `Final Project.docx` - Full IP Addressing breakdown & Subnet calculations.
- `Screenshot 2026-10-14 144055.png` - Visual architecture preview.

---

## 🏛️ Academic Context
- **Institution:** University College of Applied Sciences (UCAS)[cite: 1]
- **Major:** Cybersecurity Engineering[cite: 1]
