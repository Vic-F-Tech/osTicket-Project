<h1>Updating and Closing a Ticket</h1>
This demonstration shows how to update and close a mock service ticket that an end user created using osTicket. The osTicket environment in this scenario is downloaded on a Windows 10 Virtual Machine created through Microsoft Azure that I am connecting to via Remote Desktop Protocol (RDP). <br />

<h2>Environments and Technologies used</h2>

- Microsoft Azure
- Remote Desktop Protocol
- osTicket

<h2>Operating Systems Used</h2>

- Windows 11 (Local Device)
- Windows 10 (Virtual Machine)

<h2>Updating and Closing Steps</h2>

- Updating the ticket to provide more accurate information
- Closing the ticket to completion

<br />

<h2>Updating a mock ticket in osTicket</h2>

<p>
  <img src="" height="80%" width="80%">
</p>
<p>You come into work first thing in the morning and see you have an urgent email from the manager of the online banking department saying her employyes are reporting that users are unable to access their online banking portal. You then immediately start the process of creating a ticket before you call the online banking manager to get more information. To create a ticket on osTicket, you want to open your agent login page for osTicket which should bring you to this screen. Input your login credntials then press enter.</p> <br/>

<p>
  <img src="" height="80%" width="80%">
</p>
<p>Once you get to this screen make sure you are on the "Tickets" tab. Here you will want to click "New Ticket" to begin creating a new ticket.</p><br />

<p>
  <img src="" height="80%" width="80%">
</p>
<p>Once this screen appears, you will input the email, phone, or name to search for the manager that reported the issue to you initially, in the case of this porject, the manager of the banking departments name is Melissa. Select Melissa when her information populates.</p><br />

<p>
  <img src="" height="80%" width="80%">
</p>
<p>When this screen comes up click "Continue".</p><br />

<p>
  <img src="" height="80%" width="80%">
</p>
<p>Here you will want to set the "Ticket Source" to "Email" because you recieved the notice from Melissa via email. Then you want to set the "Help Topic" to "Report a Problem" because the problem has been reported but you do not know all the details or to which extent the problem is. Is it truly a system outage or is there a more miniscule issue not being fully communicated? For the "Issue Summary" text box below "Ticket Details", describe the summary of the issue that Melissa had reported about. For the "Deatils on the reason(s) for opening the ticket." text field undeerneath, describe the details of the issue that Melissa emailed you. Then, click "Open" at the bottom of the page.</p>

<h2>Connecting to the Windows 10 Virtual Machine using Remote Desktop Protocol (RDP)</h2>

<p>
  <img src="" height="80%" width="80%">
</p>
<p>You should see this screen indicating that the VM deployment is complete. From here you can click "Go to resource" to access you VM resource you just created.</p><br />

<p>
  <img src="" height="80%" width="80%">
</p>
<p>Once you get to this screen you are going to want to copy the "Public IP addreess". This is the IP address that we will use to connect to using RDP. At the bottom of the screen in your Windows 11 Operating System search bar search for and open "Remote Desktop Connection".</p><br />

<p>
  <img src="" height="80%" width="80%">
</p>
<p>Once the Remote Desktop Connection window pops up, input the Public IP address of the Windows 10 VM you just created into the "Computer: " field. Then click "Connect". You will then be asked to enter your credentials. These are the credentials I asked you to create and save when we created the VM in Microsoft Azure. After you enter your credentials click "Okay".</p><br />

<p>
  <img src="" height="50%" width="50%">
</p>
<p>When this screen pops up, just click "Yes". Once you click "Yes" you will begin to connect to your Windows 10 VM and you can continue to configure the privacy settings of the VM Operating System upon start up. Now you can start using the Windows 10 VM as if it was an actual Windows 10 device sitting in front of you.</p>
