# Week 9 Journal Entry

## Task 1. Knowledge test results
![KnowledgeTest Screenshot](./IMAGES/Week9_knowledgetest.png)

## Task 2. CIA Protections
**Asset 1: Customer Data**  
*Protection:* Confidentiality  
*Reason:* Unauthorised persons, such as external stakeholders, should not see customers data  

**Asset 2: Bank Account Information**  
*Protection:* Confidentiality  
*Reason:* Bank account information for the business and customers, can lead to potential data breaches and theft  

**Asset 3: Wi-Fi Access**  
*Protection:* Availability  
*Reason:* Failure of the Wi-Fi will result in system access issues.

**Asset 4: Financials**  
*Protection:* Integrity  
*Reason:* Theft of money can lead to reputational damage  

## Task 3. Threat Sources and Motivations
• Threat Source 1: Hacker  
Motivation: wants to get access to the company database to steal data to hold to ransom

• Threat Source 2: Thief  
Motivation: wants to steal the company's physical assets 

• Threat Source 3: Natural disaster (storm, fire etc)  
Motivation: the unintended destruction of company property

• Threat Source 4: Vandals  
Motivation: the intentional destruction of company property


## Task 4. Explore Vulnerabilities   
#Vulnerability 1 ID:# CVE-2026-9990  
#CVE Description:# Use after free in WebAppInstalls in Google Chrome on Mac prior to 148.0.7778.216 allowed a remote attacker who convinced a user to engage in specific UI gestures to potentially exploit heap corruption via a crafted HTML page.   
#Date:# 28 May 2026  
#CVSS Version 3 Score:# 7.5 High  
#Impact on CIA:# C = High, I = High, A = High  
#CWE ID and Name:# CWE-416 - Use After Free  
#Company:# Google and Apple  
#Description of product effected (name and what it is for): Google Chrome on Mac prior to 148.0.7778.216. Chrome is Google's web browser.  
#Simple Explanation of the Vulnerability:# An attacker could take advantage of the vulnerability to create a malicious HTML file.
#Detection/ Mitigation techniques:# Apply the official Chrome update to 148.0.7778.216.  
  
**Vulnerability 2 ID:** CVE-2026-9996   
**CVE Description:** Out of bounds read in WebRTC in Google Chrome on Mac prior to 148.0.7778.216 allowed a remote attacker to obtain potentially sensitive information from process memory via a crafted HTML page.  
**Date:** 28 May 2026  
**CVSS Version 3 Score:** 6.5 Medium  
**Impact on CIA:** C = high, I = None, A = None.  
**CWE ID and Name:** CWE- 125, Out-of-bounds read.  
**Company:** Google and Apple  
**Description of product effected (name and what it is for):** Chrome is the browser supplied by Google. Mac is the hardware supplied by Apple.  
**Simple Explanation of the Vulnerability:** There is a chance that the vulnerability could allow a hacker could obtain sensitive information.   
**Detection/ Mitigation techniques:** Update Chrome to version 148.0.7778.216 or newer on Mac OS, Launch Chrome and navigate to chrome://flags, enable the "WebRTC‑Controlled By Policy" flag, and set it to Disabled to temporarily block WebRTC functionality, and Avoid visiting untrusted or suspicious websites; consider using an ad–blocker or a content‑filtering extension to reduce exposure to malicious HTML



## Task 5. Vulnerability Disclosures
