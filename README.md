<p align="center">
<img src="https://i.imgur.com/THMn4w9.png" alt="Virtual Machine"/>
</p>

<h1>Creating a virtual machine</h1>
This will outline how to create a virtual machine (VM) in Azure. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10
- Ubuntu Server 20.04

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/6j2cFjc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> 
Either click resource group in the "Azure services" section or find it by searching "resource groups" at the top.
</p>

<p>
<img src="https://i.imgur.com/8ocdK8O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Creating a resource group CAN be skipped if you just want to make a VM. Im just doing this so I can have a singular resource group for a couple VMs I want to have on the same Vnet. Azure WILL automatically make one if you dont manually create one named after whatever name you give your VM. 
</p>
<br />

<p>
<img src="https://i.imgur.com/djuRx4z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Same idea as before, you can click it in the "Azure services" section or search "Virtual machines" in the search bar at the top.
</p>
<br />


<p>
<img src="https://i.imgur.com/ztwBzt6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/v7ep5ZI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If you've previously made a resource group then you could find it in the drop down menu there. Otherwise Azure would create one for you.
</p>
<br />


<p>
<img src="https://i.imgur.com/YSxLjod.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You can choose the image (OS/application) here. Anything with 2vcpus works for the size
</p>
<br />


<p>
<img src="https://i.imgur.com/jCHbOqW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Choose "Password" for the authentication type for the admin account. Create a username and password. This will be the username and password used when connecting to the VM using RDP. Check the licensing box at the bottom (windows only).
</p>
<br />


<p>
<img src="https://i.imgur.com/rtHCZI6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Review + create after everthing's done. Azure will give a TOS.
</p>

<p>
<img src="https://i.imgur.com/m1t6Gqi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/AjAjFhb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now the VM is created
</p>
<br />


<p>
<img src="https://i.imgur.com/AjAjFhb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
VM is deployed. It can be accessed using RDP with the public IP of the VM and the username and password made earlier.
</p>
<br />

