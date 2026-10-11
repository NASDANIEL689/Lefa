# Lefa — Animated UI prototype

A responsive, interactive front-end concept for Lefa, a community-controlled traditional ecological knowledge platform. Built as a dependency-free HTML/CSS/JavaScript prototype for a hackathon demo.

## Run locally

1. Download and unzip the project.
2. Open `index.html` in a current browser (Chrome, Safari, Firefox, or Edge).
3. No package installation, build step, or internet connection is required.

For a local development server, open a terminal in this folder and run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Interactions included

- Responsive dashboard and collapsible mobile navigation
- Knowledge registry with search, category/status/access filters, record details, and CSV export
- New-record form with a selected local file indicator (no file upload)
- Simulated verification/restriction queue actions
- Potential knowledge-match alerts and review flow
- Community access-policy cards
- Settings toggles, toast notifications, sync demo, chart time range
- Motion-reduction support and keyboard-dismissable modals

## Important prototype limits

This is a **front-end demo using synthetic/sample data**. It does not save data after a page reload, authenticate users, securely upload media, perform real cryptographic timestamping, synchronize offline records, enforce access controls on a server, or run real AI matching. Buttons labelled as demo/simulated should not be presented as production security guarantees.

Before using real traditional knowledge, connect a secure API and database; implement authentication, authorization and audit logging; encrypt local and server-side data; design consent/revocation and community governance processes; protect sensitive coordinates and restricted knowledge; validate data handling with the relevant communities; and obtain legal/IP advice. A hash or timestamp supports integrity/provenance evidence but does not alone establish legal ownership or prove misuse.
