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
<img src="https://i.imgur.com/7Q2on3g.png" height="80%" width="80%" alt="Phishing Investigation "/>
<br />

The email raises suspicion, particularly due to anomalies in the sender's email address and name. The email address lacks any indication of association with PayPal, and the sender's name (☆P.A.Y.P.A.L☆) deviates from the typical representation used by PayPal. These inconsistencies suggest a potential phishing attempt.
<br />

<p align="center">
View Source of EML File with Mozilla Thunderbird: <br/>
<img src="https://i.imgur.com/Vx2RJaW.png" height="80%" width="80%" alt="Phishing Investigation "/>
<br />

When viewing the email source, it becomes evident that the return path differs from the address used to send the email. This inconsistency is a common tactic in phishing emails and further heightens suspicion.
<br />

<p align="center">
Next Copy the Link Address in Email for Further Investigation:  <br/>
<img src="https://i.imgur.com/qw23jhY.png" height="80%" width="80%" alt="Phishing Investigation "/>
<br />
<br />
Perform Search on VirusTotal for Email Link URL, Find Multiple Security Vendors Flagged URL as Malicious and Specifically as a Phishing Attempt.: <br/>
<img src="https://i.imgur.com/tkNCM85.png" height="80%" width="80%" alt="Phishing Investigation "/>
<br />
Find Body SHA-256 Under Details: <br/>
<img src="https://i.imgur.com/toV80aq.png" height="80%" width="80%" alt="Phishing Investigation "/>
<br />

The Body SHA-256 serves multiple crucial purposes in phishing investigations. Firstly, it enables comparison of URLs against known malicious entries in databases or blacklists, aiding in the detection and prevention of future phishing attempts through automated systems. Additionally, it facilitates the sharing of phishing attempts among security professionals without compromising sensitive information contained within the phishing email.
<br />

<h2>Final Report</h2>

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
