# HK-17 – Phishing Detection System

This project is developed as part of the **Cyber Guardian Hackathon** under the problem statement:

**HK-17 – Detect & Prevent Highly Sophisticated Phishing Campaigns Using AI
(Targeting Convenience Emails and Messages)**

---

## 📌 Problem Statement
Phishing attacks today are highly sophisticated and designed to closely resemble genuine emails and messages.
Attackers exploit urgency, fear, and trust to trick users into revealing sensitive information such as
credentials and financial details.

Existing security systems struggle to detect these advanced phishing techniques effectively.

---

## 💡 Proposed Solution
The proposed system detects phishing attacks using a **rule-based AI approach** that focuses on
phishing behavior and intent rather than relying only on datasets.

The system analyzes:
- Email and message content
- URL structure
- Social engineering behavior patterns

This approach helps detect even newly generated phishing attacks.

---

## 🏗️ System Architecture
The system follows a modular, API-based architecture:

- Input Layer: Email / Message / URL
- Analysis Layer:
  - Text Analysis Module
  - URL Analysis Module
  - Behavior Analysis Module
- Decision Layer:
  - Risk scoring
  - Final classification (Safe / Suspicious / Phishing)
- Output Layer:
  - Detection result with explanation

---

## 🔄 Prototype Workflow
1. User submits an email, message, or URL
2. Input is analyzed by all modules in parallel
3. Rule-based checks are applied
4. Risk scores are combined
5. Final phishing detection result is returned

---

## 📸 Prototype Screenshots

### Phishing Detection Output
![Phishing Output](screenshots/phishing_output.png)

### Backend / API Response
![API Response](screenshots/api_response.png)

*(Screenshots show the actual working prototype developed by the team.)*


## 🛠️ Tech Stack
- Frontend: HTML, CSS, JavaScript (or your frontend framework)
- Backend: Python
- API Framework: FastAPI
- Detection Logic: Rule-based AI (Regex, pattern matching)
- Version Control: Git & GitHub

---

## 🚀 Implementation Status
- Frontend and backend implemented
- Core phishing detection logic completed
- Tested using sample phishing and legitimate inputs
- Working prototype available

---

## 👨‍💻 Team Members
- R. Sanjay
- R. Ranjith Kumar

---

## 📎 Note
This repository is actively maintained with regular commits to track development progress.

