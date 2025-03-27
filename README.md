Task 1: Vulnerability Assessment of a Web Application

 Overview

This repository contains the results and findings from the vulnerability assessment of a sample web application. The assessment was conducted using various tools such as OWASP ZAP, Burp Suite, and Nmap to identify security risks and vulnerabilities.

Objectives

- Perform an in-depth security assessment of the web application.
- Identify security flaws and misconfigurations.
- Document vulnerabilities along with their severity levels.
- Provide recommendations for mitigation.

 Tools Used

- **OWASP ZAP** - Automated web application security scanning.
- **Burp Suite** - Manual and automated web security testing.
- **Nmap** - Network scanning and enumeration.
- **Wireshark** - Packet sniffing and analysis.

 Reports

The following reports are included in this repository:

 **[Vulnerability Assessment Report](./Vulnerability%20Assessment%20Report-1.pdf)** - A comprehensive report detailing identified vulnerabilities, risk levels, and suggested mitigations.
 **[ZAP Scan Report](./ZAP%20by%20Checkmarx%20Scanning%20Report.html)** - The security scan results generated using OWASP ZAP.

 Key Findings

1. **Injection Vulnerabilities** - SQL Injection, XSS, and Command Injection risks were detected.
2. **Broken Authentication** - Weak session management and password policies.
3. **Sensitive Data Exposure** - Unencrypted data transmission over HTTP.
4. **Misconfigurations** - Default credentials, unnecessary open ports, and exposed directories.
5. **Security Headers Missing** - Lack of proper HTTP security headers.
