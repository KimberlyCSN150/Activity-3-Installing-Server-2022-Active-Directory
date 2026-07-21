# Activity-3-Installing-Server-2022-Active-Directory

Installing the Active Directory Domain Services (AD DS) role and promoting the server to a domain controller.

Requirements
Administrative privileges
Static IP address already configured
Server already named appropriately
Steps

Install the AD DS role
 Open Server Manager → Manage → Add Roles and Features
 Select the server, check Active Directory Domain Services
 Include management tools when prompted
 Allow automatic restart if required, then install
 Capture a screenshot of the installation

Promote to domain controller
 Click "Promote this server to a domain controller"
 Choose Add a new forest
 Set root domain name to xyz.local
 Set and confirm the Directory Services Restore Mode (DSRM) administrator password
 Complete the wizard and restart

Verify
 Log back in after restart
 Open Server Manager → Tools → Active Directory Users and Computers
 Pin ADUC to the taskbar
 Expand xyz.local → Users folder to confirm the domain is live
 Capture a screenshot

Notes

This activity turns a standalone server into the authoritative domain controller (xyz.local) that every later lab builds on — OUs, users, group policy, and DNS all live here going forward.

<img width="973" height="1027" alt="image" src="https://github.com/user-attachments/assets/1dc7012b-ca3c-4127-85d2-a055ea9afab2" />

<img width="973" height="1028" alt="image" src="https://github.com/user-attachments/assets/0f83ddb4-562a-473c-8ffb-0d26aa255d8e" />

<img width="975" height="755" alt="image" src="https://github.com/user-attachments/assets/c6441b46-0de6-4ac6-b62e-fbae1c7683d3" />


