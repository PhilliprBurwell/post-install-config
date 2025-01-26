<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Acknowledge Agent Panel vs Admin Panel
- Understand Grouping Permissions
- Set up Ticket Visibility, Help Desk vs SysAdmins, vs Networking
- Arrange SLA's & Help Topics as an Admin 
  
<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/42982eca-ab86-4529-8a0d-40d0e180de0a)

</p>
<p>
#1 Configuring Roles, Departments and Teams Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles Supreme Admin Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)Admin Panel -> Agents -> Departments SysAdmins Configure Teams Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

</p>
<br />

![image](https://github.com/user-attachments/assets/bc19f03f-f488-4cbe-80a2-7ba64f1f7fe8)

</p>
<p>
#2 Configuring Agents and Users Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets) Registration Required: Require registration and login to create tickets  Configure Agents (workers) Admin Panel -> Agents -> Add New Jane (Dept: SysAdmins) John (Dept: Support) Configure Users (customers) Agent Panel -> Users -> Add New, Karen, Ken

</p>
<br />

![image](https://github.com/user-attachments/assets/66800a50-0785-4d9c-81d4-2bf9850c1d7e)

![image](https://github.com/user-attachments/assets/fe8047f7-405b-4a6b-afe3-9c041c019cb1)


</p>
<p>
#3 Configuring SLA and Help Topics Configure SLA Admin Panel -> Manage -> SLA Sev-A (Grace Period: 1 hour, Schedule: 24/7) Sev-B (Grace Period: 4 hours, Schedule: 24/7) Sev-C (Grace Period: 8 hours, Business Hours) Configure Help Topics (For when users create a ticket) Admin Panel -> Manage -> Help Topics, Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, Other


</p>
<br />
