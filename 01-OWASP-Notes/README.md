
# OWASP Notes – Week 6

**Intern:** Prajapati Meet Ghanshyam  
**Organization:** DG Interns Hub  
**Task:** Web Application Security and VAPT  
**Date:** 28 October 2026

## 1. What is OWASP?

OWASP (Open Worldwide Application Security Project) is an organization that provides resources and guidance to improve web application security.

## 2. What is VAPT?

VAPT stands for Vulnerability Assessment and Penetration Testing. It helps identify and validate security weaknesses in systems and applications.

## 3. Common Web Application Vulnerabilities

- **SQL Injection (SQLi):** Improperly handled user input may affect database queries.
- **Cross-Site Scripting (XSS):** Untrusted input may execute JavaScript in a user's browser.
- **Security Misconfiguration:** Incorrect security settings may expose an application to risk.
- **Missing Security Headers:** Absent or weak HTTP security headers can reduce browser-side protection.

## 4. Tools Used

- **DVWA:** A deliberately vulnerable web application for security practice.
- **Burp Suite Community Edition:** Used to inspect and analyze HTTP requests and responses.
- **OWASP ZAP:** Used to scan web applications for potential security issues.

## 5. Security Best Practices

- Use parameterized SQL queries.
- Validate input and safely encode output.
- Apply appropriate access controls.
- Configure security headers correctly.
- Keep software and dependencies updated.
- Validate scanner findings manually before reporting them.

## 6. Lab Scope

Testing was performed on the local DVWA environment at `http://localhost:4280` for educational purposes.

## 7. Conclusion

This task introduced web application security testing, SQL Injection, XSS, HTTP traffic analysis, and automated vulnerability scanning. Findings should be reviewed and validated before being treated as confirmed vulnerabilities.
