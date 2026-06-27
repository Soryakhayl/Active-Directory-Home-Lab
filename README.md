# Enterprise Active Directory Home Lab

## Project Overview

This project documents the process of building an enterprise-style Active Directory home lab using Oracle VirtualBox and Windows Server 2022.

## Project Objectives

- Build a Windows Server 2022 Domain Controller
- Configure Active Directory Domain Services
- Configure DNS
- Configure DHCP
- Join a Windows 11 client to the domain
- Create users, groups, and Group Policy Objects
- Document the full process with screenshots

## Technologies Used

- Oracle VirtualBox
- Windows Server 2022
- Windows 11
- Active Directory Domain Services
- DNS
- DHCP
- Group Policy
- PowerShell

## Phase 1: Windows Server Setup

In this phase, I created the Windows Server 2022 virtual machine named DC01 in VirtualBox. I assigned 6 GB of RAM and 2 CPUs, installed Windows Server 2022, and configured a static IP address for the domain controller.

## Screenshots

- `02-DC01-VM-Created.png`
- `03-Windows-Server-Desktop-Loaded.png`
- `04-DC01-Static-IP.png`
- `05-Verify-Static-IP-ipconfig.png`
- `06-ADDS-Installation-Progress.png`

## Current Progress

- [x] Created GitHub repository
- [x] Installed Windows Server 2022
- [x] Configured static IP
- [x] Started Active Directory Domain Services installation
- [ ] Promoted server to Domain Controller
- [ ] Configured DNS
- [ ] Configured DHCP
- [ ] Joined Windows 11 client
