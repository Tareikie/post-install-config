<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Step 1: Setup Roles
- Step 2: Setup Departments
- Step 3: Setup Teams
- Step 4: Setup Agents
- Step 5: Setup Users and SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/pXkMrEN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To start, go to Admin Panel -> Agents -> Roles. Here, you can create new roles and adjust permissions for each role as needed.
</p>
<br />

<p>
<img src="https://i.imgur.com/jpJ6GtQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Moving on to Departments, create a new Dept. Called 'System Administators.'
</p>
<br />

<p>
<img src="https://i.imgur.com/LYVlNe0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to 'Teams' within the same Admin Panel and add a team named 'Level II Support.
</p>
<br />

<p>
<img src="https://i.imgur.com/IgvWTUs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Settings > Users and make sure 'Require registration and login' is not checked.
</p>
<br />

<p>
<img src="https://i.imgur.com/NPbzoBH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create some agents; for example, I chose to add Jane and John.
</p>
<br />

<p>
<img src="https://i.imgur.com/VhykP8B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now head to Agent Panel>Users>Add New and create some Users, I created Katie and Karen
</p>
<br />

<p>
<img src="https://i.imgur.com/nPQnPSx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, return to the Admin Panel and adjust your SLA settings by navigating to Admin Panel > Manage > SLA. Here, you can modify the SLA plan to align with your company's agreements, including adjusting the time required to resolve tickets based on their severity or priority. 
</p>
<br />
