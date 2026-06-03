Title: Telegram notifications and external integrations

Summary:
Integrate Telegram bot notifications and GitHub contribution tracking for members.

Acceptance criteria:
- Configurable Telegram bot integration to send announcements and stats.
- GitHub integration to fetch contribution counts per member (opt-in).
- Settings UI for integration configuration (tokens, webhooks).

Implementation notes:
- Use background tasks for polling and a secure storage for tokens.
