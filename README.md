<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial demonstrates the post configuration setup of the osTicket system.<br />

<p>

</p>
</p>
<p>
Okay wonderful! We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup.
first we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. 
Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role.
</p>

![image](https://github.com/IbrahimBerikaa/OsTicket-Configuration/assets/167066492/0f424431-d004-4a00-9ff6-d353ed2291d0)

</p>
<br />
<p>
</p>
<p>
Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab. 
</p>
<br />
<p>
<img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team. 
</p>
<br />
<p>
  
![image](https://github.com/IbrahimBerikaa/OsTicket-Configuration/assets/167066492/204a32ab-e91d-4f71-a13e-83230da86174)
</p>
<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.

</p>
<br />

![image](https://github.com/IbrahimBerikaa/OsTicket-Configuration/assets/167066492/6f48204e-be00-4e53-9b0a-ecbe97d9a12b)

</p>
<p>
It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab. 
</p>
<br />

![image](https://github.com/IbrahimBerikaa/OsTicket-Configuration/assets/167066492/0247f774-edf7-4877-860d-f6785e029cee)
</p>
<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new. 
</p>
<br />

![image](https://github.com/IbrahimBerikaa/OsTicket-Configuration/assets/167066492/ae887edf-23b6-4da4-a71c-a64fbdd6b56f)
</p>
<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period. 
</p>
<br />

![image](https://github.com/IbrahimBerikaa/OsTicket-Configuration/assets/167066492/6c819bf8-6b4c-4f62-b95d-1ea7f770e3f4)
</p>
<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking. 
</p>
<br />

![image](https://github.com/IbrahimBerikaa/OsTicket-Configuration/assets/167066492/c1a97f95-bf03-4f90-9e02-58780f137376)
</p>
<p>
