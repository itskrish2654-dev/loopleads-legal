# LoopLeads legal pages

Public legal pages for the current LoopLeads Instagram automation application:

- Privacy Policy: https://itskrish2654-dev.github.io/loopleads-legal/
- Data Deletion Instructions: https://itskrish2654-dev.github.io/loopleads-legal/data-deletion.html
- Terms of Service: https://itskrish2654-dev.github.io/loopleads-legal/terms.html

Last revised: 29 October 2026.

## Product scope covered

These pages describe the current multi-account early-access application, not the original single-account SQLite coaching pilot. LoopLeads uses authorized Instagram APIs and webhooks, PostgreSQL on cloud infrastructure, connected-account access tokens, comment and message records, optional lead collection, and account-level data export/deletion controls.

## Publishing via GitHub Pages

Host the three HTML files at the root of the public `loopleads-legal` repository on the `main` branch. In Settings > Pages, use the `main` branch and `/(root)` folder. GitHub Pages publishes the static HTML; no server secrets, backend source, access tokens, customer data, or `.env` files belong in this repository.

## Before Meta App Review or public launch

1. Confirm the public contact email `itskrish2654@gmail.com` is monitored and is the address you wish to use publicly.
2. Confirm the operator's correct legal identity/contact particulars with a legal professional; the current pages identify the product as LoopLeads operated from India without inventing a registered company.
3. Verify production deletion/retention and backups are consistent with the descriptions, including any changes made after V3.4.0.
4. Verify the app's Privacy and Data Deletion links point to the final public URLs; set the Terms URL in Meta where available.
5. Visit all three URLs in an incognito window and on a phone, and verify internal links.
6. Have a qualified privacy/legal advisor review these pages for the countries and customer groups you will serve. Publishing these documents alone does not establish regulatory compliance.

## Product-code accuracy notes (V3.4.0)

- Contact-level deletion and account disconnect exist in the app.
- Account-owner exports are available as JSON.
- Captured lead email and phone data and Instagram access tokens are encrypted in the application database.
- Successful webhook processing clears original raw payload from completed events; maintenance removes completed event rows older than about 30 days.
- Leads/messages do not have an automatic universal expiry.
- There is no complete self-service deletion button for a LoopLeads login account. Use support requests for those cases.
- Backup-specific expiry periods have not been verified; do not promise exact backup erasure dates.
- Paid subscription/checkout was not confirmed in the V3.4.0 package.

These pages are editorial legal drafts, not professional legal advice.
