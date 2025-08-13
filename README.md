# Cybersecurity Task 2 – Phishing Email Analysis

## 🎯 Objective
Analyze a suspicious email sample to identify phishing characteristics.

## 🧰 Tools Used
- Public phishing email sample (PayPal example)
- Manual inspection of email content
- Email header review (simulated, since only sample text available)

## 📄 Email Sample Summary
- **Sender Display Name:** service@intl.paypal.com  
- **Actual Sending Address:** service.epaypal@outlook.com  
- **Subject:** Response required  
- **Body Summary:** Claims unusual account activity, requests immediate login to resolve.

## 🔍 Phishing Indicators Found
1. **Sender Address Spoofing** – The display name uses a PayPal-like address, but actual domain is Outlook.com.  
2. **Urgent Language** – “Response required” and warnings about account limits create panic.  
3. **Unusual Activity Claim** – Fake security alert to get the user to act quickly.  
4. **Suspicious Links** – “log in” and “Resolution Center” likely point to a fake website.  
5. **Generic Greeting** – Does not address the user by full name.  
6. **Domain Mismatch** – Official PayPal emails come from `@paypal.com`, not `@outlook.com`.  
7. **Minor Grammar Issues** – Slightly awkward sentence structure.

## ⚠ Risks
- **Credential Theft** – If the user logs in via the phishing site, attackers can steal credentials.  
- **Malware Infection** – Links could lead to malicious downloads.

## 🛡 Recommendations
- Never click on links from unsolicited emails.  
- Verify sender addresses carefully.  
- Report PayPal phishing attempts to `phishing@paypal.com`.  
- Delete the suspicious email after reporting.

## 📁 Files Included
- `phishing_email.txt` – Raw phishing email text  
- `phishing_analysis.txt` – Detailed phishing indicators  
- `README.md` – Task documentation

## ✅ Outcome
Learned to identify phishing characteristics, spot spoofed email addresses, and evaluate risks of suspicious emails.


##  Interview Question Answers

1. **What is phishing?**  
   Phishing is a cyber-attack where attackers send deceptive emails or messages to trick users into revealing login credentials or downloading malware.

2. **How to identify a phishing email?**  
   Look for sender domain mismatches, urgent language, suspicious links, unexpected attachments, and poor grammar.

3. **What is email spoofing?**  
   Spoofing is when the attacker falsifies the sender address to appear as a trusted source.

4. **Why are phishing emails dangerous?**  
   They can steal login credentials, deploy malware, steal sensitive data, or compromise systems.

5. **How can you verify the sender’s authenticity?**  
   Check the sender’s domain, inspect email headers (like SPF, DKIM, DMARC), and compare with official sources.

6. **What tools can analyze email headers?**  
   Tools like MXToolbox Email Header Analyzer and Google Admin Toolbox Messageheader.

7. **What actions should be taken on suspected phishing emails?**  
   Do not click links or attachments, verify sender, report to the organization, and delete the email.

8. **How do attackers use social engineering in phishing?**  
   By exploiting emotions like fear or urgency and using trust cues like familiar branding or spoofed domains.
