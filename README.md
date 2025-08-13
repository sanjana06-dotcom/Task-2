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
