<p align="center">
<img src="https://i.imgur.com/jKfy3JS.png" alt="Azure Logo"/>
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

<h2>Setup Steps</h2>


<p>
First you need to "remote" into the VM. If you haven't already, make sure that you have a virtual machine deployed and ready to use in Azure. If using Windows go to Start and type in Remote desktop. Then select the "Remote Desktop Connection". I use macOS so you need to download Microsoft Remote Desktop from the App store. 
</p>

When you're in the application, either type in the VM's public IP address (Windows) or select "Add PC" and then enter the IP address (macOS). Connect to the machine. A new window will open up and you will be prompted to log in using the credentials you created when you made the VM. Enter these and hit **ENTER**. 

Then click **Continue**

Once connected to your Virtual Machine you should see a standard Windows 10 desktop. Go to the web browser and type http://protonvpn.com. Create a free account. This gives you access to 3 sites to connect to globally.

Once you've created your account, then login and navigate to the **Downloads** page. Select the Windows 
<p>
<img src="" height="80%" width="80%" alt=""/>
</p>
<br />



You have successfully setup and deployed 2 virtual machines in Azure. In the section on network analysis we will be going through how to connect to our Windows machine to work from.
