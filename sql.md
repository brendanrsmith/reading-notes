# SQL 
SQL is Structured Query Language, which allows you to query, manipulate, and transform data from relational databases. 

It is simple, scalalbe, and ubiquitous.

SQLite, MySQL, Postgres, Oracle, and Microsoft SQL Server all use SQL as their base language. 

## Relational Databases
A relational database is a collection of two-dimensional related tables. Kind of like excel on steriods. 

### SELECT queries
we use `SELECT` to retreive dat from a sql database. 
  SELECT * FROM table;
  // this is a quick way to dump all the data from a given table
### WHERE constraints
`WHERE` is a clause that is applied to each row. Like a filter. 
  `=`, `!=`, `<`, `>`
  `BETWEEN ... AND ...`
  `IN(...)`
  `NOT`
### DISTINCT
`DISTINCT` removes duplicate rows 
### ORDER BY
`ORDER BY` allws you to select ascending or descending order by a given column.

`LIMIT` and `OFFSET` allow you to specify the number of responses you want
### INSERT INTO and REMOVE 
allows you to add new entries to a given data table

### UPDATE
Rather than adding a new entry completely, `UPDATE` allows you to edit current data in-place

### DELETE
Removes data given conditions 

### CREATE TABLE 
takes data types
  `INTEGER`, `BOOLEAN`
  `FLOAT`, `DOUBLE`, `REAL`
  `CHARACTER(num_chars)`, `VARCHAR(num_chars)`, `TEXT`
  `DATE`, `DATETIME`
  `BLOB`

### ALTER TABLE
update the database schema bu adding, removing, and modifying columns

### DROP TABLE
super-delete 
