<p align="center">
<img src="https://i.imgur.com/pIwaoFB.png"/>
</p>

<h1>How to Create a Virtual Machine In Microsoft Azure</h1>
This is a tutorial on how to create a Virtual Machine in Microsoft Azure.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Log in to Microsoft Azure account
- Step 2: Select virtual machine 
- Step 3: Select create
- Step 4: Select Azure virtual machine
- Step 5: Set virtual machine name and image
- Step 6: Set virtual machine size and login
- Step 7: Create virtual machine
- Step 8: Wait for deployment to complete
- Step 9: Review virtual machine 
- Step 10: Open RDP and enter IP address
- Step 11: Log in with username and password

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/uSZt7dU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first step is to go to www.portal.azure.com and log into your Microsft Azure account.
</p>
<br />

<p>
<img src="https://i.imgur.com/mKUGNeb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the main screen select the "Virtual machines" icon.
</p>
<br />

<p>
<img src="https://i.imgur.com/x8ZQAPU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the Virtual machines page select create.
</p>
<br />

<p>
<img src="https://i.imgur.com/2FoTxV2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select Azure virtual machine. This will create a cloud based virtual machine hosted by Microsoft.
</p>
<br />

<p>
<img src="https://i.imgur.com/XyI7tNH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On this screen there a multiple sections to fill out. In the Project Details section you must choose the subscription you wish to use. Then you can either choose a resource group name, or let the system generate one for you. In the Instance Details section you must create a virtual machine name. For this tutorial I used PracticeVM. For region be sure to select a region that is close to you, or close to other resources the virtual machine will be interacting with. I have selected (US) East US as my region for this example. For Availability options leave it set to Availability zone, and Availability zone to Zones 1. Leave security set to Standard. Under Image select Windows 10 Pro, version 21H2 - x64 Gen2. Leave VM architecture set to x64.
</p>
<br />

<p>
<img src="https://i.imgur.com/PuaCCBX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Scroll down the page until you see the options in the image above. In the dropdown menu next to Size you will select the type of cpu and ram you would like for your virtual machine. For this example I have selected Standard_B1s - 1 vcpu, 1 GiB memory. This means the virtual machine will have 1 virtual cpu and 1 gigabyte of ram. The price will vary depending on your selection. In the Administrator account section you will have to create a username and password for the virtual machine. Be sure to remember what you enter here, or you will not be able to log into your virtual machine. Under Inbound port rules select Allow selected ports in the Public inbound ports section, as well as RDP (3389) next to Select inbound ports. This will allow you to remotely connect to your virtual machine. Finally under Licensing check the box to confirm you have an eligible copy of Windows 10. Then select Review + create at the bottom of the page. 
</p>
<br />

<p>
<img src="https://i.imgur.com/7T0MGmV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This next page will validate your virtual machine to make sure all fields were filled out correctly, and give you a summary of the virtual machine and its hourly cost. After reviewing the information click Create at the bottom of the page.
</p>
<br />

<p>
<img src="https://i.imgur.com/3KYN8tm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now you will be on the virtual machine deployment page. Be sure to wait here until the screen says that the virtual machine deployment is complete. From here you can either click the Go to resource button, or you can click Home in the top left of the screen. Once on the home screen you can select the Virtual machines icon from image number 2. 
</p>
<br />

<p>
<img src="https://i.imgur.com/mLNHGak.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now you will be on the virtual machine resource page. Here you will be able to see all the specific information about your new virtual machine. While on this page you will want to copy the public IP address of the virtual machine so you can log into it using Remote Desktop Protocol.
</p>
<br />

<p>
<img src="https://i.imgur.com/hcBTtoV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next you will want to open Remote Desktop Connection on your computer. You can do this by clicking on the Windows search bar in the bottom left corner of your PC. Type in RDP and select open. You should then see a box open on your screen like the image above, and type in the IP address of the virtual machine and click connect. 
</p>
<br />

<p>
<img src="https://i.imgur.com/aNvMjfo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next you will have to enter the username and password you created for the virtual machine. Once entered press OK and you will see the Windows login screen for the virtual machine appear in a new window. Congratulations your new virtual machine is now ready to use.
</p>
<br />
