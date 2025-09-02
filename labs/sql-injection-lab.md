# 🧪 SQL Injection Lab

## Objective
Learn how attackers exploit vulnerable SQL queries and how to defend against them.

## Tasks
1. Set up a demo web app with a login form.
2. Try basic payloads:
   - `' OR '1'='1`
   - `' OR '1'='1' --`
3. Observe how authentication is bypassed.
4. Fix the vulnerability using prepared statements.

## Defense
- Always sanitize inputs.
- Use parameterized queries.
- Apply least-privilege access to databases.
