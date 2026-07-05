# github-profile-json-generator
A Python application that retrieves GitHub profile information, analyzes repositories, and automatically generates a JSON report.
# GitHub Profile JSON Generator

> **Cyber Security Internship – Task 5**  
> **Company:** SQROCK IT SOLUTION

## 📌 Overview

The **GitHub Profile JSON Generator** is a Python-based OSINT (Open Source Intelligence) utility that collects publicly available GitHub profile information through the GitHub REST API.

The application retrieves a user's profile details, analyzes repository programming languages, generates a structured JSON output, and automatically saves the results into a `profile.json` file for further analysis or reporting.

---

## 🎯 Objectives

- Retrieve publicly available GitHub profile information.
- Analyze repository programming languages.
- Generate structured JSON data.
- Automatically create and save a `profile.json` file.
- Demonstrate API integration and JSON processing using Python.

---

## ✨ Features

- Fetch GitHub user information
- Retrieve public repositories
- Count top programming languages
- Generate formatted JSON output
- Automatically save results to `profile.json`
- Clean, readable, and modular Python code

---

## 🛠 Technologies Used

- Python 3
- GitHub REST API
- Requests Library
- JSON Module

---

## 📂 Project Structure

```
GitHub-Profile-JSON-Generator/
│── github_profile_json.py
│── profile.json
└── README.md
```

---

## ▶️ Installation

Install the required package:

```bash
pip install requests
```

---

## 🚀 Usage

Run the script:

```bash
python github_profile_json.py
```

The program will:

- Fetch GitHub profile information
- Analyze repository languages
- Display JSON output
- Automatically generate **profile.json**

---

## 📄 Sample Output

```json
{
    "name": "Linus Torvalds",
    "username": "torvalds",
    "company": null,
    "location": "Portland, OR",
    "bio": "Software engineer and creator of Linux and Git",
    "public_repos": 8,
    "followers": 310266,
    "following": 0,
    "top_languages": {
        "C": 8,
        "C++": 1,
        "OpenSCAD": 1
    }
}
```

---

## 📚 Learning Outcomes

- REST API Integration
- JSON Parsing
- Python File Handling
- Open Source Intelligence (OSINT)
- GitHub Data Collection
- Cyber Security Automation

---

## 🔐 Cyber Security Relevance

This project demonstrates how publicly available GitHub information can be collected and organized using Python. Such techniques are commonly used in **Open Source Intelligence (OSINT)** for cybersecurity research, security assessments, and reconnaissance while respecting publicly available data.

---

## 👨‍💻 Internship Details

**Internship:** Cyber Security Internship

**Company:** SQROCK IT SOLUTION

**Task:** Task 5 – GitHub Profile JSON Generator

---

## 📜 License

This project is created for educational and internship purposes only.

---

**Developed as part of the Cyber Security Internship at SQROCK IT SOLUTION.**
