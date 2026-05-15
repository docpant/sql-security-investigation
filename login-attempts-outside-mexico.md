# Retrieve Login Attempts Outside of Mexico

## SQL Query

```sql
SELECT *
FROM log_in_attempts
WHERE NOT country LIKE 'MEX%'
AND NOT country LIKE 'MEXICO%';
```

## Explanation

This query retrieves login attempts originating outside of Mexico.

- `LIKE` searches for patterns
- `%` acts as a wildcard character
- `NOT` excludes records containing Mexico-related values

## Security Benefit

This query helps identify suspicious login activity originating from unexpected locations.
