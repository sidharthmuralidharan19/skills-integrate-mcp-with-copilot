Title: Background jobs and schedulers

Summary:
Add background job support for periodic tasks (attendance import, mailer, GitHub polling, certificate generation).

Acceptance criteria:
- Add job runner (Celery + Redis or APScheduler) and example jobs.
- Dashboard or logs for job runs and failures.

Implementation notes:
- Start with APScheduler for lightweight dev use; escalate to Celery for scale.
