# active-directory-homelab
Homelab to practice enterprise grade windows enviroment.
# Windows Server Active Directory Homelab

A hands-on **Windows Server Active Directory homelab** built to practice core **IT support, system administration, and junior infrastructure tasks** in a safe virtual environment.

This lab focuses on building a foundational understanding of **Active Directory administration and Windows domain environments**, similar to what is used in many enterprise IT infrastructures.

---

# Lab Objectives

This project focuses on practicing and understanding:

- Active Directory Domain Services (AD DS)
- Organizational Units (OUs)
- User and Computer Management
- Group Policy Objects (GPOs)
- Domain Join and Client Configuration
- Windows Administration Fundamentals

The goal is to simulate real-world **IT support and junior system administration tasks** in a controlled homelab.

---

# Lab Environment

### Virtual Machines

| Machine | Role | Operating System |
|-------|------|----------------|
| DC01 | Domain Controller | Windows Server |
| CLIENT01 | Domain Client | Windows 11 |
| CLIENT02 | Domain Client | Windows 11 |

*(More client machines can be added for additional testing.)*

---

# Core Roles and Components

The following Windows Server roles and administrative tools were used:

- Active Directory Domain Services (AD DS)
- DNS Server
- Group Policy Management

---

# Key Administrative Tasks Performed

### Active Directory Setup

- Installed **Active Directory Domain Services**
- Promoted the server to **Domain Controller**
- Created a **new domain / forest**

---

### Directory Structure

- Built **Organizational Unit (OU) structure**
- Created **domain users and groups**
- Managed users 


---

### Client Configuration

- Joined Windows 11 workstations to the **Active Directory domain**
- Verified domain login functionality
- Tested domain authentication and connectivity

---

### Group Policy

- Created and configured **Group Policy Objects (GPOs)**
- Linked policies to specific **OUs**
- Tested policy application on domain clients

Example policies tested:

- Desktop restrictions
- Login behavior
- Basic security settings

---

### Administrative Verification

Administrative changes were tested from both:

- **Server side**
- **Client side**

This ensured policies and directory changes were applied correctly across the domain.

---

# Skills Demonstrated

This lab demonstrates practical experience with:

- Active Directory administration
- Windows Server configuration
- Domain infrastructure setup
- Group Policy management
- User and device lifecycle management
- Basic enterprise IT troubleshooting

---


The goal is to demonstrate **practical knowledge of real Windows enterprise environments** through documented homelab projects.

