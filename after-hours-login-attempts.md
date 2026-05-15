# Retrieve After Hours Failed Login Attempts

## SQL Query

```sql
SELECT *
FROM log_in_attempts
WHERE login_time > '18:00'
AND success = FALSE;
```

## Explanation

This query retrieves all failed login attempts that occurred after 6:00 PM.

- `WHERE` filters the records
- `login_time > '18:00'` identifies activity after business hours
- `AND success = FALSE` filters only failed login attempts

## Security Benefit

This query helps identify suspicious login activity occurring outside normal working hours.
