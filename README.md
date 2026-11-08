# Library Database Management System

## Project Overview
This project is a relational database designed to handle core library operations. It tracks information about authors, books, and member records to help streamline data management and retrieval.

## Database Schema (`library_schema.sql`)
The database consists of the following structured tables:
* **Authors Table:** Stores details about book writers (Author ID, Name, Country).
* **Books Table:** Stores book records (Book ID, Title, Published Year, and a Foreign Key linking to Authors).
* **Members Table:** Stores library user details and registration records.

## Sample Queries (`library_queries.sql`)
The project includes queries to perform:
* Retrieving complete lists of books along with their respective authors using `JOIN`.
* Filtering data based on specific criteria using `WHERE`.
* Sorting results using `ORDER BY`.

## How to Run
1. Open your SQL environment or DB Fiddle.
2. Run the `library_schema.sql` script to create the tables and insert sample data.
3. Execute the `library_queries.sql` script to test and view the data outputs.
  
