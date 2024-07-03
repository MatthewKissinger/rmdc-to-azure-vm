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

<h2>What is Remote Desktop Connection (RDP)?</h2>
<p>RDP (Remote Desktop Protocol) is a secure network protocol developed by Microsoft that enables users to remotely control and operate computers.</p>  
<p>This is a fundamental skill in IT for troubleshooting a client's PC and is becoming more and more necessary in the remote workspace. </p>


  
<h3> 1) Get the Public IP address of the virtual machine</h3>
<p>In order to connect to a computer with RDP you need only 3 things:</p>
<p>1: Public IP address of the computer</p>
<p>2: The user's username</p>
<p>3: The user's password</p>

<p>From the Microsoft Azure Homepage click on the Virtual Machines Icon [See Below]</p>

![image](https://github.com/MatthewKissinger/vm-ad-setup/assets/48774883/baddce6d-515a-45d2-88ee-490466fd3a6a)

<p>From here click on DC-1 </p>

![image](https://github.com/MatthewKissinger/vm-ad-setup/assets/48774883/d5e72456-2784-4d92-aa4e-1752a4427029)

<p>In the Overview panel, you will find the Public IP address under the Essentials dropdown menu.</p>

![image](https://github.com/MatthewKissinger/rmdc-to-azure-vm/assets/48774883/7f58db20-1426-451a-8174-e8ebd9fd3941)

<p>Copy or write the Public IP address down / save in a notes file</p>

<h3>2) Open Remote Desktop Connection and access the virtual machine DC-1</h3>

<p>From your windows search bar type in Remote Desktop</p>

<p>Click on the icon [see below]</p>

![image](https://github.com/MatthewKissinger/rmdc-to-azure-vm/assets/48774883/f073bbb7-34fc-416e-abda-39ffe69b3361)

<p>The Remote Desktop Connection app should display this screen: </p>

![image](https://github.com/MatthewKissinger/rmdc-to-azure-vm/assets/48774883/5fd6fb22-1636-4b23-bae8-e39f4c5b5b78)

<p>Copy in the Public IP address you saved from earlier in the Computer field. </p>

<p>A windows security screen will pop up, choose 'Use a different account'.</p>

![image](https://github.com/MatthewKissinger/rmdc-to-azure-vm/assets/48774883/7b889bb9-2d2a-460a-ac53-ec031a2c44eb)

<p>Type in the user name and password for DC-1 that you saved from the previous tutorial.</p>

<p>A security warning page will pop up, ignore and press Yes</p>

![image](https://github.com/MatthewKissinger/rmdc-to-azure-vm/assets/48774883/4382b6ff-255c-446b-baee-3a26a10894a3)

<p>Congrats you are now logged into a different computer from withing your own computer! Pretty neat.</p>

<h3>3) Repeat steps 1 and 2 to access the Client-1 virtual machine</h3>

<h4>Thank you for following along!</h4>
  
<p>In the next tutorial we will be connecting ensuring a connection between the 2 virtual machines</p>

