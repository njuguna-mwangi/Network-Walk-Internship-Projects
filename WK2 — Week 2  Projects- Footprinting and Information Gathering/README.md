# PENETRATION TESTING REPORT
### FOOTPRINTING & NETWORK SCANNING PHASES

W2-PM-FINAL | CYBERSECURITY | NETWORKWALKS

![Author](https://img.shields.io/badge/Pentester-Samuel_Mwangi-red) <br>
![Program](https://img.shields.io/badge/Program-NetworkWalks%20Internship-blue) <br>
![Batch](https://img.shields.io/badge/Batch-B084-orange) <br>
![Date](https://img.shields.io/badge/Date-10/11/2026-yellow) <br>
![Date](https://img.shields.io/badge/Permission_Granted-Yes-green) 

| **Client/Target|
|---|
| Networkwalks (With Permission)|
| Lab Network (Owned By Me) |


| **Modules Completed:** |
|---|
| - W2-PM1 (information ) |
| - W2-PM5 (Zenmap/Nmap Scanning) |

| **Phases Covered:** |
|---| 
| - **Phase 1**: Reconnaissance & Footprinting|
| - **Phase 2:** Scanning and Hosts Discovery|
| - **Phase 3:** In Progress | 

>Disclaimer:
_I have performed these activities only on the systems & devices where I had secured written permission or the devices/systems that I own myself. All these materials are for education and research purpose only. Do not use anything from here to break the law. The instructor, the authors and Networkwalks are not responsible for what you do with this knowledge. Every action you take is your own responsibility. Misuse can lead to criminal charges, heavy fines, loss of your job and a permanent record. In most countries unauthorised access is a crime even when nothing is damaged._
# Executive Summary
### Purpose &amp; Scope
This report documents the practical activities required for Week 2. These activites include the reconnaissance of networkwalks.com domain, host discovery using zenmap. Together, they show how an attacker collects information from their target upto the point they are able to know the most valuable target to attack. This lab activity requires us to choose one task from section I of the lab manual but in this case, we will be performing all the tasks so that we can gather a lot of information as we can.
### Key Findings
_to be filled later_
### Network Scanning 
- The scanning was to be done using Zenmap which is a GUI tool for **nmap**. However, in this case, we will use both tools so that we can clearly be able to map the infrastructure clearly.A ping scan of the network **10.0.0.0/24** was done and **_** hosts discovered to be up.Their MAC addresses were also displayed and recorded.
### Risk Assessment
### Recommendations
### Conclusion
This activity shows that a lot of information can be gathered from the public domain and network responses before any act of exploitation is attempted. The next phases in this activity will be able to determine if the services and the versions running on all the four hosts can be determined and if they have any vulnerability presented out to the attacker

# Introduction
Reconnaissance is the first stage of any security assessment or any attack depending on the type of security testing is done. Before the attacker moves on to exploitation, they use this stage to collect a lot of information on the target as they can using passive and active methods. This activities help an attacker understand what exists, which servers are online, the software versions they run and which devices are connected to the same network. 
This report covers two practical modules.  The first module **W2-PM1**, is a footprinting activity where reconnaissance was done against _networkwalks.com_ where written permission was explicitly granted for these purposes. This activity uses a variety of tools indicating that in any security assessment, there are a lot of tools available to the attacker and there is no any limit to the number of the tools uses to get any information on the target. The tools used in this recon phase are:
- WHOIS
- WhatWeb
- WafW00f
- Nslookup
- Curl
- DNSRecon

Each used is used to discover different kind of information on the target.

The second practical activity **W2-PM2** involves scanning the network using zenmap or nmap where the local IP address and the subnet are mapped assuming the attacker knows them before the engagement.A ping scan is ran to determine which hosts are available together with their MAC addresses. Zenmap helps generate the network topology map.

Overall, the two modules strengthen the reconnaissance skills and shows how information about the target is obtained from the public domain or actively engaging the target. This report captures the commands used for easier reproduction and an explanation of why the findings matter in a security point of view. The findings are assessed of risks which are then followed by recommendations so that the risks can be mitigated. All the activities in this lab were performed in test environment and on live systems, permission was granted. As set out in the liability disclaimer. All the activities recorded were done for educational purposes and no liability of illegal use of the commands contained in this document will be accepted.