# Project 4 – Password Cracking Lab

## Objective
Demonstrate password cracking techniques using Hydra and John the Ripper against vulnerable services in a controlled lab environment.

## Lab Environment
- Attacker Machine: Kali Linux
- Target Machine: Metasploitable2
- Virtualization: Oracle VirtualBox
- Network: Host-Only Adapter

## Tools Used
- Hydra
- John the Ripper
- RockYou Wordlist

## Methodology

### 1. Service Enumeration
Identified open services on the target machine using Nmap.

![Nmap Scan](01-nmap-scan.png)

### 2. SSH Brute Force Attack
Used Hydra to perform brute-force attack against SSH service.

![Hydra Attack](02-hydra-ssh-bruteforce.png)

### 3. Password Hash Extraction
Extracted password hashes from the system.

![Hash Dump](03-password-hash-dump.png)

### 4. Cracking Password Hashes
Used John the Ripper with rockyou wordlist to crack password hashes.

![John Crack](04-john-password-crack.png)

## Result
Successfully cracked user passwords using dictionary attack techniques.
Password cracked: msfadmin
Service: SSH
Target: Metasploitable2
Attack type: Hydra brute force
