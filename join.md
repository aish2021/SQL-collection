#JOIN
A JOIN clause is used to combine rows from two or more tables, based on a related column between them.

SELECT Orders.OrderID, Customers.CustomerName, Orders.OrderDate
FROM Orders
INNER JOIN Customers ON Orders.CustomerID=Customers.CustomerID;

Different Types of SQL JOINs
Here are the different types of the JOINs in SQL:

1. (INNER) JOIN: Returns records that have matching values in both tables.
  example-SELECT column_name(s)
          FROM table1
          INNER JOIN table2
          ON table1.column_name = table2.column_name;

2. LEFT (OUTER) JOIN: Returns all records from the left table, and the matched records from the right table.
   example-SELECT column_name(s)
            FROM table1
            LEFT JOIN table2
            ON table1.column_name = table2.column_name;
            
3. RIGHT (OUTER) JOIN: Returns all records from the right table, and the matched records from the left table.
   example-SELECT column_name(s)
            FROM table1
            RIGHT JOIN table2
            ON table1.column_name = table2.column_name;
            
4. FULL (OUTER) JOIN: Returns all records when there is a match in either left or right table.
   example-SELECT column_name(s)
            FROM table1
            FULL OUTER JOIN table2
            ON table1.column_name = table2.column_name
            WHERE condition;
            
#SQL Self JOIN
A self JOIN is a regular join, but the table is joined with itself.

Self JOIN Syntax:

  SELECT column_name(s)
  FROM table1 T1, table1 T2
  WHERE condition;
  
  T1 and T2 are different table aliases for the same table.


