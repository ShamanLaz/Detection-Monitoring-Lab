<h1>Detection & Monitoring Lab</h1>

<h2>Description</h2>
Created a dynamic virtual homelab environment, mirroring enterprise networks. Employed tools like Pfsense, Splunk, Kali Linux, and Security Onion to explore vulnerabilities and enhance threat detection skills. Practiced offense and defense scenarios, refining incident response strategies. All credit goes to the original author Day Johnson: https://cyberwoxacademy.com/building-a-cybersecurity-homelab-for-detection-monitoring/
<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash</b> 
- <b>Command Prompt</b>
- <b>VMware Workstation Pro 17</b>
- <b>PowerShell</b>
- <b>Pfsense</b>
- <b>Splunk</b>
- <b>Active Directory</b>
- <b>Security Onion</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (22H2)
- <b>Kali Linux Virtual Machine (VM)</b>
- <b>Ubuntu Server Virtual Machine (VM)</b>
- <b>Windows Server 2019 Virtual Machine (VM)</b>
- <b>Windows 11 (22H2) Virtual Machine (VM)</b>
- <b>pfsense Virtual Machine (VM)</b>
- <b>Security Onion Virtual Machine (VM)</b>

<h2>Program walk-through:</h2>

<p align="center">
Installed & configured pfsense VM adding 5 additional network adapters for the VM settings: <br/>
<img src="https://i.imgur.com/t0D7l0S.png" height="80%" width="80%" alt="pfsense VM config"/>
<br />
<br />
Fully configured pfsense and each interface that will be running: <br/>
<img src="https://i.imgur.com/8OV04L1.png" height="80%" width="80%" alt="pfsense full config"/>
<br />
<br />
 Installed & configured Security Onion adding 2 additional network adapters for the VM settings: <br/>
<img src="https://i.imgur.com/gBgUilp.png" height="80%" width="80%" alt="SecOnion VM config"/>
<br />
<br />
 Fully configured Security Onion : <br/>
 <img src="https://i.imgur.com/jUoSud6.png" height="80%" width="80%" alt="Security Onion Full Config"/>
 <br />
 <br />
 Accessed the web interface for Security Onion via Ubuntu Server/Desktop: <br/>
 <img src="https://i.imgur.com/NzKyQbP.png" height="80%" width="80%" alt="Security Onion Web Interface"/>
 <br />
 <br />
 Installed & configured Kali Linux VM settings changing the network adapter in the process to VMnet2: <br/>
 <img src="https://i.imgur.com/IQB1tjj.png" height="80%" width="80%" alt="Kali Linux VM Settings"/>
 <br />
 <br />
 Using Kali Linux accessed pfsense web interface and fully configured the interfaces on the network: <br/>
 <img src="https://i.imgur.com/Xx4j1vu.png" height="80%" width="80%" alt="pfsense Web Interface"/>
 <br />
 <br />
 Installed & configured the Windows Server 2019 VM settings changing the network adapter in the process to VMnet3: <br/>
 <img src="https://i.imgur.com/cTVdm4Y.png" height="80%" width="80%" alt=""/>
 <br />
 <br />
 Setup an Active Directory domain using Windows Server 2019 as the domain controller: <br/>
 <img src="https://i.imgur.com/fwA7nFx.png" height="80%" width="80%" alt="Win Server 2019"/>
 <br />
 <br /> 
 Installed & configured the Windows 11 VM settings changing the network adapter in the process to VMnet3: <br/>
 <img src="https://i.imgur.com/MOP8Oig.png" height="80%" width="80%" alt="Win11 VM Settings"/>
 <br />
 <br />
 Setup and joined the Windows 11 VM to the Windows Server 2019 VM domain: <br/>
 <img src="https://i.imgur.com/uIo6IOy.png" height="80%" width="80%" alt="Win11 Fully Configured"/>
 <br />
 <br />
 Configured Ubuntu Server VM settings to add a network adapter for splunk set to VMnet6: <br/>
 <img src="https://i.imgur.com/6Z72t84.png" height="80%" width="80%" alt="Ubuntu Server VM Settings"/>
 <br />
 <br />
 Installed and configured Splunk on the Ubuntu Server VM, accessing the web interface: <br/>
 <img src="https://i.imgur.com/qW9xw4k.png" height="80%" width="80%" alt="Splunk Web Interface"/>
 <br />
 <br />
 Installed Universal Forwarder on the windows server 2019, to forward logs to the Splunk interface: <br/>
 <img src="https://i.imgur.com/vVunzzZ.png" height="80%" width="80%" alt="Splunk Universal Forwarder"/>
 <br />
 <br />
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
