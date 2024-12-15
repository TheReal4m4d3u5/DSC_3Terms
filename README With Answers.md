# DSC_3Terms


Data-definition language (DDL):
A language used to define the structure of a database, including creating, altering, and deleting tables and schemas.


Data-manipulation language (DML):
A language used for querying and updating data in a database, such as SELECT, INSERT, UPDATE, and DELETE.

Database schema:
The structure of a database, including tables, columns, data types, relationships, and constraints.

Database instance:
The actual data stored in a database at a particular moment. It is the state of the database at a given time.

Relation schema:
The structure of a relation (table), including its name, columns, and data types.

Relation instance:
A set of rows (tuples) in a relation (table) at a specific point in time.

Primary key:
A unique identifier for each row in a table. It ensures that no two rows have the same value for the primary key.

Foreign key:
A column (or set of columns) in a table that references the primary key of another table, establishing a relationship between the tables.

Referencing relation:
The table containing the foreign key.

Referenced relation:
The table whose primary key is referenced by the foreign key.

Null Value:
A special marker in SQL for missing or undefined data.

Query Language:
A language used to perform queries on a database, such as SQL.

SQL Query Structure:
The general format of a SQL query, including clauses like SELECT, FROM, WHERE, GROUP BY, and HAVING.

SELECT Clause:
Specifies which columns or expressions to return in the query results.

FROM Clause:
Specifies the tables or subqueries to retrieve data from.

WHERE Clause:
Filters rows based on specified conditions.

Natural Join Operation:
A join that automatically matches columns with the same name in both tables.

AS Clause:
Used to create an alias for a table or column.

ORDER BY Clause:
Sorts the results of a query by specified columns or expressions.

Correlation Name (Tuple Variable):
An alias for a table used within a query, often in joins and subqueries.

Set Operations
UNION:
Combines the results of two queries and removes duplicates.

INTERSECT:
Returns rows that are common to both queries.

EXCEPT:
Returns rows from the first query that are not present in the second query.

Aggregate Functions

AVG:
Calculates the average of a set of values.

MIN:
Returns the minimum value in a set of values.

MAX:
Returns the maximum value in a set of values.

SUM:
Calculates the total sum of a set of values.

COUNT:
Returns the number of rows in a set.

Grouping and Filtering

GROUP BY Clause:
Groups rows based on specified columns and allows aggregate functions to be applied to each group.

HAVING Clause:
Filters groups based on aggregate function results.

Subqueries and Comparisons

Nested Subqueries:
A subquery within another query.

Set Comparisons:
Comparing a value to a set of values (e.g., = ANY, = ALL).

EXISTS:
Checks if a subquery returns any rows.

UNIQUE:
Ensures that a subquery returns unique rows.

LATERAL Clause:
Allows a subquery to reference columns from preceding tables in the FROM clause.

WITH Clause:
Defines common table expressions (CTEs) for use within the query.

Scalar Subquery:
A subquery that returns a single value.

Database Modification

Insertion:
Adding new rows to a table using the INSERT statement.

Deletion:
Removing rows from a table using the DELETE statement.

Updating:
Modifying existing rows in a table using the UPDATE statement.
