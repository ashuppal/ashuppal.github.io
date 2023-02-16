### nosql vs sql

What type of database is the best fit for the complex query intensive environment?
SQL databases are good fit for the complex query intensive environment.

What type of database is the best fit for hierarchical data storage?
NoSQL database fits better for the hierarchical data storage

Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
SQL databases are vertically scalable, which means you can increase their capacity by adding more power to the server that runs them. In contrast, NoSQL databases are horizontally scalable, which means you can add more servers to handle more data as needed. 


### sql modeling techniques

Among data tables, what is a one-to-many relationship and how do we “relate” them?
We connect lines between tables to show relationships.  In some cases an entry in one table can be related to more than one entry in another.  This is called a one-to-many relationship.

Prior to designing your relational database, it might be useful to create diagrams of the database tables and their relationships.

Explain the difference between a primary and foreign key.
The primary keys uniquely identify each row in a table. Foreign Key – This is a column or set of columns which match a primary key in another table.

### sql vs nosql

How do we treat keywords and parameters differently in SQL syntax?
Keywords in SQL are not case sensitive. Parameters are used to provide input to the SQL statement dynamically,

Define normalization within the context of schemas and data.
The goal of normalized schemas is to avoid storage of duplicate data so that stored data can't become inconsistent. 

Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
One-to-one: A record in one table is related to one record in another table.
One-to-many: A record in one table is related to many records in another table. 
Many-to-many: Multiple records in one table are related to multiple records in another table.
