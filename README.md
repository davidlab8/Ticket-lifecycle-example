<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Creating Admin, Departments, Agents, Users, Discussing Ticket Lifecycle </h1>
This tutorial outlines the creation of Admin Dep, Roles, Agents, and Users also the lifecycle of a ticket from intake to resolution


<h2>Video Demonstration</h2>

- ### [YouTube: OsTicket Features](https://www.youtube.com/watch?v=5Yxfe85KZGk&t=20s)
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Creating Admin, Departments, Agents, and Users. Discussing Ticket Lifecycle Stages</h2>

- Step 1. Post installation set-up configuring Roles (example) Supreme Admin having access to admin Osticket
- Step 2. Configuring Departments, Teams, Agents, Users (customers), SLA, and help topics 
- Step 3. Log-in Osticket as a User, create a ticket with a issue to be worked on 
- Step 4. Intake, Assignment and Communication, Working the Issue, Resolution.

<h2>Admin panel installation set-up</h2>

STEP 1.

![IMG_1057](https://github.com/davidlab8/Ticket-lifecycle-example/assets/154483052/7bbf6d8b-b429-4a2f-9d8b-740046e6faac)
 - Step 1. Log-in Osticket as Admin Username password (Osticket menu) admin panel, agents, roles
   
![IMG_1058](https://github.com/davidlab8/Ticket-lifecycle-example/assets/154483052/d9235f58-31a8-4832-ac23-ee280af5f8a0)
 - Add new role (create) Supreme Admin

 ![IMG_1059](https://github.com/davidlab8/Ticket-lifecycle-example/assets/154483052/8e5f2dc7-6f40-43b9-a295-313e1f6f9f54)
 - Permission tabs check off all boxes add role to have full access

STEP 2.

![IMG_1060](https://github.com/davidlab8/Ticket-lifecycle-example/assets/154483052/974d93be-dd27-4646-8349-91ad2c5a6d37)
 - Step 2. Configuring Agents, Teams, Roles, and Departments have the same steps to create:

![IMG_1061](https://github.com/davidlab8/Ticket-lifecycle-example/assets/154483052/037d92f9-250b-462f-9a0e-888ab50249ae)
 - Admin Panel, Agents Tab (select) (Add new) fill out info to create. 

<br />

<h2>Lifecycle Stages</h2>

STEP 3.

![IMG_1062](https://github.com/davidlab8/Ticket-lifecycle-example/assets/154483052/6f96e25a-c27a-40ad-a4a7-340378637d85)

- Step 3. Creating a ticket as a user log-in http://localhost/osTicket new ticket, Email, full name, Help Topic, Issue Summary, 
describe in detail what issue is
(ticket then is created will appear in osticket admin panel and agent panel)

STEP 4.

![IMG_1066](https://github.com/davidlab8/Ticket-lifecycle-example/assets/154483052/445a9eb0-53c2-4db1-ae79-bf9de84f70fe)
- Step 4. Log-in to Osticket Agent panel where ticket can be viewed, assigned, and resolved 

![IMG_1064 2](https://github.com/davidlab8/Ticket-lifecycle-example/assets/154483052/4f3f1372-68b4-452e-aca7-ba0b4f97d920)
  - Ticket # Menu, Status- (resolved or closed), Priority, Department (where ticket is gonna go), Assigned To (Agent), SLA (timeframe)
 
![IMG_1065](https://github.com/davidlab8/Ticket-lifecycle-example/assets/154483052/852cdc54-8078-4ad3-a19d-d23dc62e5901)
 - Response column (select a response), description write a response, Ticket Status ( open, resolved, or close) the admin fills out the ticket assign it gives it a SLA depending on the importance of the ticket, the agent recieves the ticket begins to work on it
 - Updates progress, by (ticket thread) where it can be seen by everyone who has access if the agent needs assistance they can send message to user, admin or other agents once ticket is resolved it will be closed thus ending ticket lifecycle.
 
</p>
<br />
