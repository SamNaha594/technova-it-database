# TechNova IT Solutions — Oracle Database Project

## Overview
A beginner-level relational database project for a fictional IT
services company. It manages customers, IT services, and sales orders
using Oracle SQL.

## Business Scenario
The company sells website development, mobile app development,
IT consultancy, and database management services.

## Database Tables
1. CUSTOMERS — customer information
2. SERVICES — service catalog and base prices
3. ORDERS — customer purchases and order details

## Relationships
- One customer can have many orders.
- One service can appear in many orders.
- Each order references one customer and one service.

## Technologies
- Oracle Database
- SQL
- Primary Keys and Foreign Keys
- Constraints
- JOIN, GROUP BY, SUM, ORDER BY

## Project Structure
- `01_create_tables.sql` — Create tables and constraints
- `02_insert_sample_data.sql` — Insert sample records
- `03_sales_queries.sql` — Sales reports and analysis

## How to Run
1. Connect to your Oracle database schema.
2. Run `01_create_tables.sql`.
3. Run `02_insert_sample_data.sql`.
4. Run `03_sales_queries.sql`.
5. Review the query results.

Run the scripts in a fresh, empty schema to avoid conflicts
with existing tables and sample IDs.

## Example Business Reports
- Customer order history
- Total sales revenue
- Spending by customer
- Sales by service

## Notes
This project uses fictional sample data for learning purposes.
It is a portfolio learning project, not a production-ready system.

## Author
Suman Naha