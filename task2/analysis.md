🔍 Phishing Email Analysis Report


Email Subject: "Important Notice: Your Account Will Be Suspended"

Sender Address: support@amaz0n-secure.com
Actual Company Spoofed: Amazon


🧩 **Phishing Indicators Identified**
1. Sender Email Address Spoofing
Suspicious Address: support@amaz0n-secure.com

Analysis: The domain uses a zero (0) instead of the letter “o” in "amazon", a common spoofing tactic.

Legit Domain: @amazon.com

2. Header Analysis
Tool Used: MxToolbox Email Header Analyzer

Discrepancy: Sender IP does not match known Amazon IP ranges.

SPF/DKIM/DMARC Failures: None of the email authentication protocols passed. Indicates spoofed sender.

3. Suspicious Links
Displayed Link: https://amazon.com/security-update

Actual URL (on hover): http://amaz0n-secure-login.ru/verify

Tactic Used: Mismatched URLs – looks legitimate but redirects to a malicious Russian domain.

4. Urgent/Threatening Language
Example from Email:
"Failure to update your information within 24 hours will result in account suspension."

Purpose: Creates panic to encourage hasty clicking.

5. Attachments
File: SecurityUpdate.zip

Concern: Unexpected attachment, possibly malware-laced.

6. Spelling and Grammar Errors
Examples:

"Your acount has beeen flagged for verification."

"Click here immediatelly to resolve."

Observation: Unprofessional tone, multiple typos, and grammar issues.
