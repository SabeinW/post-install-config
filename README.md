<p align="center">
<img src="https://www.zippyops.com/userfiles/cache/thumbnails/1920/tn-osticket-1517973894.jpg" alt="osTicket logo"
  height="200"
  width="700"/>
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

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (For when users create a ticket)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/6Hpx5x4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/qI18wae.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/oaPMOPI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open your osTicket installation in a browser (e.g., your-domain.com/support/). Log in to the Admin Panel using your Admin credentials. In the Roles section, click on the "Add New Role" button .You will be prompted to provide a Role Name. Choose a descriptive name based on the responsibilities that role will have (e.g., "Support Staff", "Admin", "Manager", etc.).
</p>
<br />

<p>
<img src="https://i.imgur.com/FgldsQQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/lg7S1ZC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/hs9tTGB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Navigate to the "Agents" Section, Add a New Department, Assign Department to Staff, Configure Department-Specific Permissions. By configuring Departments in osTicket, you can, Organize and manage tickets based on different functional areas (e.g., Help Desk, SysAdmins, Networking).
Assign staff members to specific departments and grant them relevant permissions. Control ticket visibility to ensure that only authorized staff members can see and work on tickets from their department.
</p>
<br />

<p>
<img src="https://i.imgur.com/nCvhupk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/QlUavgy.pnghttps://i.imgur.com/QlUavgy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
By configuring Teams in osTicket, you can, organize staff members into smaller, more manageable groups based on their expertise or department, assign tickets to an entire team, making collaboration more efficient and fine-tune permissions and responsibilities to make sure teams only access the tickets and features relevant to them.
</p>
<br />

<p>
<img src="https://i.imgur.com/hX4GAT7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<img src="https://i.imgur.com/FdSRo2y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Gyz5goV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/DGdsZfZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>
By configuring agents in osTicket, you ensure that each staff member has the appropriate level of access and responsibility to manage and resolve support tickets. Roles, departments, and teams help you streamline ticket management, and configuring agent permissions ensures that agents can only perform tasks relevant to their role.
</p>
<br />

<p>
<img src="https://i.imgur.com/g2nsdIy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/i22IzMw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/1JGvIsu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring users in osTicket, you ensure that customers can submit tickets, track their status, and receive relevant notifications. You can assign them to specific departments, enable them to interact with your support system, and customize their permissions based on your business needs.
</p>
<br />

<p>
<img src="https://i.imgur.com/kTO4djr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/S9lFLZv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring SLAs in osTicket ensures that you meet your organization's ticket handling goals by enforcing timely responses and resolutions. You can set specific targets for response and resolution times based on ticket priority, department, or type. Additionally, you can automate notifications and escalate tickets that approach or breach SLA targets.
</p>
<br />

<p>
<img src="https://i.imgur.com/C0dDpzA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ri6m1yk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/vOpVWGd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring Help Topics in osTicket is crucial for organizing incoming support requests and ensuring that they are routed to the right department. By giving users the ability to select the appropriate help topic, you streamline the support process, which improves both user experience and response times.
</p>
<br />
