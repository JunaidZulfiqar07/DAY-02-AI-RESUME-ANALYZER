🚀 AI Resume Analyzer using n8n

An AI-powered Resume Analyzer built with n8n, OpenAI, Gmail, and Google Sheets.


📌 Project Overview

This project automatically analyzes a candidate's CV against a specific Job Description using AI.


The user provides:



📄 CV / Resume

💼 Job Description

📧 Email Address


The workflow analyzes the CV, generates a detailed resume evaluation, stores the results in Google Sheets, and sends a professional HTML-formatted report through Gmail.


✨ Features


📄 CV / Resume Upload

💼 Job Description Input

📧 Email Collection

🤖 AI-powered Resume Analysis

📊 ATS Score

✅ Matching Skills

❌ Missing Skills

⚠️ Weak Areas

💡 AI Recommendation

📈 Improvement Suggestions

🎯 Priority Actions

📊 Google Sheets Integration

🧹 Clean Text Output

📧 Professional HTML Resume Report

📬 Gmail Integration

⚡ Automated n8n Workflow


🛠️ Tech Stack


n8n

OpenAI

Gmail

Google Sheets

HTML

JSON

AI Automation


🔄 Workflow

CV + Job Description + Email
              ↓
       CV Text Extraction
              ↓
        OpenAI Analysis
              ↓
      Structured AI Output
              ↓
          Edit Fields
              ↓
       Google Sheets
              ↓
    HTML Resume Report
              ↓
            Gmail
              ↓
     Candidate Receives Report

📊 AI Analysis Output

The system generates the following results:


📊 ATS Score

Provides an overall compatibility score between the candidate's CV and the Job Description.


✅ Matching Skills

Identifies skills and technologies present in the CV that match the requirements of the Job Description.


❌ Missing Skills

Highlights important skills required by the Job Description that are missing from the candidate's CV.


⚠️ Weak Areas

Identifies areas of the resume that could be improved to better match the target position.


💡 Recommendation

Provides an overall professional assessment of the candidate's resume.


📈 Improvement Suggestions

Provides actionable suggestions to improve the resume and increase its relevance to the target job.


🎯 Priority Actions

Highlights the most important actions the candidate should take to improve their CV.


📧 Professional HTML Resume Report

After completing the AI analysis, the workflow generates a professional HTML-formatted resume analysis report.


The report includes:



📊 ATS Score

✅ Matching Skills

❌ Missing Skills

⚠️ Weak Areas

💡 Recommendation

📈 Improvement Suggestions

🎯 Priority Actions


The report is delivered to the candidate through Gmail in a clean and professional HTML format.


📊 Google Sheets Integration

The workflow automatically stores the resume analysis in Google Sheets.


Field	Description
Email	Candidate email
ATS Score	Resume compatibility score
Matching Skills	Relevant matching skills
Missing Skills	Missing job requirements
Recommendation	Overall AI assessment
Weak Areas	Areas that need improvement
Suggestions	Resume improvement suggestions
Priority Actions	Important next steps

AI array outputs are converted into clean, readable text before being stored in Google Sheets.


⚙️ How It Works


User uploads a CV.

User enters the Job Description.

User provides an email address.

The CV content is processed.

OpenAI analyzes the CV against the Job Description.

n8n processes the structured AI response.

AI results are converted into clean text fields.

The analysis is stored in Google Sheets.

A professional HTML resume report is generated.

The report is sent to the candidate through Gmail.


📂 Folder Structure

DAY-02-AI-RESUME-ANALYZER
│
├── README.md
│
├── workflow/
│   └── workflow.json
│
├── prompts/
│   └── resume-analyzer-prompt.txt
│
├── screenshots/
│   ├── form.PNG
│   ├── workflow.PNG
│   ├── ai-output.PNG
│   ├── google-sheets.PNG
│   └── gmail.PNG
│
└── docs/
    └── project-overview.md

🧪 Testing

The workflow can be tested with different CV and Job Description combinations.


Test Case 1 — Strong Match

A highly relevant CV should generate:



High ATS Score

More Matching Skills

Fewer Missing Skills

Positive Recommendation


Test Case 2 — Weak Match

A less relevant CV should generate:



Lower ATS Score

More Missing Skills

More Weak Areas

Detailed Improvement Suggestions


Test Case 3 — Different Job

Testing the same CV against a different Job Description helps evaluate how the ATS score and skill analysis change according to different job requirements.


🔐 Security

Do not upload sensitive credentials or secrets to GitHub.


Never expose:



❌ OpenAI API Keys

❌ Gmail Credentials

❌ Google Credentials

❌ Passwords

❌ Authentication Tokens

❌ Private Webhook URLs


Use n8n's credential management system for authentication.


🚀 Future Improvements


🎯 ATS Status Classification

📊 Detailed ATS Score Breakdown

🧠 AI-powered Resume Improvement Plan

🔄 Multiple Job Description Analysis

📄 PDF Resume Analysis Report

📊 Interactive Resume Dashboard

✍️ AI Resume Optimization

📝 AI Cover Letter Generator

🌐 Multi-language Resume Analysis


👨‍💻 Author

Junaid Zulfiqar



