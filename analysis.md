---Phishing Email Analysis----

## 1. Sender's Email Address
Sender:`support@paypa1-security.com`

Observation:
The email address looks suspicious because it uses the number *1* instead of the letter **l** in "PayPal". This is a common trick used in phishing emails.

**Result: Suspicious

----

2. Email Header Analysis:
I checked the email header using an online email header analyzer.

Observation:
The header showed differences in the sender's information. Authentication checks like SPF or DKIM may fail, which is common in phishing emails.
*Result:Suspicious

---

3. Suspicious Link
The email contains the following link:
`http://paypal-login-security.com/verify`

Observation:
The link is not an official PayPal website. It also uses **HTTP** instead of **HTTPS**, making it less secure.
**Result:Suspicious

---

4. Urgent Language
The email contains phrases like:

- "Verify your information immediately."
- "Your account will be suspended."
- "Within 24 hours."
The sender is trying to create urgency so that the user clicks the link without thinking.

-----
After analyzing the email, I found several phishing indicators:

- Fake sender email address
- Suspicious website link
- Urgent language
- Header inconsistencies
