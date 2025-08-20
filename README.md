# OS-Ticket-post-installation
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

- Item 1 -Configure Roles
- Item 2 -Create Departments
- Item 3 -Set Up Teams
- Item 4 -Add Agents and End Users
- Item 5 -Configure SLA's and Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="469" height="371" alt="11" src="https://github.com/user-attachments/assets/149f5b67-1e8b-42ae-a782-57303ef8a382" />


</p>
<p>
This screenshot shows the creation of Roles and Departments in osTicket. Here, I configured the “Supreme Admin” role with all permissions, added a “CIS Admins” department, and created a cross-departmental Team. This setup controls access and workflow in the support portal.
</p>
<br />

<p>
<img width="626" height="640" alt="image" src="https://github.com/user-attachments/assets/009ffff7-4114-465a-a8f7-1e3cd590e2f8" />

</p>
<p>
 In this screenshot, I’m adding help desk agents to osTicket. "John" is set up as a support agent with view-only access in the Support department. Agents like John are responsible for reviewing, responding to, and resolving support tickets assigned to their department.
</p>
<br />

<p>
<img width="638" height="452" alt="image" src="https://github.com/user-attachments/assets/f3e8d74a-2d73-4dde-86f7-1a54940171dd" />

</p>
<p>
This screenshot documents the configuration of SLAs and the establishment of Help Topics in osTicket. SLAs define how quickly issues should be addressed, while Help Topics streamline the ticket creation and assignment process for end users and analysts.
</p>
<br />
