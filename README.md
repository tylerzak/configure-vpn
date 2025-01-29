<p align="center">
<img src="https://i.gyazo.com/37b70eefcfa22f88a8b8547177731937.jpg" height="80%" width="80%" alt="VPN Picture"/>
</p>

<h1>Proton VPN - Installation</h1>
This tutorial outlines the step-by-step process for installing Proton VPN to ensure secure and private internet access.<br />

<h2>Environments and Technologies Used</h2>

- Proton VPN (Virtual Private Network)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Procedures</h2>

- Create a Virtual Machine in Azure
- Sign Up and Install Proton VPN
- Test the VPN Connection
- Observe the Differences Between Connections

<h2>Installation Steps</h2>

<p>
<img src="https://i.gyazo.com/f21bb85ab7219dcd16c2e0cf8a4b0690.png" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
I started by creating a new virtual machine (VM) within Microsoft Azure. The VM configuration was selected based on my desired specifications, such as the region and operating system. Once the VM was successfully provisioned, I ensured it was ready for remote access.
</p>
<br />

<p>
<img src="https://i.gyazo.com/f563212d7120ee0ed2f48402dc10bff8.png" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/1f21aed85f3704d3255a63da30ff97cf.jpg" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/6b8b102cc627ee5e681de36da45d035a.png" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
After the virtual machine was set up, I proceeded to sign up for a Proton VPN account. Following the account creation, I downloaded and installed the Proton VPN client on the VM. The installation process was straightforward, and I ensured the client was properly configured before proceeding.
</p>
<br />

<p>
<img src="https://i.gyazo.com/939f6b5ea4d7b738479c305abc2f3f86.png" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/3ab93880b73d4b6eb59633425e15ff51.jpg" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/5ec1597a49d3c1803f349bab2d67b114.png" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
To establish a baseline, I visited whatismyipaddress.com on the VM to record its original IP address, ISP, and location. Afterward, I connected to a Proton VPN server located in Japan. Once the VPN connection was established, I revisited the same website and observed the changes: the IP address, ISP, and location had all shifted to reflect the Japanese server, confirming that the VPN was working properly.
</p>
<br />

<p>
<img src="https://i.gyazo.com/bcbfd57da64cb9229d84d12f7c1b69d9.jpg" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/90f7f7e3939252de6d708b2e843bc0b8.jpg" height="80%" width="80%" alt="Configure VPN Steps"/>
</p>
<p>
Finally, I conducted a practical test by opening Bing on the virtual machine. I searched for the term “Disney” both while connected to the VPN and again after disconnecting from the VPN. I observed that, while connected to the Japan server, the search results were tailored to the region (with Japanese language content and region-specific results). When disconnected, the search results reverted to the standard English version, indicating that the VPN connection influenced the language and regional search results.
</p>
<br />
