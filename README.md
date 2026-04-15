# 🔐 Network Security Implementation (Cisco Packet Tracer)

This project demonstrates the implementation of a secure network using Cisco Packet Tracer. It includes routing, secure remote access, access control, firewall configuration, and network monitoring.

---

## 📌 Project Overview

The network consists of three routers (R1, R2, R3), two switches, and end devices (PC-A, PC-C, and a Syslog Server). The network is configured to ensure secure communication and controlled access between internal and external networks.

---

## 🧱 Network Topology

- R1, R2, R3 connected via serial links
- PC-A → Internal network (192.168.1.0/24)
- PC-C → External/Management network (192.168.3.0/24)
- Syslog Server → 192.168.1.3

---

## ⚙️ Implemented Tasks

### ✅ Task 1: Basic Network Configuration
- IP addressing for all devices
- OSPF routing configuration
- Connectivity testing between hosts

---

### 🔐 Task 2: Router Security
- Password protection (console, VTY, enable secret)
- SSH configuration for secure remote access
- Login banner configuration

**Credentials:**
- Username: `admin`
- Password: `admin123`
- Enable Secret: `class`
- Console/VTY Password: `cisco`

---

### 🔒 Task 3: VPN (Conceptual)
- IPSec VPN configuration between R1 and R3
- Secure communication between internal networks
- Note: Limited support in Packet Tracer

---

### 🛡️ Task 4: Access Control (ACL)
- Only PC-C (192.168.3.2) allowed to access routers
- All other devices blocked

---

### 🔥 Task 5: Firewall Implementation
- ACL used to simulate firewall behavior
- Internal traffic allowed
- External traffic restricted

> ⚠️ Note: Zone-Based Firewall (ZPF) is not supported in Packet Tracer, so ACL is used instead.

---

### 📊 Task 6: Network Monitoring (Syslog)
- Syslog server configured (192.168.1.3)
- Router logs sent to server
- Real-time logging and monitoring enabled

> ⚠️ Note: IPS is not fully supported in Packet Tracer. Syslog is used to simulate monitoring.

---

## 🧪 Testing & Verification

- Successful ping between PC-A and PC-C
- SSH access only allowed from PC-C
- Firewall rules verified
- Logs successfully generated and captured in Syslog server

---

## 📁 Files Included

- `1.pkt` → Cisco Packet Tracer file
- `Lab_Report.docx` → Detailed lab report
- Screenshots of configuration and testing

---

## 🚀 Key Learning Outcomes

- Network configuration using OSPF
- Secure device access using SSH
- Implementing ACL for access control
- Firewall concepts using ACL
- Network monitoring using Syslog

---

## 📝 Notes

Due to limitations of Cisco Packet Tracer:
- IPS and ZPF could not be fully implemented
- Alternative solutions (ACL & Syslog) were used

---
