# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

# Security Task1
findind vulnerabilities with owasp zap and burp suite
![Image](https://github.com/user-attachments/assets/314d7449-b917-41c1-afbe-52899284583a)

![Image](https://github.com/user-attachments/assets/67d0d872-14e1-492f-9fa6-4aab8b7e4063)

![Image](https://github.com/user-attachments/assets/63c4bdb5-7597-4f64-af11-d620090b5ccd)

![Image](https://github.com/user-attachments/assets/e2172da2-7eea-433d-b972-09285c36e7b9)

Key Vulnerabilities Identified:
1. Content Security Policy (CSP) Header Not Set (57 occurrences):
The application does not define a CSP header, which can lead to cross-site scripting (XSS) attacks and data injection vulnerabilities.

2. Cross-Domain Misconfiguration (72 occurrences):
Misconfigurations in handling cross-origin requests may allow unauthorized access to resources, increasing the risk of Cross-Origin Resource Sharing (CORS) attacks.

3. Hidden File Found (4 occurrences):
Sensitive files are accessible and may expose configuration or source code.

4. Timestamp Disclosure - Unix (73 occurrences):
The system reveals timestamps that can be used to infer system information, aiding attackers in planning exploits.

5. Modern Web Application Issues (50 occurrences):
Various best practice issues in web application security were detected.
