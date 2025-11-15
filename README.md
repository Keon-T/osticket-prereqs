<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
 Outlines of the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows Server 2019 Datacenter 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS in windows with CGI
- From os ticket - installtion files install PHP Manager for IIS
- from osticket-installtion files install VC-redist.x86.exe
- from osticket-installtion files install MYSQL 5.5.62
- Install osticket v1.15.8 upload folder into c:\inetpub\wwwroot then rename "osticket"

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/peGURiE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create virtual machine install all dependencies in azure windows 10,4 vcpus named osticket-vm as username,labuser with password, osticketpassword1! using it log in remote desktop and open files of dependencies and download folder called "osticket-installation-files"
</p>
<br />

<p>
<img src="https://i.imgur.com/2oeV96Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
To enable IIS in windows with (CGI) open computer menu and go to the control panel ein programs tab click on (turn windows features on or off) and check internet information services web browser to expand it inside worldwide services and install (CGI) dependency</p>
<br />

<p>
<img src="https://i.imgur.com/zGec0e8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Registering (PHP) from within IIS making the web server aware of the existence of PHP on the computer in php manager click register new PHP version and binary executable for PHP after registing and restarting web server reload IIS Install osTicket v1.15.8

<br /># osticket-prereqs
