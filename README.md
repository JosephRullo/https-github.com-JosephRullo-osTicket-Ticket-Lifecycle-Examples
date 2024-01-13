<p align="center">
<img src="https://imgur.com/C9d2T2j.png" height="80%" width="80%" alt="Disk Sanitization Steps alt="osTicket logo"/>
</p>
<h1> <p align="center"> osTicket - Ticket Lifecycle: Intake Through Resolution </h1> 
<p align="center"> This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.
<br />
<br />
<br /> 
<br />
<h1></h1>
<br />


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

****Note**** Please view these tutorials for a full explanation of those steps.
<p>
https://github.com/josephrullo/osTicket-Prerequisites-and-Installation
<p>
https://github.com/josephrullo/osTicket---Post-Install-Configuration

<h2>Lifecycle Stages</h2>

<h2>Step 1.</h2> 

**User Sign In**
<p>
Let's begin with signing in as one of the users that was created in the previous installation and configuration of osTicket. In this example the user will go to http://localhost/osTicket/ and click on "Sign in" in the upper right corner. Now enter in the Username and Password that was assigned to them and click "Sign In".
<p>
<p>
<img src="https://i.imgur.com/cCrb2nP.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/0xAnA8Q.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Step 2.</h2> 

**Create New Ticket**
<p>
After signing in as a User, go to the "Open New Ticket" tab at the top of the screen. Now choose a "Help Topic" that best fits the issue that is occuring -> Next type in an "Issue Summary" of the problem. -> below that enter in a more detailed description of what's going on so that the Agents have a good idea of what's going on and how to resolve it. -> click "Create Ticket" to submit it. Now you can see the newly created ticket, with it's own ticket number next to the "Issue Summary", the date and time created, the User who issued it, and the description of the problem.
<p>
<p>
<img src="https://i.imgur.com/bDkiuYs.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/0xAnA8Q.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/fAAkSJZ.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Step 3.</h2> 

**Submit Additional Tickets**
<p>
Now for practic let's submit additional tickets with varying issues and topics for the Agents to resolve.
<p>
<p>
<img src="https://i.imgur.com/mcKbi2h.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/im11vWx.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/YGQYiia.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Step 4.</h2> 

**Agent Sign In**
<p>
Now that several tickets have been submitted, it's time for the Agents to respond to them. Let's begin by signing in as one of the Agents (in this case Jane Doe) we created in the previous tutorial. 
<p>
<p>
<img src="https://i.imgur.com/XogvqBw.jpg" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Step 5.</h2> 

**Answering Tickets**
<p>
Now that several tickets have been submitted, it's time for the Agents to respond to them. Let's begin by signing in as one of the Agents (in this case Jane Doe) we created in the previous tutorial. The Agent notices that there is a "Emergency" priority level ticket that is effecting the shopping cart of the business. They click on the ticket to open it to examine it further. The Agent can now see that this ticket is showing that customers are unable to view their shopping cart to complete purchase. They check above and take note of the following: "Priority" is set to "Emergency", the "Help Topic" is set to "Business Critical Outage", the "SLA Plan" is set to "Sev-A" (the higest SLA that was setup in the previous tutorial, that needs to be answered within 1hr on a 24/7 schedule) and that the Department is set to "Support". After reviewing this, the considers the severity and knows that the System Administrators are responsible for all "Business Critical Outage" tickets and reassigns it to their Department. They do this by clicking on the "Support" Department highlighted in blue and selects "System Administrators", and leaving a note explaining why they are transferring it.
<p>
<p>
<img src="https://i.imgur.com/XogvqBw.jpg" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/UggAnmT.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/TyVoyUJ.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
