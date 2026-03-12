# Project 6 – Cross Site Scripting (XSS)

## Objective
Demonstrate a Cross-Site Scripting (XSS) vulnerability using DVWA.

## Tools Used
Kali Linux
DVWA (Damn Vulnerable Web Application)
Web Browser

## Methodology
1. Logged into DVWA and set the security level to low.
2. Navigated to the XSS (Reflected) module.
3. Injected a JavaScript payload into the input field.
4. Payload used: <script>alert('XSS')</script>
5. The browser executed the script and displayed an alert popup.

## Result
Successfully demonstrated a reflected XSS vulnerability in DVWA.
