Title: Attendance integration and leave records

Summary:
Support importing live attendance (e.g., from a Raspberry Pi module) and track leaves per member.

Acceptance criteria:
- API endpoint to import attendance logs (timestamped, member email/id).
- Map logs to `Attendance` records tied to `Member` and `Event` (if applicable).
- UI and endpoints to view attendance summaries and export CSV.

Implementation notes:
- Consider a small webhook/collector service or background task to poll the attendance module.
