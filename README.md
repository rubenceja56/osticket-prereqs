 <p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial will cover the basic prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install osTicket software and unzip file into desktop.
- Install / Enable IIS in Windows WITH CGI
World Wide Web Services -> Application Development Features -> [X] CGI
- Install PHP Manager, Rewrite Module, unzip PHP into directory, install VC_redist, and MySQL
- Rename upload folder to "osTicket" and move it from extracted into inetpub > wwwroot
- Add/disable any features you need within IIS, PHP manager.

<h2>Installation Steps</h2>



<p>


![Installing osTicket](https://github.com/user-attachments/assets/09cdffbf-b945-4127-9a84-3ec8871b6138)

</p>
<p>
For this ticket project we are using the "osTicket" system, it is an open source file system. We created a virtual machine that we remotely connected to. Inside there we download the osTicket files and we begin extracting them as well.
</p>
<br />

<p>
  
  ![IIS   CGI](https://github.com/user-attachments/assets/21ef0e3a-1666-48dd-9361-4333c89fa821)

</p>
<p>
Next we need to install IIS in Windows with CGI. We do this through control panel > Programs > "Turn Windows Features on or off" then click "ok"
</p>
<br />


<p>
  
![Install PHP and rewrite](https://github.com/user-attachments/assets/c8937ec4-a6af-4b30-9c37-dc46b883ae51)

</p>
<p>
Now, we install PHP Manager for IIS, install Rewrite Module. We also unzip PHP 7.3.8 into windows C-drive in a separate folder. Lastly install VC_redist and MySQL which will store all data on the backend such as users and tickets.
</p>
<br />



<p>
  
![Rename upload to osTicket](https://github.com/user-attachments/assets/1b582ad5-2c07-42d6-a748-6daa4e36a60d)

</p>
<p>
The "Upload" folder is renamed to "osTicket". Must ensure it is spelled and capitalized as is. Then move it over to the wwwroot folder inside of Windows (C:) > inetpub > wwwroot. This will enable a successful installation of osTicket. You may enable/disable features within IIS > Sites > Default Web Site > osTicket > "PHP Manager" > "Enable or disable an extension."
</p>
<br />

<p>
  
![osTicket installer success](https://github.com/user-attachments/assets/aefb13fe-675b-4c41-9e81-6f32d646989c)

</p>

<p>
Now you're able to use the ticketing software within your virtual machine. 
</p>
