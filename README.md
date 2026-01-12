HK-17 – Detect & Prevent Highly Sophisticated Phishing Campaigns Using AI

This project is developed as part of the Cyber Guardian Hackathon under the problem statement:

HK-17 – Detect & Prevent Highly Sophisticated Phishing Campaigns Using AI
(Targeting Convenience Emails and Messages)

📌 Problem Statement

Phishing attacks have evolved into highly sophisticated cyber threats that closely resemble legitimate emails and messages.
Attackers exploit urgency, fear, trust, and authority to manipulate users into revealing sensitive information such as login credentials, OTPs, and financial details.

Due to the increasing reliance on convenience emails and messages, many users fail to identify these attacks.
Existing security systems struggle to detect such advanced phishing techniques, especially newly generated and behavior-based attacks.

💡 Proposed Solution

The proposed solution is a rule-based AI phishing detection system that focuses on phishing behavior and intent, rather than relying only on historical datasets.

The system analyzes:

Email and message content to detect urgency, fear, and impersonation

URL structure to identify fake or suspicious links

Social engineering behavior patterns commonly used in phishing campaigns

This approach enables the system to detect both known and previously unseen phishing attacks effectively.

🏗️ System Architecture

The system follows a modular, API-based architecture to ensure scalability and clarity.

Architecture Layers:

Input Layer: Email / Message / URL

Analysis Layer:

Text Analysis Module

URL Analysis Module

Behavior Analysis Module

Decision Layer:

Risk scoring mechanism

Final classification (Safe / Suspicious / Phishing)

Output Layer:

Detection result with explanation

This design allows parallel analysis and faster phishing detection.

🔄 Prototype Workflow

User submits an email, message, or URL

Input is processed by all analysis modules in parallel

Rule-based AI checks are applied in each module

Risk scores are combined

Final phishing detection result is generated with reasons

The workflow ensures real-time and explainable detection.

📸 Prototype Screenshots
🔹 Phishing Detection Output

🔹 Backend / API Response

(Screenshots represent the actual working prototype developed by the team.)

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: Python

API Framework: FastAPI

Detection Logic: Rule-based AI (Regex, pattern matching)

Version Control: Git & GitHub

🚀 Implementation Status

Frontend and backend implemented

Core phishing detection logic completed

Tested using phishing and legitimate sample inputs

Working prototype successfully classifies threats

👨‍💻 Team Members

R. Sanjay

R. Ranjith Kumar

📎 Note for Evaluators

This repository is actively maintained with regular commits to track implementation progress, documentation updates, and prototype improvements as part of the hackathon development process.
