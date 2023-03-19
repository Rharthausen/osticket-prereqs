# osticket-prereqs<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- PHP Manager for IIS
- Rewrite Module
- PHP 7.3.8
- VC_redist.x86.exe
- MySQL 5.5.62 

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First you have to Create an Azure Virtual Machine Windows 10, 4 vCPUs.Then Open the: Installation Files. After Install / Enable IIS in Windows WITH CGI.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then in the installation files download and install PHP Manager for IIS, the Rewrite Module, download PHP 7.3.8, Create the directory C:\PHP. After download PHP 7.3.8, download and install VC_redist.x86.exe, download and install MySQL 5.5.62. Now Open IIS as an Admin and Register PHP from within IIS.Reload IIS, Open IIS, Stop then Start the server.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then Install osTicket v1.15.8. After Reload IIS and Open IIS, Stop and Start the server. After Go to sites -> Default -> osTicket
On the right, click “Browse *:80”. Rename: ost-config.php, Assign Permissions: ost-config.php. Continue Setting up osTicket in the browser. Then download and install HeidiSQL. Open Heidi SQL. after Continue Setting up osticket in the browser. and it should be working all ready.




</p>
<br />
