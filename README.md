# osticket-config

 
osTicket: Installation & Virtual Machine Creation
This tutorial will show how to create the virtual machine through Microsoft Azure which will house the help desk ticketing software, osTicket
Video Demonstration
YouTube: osTicket Creating Agents and Clients
In this section, we will act as a System Administrator and create agents and clients and simulate an osTicket help desk ecosystem.
Chapter 1: Creating Roles
1.	Click on the Admin Panel to go into admin mode, then under the Agents tab, click on Roles. Click on Add New Role and let us add a role that has all permissions called Super Admin. Go to the Permissions tab click every checkbox under Tickets, Tasks, and Knowledgebase, the click on Add Role. https://i.imgur.com/6uvFJZy.png 
2.	Under Agents > Departments, it shows two departments, Maintenance and Support, each of which can have a ticket be redirected to them. Click on Add New Department to create another department that we’ll call System Admins. Click on Create Dept to create the department. https://i.imgur.com/ABbdRgE.png
3.	Under Agents > Teams, it will already show Level I Support. Click on Add New Team to make a Level II Support. This also can indicate ticket escalation.

Chapter 2: Creating Agents and Clients
1.	Under Agents > Agents, you can see the list of help desk agents and we can create new agents (of course). Click on Add New Agents and you can fill in information for new agents. Name them, give them an email address and a username and password. For this, we’ll add two new agents: Alex Ovechkin and Sidney Crosby. Alex will have System Admins and Super Admin access, and be in the Level II Support team. Sidney Crosby will only have Support and View only access. https://i.imgur.com/ndzgHpa.png
2.	Under Users > User Directory, clients or users can be added in order for them to create tickets. Click on Add User to create a client, give them a name and an email address. We will create two users, Jayson Tatum and Jaylen Brown.

Chapter 3: Service Level Agreements (SLAs)
SLAs can be defined when evaluating tickets for their level of severity and necessity to get handled. Here are the three SLA levels and their grace periods that will be defined.
Sev-A: 1 hour, 24/7
Sev-B: 4 hours, 24/7
Sev-C: 8 hours, Business hours M-F
1.	In the Admin Panel, go to Manage > SLA to create SLAs. Give the first one a name which will be ‘Sev-A,’ the grace period is 1 hour, and under a 24/7 Schedule. Click on Add Plan, then repeat this step to add Sev-B and Sev-C. https://i.imgur.com/6AjE0Jm.png 


Chapter 4: Help Topics
When creating tickets, end users will feel like their issue can be dealt with easier if there is a specific topic that aligns with their issue.
1.	In the Admin Panel, go to Manage > Help Topics to create help topics that clients may categorize their tickets under. Click on Add New Help Topic to create some. Some examples are Business Critical Outage, Computer Issues, Equipment Request, and Password Reset. The possibilities are endless.

Click for Part 3: osTicket Ticket-Handling Simulation
