# Windows AD IAM Lab

## Project Overview
This lab demonstrates **Identity and Access Management (IAM)** concepts using Windows Active Directory. It focuses on role-based access control (RBAC), least privilege enforcement, and centralized management of users and groups.

## Tools & Technologies
- Windows Server with Active Directory Domain Services (AD DS)
- Active Directory Users and Computers (ADUC)
- NTFS folder permissions
- Group Policy Management Console (GPMC)

## Lab Objectives
- Create security groups representing roles: `HR-Team`, `Finance-Team`, `IT-Team`  
- Create test users and assign them to appropriate groups  
- Configure folder permissions to enforce **least privilege** access  
- Demonstrate centralized IAM policies through AD group membership and folder access  

## Screenshots

### Screenshot 1
![Security Groups](screenshots/01-security-groups.png)  
*Security groups created in ADUC demonstrating role-based access control.*

### Screenshot 2
![Test Users](screenshots/02-test-users.png)  
*Test users added to their respective groups, showing IAM role assignments.*

### Screenshot 3
![Shared Folder Permissions](screenshots/03-shared-folder-permissions.png)  
*Folder permissions applied to groups, enforcing least privilege and restricting access.*

## Skills Demonstrated
- **Role-Based Access Control (RBAC)** – Users organized into security groups representing roles  
- **Least Privilege Enforcement** – Only authorized groups have access to sensitive folders  
- **Centralized IAM Management** – Group membership controls access across the domain  
- **Portfolio-Ready Documentation** – Clear screenshots and step-by-step lab setup  

## Notes
Due to environment limitations, access tests and event log screenshots were simulated by showing applied permissions and group membership.

