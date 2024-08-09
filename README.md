# practice-SQL-exercises

# FORMAT

## DESCRIPTION

## PROBLEM DETAILS
REF: <https://datalemur.com/>
Problem link: <>

## PROBLEM ANALYSIS

## SOLUTION

### High-level Overview

### CODE
```sql

```

## LESSONS

1. Order of execution of a Query

<b>Complete SELECT query<b>

```sql
SELECT DISTINCT column, AGG_FUNC(column_or_expression), …
FROM mytable
JOIN another_table
  ON mytable.column = another_table.column
WHERE constraint_expression
GROUP BY column
HAVING constraint_expression
ORDER BY column ASC/DESC
LIMIT count OFFSET COUNT;
```

`F (FROM) -> J (JOIN) -> W (WHERE) -> G (GROUP BY)-> H (HAVING) -> S (SELECT) -> D (DISTINCT) -> O (ORDER) -> L (LIMIT)`

