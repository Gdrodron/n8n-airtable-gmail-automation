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

![Workflow](<img width="1440" height="786" alt="n8n Workflow Airtable Ticket Notif" src="https://github.com/user-attachments/assets/81191905-5e77-4288-8047-f4ada2ecd797" />
)

---

## Airtable Database

![Airtable](<img width="1440" height="786" alt="Airtable Ai Customer Support Manager" src="https://github.com/user-attachments/assets/fefb9a93-72aa-4961-9765-a8cbdb8d7bde" />
)

---

## Workflow Process

1. Schedule Trigger runs every day at 8:00 AM.
2. Search Airtable for unsent tickets.
3. Check if new tickets exist.
4. Send email through Gmail.
5. Update Airtable record as "Reply Sent".

## Author

Rodron Camangyan
