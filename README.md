# Phishing_email_analysis_task2
# 📧 Phishing Email Analysis Report

## 🎯 Objective
To analyze and identify phishing traits in suspicious emails, and raise awareness of email-based social engineering attacks.

---

## 📩 Email Sample – Banco do Bradesco Livelo Points

![Bradesco Phishing](./phishing_email_bradesco.png)

### 📌 Details:
- **From**: banco.bradesco@atendimento.com.br  
- **Subject**: You have 92,990 Livelo points expiring today  
- **Language**: Portuguese (translated to English)  
- **Urgency**: “Redeem your points now before they expire”  
- **Red Flag**: Uses fear of losing reward points to manipulate users  
- **Unverified Link**: Call-to-action “Redeem Now” button  

### 🧪 Verdict: Phishing
- Sender domain can be spoofed.  
- Deceptive UI and reward-based bait.  
- Likely to lead to credential harvesting.

---

## 🧪 Header Analysis (General Guide)

Use tools like:  
- 🔗 [Google Header Analyzer](https://toolbox.googleapps.com/apps/messageheader/)  
- 🔗 [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx)  

Check:
- SPF/DKIM/DMARC failures  
- IP address mismatches  
- From vs. Return-Path mismatches  

---

## 🔍 VirusTotal Scanning

To scan URLs or attachments:
- Visit: https://www.virustotal.com/  
- Paste the suspicious link or file  
- Check detection results across engines  

---

## ✅ Conclusion

This email displays clear phishing indicators including:  
- Fake sender identity  
- Emotional manipulation (urgency, expiring rewards)  
- Data theft attempt via credential-harvesting links  

---
Included file
--email header analysis with
-----MXTOOL BOX
-----VIRUS TOTAL
----EMAIL SCREENSHOT
