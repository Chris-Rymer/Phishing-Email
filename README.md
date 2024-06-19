<h1>Detecting Phishing Emails</h1>

<h2>Description</h2>
Open a copy of a suspected phishing email ELM File, inspect header for discrepancies, search VirusTotal with URL included in email, and report findings. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Mozilla Thunderbird</b> 
- <b>VirusTotal</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<br />

<h2>Analysis:</h2>

<p align="center">
Open suspected phishing email in Mozilla Thunderbird: <br/>
<img src="https://i.imgur.com/7Q2on3g.png" height="80%" width="80%" alt="Phishing Investigation "/>
<br />

The email raises suspicion, particularly due to anomalies in the sender's email address and name. The email address lacks any indication of association with PayPal, and the sender's name (☆P.A.Y.P.A.L☆) deviates from the typical representation used by PayPal. These inconsistencies suggest a potential phishing attempt.
<br />

<p align="center">
View source of EML file with Mozilla Thunderbird: <br/>
<img src="https://i.imgur.com/Vx2RJaW.png" height="80%" width="80%" alt="Phishing Investigation "/>
<br />

When viewing the email source, it becomes evident that the return path differs from the address used to send the email. This inconsistency is a common tactic in phishing emails and further heightens suspicion.
<br />

<p align="center">
Next copy the link address in email for further investigation:  <br/>
<img src="https://i.imgur.com/qw23jhY.png" height="80%" width="80%" alt="Phishing Investigation "/>
<br />
<br />
Perform search on VirusTotal for email link URL, find multiple security vendors flagged URL as malicious and specifically as a phishing attempt.: <br/>
<img src="https://i.imgur.com/tkNCM85.png" height="80%" width="80%" alt="Phishing Investigation "/>
<br />
Find Body SHA-256 Under Details: <br/>
<img src="https://i.imgur.com/toV80aq.png" height="80%" width="80%" alt="Phishing Investigation "/>
<br />

The Body SHA-256 serves multiple crucial purposes in phishing investigations. Firstly, it enables comparison of URLs against known malicious entries in databases or blacklists, aiding in the detection and prevention of future phishing attempts through automated systems. Additionally, it facilitates the sharing of phishing attempts among security professionals without compromising sensitive information contained within the phishing email.
<br />

<h2>Final Report</h2>
After thorough investigation, it is evident that this email constitutes a phishing attempt. There is no indication that it was sent by PayPal, and the included links have been identified as known phishing attempts. Therefore, I recommend deleting this email immediately and performing remediation if any client has visited the URL link.
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
