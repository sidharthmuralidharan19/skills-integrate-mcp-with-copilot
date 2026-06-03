Title: Certificate generation and bulk mailer

Summary:
Add features to generate participation certificates and send bulk emails to members.

Acceptance criteria:
- Template-driven certificate generation (PDF export) per activity/event.
- Bulk mailer to send certificates and announcements.
- Audit trail for sent certificates/emails.

Implementation notes:
- Use a templating engine + `WeasyPrint` or `ReportLab` for PDF generation.
