# Osticket-prereqp align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1 set up Azure virtual machine
- Item 2 install MYSQL,PHP
- Item 3 set up osticket database
- Item 4 download and configure osticket
- Item 5 complete osticket instalation via web

<h2>Installation Steps</h2>

![image alt](https://github.com/TracyBartholomew/Osticket-prereq/blob/b7e154c3cb604f44fe507f94d43ba97130d25787/IMG_0353.jpeg)
</p>
<p>
Here’s a 5-step guide to install osTicket on Microsoft Azure:

1. Set Up a Virtual Machine on Azure

	•	Log in to your Azure Portal and navigate to Virtual Machines.
	•	Click on Create a Virtual Machine, select your desired region, and choose a Linux (Ubuntu or windows)          distribution.
	•	Choose an appropriate size for your VM and configure networking (allow HTTP and HTTPS traffic).
  •	Enable the required PHP modules and restart Apache:. Install Required Software
  •	After logging into the VM, install the necessary components for osTicket:
  •	Log into MySQL to create a database and user for osTicket:
  •	Run the following commands inside MySQL to create the database and user:
<p>
![image alt](https://github.com/TracyBartholomew/Osticket-prereq/blob/6c2d8865741d15e5200d06d673d38a176c0b4e00/IMG_0350.jpeg)
</p>
<p>
•	Open your browser and access the osTicket installer by visiting:

•	Follow the setup instructions, enter your MySQL database information, and complete the configuration.
•	After installation, remove the /setup directory for security:

<p>
![image alt](https://github.com/TracyBartholomew/Osticket-prereq/blob/2aa56292d0f10e51ec28f080de05656c9a1fc725/IMG_0350.jpeg)
</p>
Now osTicket should be running successfully on Azure!
