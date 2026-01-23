# Netflix Data Cleaning & Analysis

This project explores and cleans the **Netflix titles dataset** to make it ready for analysis and reporting.  
I used **Python, SQL and Excel** to go from raw CSV data to a clean, queryable dataset and insights about Netflix content.

## Tech Stack

- **Python** – data extraction & preprocessing (`netflix_data_extract.py`)
- **SQL** – data cleaning, transformations and analysis  
  - `netflix_raw.sql` – raw table & initial loading
  - `netflix_data_analysis.sql` – cleaning + analytical queries
- **Excel** – quick checks, manual validation and data exploration (`netflix_titles.xlsx`)

## Project Goals

- Import the raw Netflix titles dataset into a relational database
- Clean and standardize key fields (dates, ratings, categories, etc.)
- Handle missing and inconsistent values
- Build useful SQL queries for content analysis

## Main Files

- `netflix_titles.xlsx` – original Netflix titles dataset
- `netflix_data_extract.py` – Python script to prepare / load data
- `netflix_raw.sql` – script to create and populate the raw table
- `netflix_data_analysis.sql` – cleaning and analysis queries

## Example Analyses

Some of the questions explored in this project:

- How has the number of Netflix releases changed over time?
- Which countries contribute the most content to Netflix?
- What is the distribution of Movies vs TV Shows?
- Which ratings (TV-MA, TV-14, etc.) are most common?

## How to Run

1. **Set up the database**
   - Create a new database in your SQL server
   - Run `netflix_raw.sql` to create and populate the raw table

2. **(Optional) Use Python for loading**
   - Install Python 3 and required libraries (e.g. `pandas`, `sqlalchemy`)
   - Update connection details in `netflix_data_extract.py`
   - Run the script to load data into your database

3. **Run the analysis**
   - Execute the queries in `netflix_data_analysis.sql`
   - Use the results to build dashboards or reports (Power BI, Excel, etc.)

## Future Improvements

- Add automated data validation checks
- Build a small Power BI / Tableau dashboard on top of the cleaned data
- Containerize the setup using Docker for easier reproducibility
