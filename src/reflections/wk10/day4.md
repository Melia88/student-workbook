Day4

Afternoon Challenge

Read Dotnet WebAPI's > Welcome to SQL, and answer the following questions

In a SQL table, what is the difference between information in a row and information in a column?
>Rows are complete objects like books
>Columns are specific properties like title or author

Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
>

CREATE TABLE characters(
  name VARCHAR(255) NOT NULL,
  age VARCHAR(255) NOT NULL,
  description VARCHAR(255) NOT NULL,
  id int NOT NULL,
  
  PRIMARY KEY (id)
);

What is the difference between the following statements:

DELETE FROM table_name; >> Removes a row of data from a table
DROP TABLE table_name; >> Deletes the entire table