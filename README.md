# Windows Server & Active Directory Home Lab

## Overview
I built a functional Active Directory environment on Azure to learn enterprise Windows infrastructure management and systems administration.

## Architecture
- 1 Domain Controller (Windows Server 2022 Datacenter on Azure B2s VM)
- Domain Name: company.local
- Hosted on Microsoft Azure

## What I've Set Up

### Active Directory Structure
- Created a new AD forest with domain "company.local"
- Established Organizational Unit (OU) structure for IT Department

### Users Created
- testuser1 (IT Department)
- testuser2 (IT Department)
- testuser3 (IT Department)
- salesuser1 (Sales Department)
- salesuser2 (Sales Department)
- financeuser1 (Finance Department)
- financeuser2 (Finance Department)

### Groups Created
- IT Staff (security group containing testuser1 and testuser2)

### Key Configuration
- Promoted Windows Server 2022 to Domain Controller
- Installed Active Directory Domain Services
- Configured DNS for domain

## Skills Demonstrated
- Active Directory installation and configuration
- Domain controller deployment
- User account creation
- Organizational Unit design
- Security group management
- Windows Server administration

## Screenshots
[Will add after completing additional configurations]

## What I'm Learning
- How Active Directory authenticates users across a domain
- How organizational structures organize users and computers
- How security groups manage access control
- Windows Server administrative tools (Server Manager, Active Directory Users & Computers)

## Next Steps
- Set up file shares with NTFS permissions
- Create Group Policy Objects
- Join a member server to the domain
- Automate user creation with PowerShell

## Tools Used
- Microsoft Azure (IaaS)
- Windows Server 2022 Datacenter
- Active Directory Domain Services
