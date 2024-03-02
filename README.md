<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br/>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows Windows 10 (21H2)

<h2>List of Prerequisites</h2>

- Connect to your Virtual Machine with Remote Desktop
- Install / Enable IIS in Windows
- Install Web Platform Installer
- Install osTicket v1.15.8
- Download and Install HeidiSQL
- Created database for "osTicket
- Clean up 
- Change File Permissions

<br>________________________________________________________________________________________________________________________<br>

<h2>📝 Installation Steps - Part A: Create a 'Resource Group'</h2><br>

<h3>1. ) Starting at the 'Home' screen in your Microsoft Azure Portal</h3>

 >**Click: the 'Resource Groups' icon that's already on your home screen or..**

 >**You can Search: 'Resource Groups' and click that one. It will take you to the same place, which is the 'Resource Groups Default Directory'.**

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/osticket-prereqs/assets/161680745/d273a110-a34c-4707-8a06-058d12c11cc5"><br>

 >**NOTE: You can make a 'Resource Group' at the same time you create a VM. I just wanted to show you how to do it step-by-step.**
 
<h2></h2><br>

<h3>2. ) After that, select 'Create' to start your resource group</h3>

 >**Or..**

 >**You can click the blue 'Create' in the middle of the screen as well, and it will take you to the same place.**
 
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/osticket-prereqs/assets/161680745/56fec2c9-0ba3-4e35-8c26-6bc6e7e6313b"><br>

<h2></h2><br>

<h3>3. ) Next, we'll input the following:</h3>

 >**ATTENTION: Double check spelling when creating anything (resource groups, virtual machines, etc.) or you will have to delete it all and start over, because once it's created the information you initially inserted will NOT be able to be edited (name, region, etc.)**

 >**Resource Group Name: RG-osTicket**

 >**Region: (US) West US 3**

 >***Scroll Down**

<img width="1511" alt="E2C30B0C-FA81-4329-8F23-DBB018C41018" src="https://github.com/vincentchachere/osticket-prereqs/assets/161680745/4829d10a-d483-4c28-93a1-64034a6e0cf3"><br>

<h2></h2><br>

<h3>4. ) Now, let's click 'Review + Create'</h3>

 >**Dont worry about the 'Tags' section, we don't need that part for this lab.**

 >**The 'Tags' section is used for organizational purposes.**

<img width="1511" alt="F462BC66-31ED-444E-A61B-CD02C75151FD" src="https://github.com/vincentchachere/osticket-prereqs/assets/161680745/22252a11-ece8-4e38-873c-f6faf00efe29"><br>

 >**NOTE: We have NOT finished creating the resource group yet by clicking 'Review + Create'. Microsoft Azure let's you double check (review) the information you input before finalizing (creating) your resource group. It also does this for virtual machines, so make it a habit to double check the information you type in, so that you don't have to erase everything you end up creating, because of one wrong letter.**

<h2></h2><br>

<h3>6. ) Finally, we review and create!</h3>

 >**Look over the resource group information**

 >**Verify its all correct**

 >**Click 'Create' to bring alive our first resource group!**

<img width="1511" alt="6353AD56-C708-4D3D-ABEB-7C29A8E42E5F" src="https://github.com/vincentchachere/osticket-prereqs/assets/161680745/2f2d3265-2f3f-457f-a710-1be04c7d9545"><br>

<h2></h2><br>

<h3>🎊CONGRATS!🎉</h3>

<img width="1509" alt="D85CECB1-2110-411B-822C-33E0AA5D395C" src="https://github.com/vincentchachere/osticket-prereqs/assets/161680745/5e6c3401-9de6-497f-8aff-a1c59a83507c"><br>

 >**However, the mission isn't over.

________________________________________________________________________________________________________________________<br>

<h2>📝 Installation Steps - Part B: Create a 'Resource Group'</h2><br>

<h3> 7. ) Now we Refresh and Go inside our newly created Resource Group</h3>

 >**First, click Refresh then if your resource group doesnt pop up..**
 >**Click 'Refresh' and it should show up.**

<img width="1509" alt="D562A5D5-19D6-423B-BB96-A794E4869CCF" src="https://github.com/vincentchachere/osticket-prereqs/assets/161680745/28151172-7ca9-49ec-823f-14686998d4a6"><br>

 >**NOTE: If your resource group doesnt show up just go through the steps again, and if it doesn't let you create a resource group with 'RG-osTicket' (the name you originally typed in), then that's how you know it went through and you just have to wait a minute, refresh your 'Resource Groups Default Directory', and let technology do its thing.**

<h2></h2><br>

<h3>8. )<h3></h3>

 >**
 >**





