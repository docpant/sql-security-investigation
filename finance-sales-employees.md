# Retrieve Employees in Finance or Sales

## SQL Query

```sql
SELECT *
FROM employees
WHERE department = 'Finance'
OR department = 'Sales';
```

## Explanation

This query retrieves employees working in either the Finance or Sales departments.

- `OR` includes records matching either condition
- The query supports targeted security updates

## Security Benefit

This query helps identify employees requiring security-related machine updates.
