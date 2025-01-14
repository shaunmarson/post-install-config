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

- Accessing the Admin Panel
- Navigate to Admin Panel
- Email Configuration
- Departments
- Ticket Settings

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Accessing the Admin Panel
After installing osTicket, log in to the admin panel using the credentials you set during installation.

URL: http://yourdomain.com/support/scp/
Use your admin username and password.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
General Settings
Navigate to Admin Panel > Settings > System Settings to configure general system options.

System Name: Enter a recognizable name for your help desk.
Default Email Address: Set the primary email for outgoing communications.
Helpdesk URL: Ensure the URL points to your osTicket installation.
Time Zone: Set the appropriate time zone for accurate timestamps.
Default Language: Choose the primary language for your help desk interface.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Email Configuration
Configure email for both sending and receiving tickets.

<h2> Email Settings: </h2>

Go to Admin Panel > Emails > Email Settings.
Enable sending and receiving emails via SMTP and IMAP/POP3.
Add email addresses (e.g., support@yourdomain.com) under Emails > Emails.
Outgoing Email (SMTP):

Host: Your mail server (e.g., smtp.gmail.com for Gmail).
Port: Typically 465 (SSL) or 587 (TLS).
Authentication: Provide the email address and password.
Incoming Email (IMAP/POP3):

Host: Mail server (e.g., imap.gmail.com for Gmail).
Port: 993 (IMAP with SSL) or 995 (POP3 with SSL).
Authentication: Email address and password.

Departments
Define departments to categorize tickets.

Go to Admin Panel > Agents > Departments.
Create departments such as IT Support, Sales, or Customer Service.
Assign managers and configure department-specific settings, like auto-responses.

</p>
<br />

<h2>Ticket Settings</h2>
Customize how tickets are handled.

Admin Panel > Settings > Tickets:
Enable/disable ticket locking to prevent multiple agents from working on the same ticket.
Set auto-close times for inactive tickets.
Define default SLA (Service Level Agreements) for ticket resolution.

<h2> Service Level Agreements (SLAs) </h2>
Set SLAs to define response and resolution times.

Navigate to Admin Panel > Manage > SLA Plans.
Create SLA plans with specific timeframes (e.g., 4 hours for high priority).
Assign SLA plans to departments or ticket categories.

<h2>Help Topics </h2>
Streamline ticket submission with predefined topics.

Go to Admin Panel > Manage > Help Topics.
Add topics such as "Network Issues" or "Billing Query."
Customize forms for each topic if needed.
