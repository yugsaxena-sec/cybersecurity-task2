# Phishing Analysis Report

## Email Sample
From: security@paypal-support.com  
Subject: Urgent: Verify Your Account Immediately

Body:
Dear Customer,

Your PayPal account has been temporarily suspended due to suspicious activity.  
Please verify your information immediately to avoid permanent account closure.  

Click the link below to restore your account:  
https://paypal-verification-center-secure-login.com

Thank you,  
PayPal Security Team

*(Note: link is shown as text only and has been adapted for safety. Do not visit unknown domains.)*

---

## Detailed Findings

1. **Sender address / domain mismatch**  
   - Sender appears as `security@paypal-support.com`. Official PayPal emails use `@paypal.com`. The extra `-support` suggests a forged or fraudulent domain.

2. **Suspicious URL / domain**  
   - The visible URL `paypal-verification-center-secure-login.com` is not an official PayPal domain. It uses additional words to appear legitimate — a common phishing trick. I did **not** click or visit the link.

3. **WHOIS Lookup Result**
   - WHOIS lookup for `paypal-verification-center-secure-login.com` returned **no registration match**, indicating the domain does not exist or was not registered. This strongly supports that the email is fraudulent. See attached `whois_report.txt` for the full output.

4. **Urgent language and pressure**  
   - Phrases like “temporarily suspended,” “verify immediately,” and “avoid permanent account closure” are typical social-engineering tactics intended to rush recipients into action.

5. **Generic greeting and lack of personalization**  
   - The message uses “Dear Customer” rather than the recipient’s name; legitimate services typically include personalization in account-related emails.

6. **Grammar / tone**  
   - Slightly awkward phrasing and punctuation, another red flag commonly seen in phishing emails.

7. **Header analysis (if available)**  
   - If full header data is available, it should be pasted into MXToolbox Header Analyzer. Look for mismatched `Return-Path`, suspicious `Received` hops, or SPF/DKIM/DMARC failures to confirm spoofing. (Since this phishing sample was taken from an online source and not received in an actual mailbox, the original email header data is not available for analysis.
Normally, I would use MXToolbox to check the header for mismatched return-paths, suspicious routing, and SPF/DKIM/DMARC failures, which can provide strong technical proof of spoofing.)

---

## Recommended Actions
- **Do not click** any links or open attachments from this email.  
- **Report** the message to the real organization (e.g., PayPal’s official phishing reporting channel) and mark as phishing in your mail client.  
- **Delete** the email after reporting.  
- If credentials were entered anywhere: **change passwords** immediately and enable 2FA on the account.

---

## Conclusion
This sample contains multiple classic phishing indicators (spoofed sender, fake URL, urgency, generic greeting). It is a phishing attempt designed to harvest login details or other sensitive information. The WHOIS result (no match) is strong evidence the domain is not legitimate.

**Analyst:** Yug Saxena  
**Date:** October 22, 2025


