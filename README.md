<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Remote Desktop
- Internet Information Services (IIS)
- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Internet Information Services
- enabled IIS and installed PHP Manager for IIS
- Downloaded Rewrite Module
- MySQL
- configure permissions and installed osTicket
- Installed HeidiSQL and created a database. Started and cconnected to a new session

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/P7dfpK8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. (Create Virtual Machine in Azure)
- Create a Resource Group
- Create a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs
- (When creating the VM, allow it to create a new Virtual Network (Vnet))

</p>
<br />

<p>
<img src="https://i.imgur.com/1HKg1QQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2.Create an Azure Virtual Machine Windows 10, 4 vCPUs
- Name: Vm-osticket
- Create a Username & Password

</p>
<br />

<p>
<img src="https://i.imgur.com/DklkuFJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3.Added all necessary properties for the virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/44sI4vb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Opened Remote Desktop, I will then press add PC and proceed with the next set of steps. It asked for an IP address in order to connect to the virtual machine I created. In order to do that I copied the public IP address from the VM and inputed it there in the PC name section.
</p>
<br />

<p>
<img src="https://i.imgur.com/SulZsuM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Input the user and Password created when I made the RG/VM in Azure.
</p>
<br />

<p>
<img src="https://i.imgur.com/lDX5jeo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. On the Microsoft Remote Desktop, I have went to the control panel and turned on Internet Information services. With it expanded I selected world wide web, expanded that, and then went to application development features and allowed CGI. We need cgi with iis because it allows us to install php manager. Php is a backend web programming language and osTicket runs off of php
</p>
<br />

<p>
<img src="https://i.imgur.com/JvOw9gA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7.
</p>
<br />

<p>
<img src="https://i.imgur.com/E9ycyp7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8.
</p>
<br />

<p>
<img src="https://i.imgur.com/i4UTXLB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
9.
</p>
<br />

<p>
<img src="https://i.imgur.com/5QAuSeC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
10.
</p>
<br />

<p>
<img src="https://i.imgur.com/K8Alzao.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
11.
</p>
<br />

<p>
<img src="https://i.imgur.com/X3Dhywb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
12.
</p>
<br />

<p>
<img src="https://i.imgur.com/Es59jWW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
13.
</p>
<br />

<p>
<img src="https://i.imgur.com/EgxMY6B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
14.
</p>
<br />

<p>
<img src="https://i.imgur.com/FBqr1SS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
15.
</p>
<br />

<p>
<img src="https://i.imgur.com/ARP6AZJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
16.
</p>
<br />

<p>
<img src="https://i.imgur.com/5vmkOdk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
17.
</p>
<br />

<p>
<img src="https://i.imgur.com/53G14FS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
18.
</p>
<br />

<p>
<img src="https://i.imgur.com/39qGLu4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
19.
</p>
<br />
