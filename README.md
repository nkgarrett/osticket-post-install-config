<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

<b>(Post Installation Setup)</b>

<b>Click http://localhost/osTicket/scp/login.php and log into your account</b>
<br> <br>
<b>1. Configure</b> 
<a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html">Roles</a> </b>
  * Admin Panel -> Agents -> Roles
  * Supreme Admin<br>
  
<b>2. Configure</b>
<a href="https://docs.osticket.com/en/latest/Admin/Agents/Departments.htmlzz">Departments</a><br>
 * Admin Panel -> Agents -> Departments<br>
 * System Administrators
<br>

<b>3. Configure</b><a href="https://docs.osticket.com/en/latest/Admin/Agents/Teams.html">Teams<br>
* Admin Panel -> Agents -> Teams<br>
      i. Level I Support<br>
      ii. Level II Support

  
<b> 4. Allow anyone to create tickets</b>
<br>
  * Admin Panel -> Settings -> User Settings<br>
  * Registration Required: Require registration and login to create tickets 
<br>

<b>5. Configure</b> <a href="https://docs.osticket.com/en/latest/Admin/Agents/Agents.html">Agents</a> (workers)
<br>
 * Admin Panel -> Agents -> Add New<br>
   i. Jane<br>
  ii. John

<b> 6. Configure Users</b> <a href="https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html">(customers)</a>
<br>
 * Agent Panel -> Users -> Add New<br>
   i. Karen<br>
  ii. Ken

<b> 7. Configure</b> <a href="https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html">SLA</a>
<br>
  * Admin Panel -> Manage -> SLA<br>
   i. Sev-A (1 hour, 24/7)<br>
   ii. Sev-B (4 hours, 24/7)<br>
   iii. Sev-C (8 hours, business hours)

<b> 8. Configure Help Topics</b>
<br>
 * Admin Panel -> Manage -> Help Topics<br>
  i. Business Critical Outage<br>
  ii. Personal Computer Issues<br>
  iii. Equipment Request<br>
  iv. Password Reset<br>


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
