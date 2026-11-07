# The Curated Find — GitHub Pages website

A small static website for the independently developed, personal-use Pin publishing application.

## Repository

Create a **public** GitHub repository named:

`the-curated-find`

GitHub Pages is available for public repositories on GitHub Free. The expected project-site URL is:

`https://romangow.github.io/the-curated-find/`

## Before publishing — required edits

1. Create a dedicated Gmail address for this project.
2. In these files, replace every occurrence of:
   `[ADD YOUR DEDICATED GMAIL ADDRESS BEFORE PUBLISHING]`
   with the actual address:
   - `privacy-policy/index.html`
   - `terms/index.html`
   - `contact/index.html`
3. Review the privacy policy against the actual application's implementation. In particular, verify where tokens, drafts, logs and API responses are stored, whether any analytics or external services are used, and whether any data is retained.
4. If the application changes or is later offered to other people, update the privacy policy and terms before doing so.

Do not publish the site with the email placeholder still present.

## Publish with GitHub Pages

1. Sign in at https://github.com/RomanGOW.
2. Create a new **public** repository named `the-curated-find`.
3. Upload the contents of this folder to the repository root. Do not upload the outer `the-curated-find-github-pages` folder itself.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then save.
7. Wait for the Pages deployment to complete. GitHub notes that publishing can take up to 10 minutes.
8. Check these URLs in a private/incognito browser window:
   - `https://romangow.github.io/the-curated-find/`
   - `https://romangow.github.io/the-curated-find/privacy-policy/`
   - `https://romangow.github.io/the-curated-find/terms/`
   - `https://romangow.github.io/the-curated-find/contact/`

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Pinterest application details — proposed

- App name: `The Curated Find Pin Publisher`
- Company name: `The Curated Find`
- Company website: `https://romangow.github.io/the-curated-find/`
- Privacy policy: `https://romangow.github.io/the-curated-find/privacy-policy/`

Use the application purpose that accurately describes the actual app. Do not claim features that are not implemented.

## Important limitations

- A GitHub Pages URL is a third-party-hosted domain. Pinterest support must confirm that this specific GitHub Pages URL satisfies the requirement they gave you. This package does not guarantee Pinterest approval.
- GitHub Pages is static hosting. It does not run a backend or keep OAuth client secrets safe. Never put Pinterest client secrets, access tokens, refresh tokens, passwords, or private app configuration in this repository.
- The privacy policy notes that GitHub Pages logs visitor IP addresses for security purposes, based on GitHub's published documentation.
- The policy and terms are practical drafts, not legal advice. Review them for accuracy before publishing.
