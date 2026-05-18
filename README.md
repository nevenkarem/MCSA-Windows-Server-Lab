# 🖥️ MCSA Windows Server Lab

## 📌 Project Overview
This project demonstrates a complete Windows Server lab environment built using Virtual Machines.  
The lab simulates a small enterprise network with a Domain Controller, Active Directory, DHCP, Group Policy, File Server, and a Windows 10 client joined to the domain.

---

## 🖥️ Lab Environment
- Windows Server (Domain Controller)  
- Windows 10 Client Machine  
- Virtual Machine (VMware Workstation)  

---

## ⚙️ Services Implemented

### 1️⃣ Active Directory Domain Services (AD DS)
- Installed and configured Domain Controller (PDC19)  
- Created Organizational Units (OUs)  
- Created Domain Users and Groups  

### 2️⃣ Group Policy Management (GPO)
- Configured Password Policy  
- Applied User Restrictions  
- Managed domain policies using Group Policy Management Console (GPMC)  

### 3️⃣ DHCP Server
- Configured DHCP Scope  
- Configured IP Address Pool  
- Verified Address Leases  

### 4️⃣ File Server & Shared Folder
- Created shared folder on server  
- Configured NTFS Permissions  
- Configured Share Permissions  
- Tested access from client machine  

### 5️⃣ Domain Join
- Joined Windows 10 machine to the domain  
- Verified connectivity using ping and domain login  

---

## 🧪 Network Scenario
- **Domain Name:** test.local  
- **Server IP:** 192.168.1.2  
- **Client Machine:** Windows 10 joined to domain  

---

## 📷 Screenshots

### 🖥️ Server Manager Dashboard
![Server Manager](Project%20MCSA/01-server-manager-dashboard.png)

### 👥 Active Directory Users & Computers
![AD Users](Project%20MCSA/02-active-directory-users.png)

### ⚙️ Group Policy Management
![GPO](Project%20MCSA/03-group-policy-management.png)

### 🌐 DHCP Address Pool
![DHCP Pool](Project%20MCSA/04-dhcp-address-pool.png)

### 📊 DHCP Address Leases
![DHCP Leases](Project%20MCSA/05-dhcp-address-leases.png)

### 📁 Shared Folder
![Shared Folder](Project%20MCSA/06-Shared-Folder-Sharing.png)

### 🔐 NTFS Permissions
![Permissions](Project%20MCSA/07-Security-Permissions.png)

### 🖥️ Access Shared Folder from Client
![Client Access](Project%20MCSA/08-Access-PDC19-Public-Share.png)

### 💻 Windows 10 Joined to Domain
![Domain Join](Project%20MCSA/09-Windows10-Joined-to-Domain.png)

### 📡 Client Ping Domain Controller
![Ping Test](Project%20MCSA/10-Client-Ping-Domain-Controller.png)
---

## 🎯 Skills Demonstrated
- Active Directory Administration  
- Group Policy Configuration  
- DHCP Management  
- File Server Management  
- Domain Networking  
- Windows Server Administration
- ---

## Project Structure

- **Windows Server:** Windows Server 2019  
- **Client OS:** Windows 10  
- **Virtualization:** VMware Workstation  
- **Domain Name:** test.local
- ---

## Conclusion

This project simulates a real corporate IT environment
using Windows Server and Active Directory.
It demonstrates the core skills required for IT Support roles.
