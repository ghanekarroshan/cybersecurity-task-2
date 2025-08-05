**Phishing Email Analysis Report**

Recipient
Name: Roshan Ghanekar  
Email: ghanekar092@gmail.com  
Date: August 3, 2025, 5:44 PM

---

Step-by-Step Email Analysis

Step 1: Identify the Email
- Subject:  Here's Your Login Link, Roshan Ghanekar?
- Sender Email: feedback@hackingflix.com
- Display Name: Gautam Kumawat
- Message Location: Automatically marked as "Spam" by Gmail

---

Step 2: Red Flags Observed in the Email Body

| Indicator         | Description |
|----------         |-------------|
| Spam Folder       | Gmail flagged this due to prior reports from `hackingflix.com` |
| Urgent Subject    | Uses urgency & curiosity by including "Login Link" and your name |
| Suspicious Domain | Domain `hackingflix.com` is unknown and potentially malicious |
| Generic Message   | No login method or personal details, only vague praise and emotional text |
| Social Engineering| Attempts to build trust using emotional manipulation and flattery |
| No Login Method   | Despite subject saying "Login Link", there is no actual secure link present |

---

Step 3: Header Analysis (Using MXToolbox)

Tool Used: [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
| Parameter    | Status                                                                        |
-----------------------------------------------------------------------------------------------|
| SPF          | ✅ PASS (IP 149.72.58.57 is authorized to send on behalf of domain)           |
| DKIM         |✅ PASS with domain `hackingflix.com`                                          |
| DMARC        |✅ PASS                                                                         |
| Relay Info   |IP traced to `SendGrid` service                                                |
| Blacklist    |⚠️ IP found on blacklist (`149.72.58.57`)     
---

Step 4: Analysis Summary

Despite SPF, DKIM, and DMARC passing, this email is suspicious due to:
- Spam folder classification
- The sender domain is unfamiliar
- Subject line contains urgent CTA
- Message body has no links or secure authentication
- Use of social engineering language
- Blacklist hit on IP used by sender

---

Final Verdict
The email from `feedback@hackingflix.com` is likely a phishing attempt or at minimum a low-trust promotional/spam email designed to mislead or emotionally manipulate users.

---

Step 5: Supporting Screenshots

1. Screenshot 1: Email in spam folder  
2. Screenshot 2: Original message header from Gmail  
3. Screenshot 3: Header analyzed via MXToolbox  
4. Screenshot 4: SPF, DKIM, and DMARC data  
5. Screenshot 5: IP relay and full header breakdown

---

Tools Used
- Gmail (to view the message and header)
- MXToolbox Email Header Analyzer
- Screenshot tool (Snipping Tool)

---

Author
Roshan Ghanekar
05-08-2025


