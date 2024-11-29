<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Creating users with Powershell</h1>
In this tutorial, we will be creating user accounts with PowerShell, demonstrating how to automate the process efficiently using scripts <br />

<h></h>

Log into Client-1 as mydomain.com\jane_admin.
Once logged in, right-click on This PC and select Properties to open System Properties.
In the left-hand menu, click on Remote Settings. Under the Remote Desktop section, select Allow remote connections to this computer to enable Remote Desktop access

<p>
<img src="https://i.imgur.com/9miotKC.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

Allow domain users access to Remote Desktop.
You can now log into Client-1 as a regular, non-administrative user from the domain.

<p>
<img src="https://i.imgur.com/aZH4CzL.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

Login to DC-1 as jane_admin, open PowerShell_ise as an administrator, create a bunch of additional users, and attempt to log into Client-1 with one of the newly created users.



Create a new file, paste the contents of the script into it, run the script, and observe the accounts being created.

<p>
<img src="https://i.imgur.com/Es0vQuW.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/QjF3jeJ.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/ucTdEFL.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

When finished, open ADUC and observe the accounts in the appropriate _EMPLOYEES organizational unit (OU).


<p>
<img src="https://i.imgur.com/ucTdEFL.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

Attempt to log into Client-1 with one of the accounts, taking note of the password specified in the script.

<p>
<img src="https://i.imgur.com/C9b8fWF.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
