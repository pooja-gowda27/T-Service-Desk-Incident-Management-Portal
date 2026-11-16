# IT Service Desk & Incident Management Portal

A responsive, browser-based service desk MVP for demonstrating the workflow of a Junior Service Desk Analyst: incident intake, triage, troubleshooting documentation, escalation, resolution, knowledge sharing, and operational reporting. No backend or external service integrations are required.

## Features

- Dashboard KPIs, category/status charts, recent incidents, and recurring issue insights.
- Validated ticket intake with generated `INC-####` identifiers and success feedback.
- Searchable ticket register with status/priority filters and status badges.
- Ticket details with troubleshooting, root cause, resolution, follow-up, and timestamped status history.
- Start troubleshooting, resolve, escalate to specialist teams, and close tickets.
- Escalation handoff captures reason, team, priority, and analyst notes.
- Five searchable knowledge articles covering Wi-Fi, access, Outlook/application, slow computer, and password issues.
- Reports for incident totals, resolved, escalated and high-priority volume, category/status distribution, and recurring issue suggestions.
- `localStorage` persistence and a Settings action to restore sample data.
- Desktop and mobile responsive layout.

## Tech stack

React 19, JavaScript, Vite, CSS, browser `localStorage`.

## Screenshots

_Add screenshots of the Dashboard, Ticket Details, and Reports here._

## Run locally

Requirements: Node.js 20.19+ or 22.12+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. Production build: `npm run build`. Preview: `npm run preview`.

## Project structure

```text
.
├── index.html
├── package.json
├── README.md
└── src
    ├── App.jsx       # Portal, sample data, workflow, and UI components
    ├── App.css       # Layout and responsive styling
    ├── index.css     # Global reset and focus styles
    └── main.jsx      # React entry point
```

## Data and privacy

Ticket changes are stored only in the current browser profile and are not sent to a server. Sample employee addresses use the reserved `.example` domain. Do not enter real credentials or sensitive personal information.

## Future enhancements

- Add unit and end-to-end tests for ticket workflows.
- Add role-based access, a secure API, and a database.
- Add configurable service-level targets, aging views, and exportable reports.
- Add article feedback and direct knowledge-base suggestions from ticket categories.
- Add audit logs and further keyboard accessibility improvements.
