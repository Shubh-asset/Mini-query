# MiniQuery SQL Subset

MiniQuery does not aim to support full SQL. It supports a small, clean subset
of SQL focused on querying, joining, filtering, aggregation, and optimization.

## Goal

The goal of this subset is to allow MiniQuery to demonstrate:

- SQL parsing
- AST creation
- Binding and name resolution
- Logical relational planning
- Query optimization
- Volcano-style execution
- Join algorithms
- Aggregation
- EXPLAIN output

## Supported SQL statements

MiniQuery supports read-only SELECT queries.

## Supported

- SELECT
- FROM
- WHERE
- INNER JOIN
- ON
- GROUP BY
- LIMIT
- COUNT(\*)
- COUNT(column)
- SUM(column)
- AVG(column)
- MIN(column)
- MAX(column)

## Supported operators

- =
- !=
- <
- <=
- >
- > =
- AND
- OR
- NOT
- -
- -
- -
- /

## Not supported yet

- ORDER BY
- DISTINCT
- HAVING
- LEFT JOIN
- RIGHT JOIN
- FULL JOIN
- Subqueries
- INSERT
- UPDATE
- DELETE
- Transactions
- Indexes
