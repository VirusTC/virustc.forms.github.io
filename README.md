# Virus Treatment Centers [VirusTC] Forms Portal

Welcome to the official, secure forms repository for **VirusTC**. This site serves as a clean, highly accessible, and trustworthy hub for hosting patient intake, consent, and administrative medical forms.

**Live Portal:** [https://github.io](https://github.io)

---

## Available Forms

The portal currently links to and manages the following active healthcare workflows:

*   **`patient-intake-form`**: Digital entry portal for new clinical patients. Securely captures medical history, insurance validation data, and initial entry demographics.
*   **`telehealth-consent-release`**: Dedicated signature release module required for scheduling or attending remote patient care/video sessions.
*   **`rx-refill-request`**: Expedited routing matrix allowing existing patients to submit automated renewal requests directly to their assigned medical provider.

---

## Architecture & Core Components

This repository is built using pure, structural code for maximum speed, security, and uptime:

*   **Design Framework:** Styled using GitHub's official open-source design language (**Primer CSS**) to maintain a clean, recognizable layout.
*   **Iconography:** Utilizes native **Primer Octicons** for clear structural navigation visual anchors.
*   **Accessibility Compliance:** Configured to target WCAG 2.1 contrast rules, fluid typography sizing, and strict semantic HTML `<label>` tagging to ensure universal patient access.

---

## How to Add or Modify Forms

To add a new form link or update an existing text box on the central hub page:

1.  Open the `index.html` file in the root of this repository.
2.  Locate the `<div class="forms-grid">` structural block.
3.  Duplicate an existing form layout block (`<div class="form-card">...</div>`).
4.  Update the path in the `href` attribute to target your specific form location.
5.  Commit your updates to the `main` branch. GitHub Actions will auto-deploy the live edits within 60 seconds.

---

## Security & Privacy Notice

> [!WARNING]
> **Data Privacy Compliance:** This static frontend acts strictly as a visual router/index. Ensure that any backend scripts, embedded third-party endpoints (e.g., Typeform, Google Forms), or external webhooks used to parse these inputs maintain full end-to-end data encryption and strict HIPAA/GDPR regulatory processing compliance. Never log or store raw protected health information (PHI) directly inside static code files.
