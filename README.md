# SQL Notes

## Contents

- [SQL Notes](#sql-notes)
  - [Contents](#contents)
  - [Operator Precedence](#operator-precedence)

## Operator Precedence

An ordered list of the precedences of various SQL operators, from highest to lowest:

1. Parentheses: Expressions enclosed in parentheses are evaluated first.
2. Multiplication, Division, and Modulus: These arithmetic operators have the next highest precedence.
3. Addition and Subtraction: These arithmetic operators have lower precedence than multiplication, division, and modulus.
4. Comparison Operators: These operators are used to compare values, such as equality (`=`), greater than (`>`), less than (`<`), etc.
5. Logical NOT: The `NOT` operator is used to negate a boolean expression.
6. Logical AND: The `AND` operator is used to combine two or more boolean expressions, and it has higher precedence than the `OR` operator.
7. Logical OR: The `OR` operator is used to combine two or more boolean expressions.
8. IS NULL: The `IS NULL` operator checks if a value is null.
9. LIKE: The `LIKE` operator is used for pattern matching in string comparisons.
10. BETWEEN: The `BETWEEN` operator is used to check if a value lies within a range.
11. IN: The `IN` operator is used to check if a value is contained within a set of values.
12. EXISTS: The `EXISTS` operator is used to check the existence of a result from a subquery.
13. ALL, ANY, and SOME: These operators are used for comparing a value to a set of values returned by a subquery.
14. UNION, INTERSECT, and EXCEPT: These set operators combine or subtract the results of two or more SELECT statements.
15. Assignment (=): The assignment operator is used to assign a value to a variable or column.
16. ORDER BY: The `ORDER BY` clause is used to specify the sorting order of the result set.
17. GROUP BY: The `GROUP BY` clause is used to group rows based on specified columns.
18. HAVING: The `HAVING` clause is used to filter grouped results.
19. SELECT: The `SELECT` statement is used to retrieve data from one or more tables.
20. FROM: The `FROM` clause is used to specify the table or tables from which to retrieve data.
21. WHERE: The `WHERE` clause is used to filter rows based on specified conditions.
22. JOIN: The `JOIN` clause is used to combine rows from multiple tables based on a related column between them.
23. UNION: The `UNION` operator is used to combine the results of two or more SELECT statements.
24. INSERT: The `INSERT` statement is used to insert new rows into a table.
25. UPDATE: The `UPDATE` statement is used to modify existing rows in a table.
26. DELETE: The `DELETE` statement is used to delete existing rows from a table.
