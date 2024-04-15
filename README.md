<h1>Phishing Email Investigation</h1>

<h2>Description</h2>
Open a Copy of a Suspected Phishing Email ELM File, Inspect Header for Discrepancies, Search VirusTotal for URL of Email Link, and Report Findings. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Mozilla Thunderbird</b> 
- <b>VirusTotal</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Scenario</h2>
Your email address has been leaked and you receive an email from Paypal in German. Try to analyze the suspicious email.
<br />

<h2>Analysis:</h2>

<p align="center">
Open Suspected Phishing Email in Mozilla Thunderbird: <br/>
<img src="https://i.imgur.com/7Q2on3g.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Install Windows Server 2019:  <br/>
<img src="https://i.imgur.com/s6NwCpQ.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Identify and Rename Internal Network Adapter by Finding Adapter with an APIPA: <br/>
<img src="https://i.imgur.com/yTRE0d4.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Rename Server PC:  <br/>
<img src="https://i.imgur.com/rEetYO6.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Assign Server IPv4 Address and Set DNS to Loopback Address:  <br/>
<img src="https://i.imgur.com/b1Emikx.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Install Active Directory:  <br/>
<img src="https://i.imgur.com/lfaetmf.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Promote Server to a Domain Controller:  <br/>
<img src="https://i.imgur.com/mfQqQWt.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Create Organizational Unit for Admin Users:  <br/>
<img src="https://i.imgur.com/DrewKHC.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Create New Admin User:  <br/>
<img src="https://i.imgur.com/OBby43P.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Make User Member Of Domain Admin Group:  <br/>
<img src="https://i.imgur.com/3oloAVc.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Sign Out of Main Admin Account and Sign In with Newly Created Admin User:  <br/>
<img src="https://i.imgur.com/6eBOaTC.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Install Remote Access for NAT and RAS:  <br/>
<img src="https://i.imgur.com/gLNkrYJ.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Set NAT Internet Connection to Internet Adapter:  <br/>
<img src="https://i.imgur.com/pGkypis.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Install DHCP Role:  <br/>
<img src="https://i.imgur.com/gyKhEMH.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Set Scope for IPv4 Range:  <br/>
<img src="https://i.imgur.com/dXxoNeE.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Set Default Gateway to Server IP Address:  <br/>
<img src="https://i.imgur.com/tKWi1C7.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Set DNS to Server IP Address:  <br/>
<img src="https://i.imgur.com/ej8Yu0c.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Create Users with PowerShell Script:  <br/>
<img src="https://i.imgur.com/mTDxMTO.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Create New Windows 10 Virtual Machine for a Client and Set Network Adapter to Internal:  <br/>
<img src="https://i.imgur.com/AO3Tt4F.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Rename Client PC and Join the Server Domain:  <br/>
<img src="https://i.imgur.com/VfQKOEo.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Sign In to Domain from Client:  <br/>
<img src="https://i.imgur.com/ThF84jN.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
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
