# Retrieve All Employees Not in IT

## SQL Query

```sql
SELECT *
FROM employees
WHERE NOT department = 'Information Technology';
```

## Explanation

This query retrieves all employees who are not part of the Information Technology department.

- `NOT` excludes IT department employees
- The query helps identify systems requiring updates outside the IT department

## Security Benefit

This query supports efficient deployment of security updates to non-IT employees.
