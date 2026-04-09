**Project Overview**

This project focuses on **Detecting Credential Stuffing & Account Takeover Attacks** using machine learning techniques applied to authentication logs.
Credential stuffing is a cyberattack where attackers use leaked username-password pairs to gain unauthorized access to user accounts. Traditional rule-based systems (e.g., login attempt thresholds) are no longer effective due to evolving attacker strategies.
This project builds an **adaptive ML-based detection system** to identify suspicious login behavior and generate risk-based alerts.

**Problem Statement**

Modern web applications face increasing threats from:
Credential stuffing attacks
Account takeover (ATO) incidents
Static defenses such as IP blocking or login rate limits fail because attackers:
Distribute attempts across multiple IPs
Mimic normal user behavior
Reduce login frequency
Therefore, there is a need for intelligent systems that learn patterns from authentication logs and detect anomalies in real time.

**Proposed Solution**

We design a machine learning pipeline that:
Processes authentication logs
Extracts behavioral features
Trains multiple ML models
Assigns a risk score to login events
Triggers alerts when suspicious activity is detected

**Key Features Used**

Failed login bursts
Unique usernames per IP
Login success/failure patterns
Sudden behavioral changes
Time-window based activity trends

