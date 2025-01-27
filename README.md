# EmailPhishingAnalysis

# Email Analysis of Phishing Attempt

## Overview

This repository contains the analysis of a phishing email that was identified within my Gmail inbox. The goal of this analysis is to highlight the key indicators of a phishing attempt, describe the methods used to identify it, and provide insights into how to avoid falling victim to similar attacks in the future.

## Purpose

The purpose of this analysis is to:
- Educate users about how to identify phishing emails.
- Document the methodology used to assess the email.
- Raise awareness about common phishing tactics and techniques.

## Email Details

- **Subject Line:** Re
- **Sender Address:** Hoang Van Dung <DungHV6@vinhphuc.gov.vn>
- **Date Received:** Thu, Jan 2, 2025 at 6:53 PM (Delivered after 40 seconds)
- **Email Content Summary:** Claiming to be a lottery winner and using "kindness" to share his award
  
-![Screenshot 2025-01-26 222303](https://github.com/user-attachments/assets/1d730458-2fe0-4c06-aa3a-c3cb60860d14)

-![Screenshot 2025-01-26 222532](https://github.com/user-attachments/assets/463e3bf1-7a3f-4acb-8c0b-b5bd541c2e97)


## Analysis

The email was identified as phishing due to the following reasons:

### 1. **Suspicious Sender Address**
   - The email appeared to come from a legitimate source (e.g., a bank or online service), but the sender's email address was not consistent with the official domain of the organization.
   
### 2. **Suspicious Links and URLs**
   - The email contained links that appeared to direct to official websites, but upon closer inspection, the URL was malformed or led to a suspicious domain.
  
### 3. **Urgent Language and Call to Action**
   - The email used urgent language like "Immediate action required!" or "Your account will be locked unless you respond within 24 hours!"
   - Phishing emails often create a sense of urgency to provoke hasty decisions.

### 4. **Generic Greeting**
   - The email used a generic greeting like "Dear User" instead of addressing me by my name, which is common in phishing attempts.

### 5. **Spelling and Grammar Errors**
   - The email contained unusual phrasing or grammatical mistakes, which is often a red flag of a phishing attempt.

### inspection###
    - We inspected and did an email phishing analysis on the email and its contents
    - Some of the tools we used were MX toolbox, whois.com, hybrid analysis, and infobyip.com
    - When starting email analysis, we look at the email and then view its original contents to pull information such as DKIM, SPF, Message ID, header's and the contents.
### Part 1 of inspection###
    - When doing email analysis we look at the header and find things such as sender, DKIM, IP address, etc.
  -![Screenshot 2025-01-26 222532](https://github.com/user-attachments/assets/58a5ec55-9cae-493c-ac1c-dad7a437711e)

  -![Screenshot 2025-01-26 222602](https://github.com/user-attachments/assets/b71d8fe3-7117-4cdb-8487-2520c933ca25)

#### part 2 of inspection##
- We used infobyip to find the origin, Domain and ASN of the sender

-![Screenshot 2025-01-26 222847](https://github.com/user-attachments/assets/219d0051-37ef-4709-a743-92b5fb6a5f3e)

-![Screenshot 2025-01-26 222917](https://github.com/user-attachments/assets/0c6eed9c-7231-4e4a-85be-04e86650e9f7)

  We also used shodan.io for email analysis and found info on Hostnames and ISP
-![Screenshot 2025-01-26 223423](https://github.com/user-attachments/assets/e85da40c-dd7c-42e7-86b5-2d9ffebd2772)

### Part 3###
- We used mxtoolbox.com fore more analysis and put the entire email header in the contents. Upon investigation, we saw that the sender's info has been blacklisted
-![Screenshot 2025-01-26 223617](https://github.com/user-attachments/assets/96a71203-cec6-4597-a81e-9e799fd5f9b3)

-![Screenshot 2025-01-26 225005](https://github.com/user-attachments/assets/a3a1ef73-3ffd-4ab5-bece-be2b54000620)

-![Screenshot 2025-01-26 225549](https://github.com/user-attachments/assets/7c240951-6665-4a4f-983c-0a1d7d2feeac)

-![Screenshot 2025-01-26 225005](https://github.com/user-attachments/assets/306e27b7-44b0-47fa-9e4f-6d6492fe6d53)

### conclusion ##
- Through analyzing email headers, SPF SMTP, DKIM, and message bodies, we found that the sender of the email has been blacklisted and been reported for abuse. We also found the address of the sender and their ISP information. This confirms our suspicions of the email's contenrts.






## How to Protect Yourself from Phishing

- **Check the sender’s email address** for consistency with the official domain.
- **Be cautious with links**—hover over them to verify the destination URL.
- **Look out for urgent or threatening language** designed to rush you into action.
- **Avoid downloading attachments** from unknown or unexpected sources.
- **Verify the message through official channels** (e.g., by contacting the company or service directly).











