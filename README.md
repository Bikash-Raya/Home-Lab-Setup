<div align="center">

# 🏠 Home Lab – Windows Server, Active Directory, Windows 11 & Linux Integration

### VMware Workstation Enterprise Lab Simulation

![Domain](https://img.shields.io/badge/Domain-BIKSEC.com-blue?style=for-the-badge)
![Infrastructure](https://img.shields.io/badge/Infrastructure-Windows%20%26%20Linux-green?style=for-the-badge)
![Virtualization](https://img.shields.io/badge/Platform-VMware%20Workstation-orange?style=for-the-badge)

<img src="https://img.shields.io/badge/Active%20Directory-AD%20DS-green?style=flat-square" />
<img src="https://img.shields.io/badge/DNS-Windows%20DNS-blue?style=flat-square" />
<img src="https://img.shields.io/badge/Linux-Kali%20Linux-red?style=flat-square" />
<img src="https://img.shields.io/badge/Networking-VMware%20NAT-orange?style=flat-square" />

---

**Prepared by:** Bikash Raya
**Project Type:** Home Lab Infrastructure & System Administration

</div>

---

## 📋 Overview

This repository documents the design and implementation of a home lab environment built using VMware Workstation.

The lab simulates a small internal network consisting of:

* 🖥️ Windows Server 2022 Domain Controller
* 🌐 Windows Server 2022 Internal Web Server
* 💻 Windows 11 Workstation
* 🐧 Kali Linux System
* 🔐 Active Directory Domain Services (AD DS)
* 📡 DNS Services
* 🌍 VMware NAT Networking

---

## 🛠️ Technologies Used

* VMware Workstation
* Windows Server 2022
* Windows 11
* Kali Linux
* Active Directory Domain Services (AD DS)
* DNS
* PowerShell
* Linux CLI (nmcli)

---

## 🧪 Lab Components

| System       | Role                      |
| ------------ | ------------------------- |
| BIKSEC-DC01  | Domain Controller + DNS   |
| BIKSEC-WEB01 | Internal Web Server       |
| BIKSEC-WIN11 | Domain Joined Workstation |
| BIKSEC-Linux | Kali Linux Testing System |

---

## 🌐 Network Configuration

| Setting      | Value           |
| ------------ | --------------- |
| Network Type | VMware NAT      |
| Subnet       | 192.168.49.0/24 |
| Gateway      | 192.168.49.2    |
| DNS Server   | 192.168.49.10   |

---

## 🔐 Active Directory Environment

* Installed Active Directory Domain Services (AD DS)
* Configured DNS services
* Promoted server to Domain Controller
* Created domain: **BIKSEC.com**
* Joined Windows systems to the domain

---

## 🖥️ System Deployment

### Domain Controller (BIKSEC-DC01)

* Windows Server 2022
* Static IP configuration
* Active Directory installation
* DNS configuration

### Web Server (BIKSEC-WEB01)

* Windows Server 2022
* Static IP configuration
* Domain joined system

### Windows Workstation (BIKSEC-WIN11)

* Windows 11 deployment
* System configuration
* Domain join

### Linux System (BIKSEC-Linux)

* Kali Linux deployment
* Static IP configuration using nmcli
* Network connectivity testing

---

## 🛡️ Troubleshooting & Validation

### Issues Encountered

#### ICMP Blocked on Windows Servers

* Windows Defender Firewall blocked ping requests
* Enabled ICMP Echo Request rules using PowerShell

#### Static IP Configuration Errors

* Incorrect gateway and DNS settings
* Standardized network configuration across systems

#### Linux Connectivity Issue

* Windows Firewall blocked responses
* Modified firewall configuration to allow ICMP traffic

### Validation Performed

* Verified DNS resolution
* Tested inter-machine connectivity
* Confirmed successful domain joins
* Validated Linux-to-Windows communication

---

## 🎯 Skills Demonstrated

* Active Directory Administration
* DNS Configuration
* Windows Server Administration
* Windows 11 Deployment
* Linux Network Administration
* VMware Virtualization
* Network Troubleshooting
* Firewall Management
* Domain-Based Authentication
* Cross-Platform Connectivity Testing

---

## 📁 Repository Structure

| File                | Description                    |
| ------------------- | ------------------------------ |
| [Home-Lab-Report.pdf](https://github.com/Bikash-Raya/Home-Lab-Setup/blob/main/Home-Lab-Report.pdf) | Complete project documentation |
| README.md           | Project overview               |

---

## 🎯 Key Takeaway

> This project demonstrates practical experience in deploying and managing a Windows-based Active Directory environment, integrating Windows and Linux systems, configuring DNS services, troubleshooting network connectivity issues, and administering virtualized infrastructure using VMware Workstation.

---

## 🔗 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge\&logo=linkedin)](https://www.linkedin.com/in/bikash-raya/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge\&logo=github)](https://github.com/Bikash-Raya)

</div>

---

<div align="center">

⭐ If you like this project, feel free to star the repository ⭐

</div>
