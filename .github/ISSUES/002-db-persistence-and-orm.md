Title: Add persistent storage and ORM

Summary:
Introduce a database and ORM layer to replace the in-memory `activities` data structure.

Motivation:
Persistence is required for real usage, multi-process servers, and integrations.

Acceptance criteria:
- Configure SQLite (dev) and PostgreSQL (prod) connection settings.
- Add ORM models for Activity, Participant, Member, Event.
- Add migration tooling and initial migration files.

Implementation notes:
- Prefer SQLAlchemy + Alembic or Tortoise + Aerich for migrations.
- Update `requirements.txt` accordingly.
