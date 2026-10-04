# 🛡️ NiveshRaksha AI

### AI-Powered Investor Safety & Financial Fraud Awareness Platform

NiveshRaksha AI is an investor-safety web application designed to help retail investors, especially first-time and Tier-2/3 users, identify warning signs in suspicious investment communications.

The platform analyzes investment messages and provides an explainable risk score, detected warning indicators, and recommended safety actions.

---

## 🚨 Problem Statement

Retail investors increasingly receive suspicious investment messages through SMS, WhatsApp, Telegram, social media, and email.

Common warning signs include:

- Guaranteed or risk-free returns
- Unrealistic profit promises
- Urgent payment requests
- OTP or password requests
- Advance verification fees
- Suspicious links
- Social-media investment groups
- False claims of authority

Many first-time investors may not recognize these warning signs.

---

## 💡 Our Solution

NiveshRaksha AI allows users to paste an investment-related message and analyzes it for predefined financial-safety warning patterns.

The platform provides:

- Risk score from 0–100
- HIGH RISK / CAUTION / LOWER RISK classification
- Detected warning indicators
- Explanation for each indicator
- Recommended safety actions
- Analysis history
- Risk distribution dashboard
- Downloadable safety report
- Demo investment messages

---

## 🧠 Intelligent Analysis

The current prototype uses an explainable text-analysis engine.

It checks for patterns related to:

1. Guaranteed returns
2. Urgency and pressure
3. Sensitive credentials
4. Advance payment requests
5. Suspicious payment methods
6. False authority claims
7. Social-media solicitation
8. Unrealistic profit claims
9. Referral/recruitment pressure
10. Suspicious links

The system combines detected indicators into an overall risk score.

### Risk Levels

| Score | Level |
|------:|-------|
| 0–29 | LOWER RISK |
| 30–59 | CAUTION |
| 60–100 | HIGH RISK |

The result is designed to help users **pause and verify**, not to make investment decisions for them.

---

## ✨ Key Features

### 🔍 Message Analyzer
Analyze SMS, WhatsApp messages, emails, social-media posts, and investment offers.

### 🚨 Risk Detection
Identifies common warning signs associated with suspicious financial communications.

### 📊 Safety Dashboard
Displays total analyses and risk distribution.

### 📜 Analysis History
Stores recent analyses locally in the browser.

### 📄 Safety Report
Allows users to download an analysis report.

### 🛡️ Investor Awareness
Provides simple safety guidance such as:

- Never share OTPs or passwords
- Verify information independently
- Don't rush into financial decisions
- Question guaranteed returns
- Keep evidence of suspicious communications

---

## 🛠️ Technology Stack

- HTML5
- CSS3
- JavaScript
- Browser LocalStorage
- Explainable rule-based text analysis
- Responsive Web Design

---

## 📂 Project Structure

```text
NiveshRaksha-AI/
│
├── index.html
└── README.md
