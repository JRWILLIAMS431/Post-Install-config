
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Setup </h1>
This tutorial outlines the post-installation process of the open-source help desk ticketing system osTicket. We will be configuring osTicket for daily operations.

*note that the virtual machine, remote desktop, and os ticket system already exist from our prerequisite lab. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Departments
- Configure Agents (daily operators)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/GBRUbLd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Agents -> Departments 

As an admin I am tasked with creating the departments within which each agent will be granted certain accesses.These departments vary widely from business to business but achieve the same goal which is to streamline support in a central hub where the support team and users can interface with each other. 

</p>
<br />

<p>
<img src="https://i.imgur.com/IIgbgVh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Agents -> Add New

Here I am creating a simulation agent that will act as one of the help desk associates responsible for corresponding and resolving incoming tickets. 

</p>
<br />

<p>
<img src="https://i.imgur.com/Mso2w4y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agent Panel -> Users -> Add New

The users I create will act as organization employees who inevitably run into to issues throughout the work day. These users will be the ones sending tickets to be resolved by the support team/department. 
</p>
<br />

<p>
<img src="https://i.imgur.com/TzsTJ6o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Manage -> SLA

The SLA or service level agreement section is where all parameters and instructions for how the ticket should be resolved will be located. SLA is handed down by management in most cases and assigned to the support team. Every ticket is not created equal meaning that the level of urgency needed to resolve each ticket my vary. Severity levels and time-frames are included in the SLA depending on the nature of the ticket being resolved. 
</p>
<br />

<p>
<img src="https://i.imgur.com/ekiIdeQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Manage -> Help Topics

The help topics section enables the user with the ability to stage their concerns categorically. Essentially a window where all requests are filtered by topic. 
</p>
<br />


