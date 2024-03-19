<p align="center">
<img src="https://i.imgur.com/nKkd5Vz.png" alt="Active Directory logo"/>
</p>

<h1>Active Directory</h1>
How to deploy on-premises active directory and create users in azure.<br />
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory
<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
<h2>Deployment steps</h2>

- On Domain Controller enable ICMPv4 in on the local windows Firewall
  <img src="https://i.imgur.com/OSmxM7L.png" height="80%" width="80%"/>
- Setup a new forest as whatever domain name
   <img src="https://i.imgur.com/MuiHSQE.png" height="80%" width="80%"/>
- Create an Organizational Units to set which user is which(Admins, Employees etc)
   <img src="https://i.imgur.com/VZ0y6Bz.png" height="80%" width="80%"/>
- Create users with code and run the script on Powershell_ISE
   <img src="https://i.imgur.com/0iQXj1B.png" height="80%" width="80%"/>
  
  
