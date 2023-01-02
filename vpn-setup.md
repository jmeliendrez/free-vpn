<p align="center">
<img src="https://www.howtogeek.com/wp-content/uploads/2022/11/ProtonVPN-logo-on-a-white-background.jpg" height="60%" width="60%" alt="Proton VPN Logo"/>
</p>

# 🏗️ Setting Up A VPN
<p></p>

## Video Demonstration

- ### [YouTube: Setup a VPN in the Cloud](https://www.youtube.com)

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Microsoft Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Azure Subscription
- Reliable Internet Connection

<h2>Setup Process</h2>


<p>
First you need to "remote" into the VM. If you haven't already, make sure that you have a virtual machine deployed and ready to use in Azure. If using Windows go to Start and type in Remote desktop. Then select the "Remote Desktop Connection". I use macOS so you need to download Microsoft Remote Desktop from the App store. 
</p>

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>

When you're in the application, either type in the VM's public IP address (Windows) or select "Add PC" and then enter the IP address (macOS). Connect to the machine. A new window will open up and you will be prompted to log in using the credentials you created when you made the VM. Enter these and hit **ENTER**. 

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>

Then click **Continue**

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>

Once connected to your Virtual Machine you should see a standard Windows 10 desktop. Go to the web browser and type http://protonvpn.com. Create a free account. This gives you access to 3 sites to connect to globally.

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>

Once you've created your account, then login and navigate to the **Downloads** page. 

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>

Select the Windows.  

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>

Then click **Download Proton VPN**.

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>

Once the installer has downloaded, click **Open file** to run the installation. Click **Next** until you reach **Install**, then click **Install**.

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>

Once installed, Proton VPN will open and you'll need to login. 

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>

Once logged in, you will be presented with the window below. On the left hand pane you are given the option of which VPN server you would like to connect to. 

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>

Since we are using the free-tier, we only have the U.S., Netherlands and Japan available to us. Select one of these to connect to.

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>

While the VPN is connecting to the server the connection to the Virtual Machine will be interrupted. The Virtual Machine will re-establish the connection by itself. If not, simply reconnect to it.

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>



