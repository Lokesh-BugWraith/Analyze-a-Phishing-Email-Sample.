# Phishing Email Analysis Report

## Sample Email Details
- **Subject**: Norton Subscription Renewed Successfully
- **Sender**: billing@norton-support.com
- **Date**: October 22, 2025 (assumed for sample analysis)
- **Source**: Sample obtained from online phishing email archives (e.g., UC Berkeley phishing examples or Norton security blog)

## Email Content
*Below is the sample phishing email used for analysis:*

**Subject**: Norton Subscription Renewed Successfully  
**From**: billing@norton-support.com  
**Body**:  
Welcome Subscriber;  
Your Annual membership for NORTON 360 TOTAL PROTECTION has been renewed and updated successfully. The amount charged will be reflected within the next 24 to 48 hrs on your profile of account.  
**Product Information**:  
INVOICE NO. @ GGH1644259106OV  
ITEM NAME @ NORTON 360 TOTAL PROTECTION  
START DATE @ 2022 Feb 07  
END DATE @ 1 year from START DATE  
GRAND TOTAL @ $240.42 USD  
PAYMENT METHOD @ Debit from account  
If you wish to not to continue subscription and claim a REFUND then please feel free to call our Billing Department as soon as possible.  
You can Reach us on : +1 – ( 803 ) – ( 598 ) – 4473  
Regards,  
Billing Department SP  

## Phishing Indicators Found
1. **Spoofed Sender Address**: The sender’s email address, billing@norton-support.com, is not from Norton’s official domain (norton.com). Legitimate Norton emails come from addresses like support@norton.com. This suggests spoofing to impersonate a trusted company.
2. **Email Header Discrepancies**: Headers are unavailable in this text-based sample. In a real scenario, analyzing headers using tools like MX Toolbox (mxtoolbox.com/email-headers) or Google’s Message Header Analyzer would likely reveal inconsistencies, such as mismatched IP origins or failed SPF/DKIM authentication, common in phishing emails.
3. **Suspicious Contact Method**: The email includes a phone number (+1-803-598-4473) instead of directing users to an official website. This is a red flag, as it likely leads to a scam call center that may request sensitive information or payment details.
4. **Urgent or Threatening Language**: The phrase “as soon as possible” in the refund instruction creates a sense of urgency, pressuring recipients to act quickly without verifying the email’s legitimacy. This is a common tactic to bypass critical thinking.
5. **Mismatched URLs**: This sample contains no hyperlinks. In similar phishing emails, hovering over links (e.g., a “Refund” button) often reveals redirects to malicious domains (e.g., norton-renewal.com instead of norton.com). Users should always verify URLs before clicking.
6. **Spelling and Grammar Errors**: The email has multiple errors:
   - Generic greeting: “Welcome Subscriber;” lacks personalization (e.g., no recipient name).
   - Awkward phrasing: “hrs on your profile of account” and “wish to not to continue” (double negative).
   - Inconsistent capitalization: “Reach us on :” and random uppercase in “Billing Department SP”.
7. **Additional Phishing Traits**:
   - **Fake Invoice Details**: The invoice references outdated dates (e.g., “2022 Feb 07”), which is inconsistent with the current date (2025).
   - **Lack of Personalization**: No recipient-specific details, unlike legitimate company emails.
   - **Lure of Refund**: The promise of a refund entices users to engage with the scammer, a tactic to steal personal or financial information.

## Summary
This email exhibits multiple phishing characteristics, including a spoofed sender address, urgent language, grammatical errors, and a suspicious phone number as the primary contact method. These traits aim to deceive users into believing their Norton subscription was charged, prompting them to call a scam number. In a real scenario, users should verify claims through official channels (e.g., norton.com) and avoid interacting with unsolicited email prompts. Always use header analysis tools to confirm email authenticity and hover over links to check for mismatches.