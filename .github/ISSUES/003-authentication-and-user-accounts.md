Title: Authentication and user accounts

Summary:
Add user registration, login, and authentication for protected endpoints.

Motivation:
Many features (signup limits, admin actions, member profiles) require authenticated users.

Acceptance criteria:
- Implement user model with hashed passwords and email uniqueness.
- Provide registration and login endpoints with JWT or session cookies.
- Protect admin endpoints and provide `is_admin` flag.

Implementation notes:
- FastAPI + `fastapi-users` or custom JWT via `pyjwt` can be used.
- Add email validation and optional password reset flow.
