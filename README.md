# Windows Server & Active Directory Home Lab

## Overview
I built a functional Active Directory environment on Microsoft Azure to learn enterprise Windows infrastructure management and systems administration. This hands-on lab demonstrates core IT operations skills including Active Directory administration, user and group management, NTFS permissions, and domain controller configuration.

## Architecture
- **Platform:** Microsoft Azure (IaaS)
- **Operating System:** Windows Server 2022 Datacenter
- **VM Name:** DC1
- **VM Size:** B2s (2 vCPU, 4GB RAM)
- **Domain Name:** company.local
- **Role:** Domain Controller
- **IP Address:** 20.117.8.104

## What I've Built

### Active Directory Infrastructure
- Created a new Active Directory forest with domain "company.local"
- Promoted Windows Server 2022 to Domain Controller
- Installed and configured Active Directory Domain Services (AD DS)
- Configured DNS services for domain resolution

### Organizational Structure
- **IT Department** Organizational Unit (OU)
- Structured directory for user and resource management

### Users Created
- User1 (member of IT Department)
- User2 (member of IT Department)
- User3 (member of IT Department)
- User4
- User5
- User6
- User7

**Total:** 7 user accounts created and managed in Active Directory

### Groups & Membership
- **IT Department** (Security Group)
  - Members: User1, User2, User3
  - Used for access control and permission management

### File Shares & NTFS Permissions

#### C:\ITData (Main Share)
- **Network Path:** \\company.local\ITData
- **Subfolder:** Confidential (restricted access)

#### NTFS Permissions Configuration
- **C:\ITData:** Read-only for general users (Everyone group can Rea
