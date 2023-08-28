# osTicket
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
First we will use osTicket as an enduser too create tickets. Use this link (http://localhost/osTicket/). Click on "Open a New Ticket" 
</p>
<br />
<img src="https://i.ibb.co/ZKGF8Nd/step1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next fill in the empty spaces for ticket inquiry. For this example we are going with Karen reporting a "Business Critical Outage" ticket explaining that the mobile banking system is down 
</p>
<br />
<img src="https://i.ibb.co/P5FYQ9C/step1-2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.ibb.co/TKGCCrn/step1-3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Click "Create Ticket" once completed, it should create the ticket and bring you to this page.
</p>
<br />
<img src="https://i.ibb.co/Fsvp2J4/step1-4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next we will make another example from Karen creating a ticket with less severity. This ticket will be a "General Inquiry" ticket about the updates on new equipment. 
</p>
<br />
<img src="https://i.ibb.co/0QkpJgK/step1-6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Now we will log on as an agent we've created back in the last lab (jane.doe) 
</p>
<br />
<img src="https://i.ibb.co/wJCcDWz/step1-7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
You can see once we have logged in, the tickets we've created as Karen or enduser will pop up.
</p>
<br />
<img src="https://i.ibb.co/rpMHcjr/step1-8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Click ticket "767948", we will want too edit the priority level for this ticket since having the mobile banking system login down is business impacting event. Click "Normal" for the priority and change it into "Emergency".
</p>
<br />
<img src="https://i.ibb.co/xSBr5GW/step1-9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.ibb.co/M7PN4F6/step2-0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Write the reason why it will be an emergency, for this example the bank will not be able too run because the customers cannot log onto the mobile banking system. Select "Update" once you have completed it
</p>
<br />
<img src="https://i.ibb.co/Dw8xq2L/step2-1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next we will change the severity of the SLA, to do this select "Default SLA" button
</p>
<br />
<img src="https://i.ibb.co/vPKbYwx/step2-2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Select "SEV-A" since we have created that SLA plan for the most severe tickets and having a mobile banking system down is critical event for business
</p>
<br />
<img src="https://i.ibb.co/51tCvSR/step2-3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
We can see that the SLA plan has changed to Sev-A. Next we will want too transfer this ticket too the "System Adminstrators" department because they are more equipped too handle a ticket like this. It seems more of a programming technical issue. Select "Support" in the Department too start the transfer.
</p>
<br />
<img src="https://i.ibb.co/PDjRX5B/step2-4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Select "System Adminstrators" and write down the reason for the transfer. Press the transfer button after too complete the action
</p>
<br />
<img src="https://i.ibb.co/9wdKVLK/step2-5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.ibb.co/jDPY2t5/step2-6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Now that we have sent the ticket too "System Adminstrators" we can resolve the ticket. Open the ticket, write down that you have resolved it, and closed the ticket. Make sure you change the ticket status on the bottom too resolve the ticket.
</p>
<br />
<img src="https://i.ibb.co/yVsBGtq/step2-7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Congratulations! You have resolved your first ticket!
</p>
<br />
<img src="https://i.ibb.co/qpY4Y7B/step2-8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
We can see that the ticket we have just created is in the "closed" section
</p>
<br />
<img src="https://i.ibb.co/cK5WwRV/step2-9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next we will start the second ticket. Select the "General Inquiry" ticket 
</p>
<br />
<img src="https://i.ibb.co/ng2Grq3/step3-0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Select the SLA plan for this , we will want too put this on low severity since this is just a question 
</p>
<br />
<img src="https://i.ibb.co/kKFyq04/step3-1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Change it too low priority since it does not impact business operations
</p>
<br />
<img src="https://i.ibb.co/kmgXNDj/step3-2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next we will want too change it too a low priority SLA-plan (Sev-C). Select "Default SLA" too change the SLA
</p>
<br />
<img src="https://i.ibb.co/vkMK190/step3-3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Update the SLA-plan into SEV-C. It is a low priority que because it does not impact business operations and it is just an general inquiry question.
</p>
<br />
<img src="https://i.ibb.co/x2460WM/step3-4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Now post the reply that new equipment will be coming in and they are welcome too use their own equipment at the office. (Resolving the ticket) Select "Resolved" and post the reply too close out the ticket.
</p>
<br />
<img src="https://i.ibb.co/FxkW3tC/step3-5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
We can now see that we have closed out 2 tickets. 
</p>
<br />
<img src="https://i.ibb.co/84P6Lc9/step3-6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Congratulations! You have created your own tickets and resolved them! You can see that there are no more open tickets in the section. This has concluded the lab.
</p>
<br />
<img src="https://i.ibb.co/5KJqf0G/step3-7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

