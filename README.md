# osTicket-Prerequisites
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites </h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Internet Connection
- Credit/debit Card (Free 200 Azure credit)
- Azure Account (Access portal)
- Azure services Resource Group and Virtual Machine
- RDP (Remote Desktop Connection) to enter are Virtual Machine

<h2>Prerequisites Steps</h2>

<p>
<img src="https://i.imgur.com/nN1GVPx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The purpose of the lab is to develop practical skills of a IT Help Desk Professional which include creating, interacting, and closing tickets. Here we have are blueprint for the osTicket Lab.
</p>
<br />

<p>
<img src="https://i.imgur.com/EcpQGbv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
These two Azure services will be are foundation for the osTicket Lab.
</p>
<br />

<p>
<img src="https://i.imgur.com/ptK2HmK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we are going to select are resource group. The resource group should be empty and with have a button that says create resource group. Click on that button and this page should appear. Next below subscritpions give the resource group a name (ex. RG-LAB) and select Review + create.
</p>
<br />
<img src="https://i.imgur.com/bukNp8Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the resource group is validated select create and headover to the virtual machine service within Azure. Select Create Vitural Machine, and the page displayed above with prompt. Select the resource group created (RG-LAB) and give the VM a name (ex.VM-osT). select your respected region and image select windows 10 Pro. Further below there will be size, select Standard_D4s-V3-4 Cpus and create any username and password for the administrator account (Document the username and password will be needed for LAB). Dont forget to check the licensing below as well and similar to previous step select Review + Create and are VM will be set. 
</p>
<br />
<p>
<img src="https://i.imgur.com/UyaZ78o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After are VM is created we will head back into the VM services within Azure. From there we will select the created VM and look for are Public Ip Address. As show above we will go into are windows search bar and find are RDP(Remote Desktop Connection)Tool and enter the Public Ip address.
</p>
<br />
<p>
<img src="https://i.imgur.com/GLPC2p2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we have entered are public Ip address, there will be a prompt that appears to enter your credentials. These credentials were created earlier, enter those credentials. After that you will RDP into the VM, from there open upa web browser and enter the link listed here within your VM <a href='https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6'>Link</a>
</p>
<br />
<p>This will conclude the Prereq's for the osTicket Lab. The next steps for the lab are the configurations. Next steps <a href='https://github.com/DevilDog2001/post-install-config'>OsTicket Installation.</a> </p>
