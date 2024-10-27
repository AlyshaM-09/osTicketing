# osTicket
  <p align="center">
    <img src="https://i.imgur.com/Clzj7Xs.png" alt=osTicket logo"/>
    <h2> Creating Virtual Machine in Azure </h2>
    
  ### [YouTube: How to create Resource Group and Virtual Machine](https://www.youtube.com/watch?v=9o-BJx0hMEY&t=3s)
    
<h2>Installion of Files </h2>
 
  ### [YouTube: Setting up osTicket part one](https://www.youtube.com/watch?v=tuD_EZjzmFQ)<br>
  
  ### [YouTube: Setting up osTicket part two](https://www.youtube.com/watch?v=WB611i7A0YE)<br>

  <!---I apologies for my lisp and having to slpit the video tutorial in half--->
  
  <h2>Technologies Used</h2> 
  - Microsoft Azure <br>
  - Remote Desktop <br>
  - Internet Information Service

  <h2>Operating Sytems Used</h2>
  - Windows 10 <br>
 - Windows Server 2022

<h2>Step by Step</h2>
<p>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/953a2910-1f09-4c2a-ba6a-eca69ac17156"height="70%" width="70%" alt=step one"/>
  </p>
<p>
<b>
  Step 1:</b> Within Control Panel, click World Wide Services, application, and finally development feature. Here enable, CGI and common HTTP features. If done correctly IIS should be working. To know this is put in local host (127.0.0.1) into the search bar. It should show a blue screen instead of an error. 
</p>
<p>
<p align="center">
 <img src="https://github.com/user-attachments/assets/199defe7-2907-438a-a363-f6961214832e" height="70%" width="70%" alt="step two"/>
</p>
<p>
  <b>
Step 2:</b> Intall: PhP Manager, Rewrite Module, PHP 7.3.8 and unzip the contents into C:/PHP folder, VC redist, MySQL 5.5.62<br>
  <b>
Under MySQl:</b> Typical setup -> launch config wizard -> standard config -> create password
</p>
<p>
<p align="center">
<img src="https://github.com/user-attachments/assets/b8f0c893-433c-4ba4-b907-9b957c2cdf58" height="70%" width="70%" alt="step three"/>
</p>
<p>
<b>
Step 3:</b>  open IIS as Admin, register PHP, reload IIS install osTicket 1.15.8 <br>
After installing osTicket 1.15.8: copy folder to c:\inetpub\wwwroot and rename upload to osTicket 
</p>
<p>
<b>
<p align="center">
    <img src="https://github.com/user-attachments/assets/e1a9d0e0-ca64-4d95-be02-d364e94d5e45" height="70%" width="70%" alt=step four"/>
</p>
  <p>
  Step 4:</b>  Reload IIS, go to sites, defualt, osTicket, browse 80, double click PHP manager, enable: php imap, php intl, php opcache, refresh osTicket in browser 
</p>
<b>
<p>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/12dbf292-2d47-4718-8dae-d8fb9b4771c7" height="70%" width="70%" alt=step five"/>
    </p>
  <p>
  Step 5:</b>  rename ost-sampleconfig.php to ost-conf.php, assign permission by disable inheritance remove all to new permissions everyone all 
  </p>
<b>
  <p>
   <p align="center">
    <img src="https://github.com/user-attachments/assets/5cbcca38-4b3a-4a94-96c0-1213f82b625c" height="70%" width="70%" alt=step five"/>
    </p>
  <p>
  Step 6:</b> install heidisql, root, password, connect session, create database osTicket, finish setting up in browser 
</p>
