# 🛡️ TryHackMe - Phishing Emails Intro (Write-Up & Notes)

**Room Link:** [TryHackMe - Phishing Emails Intro](https://tryhackme.com/room/phishingemails2rytmuv)  
**Author:** Doğukan Akçay  
**Role:** CTI Analyst  

---

## 📌 Key Concepts Learned
- **Email Header Analysis:** Examining `Received`, `Return-Path`, `Message-ID`, and `X-Header` fields to trace the true origin of suspicious emails.
- **Email Authentication Frameworks:** Understanding **SPF** (Sender Policy Framework), **DKIM** (DomainKeys Identified Mail), and **DMARC** (Domain-based Message Authentication) to detect email spoofing.
- **IoC Extraction:** Identifying malicious artifacts such as malicious URLs, embedded tracking pixels, phishing domains, and malicious attachments (`.exe`, `.iso`, `.pdf`, etc.).
- **Initial Access Vector (MITRE ATT&CK T1566):** Analyzing how threat actors leverage phishing campaigns for credential harvesting and initial network access.

---

## 🛠️ Tools & Techniques
- Email Header Parsers (MXToolbox, CyberChef)
- URL Defanging & Domain Reputation Checking
- Indicator of Compromise (IoC) Extraction

---

*Notes and laboratory completion verification from TryHackMe CTI track.*
