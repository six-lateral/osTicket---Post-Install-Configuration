# osTicket-post-install-cfg

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configurations</h1>
In this second section of the osTicket lab I will demonstrate the necessary changes I make to configure osTicket so it can be used as a proper ticketing system. This is done by settings the roles and permissions for who can view and create a ticket.<br />

<h1>Objectives</h1>

  - <b>Create an Admin Role and Assigning Permissions</b>

  - <b>Creating Departments</b>

  - <b>Creating and Defining SLAs</b>

  - <b>Creating Help Topics</b>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (22H2)


<h2>Configuration Steps</h2>

With our osTicket database set up we will now begin our Post-Install configuration. Starting with roles and creating a supreme admin role. We will click the link named "http://localhost/osTicket/scp" and will navigate over to the admin panel on the top right and select Agents > Roles > Create New Role. Name it some kind of admin account > Permissions, check all boxes for full permissions.
<p>
<img src="https://i.imgur.com/wyWPnLg.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/FvTp4cr.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>
Now create a department. Navigate to Agents > Departments > Add a new Department. Name the department and add a new department.

</p>
<br />

<p>
<img src="https://i.imgur.com/wpEGDxa.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>
Next is to create some teams, go to Agents > Teams > Add New Team. Name level II support. We will now allow anyone to create tickets. Admin Panel > Settings > Users. Ensure “Require registration and login to create tickets” is unchecked.

</p>
<br />

<p>
<img src="https://i.imgur.com/X0gfpmt.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>
Now we will create our agents who submit tickets. Go to Admin Panel > Agents > Add New Agent. Name one John Doe and Jane Doe. Setting up a username and password for both of them.
</p>
<br />

<p>
<img src="https://i.imgur.com/UnYyh3B.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/9I00e4Q.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>
Next is creating our customers. Swap to the Agent Panel > Users > Add User. Create 2 sample users. 
</p>
<br />

<p>
<img src="https://i.imgur.com/qZi2Nns.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>
We will now create 3 SLAs. Swap back to the Admin Panel > Manage > SLA. We should look to get a result like this. Setting up 3 severities for tickets. In this case, SEV-A, B, and C have been created to categorize tickets that need to be resolved within 1 hour, 4 hours, and 8 hours respectively. This is what the result should look like. Service Level Agreements (SLAs) will have to be made in order to categorize tickets according to their level of impact. 

</p>
<br />

<p>
<img src="https://i.imgur.com/EmSnEcf.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<br />
<p>
Lastly we will now set up help topics, Manage > Help Topics. Create “Business Critical Outage”, “Equipment Request”, “Personal Computer Issues”, and “Password Reset." Help Topics need to be created to help users select an appropriate category that describes their problem so that Agents get an idea of what problem is described in the ticket.
</p>
<p>
<img src="https://i.imgur.com/N8X5Rwo.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>

<h2>osTicket Configurations are Complete </h2>

Now that the configurations have been set in place, I can now utilize osTicket as a proper ticketing system. I can create tickets and be able to traige them as if I were in a real environment.
With the configurations, roles, departments, and permissions set, I can now utilize osTicket as a ticketing system properly. Similar to a real environment I am able to create, categorize, assign, answer, and resolve tickets.
