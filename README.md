# osticket-prereqs<p align="center">
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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>![Step 1](https://user-images.githubusercontent.com/116759326/198845151-c5358899-b082-49f8-aa9e-edc92a77d359.jpg)

<p>
>
<p>
The first step to Os Ticket system will be to ensure you download all required prerequisite. You will need Web Server: IIS, PHP Manager Version 7, and MySQL database: 5.0 or above. Next go to the start menu at the bottom left of your computer/ desktop and type windows features , then select windows internet information services and select ok. Next you can select administrative tools. Next step will be to work on downloading all the prerequisite by going to Web platform installer 
  , download to your comuputer, once finish downloading to compuetr open the web platform installer. Search for mysql, select for install. Then scroll down to PHP and add each version leading up to 7.3, then click install. At this point you will be required to enter a password makesure you remember your password, then you can select continue. Select accept and wait for download process to start . You may also need to download PHP manually due to error on web platform installer. links provided below. 
  https://windows.php.net/download
 
  https://www.iis.net/downloads/community
</p>
<br />

<p>
<<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>![Step 2](https://user-images.githubusercontent.com/116759326/198847682-469ec878-2663-40f7-b52c-dc479ae343ae.jpg)

</p>
<p>
The next step would be to choose  the correct prerequisite down the zip file for PHP. Then you will extract the file, after its been extracted, you would then copy the file. Go to the local c drive, then search your PHP folder to ensure all files have been downloaded. The extracted file will then be pasted into the PHP file folder. Next step you will go to the start menu below and search for IIS  Internet Information Services Manager,  select run as administrator. Select PHP Manager,then since PHP was manually installed we will have to register this by finding the file within PHP and click open and now you will be running PHP.Next step will be downloading OS tickets at www.ostickets.com/downloads , select v1.12.2 lastest release. Once your file is downloaded go to file folder to extract file .Then copy your upload folder, and next it will be pasted into your local c drive in the inetpub select wwwroot directory paste the upload folde, from there you will then name the folder os ticket. Now you can go back to IIS and select refresh  Os tick tickets should pop up on your left under Default web site .   
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> Once this step has been completed you can then selct browse 80, which will then open Os ticket.
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
