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
Create Azure Sentinel and add to Log Analytics Workspace:
https://i.imgur.com/c0t0zk6.png
<br />
<br />
Access remote Desktop:  <br/>
https://i.imgur.com/QA3fPHz.png
<br />
<br />
open ipgeolocation to optain a API key for precicise location of failed logins: <br/>
https://i.imgur.com/Mmo7IFl.png
<br />
<br />
Open & run script on Powershell ISE on remote desktop to look through security log and grab all events of people who failed to login by their IP Address :  <br/>
https://i.imgur.com/Nn9J13K.png
<br />
<br />
Creat your Map to pinpoint failed login attempts around the world:  <br/>
https://i.imgur.com/kQfB6m6.png
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
