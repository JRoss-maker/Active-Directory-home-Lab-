![image](https://github.com/JRoss-maker/Active-Directory-home-Lab-/assets/67971410/09a6271d-db47-4d3a-b544-42da8a9be6b7)# ActiveDirectoryLab




<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b></b>

<h2>Environments Used </h2>

- <b>Windows 10, Windows Server, VirtualBox</b> 

<h2>Program walk-through:</h2>

<p align="center">
Download VirtualBox: <br/>
<img src="download virtualbox.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Download Windows Server:  <br/>
<img src="server download.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Download Windows 10: <br/>
<img src="download windows.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create new Virtual Box: File + new  <br/>
<img src="DC Vbox.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up VirtualBox hardware & Harddisc, network and settings:  <br/>
<img src="Vbox hardware.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="vbox hard disc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="vbox DC network.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="vbox settings.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch the VM to boot and select the ISO file from download folder  <br/>
<img src="vbox iso boot.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 allow Windows server to boot than set up password   <br/>
<img src="DC password.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 In the DC identify network adapters on the internal adapter assign the Ip adressing  <br/>
<img src="network adapters .png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="IPV4 address .png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Instal ADDS from Server Manager/ Add Roles <br/>
<img src="installing ADDS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Create domain Add new forest  <br/>
<img src="configure forest.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="configure domain.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
  After restart we now have an Admin account, from start menu select options to create a dedicated admin account <br/>
<img src="Admin account.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="Adnin1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="create admin.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
  Create an Orginizational unit under the new domnain with new user <br/>
<img src="ou.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="ou admins.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="new user.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="admin new user.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="Screenshot 2024-06-14 154211.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="Screenshot 2024-06-14 154319" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="Screenshot 2024-06-14 154043.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="Screenshot 2024-06-14 154541.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up NAT configuration <br/>
<img src="nat1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="nat2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="nat3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="nat4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="nat5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="nat6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="nat7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="nat8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="nat9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="nat10.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="nat11.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure DHCP <br/>
<img src="dhcp1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="nat8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp10.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp11.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp12.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp13.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp14.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp15.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp16.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp17.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp18.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dhcp19.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Create users with powershell script  <br/>
<img src="powershell1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell10.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell11.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell12.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell13.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell14.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell15.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="powershell16.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Create Client computer  <br/>
<img src="Client1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="Client2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client3.png.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="Client10.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client11.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client12.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client13.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client14.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client15.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client16.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client17.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client18.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client19.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="client20.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
