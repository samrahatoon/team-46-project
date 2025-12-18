Automated Lead Management System (n8n)
Overview

This repository contains an Automated Lead Management System built using n8n.
The system captures leads from a website, processes them automatically, stores them in Google Sheets, and provides instant feedback to the user.

The solution is designed for business owners and non-technical users who want to automate lead handling without manual effort.

Business Problem

Many businesses lose potential customers due to:

Delayed response to website inquiries

Manual data entry

No structured lead tracking

Inconsistent follow-ups

This automation solves these problems by ensuring instant processing, structured storage, and reliable execution.

Solution Summary

Website sends lead data via webhook

n8n processes and structures the lead

Lead data is stored in Google Sheets

System responds back to the website

Workflow runs automatically without human intervention

Technology Stack

Automation Platform: n8n (self-hosted or cloud)

Frontend UI: Lovable (Dummy UI for demo)

Database: Google Sheets

Integration Method: Webhooks

Demo Assets: Screen recording + AI voice-over

Workflow Diagram

The workflow follows this structure:

Webhook (Lead Intake)

Data Processing

Lead Scoring Logic

Data Storage (Google Sheets)

Webhook Response to UI

n8n Workflow

👉 Workflow URL:
PASTE YOUR n8n WORKFLOW URL HERE

This workflow can be imported directly into any n8n instance.

Demo Video

🎥 Demo Video URL:
PASTE YOUR DEMO VIDEO LINK HERE

The video demonstrates:

Business problem explanation

Website UI interaction

Live workflow execution in n8n

Different lead processing outcomes

Final business value

How to Import the Workflow (Beginner Friendly)

Open your n8n dashboard

Click Workflows

Select Import from URL or File

Paste the workflow URL

Click Import

Save the workflow

Required Credentials Setup
Google Sheets

Add Google account credentials

Select the target spreadsheet

Ensure edit permissions are enabled

Webhook

Copy webhook URL from n8n

Paste it into the website form submission action

How to Activate

Open the imported workflow

Click Activate

Submit a test lead from the website

Verify:

Data appears in Google Sheets

Response is returned to the UI

Target Users

Small to medium businesses

Agencies

Service providers

Course evaluators

Non-technical clients

Team Members

Project Lead & Automation: Samra Mukhtar

UI Design: Asif Minhas

Workflow Support & Testing: Sami Khan

Project Status

✅ Completed
✅ Tested
✅ Ready for deployment

Future Enhancements (Optional)

CRM integration

Email or WhatsApp notifications

Advanced lead scoring

Analytics dashboard

License

This project is created for educational and demonstration purposes.
