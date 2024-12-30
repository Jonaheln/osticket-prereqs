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

- Item 1 download the osTicket-Installation-Files.zip
- Item 2 install VC_redist.x86.exe.
- Item 3 install MySQL 5.5.62
- Item 4 Install / Enable IIS in Windows WITH CGI
- Item 5 unzip PHP 7.3.8

<h2>Installation Steps</h2>


![image](https://github.com/user-attachments/assets/50cac397-2d88-4fab-953f-37d8e223174f)

- I downloaded the osTicket-Installation-Files.zip and unziped it onto the desktop.



![image](https://github.com/user-attachments/assets/99b2d578-1a93-4a25-9e11-43e09c9cf402)


- I Installed / Enabled IIS in Windows WITH CGI
World Wide Web Services -> Application Development Features -> [X] CGI



![image](https://github.com/user-attachments/assets/2ff70296-5802-4b08-8611-d8e9267c1a77)


- Inside of osTicket-Installation-Files folder, I unziped PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into the “C:\PHP” folder
- Inside of osTicket-Installation-Files folder, I installed VC_redist.x86.exe.
- Inside of osTicket-Installation-Files folder, I installed MySQL 5.5.62 (mysql-5.5.62-win32.msi)




![image](https://github.com/user-attachments/assets/ea02467d-ff79-4ccc-8dd1-d2c1f3a179d1)

![image](https://github.com/user-attachments/assets/b82a1a0a-eda8-4b9c-8da3-b2ed3c571688)




- I Open IIS as an Admin -> Default -> osTicket
Double-click PHP Manager
Click “Enable or disable an extension”
Enable: php_imap.dll
Enable: php_intl.dll
Enable: php_opcache.dll



