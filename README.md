# 🚀 AI Resume Analyzer using n8n

An AI-powered Resume Analyzer workflow built with n8n, OpenAI, Google Sheets, and AI automation.

## 📌 Project Overview

This project automatically analyzes a candidate's CV against a specific Job Description using AI.

After analyzing the resume, it generates:

- ATS Score
- Matching Skills
- Missing Skills
- Weak Areas
- Professional Recommendation
- Improvement Suggestions
- Priority Actions

The analysis is then automatically structured and stored in Google Sheets.

## ✨ Features

🤖 AI-powered CV analysis  
📄 CV upload and processing  
💼 Job Description analysis  
📊 ATS Score generation  
✅ Matching skills detection  
❌ Missing skills identification  
⚠️ Weak area detection  
💡 AI-generated recommendations  
📈 Improvement suggestions  
🎯 Priority actions  
📊 Google Sheets integration  
🧹 Clean structured text output  
🎨 HTML email template  

## 🛠 Tech Stack

- n8n
- OpenAI
- Google Sheets
- HTML
- AI Automation
- Web Form

## 🔄 Workflow

CV Upload + Job Description
        ↓
CV Text Extraction
        ↓
OpenAI Resume Analysis
        ↓
Structured AI Output
        ↓
Edit Fields
        ↓
Google Sheets

## 📊 AI Analysis Output

The system generates:

### ATS Score
Provides an overall compatibility score between the CV and Job Description.

### Matching Skills
Identifies skills present in both the CV and Job Description.

### Missing Skills
Highlights important skills required by the job but missing from the CV.

### Weak Areas
Identifies areas where the candidate's resume can be improved.

### Recommendation
Provides an overall professional assessment of the CV.

### Improvement Suggestions
Provides actionable suggestions for improving the resume.

### Priority Actions
Highlights the most important actions the candidate should take.

## 📂 Folder Structure

AI-Resume-Analyzer-n8n
│
├── workflow/
│   └── workflow.json
│
├── prompts/
│   └── resume-analyzer-prompt.txt
│
├── screenshots/
│   ├── form.png
│   ├── workflow.png
│   ├── ai-output.png
│   └── google-sheets.png
│
├── docs/
│   └── project-overview.md
│
└── README.md

## ⚙️ How It Works

1. User uploads their CV.
2. User provides a Job Description.
3. The workflow extracts the CV content.
4. OpenAI analyzes the CV against the Job Description.
5. AI generates a structured resume evaluation.
6. n8n processes and formats the AI response.
7. The final analysis is stored in Google Sheets.

## 🔐 Security

API keys, credentials, passwords, tokens, and other sensitive information should never be uploaded to GitHub.

## 🚀 Future Improvements

- ATS Status Classification
- Automatic Email Delivery
- Detailed ATS Score Breakdown
- AI-powered Improvement Plan
- Multiple Job Description Analysis
- Resume Analysis Dashboard
- PDF Report Generation
- Resume Optimization Suggestions

## 👨‍💻 Author

**Junaid Zulfiqar**


## ⭐ Project Status

🟢 Day-2 Project Completed
