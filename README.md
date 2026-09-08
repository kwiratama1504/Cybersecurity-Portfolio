# Unity-Technology-Bug-Bounty
This was a university group project where we carried out a simulated penetration test on Unity's public-facing web assets. The main goal was to understand how a real web application could be assessed from the outside, starting with reconnaissance and moving into endpoint discovery and manual security testing.

# What I Worked On
- Reconnaissance and subdomain enumeration
- Endpoint discovery using FFUF
- Web application testing with Burp Suite
- API and authentication testing
- Access control testing
- Vulnerability analysis and risk assessment

# Tools Used 
- Burp Suite - Intercept and analyse web traffic.
- FFUF - Discover hidden endpoints.
- Subfinder - Find subdomains.
- Nmap - Scan ports and services.
- cURL - Send HTTP requests.
- OWASP ZAP - Analyse web traffic.
- JWT.io - Decode and inspect JWTs.

# Testing Areas
We looked at areas such as:
- Authentication and session management
- API security
- IDOR / broken access control
- JWT security
- XSS and input validation
- CORS
- Cloud storage
- Exposed endpoints

# Findings
Some of the issues identified during the assessment included token replay, broken access control, weak OTP protection, verbose error messages, and cloud storage metadata exposure. We also tested several areas where the security controls worked as expected, including JWT manipulation, CORS, and reflected XSS.

# What I learned 
This project gave me more experience with the way penetration testing is actually carried out, especially the process of going from reconnaissance to finding and testing potential vulnerabilities. It also helped me get more comfortable with Burp Suite, FFUF and other tools, as well as documenting findings and thinking about how they could be fixed.

- This project was completed as part of a university classroom exercise and was conducted within the intended testing scope.


