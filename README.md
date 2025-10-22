# Task 2 - Phishing Email Analysis

## Objective
Analyze a suspicious email sample and identify phishing indicators such as spoofed sender, mismatched URLs, urgent language, and social engineering tactics.

## Sample Source
Public phishing example used for training and analysis (text adapted for safety).

## Tools Used
- WHOIS (command-line lookup)
- Online Email Header Analyzer: MXToolbox (https://mxtoolbox.com)
- Text editor (to save and inspect the sample)
- Browser (to check domains without visiting malicious links)

## Steps Performed
1. Collected a publicly-available phishing sample (text-only, adapted for safety).  
2. Inspected the sender address for spoofing and domain mismatch.  
3. Verified the suspicious domain via WHOIS lookup and DNS checks (did not visit any links).  
4. Examined email characteristics (tone, grammar, personalization).  
5. Optionally checked headers using MXToolbox header analyzer.

## Key Findings (summary)
- Spoofed sender: 'security@paypal-support.com' (domain not official).  
- Suspicious URL text: 'paypal-verification-center-secure-login.com' (domain mismatch).  
- WHOIS lookup result: **No match for domain** — domain does not exist / not registered.  
- Urgent / threatening language encouraging immediate action.  
- Generic greeting ("Dear Customer") and slight grammar issues.  
- Conclusion: Email is a phishing attempt.

## Files Included
- phishing_analysis_report.md — full analysis and indicators found.  
- interview_questions.md — answers to the Task 2 interview questions.  
- whois_report.txt — WHOIS output for the suspicious domain (evidence).  
- README.md — this file.

---

Analyst: Yug Saxena  
Date: October 22, 2025
