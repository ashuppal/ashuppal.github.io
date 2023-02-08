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

**Altering tables** SQL provides a way for you to update your corresponding tables and database schemas by using the ALTER TABLE statement to add, remove, or modify columns and table constraints.
e.g.
ALTER TABLE Movies
  ADD COLUMN Aspect_ratio FLOAT DEFAULT 2.39;
The above example will add a column named Aspect_ratio with a FLOAT data type to store the aspect-ratio each movie was released in.

**Dropping tables** In some rare cases, you may want to remove an entire table including all of its data and metadata, and to do so, you can use the DROP TABLE statement.
e.g.
DROP TABLE Movies;
The above example will remove the movies table.

<img width="374" alt="Screen Shot 2023-02-08 at 11 01 18 AM" src="https://user-images.githubusercontent.com/90730785/217627046-5eb2f93b-4478-448d-a01c-f9b2a5fbe3e6.png">
<img width="376" alt="Screen Shot 2023-02-08 at 11 01 04 AM" src="https://user-images.githubusercontent.com/90730785/217627104-c0763b50-5511-4680-ac25-751df49b8e13.png">
<img width="373" alt="Screen Shot 2023-02-08 at 11 00 52 AM" src="https://user-images.githubusercontent.com/90730785/217627121-82458e80-da5e-4541-a6d8-f9c147c1f8ab.png">
<img width="378" alt="Screen Shot 2023-02-08 at 11 00 11 AM" src="https://user-images.githubusercontent.com/90730785/217627141-1411a20d-568e-4fad-ac2f-60ecc400f5fe.png">
<img width="379" alt="Screen Shot 2023-02-08 at 10 59 55 AM" src="https://user-images.githubusercontent.com/90730785/217627161-f022c4a9-531f-4f49-92b2-2eaaafefee6d.png">
<img width="384" alt="Screen Shot 2023-02-08 at 10 59 37 AM" src="https://user-images.githubusercontent.com/90730785/217627191-d1fbe44b-93cd-4d62-85b8-b267878cc10c.png">
<img width="375" alt="Screen Shot 2023-02-08 at 10 59 07 AM" src="https://user-images.githubusercontent.com/90730785/217627206-85bcaceb-0ccc-49f2-bd61-2f444463d2b9.png">
<img width="374" alt="Screen Shot 2023-02-08 at 10 58 55 AM" src="https://user-images.githubusercontent.com/90730785/217627218-d67e5457-b895-40de-840e-0466d62e5fa5.png">
<img width="372" alt="Screen Shot 2023-02-08 at 10 58 25 AM" src="https://user-images.githubusercontent.com/90730785/217627237-f8825c36-d5bf-4cbe-ab19-a030758be1e9.png">
<img width="372" alt="Screen Shot 2023-02-08 at 10 58 05 AM" src="https://user-images.githubusercontent.com/90730785/217627254-d4d7de3a-8f09-4790-854e-8ba81e01c71a.png">
<img width="376" alt="Screen Shot 2023-02-08 at 10 57 47 AM" src="https://user-images.githubusercontent.com/90730785/217627268-def6ec93-1144-4c3b-b51b-975a7e8fc112.png">
<img width="389" alt="Screen Shot 2023-02-08 at 10 57 29 AM" src="https://user-images.githubusercontent.com/90730785/217627281-4c1e434c-3608-4157-b341-082b8a6fa7a1.png">

