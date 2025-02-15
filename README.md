# <p align="center">
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

- Configure Roles -> Supreme Admin
- Configure Departments -> SysAdmins
- Configure Teams -> Online Banking
- Configure Agents -> Jane/John
- Configure Users(Customers) -> Karen
- Configure SLA -> Sev-A,B,C
- Configure Help Topics -> Business Critical Outage, Password Reset, etc

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/ywt4bNf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>In this project, we configured osTicket to manage support tickets efficiently by setting up roles, departments, teams, agents, users, service level agreements (SLAs), and help topics. These steps ensure that tickets are properly assigned, tracked, and resolved in an organized manner. The configuration process helps define permissions, structure the support system, and improve response times. First, we set up Roles to group permissions for agents. In the admin panel to roles, we created a Supreme Admin role, granting full administrative control. Roles define what each agent can access and modify within osTicket, ensuring a structured and secure support system.

</p>
<br />

<p>
<img src="https://imgur.com/2ZFabzV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>Next, we configured Departments to organize ticket visibility. In admin panel to select agents to departments, we created a SysAdmins department to handle IT related issues. Departments help categorize support teams, such as Help Desk, SysAdmins, and Networking, ensuring tickets are routed to the right team members.

</p>
<br />

<p>
<img src="https://imgur.com/WhoHWW1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>We then created Teams to pull agents from different departments into specialized groups. In teams, we added an Online Banking team, allowing agents from various departments to collaborate on specific issues. Teams are useful for cross-functional support cases that require expertise from multiple departments.

</p>
<br />

<p>
<img src="https://imgur.com/JRi2AYV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>To manage ticket creation, we adjusted user settings. In user settings, we enabled registration requirements, ensuring only registered users can create tickets. This prevents spam and unauthorized requests while maintaining a secure support environment. Next, we added Agents (support staff) and Users (customers). In agents we add new to create Jane (SysAdmins) and John (Support) as our agents.
</p>
<br />

<p>
<img src="https://imgur.com/eADLHnl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>We also added customers like Karen so she could submit tickets. This step ensures that users can request help and agents can respond efficiently.

</p>
<br />

<p>
<img src="https://imgur.com/RxA7GLV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>Finally, we configured SLA (Service Level Agreements) and help topics to set ticket priorities and categories. In SLA, we created three levels: Sev-A (1-hour response, 24/7), Sev-B (4-hour response, 24/7), and Sev-C (8-hour response, business hours only).

</p>
<br />

<p>
<img src="https://imgur.com/iziVwOx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>In Help Topics, we set up ticket categories like Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and Other to help users categorize their requests. These settings ensure that tickets are prioritized correctly and assigned to the appropriate teams for resolution. 
</p>
<br />
