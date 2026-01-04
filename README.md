#n8n Lead Classification Workflow (Airtable CRM)

## Overview
This repository contains an n8n workflow that automatically processes incoming emails, classifies them as leads, and stores qualified lead information into an Airtable-based CRM. The workflow is designed to reduce manual effort in lead management and ensure structured data storage.

## Use Case
- Monitor incoming business emails
- Identify valid leads based on content
- Extract relevant lead details
- Store structured lead data into Airtable for CRM usage

## Tools & Technologies
- n8n (workflow automation)
- Gmail Trigger
- IF / Switch nodes for lead classification logic
- Airtable (used as the CRM)

## Workflow 
<img width="1687" height="330" alt="image" src="https://github.com/user-attachments/assets/e5145398-9c8a-47bd-940e-50e632b1a834" />



Field names can be adjusted in the Airtable node mapping inside n8n.

## How to Use
1. Clone or download this repository
2. Open your n8n instance
3. Import the workflow JSON file
4. Configure the following credentials in n8n:
   - Gmail account
   - Airtable API key and Base ID
5. Map the email fields to Airtable fields as required
6. Activate the workflow

## Security Notes
- No credentials, API keys, or tokens are included in this repository
- All sensitive information must be configured inside n8n credentials

## Status
This workflow is functional and intended for demonstration, learning, and portfolio purposes.

## Author
Built as part of an automation and workflow engineering  using n8n and Airtable
