# 🛡️ SentinelPass: Secure Password Analyzer

A lightweight, **Zero-Trust** web application designed to analyze password entropy and strength locally in the browser. Built as a foundational project for Cloud Security studies.

## 🚀 Live Demo
[Check out the tool here!](REPLACE_WITH_YOUR_GITHUB_PAGES_LINK)

---

## 🔒 Security Features
As a security-focused project, this tool implements several industry best practices:

* **Client-Side Processing:** No password data is ever sent to a server. All analysis is done via JavaScript in the user's browser, preventing "Man-in-the-Middle" (MITM) attacks.
* **Regex-Based Entropy Check:** Evaluates complexity based on:
    * Minimum 12-character length (NIST standard).
    * Uppercase/Lowercase requirements.
    * Numerical and Special Character inclusion.
* **Shoulder-Surfing Protection:** Includes a visibility toggle so users can verify their input only when safe to do so.

## ☁️ Cloud Security Context
This project demonstrates the **"Identity"** pillar of the AWS Well-Architected Framework:
1.  **IAM Principles:** Teaches users to create stronger credentials for Cloud Console access.
2.  **Zero-Knowledge Architecture:** Demonstrates how to build tools that don't require storing sensitive user data (PII).

## 🛠️ Tech Stack
* **HTML5/CSS3:** Responsive UI with a cybersecurity-themed "Dark Mode."
* **JavaScript:** Logic and Regex for real-time security analysis.
* **GitHub Pages:** Automated deployment and hosting.

---

## 📖 How to Use
1. Clone the repository: `git clone https://github.com/kajal20-cloud/sentinel-pass.git`
2. Open `index.html` in any modern web browser.
3. Enter a password to see real-time security feedback.

## 📝 License
This project is licensed under the MIT License.