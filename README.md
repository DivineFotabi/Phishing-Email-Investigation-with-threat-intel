# Phishing-Email-Investigation-with-threat-intel

# Objective
In this project I investigated a phishing email from a client and proved the email was a spoof from the header and fail authentication. I mapped the sending infrastructure and the look-alike domain and cleared a legitimate email as a false positive with evidence, then I used the mail message trace and sign-in logs to scope the campaign, identified who clicked and confirmed two compromised accounts from an anonymus foreign sign-in. Then I wrote the incident report and recommended a detection rule to catch it faster.

# Skills 
- Email header and authentication analysis (SPF/DKIM/DMARC)
- URL and infrastructure analysis
- IOC enrichment (VirusTotal, AbuseIPDB)
- KQL campaign scoping
- phishing triage Aand reporting
- MITRE ATT&CK mapping


# Steps  
The emails represent Payroll update action required messages that looks like it is from Cloudora HR and links to a portal asking them to confirm their payroll
details. One employee also forwarded a marketing newsletter in the same batch, unsure whether it is part of the attack.
Mail 1
<img src="https://github.com/DivineFotabi/Phishing-Email-Investigation-with-threat-intel/blob/8eccf7b887339a2e15a0b58148e091777dfeae8c/Variant%20A.png" /> 

Mail 2
<img src="https://github.com/DivineFotabi/Phishing-Email-Investigation-with-threat-intel/blob/903f32f4ea24e73eb5b566311bc8a4084957269b/Variant%20B.png" /> 

Mail 3
<img src="https://github.com/DivineFotabi/Phishing-Email-Investigation-with-threat-intel/blob/c0525d404f34580f4b7306df21166abf2ad55850/Variant%2003b.png" /> 

Mail 4
<img src="https://github.com/DivineFotabi/Phishing-Email-Investigation-with-threat-intel/blob/ad02c83202cf8e2c08af9f61d63e3077e5efdcc4/Variant%2004.png" /> 

Mail 5
<img src="https://github.com/DivineFotabi/Phishing-Email-Investigation-with-threat-intel/blob/838f39f2c2f1bd94768960cde2f33020e5faf61b/Variant%2005.png" /> 

Mail 6
<img src="https://github.com/DivineFotabi/Phishing-Email-Investigation-with-threat-intel/blob/ca36582b4fc312705fbf1ddbc54b225dd6365198/Variant%2006.png" /> 
