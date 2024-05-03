<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

Creating Tickets as end users

 - Navigate to end users osTicket URL:  http://localhost/osTicket/
 - Click open a ticket
   
<img src="https://i.imgur.com/JkW02hQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


- Create a ticket for end user Karen Doe
- Type "Karen@osticket.com" in email box
- Type "Karen Doe" in Full Name box
- Select Business Critical Outage for Help Topic
- Type "entire mobile online banking is down" in Issue Summary box
- Type "Customers are reporting they are getting a 404 error when browsing to online banking" in description box
- Click Create Ticket


<img src="https://i.imgur.com/bTgxHWT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


- Create a ticket for end user Ken Doe
- Click Open a New Ticket
- Type "Ken@osticket.com" in email box
- Type "Ken Doe" in Full Name box
- Select Personal Computer Issue for Help Topic
- Type "entire account department Adobe Reader not working" in Issue Summary box
- Type "Ever since the upgrade last night, nobody in accounting has been able to use adobe reader" in description box
- Click Create Ticket


<p>
<img src="https://i.imgur.com/iYbhGqY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Create a ticket for end user Karen Doe
- Click Open a New Ticket
- Type "Karen@osticket.com" in email box
- Type "Karen Doe" in Full Name box
- Select General Inquiry for Help Topic
- Type "When are we getting a hardware refresh" in Issue Summary box
- Type "Most of my department is having issues with their current tablets, we need this ASAP" in description box
- Click Create Ticket
</p>
<br />

<p>
<img src="https://i.imgur.com/zWSCdm5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Resolving Tickets

  - Log into osTicket as an administrator
  - Click Admin panel, click agents and select Jane Doe
  - Add Jane Doe to the Support Department and assign her Supreme Admin access

  <img src="https://i.imgur.com/0sEp9YG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  - Click Save Changes
  - Log into osTicket as an Jane Doe (http://localhost/osTicket/scp/login.php)
  - Observe the end users tickets that were recently created

<img src="https://i.imgur.com/0sEp9YG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 - Click on Karen Doe's "entire mobile online banking is down" ticket
 - Click on "Normal" in the Priority section.  Change to Emergency
    - Type "Business impacting event" in notes section
  - Click assigned to.  Assign this ticket to Karen Doe
  - Change Department to Systems Administrators
  - Change SLA to Sev-A
     - Type "Business impacting event" in notes section
     - Scroll down to Reply section
        - Type "Coordinating with Sys Admin Team to bring mobile banking back to life" in the text box below post reply
        - Click Post Reply
        - Type "Jerry corrected the error.  Mobile bank should be back up" in the text box
        - Change ticket status to resolved
        - Click Post Reply

      
<img src="https://i.imgur.com/1EGb44H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
