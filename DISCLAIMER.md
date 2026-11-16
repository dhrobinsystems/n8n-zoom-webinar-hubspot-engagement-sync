# ⚠️ Disclaimer & Liability Limitation

**Repository:** `n8n-zoom-webinar-hubspot-engagement-sync`
**Author:** DH Robin (dhRobin Systems)
**Last updated:** November 2026

Use at your own risk. The code, workflows, and scripts in this repository (`n8n-zoom-webinar-hubspot-engagement-sync`) are provided for educational and architectural demonstration purposes.

* **No Liability:** The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. That includes, without limitation, missed, delayed, duplicated or misattributed registrations, attendance and Q&A data, contacts created or updated in error, incorrect engagement scores, marketing or sales actions taken on them, API charges, and any record created or changed in a connected system.

* **No Warranty:** All software, n8n JSON blueprints and JavaScript modules are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement. Zoom report data can arrive late or incomplete. Attendance merging, engagement tiers, thresholds and redaction patterns are illustrative defaults and are not guaranteed to be correct for your webinars.

* **Production Testing Required:** Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, a test Zoom app and a test webinar, with `SANDBOX_MODE=true` and `DRY_RUN=true` enabled, before you connect live Zoom or HubSpot credentials. Treat every engagement score as a signal that a person must review before acting on it.

* **Not a Consent Record:** Registering for or attending a webinar isn't consent to marketing communications. This workflow doesn't change subscription, consent or legal-basis properties, and you must manage those according to your own policies and applicable law.

* **Third-Party APIs & Compliance:** You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA and others), recording, monitoring and consent rules, and security policies of Zoom, HubSpot, Slack and any connected services. That includes telling registrants and attendees how their registration, attendance and Q&A data is collected and used, confirming a lawful basis for storing it in your CRM, honouring deletion and objection requests, keeping question text and personal data out of logs, restricting access to n8n executions, and reviewing every automatically created or updated record.

* **No Affiliation:** This project is independent. It is not affiliated with, endorsed by, or sponsored by Zoom Communications, Inc., HubSpot, Inc., Slack Technologies, LLC, Salesforce, Inc., or n8n GmbH. All product names and trademarks belong to their respective owners and are used only to describe compatibility.

* **Fictional Sample Data:** All attendee names, e-mail addresses and domains (under the reserved `.example` suffix), webinar and registrant IDs, UUIDs, questions, join links, record IDs, tokens and secrets in the pinned sample data and documentation are fictional and exist only for testing. Any resemblance to real people or organisations is coincidental. Placeholder values such as `YOUR_ZOOM_WEBHOOK_SECRET_TOKEN`, `YOUR_ZOOM_ACCOUNT_ID`, `YOUR_ZOOM_CLIENT_ID`, `YOUR_ZOOM_CLIENT_SECRET`, `YOUR_HUBSPOT_PRIVATE_APP_TOKEN`, `YOUR_HUBSPOT_PORTAL_ID` and `YOUR_SLACK_WEBHOOK_URL` must be replaced with your own values, which you keep in environment variables or n8n credentials.

* **Not Professional Advice:** Nothing in this repository is legal, privacy or compliance advice. Consult qualified professionals for decisions in those areas.

## Open-Source License Notice

This project is released under the MIT License. You may use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the conditions in [LICENSE](./LICENSE). The MIT License's own warranty disclaimer and limitation of liability apply in addition to this document. If the two conflict, the terms more protective of the author apply to the extent permitted by law.

---

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 DH Robin (dhRobin Systems) · Provided as-is, see the disclaimer.
