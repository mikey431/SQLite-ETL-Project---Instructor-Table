# SQLite-ETL-Project---Instructor-Table
This project demonstrates how to load data from a CSV file into an SQLite database using Python, perform queries, and append new data to the table.

---

## Features

### 1.Load CSV into SQLite
Reads INSTRUCTOR.csv and loads it into a table named INSTRUCTOR in STAFF.db.

### 2.Queries

-**Display all rows from the table**

-**Display only the FNAME column**

-**Display the count of rows**

### 3.Append Data
Inserts a new record (John Doe, Paris, FR) into the table.

### 4.Validation
Runs queries again to verify that the data has been successfully appended.

---

## Project Structure
- `script.py`             # Main Python script
- `INSTRUCTOR.csv`        # Source CSV file (input)
- `STAFF.db`              # SQLite database (generated)

---

## Technologies & Libraries

- Python 3.x
- sqlite3 – for database connection and queries
- pandas – for reading CSV and handling DataFrames

---

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/sqlite_instructor_project.git
cd sqlite_instructor_project
```

### 2.Install dependencies:
```bash
pip install pandas
```

### 3.Make sure you have the CSV file (INSTRUCTOR.csv) in the correct path, or update the file_path variable in the script.

### 4.Run the script:
```bash
python script.py
```
