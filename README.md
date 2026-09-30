# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
Before this project, Northstar Medical Group was struggling with severe administrative chaos by their previous Managed Service Provider. The organization lacked a centralized identity system, relying on disorganized manual processes to manage employees and system access. Without a structured active directory hierarchy or formal permissions, users had wrong access rights, which creadted many operational issues. This complete lack of access control and user auditing exposed the healthcare provider to serious HIPAA compliance violations and security risks.

## Solution Overview
To clean up this mess, I set up a local domain (NMG.com) from scratch on a Windows Server VM using VirtualBox. I organized the environment by creating distinct Organizational Units (OUs) for Finance, HR, IT, and Operations so every department had its own clear space. I then set up Role Based Access Control (RBAC) with security groups and created 15 user accounts with clean, consistent naming rules. Now, when a new user is added to a department group, they automatically get the exact permissions they need which makes user management way easier and keeping access HIPAA compliant.

## Video Walkthrough
https://www.loom.com/share/066e2ce08fe74ef89595b11a0f8cb5c2

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Implemented RBAC with security groups mapped to each department
* Provisioned 15 user accounts with consistent naming conventions and attribute standards

