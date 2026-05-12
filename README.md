# 🤖 AI Lead Qualifier

Automated lead qualification system built with n8n + Claude AI + Gmail + Google Sheets.

## What it does
- Captures leads from Google Forms automatically
- Scores each lead 1-10 using Claude AI
- Logs score and reason to Google Sheets
- Sends a personalized reply email instantly

## Tools Used
- n8n (workflow automation)
- Claude Haiku API (lead scoring + email writing)
- Google Sheets (lead tracking)
- Gmail API (automated replies)
- Google Forms (lead capture)

## Architecture
Google Form → Google Sheets Trigger → Extract Lead → 
Claude AI Scoring → Parse Response → Log to Sheets + Send Email
