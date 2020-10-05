#INSERT INTO Syntax

It is possible to write the INSERT INTO statement in two ways.

The first way specifies both the column names and the values to be inserted:

example-: INSERT INTO table_name (column1, column2, column3, ...)
          VALUES (value1, value2, value3, ...);
          
If you are adding values for all the columns of the table, you do not need to specify the column names in the SQL query.
However, make sure the order of the values is in the same order as the columns in the table. The INSERT INTO syntax would be as follows:

example-: INSERT INTO table_name
          VALUES (value1, value2, value3, ...);
          
          
#The SQL UPDATE Statement

The UPDATE statement is used to modify the existing records in a table.

UPDATE Syntax-:

example-: UPDATE table_name
          SET column1 = value1, column2 = value2, ...
          WHERE condition;
          
          
#The SQL DELETE Statement

The DELETE statement is used to delete existing records in a table.

DELETE Syntax-:
example-: DELETE FROM table_name WHERE condition;

