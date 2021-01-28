# database normalization
DB normalization is a process used to organize a database into tables and columns, with the goal of making each table about a specific topic. 

This reduces number of duplicate data and makes modifications easier in the future. 
3 main reasons to normalize: 
- minimize duplicate data
- minimize data modification issues
- simplify queries

Modification anomolies:
- insert anomaly: need to read entire row before we can access items
- update anomaly: if we don't update all rows inconsistencies appear
- deletion anomaly: deletion of a row results in loss of more than one set of facts. 

## 1st normal form: 
info is stored in a relational table with each column containing atomic values. No repeating groups of columns.

## 2nd normal form: 
All columns depend on the table's primary key.

## 3rd normal form: 
ALl columns are not transitively dependent on the primary key. 

