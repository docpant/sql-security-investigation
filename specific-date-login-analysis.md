# Retrieve Login Attempts on Specific Dates

## SQL Query

```sql
SELECT *
FROM log_in_attempts
WHERE login_date = '2022-05-09'
OR login_date = '2022-05-08';
```

## Explanation

This query retrieves all login attempts from May 8 and May 9, 2022.

- `OR` is used to include records from either date
- The query filters login activity during the suspicious time period

## Security Benefit

This query helps investigators review activity surrounding a suspicious security event.
