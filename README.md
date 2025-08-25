<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS (Internet Information Services)
- Install Web Platform Installer
- Install MySQL
- Set-up Username and Password
- Install C++ Redistributable
- Configure Permissions and Install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/pONz99g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>To begin setting up osTicket, you need to configure the server with the proper components. First, enable Internet Information Services (IIS) along with CGI and the necessary modules so that Windows can properly serve and process web pages. Next, install the Microsoft C++ Redistributable, which provides the runtime libraries required for PHP and several osTicket functions. Finally, use the Web Platform Installer (WPI), a Microsoft tool that makes it simple to add PHP, MySQL, and the extensions needed for osTicket to function correctly.
</p>
<br />

<p>
<img src="https://i.imgur.com/OIvkRdl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the server environment is ready, the next step is setting up the database. Install MySQL and create a new database specifically for osTicket. During this process, you will also need to set up a database username and password, which osTicket will use to securely connect to and manage its data.
</p>
<br />

<p>
<img src="https://i.imgur.com/F90jnmG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
With both the server and database prepared, you can now install osTicket. Begin by downloading the latest version from the official website and placing the files in the IIS web directory. Configure the necessary permissions to ensure osTicket can access and modify its files. Finally, run the installation script through your web browser, where you will provide the database details, set up your admin account, and complete the initial configuration.

<br />
# osticket-prereqs
