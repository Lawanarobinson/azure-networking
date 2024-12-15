<p align="center">
  <img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Testing VPN Connection and IP Location with Azure Virtual Machines</h1>
This tutorial covers testing the IP address on a local machine, checking the IP location on a Virtual Machine (VM) without a VPN, and testing the IP location with a VPN on the local machine.

<h2>Environments and Technologies Used</h2>

- **Microsoft Azure (Virtual Machines/Compute)**
- **Remote Desktop (RDP)**
- **ProtonVPN (Free Plan)**
- **Browser (for testing IP location)**
- **WhatIsMyIPAddress (IP address checker)**

<h2>Operating Systems Used</h2>

- **Windows 10 (VM on Azure)**
- **Local Machine (for VPN setup)**

<h2>High-Level Steps</h2>

1. **Check Local Machine’s IP Address**  
   Open a browser on the local machine and go to [WhatIsMyIPAddress](https://whatismyipaddress.com/). Note the IP address displayed.

2. **Test IP Location Without VPN on Virtual Machine**  
   Log into a Virtual Machine (VM) on Azure. Open a browser and visit [WhatIsMyIPAddress](https://whatismyipaddress.com/) to check the IP address.

   ![Watch the video on Testing IP](https://img.youtube.com/vi/YFNkjJf3lo8/0.jpg) 

   In this video I will demonstrate how to check your IP address on your own computer as well as on a Virtual Machine. You wiil create n Proton VPN account on your personal computer, then logon on the Virtual Machine and download Proton VPN. While that is loading you can go to "WhatIsMyIPAddress" from within the Virtual Machine and take note of it. Once Proton is downloaded, open the file and Install it. Click on the download according to our Virtual Machine and "create VPN location". Refresh "WhatIsMyIPAddress" and watch IP location change. Then close everything out and go Azure Portal and delete the resource group containing the VM in Azure to avoid unnecessary charges.

   *Click [here](https://www.youtube.com/watch?v=Rq3iiZJ1eVs) to watch a video demo.*


<h2>Actions and Observations</h2>

<p>
  The local machine’s IP address shows the actual location. The VM’s IP address reflects the region of the VM. With ProtonVPN enabled, the local machine’s IP address will show the location of the VPN server (e.g., Japan).
</p>

<h2>Conclusion</h2>
This demonstration illustrates how VPNs alter IP addresses and their impact on network security.
