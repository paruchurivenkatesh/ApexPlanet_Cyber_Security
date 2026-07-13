# Task 3 – Web Application Security

## Cybersecurity & Ethical Hacking Internship
**Organization:** ApexPlanet Software Pvt. Ltd.

---

# Objective

The objective of this task was to understand common web application vulnerabilities based on the OWASP Top 10 and learn how they can be identified and prevented in a controlled laboratory environment.

---

# Lab Environment

## Attacker Machine

- Operating System: Kali Linux
- IP Address: **192.168.56.101**

## Target Machine

- Metasploitable2 / DVWA
- IP Address: **192.168.56.103**

Applications Used:

- DVWA (Damn Vulnerable Web Application)
- Burp Suite Community Edition
- Firefox Browser
- Kali Linux Terminal

---

# Topics Covered

## 1. SQL Injection (SQLi)

### Objective

Understand how improper input validation can allow database queries to be manipulated.

### Learning

- What SQL Injection is
- Types of SQL Injection
- Risks of SQL Injection
- Secure coding using parameterized queries (Prepared Statements)

### Prevention

- Prepared Statements
- Input Validation
- Least Privilege Database Accounts
- Error Handling

---

## 2. Cross-Site Scripting (XSS)

### Types Studied

- Stored XSS
- Reflected XSS

### Learning

Understood how malicious scripts can execute inside a user's browser if user input is not properly sanitized.

### Prevention

- Input Validation
- Output Encoding
- Content Security Policy (CSP)
- Secure Cookies

---

## 3. Cross-Site Request Forgery (CSRF)

### Learning

Studied how attackers may trick authenticated users into performing unintended actions.

### Prevention

- CSRF Tokens
- SameSite Cookies
- User Confirmation
- Re-authentication for Sensitive Operations

---

## 4. File Inclusion

### Topics

- Local File Inclusion (LFI)
- Remote File Inclusion (RFI)

### Learning

Understood the risks of insecure file handling and how improper validation can expose sensitive resources.

### Prevention

- Validate File Names
- Restrict File Access
- Disable Remote File Inclusion
- Use Allow Lists

---

## 5. Burp Suite

### Activities

- Configure Browser Proxy
- Intercept HTTP Requests
- Modify Requests
- Analyze Responses
- Explore Web Traffic

### Learning

Burp Suite helps security professionals understand how web applications process user requests.

---

## 6. Web Security Headers

Security headers improve browser security and help reduce common attacks.

Headers Studied

- Content-Security-Policy
- X-Frame-Options
- X-Content-Type-Options
- Referrer-Policy
- Strict-Transport-Security

---

# Tools Used

- Kali Linux
- DVWA
- Burp Suite Community
- Firefox
- Apache Web Server

---

# Skills Learned

- Web Application Security
- OWASP Top 10
- Secure Coding Concepts
- Request Analysis
- HTTP Communication
- Security Headers
- Vulnerability Mitigation

---

# Learning Outcomes

After completing this task, I developed a better understanding of how common web application vulnerabilities occur and how developers and security professionals can reduce these risks through secure coding practices and proper security controls.

I also gained practical experience using DVWA and Burp Suite in an isolated laboratory environment for educational purposes.

---

# Conclusion

This task strengthened my knowledge of web application security fundamentals and the importance of secure software development.

Understanding common vulnerabilities and their mitigations is an essential skill for ethical hackers, penetration testers, and secure software developers.

All learning activities were performed in a safe and authorized lab environment intended for cybersecurity education.

---

# Author

**Paruchuri Venkatesh**

Cybersecurity & Ethical Hacking Intern

ApexPlanet Software Pvt. Ltd.