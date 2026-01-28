# AI Lead Scoring & Routing Automation

## Problem
Businesses receive inquiries from multiple sources such as forms, emails, and ads.
Manually reviewing and prioritizing them leads to slow response times and missed opportunities.

## Solution
I built an AI-powered automation that evaluates each incoming inquiry, assigns a priority level, and routes it automatically to the right destination.

High-priority inquiries are flagged instantly, medium ones enter the pipeline, and low-priority ones are organized for follow-up.

## Workflow Overview
1. Inquiry arrives via form or email
2. Data is cleaned and structured
3. AI assigns a priority score based on custom rules
4. Inquiry is routed to CRM, Slack, or email
5. Notifications are triggered for urgent cases

## Tools Used
- n8n
- OpenAI (prompt-based scoring)
- Webhooks
- Google Sheets / CRM
- Slack (notifications)

## Business Impact
- Reduced response time from hours to minutes
- Prevented high-value inquiries from being missed
- Removed manual sorting and spreadsheet work

## Notes
All data used in demos is anonymized or dummy data.
Workflow is modular, documented, and easy to maintain.
