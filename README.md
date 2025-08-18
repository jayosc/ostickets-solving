<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Creating & Solving Tickets</h1>
This project identifies a common issue in the workplace and solves the problem in the ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket
- Active Directory

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Solving the Problem </h2>

<p>
<img src="https://i.imgur.com/ylSGAuC.jpeg" height="80%" width="80%" alt="1"/>
</p>
<p>
John Doe is working from home and is accessing his work computer using remote desktop. He is having a password problem and has locked his work account. He now realizes his caps lock was on, and that's what was causing his password to be put in incorrectly. 
</p>
<br />

<p>
<img src="https://i.imgur.com/hVzl2ei.jpeg" height="80%" width="80%" alt="2"/>
</p>
<p>
John Doe submits his work order request to have his account unlocked so that he can type in his password correctly and get to work.
</p>
<br /># ostickets-solving

<p>
<img src="https://i.imgur.com/Elmq5Kw.jpeg" height="80%" width="80%" alt="3"/>
</p>
<p>
I get to work and log in to osTicket. I see that there is a ticket request in open status regarding a locked account.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZYOBuQr.jpeg" height="80%" width="80%" alt="4"/>
</p>
<p>
I open the ticket and see that an account unlock is needed for a specific user account. Since this person remembers their password, a password reset is not necessary at this time.
</p>
<br />

<p>
<img src="https://i.imgur.com/oVGNXth.jpeg" height="80%" width="80%" alt="4"/>
</p>
<p>
This is a screenshot that was attached to the ticket of the error message that this user is receiving.
</p>
<br />

<p>
<img src="https://i.imgur.com/znJU2mj.jpeg" height="80%" width="80%" alt="5"/>
</p>
<p>
I've loaded Active Directory, so that I can see all users and look for the specific user name that John Doe provided, bac.bub. 
</p>
<br />

<p>
<img src="https://i.imgur.com/EqQB9p1.jpeg" height="80%" width="80%" alt="6"/>
</p>
<p>
I've found the user and opened the account properties. 
</p>
<br />

<p>
<img src="https://i.imgur.com/98Gmr38.jpeg" height="80%" width="80%" alt="7"/>
</p>
<p>
I've clicked on the account section.
</p>
<br />

<p>
<img src="https://i.imgur.com/2k5MPKt.jpeg" height="80%" width="80%" alt="8"/>
</p>
<p>
I've found the unlock account button and checked it. I then click apply and ok to unlock the account.
</p>
<br />

<p>
<img src="https://i.imgur.com/eLLzfT3.jpeg" height="80%" width="80%" alt="9"/>
</p>
<p>
I then go back to osTicket, update the user, and finish out the ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/kDnOQH4.jpeg" height="80%" width="80%" alt="10"/>
</p>
<p>
The ticket is now resolved and in the closed section of osTicket.
<br />

<p>
<img src="https://i.imgur.com/HdlhhDl.jpeg" height="80%" width="80%" alt="11"/>
</p>
<p>
Here is the user logging in to the remote desktop using their correct username and password.
</p>
<br />

<p>
<img src="https://i.imgur.com/yGNK1AW.jpeg" height="80%" width="80%" alt="12"/>
</p>
<p>
The user is able to successfully log in to the computer after the account has been unlocked. 
</p>
<br />

<p>
<img src="https://i.imgur.com/z5jNMZf.jpeg" height="80%" width="80%" alt="13"/>
</p>
<p>
Here is the user fully logged in and ready to get to work for the day.
</p>
<br />
