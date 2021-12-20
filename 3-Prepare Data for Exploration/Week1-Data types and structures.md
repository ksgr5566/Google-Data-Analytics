### How data is collected
- Interviews, Observations(most often used by scientists), Forms, Questionnaires, Surveys, Cookies.

### Data collection considerations 
- How the data will be collected
  - Decide if you will collect the data using your own resources or receive (and possibly purchase it) from another party.
- Choose the data sources
  - **First-party data**: Data collected by an individual or group using their own resources. Collecting first-party data is typically the preferred method because you know exactly where it came from.
  - **Second-party data**: Data collected by a group directly from its audience and then sold.
  - **Third-party data**: Data collected from outside sources who did not collect it directly. This data might have come from a number of different sources before you investigated it. It might not be as reliable, but that doesn't mean it can't be useful.
  
  No matter what kind of data you use, it needs to be inspected for accuracy, bias, and credibility.
- Decide what data to use
  - Choosing the data that can help you find answers and solve problems and not getting distracted by other data.
- How much data to collect
  - A **population** refers to all possible data values in a certain data set.
  - In instances when collecting data from an entire population is challenging, data analysts may choose to use a sample. A **sample** is a part of a population that is representative of that population. 
- Select the right data type
- Determine the time frame
  - If you are collecting your own data, decide how long you will need to collect it, especially if you are tracking trends over a long period of time. If you need an immediate answer, you might not have time to collect new data. In this case, you would need to use historical data that already exists. 
![image](https://user-images.githubusercontent.com/74421758/146727002-6e8bad8d-0412-4597-aead-b9eeae3e989d.png)

---

<details>
  <summary><strong>Data formats</strong></summary> <br>

Primary | Secondary
------- | ---------
Collected by a researcher from first-hand sources | Gathered by other people or from other research
Examples: <ul><li>Data from an interview you conducted</li><li>Data from a survey returned from 20 participants</li><li>Data from questionnaires you got back from a group of workers</li></ul> | Examples: <ul><li>Data you bought from a local data analytics firm’s customer profiles</li><li>Demographic data collected by a university </li><li>Census data gathered by the federal government</li></ul>

Internal | External
-------- | --------
Data that lives inside a company’s own systems | Data that lives outside of a company or organization
Examples: <ul><li>Wages of employees across different business units tracked by HR</li><li>Sales data by store location </li><li>Product inventory levels across distribution centers</li></ul> | Examples: <ul><li>National average wages for the various positions throughout your organization</li><li>Credit reports for customers of an auto dealership</li></ul>

Continuous | Discrete
---------- | --------
Data that is measured and can have almost any numeric value | Data that is counted and has a limited number of values
Examples: <ul><li>Height of kids in third grade classes (52.5 inches, 65.7 inches)</li><li>Runtime markers in a video</li><li>Temperature</li></ul> | Examples: <ul><li>Number of people who visit a hospital on a daily basis (10, 20, 200)</li><li>Room’s maximum capacity allowed</li><li>Tickets sold in the current month</li></ul>

Qualitative | Quantitative
----------- | ------------
Subjective and explanatory measures of qualities and characteristics | Specific and objective measures of numerical facts
Examples: <ul><li>Exercise activity most enjoyed</li><li>Favorite brands of most loyal customers</li><li>Fashion preferences of young adults</li></ul> | Examples: <ul><li>Percentage of board certified doctors who are women</li><li>Population of elephants in Africa</li><li>Distance from Earth to Mars</li></ul>

Nominal | Ordinal
------- | -------
A type of qualitative data that isn’t categorized with a set order | A type of qualitative data with a set order or scale
Examples: <ul><li>First time customer, returning customer, regular customer</li><li>New job applicant, existing applicant, internal applicant</li><li>New listing, reduced price listing, foreclosure</li></ul> | Examples: <ul><li>Movie ratings (number of stars: 1 star, 2 stars, 3 stars)</li><li>Ranked-choice voting selections (1st, 2nd, 3rd)</li><li>Income level (low income, middle income, high income)</li></ul>

Structured | Unstructured
---------- | ------------
Data organized in a certain format, like rows and columns | Data that isn’t organized in any easily identifiable manner
Examples: <ul><li>Expense reports</li><li>Tax returns</li><li>Store inventory</li></ul> | Examples: <ul><li>Social media posts</li><li>Emails</li><li>Videos</li></ul>
  
![image](https://user-images.githubusercontent.com/74421758/146743810-7ab91e2b-9f6b-4954-9305-1db516d8aca3.png)

</details>

### Data modeling

<strong>Data modeling</strong> is the process of creating diagrams that visually represent how data is organized and structured. These visual representations are called data models. You can think of data modeling as a blueprint of a house. At any point, there might be electricians, carpenters, and plumbers using that blueprint. Each one of these builders has a different relationship to the blueprint, but they all need it to understand the overall structure of the house. Data models are similar; different users might have different data needs, but the data model gives them an understanding of the structure as a whole. 

Data model is a model that is used for organizing data elements and how they relate to one another. **Data elements** are pieces of information, such as people's names, account numbers, and addresses. Data models help to keep data consistent and provide a map of how data is organized. This makes it easier for analysts and other stakeholders to make sense of their data and use it for business purposes.

<details>
  <summary>Each level of data modeling has a different level of detail.</summary>
  <ol><li><strong>Conceptual data modeling</strong> gives a high-level view of the data structure, such as how data interacts across an organization. For example, a conceptual data model may be used to define the business requirements for a new database. A conceptual data model doesn't contain technical details.</li>

<li><strong>Logical data modeling</strong> focuses on the technical details of a database such as relationships, attributes, and entities. For example, a logical data model defines how individual records are uniquely identified in a database. But it doesn't spell out actual names of database tables. That's the job of a physical data model.</li>

<li><strong>Physical data modeling</strong> depicts how a database operates. A physical data model defines all entities and attributes used; for example, it includes table names, column names, and data types for the database.</li></ol>
</details>

<details><summary>Data-modeling techniques</summary>There are a lot of approaches when it comes to developing data models, but two common methods are the <strong>Entity Relationship Diagram (ERD)</strong> and the <strong>Unified Modeling Language (UML)</strong> diagram. ERDs are a visual way to understand the relationship between entities in the data model. UML diagrams are very detailed diagrams that describe the structure of a system by showing the system's entities, attributes, operations, and their relationships. As a junior data analyst, you will need to understand that there are different data modeling techniques, but in practice, you will probably be using your organization’s existing technique.</details> <br>

Data modeling can help you explore the high-level details of your data and how it is related across the organization’s information systems. Data modeling sometimes requires data analysis to understand how the data is put together; that way, you know how to map the data. And finally, data models make it easier for everyone in your organization to understand and collaborate with you on your data.

---
