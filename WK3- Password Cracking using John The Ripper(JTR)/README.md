## Week 3 John the Ripper Assignment
WEEK 3 | Password Cracking | John The Ripper

![Author](https://img.shields.io/badge/Student-Samuel_Mwangi-red) <br>
![Program](https://img.shields.io/badge/Program-NetworkWalks%20Internship-blue) <br>
![Batch](https://img.shields.io/badge/Batch-B084-orange) <br>
![Date](https://img.shields.io/badge/Date-20/11/2026-yellow) <br>
# Executive Summary 
This lab activity is focused on understanding and practically demonstrating how passwords are recovered in an IT settings.The passwords are recovered so that the password protected documents can be read. Password protected documents are increasingly used in the industry to limit unauthorised access to confidential information in case the document falls into wrong hands.This exercise involved cracking a pdf password which is part of week 3 project module in **NetworkWalks** ethical hacking internship program.

The primary objective of this lab activity was to gain hands on skills required to audit passwords protecting organizations confidential document using tools such as **John the Ripper** which helps in extracting the passwords and assessing their strength.
This practical activity involved recovering passwords from password protected documents by first extracting the hash from the document which contains information required by john the ripper to recover the password.

Beyond password recovery and assessment, this activity provided insights between encryption, hashing and password security which shows that a document can also be subjected to offline password cracking stressing on the importance of a complex password that is not easily predictable.


In conclusion, the project showed the use of john the ripper to recover and assess password strength from a password protected documents. The knowledge and skills acquired here are foundational to the skills and techniques used in professional cybersecurity assessments.

# Introduction
Password security is a critical aspect of information security where critical information is protected from unauthorised access. This password protection applies to digital resources specifically documents where weak or less complex passwords are easier to crack compared to complex passwords. Password cracking is therefore essential for a cyber security professional so that they can help identify potential weak security links.

This project focuses on using John the Ripper to recover passwords from an encrypted pdf document. The recovery process required extracting the document hash, saving the hash and importing the hash to **john**  for password recovery.

Through this, the project allows us acquire practical skills in password recovery ranging from hash extraction to use of password tool in password cracking. This lab activity also highlights the importance of a complex password in protecting confidential data.

# Technical Summary
This project involved using password auditing tools:- John the ripper herein referred to as **john**. Although there are other tools such as **hashcat** that can be used to recover the password, our focus in this lab activity is with john. The technical implementation of how password assessment and recovery worked followed the following steps.

1. **Tool installation:** By default, the tool is already installed in Kali Linux and configured to run with the command **john** directly in the terminal.


2. Hash extraction from the pdf file

3. Hash preparation and storage in a hash.txt file

4. Hash importation to john

5. Password cracking where john runs the file hash against a wordlist and recovers the password.

6. Password verification where after successful cracking of the password, the password is tried to open the password protected document.

# Lab Objectives
The primary objectives of this lab activity was to equip the student with hands on skills to assess passwords using a password auditing and assessment tool.Other objectives include:

- generating file hashes from any file
- importing the file  hash into password auditing tool
- loading a password wordlist into the password auditing tool

# Tools and resources used
The tool required in this activity is john. It performs the activities of generating the file hash and running a password crack against the generated hash file.

# Methodology
