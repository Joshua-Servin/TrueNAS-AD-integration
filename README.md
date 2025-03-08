# TrueNAS-AD-integration



<h2>Description</h2>
This project is a walkthrough on how to create an OU and a User inside the OU.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Oracle VirtualBox</b> 
- <b>Active Directory Domain Controller</b>

<h2>Environments Used </h2>

- <b>Windows Server 2019</b> (22H2)

<h2>Project walk-through:</h2>
<p align="center">
Open "Active Directory Users and Computers" under the "Tools" tab on the top right: <br/>
<img src="https://imgur.com/7GZOlRQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Find your Domain:  <br/>
<img src="https://imgur.com/h8F6PcV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right click, hover over "New" and click on "Organizational Unit": <br/>
<img src="https://imgur.com/zTxT0bw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Name your OU:  <br/>
<img src="https://imgur.com/KD38907.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once the OU is created, Right Click on the OU you created and hover over "NEW" and click on "USER":  <br/>
<img src="https://imgur.com/QB1v67r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Name your User with a first name, last name, and Logon Name. Click next  <br/>
<img src="https://imgur.com/s8yjwnu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter a password for the user to enter when they log in. Check the box for "User must change password at next logon" to ensure they create their own password. Press next  <br/>
<img src="https://imgur.com/deRKWZd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 Check everything is correct and hit Finish <br/>
  <img src="https://imgur.com/Kwsxxo3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Verify the User is in the correct OU you created and you are done!  <br/>
<img src="https://imgur.com/IIRAzhM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
