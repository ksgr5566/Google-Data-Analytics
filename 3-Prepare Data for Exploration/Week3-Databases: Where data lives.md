A <strong>database</strong> is a collection of data stored in a computer system. <strong>Metadata</strong> is data about data. Metadata tells you where the data comes from, when and how it was created, and what it's all about.

#### Relational database
A relational database is a database that contains a series of related tables that can be connected via their relationships. For two tables to have a relationship, one or more of the same fields must exist inside both tables.<br>In a non-relational table, you will find all of the possible variables you might be interested in analyzing all grouped together. This can make it really hard to sort through. This is one reason why relational databases are so common in data analysis: they simplify a lot of analysis processes and make data easier to find and use across an entire database. 

There are two types of keys that connect tables in relational databases.:
- A **primary key** is an identifier that references a column in which each value is unique.
  - Used to ensure data in a specific column is unique
  - Uniquely identifies a record in a relational database table
  - Only one primary key is allowed in a table 
  - Cannot contain null or blank values
  -  A primary key may also be constructed using multiple columns of a table. This type of primary key is called a **composite key**.
- A **foreign key** is a field within a table that's a primary key in another table.
  - A column or group of columns in a relational database table that provides a link between the data and two tables
  - Refers to the field in a table that's the primary key of another table
  - More than one foreign key is allowed to exist in a table

---
