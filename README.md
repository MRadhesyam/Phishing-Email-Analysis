##  Task Overview
This task involves analyzing a phishing email to identify common phishing indicators such as suspicious sender addresses, spoofed domains, urgent language, and misleading links. The goal is to understand how phishing attacks work and how to detect them.

##  Steps Followed

1. **Obtained a Sample Phishing Email**  
   - Used a fake PayPal email as an example.

2. **Checked Sender Email**  
   - Found spoofed domain: `paypa1.com` instead of `paypal.com`.

3. **Analyzed Email Headers**  
   - SPF and DKIM likely fail (based on spoofed domain).

4. **Inspected Links**  
   - Hovered over the link and found:  
     `https://www.paypal.com-security-login.com/verify` (fake domain).

5. **Reviewed Email Content**  
   - Urgent language: "Your account will be suspended in 24 hours."
   - Generic greeting: "Dear Customer."
   - Threatening tone to create fear.

6. **Social Engineering Techniques**  
   - Fear + Urgency + Authority.


## 🔍 Tools Used
- Header analysis (manual assumptions, could use MxToolbox).
- Manual inspection for phishing indicators.


##  Outcome
- Learned how to identify phishing emails.
- Understood common tactics used by attackers.
- Documented findings in a structured report.


## 🛡 Recommendations
- Do NOT click on links in suspicious emails.
- Verify sender domains carefully.
- Use multi-factor authentication (MFA).
- Report phishing attempts to IT/security team.
