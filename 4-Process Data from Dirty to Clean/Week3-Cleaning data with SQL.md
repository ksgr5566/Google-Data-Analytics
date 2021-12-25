SQL can process large amounts of data much more quickly than spreadsheets.

Where the data lives will decide which tool you use. If you are working with data that is already in a spreadsheet, that is most likely where you will perform your analysis. And if you are working with data stored in a database, SQL will be the best tool for you to use for your analysis. SQL can handle huge amounts of data, can be adapted and used with multiple database programs, and offers powerful tools for cleaning data. SQL is also a well-known standard in the professional community.

Data stored in a SQL database is useful to a project with multiple team members because they can access the data at the same time, use SQL to interact with the database program, and track changes to SQL queries across the team.

Structured Query Language, or SQL, is a language used to talk to databases. Learning SQL can be a lot like learning a new language — including the fact that languages usually have different dialects within them. Some database products have their own variant of SQL, and these different varieties of SQL dialects are what help you communicate with each database product. These dialects will be different from company to company and might change over time if the company moves to another database system. So, a lot of analysts start with Standard SQL and then adjust the dialect they use based on what database they are working with. Standard SQL works with a majority of databases and requires a small number of syntax changes to adapt to other dialects.

---

- We can use `SELECT` to specify exactly what data we want to interact with in a table. If we combine `SELECT` with `FROM`, we can pull data from any table in this database as long as they know what the columns and rows are named.
- We can also insert new data into a database or update existing data. We can use the `INSERT INTO` query to put that information in. We also want to specify which columns we're adding this data to by typing their names in the parentheses.
- If we want to create a new table for an updated database, we can use the `CREATE TABLE IF NOT EXISTS` statement. Just running a SQL query doesn't actually create a table for the data we extract. It just stores it in our local memory.
- If you're creating lots of tables within a database, you'll want to use the `DROP TABLE IF EXISTS` statement to clean up.
- `DELETE` removes data from a database.
- `UPDATE` changes existing data in a database.
<br>

- Including `DISTINCT` in your `SELECT` statement removes duplicates.
- In a query, if you use the `LENGTH()`, `SUBSTR()`, or `TRIM()` function in a WHERE clause, you can select data based on a string condition. `SUBSTR()` and `TRIM()` functions can be used to clean string variables. `LENGTH()` can be used in the general cleaning process to check if the data is as expected, but it does not actually clean strings.
  - If we already know the length our string variables are supposed to be, we can use `LENGTH(column)` to double-check that our string variables are consistent. For some databases, this query is written as `LEN(column)`, but it does the same thing.
  - `SUBSTR(column, starting position, number of letters including starting position)` is the substring function. 
  - `TRIM(column)` function is really useful if you find entries with extra spaces and need to eliminate those extra spaces for consistency.

<br>

- `MIN(column)` and `MAX(column)` returns the minimum and maximum numerical values respectively in the specified column.
- `COUNT(*)` returns the number of rows.

---

- `CAST(column AS data_type)` can be used to convert anything from one data type to another.
- `ORDER BY` statement allows us to order rows in the specified column in descending or ascending order as specified in the statement.
- `CONCAT(column1, column2)` lets you add strings together to create new text strings that can be used as unique keys.
- `COALESCE(column to check first, column to check second if the first column is null)` can be used to return non-null values in a list. Null values are missing values.

---

[Glossary](https://docs.google.com/document/d/11qyveOPiz27RWNKfQa2xrJ2QwCHwNMHN_Z8_sBr0GNk/template/preview)

---
