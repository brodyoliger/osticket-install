<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This example covers the prerequisites and the installation of the open-source help desk ticketing system osTicket. The installation of osTicket will be done from scratch and all major steps in this process will be listed with brief descriptions.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Windows Virtual Machine and Network)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Windows 10 Virtual Machine in Azure and Remote Desktop
- Internet Information Services and CGI enabled
- Programs needed to install and run osTicket
- IIS and PHP manager to configure and run osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/vEVpyLB.png" height="80%" width="80%" alt="osticket"/>
</p>
<p>
Within Microsoft Azure I created resource group, Windows 10 21H2 Virtual Machine within resource group as well as virtual network for VM to use. I then connected to the VMs public IP address via Remote Desktop to gain control and begin steps to get osTicket installed and running.
</p>
<br />

<p>
<img src="https://i.imgur.com/kmHNZ0W.png" height="80%" width="80%" alt="osticket"/>
</p>
<p>
Enabled Internet Information Services as well as CGI within Control Panel to allow for PHP manager neede for osTicket and installation of the osTicket program itself.
</p>
<br />

<p>
<img src="https://i.imgur.com/9Y1xjdH.png" height="80%" width="80%" alt="osticket"/>
</p>
<p>
Downloaded, installed and configured all programs required to both run the osTicket program and the SQL Database(HeidiSQL) for osTicket to use.
</p>
<br />

<p>
<img src="https://i.imgur.com/VAf4oFR.png" height="80%" width="80%" alt="osticket"/>
</p>
<p>
After osTicket installation and SQL Database configuration it was time for the Administrator as well as Agent accounts to be created and configured, assigned their own access, permissions and teams. End-user accounts would also be made to fully simulate the ticket lifecycle from creation by end-user to resolution by help desk agent.
<br />

