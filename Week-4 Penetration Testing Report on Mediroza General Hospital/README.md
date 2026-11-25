<!-- Penetration Testing Report -->
![Scope](https://img.shields.io/badge/Pentester-Njuguna_Mwangi-red) <br>
![Program](https://img.shields.io/badge/Program-NetworkWalks%20Internship-blue) <br>
![Batch](https://img.shields.io/badge/Batch-B084-orange) <br>
![Date](https://img.shields.io/badge/Date-25/11/2026-yellow) <br>
![Permission](https://img.shields.io/badge/Permission_Granted-Yes-green) <br>


# Project Details
|Project Type|Penetration Testing & Vulnerability Assessment|
|---|---|
|Client Name|Mediroza General Hospital|
|Target|https://medirozahospital.com|
|Scope|Full black-box penetration test. Identify vulnerabilities, exploit them to demonstrate real impact, and document all findings in a professional report.|
|RoE|Testing limited to the target domain only. No social engineering. No denial of service. No testing outside agreed scope|
|Authorization|The client has provided written authorisation to conduct security testing on their web infrastructure.|
|Timeline|5 days.|
|Pentester|Njuguna Mwangi|
|Date| 25/11/2026|

---

# 1. Executive Summary
A black-box penetration testing and vulnerability assessment was conducted against Mediroza General Hospital's web infrastructure, targeting https://medirozahospital.com, as part of the NetworkWalks Week 4 Penetration Testing Project (Batch B084).

The engagement was designed to evaluate the security of the hospital's web application by identifying potential vulnerabilities, assessing their impact, and demonstrating the risks associated with unauthorized access to sensitive information. The assessment was conducted over a five-day period under written authorization, with testing restricted to the agreed target domain.

The assessment focused on four major objectives: gaining initial access to restricted areas of the website and retrieving three confidential patient laboratory reports; analysing and recovering the contents of the encrypted PDF files; investigating potential server-side data exposure involving employee salary information and hospital shareholder details; and documenting the identified security weaknesses through a professional penetration testing report.

The engagement highlights the importance of protecting sensitive healthcare information, particularly patient medical records, employee information, and confidential organizational data. Unauthorized access to such information could expose the hospital to privacy violations, reputational damage, operational disruption, and potential legal and regulatory consequences.

The assessment findings, supporting evidence, risk ratings, and recommended remediation measures are documented in this report to help Mediroza General Hospital understand its security weaknesses and strengthen the protection of its web infrastructure and sensitive information.

# 2. Introduction

Mediroza General Hospital's web infrastructure was selected for a penetration testing and vulnerability assessment exercise as part of the NetworkWalks Week 4 Practical Penetration Testing Project (Batch B083). The engagement involved conducting a black-box security assessment of the hospital's web application, targeting **https://medirozahospital.com**.

The primary objective of the assessment was to identify security vulnerabilities and weaknesses within the target application, demonstrate their potential impact through controlled exploitation, and document the findings in a professional penetration testing report.

The assessment was structured around four key milestones:

1. **Initial Access:** Identify exposed entry points, examine authentication mechanisms, assess input-handling weaknesses, and attempt to gain access to restricted areas to retrieve three confidential patient laboratory reports.
2. **Data Extraction:** Analyse and recover the contents of the three retrieved encrypted PDF laboratory reports.
3. **Further Data Exposure:** Investigate the retrieved information and associated file properties to identify potential server-side data exposure, including hospital employee salaries and shareholder details.
4. **Reporting:** Document the assessment process, findings, supporting evidence, risk ratings, and recommendations for remediation.

The engagement was scheduled to run for five days and was conducted under written authorization granted by the client. Testing was restricted to the specified target domain. Social engineering, denial-of-service attacks, and activities outside the agreed scope were prohibited.

This report presents the assessment objectives, identified security weaknesses, exploitation evidence, potential business impact, and recommended remediation measures. Its purpose is to provide a clear understanding of the security risks identified during the engagement and support improvements to the confidentiality and security of the hospital's information systems.

# 3. Technical Summary

The Mediroza General Hospital penetration testing engagement involved a black-box assessment of the target web application hosted at **https://medirozahospital.com**. The assessment was designed to evaluate the application's security posture by examining exposed entry points, authentication mechanisms, input-handling processes, file protection mechanisms, and potential information disclosure vulnerabilities.

The technical assessment was divided into four phases:

**1. Initial Access and Web Application Assessment**

The first phase focused on reconnaissance and identifying exposed application entry points. Authentication mechanisms and user-input handling were examined to identify weaknesses that could potentially allow unauthorized access to restricted resources. The primary objective was to retrieve three confidential patient laboratory reports in PDF format.

**2. PDF Encryption Analysis and Data Recovery**

The second phase involved examining the encryption mechanisms applied to the three retrieved PDF documents. Appropriate tools and wordlists were to be selected to attempt password recovery and gain access to the protected document contents. Each document was treated independently, as different recovery techniques might be required.

**3. Server-Side Information Disclosure Investigation**

The third phase focused on analysing the previously retrieved information and examining file properties for additional evidence of sensitive data exposure. The investigation aimed to identify a further exposure on the client's server involving hospital employee salary records and shareholder details.

**4. Security Reporting and Remediation**

The final phase involved consolidating the technical findings into a professional penetration testing report. Each identified vulnerability was to be documented with supporting evidence, an appropriate severity rating (Critical, High, Medium, or Low), an explanation of its potential business impact, and actionable remediation recommendations.

The engagement was conducted over five days under written authorization, with testing restricted to the specified target domain. Social engineering, denial-of-service attacks, and testing outside the agreed scope were prohibited.

The technical findings and exploitation evidence should be used to establish the final security assessment and determine the level of risk posed to the hospital's web infrastructure and sensitive information.


# 4. Lab Objectives

The primary objective of this penetration testing lab was to assess the security of Mediroza General Hospital's web application through an authorized black-box penetration test. The exercise aimed to identify security weaknesses, demonstrate their potential impact, and evaluate the exposure of sensitive hospital information.

The specific objectives were:

- **Conduct Reconnaissance:** Gather information about the target web application and identify exposed entry points and potential attack surfaces.

-  **Identify Application Vulnerabilities:** Examine authentication mechanisms, user-input handling, and other application components to identify security weaknesses.

-  **Gain Initial Access:** Exploit identified weaknesses to access restricted areas of the application and retrieve three confidential patient laboratory reports.

-  **Analyse PDF Encryption:** Examine the encryption mechanisms protecting the retrieved PDF documents and attempt to recover their contents using appropriate tools and wordlists.

-  **Investigate Sensitive Data Exposure:** Analyse retrieved documents and their properties to identify further server-side information exposure.

-  **Identify Confidential Organizational Information:** Locate and document hospital employee salary information and shareholder details exposed through the identified server-side weakness.

-  **Document Security Findings:** Provide technical evidence of identified vulnerabilities and successful exploitation, including relevant screenshots and recovered information.

-  **Assess Security Risks:** Assign appropriate severity ratings (Critical, High, Medium, or Low) based on the identified vulnerabilities and their potential impact.

-  **Recommend Remediation Measures:** Provide actionable security recommendations to address identified weaknesses and improve the protection of sensitive hospital information.

-  **Maintain Testing Scope and Authorization:** Conduct all activities within the explicitly authorized target domain while adhering to the project restrictions and ethical penetration testing principles.

# 5. Tools and Technologies Used

The penetration testing engagement involved the use of cybersecurity tools and technologies to support reconnaissance, vulnerability assessment, exploitation, document analysis, and security reporting.

The tools used or selected for the assessment included:

| Tool | Purpose |
|---|---|
|Nikto|A web application vulnerability scanner|
|Maltego|OSINT tool for relationships graphing|
| Nmap/rustscan | Network reconnaissance, port scanning, and service enumeration. |
| WhatWeb | Web technology identification and fingerprinting. |
| feroxbuster | Web directory and file enumeration. |
| Burp Suite | Intercepting HTTP requests, analysing application responses, and testing web application vulnerabilities. |
| cURL | Sending HTTP requests and examining server responses. |
| Browser Developer Tools | Inspecting application behaviour, cookies, requests, and responses. |
| Hashcat & John the Ripper | Password recovery and encryption analysis where supported. |
| PDF analysis utilities | Examining PDF document properties, encryption, and metadata. |
| ExifTool | Extracting metadata from retrieved documents and other files. |
| Linux Terminal | Executing assessment commands, managing tools, and analysing results. |
| Git / GitHub | Maintaining technical documentation and organizing project evidence. |

**Operating Environment**

- Operating System: Linux-based penetration testing environment.

The selected tools supported the different assessment activities, from initial reconnaissance and web application testing to encrypted document analysis and preparation of the final security report.

# 6. Methodology

The assessment followed a structured black-box penetration testing methodology designed to identify, validate, and document security vulnerabilities within Mediroza General Hospital's web application.

The testing process was divided into the following phases:

### 6.1 Reconnaissance

Initial reconnaissance involved gathering information about the target domain, identifying exposed entry points, and understanding the publicly accessible web application. The objective was to establish the application's attack surface and identify potential areas for further investigation.

### 6.2 Enumeration and Attack Surface Identification

The identified entry points were examined to understand available resources, application functionality, authentication mechanisms, and input-handling behaviour. This phase helped identify potentially vulnerable components and restricted areas requiring further security assessment.

### 6.3 Vulnerability Identification and Initial Access

The application was assessed for weaknesses in authentication and user-input handling. Identified vulnerabilities were investigated through controlled testing to determine whether they could provide unauthorized access to restricted resources. The primary objective was to retrieve the three confidential patient laboratory reports specified in the project brief.

### 6.4 PDF Encryption Analysis and Password Recovery

The three retrieved PDF documents were examined to identify their encryption properties and protection mechanisms. Appropriate analysis and password-recovery techniques were considered for each document, with different approaches applied where necessary.

### 6.5 Data Analysis and Information Disclosure Investigation

Following document recovery, the retrieved files were analysed beyond their visible contents. Their properties and metadata were examined for additional information that could reveal further exposure on the client's server. This investigation focused on identifying hospital employee salary information and shareholder details.

### 6.6 Exploitation Validation and Evidence Collection

Potential vulnerabilities were evaluated to establish their security implications. Relevant evidence, including screenshots, application responses, retrieved documents, and technical observations, was collected to support the assessment findings and demonstrate the impact of identified weaknesses.

### 6.7 Risk Assessment

Each confirmed vulnerability was evaluated according to its potential impact and associated security risk. Findings were classified using the following severity levels:

- Critical
- High
- Medium
- Low

### 6.8 Reporting and Recommendations

The final phase involved consolidating the assessment results into a professional penetration testing report. Each finding was documented with its description, supporting evidence, potential business impact, severity rating, and recommended remediation measures.

### 6.9 Rules of Engagement

All testing activities were conducted within the authorized scope of the engagement. Testing was restricted to the specified target domain. Social engineering, denial-of-service attacks, and testing outside the agreed scope were prohibited.

The methodology followed the four project milestones established by NetworkWalks: Initial Access, Data Extraction, Attack (Cracking), and Penetration Testing Report.