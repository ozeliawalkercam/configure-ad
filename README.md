<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3


<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://[i.imgur.com/DJmEXEB.png](https://i.imgur.com/Dc4HuIR.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set up resources in Azure by creating a domain controller virtual machine using Windows Server 2022 and a client virtual machine using Windows 10.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ensured connectivity between the client and domain controller virtual machines.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installed active directory and created admin and normal user accounts. Set-up remote desktop for non-administrative users on the client 1 virtual machine created. Created mutiple additional users and used Windows PowerShell to log in to the client virtual machine with one of the users created.
</p>
<br />
