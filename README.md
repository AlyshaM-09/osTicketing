# osTicketing-Prerequisites
  <p align="center">
    <img src="https://i.imgur.com/Clzj7Xs.png" alt=osTicket logo"/>
    <h2> Creating Virtual Machine in Azure </h2>
    
  ### [YouTube: How to create Resource Group and Virtual Machine](https://www.youtube.com/watch?v=9o-BJx0hMEY&t=3s)
    
<h2>Installion of Files </h2>
 
  ### [YouTube: Setting up osTicket part one](https://www.youtube.com/watch?v=tuD_EZjzmFQ)<br>
  
  ### [YouTube: Setting up osTicket part two]()<br>
    

<b>Step 1:</b> go to RUN -> Control Panel -> click world wide web service -> application development feature -> enable CGI and common HTTP features <br>
<b>Step 2:</b> intall: PhP Manager, Rewrite Module, PHP 7.3.8 and unzip the contents, VC exe, MySQL 5.5.62
Under MySQl: typical setup -> launch config wizard -> standard config -> create password <br>
<b>Step 3:</b>  open IIS as Admin, register PHP, reload IIS install osTicket 1.15.8 <br>
After installing osTicket 1.15.8: copy folder to c:\inetpub\wwwroot and rename upload to osTicket <br>
<b>Step 4:</b>  Reload IIS, go to sites, defualt, osTicket, browse 80, double click PHP manager, enable: php imap, php intl, php opcache, refresh osTicket in browser <br>
<b>Step 5:</b>  rename ost-sampleconfig.php to ost-conf.php, assign permission by disable inheritance remove all to new permissions everyone all <br>
<b>Step 6:</b> install heidisql, root, password, connect sessiom, create database osTicket, finish setting up in browser
