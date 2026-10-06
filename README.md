# Z2-1 Hermes site

This repository contains the public homepage and privacy notice for one personally operated Hermes Agent instance and its Google Calendar integration.

The site source is kept under `pages/` and deployed by GitHub Actions. It serves the homepage at `/` and the privacy notice at `/privacy/` on `hermes.omkarubale.com`.

In the repository's **Settings → Pages**, set the publishing source to **GitHub Actions**. Branch-based publishing supports only the repository root or `/docs`, so it cannot publish directly from `/pages`.

Keep the description of OAuth scopes, server storage, messaging, and model routing aligned with the live configuration. The current setup routes model requests through OpenRouter and stores conversation history in Hermes' local SQLite session database.

No OAuth client JSON, tokens, API keys, private calendar data, or Hermes session exports belong in this repository.
