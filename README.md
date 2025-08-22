<p align="center">
<img src="https://github.com/bigbearbunkie/VPN-Setup-and-Usage/blob/main/IMG_6567.jpeg" height="20%" width="40%" alt="Proton VPN logo"/>
</p>

<h1>VPN Setup and Usage</h1>
This tutorial explains how to set up a VPN using ProtonVPN. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (22H2)

<h2>Prerequisites</h2>

- Create and log into a Windows 10 Virtual Machine
- Create a free Proton VPN account https://protonvpn.com/?srsltid=AfmBOor5Gqn9-R5DOHQ6HCuq95f9j7M31sMhotg0Z8AZ4xn9xp6RMzEX

<h2>Follow These Steps</h2>

<p>
Step 1: Check Your Personal IP Info
</p>

<p> + On your personal computer, browse to https://whatismyipaddress.com/</p>

<p> + Take note of your IP information in a text file</p>

<p>
Step 2: Your VM's IP Info
</p>

<p> + Log into your VM and browse to https://whatismyipaddress.com/</p>

<p> + Take note of your VM's IP information in a text file BEFORE you connect to the VPN so that you can compare it after</p>

<p>
<img src="https://github.com/bigbearbunkie/VPN-Setup-and-Usage/blob/main/prevpnip.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Step 3: Log in to Proton VPN 
</p>

<p> + On your VM, download Proton VPN, sign in, and pick a server (preferably one in a different country)</p>

<p>
<img src="https://github.com/bigbearbunkie/VPN-Setup-and-Usage/blob/main/vpnscreeshot.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Step 4: Observe the Changes
<p>

<p> + Once the VPN is connected, go back to https://whatismyipaddress.com/ on your VM</p>

<p> + If it shows the same IP information, refresh the page, and it should give you a completely new set of info for your VM as well as a new location</p>

<p>
<img src="https://github.com/bigbearbunkie/VPN-Setup-and-Usage/blob/main/postvpnip.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p> + Take note of the new IP information in your text file and compare it to the previous info. It should all be different. This is because the VPN makes it appear as though you are operating from a server located in whatever country you chose</p>

<p> + You can check websites such as Netflix and Google to see what they look like from the location you chose</p>

<p>
<img src="https://github.com/bigbearbunkie/VPN-Setup-and-Usage/blob/main/postvpnipb.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

</p>
<br />
