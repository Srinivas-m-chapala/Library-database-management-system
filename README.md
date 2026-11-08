# Library Database Management System

## Project Overview
This project is a relational database designed to handle core library operations. It organized data about authors, books, and members, establishing clear relationships between them to perform clean data retrieval and reporting.

## Database Schema (`library_schema.sql`)
The database consists of the following structured tables:
* **Authors Table:** Stores author details including AuthorID (primary key with auto-increment),First name,Last Name,and Birth Date.
* **Books Table:** Stores book records including Book ID(primary key with auto-increment) Title, Published Year,Genre and Author ID (Foreign Key linking to Authors table).
* **Members Table:** Stores library user information ,including MemberID,Full Name,Membership Date,and Email. 

## Sample Queries (`library_queries.sql`)
The project includes analytical queries written to explore and extract useful insights:
* Retrieving complete lists of books along with their respective authors using `JOIN`.
* Filtering data based on specific criteria using `WHERE`.
* Pattern searching and text matching using 'LIKE'wildcard operators.
* Summarising and grouping Data using the 'GROUP BY' clause.
* Sorting results using `ORDER BY`.

## How to Run
1. Open your SQL environment or DB Fiddle.
2. Run the `library_schema.sql` script to create the tables and insert sample data.
3. Execute the `library_queries.sql` script to test and view the data outputs.
  
