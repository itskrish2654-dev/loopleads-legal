# LoopLeads Legal Pages — GitHub Pages starter kit

## Before publishing — REQUIRED

1. The public customer-support/privacy email is configured in both HTML pages as **itskrish2654@gmail.com**. This address will be visible to anyone on the internet.
2. Read the policies to ensure they accurately describe your actual hosting, retention, support, and deletion process. These pages reflect the October 2026 **single-account local LoopLeads MVP** reviewed for this kit, not a production multi-customer SaaS.
3. Never upload the LoopLeads backend, `.env`, Instagram access token, Meta App Secret, or SQLite user database into this public repository.

## Publish on GitHub Pages for free

1. Sign in to GitHub and create a **public** repository called `loopleads-legal` at https://github.com/new. Create it with a README (or an empty repo).
2. Add the three website files to the **root** of the repository: `index.html`, `data-deletion.html`, and `.nojekyll` (hidden `.nojekyll` is optional).
3. In the repository, open **Settings > Pages**.
4. Under **Build and deployment > Source**, select **Deploy from a branch**.
5. Select branch **main**, folder **/(root)** and click **Save**.
6. Wait for the Pages deployment to complete, then verify both URLs in an incognito browser:
   - Privacy Policy: `https://YOUR_GITHUB_USERNAME.github.io/loopleads-legal/`
   - Data deletion: `https://YOUR_GITHUB_USERNAME.github.io/loopleads-legal/data-deletion.html`
7. In Meta Developers > LoopLeads > App settings > Basic, paste the privacy URL in **Privacy Policy URL** and (if required) data-deletion URL in **User Data Deletion / Data Deletion Instructions URL**. Save changes.

Note: For GitHub Free, GitHub Pages publishing needs a **public** repository. The website and repository can be viewed by anyone. The URLs above are examples, not live until you enable Pages.

## Policy-to-code accuracy notes

The current LoopLeads MVP stores `comments`, `leads`, `messages`, and `events` tables in SQLite. There is no automatic retention expiry, user self-service deletion, or external billing. The `STOP` keyword sets a lead's opt-out flag but does not delete their previous records. Handle verified deletion requests manually, and implement a reliable deletion/export/retention workflow before public customer launch.

These files are a product-specific starting draft, not a substitute for review by a legal/privacy professional.
