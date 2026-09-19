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
**Vulnerability 1 ID:** CVE-2026-9990  
**CVE Description:** Use after free in WebAppInstalls in Google Chrome on Mac prior to 148.0.7778.216 allowed a remote attacker who convinced a user to engage in specific UI gestures to potentially exploit heap corruption via a crafted HTML page.   
**Date:** 28 May 2026  
**CVSS Version 3 Score:** 7.5 High  
**Impact on CIA:** C = High, I = High, A = High  
**CWE ID and Name:** CWE-416 - Use After Free  
**Company:** Google and Apple  
**Description of product effected (name and what it is for):** Google Chrome on Mac prior to 148.0.7778.216. Chrome is Google's web browser.  
**Simple Explanation of the Vulnerability:** An attacker could take advantage of the vulnerability to create a malicious HTML file.
**Detection/ Mitigation techniques:** Apply the official Chrome update to 148.0.7778.216.  
  
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

**Vulnerability 3 ID:** CVE-2021-33045  
**CVE Description:** The identity authentication bypass vulnerability found in some Dahua products during the login process. Attackers can bypass device identity authentication by constructing malicious data packets.  
**Date:** 15 September 2021  
**CVSS Version 3 Score:** 9.8 Critical  
**Impact on CIA:** C = High, I = High, Availability = High  
**CWE ID and Name:** CWE-287, Improper Authentication  
**Company:** Dahua    
**Description of product effected (name and what it is for):** Dahua provides CCTV products.  
**Simple Explanation of the Vulnerability:** There is a vulnerability in the devices that allow a hacker to bypass the authentication.  
**Detection/ Mitigation techniques:** There is currently no remediation available yet.  



## Task 5. Vulnerability Disclosures

To ensure that the appropriate fix can be released, the vendor may need time to ensure they understand the problem. This will help to ensure that the right remediation can be released to the public. Further to this, it is recommended that vendors should be made aware of vulnerabilities via private disclosure (OWASP, n.d. and Microsoft, n.d.). OWASP (n.d.) says that organisations may request that the vulnerability is not made public until such a time that a fix can be implemented. OWASP (n.d.) also suggests that by going public too early, attackers may be able to take advantage of the vulnerability if it is released to the public before the appropriate fix is created.
  
While I don't have the answer to what is acceptable, I believe that a time limit should be placed. Google's Project Zero (Willis, 2020) has set a policy of 90 days for when they will publicly disclosure the bug details. This is irrespective of whether the vendor has a patch available. Willis (2020) states by setting a clear goal, this encourages faster patch development. Although, this does go against the guidance provided by OWASP, that the public release of vulnerabilities could allow attackers to take advantage. 
  
**References**
Microsoft. n.d. Microsoft's Approach to Coordinated Vulnerability Disclosure. Microsoft. https://www.microsoft.com/en-us/msrc/cvd 
OWASP. n.d. Vulnerability Disclosure Cheat Sheet. OWASP. https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html
Willis, T. 2020. Policy and Disclosure: 2020 Edition. Google. https://projectzero.google/2020/01/policy-and-disclosure-2020-edition.html 
