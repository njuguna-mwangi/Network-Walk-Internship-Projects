<!-- Penetration Testing Report -->
![Author](https://img.shields.io/badge/Pentester-Samuel_Mwangi-red) <br>
![Program](https://img.shields.io/badge/Program-NetworkWalks%20Internship-blue) <br>
![Batch](https://img.shields.io/badge/Batch-B084-orange) <br>
![Date](https://img.shields.io/badge/Date-24/11/2026-yellow) <br>
![Permission](https://img.shields.io/badge/Permission_Granted-Yes-green) <br>
![Client](https://img.shields.io/badge/Client_Mediroza_General_Hospital-Yes-cyan) <br>


# Meduroza General Hospital
## Penetration Testing Report

# Executive Summary
A black-box penetration testing and vulnerability assessment was conducted against Mediroza General Hospital's web infrastructure, targeting https://medirozahospital.com, as part of the NetworkWalks Week 4 Penetration Testing Project (Batch B084).

The engagement was designed to evaluate the security of the hospital's web application by identifying potential vulnerabilities, assessing their impact, and demonstrating the risks associated with unauthorized access to sensitive information. The assessment was conducted over a five-day period under written authorization, with testing restricted to the agreed target domain.

The assessment focused on four major objectives: gaining initial access to restricted areas of the website and retrieving three confidential patient laboratory reports; analysing and recovering the contents of the encrypted PDF files; investigating potential server-side data exposure involving employee salary information and hospital shareholder details; and documenting the identified security weaknesses through a professional penetration testing report.

The engagement highlights the importance of protecting sensitive healthcare information, particularly patient medical records, employee information, and confidential organizational data. Unauthorized access to such information could expose the hospital to privacy violations, reputational damage, operational disruption, and potential legal and regulatory consequences.

The assessment findings, supporting evidence, risk ratings, and recommended remediation measures are documented in this report to help Mediroza General Hospital understand its security weaknesses and strengthen the protection of its web infrastructure and sensitive information.

# Introduction
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

# Technicla Summary

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