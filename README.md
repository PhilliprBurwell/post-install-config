<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
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

(Image #1)

![image](https://github.com/user-attachments/assets/42982eca-ab86-4529-8a0d-40d0e180de0a)

</p>
<p>
#1 Configuring Roles, Departments and Teams - To configure Roles for grouping permissions go to Admin Panel -> Agents -> Roles. Click all of the boxes to make a Supreme Admin role. To configure Departments go to the Admin Panel -> Agents -> Departments. Create new department and add SysAdmins. To configure go to Teams Admin Panel -> Agents -> Teams. Create new teams and name it online banking.

</p>
<br />

(Image #1)

![image](https://github.com/user-attachments/assets/bc19f03f-f488-4cbe-80a2-7ba64f1f7fe8)

</p>
<p>
#2 Configuring Agents and Users - In order to allow anyone to create tickets we need to go to the Admin Panel -> Settings -> User Settings we are going to uncheck "unregistered users" so we can create tickets Registration Required: Require registration and login to create tickets." To configure Agents we go to the Admin Panel -> Agents -> and we are going to add new. We are going to name them Jane and going to put her in the SysAdmins department. We are gong to create another agent and name them John. He will be in the Support department. To configure Users or the customers making the tickets we go to the Agent Panel -> Users -> and add New. We are going to add 2 users which will be Karen and Ken.

</p>
<br />
(Image #1)

![image](https://github.com/user-attachments/assets/66800a50-0785-4d9c-81d4-2bf9850c1d7e)

(Image #2)

![image](https://github.com/user-attachments/assets/fe8047f7-405b-4a6b-afe3-9c041c019cb1)


</p>
<p>
#3 Configuring SLA and Help Topics - To configure SLA we are going to open the Admin Panel -> Manage -> SLA. We are going to set Sev-A's grace period to 1 hour and the schedule to 24/7. Set Sev-B's grace period to 4 hours and the schedule to 24/7. Then set Sev-C's grace period to 8 hours and to Business Hours. To configure the Help Topics for when users create a ticket we go to the Admin Panel -> Manage -> Help Topics. Add Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset and Other.


</p>
<br />
