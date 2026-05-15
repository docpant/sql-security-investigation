# Retrieve Employees in Marketing

## SQL Query

```sql
SELECT *
FROM employees
WHERE department = 'Marketing'
AND office LIKE 'East%';
```

## Explanation

This query retrieves all employees in the Marketing department located in East building offices.

- `AND` combines multiple conditions
- `LIKE 'East%'` filters office names beginning with "East"

## Security Benefit

This query helps identify employee machines requiring security updates.
