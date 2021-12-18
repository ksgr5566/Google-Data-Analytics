### Spreadsheet tasks
- Organize your data
  - Pivot tables
    - Sort and filter
- Calculate your data
  - Formulas
  - Functions
  
<details>
  <summary>Spreadsheets and the data life cycle</summary> <br>
  <ul>
    <li><strong>Plan</strong> for the users who will work within a spreadsheet by developing organizational standards. This can mean formatting your cells, the headings you choose to highlight, the color scheme, and the way you order your data points. When you take the time to set these standards, you will improve communication, ensure consistency, and help people be more efficient with their time.</li>
    <li><strong>Capture</strong> data by the source by connecting spreadsheets to other data sources, such as an online survey application or a database. This data will automatically be updated in the spreadsheet. That way, the information is always as current and accurate as possible.</li>
    <li><strong>Manage</strong> different kinds of data with a spreadsheet. This can involve storing, organizing, filtering, and updating information. Spreadsheets also let you decide who can access the data, how the information is shared, and how to keep your data safe and secure.</li>
    <li><strong>Analyze</strong> data in a spreadsheet to help make better decisions. Some of the most common spreadsheet analysis tools include formulas to aggregate data or create reports, and pivot tables for clear, easy-to-understand visuals.</li>
    <li><strong>Archive</strong> any spreadsheet that you don’t use often, but might need to reference later with built-in tools. This is especially useful if you want to store historical data before it gets updated.</li>
    <li><strong>Destroy</strong> your spreadsheet when you are certain that you will never need it again, if you have better backup copies, or for legal or security reasons. Keep in mind, lots of businesses are required to follow certain rules or have measures in place to make sure data is destroyed properly.</li>
  </ul>
</details> 

[Google Sheets shortcuts](https://support.google.com/docs/answer/181110), [Microsoft Excel shortcuts](https://support.microsoft.com/en-us/office/keyboard-shortcuts-in-excel-1798d9d5-842a-42b8-9c99-9b7213f0040f)

<details>
  <summary>Useful links</summary> <br>
  <ul>
    <li><strong>Excel</strong>: <a href="https://support.microsoft.com/en-us/office/office-quick-starts-25f909da-3e76-443d-94f4-6cdf7dedc51e#ID0EAADAAA=At_work_or_school" target="_blank">Office Quick Starts</a>, <a href="https://support.microsoft.com/en-us/office/excel-video-training-9bc05390-e94c-46af-a5b3-d7c22f6990bb?wt.mc_id=otc_home" target="_blank">Excel video training</a>, <a href="https://support.microsoft.com/en-us/office/sort-data-in-a-range-or-table-62d0b95d-2a90-4610-a6ae-2e545c4a4654" target="_blank">Sort data in a range or table</a>, <a href="https://support.microsoft.com/en-us/office/filter-data-in-a-range-or-table-01832226-31b5-4568-8806-38c37dcc180e" target="_blank">Filter data in a range or table</a>, <a href="https://support.microsoft.com/en-us/office/quick-start-format-a-worksheet-d70f75a2-23e6-4c92-83d6-2f219e4ad42e" target="_blank">Format a worksheet</a>, <a href="https://support.microsoft.com/en-us/office/guidelines-for-organizing-and-formatting-data-on-a-worksheet-90895cad-6c85-4e02-90d3-8798660166e3" target="_blank">Guidelines for organizing and formatting data on a worksheet</a>.</li>
    <li><strong>Google Sheets</strong>: <a href="https://support.google.com/a/users/answer/9300311?hl=en&ref_topic=9296423" target="_blank">Get started with Sheets: Create and import files</a>, <a href="https://support.google.com/docs/answer/3540681?co=GENIE.Platform%3DDesktop&hl=en" target="_blank">Sort and filter your data</a>, <a href="https://support.google.com/docs/answer/46973?co=GENIE.Platform%3DDesktop&hl=en&oco=0" target="_blank">Edit and format a spreadsheet</a>.</li>
    <li><a href="https://support.google.com/a/users/answer/9331278?hl=en" target="_blank">Overview: Differences between Sheets and Excel</a>.</li>
  </ul>
</details>
  
---

### Formulas
A formula is a set of instructions that perform a specific calculation. Formulas are built on operators which are symbols that name that type of operation or calculation to be performed.

#### Cell reference
A cell reference is a single cell or range of cells in a worksheet that can be used in a formula. Cell references contain the letter of the column and the number of the row where the data is. A range of cells is a collection of two or more cells. A range can include cells from the same row or column, or from different columns and rows collected together. The great thing about using cell references is that they also automatically update when a formula is copied to a new cell. <br>

<details>
  <summary>Auto-filling</summary> <br>
  The lower-right corner of each cell has a fill handle. It is a small green square in Microsoft Excel and a small blue square in Google Sheets.
  <ul>
    <li>Click the fill handle for a cell and drag it down a column to auto-fill other cells in the column with the same value or formula in that cell. </li>
    <li>Click the fill handle for a cell and drag it across a row to auto-fill other cells in the row with the same value or formula in that cell. </li>
    <li>If you want to create a numbered sequence in a column or row, do the following: 1) Fill in the first two numbers of the sequence in two adjacent cells, 2) Select to highlight the cells, and 3) Drag the fill handle to the last cell to complete the sequence of numbers. For example, to insert 1 through 100 in each row of column A, enter 1 in cell A1 and 2 in cell A2. Then, select to highlight both cells, click the fill handle in cell A2, and drag it down to cell A100. This auto-fills the numbers sequentially so you don't have to type them in each cell.</li>
  </ul>
</details>

<details>
  <summary>Absolute referencing</summary> <br>
  <ul>
    <li>Absolute referencing is marked by a dollar sign ($). For example, =$A$10 has absolute referencing for both the column and the row value</li>
    <li>Relative references (which is what you normally do e.g. “=A10”) will change anytime the formula is copied and pasted. They are in relation to where the referenced cell is located. For example if you copied “=A10” to the cell to the right it would become “=B10”. With absolute referencing “=$A$10” copied to the cell to the right would remain “=$A$10”. But if you copied $A10 to the cell below, it would change to $A11 because the row value isn't an absolute reference.</li>
    <li>Absolute references will not change when you copy and paste the formula in a different cell. The cell being referenced is always the same.</li>
    <li>To easily switch between absolute and relative referencing in the formula bar, highlight the reference you want to change and press the F4 key; for example, if you want to change the absolute reference, $A$10, in your formula to a relative reference, A10, highlight $A$10 in the formula bar and then press the F4 key to make the change. </li>
  </ul>
</details>

<details>
  <summary>Data range</summary> <br>
  The set of cells a data analyst selects to include in a formula is called the data range.
  <ul>
    <li>When you click into your formula, the colored ranges let you see which cells are being used in your spreadsheet. There are different colors for each unique range in your formula.</li>
    <li>In a lot of spreadsheet applications, you can press the F2 (or Enter) key to highlight the range of data in the spreadsheet that is referenced in a formula. Click the cell with the formula, and then press the F2 (or Enter) key to highlight the data in your spreadsheet. </li>
  </ul>
</details>

<details>
  <summary>Combining with functions</summary> <br>
  <ul><li>COUNTIF() is a formula and a function. This means the function runs based on criteria set by the formula. In this case, COUNT is the formula; it will be executed IF the conditions you create are true. For example, you could use =COUNTIF(A1:A16, “7”) to count only the cells that contained the number 7. Combining formulas and functions allows you to do more work with a single command. </li></ul>
</details>

[**Spreadsheet errors and fixes**](https://d3c33hcgiwev3.cloudfront.net/fDHAQD8OQX6xwEA_DsF-tw_299c2bf89be04d0bae30bf763b606af1_DAC2-Spreadsheet-Errors-and-Fixes.pdf?Expires=1639958400&Signature=khlJhAOS7CarbwgvV-AGUp5XyXkMXYy5ssfw0te3fL7kR68rBLSv-1bafnENkYmL8F2cBpwz6fvGTkfifiI8pkkxlyi58m8PLWZXLpkAYP8zmwUbajS4LWLSJ-1wIzrRIGm6rGsKeBKDGN~QiZeuei2UlXpTt4~A5viTEuJIMzM_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

---

### Functions
A function is a preset command that automatically performs a specific process or task using the data.

**Difference between formulas and functions**
- A formula is a set of instructions used to perform a calculation using the data in a spreadsheet.
- A function is a preset command that automatically performs a specific process or task using the data in a spreadsheet.

<details>
  <summary>Relative, absolute, and mixed references</summary> <br>
  <ul>
    <li>Relative references (cells referenced without a dollar sign, like A2) will change when you copy and paste the function into a different cell. With relative references, the location of the cell that contains the function determines the cells used by the function. </li>
    <li>Absolute references (cells fully referenced with a dollar sign, like $A$2) will not change when you copy and paste the function into a different cell. With absolute references, the cells referenced always remain the same.</li>
    <li>Mixed references (cells partially referenced with a dollar sign, like $A2 or A$2) will change when you copy and paste the function into a different cell. With mixed references, the location of the cell that contains the function determines the cells used by the function, but only the row or column is relative (not both).   </li>
    <li>In spreadsheets, you can press the F4 key to toggle between relative, absolute, and mixed references in a function. Click the cell containing the function, highlight the referenced cells in the formula bar, and then press F4 to toggle between and select relative, absolute, or mixed referencing.  </li>
  </ul>
</details>

[DAC2 Keyboard functions 1](https://d3c33hcgiwev3.cloudfront.net/UbHnj9LnRlGx54_S5yZRJA_64a50a70b938476c852b172e826e9af1_DAC2-Keyboard-functions-1.pdf?Expires=1639958400&Signature=A2lNbKBH4jhT7PyaLm5SiV73QbYwRaY0s3e7EqwSRSE8hdxQAJKOdLY9zed3f2JMtAExTbPZtaPt2i8xRAqbDakzYJ6OwMp4sfsgE8tcThQ~M84UL~EZd8rqrtoVp1GQXfc66n5Pqo1gY9KPGv0WpX030AEHZHyyCDtBtst-bhE_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A), [DAC2 Keyboard functions 2](https://d3c33hcgiwev3.cloudfront.net/9gsOZ_tGTtOLDmf7Rh7T1Q_8a825edae2a94e5e81d880681270acf1_DAC2-Keyboard-functions-2.pdf?Expires=1639958400&Signature=VJUZw6DnuoBIGeqdafuH1OtvsD~g99yDHMWTHDl-rR2PWf9W14kcH9VJ1ktkfeVGkiSFX8TIfWCGHTCyDPtFPXOodtRrATIwzU1~FWunUxkKHZVXwmWdYHDYbNuED10hOXtBSVKAQoYISmWoyZHbM5Jlb0qUnGgHBH7VxUV8mw8_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A).

---

### Problem domain
The specific area of analysis that encompasses every activity affecting or affected by the problem.

Carefully defining a business problem can ultimately save time, money, and resources. All of this is achieved through structured thinking.

### Structured thinking
The process of recognizing the current problem or situation, organizing available information, revealing gaps and opportunities, and identifying the options.

The starting place for structured thinking is the problem domain. Once you know the specific area of analysis, you can set your base and lay out all your requirements and hypotheses before you start investigating.

You can practice structured thinking and avoid mistakes is by using a scope of work.

### Scope of work (SOW)
An agreed- upon outline of the work you're going to perform on a project. A scope of work is project-based and sets the expectations and boundaries of a project. A scope of work keeps everyone on the same page. Using structured thinking, you can define what is being delivered, when, and how you will measure success along the way.

There’s no standard format for an SOW. They may differ significantly from one organization to another, or from project to project. However, they all have a few foundational pieces of content in common: 
- **Deliverables** are items or tasks you will complete before you can finish the project. <br> What work is being done, and what things are being created as a result of this project? When the project is complete, what are you expected to deliver to the stakeholders? Be specific here. Will you collect data for this project? How much, or for how long?
- **Timelines** include due dates for when deliverables, milestones, and/or reports are due. <br> The timeline is a way of mapping expectations for how long each step of the process should take. The timeline should be specific enough to help all involved decide if a project is on schedule. When will the deliverables be completed? How long do you expect the project will take to complete? If all goes as planned, how long do you expect each component of the project will take? When can we expect to reach each milestone?
- **Milestones** are significant tasks you will confirm along your timeline to help everyone know the project is on track. <br> This is closely related to your timeline. What are the major milestones for progress in your project? How do you know when a given part of the project is considered complete? 
- **Reports** notify everyone as you finalize deliverables and meet milestones. <br> Good SOWs also set boundaries for how and when you’ll give status updates to stakeholders. How will you communicate progress with stakeholders and sponsors, and how often? Will progress be reported weekly? Monthly? When milestones are completed? What information will status reports contain?

![image](https://user-images.githubusercontent.com/74421758/146637082-0cc28c96-6c1d-4005-8d66-748e2d766f5c.png)

[Data Analysis Project Scope-of-Work (SOW) Strong Example](https://docs.google.com/document/d/16x-E04Nr48Ww1Nlxwa0PNOXyaytKbVCxrF5yRJy6Y70/template/preview?resourcekey=0-X1a531fuUVbtlNKdIA11dQ)

<br>

Usually, projects don’t start until an SOW is approved with its key pieces of content: the deliverables, milestones, timeline, and reports. To collect and synthesize this information, analysts identify and formalize quantifiable project requirements. They use structured thinking to ask clarifying questions, define what to accomplish, and specify project boundaries.

### Context
The condition in which something exists or happens. To avoid bias when collecting data, a data analyst should keep context in mind. Context can turn raw data into meaningful information. It is very important for data analysts to contextualize their data. This means giving the data perspective by defining it. To do this, you need to identify:
- **Who**: The person or organization that created, collected, and/or funded the data collection
- **What**: The things in the world that data could have an impact on
- **Where**: The origin of the data
- **When**: The time when the data was created or collected
- **Why**: The motivation behind the creation or collection
- **How**: The method used to create or collect it

To ensure your data is accurate and fair, make sure you start with an accurate representation of the population in the sample; collect the data in an objective way; and ask questions about the data.

---

[Glossary](https://docs.google.com/document/d/1v1_vAc7R81IK2JL4QTIbkUdHVYXnIvithZ_gC_k--jw/template/preview)

---
