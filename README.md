# Car Rental Management System — DBMS Mini Project

A beginner-friendly MySQL 8.0 mini project to manage customers, cars, and rental records.

## Features
- Customer, car, and rental tables
- Primary keys, foreign keys, UNIQUE constraints, CHECK constraints
- Sample records for testing
- JOIN, GROUP BY, aggregate, subquery, and NOT EXISTS examples
- CRUD examples and an index with `EXPLAIN`

## Requirements
- MySQL 8.0 or later
- MySQL Workbench or MySQL command-line client

## Run
1. Open `car_rental_management.sql` in MySQL Workbench.
2. Execute the script from top to bottom.
3. Run the SELECT queries near the end to inspect the results.
4. Capture screenshots of the SQL statements and their result grids for the printed report.

## Database design
- `customers` — customer contact and driving-license details
- `cars` — vehicle details, daily rate, and availability
- `rentals` — customer/car relationship, dates, amount, and status

## Important note
The names, phone numbers, emails, registration numbers, and transactions are fictional sample data for classroom demonstration. Do not use them as real customer records.

## Suggested screenshots
1. Database and three tables in the schema navigator
2. `SELECT * FROM cars;` result grid
3. Joined rental details (Query 3)
4. Customer-wise total amount (Query 4)
5. `EXPLAIN` result for Query 10

## Suggested repository contents
- `Car_Rental_Management_System_Report.docx`
- `car_rental_management.sql`
- `README.md`
