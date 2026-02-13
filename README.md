# IT Home Lab Portfolio

## About Me

Entry-level IT candidate with hands-on lab experience and freelance support work. Familiar with Active Directory, Microsoft 365 administration, ServiceNow ITSM, and basic networking using VMware.

## 👨‍💻 About This Portfolio

This repository documents my hands-on IT home lab projects built in a VMware-based enterprise-style environment.

Technologies and systems covered include:

- Windows Server 2022 (Domain Controller)
- Active Directory & Group Policy (GPO)
- DNS & DHCP configuration
- Microsoft 365 & Entra ID
- ServiceNow (ITSM workflows & incident management)
- Ubuntu Linux administration & Bash scripting
- RAID configuration & disk management
- Backup automation in virtualized environments

The goal of this lab is to simulate real-world IT Support and System Administration scenarios.

## Lab Environment Overview

- VMware Workstation running on Windows 11
- Windows Server 2022 Domain Controller
- Windows 10/11 Client Machines
- Local virtual network simulating a small enterprise environment

## Completed Labs

### 1. Active Directory Domain Lab

- Deployed Windows Server 2022 as a Domain Controller
- Created and managed users, groups, and OUs
- Joined Windows client machines to the domain
- Applied Group Policy Objects (GPOs)
- Configured basic file sharing and permissions

📂 Lab file: `labs/02-active-directory-domain.md`
**Client Machine Login (Domain User)**
Domain-joined Windows client successfully authenticated using Active Directory Credentials.
![Client Login](screenshots/01-active-directory/cl01/user-login.png)

### 2. Microsoft 365 / MS-102 Lab

- Configured Microsoft 365 tenant
- Managed users and licenses
- Worked with Exchange Admin Center
- Created shared mailboxes
- Reviewed Teams policies and basic security settings

📂 Lab file: `labs/01-microsoft-365-ms102.md`
**Exchange Admin Center – Shared Mailbox Permissions**

### Client Machine Login (Domain User)

<img src="screenshots/01-active-directory/cl01/user-login.png" width="700">

### 3. ServiceNow Helpdesk Lab

- Created and managed incidents
- Assigned tickets to technicians
- Updated work notes and resolution status
- Practiced real helpdesk ticket lifecycle
- Followed ITSM best practices

📂 Lab file: `labs/03-servicenow-helpdesk.md`

### 4. Network Topology

- Designed a logical network diagram
- Simulated enterprise-style connectivity:
  - Internet → Home Router → VMware Host
  - Domain Controller and Client Machines connected internally

📂 Network topology diagram included in the `screenshots/network-diagram/`
**Incident Assigned and Resolved (ServiceNow ITSM)**  
Demonstrates full help desk ticket lifecycle from creation to assignment and resolution.
![Incident Assigned](screenshots/03-servicenow/03-users/incident-assigned-and-resolved.png)

**ServiceNow User List**  
Shows user records used for end-user support and incident handling.
![ServiceNow Users](screenshots/03-servicenow/03-users/user-list.png)

### 05. Linux Scripting – System Health Check

- Built a custom Bash script on Ubuntu Linux to perform a system health check
- Displayed uptime, memory usage, disk usage, and internet connectivity
- IP address intentionally hidden for public GitHub sharing
- Script executed manually from the terminal (no automation)

## Tools & Technologies Used

**Home Lab Network Diagram**  
Illustrates the virtual network architecture including domain controller, client machines, and services.
**Home Lab Network Diagram**
Illustrates the virtual network architecture including domain controller, client machines, and services.

![Network Diagram](screenshots/04-network-diagrams/network-diagram.png)

- Windows Server 2022
- Windows 10 / Windows 11, Linux (Ubuntu Desktop – daily use)
- VMware Workstation
- Active Directory
- Group Policy
- Microsoft 365 Admin Center
- ServiceNow
- Basic Networking Concepts
- CMD & PowerShell (basic usage)
- Version Control: Git & GitHub

## Career Focus

Seeking opportunities in:

- IT Support / Helpdesk
- Junior System Administrator
- Desktop Support

## 📄 Resume

My resume is available upon request.

Connect with me on LinkedIn:
IT-homelab-portfolio/portfolio-site
