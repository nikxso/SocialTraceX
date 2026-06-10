# SocialTraceX
 ## Web-Based Social Media Forensic Investigation System
A real-time forensic evidence acquisition and analysis platform designed to assist investigators in collecting, organizing, and reporting social media evidence through browser automation.

## Overview

The Web-Based Social Media Forensic Investigation System automates the process of collecting publicly accessible social media evidence and organizing it into structured investigation cases.

The platform integrates browser automation, evidence management, real-time updates, and report generation into a unified investigation workflow.

# Technology Stack

## Backend

- FastAPI
    
- SQLAlchemy
    
- SQLite
    
- WebSockets
    
- Pydantic
    

## Automation

- Playwright
    
- Chromium Browser
    
- Chrome DevTools Protocol (CDP)
    

## Frontend

- HTML
    
- CSS
    
- JavaScript
    

## Reporting

- HTML Report Templates
    
- PDF Export Support
    

---

# Project Structure

```text
project-root/
│
├── main.py
├── scraper.py
├── auth.py
├── database.py
├── requirements.txt
│
├── templates/ 
|   ├── admin.html
|   ├── base.html
│   ├── dashboard.html
│   ├── case_detail.html
|   ├── login.html
│   └── report.html
│
├── static/
│   ├── css/
│   └── js/
│
├── screenshots/
│
├── database/
│
└── README.md
```

---
# Installation

## Prerequisites

- Python 3.10+

# Clone Repository

```bash
git clone https://github.com/nikxso/SocialTraceX.git
```

```bash
cd SocialTraceX
```
---

# Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Install Playwright Browsers

```bash
playwright install
```

---

Start backend:

```bash
python app.py
```

# Current Limitations

- Platform-specific extraction logic
    
- Browser automation dependency
    
- Dynamic UI changes on social media platforms
    
- Limited advanced analytics
    
- Desktop-oriented workflow
    

---

# Future Enhancements

- Multi-platform investigations
    
- AI-assisted analysis
    
- Sentiment analysis
    
- Mobile support
    
- Enhanced analytics dashboard
    
- Advanced evidence correlation
    

---

# Security Notice

This project is intended for:

- Academic research
    
- Educational purposes
    
- Digital investigation workflow demonstrations
    

Users are responsible for complying with applicable laws, platform policies, and privacy regulations.
