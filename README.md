<h1>Active Directory Home Lab</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>

I have set up several Home Active Directory labs in ProxMox, ESXi (VMWare), VirtualBox and Hyper-V. Below is the latest setup using ProxMox.
<br />

<h2> Hardware</h2>
- HP Z820 | 1x 2.00GHz Xeon E5-2620 | 16GB DDR3 | 1TB HDD | DVD-RW | Quadro K600<br>
- (x2) Samsung 16GB 2Rx4 PC3-12800R DDR3 ECC REG Server RAM M393B2G70BH0-CK0<br>
- (x4) 4TB 3.5" HDD <br>

<h2>Languages and Utilities Used</h2>

- ProxMox - My current virtualization platform of choice
- Windows Server 2019 - Main OS for AD DS
- Active Directory Domain Services (AD DS) - To create users and computers
- Group Policy Management Console (GPMC) - To create policies within the environment
- LDAP (Lightweight Directory Access Protocol)
- DNS to resolve hostnames within my network
- DHCP - provides IP address to all of my devices within my lab
- RSAT
- File Server Role - Dedicated to managing file shares and storage within my network
- Shadow Copies - To create point-in-time copies of files, allowing users to restore previous versions.
- Powershell - used for automating tasks and to configure Shadow Copies
- Samba - To share files between Linux servers and Windows PCs
  
<h2>Environments Used </h2>

- Windows Server 2019 - Virtual (21H2) - Main OS
- Windows 10 Professional - Virtual (22H2) - Workstations
- Windows 11 Professional - Virtual (22H2) - Workstations
- Ubuntu 24.04 LTS - Samba FS for file redudancy and to further Linux knowledge.
  
<h2>Monitoring</h2>

- Event Viewer
- Reliability Monitor
- 
<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
@@ text in purple (and bold)@@
```
--!>
