# Receptionist OS — Prototype v0.1

A mobile-friendly static prototype for a small-business receptionist workflow.

## Features
- Overview dashboard
- Add, update and delete enquiries
- Add, update and delete bookings
- Template-based customer reply drafts
- Simple reports and JSON export
- Browser `localStorage` persistence on the same device/browser
- Responsive layout for phones and desktops

## Run locally
Open `index.html` in a browser. No build tools or package installation required.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `receptionist-os`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for the Pages URL to appear in that settings section.

## Important limitations
This is a prototype, not a production SaaS:
- Reply drafting uses a local template, not a connected AI model.
- No automatic WhatsApp messages, voice calls, email sending, login, cloud sync or payment system.
- Data is stored only in the browser on the device. Clearing browser data may delete it.
- Do not enter sensitive personal data. A production version needs secure authentication, a server/database, privacy safeguards, backups, and tested integrations.
- Before taking payments or signing customer agreements, involve a trusted adult if you are under 18.

## Next build steps
1. Validate the workflow with a few business owners using fictional/demo data.
2. Add a real backend and authentication.
3. Connect an AI provider securely through a server-side API (never expose API keys in browser code).
4. Add official WhatsApp/telephony integrations only after checking provider terms and costs.
