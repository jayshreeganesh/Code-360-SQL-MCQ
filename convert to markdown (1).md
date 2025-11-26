<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# convert to markdown

Here is the markdown conversion for your SQL MCQ screenshots, each presented with its question, selected answer, and brief explanation:

***

### Subqueries-1

**Question:**
Suppose a user has 3 queries Q1, Q2 and Q3. These queries are written in a way i.e. Q1(Q2(Q3)). Which SQL query will be executed first?

- Q1
- Q2
- **Q3** (selected)
- All are updated at the same time

**Explanation:**
Subqueries are executed from the innermost query outward. So Q3 is executed first.
![Subqueries MCQ Screenshot][^1_1]

***

### SQL UNION Operator

**Question:**
What does UNION do in SQL?

- Groups data
- Joins tables
- Filters data
- **Combines results of two queries** (selected)

**Explanation:**
UNION combines the results of two or more SELECT queries.
![SQL UNION Screenshot][^1_2]

***

### Functional Dependencies

**Question:**
Functional Dependencies are the types of constraints that are based on _____.

- Key revisited
- Superset key
- None of the mentioned
- **Key** (selected)

**Explanation:**
The key is the basic element needed for the constraints.
![Functional Dependencies Screenshot][^1_3]

***

### Procedure Lookup

**Question:**
Suppose you need to look out for the procedure containing the word "blog" (can be anywhere in the name), which command should be used in SQL:

- SHOW PROCEDURE STATUS WHERE db = 'blog';
- SHOW PROCEDURE STATUS LIKE '%blog%';
- SHOW PROCEDURE STATUS WHERE db LIKE '%blog%';
- **SHOW PROCEDURE STATUS LIKE '%blog%'** (selected)

**Explanation:**
To find procedures by part of their name, use SQL LIKE with wildcards.
![Procedure Lookup Screenshot][^1_4]

***

### Constraint Violation

**Question:**
In the following table in Database, which integrity constraint is being violated?

- Referential Integrity constraint
- Domain constraint
- None of the above
- **Entity Integrity constraint** (selected)

**Explanation:**
The Book_code column is the primary key but is not unique, violating the Entity Integrity Constraint.
![Constraint Violation Screenshot][^1_5]

---

<div align="center">⁂</div>

[^1_1]: Screenshot-2025-11-01-172823.jpg

[^1_2]: Screenshot-2025-11-01-172648.jpg

[^1_3]: Screenshot-2025-11-01-172742.jpg

[^1_4]: Screenshot-2025-11-01-172720.jpg

[^1_5]: Screenshot-2025-11-01-172804.jpg


---

# convert to markdown

Here is the markdown conversion for your SQL MCQ screenshots, including the question, selected answer, and a brief explanation for each:

***

### Transaction Permanency

**Question:**
Which ACID property ensures that once a transaction is committed, its changes are permanent, even in the event of a system crash?

- Atomicity
- Consistency
- Isolation
- **Durability** (selected)

**Explanation:**
Durability guarantees that the results of committed transactions are permanently saved, even if a crash occurs.
![Transaction Permanency Screenshot][^2_1]

***

### Index Drawbacks

**Question:**
Which of the following operations does indexing slow down in SQL?

1. DELETE
2. INSERT
3. SELECT
4. READ

- Only 1,3
- Only 2,4
- **Only 1,2** (selected)
- Only 1,2,4

**Explanation:**
Indexing reduces the speed of write operations like INSERT, UPDATE, and DELETE.
![Index Drawbacks Screenshot][^2_2]

***

### Data Fragmentation

**Question:**
Some of the columns of a relation are at different sites; in which SQL technique does this occur?

- Data Replication
- Horizontal Partitioning
- **Vertical Partitioning** (selected)
- Horizontal and Vertical Partitioning

**Explanation:**
Vertical partitioning distributes columns across different data sites or servers, while horizontal partitioning does so row-wise.
![Data Fragmentation Screenshot][^2_3]

***

### ER Diagram

**Question:**
ER diagram represents which of the following data models?

- Physical
- Logical
- Minimised
- **Conceptual** (selected)

**Explanation:**
ER diagrams are created as part of conceptual data design, identifying entities, relationships, and attributes.
![ER Diagram Screenshot][^2_4]

***

### SQL IN Operator

**Question:**
What does the IN operator do in SQL?

- Joins tables
- Filters data
- Groups data
- **Matches multiple values** (selected)

**Explanation:**
IN checks if a value matches any value in a specified list.
![SQL IN Operator Screenshot][^2_5]

---

<div align="center">⁂</div>

[^2_1]: Screenshot-2025-11-02-184347.jpg

[^2_2]: Screenshot-2025-11-02-184317.jpg

[^2_3]: Screenshot-2025-11-02-184215.jpg

[^2_4]: Screenshot-2025-11-02-184357.jpg

[^2_5]: Screenshot-2025-11-02-184150.jpg


---

# convert to markdown

Here is the markdown conversion for your MCQ screenshots, including each question, answers, and provided explanations:

***

### Projection

**Question:**
Which clause from the following corresponds to the projection operation of relational algebra?

- From
- **Select** (selected)
- Where
- None of these

**Explanation:**
The 'select' clause in SQL is analogous to the projection operation in relational algebra, as it chooses specific columns to display.
![Projection Screenshot][^3_1]

***

### Query Filter

**Question:**
In the context of a DBMS, which of the following should be used to list all names of the Book whose Book_price is less than 100 from relation 'Book'?

- σBook_name, Book_price<100(Book)
- **ΠBook_name(σBook_price<100(Book))** (selected)
- σBook_name(σBook_price<100(Book))
- ΠBook_price<100(Book)

**Explanation:**
Use the projection operator (Π) for column display after applying the selection (σ) for Book_price < 100.
![Query Filter Screenshot][^3_2]

***

### ER Basics 2

**Question:**
In DBMS, every weak entity set can be processed into a strong entity set by:

- Using generalization
- **Adding appropriate attributes** (selected)
- Using aggregation
- None of the above

**Explanation:**
Weak entity sets become strong entity sets when appropriate attributes are added.
![ER Basics 2 Screenshot][^3_3]

***

### Select Operation

**Question:**
For select operation the ______ appear in the subscript and the ______ argument appears in the parentheses after the sigma in SQL.

- **Predicates, relation** (selected)
- Relation, Predicates
- Operation, Predicates
- Relation, Operation

**Explanation:**
For selection, predicates are written as subscript and the relation is the argument in parentheses.
![Select Operation Screenshot][^3_4]

***

### SQL INNER JOIN

**Question:**
What does an INNER JOIN return in SQL?

- All records from both tables
- **Only matching records** (selected)
- Only unmatched records
- First table records

**Explanation:**
INNER JOIN returns only those rows that match in both tables.
![INNER JOIN Screenshot][^3_5]

---

<div align="center">⁂</div>

[^3_1]: Screenshot-2025-11-03-183302.jpg

[^3_2]: Screenshot-2025-11-03-183234.jpg

[^3_3]: Screenshot-2025-11-03-183249.jpg

[^3_4]: Screenshot-2025-11-03-183214.jpg

[^3_5]: Screenshot-2025-11-03-183151.jpg


---

# convert to markdown

Here is the markdown conversion for your MCQ screenshots, including each question, selected answer, and explanation:

***

### Replace vs Update

**Question:**
Choose the correct statement regarding replace and update in database.

- If the row which we want to replace is not present, replace will not do anything but update will add a new row.
- Update delete old data and then add new data while replace always makes changes in current data.
- **If the row is not present, replace will add a new row and update will not do anything.** (selected)
- Replace is faster than update because it always adds new data instead of making changes in existing one.

**Explanation:**
REPLACE adds new rows if they don't exist and updates old rows if they do. UPDATE only makes changes to existing rows and does nothing if the row is not present.
![Replace vs Update Screenshot][^4_1]

***

### Composite Key

**Question:**
In DBMS, a primary key is made up of two or more columns then it is called ______ primary key.

- Mixed
- **Composite** (selected)
- Reference
- Compost

**Explanation:**
A composite key consists of two or more columns used together as a primary key.
![Composite Key Screenshot][^4_2]

***

### SQL View

**Question:**
What is a view in SQL?

- A temporary table
- **A virtual table** (selected)
- A data type
- A physical table

**Explanation:**
A view is a virtual table created using a SQL query.
![SQL View Screenshot][^4_3]

***

### Dependency Rule

**Question:**
The rule which states that addition of same attributes to the right side and left side will result in other valid dependency in DBMS is classified as:

- Reflexive rule
- **Augmentation rule** (selected)
- Transitivity rule
- Sigma rule

**Explanation:**
The augmentation rule allows adding the same attributes to both sides of a functional dependency, resulting in a valid dependency.
![Dependency Rule Screenshot][^4_4]

***

### Index Ordering

**Question:**
In DBMS, when the records of the main table are sorted on the basis of search key which is also the primary key, and so is the order of the index table, it’s called:

- Secondary Indexing with key
- Clustered Indexing
- Secondary Indexing with non-key
- **Primary Indexing** (selected)

**Explanation:**
Primary indexing sorts and orders records by the primary key and organizes the index table accordingly.
![Index Ordering Screenshot][^4_5]

---

<div align="center">⁂</div>

[^4_1]: Screenshot-2025-11-04-211356.jpg

[^4_2]: Screenshot-2025-11-04-211236.jpg

[^4_3]: Screenshot-2025-11-04-211225.jpg

[^4_4]: Screenshot-2025-11-04-211314.jpg

[^4_5]: Screenshot-2025-11-04-211253.jpg


---

# convert to markdown

Here is the markdown conversion for your MCQ screenshots, including each question, selected answer, and explanation:

***

### File System

**Question:**
File System in which each teacher of a college is maintaining their separate files concerning the same subjects taught in the course would lead to:

- High data integrity
- **High data redundancy** (selected)
- High data security
- High efficiency to access data

**Explanation:**
When data about the same subjects is kept separately by each teacher, there will be multiple copies of the same data in different locations, resulting in high data redundancy.
![File System Screenshot][^5_1]

***

### SQL DROP Command

**Question:**
What does the DROP command do in SQL?

- Deletes data
- Modifies data
- **Deletes a table or database** (selected)
- Joins tables

**Explanation:**
DROP permanently removes a table or database from SQL.
![SQL DROP Command Screenshot][^5_2]

***

### Normal Form

**Question:**
Every constraint on the table is a logical consequence of the table's domain in DBMS.

- Fourth normal form
- Fifth normal form
- **Domain/key normal form** (selected)
- None of the mentioned

**Explanation:**
A relation is in domain-key normal form (DK/NF) if all constraints are a logical consequence of the key and domain definitions.
![Normal Form Screenshot][^5_3]

***

### SQL Database

**Question:**
SQL uses ______ format to store data.

- Key-value pairs
- Json object
- **Tables** (selected)
- Graphs

**Explanation:**
SQL is a relational database that stores data in tables, each made of rows and columns.
![SQL Database Screenshot][^5_4]

***

### Non Clustered Index

**Question:**
How do non clustered indexes point to the data?

- **Points to rows with key values** (selected)
- It never points to anything
- It points to a data row
- None of the mentioned

**Explanation:**
Non clustered indexes have pointers that refer to the data rows containing key values, and the index structure is kept separate from the actual data rows.
![Non Clustered Index Screenshot][^5_5]

---

<div align="center">⁂</div>

[^5_1]: Screenshot-2025-11-05-171506.jpg

[^5_2]: Screenshot-2025-11-05-171412.jpg

[^5_3]: Screenshot-2025-11-05-171426.jpg

[^5_4]: Screenshot-2025-11-05-171449.jpg

[^5_5]: Screenshot-2025-11-05-171438.jpg


---

# convert to markdown

Here is the markdown conversion for your MCQ screenshots:

***

### Transaction Mode

**Question:**
In DBMS, if a transaction has obtained a __________ lock, it can read but cannot write on the item.

- Exclusive mode
- Read only mode
- Write only mode
- **Shared mode** (selected)

**Explanation:**
A shared lock allows reading but not writing on the item.
![Transaction Mode Screenshot][^6_1]

***

### DBMS Basics

**Question:**
Which of the following is not true?

- **DB and DBMS are the same** (selected)
- Database stores data.
- DBMS is a software.
- All of the above.

**Explanation:**
Database stores data, while DBMS is a software used for database management. They are not the same.
![DBMS Basics Screenshot][^6_2]

***

### Limitation of View

**Question:**
Which of the following is not a limitation of view?

- ORDER BY Does Not Work
- Cross Database Queries Not Allowed in Indexed View
- Adding Column is Expensive by Joining Table Outside View
- **Index Created on View Used Often** (selected)

**Explanation:**
Views created on indexed columns are often used for performance optimization.
![Limitation of View Screenshot][^6_3]

***

### Handling Large Indexes

**Question:**
What happens when the first-level index in a database becomes too large?

- The system stops using indexes for searches.
- The first-level index is divided into smaller tables.
- The database automatically optimizes queries without using the index.
- **A second-level index is created to point to entries in the first-level index.** (selected)

**Explanation:**
A second-level index is created to point to entries in the first-level index for managing large datasets efficiently.
![Handling Large Indexes Screenshot][^6_4]

***

### SQL LIKE Operator

**Question:**
What is the purpose of LIKE in SQL?

- Compare exact values
- Sort data
- Group data
- **Pattern matching** (selected)

**Explanation:**
LIKE is used for pattern matching with wildcards in SQL.
![SQL LIKE Operator Screenshot][^6_5]

---

<div align="center">⁂</div>

[^6_1]: Screenshot-2025-11-06-172318.jpg

[^6_2]: Screenshot-2025-11-06-172256.jpg

[^6_3]: Screenshot-2025-11-06-172220.jpg

[^6_4]: Screenshot-2025-11-06-172232.jpg

[^6_5]: Screenshot-2025-11-06-172155.jpg


---

# convert to markdown

Here is the markdown conversion for your MCQ screenshots:

***

### Create User

**Question:**
Which command creates a new database user?

- **CREATE USER** (selected)
- CREATE LOGIN
- ADD USER
- MAKE USER

**Explanation:**
CREATE USER is used to create a new user account with specific privileges in SQL databases.
![Create User Screenshot][^7_1]

***

### SQL Indexes

**Question:**
What is the purpose of an index?

- Sorts data
- **Speeds up queries** (selected)
- Joins tables
- Group data

**Explanation:**
Indexes improve query speed by allowing faster data retrieval.
![SQL Indexes Screenshot][^7_2]

***

### Entity Subgrouping

**Question:**
The process of designating subgroupings within the entity set is called:

- **Specialization** (selected)
- Division
- Aggregation
- Finalization

**Explanation:**
Specialization divides entities into sub-entities based on functionalities or features, making sub-groups distinct.
![Entity Subgrouping Screenshot][^7_3]

***

### Query Processor Role

**Question:**
What is the role of the Query Processor in a DBMS?

- To manage data consistency during transactions
- To execute low-level database operations
- **To optimize and execute SQL queries** (selected)
- To store and retrieve data from the database

**Explanation:**
The query processor optimizes and executes SQL queries by converting high-level commands into low-level operations.
![Query Processor Role Screenshot][^7_4]

***

### Query

**Question:**
Given a table Employee (id, FirstName, LastName), choose the best SQL query to display employees whose first names start with 'R' and end with 'I'.

- Only (c)
- Only (b)
- **(b) and (d)** (selected)
- (b), (c), and (d)
- (a) and (c)
- None of the above

**Explanation:**
The queries (b) and (d) use the LIKE operator with '%' wildcard to filter names starting with 'R' and ending with 'I'.
![Query Screenshot][^7_5]

---

<div align="center">⁂</div>

[^7_1]: Screenshot-2025-11-07-113333.jpg

[^7_2]: Screenshot-2025-11-07-113212.jpg

[^7_3]: Screenshot-2025-11-07-113322.jpg

[^7_4]: Screenshot-2025-11-07-113229.jpg

[^7_5]: Screenshot-2025-11-07-113308.jpg


---

# convert to markdown

Here is the markdown conversion for your MCQ screenshots:

***

### Data Definition Language (DDL)

**Question:**
Which is a DDL command in SQL?

- SELECT
- UPDATE
- DELETE
- **CREATE** (selected)

**Explanation:**
CREATE is a DDL command used to create tables or databases.
![Data Definition Language Screenshot][^8_1]

***

### Graph Databases

**Question:**
Out of the following, for which situation a graph based database will be apt?

- Leaderboard for online games
- Content management
- Shopping cart at any online e-commerce website
- **Semantic Search** (selected)

**Explanation:**
Semantic search understands the intent and context of queries, making graph databases suitable for modeling relationships.
![Graph Databases Screenshot][^8_2]

***

### Key Relationship

**Question:**
In DBMS, a primary key with the help of foreign key creates a parent-child relationship between the tables that connect them.

- True (selected)
- False

**Explanation:**
Primary key referenced by a foreign key establishes referential integrity, creating parent-child relationships between tables.
![Key Relationship Screenshot][^8_3]

***

### Foreign Key1

**Question:**
Identify the Foreign Key from the table "Sales" in Database:

- SalesID
- Profit
- Clientphone
- **ClientID** (selected)

**Explanation:**
ClientID is a foreign key linking "Sales" and "Client" tables.
![Foreign Key1 Screenshot][^8_4]

***

### Hash Index

**Question:**
The method of access that uses key transformation is known as?

- Direct
- **Hash** (selected)
- Random
- Sequential

**Explanation:**
Hash indexing uses key transformations to efficiently access data.
![Hash Index Screenshot][^8_5]

---

<div align="center">⁂</div>

[^8_1]: Screenshot-2025-11-08-102717.jpg

[^8_2]: Screenshot-2025-11-08-102815.jpg

[^8_3]: Screenshot-2025-11-08-102756.jpg

[^8_4]: Screenshot-2025-11-08-102731.jpg

[^8_5]: Screenshot-2025-11-08-102742.jpg


---

# convert to markdown

Here is the markdown conversion for your latest MCQ screenshots:

***

### DDL

**Question:**
The result of compilation of the DDL statement is stored in a special file called as _____.

- Symbol Table
- Database File
- Database schema File
- **Data Dictionary** (selected)

**Explanation:**
The results of DDL statements are stored in the data dictionary.
![DDL Screenshot][^9_1]

***

### SQL DELETE Statement

**Question:**
What does the DELETE statement in SQL do?

- Retrieves data
- Modifies data
- Creates a table
- **Removes data** (selected)

**Explanation:**
DELETE removes rows from a table.
![SQL DELETE Statement Screenshot][^9_2]

***

### DBMS Efficiency Challenges

**Question:**
Which of the following is a potential performance issue of DBMS?

- It eliminates the need for data security measures
- It reduces the need for data normalization
- It enhances the speed of manual queries
- **It introduces performance overhead due to abstraction layers** (selected)

**Explanation:**
DBMS may introduce latency due to abstraction layers.
![DBMS Efficiency Challenges Screenshot][^9_3]

***

### Set Operators

**Question:**
In precedence of set operators, the expression is evaluated from _____.

- Left to left
- Right to left
- From user specification
- **Left to right** (selected)

**Explanation:**
Set operator expressions are evaluated from left to right by precedence.
![Set Operators Screenshot][^9_4]

***

### Type Constraint

**Question:**
In SQL, for an attribute "Adhaar Number" which is defined as integer type, which constraint would be violated if we enter the PAN (has numbers and alphabets) in it?

- Entity Integrity constraint
- Key constraint
- **Domain constraint** (selected)
- Referential Integrity constraint

**Explanation:**
A domain constraint restricts the value to the valid data type for the attribute.
![Type Constraint Screenshot][^9_5]

---

<div align="center">⁂</div>

[^9_1]: Screenshot-2025-11-09-180059.jpg

[^9_2]: Screenshot-2025-11-09-175955.jpg

[^9_3]: Screenshot-2025-11-09-180041.jpg

[^9_4]: Screenshot-2025-11-09-180013.jpg

[^9_5]: Screenshot-2025-11-09-180029.jpg


---

# convert to markdown

Here is the markdown conversion for your MCQ screenshots:

***

### Boyce Code (Normal Form)

**Question:**
In DBMS, which one of the following statements about normal forms is FALSE?

- Lossless, dependency-preserving decomposition into 3 NF is always possible.
- BCNF is stricter than 3 NF.
- **Lossless, dependency-preserving decomposition into BCNF is always possible.** (selected)
- Any relation with two attributes is BCNF.

**Explanation:**
It is NOT always possible to have both lossless and dependency-preserving decomposition into BCNF.
![Boyce Code Screenshot][^10_1]

***

### SQL BETWEEN Operator

**Question:**
What does the BETWEEN operator do in SQL?

- Joins tables
- Compares two values
- **Checks within a range** (selected)
- Groups data

**Explanation:**
BETWEEN checks if a value lies within a specified range.
![BETWEEN Operator Screenshot][^10_2]

***

### FD Relationship

**Question:**
In DBMS, a functional dependency is a relationship between or among _____.

- Entities
- Rows
- **Attributes** (selected)
- Tables

**Explanation:**
Functional dependency occurs among attributes.
![FD Relationship Screenshot][^10_3]

***

### Null Values

**Question:**
In DBMS, which of the following aggregate functions does not ignore null values?

- Max(attribute)
- Count(attribute)
- Min(attribute)
- **Count(*)** (selected)
- Both ii) and iv)
- Both i) and iii)

**Explanation:**
Count(*) includes null values, while other functions ignore them.
![Null Values Screenshot][^10_4]

***

### ORDER BY

**Question:**
If you don't specify ASC or DESC after a SQL ORDER BY clause, the following is used by default _____.

- **ASC** (selected)
- DESC
- There is no default value
- None of the mentioned

**Explanation:**
ASC (ascending) is the default sort order in SQL.
![ORDER BY Screenshot][^10_5]

---

<div align="center">⁂</div>

[^10_1]: Screenshot-2025-11-10-171712.jpg

[^10_2]: Screenshot-2025-11-10-171558.jpg

[^10_3]: Screenshot-2025-11-10-171638.jpg

[^10_4]: Screenshot-2025-11-10-171652.jpg

[^10_5]: Screenshot-2025-11-10-171619.jpg

