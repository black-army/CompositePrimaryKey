# CompositePrimaryKey
Composite Primary Key AutoIncrement Trigger on SQL

It is an important requirement that a field in SQL be unique. This is the "Primary Key".

A unique field can be made auto-increment by classic SQL methods.

When we define two columns as keys in sql, this is "Composite Key".

This is not possible with traditional SQL auto-increment methods when we need an auto-increment like the one below.

Example:
ColumnA | ColumnB

10001 | 1

10001 | 2

10001 | 3

10002 | 1

10002 | 2

To solve this problem, you need to write an SQL Trigger as follows;
