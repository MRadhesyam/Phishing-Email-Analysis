# Phishing Email Analysis Report

## 1. Sender Analysis
- **Display Name**: PayPal Support
- **Email Address**: support@paypa1.com
- **Issue**: Domain is spoofed. "paypa1.com" uses the number "1" instead of letter "l".

## 2. Header Analysis (Assumed)
- SPF: Likely FAIL (Domain doesn't match legitimate PayPal servers)
- DKIM: Missing or invalid
- Received From: Suspicious IP address (not PayPal)

## 3. Links
- **Visible Text**: https://www.paypal.com-security-login.com/verify
- **Actual URL**: Suspicious because:
  - Contains "paypal" but not the official domain
  - Hyphenated domain tricks users

## 4. Email Content
- **Urgency**: “Verify your information within 24 hours”
- **Threats**: “Account will be suspended”, “Permanent closure”
- **Generic Greeting**: “Dear Customer” (legitimate services usually use your name)
- **Spelling/Grammar**: Looks professional but uses scare tactics

## 5. Attachments
- No attachments present in this sample

## 6. Social Engineering Techniques Used
- **Fear**: Account suspension
- **Urgency**: 24-hour deadline
- **Authority**: Posing as PayPal

## 7. Conclusion
This is a classic phishing email because:
- Spoofed email domain
- Suspicious link redirecting to a fake site
- Urgent language and threats
- Generic greeting
- No personalization
