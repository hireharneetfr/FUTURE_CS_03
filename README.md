# API Security Risk Analysis – Future Interns Cyber Security Task 3

## Overview

This repository contains my submission for **Future Interns – Cyber Security Task 3 (2026)**.

The objective of this project was to perform a **read-only API Security Risk Analysis** on a public REST API while following ethical security testing practices. The assessment focused on identifying common API security risks, analysing API behaviour, evaluating HTTP requests and responses, and providing practical remediation recommendations.

The selected API for this assessment is:

**JSONPlaceholder**
https://jsonplaceholder.typicode.com

JSONPlaceholder is a free REST API designed for testing and learning purposes. Since it intentionally exposes public endpoints, it provides an ideal environment for analysing API security concepts without affecting production systems.

---

## Project Objectives

- Perform a read-only API security assessment.
- Analyse publicly accessible API endpoints.
- Evaluate authentication and access control.
- Inspect HTTP request and response headers.
- Identify common API security risks.
- Assess risk severity and business impact.
- Recommend security best practices.

---

## Scope

The assessment was limited to passive security testing of the publicly available JSONPlaceholder API.

The following activities were included:

- Reviewing API documentation
- Testing GET and safe POST requests
- Inspecting HTTP request headers
- Inspecting HTTP response headers
- Analysing response bodies
- Observing API behaviour
- Reviewing network timing information

The following activities were **not** performed:

- Exploitation attempts
- Authentication bypass
- Brute-force attacks
- SQL Injection
- Denial-of-Service testing
- Modification of production systems
- Testing private APIs

All testing was performed within ethical and legal boundaries.

---

## Methodology

A structured read-only testing methodology was followed throughout the assessment.

1. Reviewed the official API documentation.
2. Selected publicly accessible API endpoints.
3. Sent requests using Postman and Insomnia.
4. Inspected requests and responses using Chrome Developer Tools.
5. Analysed authentication requirements.
6. Reviewed response headers and request headers.
7. Examined returned JSON data.
8. Identified potential API security risks.
9. Classified findings based on risk severity.
10. Proposed remediation recommendations using industry best practices.

---

## Tools Used

- Postman
- Insomnia
- Google Chrome Developer Tools
- JSONPlaceholder REST API
- Microsoft Word
- GitHub

---

## API Tested

**API Name:** JSONPlaceholder

**Base URL**

https://jsonplaceholder.typicode.com

---

## Security Areas Analysed

- Authentication
- Access Control
- Information Disclosure
- Response Headers
- Request Headers
- Response Body
- Error Handling
- API Responses
- Network Timing
- HTTP Status Codes

---

## Key Findings

The assessment identified several observations relating to API security, including:

- Public API endpoints accessible without authentication
- Excessive data exposure through API responses
- Controlled handling of invalid resource requests
- Simulated resource creation using POST requests
- Public access to multiple API resources
- Standard HTTP request and response header configuration
- Structured JSON responses
- Stable API response timing

---

## Disclaimer

This assessment was conducted solely for educational purposes as part of the Future Interns Cyber Security Internship.

The API selected for analysis (JSONPlaceholder) is intentionally designed as a public testing platform. No exploitation, unauthorised access, or malicious activity was performed during this assessment.

---

## Author

**Harneet Kour**

BSc Cyber Security Student

Future Interns – Cyber Security Internship (2026)
