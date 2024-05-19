# osTicketing-Prerequisites
<h2> Creating Virtual Machine in Azure </h2>
  Under Virtual Machine in Azure click Create and choose first option <br>
  Create a Resource Group or choose an existing Resource Group  <br>
  Choose Windows 10 or Ubuntu Server  <br>
  Create an username and password then create  <br>
After creation take the public IP adress and place in Remote Desktop. This will give access to the VM.
<h3>Installion of Files </h3>
<b>Step 1:</b> go to RUN -> Control Panel -> click world wide web service -> application development feature -> enable CGI and common HTTP features <br>
<b>Step 2:</b> intall: PhP Manager, Rewrite Module, PHP 7.3.8 and unzip the contents, VC exe, MySQL 5.5.62
Under MySQl: typical setup -> launch config wizard -> standard config -> create password <br>
<b>Step 3:</b>  open IIS as Admin, register PHP, reload IIS install osTicket 1.15.8 <br>
After installing osTicket 1.15.8: copy folder to c:\inetpub\wwwroot and rename upload to osTicket <br>
<b>Step 4:</b>  Reload IIS, go to sites, defualt, osTicket, browse 80, double click PHP manager, enable: php imap, php intl, php opcache, refresh osTicket in browser <br>
<b>Step 5:</b>  rename ost-sampleconfig.php to ost-conf.php, assign permission by disable inheritance remove all to new permissions everyone all <br>
<b>Step 6:</b> install heidisql, root, password, connect sessiom, create database osTicket, finish setting up in browser
