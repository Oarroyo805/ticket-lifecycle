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

<h2>Example 1 </h2>

<p>

![1](https://github.com/user-attachments/assets/62b74217-6532-43e4-9dc1-4729f4fed345)

</p>
<p>
Summary: Creating a Ticket as End User Karen in osTicket

Access the osTicket End User Portal

Go to http://localhost/osTicket.

Click on "Open a New Ticket".

Log in as Karen

Enter Karen’s email address and password.

Create a New Ticket

Help Topic: General Inquiry → Other

Issue Summary: Accounting department needs Adobe upgrade/broken

Issue Details: "It looks like many people in the accounting department can't use their Adobe software."

Submit the Ticket

Click Create Ticket.
</p>
<br />

<p>

![2](https://github.com/user-attachments/assets/def54d54-98bf-4c9d-ae40-1d3e4a93b24d)

</p>
<p>
Summary: Logging in as John to Work on the Ticket in osTicket

Go to http://localhost/osTicket/scp/login.php.

Log in with John’s credentials.

Inspect the Ticket

Locate the newly created ticket.

Click on it to view details.

Update the Ticket

Based on a scenario where only 2 people are unable to open Adobe Reader, update the ticket:

SLA: Change to Sev-C

Internal Note: "Only 2 people unable to open Adobe Reader, classifying as Sev-C."

Click Update.

Assign the Ticket

Assign the ticket to John Doe.

Click Save Changes.
</p>
<br />

<p>

![3](https://github.com/user-attachments/assets/c5928fcb-4a03-451e-a251-2acc89e58ddf)

</p>
<p>
Summary: Working the ticket

Scroll Down to "Post Reply"

Enter a Response:

"Customer states only 2 people in the accounting department are unable to open and use Adobe Reader. Customer testing restart and will call back after lunch."

Click "Post Reply"
</p>
<br />

<p>

![4](https://github.com/user-attachments/assets/877dbc5d-c33b-4777-8b9b-0ae77028eb49)

</p>
<p>
Summary: Resolving the Ticket in osTicket

Scroll Down to "Post Reply"

Enter: "Customer states that restarting the computer fixed the issue. Closing ticket now."

Click Post Reply.

Change Ticket Status

Scroll up to Status.

Change from Open to Resolved.

Click Save Changes.
</p>
<br />

<h2>Example 2 </h2>

<p>

![1b](https://github.com/user-attachments/assets/2662a278-c564-463d-8243-61f8ac91cb98)

</p>
<p>
Summary: Creating a Ticket as End User Karen

Go to the osTicket End User Portal

Open http://localhost/osTicket.

Create a New Ticket

Click "Open a New Ticket".

Enter Karen’s email address and password.

Fill Out Ticket Details

Help Topic: Report a Problem → Personal Computer Issues.

Issue Summary: "CFO’s laptop will no longer turn on."

Issue Details: "Laptop won’t power on, despite pressing the power button."

Submit the Ticket

Click "Create Ticket".
</p>
<br />

<p>

![2b](https://github.com/user-attachments/assets/588db84e-41b9-4253-a42f-4d50e34985ca)

</p>
<p>
Summary: Working the Ticket as John Doe

Login as John Doe

Go to http://localhost/osTicket/scp/login.php.

Enter John’s credentials to access the admin panel.

Locate and Inspect the Ticket

Find the new ticket regarding the CFO’s laptop issue.

Click on the ticket to review the details.

Update SLA and Notes

Change the SLA to Sev-B.

Add a note: “May reclassify after getting more info.”

Assign the Ticket

Assign the ticket to John Doe for further troubleshooting.
</p>
<br />

<p>

![3b](https://github.com/user-attachments/assets/ab20d44d-1a75-4ccd-90bc-bdfab87ec4a2)

</p>
<p>
Summary: Working the ticket

Scroll Down to the Post Reply Section.

Enter the Update:

"After inspecting the CFO’s laptop in their office, I found that the issue was due to a broken charger. The laptop is now successfully charging."

Post the Reply to document the resolution progress.
</p>
<br />

<p>

![4b](https://github.com/user-attachments/assets/195b77fe-15bb-400c-b249-4dcadee7d0e8)

</p>
<p>
Summary: Closing the Ticket

Since the issue is resolved, no need to post another reply.

Scroll up to the status section.

Change the status from "Open" to "Resolved."

The ticket is now closed.
</p>
<br />
