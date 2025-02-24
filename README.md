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

<p>Next, we need to configure Departments, which control ticket visibility and responsibility. Departments help categorize tickets so that the right people handle the right issues. For instance, we can create a Help Desk department for general IT support, a SysAdmins department for infrastructure-related issues, and a Networking department for handling network-related requests. Assigning agents to these departments ensures that tickets are automatically routed to the appropriate teams.

</p>
<br />

<p>
<img src="https://imgur.com/WhoHWW1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>Sometimes, multiple departments need to collaborate on specific types of tickets. This is where Teams come into play. Unlike departments, teams allow us to pull agents from different areas to work together on particular issues. For example, we might create an Online Banking Team, which includes agents from both the Support and SysAdmins departments to handle technical issues related to online banking. Teams help improve coordination and efficiency in resolving complex problems.
</p>
<br />

<p>
<img src="https://imgur.com/JRi2AYV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>To control how users create tickets, we need to configure user settings. By navigating to the Admin Panel -> Settings -> User Settings, we can uncheck the option that allows unregistered users to create tickets. Instead, we enable the requirement for users to register and log in before submitting tickets. This prevents spam and ensures that every ticket is associated with a verified user, improving accountability and security. After setting up departments and permissions, we configure the Agents, who are responsible for working on tickets. Agents are added in the Admin Panel under the “Agents” section. For example, we might add Jane, who belongs to the SysAdmins department and specializes in handling infrastructure-related tickets, and John, who is part of the Support department and assists with general IT issues. Assigning agents to specific departments helps streamline ticket resolution and ensures expertise-based ticket assignment.
</p>
<br />

<p>
<img src="https://imgur.com/eADLHnl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>On the customer side, we need to configure Users, who are the individuals submitting tickets for assistance when they encounter technical issues or require support. Users can be added in the Agent Panel under “Users”, where their information is recorded to facilitate streamlined communication and efficient ticket tracking. For instance, we can add Karen, a customer who frequently requires IT support for personal computer issues, and Ken, a corporate client with business-critical requests that may involve system outages, security concerns, or high-priority operational disruptions. Proper user management is crucial in ensuring that every customer interaction is logged, categorized, and tracked systematically, allowing agents to access user history, previous support requests, and any ongoing issues. Additionally, by maintaining an organized user database, agents can personalize their responses, provide faster resolutions, and escalate cases more effectively based on the user’s needs and priority level. Well-structured user management also enables reporting and analytics, allowing the organization to identify trends, recurring issues, and areas for service improvement, ultimately enhancing the overall customer experience and efficiency of the help desk system.
</p>
<br />

<p>
<img src="https://imgur.com/RxA7GLV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>A critical part of ticket management is defining Service Level Agreements (SLAs), which set expectations for response times. SLAs can be configured under Admin Panel -> Manage -> SLA to ensure that tickets are resolved within a specified timeframe. For example, a Sev-A SLA might apply to business-critical outages, requiring a 1-hour response time with 24/7 support, while a Sev-B SLA might allow a 4-hour response time for high-priority but non-critical issues. Meanwhile, Sev-C could be assigned to low-priority tickets, with an 8-hour response time limited to business hours. SLAs help prioritize issues based on urgency and ensure timely support.
</p>
<br />

<p>
<img src="https://imgur.com/iziVwOx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>To further streamline ticket creation, we configure Help Topics, which guide users in selecting the appropriate category when submitting a request. This is done in the Admin Panel -> Manage -> Help Topics. Some example help topics include Business Critical Outage for major system failures, Personal Computer Issues for individual device troubleshooting, Equipment Request for hardware or software needs, Password Reset for login problems, and Other for miscellaneous requests. Categorizing tickets in this way ensures that they are routed to the correct department right from the start. In conclusion, setting up osTicket correctly leads to a more efficient and professional ticketing system, improving both the user experience and agent productivity.
</p>
<br />
