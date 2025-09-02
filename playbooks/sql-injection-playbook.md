# 🔒 SQL Injection Playbook

## Detection
- Look for `' OR '1'='1` in logs.
- Unexpected database errors in responses.
- High number of failed login attempts.

## Response
1. Block attacker IP in WAF/firewall.
2. Check affected DB for unauthorized queries.
3. Roll back malicious data changes.

## Prevention
- Use parameterized queries.
- Apply WAF rules.
- Conduct regular code reviews.
