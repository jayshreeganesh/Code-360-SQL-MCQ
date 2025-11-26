<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# convert to markdown

Here is the content from your screenshots represented in Markdown format:

***

### Database Schema

**Problem Statement:**
In DBMS, database schema is part of which design process?

**Options:**

- Conceptual design
- **Logical design**
- Physical Design
- None of the above

**Solution Explanation:**
The database schema is the skeleton structure that demonstrates the logical view of the complete database, describing the organization of data and relations, and formulating conditions for the data.

***

### SQL DEFAULT Constraint

**Problem Statement:**
What does the DEFAULT constraint do?

**Options:**

- **Sets a default value**
- Ensures unique values
- Checks within a range
- Prevents NULL values

**Solution Explanation:**
DEFAULT sets a default value for a column when no value is specified.

***

### Relational Algebra

**Problem Statement:**
In the context of DBMS, relational algebra is:

**Options:**

- Non procedural query language
- High level language
- **Procedural query language**
- None of the above

**Solution Explanation:**
Relational Algebra is a procedural query language in which the user specifies the set of operations to be performed sequentially to get the desired output.

***

### Normalization

**Problem Statement:**
Which is a bottom-up approach to database design that examines the relationship between attributes?

**Options:**

- Functional dependency
- Database modeling
- **Normalization**
- Decomposition

**Solution Explanation:**
Normalization is the process of removing redundancy and unwanted data.

***

### Join Operations

**Problem Statement:**
Which of the join operations do not preserve non matched tuples in DBMS?

**Options:**

- Left outer join
- Right outer join
- **Inner join**
- Natural join

**Solution Explanation:**
INNER JOIN: Returns all rows when there is at least one match in BOTH tables.

***

This Markdown represents each question block as shown in your screenshots, with clear separation, options, and solution descriptions.
<span style="display:none">[^1_1][^1_2][^1_3][^1_4][^1_5]</span>

<div align="center">⁂</div>

[^1_1]: Screenshot-2025-10-21-202141.jpg

[^1_2]: Screenshot-2025-10-21-202017.jpg

[^1_3]: Screenshot-2025-10-21-202037.jpg

[^1_4]: Screenshot-2025-10-21-202124.jpg

[^1_5]: Screenshot-2025-10-21-202106.jpg


---

# convert to markdown

Here is the content from your new set of screenshots converted to Markdown format:

***

### Data Abstraction

**Problem Statement:**
Which of the following data models describes the database at the highest level in DBMS?

**Options:**

- **Conceptual data model**
- Physical data model
- Network data model
- Hierarchical data model

**Solution Explanation:**
A Conceptual Data Model describes high-level relationships between concepts/entities and helps organizations see their data and relationships between distinct data.

***

### SQL ROLLBACK Statement

**Problem Statement:**
What does ROLLBACK do in DBMS?

**Options:**

- Saves changes
- **Reverts changes**
- Joins tables
- Groups data

**Solution Explanation:**
ROLLBACK undoes all changes made during the transaction.

***

### Transactions

**Problem Statement:**
Collections of operations that form a single logical unit of work are called ________.

**Options:**

- Views
- Networks
- Units
- **Transactions**

**Solution Explanation:**
Collections of operations that form a single logical unit of work are called transactions. A database system must ensure the proper execution of the transaction.

***

### Null Restriction

**Problem Statement:**
Consider the following table:


| Employee_ID | Name | Department | Clubs |
| :--: | :--: | :--: | :--: |
| 1 | Navdeep | Content | Fitness Freaks |
| 2 | Shubhangi | Marketing | Marketing Club |
| 3 | Shubhangi | Marketing | Management Club |
| 4 | Gaurav | CIS | Technology Org. |
| 5 | Gaurav | CIS | Fitness Freaks |

While creating the database, the column “Clubs” was set so null values are not allowed. A new intern with no club affiliation cannot be added. What kind of anomaly might occur due to this restriction?

**Options:**

- Updation Anomaly
- Deletion Anomaly
- **Insertion Anomaly**
- None of the above

**Solution Explanation:**
A new employee without a club affiliation cannot be added into the database.

***

### Data Sharing

**Problem Statement:**
What do you mean by Data Sharing in DBMS?

**Options:**

- **Same data visible to everyone**
- Different data for everyone
- Multiple versions of data
- Anyone can access data

**Solution Explanation:**
Sharing the same data resource with multiple applications or users is known as data sharing. In DBMS, when the same information is visible to everyone, it is called data sharing.

***

This Markdown captures each MCQ question, options, and explanation from your screenshots in an organized format.
<span style="display:none">[^2_1][^2_2][^2_3][^2_4][^2_5]</span>

<div align="center">⁂</div>

[^2_1]: Screenshot-2025-10-22-161659.jpg

[^2_2]: Screenshot-2025-10-22-161534.jpg

[^2_3]: Screenshot-2025-10-22-161546.jpg

[^2_4]: Screenshot-2025-10-22-161626.jpg

[^2_5]: Screenshot-2025-10-22-161639.jpg


---

# convert to markdown

Here is the content from your latest set of screenshots in Markdown format:

***

### Relational Algebra

**Problem Statement:**
In DBMS, Relational Algebra does not have

**Options:**

- Selection operator
- Projection operator
- **Aggregation operator**
- Division operator

**Solution Explanation:**
Relational Algebra does not have an aggregator operator because it was designed as a set-based, foundational query language focused on basic operations. Aggregation functions like SUM, COUNT, and AVERAGE are more complex and were introduced in SQL to meet practical needs but are not part of the original framework.

***

### Aggregate

**Problem Statement:**
Find all the tuples having a temperature greater than 'Paris' in SQL.

**Options:**

- **SELECT * FROM weather WHERE temperature > (SELECT temperature FROM weather WHERE city = 'Paris')**
- SELECT * FROM weather WHERE temperature > (SELECT city FROM weather WHERE city = 'Paris')
- SELECT * FROM weather WHERE temperature > (SELECT * FROM weather WHERE city = 'Paris')
- SELECT * FROM weather WHERE temperature > 'Paris' temperature

**Solution Explanation:**
A subquery (inner query) is a SELECT statement embedded within another DML statement or nested within another subquery.

***

### Exclusive Mode

**Problem Statement:**
In DBMS, if a transaction has obtained a ______ lock, it can both read and write on the item.

**Options:**

- Shared mode
- **Exclusive mode**
- Read only mode
- Write only mode

**Solution Explanation:**
If a transaction has obtained an exclusive mode lock, it can both read and write on the item it is operating on.

***

### SQL NULL Handling

**Problem Statement:**
What is the IS NULL condition used for in SQL?

**Options:**

- Group data
- **Check for NULL values**
- Sort data
- Join tables

**Solution Explanation:**
IS NULL checks if a value is NULL.

***

### Dirty Read Example

**Problem Statement:**
Which of the following is an example of a dirty read in database transactions?

**Options:**

- **A transaction reads data that another transaction has not yet committed.**
- A transaction updates the same record as another transaction, overwriting changes.
- A transaction retrieves inconsistent results due to other transactions inserting or deleting rows.
- A transaction locks a table, preventing others from accessing it.

**Solution Explanation:**
A dirty read occurs when one transaction reads uncommitted changes made by another transaction. If changes are rolled back, the data read becomes invalid.

***

This Markdown accurately organizes each MCQ question, options, and solution explanations from your DBMS screenshots.
<span style="display:none">[^3_1][^3_2][^3_3][^3_4][^3_5]</span>

<div align="center">⁂</div>

[^3_1]: Screenshot-2025-10-23-184656.jpg

[^3_2]: Screenshot-2025-10-23-184709.jpg

[^3_3]: Screenshot-2025-10-23-184724.jpg

[^3_4]: Screenshot-2025-10-23-184618.jpg

[^3_5]: Screenshot-2025-10-23-184742.jpg


---

# convert to markdown

Here is the Markdown representation of your latest set of screenshots:

***

### Union of Primary Keys

**Problem Statement:**
The union of primary keys of the related entity sets becomes a ______ of the relation.

**Options:**

- **Super Key**
- Candidate key
- Foreign key
- Primary key

***

### Denormalization

**Problem Statement:**
Designers use which of the following to tune the performance of systems to support time-critical operations in DBMS?

**Options:**

- **Denormalization**
- Redundant optimization
- Optimization
- Realization

**Solution Explanation:**
Designers use denormalization to support time-critical operations in DBMS by reducing the number of joins and improving query performance.

***

### Virtual Tables

**Problem Statement:**
Which of the following statement is true in DBMS?

**Options:**

- Views protect sensitive data
- Views compiled at runtime
- Views improve query speed
- **All of the mentioned**

***

### SQL ORDER BY Clause

**Problem Statement:**
What is the purpose of ORDER BY?

**Options:**

- Join tables
- Filter data
- Group data
- **Sort data**

**Solution Explanation:**
ORDER BY sorts the result set in ascending or descending order.

***

### 1NF Requirements

**Problem Statement:**
In DBMS, which of the following is not required for a table to be in 1NF?

**Options:**

- Attributes to have unique names
- **Free from Transitive dependencies**
- Single valued attribute
- Each value in an attribute is of a similar type.

**Solution Explanation:**
To justify 1NF, a relation must have atomic values, values of the same type, unique attribute names, and order of data does not matter. Transitive dependencies are not required to be free for 1NF.

***

This Markdown summarizes each MCQ question, options, and selected/solution as shown in your screenshots.
<span style="display:none">[^4_1][^4_2][^4_3][^4_4][^4_5]</span>

<div align="center">⁂</div>

[^4_1]: Screenshot-2025-10-24-182303.jpg

[^4_2]: Screenshot-2025-10-24-182321.jpg

[^4_3]: Screenshot-2025-10-24-182332.jpg

[^4_4]: Screenshot-2025-10-24-182243.jpg

[^4_5]: Screenshot-2025-10-24-182358.jpg


---

# convert to markdown

Here is the Markdown representation for your latest screenshots:

***

### SQL UPDATE Statement

**Problem Statement:**
What does the SQL UPDATE statement do?

**Options:**

- Adds data
- Deletes data
- **Modifies data**
- Retrieves data

**Solution Explanation:**
UPDATE modifies existing records in a table.

***

### Key Update

**Problem Statement:**
There are two tables Employee and Payment. The id of the Employee Table acts as a foreign key for the Payment Table.

- If updating the correct value of id in the Employee table, what should be the correct course of action?

Employee Table:

```
id | Name    | gender | hire_date
101 | Bryan  | M      | 2015-08-26
102 | Joseph | M      | 2014-10-21
103 | Mike   | M      | 2017-10-28
104 | Daren  | M      | 2006-11-01
105 | Marie  | F      | 2018-10-12
```

Payment Table:

```
payment_id | id  | amount | payment_date
101        | 101 | 1200   | 2015-09-15
302        | 101 | 1200   | 2015-09-30
303        | 101 | 1500   | 2015-10-15
304        | 103 | 1800   | 2017-11-09
305        | 103 | 1800   | 2017-12-09
306        | 102 | 1500   | 2014-11-10
```

**Options:**

- We cannot update the id of the employee
- We should update the correct value of id in the employee table only
- **We should make sure that if we are updating the correct value of id in the Employee table, it should also get updated in another table referencing it (Payment table) so that the data remains consistent.**
- None of the above is correct

**Solution Explanation:**
If updating the id, update all references in related tables to maintain consistency.

***

### Incremental vs Full Backup

**Problem Statement:**
How does an incremental backup differ from a full backup?

**Options:**

- It includes a copy of all data and configurations.
- **It captures only the changes made since the last backup.**
- It requires more storage space than a full backup.
- It can only be performed once a week.

**Solution Explanation:**
Incremental backups save only the data changed since the last backup, reducing storage and speeding up the process.

***

### Session Storage

**Problem Statement:**
Which of the following databases is ideal for being used for User's session data retrieval?

**Options:**

- Columnar NoSQL database
- Graph based NoSQL database
- **Key-value NoSQL database**
- Document based NoSQL database

**Solution Explanation:**
Key-value stores are ideal for fast session data retrieval; unique IDs act as keys and user profiles as values.

***

### Read Lock

**Problem Statement:**
Which of the following is the query to apply Read Lock on table Employees in DBMS?

**Options:**

- **LOCK TABLE Employees READ;**
- LOCK TABLE Employees READ|WRITE;
- LOCK TABLE Employees PRIORITY READ;
- LOCK TABLE Employees READ ONLY;

**Solution Explanation:**
READ LOCK allows users to only read data. Syntax: LOCK TABLES T_name READ.

***

This Markdown organizes each MCQ question, options, and solution for your database concepts screenshots.
<span style="display:none">[^5_1][^5_2][^5_3][^5_4][^5_5]</span>

<div align="center">⁂</div>

[^5_1]: Screenshot-2025-10-25-155552.jpg

[^5_2]: Screenshot-2025-10-25-155728.jpg

[^5_3]: Screenshot-2025-10-25-155603.jpg

[^5_4]: Screenshot-2025-10-25-155618.jpg

[^5_5]: Screenshot-2025-10-25-155645.jpg


---

# convert to markdown

Here is the Markdown representation for your latest set of screenshots:

***

### Clustered Index

**Problem Statement:**
Which one is true about the clustered index?

**Options:**

- Not linked with table
- **Built on unique key by default**
- Not built on unique key
- None of the mentioned

**Solution Explanation:**
A clustered index is built by default on unique key columns. Nonclustered indexes have a structure separate from the data rows; each key-value entry points to the data row.

***

### SQL SELECT Statement

**Problem Statement:**
What does the SQL SELECT statement do?

**Options:**

- Deletes data
- Inserts data
- **Retrieves data**
- Updates data

**Solution Explanation:**
SELECT is used to retrieve data from a database.

***

### Table Properties

**Problem Statement:**
Which of the following is not a property of the table in DBMS?

**Options:**

- Every column should have unique name
- **An attribute can have multiple values for a row**
- Column values should be of same type
- Sequence of rows is insignificant

**Solution Explanation:**
A relation should contain atomic values, so multiple values for an attribute should be avoided.

***

### Concurrent Access Explanation

**Problem Statement:**
What does concurrent access in a DBMS allow?

**Options:**

- Only one user can access the database at a time
- **Multiple users can access the database simultaneously without conflicts**
- Data is replicated across multiple databases for access
- The database can only handle small amounts of data

**Solution Explanation:**
DBMS supports concurrent data access, allowing multiple users to access/interact with the database at the same time without interfering with each other's actions.

***

### Relational Model

**Problem Statement:**
In a relational model in DBMS, which of the following indicates the cardinality?

**Options:**

- Number of attributes
- Number of keys
- **Number of tuples**
- Number of relations

**Solution Explanation:**
In a relational model, cardinality refers to the number of tuples present in a relation or table.

***

This Markdown lists each MCQ question, available options, and solution explanation according to your screenshots.
<span style="display:none">[^6_1][^6_2][^6_3][^6_4][^6_5]</span>

<div align="center">⁂</div>

[^6_1]: Screenshot-2025-10-26-162236.jpg

[^6_2]: Screenshot-2025-10-26-162219.jpg

[^6_3]: Screenshot-2025-10-26-162305.jpg

[^6_4]: Screenshot-2025-10-26-162337.jpg

[^6_5]: Screenshot-2025-10-26-162322.jpg


---

# convert to markdown

Here is the Markdown representation for your latest screenshots:

***

### Higher Abstraction

**Problem Statement:**
In DBMS, which of the following is a type of abstraction in which entities with relationships come together to form higher level entity?

**Options:**

- Generalization
- Specialization
- **Aggregation**
- None of the above

**Solution Explanation:**
Aggregation is used to express a relationship among relationships—treating multiple entities as a single higher-level entity that can then have new relationships.

***

### Indexing Structure Basics

**Problem Statement:**
In a multi-level index, what does the first-level index typically point to?

**Options:**

- The entries in the second-level index.
- **The raw data blocks in the database.**
- The entries in the third-level index.
- The memory used by the database engine.

**Solution Explanation:**
The first-level index contains pointers to the blocks of raw data in the database table, enabling faster access to the actual data.

***

### Unary Operation

**Problem Statement:**
Which is a unary operation in database?

**Options:**

- Selection operation
- Primitive operation
- Projection operation
- **Generalized selection**

**Solution Explanation:**
Generalized selection takes only one argument for operation.

***

### Foreign Key

**Problem Statement:**
Which key links two tables in SQL?

**Options:**

- Primary Key
- **Foreign Key**
- Candidate Key
- Unique Key

**Solution Explanation:**
A foreign key in one table references a primary key in another, establishing their relationship.

***

### SQL Alias

**Problem Statement:**
What does an alias do in SQL?

**Options:**

- **Renames a column**
- Joins tables
- Sorts data
- Groups data

**Solution Explanation:**
Alias temporarily renames a column or table in the output.

***

This Markdown covers each MCQ with the question, options, and the selected answer/solution.
<span style="display:none">[^7_1][^7_2][^7_3][^7_4][^7_5]</span>

<div align="center">⁂</div>

[^7_1]: Screenshot-2025-10-27-181357.jpg

[^7_2]: Screenshot-2025-10-27-181302.jpg

[^7_3]: Screenshot-2025-10-27-181326.jpg

[^7_4]: Screenshot-2025-10-27-181339.jpg

[^7_5]: Screenshot-2025-10-27-181243.jpg


---

# convert to markdown

Here is the Markdown representation for your latest screenshots:

***

### Parameter Types

**Problem Statement:**
Which procedure parameter enables the caller to pass in a value and get back a value in DBMS?

**Options:**

- **INOUT**
- IN
- OUT
- GOINOUT

**Solution Explanation:**
The IN OUT parameter allows passing a value to a procedure and retrieving a value from it.

***

### SQL GROUP BY Clause

**Problem Statement:**
What is the purpose of GROUP BY?

**Options:**

- Filter rows
- **Group rows**
- Sort rows
- Join tables

**Solution Explanation:**
GROUP BY groups rows that have the same values.

***

### Deadlock in Databases

**Problem Statement:**
What is a deadlock in the context of database transactions?

**Options:**

- A situation where a transaction is terminated due to insufficient resources.
- **A state where multiple transactions are waiting for each other to release resources, causing a circular wait.**
- A condition where a transaction fails to acquire a lock due to high contention.
- A scenario where transactions complete successfully but with inconsistent data.

**Solution Explanation:**
A deadlock occurs when two or more transactions hold resources and simultaneously request resources held by each other, causing a circular wait.

***

### Storage Issue

**Problem Statement:**
What does same data being saved in multiple locations called?

**Options:**

- Inconsistency
- **Redundancy**
- Integrity
- Security

**Solution Explanation:**
Repeating the same data at different locations is called redundancy.

***

### Concurrency Control

**Problem Statement:**
In File based systems it is easy to maintain concurrency control when multiple users are updating the same file.

**Options:**

- True
- **False**

**Solution Explanation:**
Concurrency is not easy to achieve in file-based systems; it can lead to data integrity problems.

***

This Markdown reflects the questions, possible answers, and solutions captured in your screenshots.
<span style="display:none">[^8_1][^8_2][^8_3][^8_4][^8_5]</span>

<div align="center">⁂</div>

[^8_1]: Screenshot-2025-10-28-122957.jpg

[^8_2]: Screenshot-2025-10-28-122851.jpg

[^8_3]: Screenshot-2025-10-28-122941.jpg

[^8_4]: Screenshot-2025-10-28-122911.jpg

[^8_5]: Screenshot-2025-10-28-122927.jpg


---

# convert to markdown

Here is the Markdown representation for your latest screenshots:

***

### Join Condition

**Problem Statement:**
Which is a join condition that contains an equality operator?

**Options:**

- **Equijoin**
- Cartesian
- Natural
- Left

***

### TCL Command

**Problem Statement:**
Which of the following are TCL commands in DBMS?

**Options:**

- UPDATE and TRUNCATE
- SELECT and INSERT
- GRANT and REVOKE
- **ROLLBACK and SAVEPOINT**

**Solution Explanation:**
Transaction control commands (TCL) manage changes made by DML commands and are used to manage data-affecting changes.

***

### Schedules

**Problem Statement:**
In DBMS, the execution sequences in concurrency control are termed as ______.

**Options:**

- Serials
- **Schedules**
- Organizations
- Timetables

**Solution Explanation:**
The execution sequences in concurrency control are known as schedules.

***

### Procedure Alteration

**Problem Statement:**
Which of the following is a correct command if we have to alter an existing Stored Procedure in MySQL?

**Options:**

- ALTER PROCEDURE Sp1;
- ALTER PROCEDURE Sp1 ADD PARAMETER OUT w VARCHAR(10);
- ALTER PROCEDURE Sp1 ADD PARAMETER SET VALUE = DEFAULT;
- **Can't alter in MySQL, we must drop the procedure and create a new one.**

**Solution Explanation:**
MySQL does not allow direct procedure alteration. You must drop and recreate the procedure.

***

### SQL INSERT Statement

**Problem Statement:**
What does the SQL INSERT statement do?

**Options:**

- **Adds new data**
- Deletes data
- Updates data
- Retrieves data

**Solution Explanation:**
INSERT adds new rows to a table.

***

This Markdown covers each MCQ question, available answers, and the selected/solution for your screenshots.
<span style="display:none">[^9_1][^9_2][^9_3][^9_4][^9_5]</span>

<div align="center">⁂</div>

[^9_1]: Screenshot-2025-10-29-205919.jpg

[^9_2]: Screenshot-2025-10-29-205903.jpg

[^9_3]: Screenshot-2025-10-29-205936.jpg

[^9_4]: Screenshot-2025-10-29-205955.jpg

[^9_5]: Screenshot-2025-10-29-205853.jpg


---

# convert to markdown

Here is the Markdown version for your most recent screenshots:

***

### SQL Transactions

**Problem Statement:**
What does a transaction in SQL do?

**Options:**

- Joins tables
- **Ensures data consistency**
- Sorts data
- Groups data

**Solution Explanation:**
A transaction ensures a sequence of SQL operations is completed successfully.

***

### One to Many

**Problem Statement:**
In a one-to-many relationship, the entity that is on the one side of the relationship is called a ______ entity in DBMS.

**Options:**

- **Parent**
- Child
- Instance
- Subtype

**Solution Explanation:**
In a one-to-many relationship, the one side entity is called the parent entity.

***

### ER Diagram

**Problem Statement:**
Which of the following is not true for ER Diagram in DBMS?

**Options:**

- ER Diagram is a visual representation for ER model
- ER diagrams have three components: entities, relationships and attributes
- **ER diagram is not a high level data model diagram**
- All of the above

**Solution Explanation:**
ER Diagram is a high level data model diagram, which helps in designing the database components.

***

### DBMS Basics

**Problem Statement:**
Which of the following is true?

**Options:**

- Relation and table are same
- Attribute is column in table
- None of the above
- **A and B both**

**Solution Explanation:**
For design purposes, table and relation mean the same; attribute and column are also the same.

***

### Trivial Dependency

**Problem Statement:**
What is trivial functional dependency in DBMS?

**Options:**

- If A→B holds where B is not a subset of A.
- **If A→B holds where B is a subset of A.**
- If A→B holds where B is not an intersection of A.
- If A→B holds where B is an intersection of A.

**Solution Explanation:**
A trivial dependency occurs if the dependent set is a subset of the determinant.
![Trivial Dependency Venn Diagram][^10_1]

***

This Markdown covers the MCQs, answers, explanations, and the included Venn diagram for the trivial dependency concept.[^10_1]
<span style="display:none">[^10_2][^10_3][^10_4][^10_5][^10_6][^10_7]</span>

<div align="center">⁂</div>

[^10_1]: Screenshot-2025-10-30-145125.jpg

[^10_2]: Screenshot-2025-10-30-145350.jpg

[^10_3]: Screenshot-2025-10-30-145330.jpg

[^10_4]: Screenshot-2025-10-30-145143.jpg

[^10_5]: Screenshot-2025-10-30-145238.jpg

[^10_6]: Screenshot-2025-10-30-145217.jpg

[^10_7]: Screenshot-2025-10-30-145207.jpg


---

# convert to markdown

Here is the Markdown representation for your latest screenshots:

***

### Data Modelling

**Problem Statement:**
Data modelling helps in achieving abstraction in DBMS.

**Options:**

- **True**
- False

**Solution Explanation:**
Abstraction means showing only what is required and hiding extra information, achieved by data modelling (conceptual, representational, physical).

***

### DBMS Functionality

**Problem Statement:**
Which of the following best describes the primary function of a Database Management System (DBMS)?

**Options:**

- To only store data
- **To ensure efficient data retrieval and management**
- To convert data into flat files
- To enhance file system performance

**Solution Explanation:**
A DBMS helps in organizing, retrieving, and managing data effectively—beyond just storing data.

***

### Data Abstraction Principles

**Problem Statement:**
What is meant by data abstraction and independence in a DBMS?

**Options:**

- **Data is separated from the application logic, allowing changes without affecting applications**
- Data is physically stored in the same format as applications require
- Application logic cannot be changed without modifying the data structure
- Data is made accessible only to a specific group of users

**Solution Explanation:**
Data abstraction and independence mean the underlying data structure can change without affecting application programs, offering flexibility and maintenance ease.

***

### Drawback of DBMS

**Problem Statement:**
What is/are the drawback(s) of using DBMS?

**Options:**

- Requires training
- Complex to use
- It is costly
- **All of the above**

**Solution Explanation:**
DBMS requires training, is complex for non-technical users, and has high cost due to resource requirements.

***

### SQL Foreign Key

**Problem Statement:**
What is the purpose of a Foreign Key in DBMS?

**Options:**

- Uniqueness
- **Data integrity**
- Data indexing
- Sort data

**Solution Explanation:**
Foreign Key enforces referential integrity between tables.

***

This Markdown covers each MCQ, available options, and the solution/explanation for your screenshots.
<span style="display:none">[^11_1][^11_2][^11_3][^11_4][^11_5]</span>

<div align="center">⁂</div>

[^11_1]: Screenshot-2025-10-31-191203.jpg

[^11_2]: Screenshot-2025-10-31-191141.jpg

[^11_3]: Screenshot-2025-10-31-191129.jpg

[^11_4]: Screenshot-2025-10-31-191153.jpg

[^11_5]: Screenshot-2025-10-31-191115.jpg

