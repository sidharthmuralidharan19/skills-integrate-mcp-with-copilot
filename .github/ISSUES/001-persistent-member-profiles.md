Title: Persistent member profiles and membership model

Summary:
Add a database-backed member profile system with groups, teams, responsibilities, mentor relationships, and leave records.

Motivation:
Current app stores participant emails in-memory only. A proper member model enables richer features (profile pages, roles, reporting, and integrations).

Acceptance criteria:
- Add `Member` model with name, email (unique), avatar, role, bio, and contact fields.
- Add `Group` and `Team` models and relationships to `Member`.
- Add Mentor/Mentee mapping and `LeaveRecord` model.
- Provide CRUD REST endpoints and admin management.

Implementation notes:
- Use SQLAlchemy (or Tortoise ORM) + SQLite for MVP.
- Add migrations, fixtures, and example data.
