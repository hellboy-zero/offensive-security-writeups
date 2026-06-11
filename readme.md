# 🛡️ Offensive Security Notes

> Hands-on vulnerability research and exploitation writeups from personal home lab practice.  
> Focused on web application security — documenting real techniques, not just theory.

---

## 🧪 Lab Environment

| Component | Details |
|---|---|
| **Vulnerable Apps** | DVWA, Juice Shop, WebGoat, SecureBank |
| **Operating Systems** | Kali Linux, Windows (VM) |
| **Setup** | Local virtualized environment |

---

## 📂 Topics Covered

### 🔴 Injection
- SQL Injection (Classic, Blind, Error-based)
- Command Injection
- XML Injection

### 🟠 Client-Side Attacks
- Cross-Site Scripting (Reflected, Stored, DOM-based)
- Cross-Site Request Forgery (CSRF)
- Clickjacking

### 🟡 Broken Access Control
- Insecure Direct Object Reference (IDOR)
- Privilege Escalation
- Forced Browsing

### 🟢 Authentication & Session
- Broken Authentication
- Session Hijacking
- Weak Password Policies

---

## 📁 Repository Structure

```
offensive-security-notes/
│
├── README.md
│
├── DVWA/
│   ├── XSS.md
│   ├── SQL-Injection.md
│   └── Command-Injection.md
│
├── JuiceShop/
│   ├── Broken-Authentication.md
│   └── IDOR.md
│
└── WebGoat/
    ├── CSRF.md
    └── SQL-Injection.md
```

---

## 📝 Writeup Format

Each writeup follows a consistent structure:

- **Objective** — what vulnerability is being tested
- **Steps** — exact steps to reproduce
- **Proof of Concept** — screenshots and payloads
- **Impact** — what an attacker could do in a real scenario
- **Remediation** — how developers should fix it

---

## 🎯 Goal

I am an aspiring cybersecurity professional focused on **web application security and penetration testing.**  
These notes document my practical learning journey and serve as a reference for real-world security assessments.

---

## 🛠️ Tools Used

`Burp Suite` `Nmap` `Kali Linux` `Firefox DevTools` `SQLMap` `Nikto`

---

## 📬 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://linkedin.com/in/YOUR-LINKEDIN)
[![Email](https://img.shields.io/badge/Email-red?style=flat&logo=gmail)](mailto:YOUR-EMAIL)

---

*⚠️ All research is conducted in isolated lab environments for educational purposes only.*
