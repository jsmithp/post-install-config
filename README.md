<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-instal configurat of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Teams and Departments
- Configure Agents
- Configure SLA
- Create Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/za1c6FE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure roles, go to: Admin Panel > Agents > Roles. Add role. Name it and enable all ticket permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/9Gy76jo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel > Agents > Departments, Name the department and select a manager. Click "Creat Dept". Next, go to Admin Panel -> Agents -> Teams. Select "Add team". Name it "Level II Support" and add member by clicking on "Members" tab. Go to Admin Panel > Settings > User Settings to make sure that the registration required box is not checked.
</p>
<br />

<img src="https://i.imgur.com/DVzw0Fn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel -> Agents and click "Add new agent". Create name and email. Press the set password button. Deselect the "Send the agent a password reset" box and create a password. Deselect the "require password change" box and press "set". Click on "Access" tab and select "System Administrators". Also select the department you created. In extended access below, select the department you created and add "support" department as well. Next, click on "teams" tab and select the team you created. Click "Create". Add another agent with limited permissions. To create users, go to Agent Panel > Users > and click on "Add user". Create name, email and password. Click "Add User".
</p>
<br />

<p>
<img src="https://i.imgur.com/qVA7OCX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/R6WlRCZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/mW9MY1K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel > Manage > SLA and click "add new SLA plan". Place these settings for Sev-A: (1 hour, 24/7). Sev-B will be (4 hours, 24/7) and Sev-C will be (8 hours, Monday - Friday).
</p>
<br />

<p>
<img src="https://i.imgur.com/rlspBuk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel > Manage > Help Topics and click "Add help topic". Title the first one "Business Critical Outage", the second "Personal Computer Issues", the third "Equipment Request", and lastly "Password Reset". Log into the user portal of osTicket at: http://localhost/osTicket/. Use a user you created to create tickets.
</p>
<br />
