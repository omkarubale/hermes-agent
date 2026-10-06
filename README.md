# Z2-1 Hermes site

This repository contains the public homepage and privacy notice for one personally operated Hermes Agent instance and its Google Calendar integration.

The homepage is served at `/`; the privacy notice is served at `/privacy/`. The custom domain is `hermes.omkarubale.com`.

Keep the description of OAuth scopes, server storage, messaging, and model routing aligned with the live configuration. The current setup routes model requests through OpenRouter and stores conversation history in Hermes' local SQLite session database.

No OAuth client JSON, tokens, API keys, private calendar data, or Hermes session exports belong in this repository.
