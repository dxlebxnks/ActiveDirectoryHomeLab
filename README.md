<h1>Active Directory Home Lab</h1>



<h2>Description</h2>

This repository holds the setup and documentation of my home lab, I've built up my lab from YouTube guides and other free online documentation.

<h2>Updates</h2>
- 8.10.24 <br>
- Added Windows Server Core VM and created Lab.local domain <br>
- Added DNS Server Tools and Remote Remote Sever tools including AD DS and AD LDS Tools to my Windows Server 2022 File Server VM to be able to administer domain with GUI. <br>
- Installed OpenSSH on both servers. Tested connectivity to both with PuTTY. <br>
   
<br />

<h2> Hardware</h2>
- <a href="https://support.hp.com/us-en/product/details/hp-z820-workstation/5225041">HP Z820 Server</a> | 1x 2.00GHz Xeon E5-2620 | 16GB DDR3 | 1TB HDD | DVD-RW | Quadro K600<br>
- <a href="https://semiconductor.samsung.com/us/dram/module/rdimm/m393b2g70bh0-ck0/">Samsung 16GB 2Rx4 PC3-12800R DDR3 ECC REG Server RAM M393B2G70BH0-CK0</a> (x2)<br>
- 4TB 3.5" HDD (x4) <br>
- <a href="https://shop.kingston.com/products/datatraveler-exodia-usb-flash-drive?variant=39392789528768">Kingston 128GB DataTraveler Exodia SuperSpeed+ USB 3.1 (Gen 1) Flash Drive<a></a> for ProxMox VE UI <br>
- <a href="https://www.amazon.com/HAMTYSAN-Raspberry-Pi-Monitor-Non-Touch/dp/B0B8S9DYQC">HAMTYSAN Upgraded Raspberry Pi Screen Monitor, 7 Inch </a> for onsite  maintenance of HP Z820 server

<h2>Languages and Utilities Used</h2>

<h2>Utilities</h2>
<ul>
  <li><a href="https://www.proxmox.com/proxmox-ve">ProxMox</a>: My current virtualization platform of choice.</li>
  <li><a href="https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019">Windows Server 2019</a>: Main OS for Active Directory Domain Services (AD DS).</li>
  <li><a href="https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/active-directory-domain-services-overview">Active Directory Domain Services (AD DS)</a>: Used to create users and computers.</li>
  <li><a href="https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/gpmc">Group Policy Management Console (GPMC)</a>: Tool for creating and managing policies within the environment.</li>
  <li><a href="https://ldap.com/ldap-directory/">LDAP (Lightweight Directory Access Protocol)</a>: Protocol for accessing and maintaining distributed directory information services.</li>
  <li><a href="https://www.cloudflare.com/learning/dns/what-is-dns/">DNS (Domain Name System)</a>: Resolves hostnames within my network.</li>
  <li><a href="https://docs.microsoft.com/en-us/windows-server/networking/technologies/dhcp/dhcp-top">DHCP (Dynamic Host Configuration Protocol)</a>: Provides IP addresses to all devices within my lab.</li>
  <li><a href="https://docs.microsoft.com/en-us/windows-server/remote/remote-server-administration-tools">RSAT (Remote Server Administration Tools)</a>: Tools for managing roles and features on remote servers.</li>
  <li><a href="https://docs.microsoft.com/en-us/windows-server/storage/file-server/file-server-role">File Server Role</a>: Dedicated to managing file shares and storage within my network.</li>
  <li><a href="https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/vssadmin">Shadow Copies</a>: Creates point-in-time copies of files, allowing users to restore previous versions.</li>
  <li><a href="https://docs.microsoft.com/en-us/powershell/scripting/overview">PowerShell</a>: Used for automating tasks and configuring Shadow Copies.</li>
  <li><a href="https://www.samba.org/">Samba</a>: Allows file sharing between Linux servers and Windows PCs.</li>
</ul>


<h2>Networking Utilities</h2>
<ul>
  <li><a href="https://www.wireshark.org/">Wireshark</a>: For network packet analysis, useful in troubleshooting.</li>
  <li><a href="https://www.putty.org/">Putty</a>: For SSH access to my Ubuntu / Samba file servers.</li>
  <li><a href="https://opnsense.org/">Opnsense</a>: A firewall/router software, sometimes used for managing network traffic within the lab.</li>
</ul>

  
<h2>Environments Used </h2>

<ul>
  <li><a href="https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019">Windows Server 2019 - Virtual (21H2)</a>: Main OS.</li>
  <li><a href="https://www.microsoft.com/en-us/windows/get-windows-10">Windows 10 Professional - Virtual (22H2)</a>: Workstations.</li>
  <li><a href="https://www.microsoft.com/en-us/windows/get-windows-11">Windows 11 Professional - Virtual (22H2)</a>: Workstations.</li>
  <li><a href="https://ubuntu.com/download/server">Ubuntu 24.04 LTS</a>: Samba FS for file redundancy and to further Linux knowledge.</li>
</ul>
  

<h2>Monitoring Tools</h2>
<ul>
  <li><a href="https://learn.microsoft.com/en-us/shows/inside/event-viewer">Event Viewer</a>: For monitoring system and security logs within Windows Server.</li>
  <li><a href="https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/tools-monitor-performance-counters-and-events">PerfMon</a>: For monitoring performance metrics on the server.</li>
</ul>


<h2>Backup and Restore Tools</h2>
<ul>
  <li><a href="https://docs.microsoft.com/en-us/windows-server/backup/windows-server-backup">Windows Server Backup</a>: Set up regular backups for your File Server, including shadow copies.</li>
  <li><a href="https://docs.microsoft.com/en-us/windows-server/backup/restore-files-using-shadow-copies">Shadow Copy Client</a>: Users can restore previous versions of files using the "Previous Versions" tab in Windows Explorer on client machines.</li>
  <li><a href="https://www.idrive.com/">iDrive</a>: Cloud backup and storage installed on Windows File Server.</li>
</ul>






