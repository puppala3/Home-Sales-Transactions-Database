# Home-Sales-Transactions
This project analyzes home sales transactions using SQL queries and database management techniques. It includes data modeling, query optimization, and analysis of property sales data
# Features
- SQL queries for analyzing home sales data
- Data modeling for property, buyer, seller, and realtor entities
- Transaction history tracking
- Performance optimization techniques
# Project Structure
- 'populate_tables.sql': SQL script to populate sample data
- 'queries.sql': SQL queries for data analysis
- 'Triggers-Stored-Procedure.sql': SQL triggers and stored procedures
- 'Final_Project_Report.pdf': Detailed project report
# Key Queries
- Properties with specific bedroom and bathroom counts in a given city
- Buyer information for a specific property
- Properties listed for over 15 days without closing
- Properties without bids
- Average listing time for closed properties
# Triggers and Stored Procedures
- Trigger to validate bid date against property listing date
- Trigger to ensure buyer and seller have different realtors
- Trigger to enforce minimum bid price
- Stored procedure to retrieve highest bidder information
# Usage
- Set up a SQL database (e.g., MySQL, PostgreSQL)
- Run populate_tables.sql to create and populate tables
- Execute queries from queries.sql for analysis
- Implement triggers and stored procedures from 'Triggers-Stored-Procedure.sql'
# Database Schema
- PROPERTY
- BUYER
- SELLER
- REALTOR
- BID_HISTORY



