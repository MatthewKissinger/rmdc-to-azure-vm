<p align="center">
  <img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Microsoft Azure Tutorial</h1>
<h2>Connect to a Microsoft Azure VM via Remote Desktop Connection</h2>
<p>This tutorial outlines the prerequisites and the process of connecting to a virtual machine from the cloud computing platform Microsoft Azure with Microsoft Remote Desktop Connection.</p> 
<p>We will first create a Domain Controller VM (named DC-1) with the windows server OS, then create a Client VM (named Client-1).</p>  

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer) online portal
- Windows 10 / 11 OS
- Remote Desktop Connection App

<h2>Operating Systems Used </h2>

- Windows 10 / 11

<h2>List of Prerequisites</h2>

- Microsoft Azure Account (Free version of $200 credits available)
- Personal Computer running Windows 10 or 11
- Completed Part 1 of my tutorial series [Setup and configure Virtual Machines for Active Directory Deployment]

<h2>What is Remote Desktop Connection?</h2>

<p>A Windows Domain Controller is essentially any server that has Active Directory Domain Services installed.</p>
<p>Its job is to handle authentication requests across the domain (network of computers). </p>
<p>You can have several Domain Controllers in a network, but there is always only one Main Domain Controller, and the primary reason for multiple Domain Controllers is to replicate important data.</p>
  
<h3> 1) Get the Public IP address of the virtual machine</h3>

<p>From the Microsoft Azure Homepage click on the Virtual Machines Icon [See Below]</p>

![image](https://github.com/MatthewKissinger/vm-ad-setup/assets/48774883/baddce6d-515a-45d2-88ee-490466fd3a6a)

<p>From here click on DC-1 </p>

![image](https://github.com/MatthewKissinger/vm-ad-setup/assets/48774883/d5e72456-2784-4d92-aa4e-1752a4427029)







<h3>Thank you for following along!</h3>
  
<p>In the next tutorial we will be connecting ensuring a connection between the 2 virtual machines</p>

