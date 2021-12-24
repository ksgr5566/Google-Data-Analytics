#### Dirty data and Clean data
Dirty data is data that is incomplete, incorrect, or irrelevant to the problem you're trying to solve. Clean data is data that is complete, correct, and relevant to the problem you're trying to solve.

**Data engineers** transform data into a useful format for analysis and give it a reliable infrastructure. This means they develop, maintain, and test databases, data processors and related systems. <br> **Data warehousing specialists** develop processes and procedures to effectively store and organize data. They make sure that data is available, secure, and backed up to prevent loss.

A **null** is an indication that a value does not exist in a data set.

<details>
  <summary>Types of dirty data</summary> <br>
  
Description | Possible Causes | Potential harm to businesses
----------- | --------------- | ----------------------------
<strong>Duplicate data</strong>: Any data record that shows up more than once | Manual data entry, batch data imports, or data migration | Skewed metrics or analyses, inflated or inaccurate counts or predictions, or confusion during data retrieval
<strong>Outdated data</strong>: Any data that is old which should be replaced with newer and more accurate information | People changing roles or companies, or software and systems becoming obsolete | Inaccurate insights, decision-making, and analytics
<strong>Incomplete data</strong>: Any data that is missing important fields | Improper data collection or incorrect data entry | Decreased productivity, inaccurate insights, or inability to complete essential services
<strong>Incorrect/inaccurate data</strong>: Any data that is complete but inaccurate | Human error inserted during data input, fake information, or mock data | Inaccurate insights or decision-making based on bad information resulting in revenue loss
<strong>Inconsistent data</strong>: Any data that uses different formats to represent the same thing | Data stored incorrectly or errors inserted during data transfer | Contradictory data points leading to confusion or inability to classify or segment customers

</details>

A **field** is a single piece of information from a row or column of a spreadsheet. **Field length** is a tool for determining how many characters can be keyed into a field. Using the field length tool to specify the number of characters in each cell in the column could be part of data validation.

**Data validation** is a tool for checking the accuracy and quality of data before adding or importing it.

---

#### Data merging
The process of combining two or more datasets into a single dataset. This presents a unique challenge because when two totally different datasets are combined, the information is almost guaranteed to be inconsistent and misaligned. In data analytics, **compatibility** describes how well two or more datasets are able to work together. 

Key questions to think about to avoid redundancy and to confirm that the datasets are compatible:
- Do I have all the data I need?
- Does the data I need exist within these datasets?
- Do the datasets need to be cleaned, or are they ready for me to use?
- Are the datasets cleaned to the same standard?

<details><summary>Common data-cleaning pitfalls</summary><br><ul>
  <li><strong>Not checking for spelling errors</strong>: Misspellings can be as simple as typing or input errors. Most of the time the wrong spelling or common grammatical errors can be detected, but it gets harder with things like names or addresses. For example, if you are working with a spreadsheet table of customer data, you might come across a customer named “John” whose name has been input incorrectly as “Jon” in some places. The spreadsheet’s spellcheck probably won’t flag this, so if you don’t double-check for spelling errors and catch this, your analysis will have mistakes in it.</li>
  <li><strong>Forgetting to document errors</strong>: Documenting your errors can be a big time saver, as it helps you avoid those errors in the future by showing you how you resolved them. For example, you might find an error in a formula in your spreadsheet. You discover that some of the dates in one of your columns haven’t been formatted correctly. If you make a note of this fix, you can reference it the next time your formula is broken, and get a head start on troubleshooting. Documenting your errors also helps you keep track of changes in your work, so that you can backtrack if a fix didn’t work.</li>
  <li><strong>Not checking for misfielded values</strong>: A misfielded value happens when the values are entered into the wrong field. These values might still be formatted correctly, which makes them harder to catch if you aren’t careful. For example, you might have a dataset with columns for cities and countries. These are the same type of data, so they are easy to mix up. But if you were trying to find all of the instances of Spain in the country column, and Spain had mistakenly been entered into the city column, you would miss key data points. Making sure your data has been entered correctly is key to accurate, complete analysis. </li>
  <li><strong>Overlooking missing values</strong>: Missing values in your dataset can create errors and give you inaccurate conclusions. For example, if you were trying to get the total number of sales from the last three months, but a week of transactions were missing, your calculations would be inaccurate.  As a best practice, try to keep your data as clean as possible by maintaining completeness and consistency.</li>
  <li><strong>Only looking at a subset of the data</strong>: It is important to think about all of the relevant data when you are cleaning. This helps make sure you understand the whole story the data is telling, and that you are paying attention to all possible errors. For example, if you are working with data about bird migration patterns from different sources, but you only clean one source, you might not realize that some of the data is being repeated. This will cause problems in your analysis later on. If you want to avoid common errors like duplicates, each field of your data requires equal attention.</li>
  <li><strong>Losing track of business objectives</strong>: When you are cleaning data, you might make new and interesting discoveries about your dataset-- but you don’t want those discoveries to distract you from the task at hand. For example, if you were working with weather data to find the average number of rainy days in your city, you might notice some interesting patterns about snowfall, too. That is really interesting, but it isn’t related to the question you are trying to answer right now. Being curious is great! But try not to let it distract you from the task at hand.</li>
  <li><strong>Not fixing the source of the error</strong>: Fixing the error itself is important. But if that error is actually part of a bigger problem, you need to find the source of the issue. Otherwise, you will have to keep fixing that same error over and over again. For example, imagine you have a team spreadsheet that tracks everyone’s progress. The table keeps breaking because different people are entering different values. You can keep fixing all of these problems one by one, or you can set up your table to streamline data entry so everyone is on the same page. Addressing the source of the errors in your data will save you a lot of time in the long run.</li>
  <li><strong>Not analyzing the system prior to data cleaning</strong>: If we want to clean our data and avoid future errors, we need to understand the root cause of your dirty data. Imagine you are an auto mechanic. You would find the cause of the problem before you started fixing the car, right? The same goes for data. First, you figure out where the errors come from. Maybe it is from a data entry error, not setting up a spell check, lack of formats, or from duplicates. Then, once you understand where bad data comes from, you can control it and keep your data clean.</li>
  <li><strong>Not backing up your data prior to data cleaning</strong>: It is always good to be proactive and create your data backup before you start your data clean-up. If your program crashes, or if your changes cause a problem in your dataset, you can always go back to the saved version and restore it. The simple procedure of backing up your data can save you hours of work-- and most importantly, a headache.</li>
  <li><strong>Not accounting for data cleaning in your deadlines/process</strong>: All good things take time, and that includes data cleaning. It is important to keep that in mind when going through your process and looking at your deadlines. When you set aside time for data cleaning, it helps you get a more accurate estimate for ETAs for stakeholders, and can help you know when to request an adjusted ETA.</li>
  </ul></details>
  
Refer to these "top ten" lists for data cleaning in Microsoft Excel and Google Sheets to help you avoid the most common mistakes:
- [Top ten ways to clean your data](https://support.microsoft.com/en-us/office/top-ten-ways-to-clean-your-data-2844b620-677c-47a7-ac3e-c2e157d1db19): Review an orderly guide to data cleaning in Microsoft Excel.
- [10 Google Workspace tips to clean up data](https://support.google.com/a/users/answer/9604139?hl=en#zippy=): Learn best practices for data cleaning in Google Sheets.

Cleaning is a fundamental step in data science as it greatly increases the integrity of the data. If data analysis is based on bad or “dirty” data, it may be biased, erroneous, and uninformed. Good data science results rely heavily on the reliability of the data. Data analysts clean data to make it more accurate and reliable. This is important for making sure that the projects you will work on as a data analyst are completed properly.

---

- **Conditional formatting** is a spreadsheet tool that changes how cells appear when values meet specific conditions.
- **Remove duplicates** is a tool that automatically searches for and eliminates duplicate entries from a spreadsheet.
- In data analytics, a **text string** is a group of characters within a cell, commonly composed of letters, numbers or both. An important characteristic of a text string is its length, which is the number of characters in it. A **substring** is a smaller subset of a text string.
- **Split** is a tool that divides a text string around the specified character and puts each fragment into a new and separate cell.

<br>

- **COUNTIF** is a function that returns the number of cells that match a specified value. `=COUNTIF(range, "value")` 
- **LEN** is a function that tells you the length of the text string by counting the number of characters it contains. `=LEN(range)`
- **LEFT** is a function that gives you a set number of characters from the left side of a text string. `=LEFT(range, number of characters)`
- **RIGHT** is a function that gives you a set number of characters from the right side of a text string. `=RIGHT(range, number of characters)`
- **MID** is a function that gives you a segment from the middle of a text string. `=MID(range, reference starting point, number of middle characters)` 
- **CONCATENATE** is a function that joins multiple text strings into a single string. `=CONCATENATE(item 1, item 2)`
- **TRIM** is a function that removes leading, trailing, and repeated spaces in data. `=TRIM(range)`

<br>

Different methods that data analysts use to look at data differently and how that leads to more efficient and effective data cleaning: Some of these methods include sorting and filtering, pivot tables, a function called VLOOKUP, and plotting to find outliers.

- For data cleaning, you can use sorting to put things in alphabetical or numerical order, so you can easily find a piece of data. Sorting can also bring duplicate entries closer together for faster identification. Filters, on the other hand, are very useful in data cleaning when you want to find a particular piece of information.
- **Pivot tables** sort, reorganize, group, count, total or average data stored in the database. In data cleaning, pivot tables are used to give you a quick, clutter- free view of your data. You can choose to look at the specific parts of the data set that you need to get a visual in the form of a pivot table.
- **VLOOKUP** stands for vertical lookup. It's a function that searches for a certain value in a column to return a corresponding piece of information. `=VLOOKUP(data to look up, 'where to look up' !Range, column, false)`
- When you plot data, you put it in a graph chart, table, or other visual to help you quickly find what it looks like. Plotting is very useful when trying to identify any skewed data or outliers.

<br>

#### Data mapping
Data mapping is the process of matching fields from one data source to another. Different systems store data in different ways. Data mapping helps us note these kinds of differences so we know when data is moved and combined it will be compatible.

1. The first step to data mapping is identifying what data needs to be moved. This includes the tables and the fields within them. We also need to define the desired format for the data once it reaches its destination.
2. Next comes mapping the data. Depending on the schema and number of primary and foreign keys in a data source, data mapping can be simple or very complex. A **schema** is a way of describing how something is organized. For more challenging projects there's all kinds of data mapping software programs you can use. These data mapping tools will analyze field by field how to move data from one place to another then they automatically clean, match, inspect, and validate the data. They also create consistent naming conventions, ensuring compatibility when the data is transferred from one source to another. When selecting a software program to map your data, you want to be sure that it supports the file types you're working with, such as Excel, SQL, Tableau, and others.
3. The next step is to transform the data into a consistent format.
4. Now that everything's compatible, it's time to transfer the data to it's destination. There's a lot of different ways to move data from one place to another, including querying, import wizards, and even simple drag and drop.
5. We would still want to make sure everything was transferred properly. We'll go into the testing phase of data mapping. For this, you inspect a sample piece of data to confirm that it's clean and properly formatted. It's also a smart practice to do spot checks on things such as the number of nulls. For the test, you can use a lot of the data cleaning tools such as data validation, conditional formatting, COUNTIF, sorting, and filtering.
6. Once you've determined that the data is clean and compatible, you can start using it for analysis.

---

[Glossary](https://docs.google.com/document/d/1JC24x3TypcFdueCPEd5UAnKIzL9sM8UpOKaMHdibiq4/template/preview)

---


