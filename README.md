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
  * Add new role -> Supreme Admin -> ALL access to ALL permissions <br>
  
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
<b>1. Configure Roles</b><br>

![image](https://github.com/nkgarrett/osticket-post-install-config/assets/156832893/f065f46e-4ddf-424b-bfed-658e119f1b5e)

<br/>
<b>4. Allow anyone to create tickets</b><br>
Be sure to leave registration required blank
<p>

 ![image](https://github.com/nkgarrett/osticket-post-install-config/assets/156832893/588d03ab-9cef-458e-b7ea-e51730b2e712)



</p>
<b> 5. Configure Agents (workers) </b> <br>
Create/remember credentials to be able to log in
Make sure these boxes are empty

![image](https://github.com/nkgarrett/osticket-post-install-config/assets/156832893/4ad050d9-e219-423c-a03a-ad373afae2c6)
<br>
<b>Configure Jane's settings:</b>
  * Department -> System Administrators -> Supreme Admin
  * Teams -> Level II Support

![image](https://github.com/nkgarrett/osticket-post-install-config/assets/156832893/1a8cf75c-fc25-4894-97e4-836e743c125a)

<br>
<b>Configure John's settings:</b><br> 
  * Department -> Support -> View Only<br>
  * Extended Access -> Support

  ![image](https://github.com/nkgarrett/osticket-post-install-config/assets/156832893/d2a153b5-84a3-481a-9420-44ca055b7a98)

<br />
<br>
<b>7. Configure SLA</b><br>
   i. Sev-A (1 hour, 24/7)
   
![image](https://github.com/nkgarrett/osticket-post-install-config/assets/156832893/97fdd003-2ee8-4f06-8b06-5d5c82e89803)

<p>
<b>8. Configure Help Topics</b><br>
    i. Business Critical Outage

 ![image](https://github.com/nkgarrett/osticket-post-install-config/assets/156832893/a2127338-ef5a-4560-859f-85957ca3a689)

</p>
<br />
