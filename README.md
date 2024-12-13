# Interview Questions

## SQL Questions
What are the 5 types of SQL statements?

SQL statements can be categorized into five main types:

**DDL** (Data Definition Language): Used to define or modify database structure (e.g., CREATE, ALTER, DROP).

**DML** (Data Manipulation Language): Used to manipulate data in tables (e.g., INSERT, UPDATE, DELETE).

**DQL** (Data Query Language): Used to query data from the database (e.g., SELECT).
  
**DCL** (Data Control Language): Used to control access to the database (e.g., GRANT, REVOKE).

**TCL** (Transaction Control Language): Used to manage transactions (e.g., COMMIT, ROLLBACK, SAVEPOINT).

Difference between primary key and a foreign key:
**Primary Key**:

Uniquely identifies each record in a table.
Cannot contain NULL values.
A table can have only one primary key.

**Foreign Key**:
A column (or set of columns) in one table that refers to the primary key in another table.
Establishes a relationship between two tables.
Can contain NULL values unless explicitly restricted.

Difference between WHERE and HAVING:

**WHERE**:
Filters rows before grouping or aggregation.
Cannot use aggregate functions.
Example: SELECT * FROM employees WHERE salary > 50000;

**HAVING**:
Filters groups after aggregation.
Can use aggregate functions.
Example: SELECT department, AVG(salary) FROM employees GROUP BY department HAVING AVG(salary) > 50000;
Difference between a UNION and a JOIN:

**UNION**:
Combines results from two or more SELECT statements into a single result set.
Removes duplicates unless UNION ALL is used.
Tables do not need to have a relationship.
Example:

![image](https://github.com/user-attachments/assets/b5a87b2e-305f-4f62-90b6-11d90329a87f)

**JOIN**:
Combines rows from two or more tables based on a related column.
Requires a relationship (e.g., primary and foreign keys).
Types: INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN.
Example:

![image](https://github.com/user-attachments/assets/c53dace1-b4b1-4d68-81d2-fc1b06273b29)

What is a trigger in SQL?
A trigger is a set of SQL statements automatically executed in response to certain events on a table (e.g., INSERT, UPDATE, DELETE).
Used to enforce business rules, audit changes, or maintain derived data.
Example:
![image](https://github.com/user-attachments/assets/8cccbd17-2747-48a9-bdfd-0263fe2b2b6d)


### Python Questions
How do you handle missing data in a dataset?

Drop rows/columns: Remove rows or columns with missing values if the impact is minimal.
Imputation: Fill missing values with:
Mean/Median/Mode for numerical data.
Forward/Backward fill for time-series data.
Predicted values using models.
Use algorithms that handle missing values: E.g., Decision Trees or KNN.
Mark missing data: Add a flag column indicating missingness.

Difference between supervised and unsupervised learning:
**Supervised Learning**:
Uses labeled data (input-output pairs).
Goal: Predict outputs for new inputs.
Examples: Classification, Regression.

**Unsupervised Learning**:
Uses unlabeled data.
Goal: Discover patterns or structure.
Examples: Clustering, Dimensionality Reduction.

How do you handle imbalanced datasets?
Resampling techniques:
Oversampling minority class (e.g., SMOTE).
Undersampling majority class.
Use class-weighted algorithms: Adjust weights to penalize misclassifications of the minority class.
Data augmentation: Generate synthetic data for the minority class.
Evaluation metrics: Use precision, recall, F1-score, or AUC instead of accuracy.

What is __init__() in Python?
A special method in Python classes called a constructor.
Automatically executed when an instance of the class is created.
Used to initialize instance attributes.

Example:

![image](https://github.com/user-attachments/assets/9e1e2d78-1249-40c6-b80d-cf6a23de44d4)


What is the difference between is and ==?
is:
Checks if two objects refer to the same memory location (identity). 

Example:

![image](https://github.com/user-attachments/assets/81cd82db-6353-432d-ac37-be6ba61fae6c)

==:
Checks if two objects have the same value (equality).

Example:

![image](https://github.com/user-attachments/assets/94b41094-00bb-4de2-9924-aece0ff7869c)

















