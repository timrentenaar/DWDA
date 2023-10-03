# Read me
This repository contains
- a cheat sheet that can be used during the midterm exam
- flashcard that can be used to memorize material for the midterm exam

If there is anything missing or incorrect please contact me.
Below is a study plan for the midterm.

# Midterm study plan

Here is a study plan for the midterm exam. This study plan includes reading material, exercise topics and flashcards for memorization. This study plan does not include a studying schedule, because this is something that differs from person to person.

### Reading material

- Lecture Slides
- DBSC: 1, 2.6, 3.2, 3.3-3.8, 4.4, 6.1, 6.2, 7.1-7.4.1
- MMDS: 3.1-3.5
- PDSH: 3
- DMCT: 3.1, 3.2, 3.3-3.5, 12.1-12.4
- R4DS: 3, 5, 7, (2.8)
- ISLR: 1, 2.1, 2.2, 3.1, 3.2, 3.3, 3.5, 5.1

### Practical exercises

Exercises can be found in the reading material, labs and external (online) sources. Exercises of the following topics can be practiced:

- SQL
    - Creating Tables
    - Inserting Records
    - Modifying and Deleting Tables
    - Delete Records based on condition
    - Update values of records based on condition
    - SELECT FROM WHERE
    - Using DISTINCT
    - Using ALL
    - SELECT literal without FROM clause
    - SELECT literal with FROM clause
    - SELECT AS
    - Calculations inside query
    - SELECT from multiple tables
    - Logical operators (AND, OR, NOT)
    - Comparison =, <>, <, >, <=, >=
    - SELECT FROM … AS
    - JOIN operator
    - LIKE operator
    - BETWEEN operator
    - Set operations: UNION, INTERSECT, EXCEPT
    - NULL
    - IN
    - Aggregate functions: avg, min, max, sum, count
    - GROUP BY
    - HAVING
    - Subqueries
    - Specify data type of an attribute
    - Specify primary key
    - Specify unique
    - Specify foreign keys
    - NO ACTION / CASCADE / SET NULL / SET DEFAULT
    - CHECK clause
    - NOT NULL constraint
- Relational algebra
    - Natural language query to relational algebra
    - Explaining relational algebra (relational algebra to natural language)
    - Relational algebra to SQL
    - SQL to Relational algebra
    - Natural Language query to SQL
    - Explaining SQL (SQL to natural language)
- Functional dependencies
    - Verify if a decomposition is lossless
    - Verify if a relation is in 1NF/2NF/3NF/BCNF
    - Find all functional dependencies from a given relation
    - Find superkey or candidate key
- Integrity Constraints
    - Identify the datatype of each attribute
    - Identify primary keys
    - Identify the foreign keys, identify from which relation they reference, identify to which relation they reference
    - Create a table with integrity constraints in SQL
    - Add a foreign key attribute referencing to a different relation
    - Identify the addition or deletion of records that breach integrity constraints
    - Identify the carnality of relationships between tables
- String similarity
    - Calculate Levenshtein distances between strings
        - deletion, insertion, substituion costs
    - Calculate Jaro similarity between strings
    - Calculate Jaro-Winkler similarity between strings
    - Soundex <- Not sure of any exercises but know the definition
- Set similarity
    - Calculate Jaccard similarity between sets
    - Calculate Jaccard distance between sets
    - Calculate Sørensen Coefficient between sets
    - Calculate Tversky Index between sets
    - Calculate Overlap Coefficient
- Shingling, MinHash, and LSH
    - Find the list of k-shingles from a document
    - Create a document-shingles matrix
    - Min-Hashing: create signature matrix from a set of permutations
    - Find similarity between documents using different set similarity techniques (e.g. Jaccard) from the document-shingles matrix
    - Find similarity between documents using different set similarity techniques (e.g. Jaccard) from the signature matrix
    - Locality Sensitive Hashing <- Not sure of any exercises but know the definition and its use
- Python pandas
    - Creating DataFrames from pandas series, data matrix, csv file, excel file
    - Load DataFrame from MySQL, PostgreSQL, SQLite
    - Extract rows and columns by index
    - Extract rows that satisfy specific condition
    - Display names, datatypes, (amount of) unique values, amount of missing values, aggregates of attributes
    - Display number of rows, columns
    - Concat and Merge of DataFrames
- Data preparation
    - Handling missing values (Deletion, Front Fill, Back Fill, Fill with standard value, Fill with mean/median)
    - Binning data
        - Smoothing (by mean / median / mode / boundary)
    - Outlier detection methods (Statistical / KNN / LOF)
    - Normalizing data (sum=1 / Min-max / Z-score / Decimal scaling)
    - Data reduction (Sampling (with and without replacement) / PCA)
- Data visualization
    - Different Aesthetics, Geoms, Scales, Facets, Transformations, Coordinate systems

### Memorization

Some key information can be memorized using the provided flashcards
