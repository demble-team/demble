# Security Policy

Demble is in pre-alpha. No production security guarantees or supported release versions are available yet.

## Reporting a vulnerability

**Please do not open a public Issue for vulnerabilities, secrets, or private user data.**

Use GitHub's **Report a vulnerability** flow under this repository's Security tab. The maintainers should enable **Private vulnerability reporting** in repository settings when the repository is created.

Include a concise description, affected area, reproducible steps, expected impact, and a safe proof of concept if appropriate. Do not access data you do not own.

## Security priorities

The planned product will handle team discussion, meetings, artifacts, agent credentials, and source-linked shared context. Early review should focus on:

- Room and membership isolation across the UI, API, search, and AI retrieval.
- Minimal, revocable scopes for agent credentials.
- Explicit consent and retention for audio, transcripts, and files.
- No accidental upload of private agent sessions or local workspaces.
- No unbounded execution or public exposure of local demo services.
- Auditable changes and safe handling of source deletion or revoked access.

Security-sensitive design choices should be reviewed before implementing them.
