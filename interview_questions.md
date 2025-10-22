# Interview Questions - Task 2

### 1. What is phishing?
Phishing is a form of cyberattack where attackers impersonate trusted entities (via email, messages, or websites) to trick people into revealing sensitive information or performing actions that compromise security.

### 2. How to identify a phishing email?
Look for signs such as suspicious sender addresses, mismatched or odd-looking URLs, urgent or threatening language, generic greetings, unexpected attachments, and poor spelling/grammar. Check email headers and domain authentication (SPF/DKIM/DMARC) if possible.

### 3. What is email spoofing?
Email spoofing is forging the sender’s address and header information so a message appears to come from a legitimate source. Attackers use spoofing to increase the likelihood that the target will trust the message.

### 4. Why are phishing emails dangerous?
They can steal login credentials, financial data, or install malware/ransomware on the victim’s device. Successful phishing can lead to identity theft, financial loss, and broader network compromise.

### 5. How can you verify the sender’s authenticity?
Check the full email headers for the message path and SPF/DKIM/DMARC results, compare the sender domain with the organization’s official domain, and verify through an independent channel (e.g., official website or customer support).

### 6. What tools can analyze email headers?
MXToolbox Header Analyzer, Google Admin Toolbox (Messageheader), and mail client header viewers or security gateways can parse headers and show SPF/DKIM/DMARC outcomes.

### 7. What actions should be taken on suspected phishing emails?
Do not click links or attachments, report the email to your email provider or the impersonated organization, block the sender, and delete the email. If credentials or sensitive info were disclosed, take immediate remediation (change passwords, enable 2FA).

### 8. How do attackers use social engineering in phishing?
Attackers exploit human emotions such as fear, urgency, curiosity, or authority to manipulate victims into acting quickly without verifying the message’s legitimacy.
