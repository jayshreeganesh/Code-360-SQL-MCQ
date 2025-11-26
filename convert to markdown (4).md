<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# convert to markdown

Here is a markdown format representation of the solved MCQ quiz from your attached screenshots:

***

## DBMS \& SQL MCQs with Answers

### 1. Normal Form

**Question:**
Every constraint on the table is a logical consequence of the table's in DBMS.

**Options:**

- Fourth normal form
- Fifth normal form
- Domain/key normal form 🟩
- None of the Mentioned

**Answer:**
Domain/key normal form

**Explanation:**
A relation is in domain-key normal form (DK/NF) if every constraint on the relation is a logical consequence of the definition of keys and domains.[^1_1]

***

### 2. SQL Indexes

**Question:**
What is the purpose of an index?

**Options:**

- Sorts data
- Speeds up queries 🟩
- Joins tables
- Group data

**Answer:**
Speeds up queries

**Explanation:**
Indexes are used to speed up query processing.[^1_2]

***

### 3. Commands DDL

**Question:**
SQL has how many main commands for DDL:

**Options:**

- 1
- 2
- 3 🟩
- 4

**Answer:**
3

**Explanation:**
Create, Delete, Alter—these are 3 main commands.[^1_3]

***

### 4. Concurrent Access Explanation

**Question:**
What does concurrent access in a DBMS allow?

**Options:**

- Only one user can access the database at a time
- Multiple users can access the database simultaneously without conflicts 🟩
- Data is replicated across multiple databases for access
- The database can only handle small amounts of data

**Answer:**
Multiple users can access the database simultaneously without conflicts

**Explanation:**
DBMS supports concurrent data access, allowing multiple users to interact with the database at the same time without interfering with each other's actions.[^1_4]

***

### 5. DBMS Basics

**Question:**
Which of the following is true?

**Options:**

- Relation and table are same
- Attribute is column in table
- None of the above
- A and B both 🟩

**Answer:**
A and B both

**Explanation:**
For design purpose, table and relation mean the same, and the attributes and the column are also the same.[^1_5]

---

<div align="center">⁂</div>

[^1_1]: Screenshot-2025-09-29-195720.jpg

[^1_2]: Screenshot-2025-09-29-195618.jpg

[^1_3]: Screenshot-2025-09-29-195632.jpg

[^1_4]: Screenshot-2025-09-29-195648.jpg

[^1_5]: Screenshot-2025-09-29-195740.jpg


---

# convert to markdown

Here is a markdown format representation for each of the quiz questions from your second set of screenshots:

***

## DBMS \& SQL MCQs with Answers (Set 2)

### 1. Primary Key

**Question:**
What does a Primary Key enforce?

**Options:**

- Uniqueness and Null allowed
- Uniqueness and Not Null 🟩
- Only Not Null
- Only Uniqueness

**Answer:**
Uniqueness and Not Null

**Explanation:**
The Primary Key ensures each record in the table is unique and cannot be NULL.[^2_1]

***

### 2. Data Sharing

**Question:**
What do you mean by Data Sharing in DBMS?

**Options:**

- Same data visible to everyone 🟩
- Different data for everyone
- Multiple versions of data
- Anyone can access data

**Answer:**
Same data visible to everyone

**Explanation:**
In DBMS, data sharing refers to the act of sharing the same data resource with multiple applications or users, making the same information visible to everyone.[^2_2]

***

### 3. Key Update

**Question:**
Scenario: There are two tables Employee and Payment. The id of Employee acts as a foreign key for the Payment Table. If an employee's id needs updating across both tables, which option is correct?

**Options:**

- We cannot update the id of the employee
- We should update the correct value of id in the employee table only
- We should make sure that if we are updating the correct value of id in the Employee table, it should also get updated in another table referencing it (Payment table) so that the data remains consistent 🟩
- None of the above is correct

**Answer:**
Update id in both tables to maintain consistency

**Explanation:**
If updating the employee id, it must also be updated in all referencing tables (like Payment) to keep data consistent.[^2_3]

***

### 4. Relational Matching

**Question:**
Match the components of the relational model which are the same.


| Option | Match |
| :-- | :-- |
| a. Tuples | 3. Rows/Record |
| b. Column | 2. Field |
| c. Table | 1. Relation |

**Options:**

- a2 b1 c3
- a3 b2 c1 🟩
- a1 b3 c2
- a3 b1 c2

**Answer:**
a3 b2 c1

**Explanation:**
Tuples are equivalent to rows/records, columns to fields, and tables to relations in the relational model.[^2_4]

***

### 5. Functional Dependencies

**Question:**
Functional Dependencies are the types of constraints that are based on _____.

**Options:**

- Key 🟩
- Key revisted
- Superset key
- None of the mentioned

**Answer:**
Key

**Explanation:**
The key is the basic element needed for the constraints in functional dependencies.[^2_5]

---

<div align="center">⁂</div>

[^2_1]: Screenshot-2025-09-30-164808.jpg

[^2_2]: Screenshot-2025-09-30-164832.jpg

[^2_3]: Screenshot-2025-09-30-164945.jpg

[^2_4]: Screenshot-2025-09-30-164856.jpg

[^2_5]: Screenshot-2025-09-30-165008.jpg


---

# convert to markdown

Here is a markdown format representation for each of the quiz questions from your latest set of screenshots:

***

## DBMS \& SQL MCQs with Answers (Set 3)

### 1. Multi-level Indexing

**Question:**
Which of the following will be considered as multi-level indexing in Database?

**Options:**

- Clustering indexing
- Secondary indexing 🟩
- Primary Indexing
- All of them

**Answer:**
Secondary indexing

**Explanation:**
Secondary indexing, also known as multi-level indexing, is used when the size of the data file increases. It involves having a second level of indexing to speed up access and management of large tables.[^3_1]

***

### 2. SQL LIKE Operator

**Question:**
What is the purpose of LIKE in SQL?

**Options:**

- Compare exact values
- Pattern matching 🟩
- Sort data
- Group data

**Answer:**
Pattern matching

**Explanation:**
LIKE is used for pattern matching with wildcards, enabling flexible search conditions.[^3_2][^3_3]

***

### 3. Result Computation

**Question:**
In software architecture, which of the following is responsible for computing the result and returning it?

**Options:**

- Client
- Server 🟩

**Answer:**
Server

**Explanation:**
The server is responsible for all heavy computations and returning their result; the client merely displays them.[^3_4]

***

### 4. Sparse Indexing

**Question:**
Which of the following is true?

1. Sparse indices can be used only if the relation is stored in sorted order of the search key.
2. It is generally faster to locate a record if we have a dense index rather than a sparse index.

**Options:**

- Only 1
- Only 2
- None
- Both 1 and 2 🟩

**Answer:**
Both 1 and 2

**Explanation:**
Sparse indices work only when data is sorted, and dense indices provide faster access to records than sparse indices.[^3_5]

***

### 5. Safe Concurrency

**Question:**
Which of the following concurrency control protocols ensure both conflict serializability and freedom from deadlock?

**Options:**

- Timestamp ordering 🟩
- 2 Phase locking
- Both (a) and (b)
- None

**Answer:**
Timestamp ordering

**Explanation:**
Timestamp ordering ensures conflict serializability and is free from deadlocks because it does not rely on locking data items.[^3_6]

---

<div align="center">⁂</div>

[^3_1]: Screenshot-2025-10-01-214414.jpg

[^3_2]: Screenshot-2025-10-01-214343.jpg

[^3_3]: Screenshot-2025-10-01-214503.jpg

[^3_4]: Screenshot-2025-10-01-214355.jpg

[^3_5]: Screenshot-2025-10-01-214445.jpg

[^3_6]: Screenshot-2025-10-01-214334.jpg


---

# convert to markdown

Here is a markdown format representation for each of the quiz questions from your latest set of screenshots:

***

## DBMS \& SQL MCQs with Answers (Set 4)

### 1. SQL Constraints

**Question:**
What does a UNIQUE constraint enforce in SQL?

**Options:**

- NULL values
- Unique values 🟩
- Default values
- Grouping rows

**Answer:**
Unique values

**Explanation:**
A UNIQUE constraint ensures all values in a column are different.[^4_1]

***

### 2. Procedure Drop

**Question:**
In SQL, there exist multiple procedures for certain databases. To get rid of a particular procedure, which command is correct and avoids errors if the procedure is already removed?

**Options:**

- DELETE procedure name_of_SP;
- DELETE procedure [ IF EXISTS ] name_of_SP;
- DROP procedure [ IF EXISTS ] name_of_SP; 🟩
- DROP procedure name_of_SP;

**Answer:**
DROP procedure [ IF EXISTS ] name_of_SP;

**Explanation:**
The correct command is DROP procedure [ IF EXISTS ] name_of_SP; so that if the procedure is already removed, running the command doesn't throw an error.[^4_2]

***

### 3. Entity Subgrouping

**Question:**
The process of designating sub groupings within the entity set is called _______.

**Options:**

- Specialization 🟩
- Division
- Aggregation
- Finalization

**Answer:**
Specialization

**Explanation:**
In the ER Model, specialization is the procedure to split entities into further sub-entities based on functionality or features.[^4_3]

***

### 4. Types of FD

**Question:**
Which functional dependency type is/are not present in the following dependencies in DBMS?

**Empno -> EName, Salary, Deptno, DName**
**DeptNo -> DName**
**EmpNo -> DName**

**Options:**

- Full functional dependency
- Partial functional dependency 🟩
- Transitive functional dependency
- Both B and C

**Answer:**
Partial functional dependency

**Explanation:**
Partial functional dependency types
<span style="display:none">[^4_4][^4_5]</span>

<div align="center">⁂</div>

[^4_1]: Screenshot-2025-10-02-200327.jpg

[^4_2]: Screenshot-2025-10-02-200515.jpg

[^4_3]: Screenshot-2025-10-02-200424.jpg

[^4_4]: Screenshot-2025-10-02-200454.jpg

[^4_5]: Screenshot-2025-10-02-200357.jpg


---

# convert to markdown

Here is a markdown format representation for each quiz question from your latest screenshots:

***

## DBMS \& SQL MCQs with Answers (Set 5)

### 1. SQL Transactions

**Question:**
What does a transaction in SQL do?

**Options:**

- Joins tables
- Ensures data consistency 🟩
- Sorts data
- Groups data

**Answer:**
Ensures data consistency

**Explanation:**
A transaction ensures a sequence of SQL operations is completed successfully, maintaining data consistency.[^5_1]

***

### 2. Database Partitioning

**Question:**
Partitioning of the database is usually committed when:

**Options:**

- a. Dealing with huge dataset, which one server alone cannot handle.
- b. The requests to database access are taking longer time to be accepted i.e. long response time.
- c. Both (a) and (b) 🟩
- d. None of the Above

**Answer:**
Both (a) and (b)

**Explanation:**
Partitioning divides stored objects into servers for optimal performance—used with large datasets or slow access times.[^5_2]

***

### 3. Order By

**Question:**
If you don’t specify ASC or DESC after a SQL ORDER BY clause, the following is used by default _____

**Options:**

- ASC 🟩
- DESC
- There is no default value
- None of the mentioned

**Answer:**
ASC

**Explanation:**
ASC is the default sort order; null values are the lowest possible values.[^5_3]

***

### 4. Foreign Key

**Question:**
Identify the Foreign Key from table “Sales” in Database
(Table Client: ClientID is Primary Key, Table Sales: SalesID is Primary Key, ClientID, Profit)

**Options:**

- SalesID
- Profit
- Clientphone
- ClientID 🟩

**Answer:**
ClientID

**Explanation:**
ClientID is the foreign key in the Sales table, referencing ClientID in the Client table.[^5_4]

***

### 5. Hashing Techniques Comparison

**Question:**
What is an advantage of dynamic hashing over static hashing?

**Options:**

- It is simpler to implement for predictable data sizes.
- It avoids overflow buckets by adjusting the number of buckets dynamically. 🟩
- It uses fewer resources for data retrieval operations.
- It is ideal for datasets that remain constant in size.

**Answer:**
It avoids overflow buckets by adjusting the number of buckets dynamically.

**Explanation:**
Dynamic hashing expands/contracts the number of buckets as needed, making it efficient for unpredictable or growing datasets.[^5_5]

---

<div align="center">⁂</div>

[^5_1]: Screenshot-2025-10-03-134943.jpg

[^5_2]: Screenshot-2025-10-03-135100.jpg

[^5_3]: Screenshot-2025-10-03-135028.jpg

[^5_4]: Screenshot-2025-10-03-135016.jpg

[^5_5]: Screenshot-2025-10-03-134958.jpg


---

# convert to markdown

Here is a markdown format representation for each of the quiz questions from your latest set of screenshots:

***

## DBMS \& SQL MCQs with Answers (Set 5)

### 1. Type Constraint

**Question:**
In SQL, for an attribute "Aadhaar Number" which is defined as integer type, which constraint would be violated if we enter the PAN (has numbers and alphabets) in it?

**Options:**

- Entity Integrity constraint
- Key constraint
- Domain constraint 🟩
- Referential Integrity constraint

**Answer:**
Domain constraint

**Explanation:**
Domain integrity constraints restrict the value in particular attributes, defining which values are valid. Entering a PAN with alphabets into an integer-type column would violate the domain constraint.[^6_1]

***

### 2. JOIN Operations

**Question:**
What does an INNER JOIN return?

**Options:**

- All records from both tables
- Matching records from both tables 🟩
- Only unmatched records
- All records from one table

**Answer:**
Matching records from both tables

**Explanation:**
INNER JOIN returns rows where there is a match in both tables.[^6_2]

***

### 3. Constraint Violation

**Question:**
In the following table in Database, which integrity constraint is being violated?


| Book_name | Book_code | Book_price | Author_name | Publish_date |
| :-- | :-- | :-- | :-- | :-- |
| Physics-1 | 011 | 180 | Dr. Raj Nag | 21-03-1996 |
| Chemistry-1 | 021 | 200 | Dr. Kiran Sethi | 25-2-2001 |
| Maths-1 | 031 | 175 | Vipul Sen | 1-6-2006 |
| Grammar-1 | 021 | 150 | Dr. Jay | 11-6-2020 |

**Note:** Book_code is the primary key.

**Options:**

- Referential Integrity constraint
- Entity Integrity constraint 🟩
- Domain constraint
- None of the above

**Answer:**
Entity Integrity constraint

**Explanation:**
Book_code column has the value '021' for two different books; the primary key is not unique, violating entity integrity.[^6_3]

***

### 4. Transaction Permanency

**Question:**
Which ACID property ensures that once a transaction is committed, its changes are permanent, even in the event of a system crash?

**Options:**

- Atomicity
- Consistency
- Isolation
- Durability 🟩

**Answer:**
Durability

**Explanation:**
Durability guarantees that results of a committed transaction are permanently saved to the database.[^6_4]

***

### 5. Boyce code

**Question:**
In DBMS, which one of the following statements about normal forms is FALSE?

**Options:**

- Lossless, dependency-preserving decomposition into 3 NF is always possible
- BCNF is stricter than 3 NF
- Loss less, dependency–preserving decomposition into BCNF is always possible 🟩
- Any relation with two attributes is BCNF

**Answer:**
Loss less, dependency–preserving decomposition into BCNF is always possible

**Explanation:**
Lossless, dependency–preserving decomposition into BCNF is not always possible; this statement is false.[^6_5]

---

<div align="center">⁂</div>

[^6_1]: Screenshot-2025-10-04-154257.jpg

[^6_2]: Screenshot-2025-10-04-154129.jpg

[^6_3]: Screenshot-2025-10-04-154211.jpg

[^6_4]: Screenshot-2025-10-04-154238.jpg

[^6_5]: Screenshot-2025-10-04-154225.jpg


---

# convert to markdown

Here is a markdown format representation for each of the quiz questions from your latest set of screenshots:

***

## DBMS \& SQL MCQs with Answers (Set 6)

### 1. Functional Query

**Question:**
What is the meaning of LIKE '%0%0%' in SQL?

**Options:**

- Feature begins with two 0's
- Feature ends with two 0's
- Feature has more than two 0's
- Feature has two 0's anywhere 🟩

**Answer:**
Feature has two 0's anywhere

**Explanation:**
The LIKE operator is used in a WHERE clause to search for a specified pattern in a column. The pattern '%0%0%' matches any value containing two 0's anywhere in the string.[^7_1]

***

### 2. Query

**Question:**
SQL query to display all employees whose first names start with 'R' and end with 'I'.

**Options:**

- Only (c)
- Only (b)
- (b) and (d) 🟩
- (b), (c) and (d)
- (a) and (c)
- None of the above

**Details:**

- (a) SELECT * FROM Employee WHERE FirstName LIKE '%R%I%';
- (b) SELECT * FROM Employee WHERE FirstName LIKE 'R%' AND FirstName LIKE '%I';
- (c) SELECT * FROM Employee WHERE FirstName LIKE 'R' AND 'I';
- (d) SELECT * FROM Employee WHERE FirstName LIKE 'R%I';

**Answer:**
(b) and (d)

**Explanation:**
LIKE 'R%' finds names starting with R, LIKE '%I' finds names ending with I, and LIKE 'R%I' combines both. These queries accurately select employees whose first names start with R and end with I.[^7_2]

***

### 3. SQL DEFAULT Constraint

**Question:**
What does the DEFAULT constraint do?

**Options:**

- Sets a default value 🟩
- Ensures unique values
- Checks within a range
- Prevents NULL values

**Answer:**
Sets a default value

**Explanation:**
DEFAULT sets a default value for a column when no value is specified.[^7_3]

***

### 4. ER Mapping

**Question:**
Match the ER diagram components to their representation in the relational model.


|  | 1. Foreign key | 2. Relation | 3. Columns |
| :-- | :-- | :-- | :-- |
| a. Entity |  |  |  |
| b. Attribute |  |  |  |
| c. Relationship between entities |  |  |  |

**Options:**

- a1 b2 c3
- a2 b3 c1 🟩
- a2 b1 c3
- a3 b1 c2

**Answer:**
a2 b3 c1

**Explanation:**
Entity in ER diagram maps to relation in relational model, attributes to columns, and relationships between entities to foreign keys.[^7_4]

***

### 5. Null Restriction

**Question:**
What kind of anomaly might occur due to the restriction that null values are not allowed in the "Clubs" column when a new intern without a club affiliation is hired?

**Options:**

- Updation Anomaly
- Deletion Anomaly
- Insertion Anomaly 🟩
- None of the above

**Answer:**
Insertion Anomaly

**Explanation:**
A new employee without a club affiliation cannot be added to the database, resulting in insertion anomaly.[^7_5]

---
<span style="display:none">[^7_6]</span>

<div align="center">⁂</div>

[^7_1]: Screenshot-2025-10-05-110247.jpg

[^7_2]: Screenshot-2025-10-05-110337.jpg

[^7_3]: Screenshot-2025-10-05-105958.jpg

[^7_4]: Screenshot-2025-10-05-110046.jpg

[^7_5]: Screenshot-2025-10-05-110222.jpg

[^7_6]: Screenshot-2025-10-05-105318.jpg


---

# convert to markdown

Here is a markdown format representation for each of the quiz questions from your latest set of screenshots:

***

## DBMS \& SQL MCQs with Answers (Set 7)

### 1. Address Field

**Question:**
In DBMS, the address field of a person should not be part of the primary key, since it is likely to?

**Options:**

- Dependent
- Too long
- Changed 🟩
- Not changed

**Answer:**
Changed

**Explanation:**
The address field should not be part of the primary key because it is likely to change, violating primary key stability.[^8_1]

***

### 2. Data Modelling

**Question:**
Data modelling helps in achieving abstraction in DBMS.

**Options:**

- True 🟩
- False

**Answer:**
True

**Explanation:**
Abstraction means showing only what is required and hiding extra information, achieved through conceptual, representational, and physical data models.[^8_2]

***

### 3. Acid Property

**Question:**
The "all-or-none" property is commonly referred to as ________.

**Options:**

- Isolation
- Durability
- Atomicity 🟩
- None of the mentioned

**Answer:**
Atomicity

**Explanation:**
The all-or-none policy is atomicity, ensuring work is either fully completed or not at all, with no intermediate stages.[^8_3]

***

### 4. TCL Command

**Question:**
Which of the following are TCL commands in DBMS?

**Options:**

- UPDATE and TRUNCATE
- SELECT and INSERT
- GRANT and REVOKE
- ROLLBACK and SAVEPOINT 🟩

**Answer:**
ROLLBACK and SAVEPOINT

**Explanation:**
Transaction control commands manage changes made by DML commands; ROLLBACK and SAVEPOINT are used for managing transactional changes.[^8_4]

***

### 5. SQL BETWEEN Operator

**Question:**
What does the BETWEEN operator do in SQL?

**Options:**

- Joins tables
- Compares two values
- Checks within a range 🟩
- Groups data

**Answer:**
Checks within a range

**Explanation:**
BETWEEN checks if a value lies within a specified range.[^8_5]

---

<div align="center">⁂</div>

[^8_1]: Screenshot-2025-10-06-164650.jpg

[^8_2]: Screenshot-2025-10-06-164630.jpg

[^8_3]: Screenshot-2025-10-06-164701.jpg

[^8_4]: Screenshot-2025-10-06-164711.jpg

[^8_5]: Screenshot-2025-10-06-164619.jpg


---

# convert to markdown

Here is a markdown format representation for each of the quiz questions from your latest set of screenshots:

***

## DBMS \& SQL MCQs with Answers (Set 8)

### 1. SQL Foreign Key

**Question:**
What is the purpose of a Foreign Key in DBMS?

**Options:**

- Uniqueness
- Data integrity 🟩
- Data indexing
- Sort data

**Answer:**
Data integrity

**Explanation:**
Foreign Key enforces referential integrity between tables, ensuring that linked records remain consistent.[^9_1]

***

### 2. Attribute

**Question:**
In SQL, the attribute AGE is calculated from DATEOF BIRTH. The attribute AGE is...

**Options:**

- Single valued
- Multi-valued
- Composite
- Derived 🟩

**Answer:**
Derived

**Explanation:**
A derived attribute is calculated from the values of other attributes—AGE is derived from DATEOF BIRTH.[^9_2]

***

### 3. DBMS Basics

**Question:**
Which of the following is not True?

**Options:**

- DB and DBMS are the same 🟩
- Database stores data
- DBMS is a software
- All of the above

**Answer:**
DB and DBMS are the same

**Explanation:**
A database is a data store, while DBMS is a software to manage, retrieve, and manipulate the database.[^9_3]

***

### 4. Data Consistency Advantage

**Question:**
Which is a key advantage of DBMS over file systems regarding data consistency?

**Options:**

- File systems use better indexing techniques
- DBMS ensures consistent data by managing concurrent access 🟩
- File systems allow multiple users to access data simultaneously
- DBMS cannot handle concurrent data access

**Answer:**
DBMS ensures consistent data by managing concurrent access

**Explanation:**
DBMS can handle concurrent data access, providing consistent information to all users and avoiding anomalies.[^9_4]

***

### 5. Hash Index

**Question:**
The method of access that uses key transformation is known as ______

**Options:**

- Direct
- Hash 🟩
- Random
- Sequential

**Answer:**
Hash

**Explanation:**
Hashing transforms a key for efficient direct access to records, commonly used for index formation in DBMS.[^9_5]

---

<div align="center">⁂</div>

[^9_1]: Screenshot-2025-10-07-141316.jpg

[^9_2]: Screenshot-2025-10-07-141354.jpg

[^9_3]: Screenshot-2025-10-07-141421.jpg

[^9_4]: Screenshot-2025-10-07-141341.jpg

[^9_5]: Screenshot-2025-10-07-141437.jpg


---

# convert to markdown

Here is a markdown format representation for each quiz question from your latest screenshots:

***

## DBMS \& SQL MCQs with Answers (Set 9)

### 1. Intersect Operator

**Question:**
What is true regarding the intersect operator?

**Options:**

- INTERSECT operation returns rows from the combined queries and NOT NULL values.
- INTERSECT operation returns columns for the combined queries after eliminating duplicates.
- INTERSECT operation returns the common rows from the combined queries. 🟩
- INTERSECT keyword is available in MySQL.

**Answer:**
INTERSECT operation returns the common rows from the combined queries.

**Explanation:**
INTERSECT operation only returns the common rows in both queries after sorting them and removing duplicates.[^10_1]

***

### 2. Entity Relationships

**Question:**
In DBMS, an entity can be:

**Options:**

- Related to one entity only
- Related only to itself
- Related to two entities
- Related to many entities 🟩

**Answer:**
Related to many entities

**Explanation:**
An entity can be related to many different entities, including itself, in a database design.[^10_2]

***

### 3. SQL GROUP BY Clause

**Question:**
What is the purpose of GROUP BY?

**Options:**

- Filter rows
- Group rows 🟩
- Sort rows
- Join tables

**Answer:**
Group rows

**Explanation:**
GROUP BY groups rows that have the same values, allowing aggregate functions and meaningful analysis.[^10_3]

***

### 4. ER Basics 1

**Question:**
In the context of DBMS, the descriptive property possessed by each entity set is ________.

**Options:**

- Entity
- Attribute 🟩
- Relation
- Model

**Answer:**
Attribute

**Explanation:**
The descriptive property of each entity set is an attribute.[^10_4]

***

### 5. Subqueries-1

**Question:**
Suppose a user has 3 queries Q1, Q2, and Q3. These queries are written in a way i.e. Q1(Q2(Q3)). Which SQL query will be executed first?

**Options:**

- Q1
- Q2
- Q3 🟩
- All are updated at the same time

**Answer:**
Q3

**Explanation:**
In nested subqueries, the innermost query is executed first, so Q3 is executed before Q2 and Q1.[^10_5]

---

<div align="center">⁂</div>

[^10_1]: Screenshot-2025-10-08-020918.jpg

[^10_2]: Screenshot-2025-10-08-020848.jpg

[^10_3]: Screenshot-2025-10-08-020802.jpg

[^10_4]: Screenshot-2025-10-08-020837.jpg

[^10_5]: Screenshot-2025-10-08-020815.jpg


---

# convert to markdown

Here is the markdown format for your latest set of quiz screenshots:

***

## DBMS \& SQL MCQs with Answers (Set 10)

### 1. Relational Algebra

**Question:**
In the context of DBMS, relational algebra is:

**Options:**

- Non procedural query language
- High level language
- Procedural query language 🟩
- None of the above

**Answer:**
Procedural query language

**Explanation:**
Relational Algebra is a procedural query language where users specify the sequence of operations for the desired output.[^11_1]

***

### 2. SQL Delete

**Question:**
In SQL, _____ removes all rows from a table without logging the individual row deletions.

**Options:**

- DELETE
- REMOVE
- DROP
- TRUNCATE 🟩

**Answer:**
TRUNCATE

**Explanation:**
TRUNCATE is a DDL command that deallocates the data without logging individual row deletions.[^11_2]

***

### 3. Trivial Dependency (Venn diagram)

**Question:**
What is trivial functional dependency in DBMS?

**Options:**

- If A→B holds where B is not a subset of A.
- If A→B holds where B is a subset of A. 🟩
- If A→B holds where B is not an intersection of A.
- If A→B holds where B is an intersection of A.

**Answer:**
If A→B holds where B is a subset of A.

**Explanation:**
Trivial dependency is where dependent (B) is a subset of determinant (A). The diagram below shows this as B within A.[^11_3][^11_4][^11_5]

***

### 4. Index Components

**Question:**
In DBMS, the index consists of:

**Options:**

- list of keys
- pointers to the key in the table
- both (a) and (b) 🟩
- none

**Answer:**
both (a) and (b)

**Explanation:**
An index contains both a list of search keys and pointers to the data, improving access speed.[^11_6]

***

### 5. SQL COMMIT Statement

**Question:**
What does the COMMIT statement do?

**Options:**

- Reverts changes
- Saves changes 🟩
- Groups data
- Joins tables

**Answer:**
Saves changes

**Explanation:**
COMMIT saves all changes made during the transaction.[^11_2]

---

<div align="center">⁂</div>

[^11_1]: Screenshot-2025-10-09-164406.jpg

[^11_2]: Screenshot-2025-10-09-164458.jpg

[^11_3]: Screenshot-2025-10-09-164427.jpg

[^11_4]: Screenshot-2025-10-09-164440.jpg

[^11_5]: Screenshot-2025-10-09-164422.jpg

[^11_6]: Screenshot-2025-10-09-164333.jpg


---

# convert to markdown

Here is a markdown format representation for each of the quiz questions from your latest set of screenshots:

***

## DBMS \& SQL MCQs with Answers (Set 11)

### 1. Virtual Tables (Views)

**Question:**
Which of the following statement is true in DBMS?

**Options:**

- Views protect sensitive data
- Views compiled at runtime
- Views improve query speed
- All of the Mentioned 🟩

**Answer:**
All of the Mentioned

**Explanation:**
Views in DBMS can protect sensitive data, are compiled at runtime, and can improve query speed by encapsulating frequently used queries.[^12_1]

***

### 2. SQL INSERT Statement

**Question:**
What does the SQL INSERT statement do?

**Options:**

- Adds new data 🟩
- Deletes data
- Updates data
- Retrieves data

**Answer:**
Adds new data

**Explanation:**
INSERT adds new rows to a table.[^12_2]

***

### 3. ER Diagram

**Question:**
ER diagram represents which of the following data models?

**Options:**

- Conceptual 🟩
- Physical
- Logical
- Minimised

**Answer:**
Conceptual

**Explanation:**
ER diagrams are a part of conceptual design, identifying entities, relationships, and attributes.[^12_3]

***

### 4. Key Concepts

**Question:**
Which of the following is true?

**Options:**

- A candidate key is a minimal super key.
- Candidate keys which do not become primary keys are called alternate keys.
- Any candidate key can become a Primary key.
- All of the above 🟩

**Answer:**
All of the above

**Explanation:**
Candidate keys are minimal super keys; alternate keys are candidate keys not chosen as primary; any candidate may be picked as primary.[^12_4]

***

### 5. Storage Issue

**Question:**
What does same data being saved in multiple locations called?

**Options:**

- Inconsistency
- Redundancy 🟩
- Integrity
- Security

**Answer:**
Redundancy

**Explanation:**
Repeating the same data at different locations is redundancy, a common issue to manage in file-based systems.[^12_5]

---

<div align="center">⁂</div>

[^12_1]: Screenshot-2025-10-10-151227.jpg

[^12_2]: Screenshot-2025-10-10-151209.jpg

[^12_3]: Screenshot-2025-10-10-151311.jpg

[^12_4]: Screenshot-2025-10-10-151243.jpg

[^12_5]: Screenshot-2025-10-10-151259.jpg

