# 🛡️ Python Vulnerability Scanner

A modular Python-based security scanner for auditing your Python code, packages, and web headers. Built for security learners, engineers, and students looking to better understand software supply chain and static analysis risks.

## 🚀 Features

- 🔍 **Package Vulnerability Scanning**  
  Scan installed Python packages or `requirements.txt` for known CVEs using the [Safety](https://pypi.org/project/safety/) API or OSV.dev database.

- 🧠 **Static Code Analysis (SAST)**  
  Analyze Python source code using [Bandit](https://bandit.readthedocs.io/en/latest/) to detect insecure functions, weak cryptography, hardcoded secrets, and more.

- 🌐 **Web Security Header Checker**  
  Audit HTTP responses for missing or misconfigured security headers like `Content-Security-Policy`, `Strict-Transport-Security`, and `X-Content-Type-Options`.

- 🧰 **CLI Interface**  
  Choose scan types with command-line flags. Results are color-coded and saved to JSON re

## 📘 Educational Use Cases
This scanner is great for:

- Security students practicing real-world audit skills
- Developers adding checks to their CI pipeline
- Interview projects to showcase SAST and dependency security awareness
- Teaching interns and new engineers how to identify insecure code

## 🔒 Security Concepts
SAST (Static Analysis Security Testing)

- Software Supply Chain Risk
- Security Headers
- CVE Enumeration
- Python Attack Surface (e.g., eval, assert, weak hashes)

## 🧱 Future Improvements
- Add CVE search via OSV.dev API
- Dockerized version for portability
- Web GUI for non-technical users
- JSON → HTML report converter

## 🤝 Contributing
Pull requests are welcome, especially for new detection modules, custom Bandit plugins, or report enhancements.

