<h1>Azure Sentinel Tutorial Map</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
In this lab, I created a cloud based SIEM which is also a virtual machine in the cloud, using Azure Sentinel. I made the VM vulnerable to different IP Addresses from many different countries all over the world, creating a honey pot. I then take this data and display it on a map so all the attacks can be monitored and we can see where they are all coming from.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Microsoft Azure</b>
- <b>Windows Powershell ISE</b>
- <b>Event Viewer</b>

<h2>Environments Used </h2>

- <b>Windows 11 Pro</b> (21H2)
- <b>Remote Desktop</b>

<h2>Program walk-through:</h2>

<p align="center">
Create Virtual Machine: <br/>
https://i.imgur.com/nghOqbll.png
<br />
<br />
Create Log Analytics Workspace to store logs and connect SIEM to display geo data:  <br/>
https://i.imgur.com/F5eCIeK.png
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
