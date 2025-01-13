<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>



- Install https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD and unzip file into desktop.
- Install / Enable IIS in Windows WITH CGI
World Wide Web Services -> Application Development Features -> [X] CGI

- Install PHP Manager, Rewrite Module, unzip PHP into directory, install VC_redist, and MySQL
- Item 4
- Item 5

<h2>Installation Steps</h2>



<p>


![Installing osTicket](https://github.com/user-attachments/assets/09cdffbf-b945-4127-9a84-3ec8871b6138)

</p>
<p>
For this ticket project we are using a osticket system. First we must download the zip file and then extract it.
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
  
![Install PHP and rewrite](https://github.com/user-attachments/assets/c8937ec4-a6af-4b30-9c37-dc46b883ae51)

</p>
<p>
Now, we install PHP Manager for IIS, install Rewrite Module. We also unzip PHP 7.3.8 into windows C-drive in a separate folder. Lastly install VC_redist and MySQL which will store all data on the backend such as users and tickets.
</p>
<br />
