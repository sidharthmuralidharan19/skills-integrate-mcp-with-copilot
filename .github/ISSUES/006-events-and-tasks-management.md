Title: Events, RSVPs, and task management

Summary:
Implement a richer events subsystem with RSVP, capacity handling, and a tasks feature for organizers.

Acceptance criteria:
- Event model with date/time, location, capacity, description.
- RSVP endpoints for members (with waitlisting once full).
- Task model for organizers with assignment and status.

Implementation notes:
- Reuse Activity and Member models; add notifications when RSVPs change.
