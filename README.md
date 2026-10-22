# AI-Customer-Support-Triage-Bot
An AI-powered Customer Support Triage Bot. The agent classifies customer feedback by category and urgency, logs each submission in a Google Sheets tracker, sends automated acknowledgement emails. This project demonstrates AI agent development, workflow automation, customer support triage, and automated notification systems.

# AI Customer Support Triage Bot

## Project Overview

An AI-powered Customer Support Triage Bot built using n8n and OpenAI. The agent classifies customer feedback by category and urgency, logs each submission in a Google Sheets tracker, sends automated acknowledgement emails, and escalates high-priority issues to the support team.

This project demonstrates AI agent development, workflow automation, customer support triage, and automated notification systems.

## Objectives

- Automatically classify incoming customer feedback.
- Identify the category and urgency of each message.
- Record customer feedback in Google Sheets.
- Send acknowledgement emails to customers through Gmail.
- Escalate high-priority issues to the support team.
- Reduce manual effort in customer support operations.

## Technology Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow automation and AI agent orchestration |
| OpenAI GPT-4.1-mini | Customer feedback classification and analysis |
| Google Sheets | Customer feedback tracking and logging |
| Gmail | Customer acknowledgement and escalation notifications |

## How It Works

1. **Receive feedback:** The customer submits a feedback message through the n8n chat panel.
2. **Analyse feedback:** The AI agent interprets the message and identifies its category and urgency.
3. **Record the submission:** The feedback details are added to the Customer Feedback Tracker in Google Sheets.
4. **Acknowledge the customer:** An automated email confirms that the feedback has been received.
5. **Escalate urgent issues:** High-priority issues are forwarded to the designated support team for further action.

## Test Scenarios

The workflow is designed to be tested with three customer feedback scenarios.

| Customer | Feedback type | Expected urgency |
|---|---|---|
| Priya | Bug report | High |
| Rohan | Feature request | Low |
| Anjali | Question | Low |

*Note: These are the intended test scenarios. Actual classifications and workflow results should be verified during testing.*

## Prerequisites

Before running the workflow, you will need:

- An n8n instance with access to the workflow editor and chat panel.
- An OpenAI API key with access to the selected model.
- A Google account with Google Sheets access.
- A Gmail account for testing email notifications.
- A Google Sheet named `Customer Feedback Tracker`.
- The necessary credentials and permissions configured in n8n.

## Setup Instructions

1. Clone or download this repository.
2. Open your n8n instance.
3. Import `ai-customer-support-triage-bot.json` into n8n.
4. Configure your OpenAI credentials.
5. Connect your Google Sheets account and select the `Customer Feedback Tracker` spreadsheet.
6. Configure your Gmail credentials and the appropriate recipient addresses.
7. Verify the workflow nodes, field mappings, and escalation conditions.
8. Save the workflow and test it using the n8n chat panel.

**Security:** Never commit API keys, passwords, OAuth tokens, or exported credentials to a public repository. Configure credentials securely within n8n.

## Expected Outcome

The completed workflow should demonstrate an automated customer support process that classifies feedback, records submissions, acknowledges customers, and escalates urgent issues according to the configured rules.

## Project Structure

```text
ai-customer-support-triage-bot/
├── ai-customer-support-triage-bot.json
├── README.md
└── screenshots/
    └── workflow-overview.png
```

The screenshot is optional. Add it after capturing your actual n8n workflow.

## Learning Outcomes

- Building AI-powered workflows using n8n.
- Integrating OpenAI models into automation pipelines.
- Connecting Google Sheets and Gmail.
- Implementing feedback classification and urgency-based routing.
- Designing automated acknowledgement and escalation processes.
- Handling credentials and workflow configuration securely.

## Project Information

**Programme:** AI Generalist Accelerator Programme

**Track:** AI Automations and Agents

**Use
