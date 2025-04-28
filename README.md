# 🔒 Web Application Penetration Test: OWASP Juice Shop

## 🧠 Overview
This lab focuses on discovering and exploiting vulnerabilities in a deliberately insecure web application, OWASP Juice Shop, using manual testing and interception proxies.

## 🎯 Objectives
- Set up OWASP Juice Shop locally
- Perform OWASP Top 10 attacks
- Document vulnerabilities and remediation steps

## 🛠 Tools and Technologies Used
- Kali Linux 2024.1
- OWASP Juice Shop
- Burp Suite Community Edition

## 🏗 Environment Setup
- Juice Shop hosted locally using Docker
- Proxy traffic through Burp Suite

## 🕵️‍♂️ Process
1. Deployed Juice Shop via Docker
2. Configured Burp Suite to intercept browser traffic
3. Identified vulnerabilities (e.g., SQLi, XSS)
4. Documented findings with screenshots

## 📷 Screenshots
- SQL Injection success
- XSS proof-of-concept

## 📄 Reports
- [Vulnerability Testing Report (PDF)](reports/juice-shop-report.pdf)

## 📚 Key Learnings
- Understanding the OWASP Top 10 risks
- Hands-on exploitation techniques
- Importance of secure coding practices

## 🔗 References
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)
- [Burp Suite Docs](https://portswigger.net/burp)
