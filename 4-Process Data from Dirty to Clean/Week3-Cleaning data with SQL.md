SQL can process large amounts of data much more quickly than spreadsheets.

Where the data lives will decide which tool you use. If you are working with data that is already in a spreadsheet, that is most likely where you will perform your analysis. And if you are working with data stored in a database, SQL will be the best tool for you to use for your analysis. SQL can handle huge amounts of data, can be adapted and used with multiple database programs, and offers powerful tools for cleaning data.

Data stored in a SQL database is useful to a project with multiple team members because they can access the data at the same time, use SQL to interact with the database program, and track changes to SQL queries across the team.

Structured Query Language, or SQL, is a language used to talk to databases. Learning SQL can be a lot like learning a new language — including the fact that languages usually have different dialects within them. Some database products have their own variant of SQL, and these different varieties of SQL dialects are what help you communicate with each database product. These dialects will be different from company to company and might change over time if the company moves to another database system. So, a lot of analysts start with Standard SQL and then adjust the dialect they use based on what database they are working with. Standard SQL works with a majority of databases and requires a small number of syntax changes to adapt to other dialects.

---

- We can use `SELECT` to specify exactly what data we want to interact with in a table. If we combine `SELECT` with `FROM`, we can pull data from any table in this database as long as they know what the columns and rows are named.
- We can also insert new data into a database or update existing data. We can use the `INSERT INTO` query to put that information in. We also want to specify which columns we're adding this data to by typing their names in the parentheses.
- If we want to create a new table for an updated database, we can use the `CREATE TABLE IF NOT EXISTS` statement. Just running a SQL query doesn't actually create a table for the data we extract. It just stores it in our local memory.
- If you're creating lots of tables within a database, you'll want to use the `DROP TABLE IF EXISTS` statement to clean up.

---
