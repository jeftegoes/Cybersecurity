# Cybersecurity <!-- omit in toc -->

## Contents <!-- omit in toc -->

- [1. Information Security vs Cybersecurity](#1-information-security-vs-cybersecurity)
- [2. CIA](#2-cia)
  - [2.1. Confidentiality](#21-confidentiality)
  - [2.2. Integrity](#22-integrity)
  - [2.3. Availability](#23-availability)
- [3. DAD](#3-dad)
  - [3.1. Disclosure](#31-disclosure)
  - [3.2. Alteration](#32-alteration)
  - [3.3. Deniability](#33-deniability)
- [4. Computer protocols](#4-computer-protocols)
  - [4.1. HTTP \& HTTPs](#41-http--https)
  - [4.2. SSL \& SSH](#42-ssl--ssh)
  - [4.3. FTP \& sFTP](#43-ftp--sftp)
  - [4.4. IMAP \& SMTP](#44-imap--smtp)
- [5. Cookies](#5-cookies)
- [6. TCP/IP Protocol](#6-tcpip-protocol)
  - [6.1. TCP](#61-tcp)
  - [6.2. IP](#62-ip)
  - [6.3. Uses](#63-uses)
- [7. Hackers](#7-hackers)
- [8. Hacking Methodology](#8-hacking-methodology)
  - [8.1. Reconnaissance / Footprinting](#81-reconnaissance--footprinting)
    - [8.1.1. Passive reconnaissance.](#811-passive-reconnaissance)
    - [8.1.2. Active reconnaissance.](#812-active-reconnaissance)
  - [8.2. Exploitation](#82-exploitation)
  - [8.3. Privilege Escalation](#83-privilege-escalation)
  - [8.4. Establish Persistence](#84-establish-persistence)
  - [8.5. Attack Phase](#85-attack-phase)
  - [8.6. Cover up](#86-cover-up)
- [9. WhoIS](#9-whois)
- [10. Social Engineering](#10-social-engineering)
- [11. Attacks](#11-attacks)
- [12. Malware](#12-malware)
- [13. Defences](#13-defences)
- [14. Cybersecurity at the Work Place](#14-cybersecurity-at-the-work-place)
- [15. Basic terminologies](#15-basic-terminologies)

# 1. Information Security vs Cybersecurity

- These two terms are used interchangeably all the time.
- **Cybersecurity** deals specifically with protecting your data from **cyber threats**.
- T hreats that exist on the internet threats that exist in the cyber world.
- But when you're talking about **Information Security**.
  - It's all about protecting your data.

# 2. CIA

- These are the three fundamental pillars of cybersecurity and cyber crime in general (CIA).

## 2.1. Confidentiality

- Ensuring that data is private and accessed only by those with permission to do so.
- Can be achieved with the use of passwords, biometrics, 2FA, MFA and encryption.

## 2.2. Integrity

- Ensuring that data has not been altered or tampered in any way.
- Can be achieved through the use of **hashing** or **checksums** and **access control**.

## 2.3. Availability

- Ensuring that data is always available for access and use.
- Can be achieved through the use of **backups**, **maintenance** & **disaster recovery plans**.

# 3. DAD

- DAD is basically the exact opposite of CIA.

## 3.1. Disclosure

- Data is accessed by non-authoried users.
- Trojans, brute force attacks, theft.

## 3.2. Alteration

- Data has been compromised or tampered with Malware, viruses, SQL Injection.

## 3.3. Deniability

- Access to data and resources are blocked
- Denial of Service Attacks (DDOs), Ransomware.

# 4. Computer protocols

- What's a **Protocol**?
  - A Protocol is a set of rules that determine how computers communicate with each other.
- Protocols also govern how an internet document gets transmitted to a computer screen.
- The Protocol will determine what part of the conversation comes at which time and also how the conversation ends.

## 4.1. HTTP & HTTPs

- **HTTP** = Hyper Text Transfer Protocol.
  - Determines how browsers and web servers communicate.
  - The connection is dropped once the request has been made **stateless system**.
- HTTP**s** is the **secure** version of HTTP.

## 4.2. SSL & SSH

- **SSL** = Secure Sockets Layer.
  - Used by HTTPs to provide encryption.
- **SSH** = Secure Shell.
  - Used specifically by programmers and network administrators.
- **Technically not protocols.**

## 4.3. FTP & sFTP

- **FTP** = File Transfer Protocol.
  - Governs how files are transmitted from one computer to another.
- **s**FTP = **Secure** File Transfer Protocol.

## 4.4. IMAP & SMTP

- **IMAP** = Internet Access Message Protocol.
  - Constrols how internet messages are sent.
- **SMTP** = Simple Mail Transfer Protocol.
  - Governs how emails are sent and received.

# 5. Cookies

- What's Cookies?
  - There are pieces of text stored by a web server on your hard disk.
- They allow a web site to store information on your computer and then later retrieve it.
- Their purpose is to identify a user, check for their **past activity** on the website and use this record to provide the most relevant information to the user.
- In other words, cookies are like **tags** used by web servers to identify a user.
- There are different kinds of cookies that can store different types of data.
  - Session cookies.
    - Can store your shopping cart on e-commerce sites.
  - Persistent cookies.
    - Can store your **Remember Me** data on a website e.g. login information.
- In general, cookies are mostly harmless and help websites run more efficiently but they can also be used to track you and can be exploited by hackers.

# 6. TCP/IP Protocol

- A suite of protocols used to interconnect network devices on the internet.
- Divided into 4 major layers:
  - **Datalink Layer:** Consists of protocols that operate on a link that connects hosts on a network e.g. Ethernet.
  - **Internet/Networking Layer:** Connects independent networks together e.g. IP.
  - **Transport Layer:** Handles communication between hosts e.g. TCP.
  - **Application Layer:** Standardizes data exchange for applications e.g. HTTP, FTP.

## 6.1. TCP

- **TCP** = Transmission Control Protocol.
- Divides a message or file into packets that are transmitted over the internet and then reassembled when destination is reached.

## 6.2. IP

- **IP** = Internet Protocol.
- Responsible for the address of each packet so it is sent to the correct destination.

## 6.3. Uses

- Used mostly on the internet.
- Used for emails.
- Used for playing games.

# 7. Hackers

- **Black Hat**
  - Very skilled.
  - Financial interests.
- **Grey Hat**
  - Very skilled.
  - Black Hat tatics for White Hat objectives.
  - Means justifies the end.
- **Script Kiddie**
  - Unskilled nuisances.
- **Hacktivists**
  - - Hacking for a cause, like Anonymous, WikiLeaks.
- **Disgruntled Employee (ex)**
  - Unhappy.
  - Revenge.
- **Insider Threat**
  - Spy / Saboteur.

# 8. Hacking Methodology

## 8.1. Reconnaissance / Footprinting

- Gathering as much information about the target.
- _"If you know the enemy and know yourself, you need not fear the result of a hundred battles. If you know yourself but not the enemy, for every victory gained you will also suffer a defeat. If you know neither the enemy nor yourself, you will succumb in every battle." - Sun Tzu, The Art of War_

### 8.1.1. Passive reconnaissance.

- The **only** step **that is not illegal** in the hacker methodology.
- Email addresses.
- Phone numbers.
- Social media accounts.
- Physical location.

### 8.1.2. Active reconnaissance.

- Searching for vulnerabilities and weaknesses.
  - IP Address.
  - DNS Servers.
  - Open ports.
  - Usernames.
  - Passwords.
  - Company software.

## 8.2. Exploitation

- Taking advantage of a vulnerability to gain access.
  - Phishing Email.
  - Social Engineering.
  - Unpatched software.
  - Weak passwords.
  - Malware Injection.

## 8.3. Privilege Escalation

- Increasing the control over the exploited target.
  - Creating new accounts.
  - Network Hijack (Unauthorized use of groups of IP).
  - Admin account access.

## 8.4. Establish Persistence

- Ensuring continous access even after the breach/attack has been discovered by the victim.
  - Adding backdoors.
  - Remote access control.

## 8.5. Attack Phase

- Data extraction, data corruption, malware injection.
- _The Greatest Trick the Devil Ever Pulled Was Convincing the World He Didn't Exist - Charles Baudelaire_

## 8.6. Cover up

- Avoiding detection.
  - Using ICMP tunnels (VPC).
  - Clearing event logs.
  - Erasing the command history.

# 9. WhoIS

- WHOIS is a public database that stores the information collected when someone registers a domain name or updates their DNS settings.

# 10. Social Engineering

# 11. Attacks

# 12. Malware

# 13. Defences

# 14. Cybersecurity at the Work Place

# 15. Basic terminologies

- Below are some of the main terminologies that you should be aware about in the world of computer and network security:
  - Blacklist - Used to refer to a list of banned IP addresses, applications or users.
  - Whitelist - The exact opposite of a blacklist.
  - Cat fishing - The process of creating a fake online profile in order to trick people into believing they are someone else for financial gain.
  - Authentication - The process of proving an individual is who they claim to be.
  - Data Mining - The activity of analyzing and/or searching through data in order to find items of relevance, significance or value.
  - Threat - This generally refers to anything that has the potential to cause our data, systems and networks harm.
  - Exploit - A clearly defined way to breach the security of a system.
  - Vulnerabilities - These are weaknesses within a system or network that can be exploited to cause us harm.
  - Risk - This refers to the likelihood of something bad happening. A risk requires both a threat and a vulnerability to exist.
  - Zero Day - This is used to describe a threat that is unknown to security specialists and has not been addressed.
  - Hack Value - This describes a target that may attract an above average level of attention from an attacker.
  - Non-Repudiation - This is the concept that once an action is carried out by a party it cannot be denied by that same party.
  - Logic Bomb - A malicious code that is only triggered when a set of conditions are met.
  - Obfuscation - A term used to describe the tactic of making code unclear so that humans or programs like an antivirus cannot understand it.
  - Honey Pot - A decoy or trap for hackers.
  - Spoof - The act of falsifying the identity of the source of a communication or interaction.
