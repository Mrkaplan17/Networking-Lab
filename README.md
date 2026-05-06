# 🖧 Networking Lab: Small Office Enterprise Network

## 📌 Overview

This project simulates a **small office enterprise network** designed using Cisco Packet Tracer. It demonstrates core networking concepts such as redundancy, segmentation, and centralized services.

The network includes multiple departments, dedicated servers, and redundant routing to ensure reliability and scalability.

---

## 🎯 Objectives

* Design a structured enterprise network
* Implement **redundancy** using dual routers (MAIN & BACKUP)
* Segment departments using switches
* Configure essential network services (DHCP, DNS, HTTP)
* Simulate real-world office communication

---

## 🏗️ Network Architecture

🔹 Core Components

* **ISP Connection**
* **2 Routers (2911)**

  * MAIN Router
  * BACKUP Router (failover simulation)
* **Access Switch (2960)**
* **Server Switch**
* **Departmental Switches**

---

### 🏢 Departments

* **HR Department**
* **Finance Department**
* **IT/Admin**
* **CEO Office**

Each department is connected via dedicated switches to improve organization and scalability.

---

### 🖥️ Servers

* **DHCP Server** – Automatic IP assignment
* **DNS Server** – Name resolution
* **HTTP Server** – Web service simulation

---

### 🖨️ Devices

* Multiple client PCs across departments
* Network printer for CEO office

---

## ⚙️ Key Features

### 🔁 Redundancy

* Dual-router setup (MAIN & BACKUP)
* Ensures network availability if one router fails

### 🌐 Network Services

* DHCP for automated IP configuration
* DNS for domain name resolution
* HTTP server for internal web access

### 🧩 Scalability

* Modular switch design per department
* Easy to expand with additional devices

---

## 🧪 What I Learned

* Designing structured network topology
* Importance of redundancy in networks
* Role of centralized services (DHCP, DNS)
* Basic enterprise network layout

---

## 📷 Topology

![Network Topology](topology.png)

---

## 📂 Files Included

* `network.pkt` – Cisco Packet Tracer file
* `topology.png` – Network diagram screenshot
* `configs/` – (optional) device configurations

---

## 🚀 Future Improvements

* Implement VLAN segmentation
* Add Inter-VLAN routing
* Configure ACLs for security
* Simulate real failover testing
* Add monitoring tools (e.g., SNMP)

---

## 👨‍💻 Author

**Billy Alcayaga**
Aspiring Network Engineer / IT Support

---

## 📬 Notes

This project is part of my networking portfolio to demonstrate hands-on skills for entry-level IT and networking roles.
