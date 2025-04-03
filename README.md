<p align="center">
<img src="https://github.com/user-attachments/assets/0975111e-51db-4d5d-b695-f2114b1c6e6e" 
</p>


# 👥 Active Directory: Users, Groups, and OUs

## 📌 Overview
This lab focused on organizing user accounts and computer objects within Active Directory. I created Organizational Units (OUs), added users, and structured groups for access control.

## 🧰 Skills & Tools
- Active Directory Users and Computers (ADUC)  
- Group Management  
- Organizational Unit (OU) Structuring  
- Domain Login Testing  

## ✅ What Was Done
- Created Organizational Units: `_EMPLOYEES`, `_ADMINS`, and `_CLIENTS`
- Created a domain admin user: `jane_admin` and added to the “Domain Admins” security group
- Moved the domain-joined client machine (Client-1) into the `_CLIENTS` OU
- Logged in as `jane_admin` to verify domain administrative privileges and access

## 🛠️ Tools Used
- ADUC (Active Directory Users and Computers)  
- Windows Server GUI / Authentication Tools  

## 🖼️ Screenshots  
*(Insert screenshots showing ADUC structure, user creation, OU assignments, and group memberships)*

## 📘 Lessons Learned
- OUs allow for scalable and organized domain structures
- Security group assignments directly influence access permissions
- Domain admin accounts must be managed carefully to prevent privilege abuse
