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
        - Type "Re-assigned to SEV-B, reached out to John for a warm handoff" in the text box below post reply
        - Click Post Reply
        - Type "Jerry corrected the error.  Mobile bank should be back up" in the text box
        - Change ticket status to resolved
        - Click Post Reply

      
<img src="https://i.imgur.com/1EGb44H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

Click on Ken Doe's "Entire Account Department Adobe Reader Not Working" ticket
 - Click on "Normal" in the Priority section.  Change to High
  - Click assigned to.  Assign this ticket to John Doe
  - Change Department to Systems Administrators
  - Change SLA to Sev-B
     - Scroll down to Reply section
        - Type "Re-assigned to SEV-B, reached out to John for a warm handoff" in the text box below post reply
        - Click Post Reply
  - Click Tickets tab

    
<img src="https://i.imgur.com/tGHnGbv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
- Click on Karen Doe's "When are we getting a hardware refresh" ticket
  - Click assigned to.  Assign this ticket to Jane Doe
  - Change Department to Systems Administrators
  - Change SLA to Sev-C
     - Scroll down to Reply section
        - Type "Hardware refresh is scheduled for Q1." in the text box below post reply
        - Change Ticket Status to "Resolved"
        - Click Post Reply

<img src="https://i.imgur.com/4rCQqW5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 - Log off of Janed Doe account and log into John Doe's account
 - Open "entire account department Adobe Reader not working" ticket
 - Scroll down to reply section and type "Rolled back version of Adobe Reader to previous version allowing them to work" in the text box
 - Click Post Note
 - Log out of John's account
 - Log in using administrator account
 - Click Agents, then click departments, click support department, click access tab
 - Change John's access to Supreme Admin
 - Click save changes
 - Log out of this account

<img src="https://i.imgur.com/P9S1Cpb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>   

  - Log in as John Doe
  - Open "entire account department Adobe Reader not working" ticket
  - Type "Figured out the problem, upgraded everyone.  Everyone's Adobe Reader works" in the text box below post reply
  - Change Ticket Status to "Resolved"
   - Click Post Reply

<img src="https://i.imgur.com/hA9ODMi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  


</p>
<br />
