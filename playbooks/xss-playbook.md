# 🔒 Cross-Site Scripting (XSS) Playbook

## Detection
- Alerts triggered from CSP reports.
- Logs showing `<script>` injection attempts.
- User complaints about strange popups.

## Response
1. Remove injected payloads from DB.
2. Patch vulnerable pages with output encoding.
3. Notify affected users if session hijacking suspected.

## Prevention
- Encode all untrusted data.
- Use HTTP-only & Secure cookies.
- Implement strong CSP.
