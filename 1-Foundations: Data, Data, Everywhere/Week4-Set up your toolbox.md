### Spreadsheet basics

- Each rectangular block is a cell.
- Each cell is meant for one data point.
- Cells are organized by columns and rows.
- Each column has a distinct letter, and each row has a distinct number. 
- Each cell has a unique identifier composed of the column letter and row number. This identifier is like the cell’s address.

<br />

- Adding labels to the top of the columns will make it easier to reference and find data later on when you're doing analysis. These column labels are usually called attributes. An **attribute** is a characteristic or quality of data used to label a column in a table. More commonly, attributes are referred to as column names, column labels, headers, or the header row.
- In a dataset, a row is also called an observation. An **observation** includes all of the attributes for what is contained in a row of a data table.

<br />

A spreadsheet helps you structure data in rows and columns, prepare data for analysis, and create custom data visualizations. To better analyze your data, you clean up your chart to make it more visually appealing and to clarify what data means by making your chart more descriptive. To do that, it’s important to add chart titles and axis titles.

<br />

[Google Sheets Training and Help](https://support.google.com/a/users/answer/9282959?visit_id=637361702049227170-1815413770&rd=1)

[Google Sheets Cheat Sheet](https://support.google.com/a/users/answer/9300022)

[Microsoft Excel for Windows Training](https://support.microsoft.com/en-us/office/excel-video-training-9bc05390-e94c-46af-a5b3-d7c22f6990bb)

---

### Structured Query Language (SQL)

Structured Query Language (or SQL, often pronounced “sequel”) enables data analysts to talk to their databases. SQL is one of the most useful data analyst tools, especially when working with large datasets in tables. It can help you investigate huge databases, track down text (referred to as strings) and numbers, and filter for the exact kind of data you need—much faster than a spreadsheet can. 

- A **query** is a request for data or information from a database.
- SQL follows a unique set of guidelines known as syntax. **Syntax** is the predetermined structure of a language that includes all required words, symbols, and punctuation, as well as their proper placement.
- The syntax of every SQL query is the same:
  - Use `SELECT` to choose the columns you want to return. A comma to separate fields/variables/parameters.
  - Use `FROM` to choose the tables where the columns you want are located. The dataset name is always followed by a dot, and then the table name.
  - Use `WHERE` to filter for certain information. WHERE command uses the connectors/operators, such as OR and NOT statements, to connect conditions.
  - Example:
  
  ![image](https://user-images.githubusercontent.com/74421758/145982325-4c465a0c-3330-49f5-9236-bcb8402dbe6f.png)
  
  <br />
  
  - The semicolon is a statement terminator, not all SQL databases have adopted or enforce the semicolon, so it’s possible you may come across some SQL statements that aren’t terminated with a semicolon. If a statement works without a semicolon, it’s fine.
  - The WHERE clause narrows your query so that the database returns only the data with an exact value match or the data that matches a certain condition that you want to satisfy. The `LIKE` clause is very powerful because it allows you to tell the database to look for a certain pattern. The percent sign `%` is used as a wildcard to match one or more characters. Note that in some databases an asterisk `*` is used as the wildcard instead of a percent sign `%`.
  -  If you replace `SELECT field1` with `SELECT *` , you would be selecting all of the columns in the table instead of the field1 column only.
  -  Comments are text placed between certain characters, `/*` and `*/`, or after two dashes `--`.
  -  You can also make it easier on yourself by assigning a new name or alias to the column or table names to make them easier to work with. This is done with a SQL `AS` clause.
  -  `<>` means "does not equal" in SQL.
  
  <br />
  
  [W3Schools SQL Tutorial](https://www.w3schools.com/sql/default.asp)
  
  [SQL Cheat Sheet](https://towardsdatascience.com/sql-cheat-sheet-776f8e3189fa)
  
  ---
