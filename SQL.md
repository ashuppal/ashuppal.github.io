**SQL :Structured Query Language**

It is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. 

To retrieve data from a SQL database, we need to write **SELECT** statements, which are often colloquially refered to as queries. A query in itself is just a statement which declares what data we are looking for, where to find it in the database. We can add constraints to the query to get some specific data.
for e.g. we can use **WHERE** clause which is applied to each row of data by checking specific column values to determine whether it should be included in the results or not. We can also use different constrians like = , != or <>	, LIKE, NOT LIKE etc.

e.g  1.  SELECT title, year FROM movies
WHERE year BETWEEN 2000 AND 2010;
The above example will give us movies which are realesed between the year 2000 and 2010.
e.g. 2. SELECT title, director FROM movies 
WHERE director != "John Lasseter";
The above example will give us all the movies not directed by John Lasseter.

We can also filter and sort the data using SQL.
SQL provides a way to sort your results by a given column in ascending or descending order using the ORDER BY clause. When an ORDER BY clause is specified, each row is sorted alpha-numerically based on the specified column's value. In some databases, you can also specify a collation to better sort data containing international text.

e.g. SELECT title, year FROM movies
ORDER BY year DESC
LIMIT 4;;
The above example will give us the first five movies sorted alphabetically.

Multi-table queries with JOINs:

Tables that share information about a single entity need to have a primary key that identifies that entity uniquely across the database. 
Using the **JOIN** clause in a query, we can combine row data across two separate tables using this unique key.The INNER JOIN is a process that matches rows from the first table and the second table which have the same key to create a result row with the combined columns from both tables.
e.g. 
SELECT title, rating
FROM movies
  JOIN boxoffice
    ON movies.id = boxoffice.movie_id
ORDER BY rating DESC;
The above example wikk list all the movies by their ratings in descending order.

**Inserting rows**: When inserting data into a database, we need to use an INSERT statement, which declares which table to write into, the columns of data that we are filling, and one or more rows of data to insert.
e.g.
INSERT INTO movies VALUES (4, "Toy Story 4", "Ash", 2015, 90);
The above example will add the studio's new production, Toy Story 4 to the list of movies with "Ash" as a director.

**Updating rows**: We can update the data using **UPDATE** statment.
e.g.
UPDATE movies
SET year = 1999
WHERE id = 3;
The above example will update the year that Toy Story 2 which was incorrect: it will update it to year as 1999.

**Deleting rows** :When you need to delete data from a table in the database, you can use a DELETE statement, which describes the table to act on, and the rows of the table to delete through the WHERE clause.
e.g.
DELETE FROM movies
where year < 2005;
The above example will remove all movies that were released before 2005.

**Creating tables** When you have new entities and relationships to store in your database, you can create a new database table using the CREATE TABLE statement.
**Table data types** Different databases support different data types, but the common types support numeric, string, and other miscellaneous things like dates, booleans, or even binary data.
e.g.
CREATE TABLE Database (
    Name TEXT,
    Version FLOAT,
    Download_count INTEGER
);
The above example will create a new table named Database with the following columns:
– Name A string (text) describing the name of the database
– Version A number (floating point) of the latest version of this database
– Download_count An integer count of the number of times this database was downloaded




