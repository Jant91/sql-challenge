# SQL-Challenge

This project involves analyzing an employee database with multiple tables using SQL queries. The database includes information about employees, departments, salaries, titles, and more.

## Table of Contents

- [Introduction](#introduction)
- [Table Schema](#table-schema)
- [Data Analysis](#data-analysis)
- [Usage](#usage)
- [Queries](#queries)

## Introduction

The purpose of this project is to demonstrate how to work with a relational database by performing data analysis using SQL queries. The database consists of multiple tables related to employees, departments, and various attributes associated with them.

## Table Schema

The database schema includes the following tables:

- `department`
- `employees`
- `titles`
- `salary`
- `dept_manager`
- `dept_emp`

Each table has specific columns with relationships established through primary and foreign keys.

## Data Analysis

The project includes SQL queries that address various analysis requirements, such as:

- Retrieving employee details including employee number, last name, first name, sex, and salary.
- Listing employees hired in a specific year with hire date and names.
- Listing managers along with department information.
- Displaying employee department information.
- Extracting specific employee details based on conditions.
- Calculating frequency counts of employee last names.

## Usage

To use this project, follow these steps:

1. Create a database in your preferred database management system (e.g., MySQL, PostgreSQL).
2. Execute the provided SQL scripts to create the required tables and import data from CSV files.
3. Run the SQL queries provided in the project to perform data analysis.

## Queries

In the `queries.sql` file, you'll find a collection of SQL queries corresponding to different data analysis requirements. Each query is documented with its purpose.
