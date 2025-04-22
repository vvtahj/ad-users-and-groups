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

![Screenshot 2025-04-21 112136 - Copy](https://github.com/user-attachments/assets/5dcffa19-005f-4ae1-93ff-947539a3b531)

![Screenshot 2025-04-21 113044](https://github.com/user-attachments/assets/5b8badbb-961b-4a44-b342-0b2428b45373)
![Screenshot 2025-04-21 113139](https://github.com/user-attachments/assets/571ef730-47fa-4c9d-99a0-cab77958a992)
![Screenshot 2025-04-21 113202](https://github.com/user-attachments/assets/4bc789af-e4ad-4c6b-ba3b-592ddef50f45)
![Screenshot 2025-04-21 112315](https://github.com/user-attachments/assets/11b9d8e6-5314-4afb-99cc-d3ea7f66f2b9)
![Screenshot 2025-04-21 112230](https://github.com/user-attachments/assets/9eeb2290-2a05-4ecf-bc13-0153e54e8610)


## 📘 Lessons Learned
- OUs allow for scalable and organized domain structures
- Security group assignments directly influence access permissions
- Domain admin accounts must be managed carefully to prevent privilege abuse
