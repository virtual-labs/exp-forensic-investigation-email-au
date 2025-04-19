### Theory
Forensic investigation on email refers to the process of examining and analyzing email communications to gather evidence for legal or investigative purposes. This type of investigation is commonly conducted in various scenarios, including criminal cases, corporate investigations, intellectual property disputes, and civil litigation. 
1. Header Analysis
Email headers contain metadata that provides crucial information about the origin and path of the email. Investigators analyze headers to:

- Identify the sender's IP address.

- Trace the route the email took through different mail servers.

- Verify if the sender’s domain and email address were spoofed.

- Check authentication results like SPF, DKIM, and DMARC. This helps determine the authenticity of the email and locate the actual source.

2. Link Analysis
Email links are often used in phishing attacks or malware distribution. Link analysis involves:

- Extracting all URLs from the email body.

- Checking the legitimacy of the URLs by examining their domain names.

- Investigating redirection behavior (e.g., shortened links).

- Using threat intelligence databases to check for malicious or blacklisted links. This step helps assess whether the email was designed for phishing or redirecting the recipient to a harmful website.

3. Content analysis
Content analysis involves examining the body and attachments of the email. Focus areas include:

- Suspicious or manipulative language 
- Unusual formatting or spelling/grammar mistakes
- Social engineering tactics used to trick users

Suspicious attachments are a major concern:
- Executable files (.exe, .scr, .bat)
- Scripted Office docs (.docm, .xlsm)
- Compressed files (.zip, .rar)
- Files with double extensions (e.g., "invoice.pdf.exe")