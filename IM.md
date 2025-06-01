# PRELIMS
1. refers to transformed data - [Information]
2. same data is stored unnecessarily - [Data Redundancy]
3. data about data in which end-user data is integrated - [Metadata]
4. characteristic of an entity - [Attribute]
5. data model is represented by an upside down tree - [Hierarchical Model]
6. type of database supports relatively small number of users - [Workgroup database]
7. type of database focuses primarily on storing historical data and business metrics used for tactical decision making - [Analytical Database]
8. overall design of a db - [db design]
9. raw facts that have not been processed - [data]
10. type of buildinbg block in data model refers to a place, thing, or event - [Entity]
11. type of db contains wide variety of data used in multiple discipline - [ General-purpose db]
12. represents global view of entire database by the org - [Conceptual Model]
13. collection of programs that manage the database structure - [DBMS]
14. data abnormality in which inconsistent changes have been made - [Data Anomaly]
15. type of db supports only 1 user at a time - [Single-user db]
16. represents the db as a collection of relations pertaining to tables with rows and cols - [Relational Model]
17. importance of db model - [can facilitate interaction among the designer, applications programmer, and end user]
18. Not true about SQL - [can create stored proedures]
19. Advantage of db - [Consumption]
20. characteristic of NoSQL - [high scalability, high availability, and fault tolerance]
21. SQL - [Structured Query Language]
22. major key or unique identifier of a tuple - [Primary key]
23. True about improved data access of BDSM - [produce quick answers to ad hoc queries]
24. implies that db design is not used often - []
25. uncontrolled data redundancy - [exists when conflicting data appear in different places]
26. multiuser db - [supports multiple users at the same time]
27. change in db schema affects data ac4ess and requires changes - [Structural Independence]
28. component that allows the user to retrieve update add and delete data in a db - [Data Manipulation Language]
29. correct syntax to create a table in the db - [CREATE TABLE tblFruit(INT PRIMARY KEY, item VARCHAR(10))]
30. field in one table whose values are constrained to be values of the primary key in another table - [Foreign Key]

#MIDTERM
1. process of assigning attributes to entities to minimize data redundancy - [Normalization]
2. 2D structure composed of rows and cols - [Table]
3. AKA row - [Tuple]
4. condition in which each row in a table has its own unique identity - [Entity Integrity]
5. Set of data about specific entity - [Row]
6. used to describe association among entities - [Relationship]
7. range of values in a column - [Domain]
8. rules in DB normalization - [Normal Forms]
9. ERD shape represents in entity - [Rectangle]
10. normal form considered highest level necessary - [Third NF]
11. undesirable consequence of data mod- [Data Anomaly]
12. table column represents - [Attribute]
13. Chen model, shape that represents relationship between entities - [Diamond]
14. Original Chen notation, shape for representing attributes - [Oval]
15. determine the values of other attributes - [Key]
16. how can EMP_ID be identified as primary key - [Underline it]
17. Not an objective of normalization - [each row has multiple values]
18. Crows Foot table, what is written above all the attributes - [Table Name]
19. Crows Foot, how can you mark the attrbtes that are required - [Write in boldface]
20. for eliminating repeating groups - [1NF]
22. does not cause data anomaly - [Search]
21. STUDENTS in number(STUDENTS) - [ROW]
23. best represents an entity - [Teacher]
24. combines the rows - [ABC U XYZ]
25. retrieves rows - [ABC n XYZ]
26. retrieves ABC rows that are not in XYZ - [ABC - XYZ]
27. EMP_MI in EMP_MI(EMployees) - [Column]
28. highest normal form - [4NF]
29. retrieves possible pairs - [ABC x XYZ]
30. functional dependence happen - [When the value of attributes determine the value of one or more other attributes]

PREFI
1. operator used with WHERE to check whether a value matches any value - [IN]
2. used to uniquely identify each row - [CHECK]
3. used with WHERE to determine whether a value matches a given string pattern - [BETWEEN]
4. used with SELECT to retrieve unique values from columns in a table - [DISTINCT]
5. used to delete an existing database - [DROP DATABASE]
6. ensures that a column cannot be empty upon creation - [NOT NULL]
7. used to modify the columns of an EXISTING table - [ALTER]
8. used to delete an EXISTING table - [DROP TABLE]
9. used with SELECT to determine whether a field is empty or not - [IS NULL]
10. used to uniquely identify a row in another table - [FOREIGN KEY]
11. used with WHERE to check whether a value is within a range - [BETWEEN]
12. S in SQL - Structured
13. ensures that all the vales in a column satisfy a specific condition upon creation - [CHECK]
14. sets a default value for a column when there is no value specified - [DEFAULT]
15. ensures that all the values in a column are different upon creation - [UNIQUE]
16. Not a basic manipulation command - [COPY]
17. NOT a logical operator - [DEFAULT]
18. creates a UNIQUE constraint - [ALTER TABLE Employee ADD UNIQUE(EmpNum)]
19. creates a CHECK constraint - [ALTER TABLE Employee ADD CHECK(Age >=16)]
20. creates a database - [CREAE DATABASE preDB]
21. NOT an SQL operator - SELECT
22. removes the record of employees under the Marketing dept. - [DELETE FROM Employees WHERE Dept = 'Marketing']
23. deletes the Age col from the Students table - [ALTER TABLE Students DROP COLUMN Age]
24. deletes a database named preDB - [DROP DATABASE preDB]
25. NOT a comparison Operator - [-]
26. NOT a compound Op - [<>]
27. removes all the records - [DELETE FROM Employee]
28. adds the Age col to the Students table - [ALTER TABLE Students ADD Age int]
29. retrieves unique values in the Age col - [SELECT DISTINCT Age FROM Employees]
30. approzimate numeric data type - [float]

FIN
## Aggregate Functions - [performs a calculation on a set of values and returns single value]

MIN
MAX
SUM
AVG
COUNT

[GROUP BY] - command option to group the result-set by one or more cols
[alias] - assign a temporary name

[HAVING] - used to restrict the output of a GROUP BY by applying conditional criteria 
 EX: SELECT columns FROM tableName GROUP BY columns HAVING condition

 # Date Functions
 [YEAR]- four digit year
 [Month] - number of the month
 [DAY] - number of the day

[GETDATE] - returns the current date and time
[DATEADD] - adds the number of selected time/date periods
[DATEDIFF] - returns the different between two dates

# Numeric Functions
[ABS] - absolute value
[ROUND] - rounds a number to a specified number of decimal
[CEIL]- returns the smallest integer that is greater than or equal to a number
[FLOOR] - returns the smallest integer that is greater than or equal to a number

# String dx/dy
[CONCAT] - joins 2 or more strings
[LEN] - number of chars in a string
[LOWER] - lowercase all string
[UPPER] - uppercase all string
[SUBSTRING] - returns a part of a string
[TRIM] - removes spaces


# JOINS
## combines rows from two or more tables
[INNER JOIN] - returns rows that have matching values in both tables
[LEFT JOIN] - returns rows from the left, if no match - result = NULL
[RIGHT JOIN] - returns rows from the right, if no match - result = NULL
[FULL JOIN] - returns all records when no match = NULL