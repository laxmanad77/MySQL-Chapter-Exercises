# MySQL Practice Repository

This repository is a collection of MySQL SQL scripts and exercises organized by chapter. It is intended for learning and practicing database creation, schema design, querying, and SQL operations using MySQL.

## Repository structure

The project is organized into chapter folders such as:

- `ch01/` – basic table creation, ALTER TABLE operations, and index examples
- `ch02/` – SELECT queries and aggregate calculations
- `ch03/` through `ch19/` – additional MySQL practice exercises and SQL examples

Examples in the repository include:

- creating tables and relationships
- adding and dropping columns
- creating and dropping indexes
- querying vendor and invoice data
- using aggregate functions such as `COUNT()` and `SUM()`

## Example files

A few sample SQL scripts in the repo include:

- `ch01/1-11.sql`
- `ch01/1-12.sql`
- `ch01/1-13.sql`
- `ch02/select_vendor_information.sql`
- `ch02/select_vendor_total_due.sql`

## Prerequisites

Before running the scripts, make sure you have:

- MySQL Server installed
- A MySQL client or command-line interface
- A database schema prepared for the exercises

## How to use

1. Clone the repository:
   ```bash
   git clone https://github.com/laxmanad77/MySQL.git
   ```

2. Open a chapter folder and select the SQL file you want to run.

3. Execute the script in MySQL:
   ```bash
   mysql -u your_username -p your_database_name < ch01/1-11.sql
   ```

4. Review the results and continue through the chapter exercises.

## Notes

This repository is focused on hands-on SQL learning and is best used as a practice set for understanding MySQL fundamentals and query writing.

## License

This project does not currently specify a license. If you plan to reuse or distribute the code, check whether a license is added later.
