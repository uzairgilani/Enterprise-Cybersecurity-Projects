# Project 5 – Privilege Escalation

## Objective
Demonstrate privilege escalation on a vulnerable Linux machine (Metasploitable2).

## Tools Used
- Kali Linux
- Metasploitable2
- SSH

## Methodology
1. Connected to the target machine using SSH from Kali Linux.
2. Verified user access using the `whoami` command.
3. Performed system enumeration using `uname -a` and `id`.
4. Checked sudo permissions using `sudo -l`.
5. Escalated privileges to root using `sudo su`.

## Result
Successfully gained root access on the Metasploitable machine, demonstrating a privilege escalation vulnerability.
