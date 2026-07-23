# AI Customer Support Manager

An automated customer support workflow built with n8n that retrieves new tickets from Airtable, sends email notifications via Gmail, and automatically updates the ticket status after successful delivery.

## Features

- 📅 Daily scheduled automation
- 📋 Retrieves new tickets from Airtable
- 📧 Sends email notifications using Gmail API (OAuth2)
- ✅ Updates ticket status automatically
- 🔄 Prevents duplicate email notifications

## Tech Stack

- n8n
- Airtable
- Gmail API
- OAuth2
- Workflow Automation

---

## Workflow

<img width="1440" height="786" alt="Worfklow" src="https://github.com/user-attachments/assets/5d495071-2d7b-4313-b135-16c23f86e3cf" />


---

## Airtable Database

<img width="1440" height="786" alt="Airtable" src="https://github.com/user-attachments/assets/bf788b3a-1667-4c7e-8d0d-20ed36a05971" />


---

## Workflow Process

1. Schedule Trigger runs every day at 8:00 AM.
2. Search Airtable for unsent tickets.
3. Check if new tickets exist.
4. Send email through Gmail.
5. Update Airtable record as "Reply Sent".

## Author

Rodron Camangyan
