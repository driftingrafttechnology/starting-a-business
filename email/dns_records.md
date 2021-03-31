# Setting up DNS records for DKIM and SPF
- SPF is a record that says which IP addresses are allowed to send mail for that particular domain.
	- This will be your email hosting providers mail server addresses.
	- This prevents people from sending emails from other servers pretending to be you.
- DKIM is a digital encryption key and signature that verifies that an email message was not forged or changed.
	- This protects from someone sending spam, phishing emails, or other emails from your domain pretending to be you.	
