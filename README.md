# AI-Lead-Generation-Automation

An AI-powered lead generation workflow built using n8n, Tally, Airtable, OpenAI, and Gmail.

## Project overview:

The project described herein aims at automating the way incoming inquiries for participation in training programs are collected, organized, and analyzed. By using an artificial intelligence mechanism, incoming inquiries for participation in training programs are automatically assessed for relevance.

## Technologies utilized:

- **Tally** - Gathers requests via an online questionnaire.
- **n8n** - Links and automates the process in the workflow.
- **Airtable** - Keeps and organizes information on leads.
- **OpenAI** - Sorts requests, assigns priority levels, and creates summaries.
- **Gmail** - Sends automatic alerts.

## Operation of the Process Step by Step

1. The potential client fills in the Tally form.
2. The n8n system receives the submission.
3. The system checks whether the email is correct.
4. The information about the lead goes to Airtable.
5. The inquiry will be analyzed by OpenAI and classified and summarized.
6. Airtable is updated.
7. Gmail sends an email with the information regarding the lead.

## Characteristics of the Process

- Automated lead generation.
- Email verification.
- Using Airtable database.
- Automatic inquiry categorization.
- Prioritization of inquiries.
- Inquiry summaries created by AI.
- Automated sending of emails.

## Testing of the Process

The testing was held with the help of inquiry submission in the training seminar.

The inquiry process proved that the system can store the information in Airtable.

## Project Files

Tally AI Lead Generation.json – n8n workflow configuration exported.

## Safety of the Project

API credentials are kept in n8n connection so no need to include them in an exported workflow.

## Future Improvements of the Project

- Automated sending of follow-up emails.
- Lead scoring.
- Establishing connection with CRM.
- Dashboard for reporting.

## Current Status of the Project

The main process has been tested successfully.
