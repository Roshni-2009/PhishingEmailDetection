# Phishing Email Detection System

A Python Flask-based web application that analyzes email content and identifies potential phishing indicators using rule-based detection.

## Overview

Phishing is a type of cyberattack in which attackers use fraudulent emails to steal sensitive information. This project helps identify suspicious emails by analyzing sender addresses, subject lines, message content, and embedded URLs.

## Features

- Email sender address validation
- Suspicious keyword detection
- Detection of possible brand impersonation
- URL analysis
- Identification of unencrypted HTTP links
- Phishing risk score calculation
- Low, Medium, and High risk classification
- Simple web interface using Flask

## Technologies Used

- Python
- Flask
- HTML
- CSS
- Regular Expressions

## Project Structure

```text
PhishingEmailDetection/
│
├── app.py
├── detector.py
├── requirements.txt
├── README.md
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Roshni-2009/PhishingEmailDetection.git
```

### 2. Open the project folder

```bash
cd PhishingEmailDetection
```

### 3. Install dependencies

```bash
py -m pip install -r requirements.txt
```

### 4. Run the application

```bash
py app.py
```

### 5. Open in your browser

Visit:

```text
http://127.0.0.1:5000
```

## Sample Test

**Sender:** security@gmail.com

**Subject:** Urgent! Verify your account

**Email Body:** Your account will be suspended. Click here to verify your password immediately.

The application analyzes the provided information and displays a risk score, classification, and detected suspicious indicators.

## How It Works

1. The user enters the sender address, subject, and email body.
2. The application validates the sender address.
3. It checks for suspicious keywords and possible brand impersonation.
4. It extracts and analyzes URLs.
5. It calculates a risk score based on detected indicators.
6. It displays the final risk classification.

## Limitations

- This is a basic rule-based educational project.
- It does not use machine learning or deep learning.
- It cannot guarantee that an email is safe.
- Its results depend on the detection rules implemented in the application.

## Disclaimer

This project is developed for educational purposes and cybersecurity awareness. It should not be used as the sole method of determining whether an email is safe.

## Author

**Roshni Mukherjee**

GitHub: [Roshni-2009](https://github.com/Roshni-2009)