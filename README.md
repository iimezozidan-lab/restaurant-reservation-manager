# Restaurant Reservation & Waitlist Manager

Workflow automation built with n8n.

## Features

- Automatic reservation monitoring
- Waitlist management
- Email notification when table is ready
- Reservation status updates
- Notification logging
- PostgreSQL integration

## Tech Stack

- n8n
- PostgreSQL
- SMTP Email
- SQL

## Workflow

Schedule Trigger
→ Read Reservations
→ Check Waiting Status
→ Send Email
→ Update Status
→ Log Notification
