# ActiveDirectoryLab
<h1>JWipe - Disk Sanitization</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

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
<img src="Admin account.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
  Instal ADDS from Server Manager/ Add Roles <br/>
<img src="installing ADDS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
