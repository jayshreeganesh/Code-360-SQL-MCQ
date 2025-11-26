<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# convert to markdown

Here is the conversion of your quiz screenshots into a Markdown-format question and answer set. Each problem, its options, answer, and explanation are presented clearly for study or documentation purposes.

***

## SQL COMMIT Statement

**Question:**
What does the COMMIT statement do?

- Reverts changes
- Saves changes ✅
- Groups data
- Joins tables

**Solution description:**
COMMIT saves all changes made during the transaction.
![Screenshot-2025-11-11-174406.jpg][^1_1]

***

## Two Phase Lock

**Question:**
In DBMS, the two-phase locking protocol consists of which of the following phases?

- Growing phase
- Shrinking phase
- More than one of the mentioned ✅
- None of the mentioned

**Solution description:**
The two-phased locking protocol consists of the growing phase and the shrinking phase.
![Screenshot-2025-11-11-174535.jpg][^1_2]

***

## Sparse Indexing

**Question:**
Which of the following is true?

1. Sparse indices can be used only if the relation is stored in sorted order of the search key.
2. It is generally faster to locate a record if we have a dense index rather than a sparse index.

- Only 1
- Only 2
- None
- Both 1 and 2 ✅

**Solution description:**
Sparse indices are smaller in size compared to dense indices and can only be used if the relation is sorted. Dense indices are generally faster for record location.
![Screenshot-2025-11-11-174501.jpg][^1_3]

***

## Update Ages

**Question:**
A University has the following dataset (id, name, age). The dataset was last updated 1 year ago; update ages accordingly.


| Id | Name | Age |
| :-- | :-- | :-- |
| 1 | Lawrence | 21 |
| 2 | Aniket | 18 |
| 3 | Carla | 25 |

- UPDATE * in University Age=Age+1;
- UPDATE University SET Age = Age+1; ✅
- UPDATE University SET ALL Age=Age+1;
- We cannot update all the rows at once.

**Solution description:**
Use `UPDATE University SET Age = Age + 1` to update all ages correctly.
![Screenshot-2025-11-11-174430.jpg][^1_4]

***

## Query Language

**Question:**
In DBMS, Relational algebra is:

- Data Definition Language
- Meta Language
- Procedural query language ✅

**Solution description:**
Relational algebra is a procedural query language using operations like selection, projection, and union to retrieve and manipulate data.
![Screenshot-2025-11-11-174514.jpg][^1_5]

---

<div align="center">⁂</div>

[^1_1]: Screenshot-2025-11-11-174406.jpg

[^1_2]: Screenshot-2025-11-11-174535.jpg

[^1_3]: Screenshot-2025-11-11-174501.jpg

[^1_4]: Screenshot-2025-11-11-174430.jpg

[^1_5]: Screenshot-2025-11-11-174514.jpg


---

# convert to markdown

Here is the Markdown-formatted version of your latest quiz questions and answers, with clear formatting for review and notes.

***

## SQL WHERE Clause

**Question:**
What is the purpose of the WHERE clause in SQL?

- Order data
- Filter data ✅
- Join tables
- Group data

**Solution description:**
WHERE is used to filter records in a query.
![Screenshot-2025-11-12-173407.jpg][^2_1]

***

## ER Basics 3

**Question:**
In DBMS, the E-R modeling technique is a:

- Top-down approach ✅
- Bottom-up approach
- Left-right approach
- None of the above

**Solution description:**
The E-R modeling technique is a top-down approach.
![Screenshot-2025-11-12-173419.jpg][^2_2]

***

## Semester Update

**Question:**
Which of the following is the most efficient way in SQL to update the current value of "Semester" attribute by 1, for all the rows of the table "Student"?

- Write 'n' update commands, if 'n' number of rows are present in the table.
- Instead of updating, insert all the records again in the table.
- Update Student SET Semester = Semester + 1; ✅
- We cannot update all the rows at once.

**Solution description:**
We can update all rows at once using `UPDATE Student SET Semester = Semester + 1`. No WHERE condition is needed for this operation.
![Screenshot-2025-11-12-173450.jpg][^2_3]

***

## Multi-level Indexing

**Question:**
Which of the following will be considered as multi-level indexing in Database?

- Clustering indexing
- Secondary indexing ✅
- Primary Indexing
- All of them

**Solution description:**
Secondary indexing is taken into consideration when the size of a data file increases and is also known as multi-level indexing.
![Screenshot-2025-11-12-173502.jpg][^2_4]

***

## Recursive Relation

**Question:**
In DBMS, a recursive relationship is a relationship between an entity and _____.

- itself ✅
- a subtype entity
- an archetype entity
- an instance entity

**Solution description:**
A recursive relationship links an entity to itself, such as an employee supervising another employee within the same entity set.
![Screenshot-2025-11-12-173433.jpg][^2_5]

---

<div align="center">⁂</div>

[^2_1]: Screenshot-2025-11-12-173407.jpg

[^2_2]: Screenshot-2025-11-12-173419.jpg

[^2_3]: Screenshot-2025-11-12-173450.jpg

[^2_4]: Screenshot-2025-11-12-173502.jpg

[^2_5]: Screenshot-2025-11-12-173433.jpg


---

# convert to markdown

Here is the Markdown-formatted version of your latest quiz questions and answers. Each entry contains the question, options, correct answer, a brief explanation, and the relevant screenshot.

***

## Multivalued Attribute

**Question:**
Which of these can be a multivalued attribute in DBMS?

- Phone_number ✅
- Name
- Date_of_birth
- All of the mentioned

**Solution description:**
Name and Date_of_birth cannot hold more than 1 value.
![Screenshot-2025-11-13-180047.jpg][^3_1]

***

## Primary Key

**Question:**
What does a Primary Key enforce?

- Uniqueness and Null allowed
- Uniqueness and Not Null ✅
- Only Not Null
- Only Uniqueness

**Solution description:**
The Primary Key ensures each record in the table is unique and cannot be NULL.
![Screenshot-2025-11-13-175930.jpg][^3_2]

***

## Key Concepts

**Question:**
Which of the following is true?

- A candidate key is a minimal super key.
- Candidate keys which do not become primary keys are called alternate keys.
- Any candidate key can become a Primary key.
- All of the above ✅

**Solution description:**
A candidate key is a minimal subset of super keys, no redundant attributes. Alternate keys are candidate keys not chosen as primary keys. Any candidate key can be selected as a primary key.
![Screenshot-2025-11-13-175950.jpg][^3_3]

***

## Transitivity Rule

**Question:**
Every time attribute A appears, it is matched with some value of attribute B, but not attribute C. Therefore, it is true that:

- A -> B ✅
- A -> C
- A -> (B, C)
- (B, C) -> A

**Solution description:**
Transitivity rule: If A -> B and B -> C hold, then A -> C also holds. A -> B is called "A functionally determines B."
![Screenshot-2025-11-13-180028.jpg][^3_4]

***

## Disaster Recovery

**Question:**
Most NoSQL databases support automatic ________, meaning you get high availability and disaster recovery.

- processing
- scalability
- replication ✅
- all of the mentioned

**Solution description:**
NoSQL databases are highly available due to auto-replication features, which helps with high availability and disaster recovery.
![Screenshot-2025-11-13-180007.jpg][^3_5]

---

<div align="center">⁂</div>

[^3_1]: Screenshot-2025-11-13-180047.jpg

[^3_2]: Screenshot-2025-11-13-175930.jpg

[^3_3]: Screenshot-2025-11-13-175950.jpg

[^3_4]: Screenshot-2025-11-13-180028.jpg

[^3_5]: Screenshot-2025-11-13-180007.jpg


---

# convert to markdown

Here is the Markdown version of your latest quiz questions and answers:

***

## SQL: LIKE Operator

**Question:**
What is the meaning of LIKE '%00%' in SQL?

- Feature begins with two 0's
- Feature ends with two 0's
- Feature has more than two 0's
- Feature has two 0's anywhere ✅

**Solution description:**
The LIKE operator is used in a WHERE clause to search for a specified pattern in a column.
![Screenshot-2025-11-14-153410.jpg][^4_1]

***

## SQL Aggregate Functions

**Question:**
What does the COUNT function do in SQL?

- Counts rows ✅
- Counts columns
- Adds values
- Finds the max value

**Solution description:**
COUNT returns the number of rows in a query.
![Screenshot-2025-11-14-153234.jpg][^4_2]

***

## Database Partitioning

**Question:**
Partitioning of the database is usually committed when:

- a. Dealing with huge dataset, which one server alone cannot handle.
- b. The requests to database access are taking longer time to be accepted i.e. long response time.
- c. Both (a) and (b) ✅
- d. None of the Above

**Solution description:**
Partitioning is committed when dealing with a huge dataset or requests are taking more time than expected, improving performance and management.
![Screenshot-2025-11-14-153308.jpg][^4_3]

***

## Isolation (DBMS)

**Question:**
Execution of translation in isolation preserves the _________ of a database.

- Atomicity
- Consistency ✅
- Durability
- All of the mentioned

**Solution description:**
Execution of translation in isolation preserves the consistency of a database, ensuring no other transaction is running concurrently.
![Screenshot-2025-11-14-153253.jpg][^4_4]

***

## SQL: Intersect Operator

**Question:**
What is true regarding the intersect operator?

- INTERSECT operation returns rows from the combined queries and NOT NULL values.
- INTERSECT operation returns columns for the combined queries after eliminating duplicates.
- INTERSECT operation returns the common rows from the combined queries. ✅
- INTERSECT keyword is available in MySQL.

**Solution description:**
INTERSECT operation returns only common rows in both queries after sorting them and removing duplicates.
![Screenshot-2025-11-14-153329.jpg][^4_5]

---

<div align="center">⁂</div>

[^4_1]: Screenshot-2025-11-14-153410.jpg

[^4_2]: Screenshot-2025-11-14-153234.jpg

[^4_3]: Screenshot-2025-11-14-153308.jpg

[^4_4]: Screenshot-2025-11-14-153253.jpg

[^4_5]: Screenshot-2025-11-14-153329.jpg


---

# convert to markdown

Here is the Markdown-formatted version of your quiz questions and answers with the corresponding screenshots:

***

## Hashed File

**Question:**
The physical location of a record is determined by a mathematical formula that transforms a file key into a record location is:

- B-Tree File
- Hashed File ✅
- Indexed File
- Sequential file

**Solution description:**
Hashed File uses a formula to transform a key into a record location.
![Screenshot-2025-11-16-204633.jpg][^5_1]

***

## CRUD Operations

**Question:**
What does R refer to in CRUD operations in DBMS?

- Replicate
- Read ✅
- Redundant
- Replace

**Solution description:**
R in CRUD stands for Read, typically accomplished using the SELECT statement in SQL.
![Screenshot-2025-11-16-204652.jpg][^5_2]

***

## Unary Operation (Relational Algebra)

**Question:**
In DBMS context, which of the following is not a valid unary operation in relational algebra?

- Select
- Min ✅
- Project
- Rename

**Solution description:**
Min is not a valid unary operation in relational algebra.
![Screenshot-2025-11-16-204618.jpg][^5_3]

***

## Many-to-Many Relationship

**Question:**
In DBMS, a many-to-many relationship between two entities usually results in how many tables?

- ONE
- TWO
- THREE ✅
- FOUR

**Solution description:**
A many-to-many relationship usually results in three tables.
![Screenshot-2025-11-16-204712.jpg][^5_4]

***

## SQL TRUNCATE Command

**Question:**
What does the TRUNCATE command do?

- Deletes a table
- Removes all rows ✅
- Modifies table structure
- Sorts data

**Solution description:**
TRUNCATE removes all rows from a table but retains the table structure.
![Screenshot-2025-11-16-204603.jpg][^5_5]

---

<div align="center">⁂</div>

[^5_1]: Screenshot-2025-11-16-204633.jpg

[^5_2]: Screenshot-2025-11-16-204652.jpg

[^5_3]: Screenshot-2025-11-16-204618.jpg

[^5_4]: Screenshot-2025-11-16-204712.jpg

[^5_5]: Screenshot-2025-11-16-204603.jpg


---

# convert to markdown

Here is the Markdown-formatted version of your quiz questions and answers with screenshots:

***

## Selection Operation

**Question:**
Which of the following is used to denote the selection operation in relational algebra in DBMS?

- Pi (Greek)
- Sigma (Greek) ✅
- Lambda (Greek)
- Omega (Greek)

**Solution description:**
The select operation picks tuples that satisfy a given predicate.
![Screenshot-2025-11-17-181638.jpg][^6_1]

***

## Primary Key

**Question:**
In DBMS, a primary key should be:

- Null
- Not null
- Unique
- Unique and not Null ✅

**Solution description:**
A primary key uniquely identifies each tuple, cannot be null, and is selected from candidate keys.
![Screenshot-2025-11-17-181648.jpg][^6_2]

***

## SQL Table Deletion

**Question:**
In SQL, _____ removes all rows from a table without logging the individual row deletions.

- DELETE
- REMOVE
- DROP
- TRUNCATE ✅

**Solution description:**
TRUNCATE removes all rows but keeps the table structure; it is a Data Definition Language (DDL) operation.
![Screenshot-2025-11-17-181627.jpg][^6_3]

---

<div align="center">⁂</div>

[^6_1]: Screenshot-2025-11-17-181638.jpg

[^6_2]: Screenshot-2025-11-17-181648.jpg

[^6_3]: Screenshot-2025-11-17-181627.jpg

