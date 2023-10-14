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

- Create Domain Controller VM and Client VM in Azure
- Use same resource group for both VMs
- Ensure both VMs are in same Vnet
- Install Active Directory
- Create an Admin and Normal User account in AD
- Join Client VM to your domain
- Setup Romote Desktop for non-admin users on Client VM
- Create additional users and attempt to login to Client VM with one of the users

<h2>Deployment and Configuration Steps</h2>

<p> 1. Create Domain Controller VM and Client VM in Azure


  

<img src="https://i.imgur.com/Dw7SOfz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>



<p> 2. Use same resource group for both VMs
<p> 3. Ensure both VMs are in the same Vnet
<p> 4. Install Active Directory



  
<img src="https://i.imgur.com/Md6fyWk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>



<p> 5. Create an admin and normal user account in AD
</p>
<br />

<p>
<img src="https://i.imgur.com/KfuESO5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


<p> 6. Join Client VM to your domain
<br />



<img src="https://i.imgur.com/UqVouOi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>




<p> 7. Setup remote desktop for non-admin users on client VM
<p> 8. Create additional users and attempt to login to client Vm with one of the users




<img src="https://i.imgur.com/58rFPqz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>




<p> 9. Close resource groups/VMs




<p> 9. Close resource groups/VMs
