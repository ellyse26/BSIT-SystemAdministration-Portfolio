# 🖥️ Enterprise Infrastructure Plan
### ABC Startup Solutions

> **ITEP 414 – System Administration and Maintenance**  
> **Bachelor of Science in Information Technology**  
> **Prepared by:** Janelle M. Clemeno  
> **Date:** August 14, 2026

---

## 📌 Project Overview

This project presents an **Enterprise Infrastructure Plan** designed for ABC Startup Solutions, a fictional technology company based in Santa Cruz, Laguna, Philippines. The plan focuses on designing a reliable, secure, organized, and scalable IT infrastructure that can support the company's 20 employees and its four main departments.

The project covers the company's hardware and software requirements, network infrastructure, system administration roles, security recommendations, backup strategies, and future expansion plans.

---

## 🏢 Company Profile

**ABC Startup Solutions** is an emerging technology company that provides software development and IT services to support organizational operations.

### Departments

| Department | Employees | Main Function |
|------------|-----------|---------------|
| 💻 IT | 5 | Systems, development, and technical infrastructure |
| 👥 Human Resources | 4 | Employee records and administration |
| 💰 Finance | 5 | Financial records and reporting |
| 📈 Sales | 6 | Customer and sales operations |
| **Total** | **20** | |

---

## 🖥️ Hardware Infrastructure

The proposed infrastructure provides each employee with a dedicated workstation while also supporting administration, development, networking, storage, and backup requirements.

### Main Hardware

- 20 Desktop Computers
- 4 Laptops
- 1 Dedicated Server
- 1 NAS Storage System
- 1 Network Printer
- 1 Router
- 1 Managed Network Switch
- 3 Wireless Access Points
- 1 ISP Modem
- 1 Firewall
- Patch Panel
- CAT6 Ethernet Cables
- RJ45 Connectors
- 5 UPS Units
- 2 External Backup Drives

The hardware inventory is designed to provide the company with the equipment needed for daily operations while allowing the infrastructure to support future growth.

---

## 💿 Software Infrastructure

The software environment includes operating systems, productivity applications, development tools, security software, and system administration utilities.

### Main Software

| Software | Purpose |
|----------|---------|
| Windows 11 Pro | Operating system for company computers |
| Ubuntu Server | Server operating system |
| Microsoft 365 | Documents, spreadsheets, presentations, and office work |
| Visual Studio Code | Software development and programming |
| Git | Version control |
| GitHub Desktop | Graphical Git repository management |
| VirtualBox | Virtual machine management |
| Google Chrome | Web browsing and online applications |
| Microsoft Defender | Malware and endpoint protection |
| AnyDesk | Remote technical support |
| 7-Zip | File compression and extraction |

---

## 🌐 Enterprise Network Diagram

The network follows a **hierarchical star topology**, with the core switch serving as the central connection point for the company's internal network. Internet traffic passes through the ISP modem, router, and firewall before reaching the core switch, providing controlled access to the internal network. The core switch connects the Ubuntu server, NAS storage, network printer, wireless access points, and the four department networks. This design provides a structured network that is easier to manage, troubleshoot, and expand as ABC Startup Solutions grows.

### Network Diagram

![ABC Startup Solutions Enterprise Network Diagram](Diagrams/Network_Topology.drawio.png)

**Figure 1.** ABC Startup Solutions – Enterprise Network Diagram


### 👨‍💻 System Administration Roles

The infrastructure identifies four important system administration roles that work together to maintain the company's IT environment.

#### Helpdesk Technician

The Helpdesk Technician provides technical assistance to employees and handles common computer, software, and IT-related problems. The role focuses on resolving user issues, assisting with troubleshooting, installing or configuring software, and documenting technical concerns.

#### Network Administrator

The Network Administrator manages the company's network infrastructure, including routers, switches, firewalls, wireless access points, and network connectivity. The role ensures that the company's network remains reliable, secure, and available to employees.

#### Linux System Administrator

The Linux System Administrator manages the company's Linux-based server environment. The role includes configuring the server, managing user permissions, installing updates, monitoring system performance, troubleshooting problems, and maintaining server security.

#### Cloud Administrator

The Cloud Administrator manages cloud-based services and resources used by the organization. The role includes managing cloud storage, virtual machines, user access, cloud configurations, and security settings.

Together, these professionals help maintain a reliable, secure, and efficient IT environment.

### 🔐 Infrastructure Recommendations
#### 🌐 Internet Provider

ABC Startup Solutions should use a reliable business fiber internet connection to support cloud services, online applications, email, communication, and other daily business operations.

#### 🖥️ Server Specifications

A dedicated Ubuntu Server with sufficient processing power, RAM, and SSD storage is recommended to support centralized services and company resources.

#### 💾 Backup Strategy

The company should maintain multiple copies of important data using NAS storage and external backup drives. Regular backups help protect company information from accidental deletion, hardware failure, malware, and other forms of data loss.

#### 🔒 Security Recommendations

The company should use a firewall, secure network configuration, software updates, access controls, endpoint protection, and employee security awareness to reduce security risks.

#### 🛡️ Antivirus

Microsoft Defender is recommended for Windows computers to provide protection against malware, viruses, and other common security threats. Security updates should also be kept current.

#### 🔑 Password Policy

Employees should use strong and unique passwords and avoid sharing their account credentials. Multi-factor authentication should also be enabled for important accounts whenever available.

#### 📈 Expansion Plan

The infrastructure is designed with future growth in mind. Additional network capacity, storage, computing resources, and wireless coverage can be added as the company expands.

### 💭 Personal Reflection

This project helped me understand that system administration involves more than simply managing computers and software. Proper planning is necessary to ensure that an organization's hardware, software, network, security, backup, and future expansion requirements are properly considered.

One of the most challenging parts of the project was designing the enterprise network because I needed to understand how different devices and departments should connect. Creating the network diagram helped me visualize how the Internet, network security devices, servers, storage, wireless access points, and departments work together.

Overall, this project improved my understanding of enterprise infrastructure planning and gave me practical experience that can help me become a better System Administrator in the future.
