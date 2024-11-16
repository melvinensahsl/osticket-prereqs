<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

<ol>
  <li>download osTicket-Ins</li>
  <li>Install/Enable IIS in Windows with cgi</li>
  <li>Unzip PhP 7.3.8 from osTicket-Install-Files</li>
  <li>instill VC_redist.x86.exe from osTicket-Install-Files</li>
  <li>Install MySQL 5.5.62 from osTicket-Install-Filws</li>
</ol>
<img src="https://github.com/user-attachments/assets/7f0948ec-4d26-4a99-862f-853ee5632333" height="80%" width="80%" alt="Installing SQL"/>
<p>
Installing a MySQL database for the osticketing system. Select normal setup, run configuration wizard (after installation), choose standard settings, and use root as both login and password.
</p>
<br />
<img src="https://github.com/user-attachments/assets/a4373b20-37e4-4b49-b8e4-165b4ae39126" height="80%" width="80%" alt="Set up PHP manager"/>
<p>
Open IIS (Information Internet Service) as administrator and navigate to sites-default-osTicket. Open the PHP management and choose to activate or disable extension. After activating some extensions, reload osTickt in the browser.
</p>
<br />
<img src="https://github.com/user-attachments/assets/a59c4e64-7a6a-4f0e-816e-d454b2c1bbbf" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Open Heidi SQL and create a database called "osTicket", fill in the information on the osTicket browser including email, and password, and create a primary administrator account. Include the database recently created by Heidi
</p>
<br />
