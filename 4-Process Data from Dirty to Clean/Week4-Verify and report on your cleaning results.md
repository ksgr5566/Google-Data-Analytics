### Verification
Verification is a process to confirm that a data cleaning effort was well- executed and the resulting data is accurate and reliable. It involves rechecking your clean dataset, doing some manual clean ups if needed, and taking a moment to sit back and really think about the original purpose of the project. That way, you can be confident that the data you collected is credible and appropriate for your purposes.

Reporting is a great opportunity to show stakeholders that you're accountable, build trust with your team, and make sure you're all on the same page of important project details.  Different strategies for reporting include creating **data- cleaning reports**, **documenting your cleaning process**, and using **changelog**.

#### Changelog
A changelog is a file containing a chronologically ordered list of modifications made to a project. It's usually organized by version and includes the date followed by a list of added, improved, and removed features. Changelogs are very useful for keeping track of how a dataset evolved over the course of a project. They're also another great way to communicate and report on data to others. They can be referred to during the verification period if there are errors or questions.

<br />

- The first step in the verification process is going back to your original unclean data set and comparing it to what you have now, review the dirty data and try to identify any common problems.
- Another key part of verification involves taking a big-picture view of your project. This is an opportunity to confirm you're actually focusing on the business problem, that you need to solve, and the overall project goals; and to make sure that your data is actually capable of solving that problem and achieving those goals. Taking a big picture view of your project involves doing three things:
  1. Consider the business problem you're trying to solve with the data. Taking a problem-first approach to analytics is essential at all stages of any project.
  2. Consider the goal of the project. On top of that, you also need to know whether the data you've collected and cleaned will actually help your company achieve that goal.
  3. Consider whether your data is capable of solving the problem and meeting the project objectives.

<br>

- **COUNTA** counts the total number of values within a specified range. Note that there's also function called **COUNT**, which only counts the numerical values within a specified range.
- If you're working in SQL, you can address misspellings using a `CASE` statement. The `CASE` statement goes through one or more conditions and returns a value as soon as a condition is met. You should add a CASE statement as a `SELECT` clause. The typo would be a condition and the correction would be the returned value for the condition.

---

#### Documentation
The process of tracking changes, additions, deletions and errors involved in your data cleaning effort. Changelogs are good example of this, since it's staged chronologically, it provides a real-time account of every modification. Documenting data-cleaning makes it possible to be transparent about your process, keep team members on the same page, and demonstrate to project stakeholders that you are accountable.

Having a record of how a data set evolved does three very important things:
- Lets us recover data-cleaning errors (recalling the errors that were cleaned).
- Documentation gives you a way to inform other users of changes you've made.
- Documentation helps you to determine the quality of the data to be used in analysis.

Most software applications have a kind of history tracking built in. You can use and view a changelog in spreadsheets and SQL to achieve similar results.
- In the spreadsheet, we can use *Sheets Version History*, which provides a real-time tracker of all the changes and who made them from individual cells to the entire worksheet. If you want to check out changes in a specific cell, we can right-click and select *Show Edit History*. 
- The way you create and view a changelog with SQL depends on the software program you're using. 
  - In BigQuery, *Query History* tracks all the queries you've run. You can click on any of them to revert back to a previous version of your query or to bring up an older version to find what you've changed.

While your team can view changelogs directly, stakeholders can't and have to rely on your report to know what you did. There're plenty of ways we could go about documenting what we did, one common way is to just create a doc listing out the steps we took and the impact they had. If we were working with SQL, we could include a comment in the statement describing the reason for a change without affecting the execution of the statement.

Clean data is important to the task at hand. But the data-cleaning process itself can reveal insights that are helpful to a business. The feedback we get when we report on our cleaning can transform data collection processes, and ultimately business development. With consistent documentation and reporting, we can uncover error patterns in data collection and entry procedures and use the feedback we get to make sure common errors aren't repeated. Maybe we need to reprogram the way the data is collected or change specific questions on the survey form. In more extreme cases, the feedback we get can even send us back to the drawing board to rethink expectations and possibly update quality control procedures. For example, sometimes it's useful to schedule a meeting with a data engineer or data owner to make sure the data is brought in properly and doesn't require constant cleaning.

Some advanced functions that can help you speed up the data cleaning process in spreadsheets. Below is a table summarizing three functions and what they do:

![image](https://user-images.githubusercontent.com/74421758/147387359-ffa51f93-0531-4b1e-a7a1-c1f1f49ec236.png)

---

[Glossary](https://docs.google.com/document/d/1rYNIY-fDkA2lLCwrBrvhzNV5BzzHpjTcsiWwXou0bj4/template/preview)

---
