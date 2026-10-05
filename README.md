# Freelancer Project Automation

AI-powered n8n automation for finding, scoring, and preparing proposals for Freelancer.com projects.

## 🚀 Features

- Reads Freelancer project notification emails
- Extracts multiple projects from a single email
- Uses AI to evaluate project-skill compatibility
- Generates a match score
- Filters projects based on a configurable score threshold
- Generates customized proposals
- Detects duplicate projects using the Freelancer URL
- Stores projects and proposals in Google Sheets
- Sends notifications for new matching projects

## 🛠️ Tech Stack

- n8n
- OpenAI
- Gmail
- Google Sheets
- JavaScript
- JSON

## 🔄 Workflow

Gmail
→ Project Parser
→ AI Matching
→ Score Filter
→ AI Proposal Generator
→ Duplicate Detection
→ Google Sheets
→ Notification

## 📊 Matching

The system evaluates projects against the combined skills of the available developers and assigns a match score.

The current testing threshold is 60%.

## ⚠️ Disclaimer

This project is designed to assist with project discovery and proposal preparation. Final project selection and submission should be reviewed manually.

## 📸 Workflow Preview

Add screenshots of the n8n workflow here.

## 👨‍💻 Author

Alok Kumar
