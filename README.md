# ETL Project: Extract, Transform, and Load GDP Data

## Introduction
This practice project involves creating a complete ETL (Extract, Transform, Load) pipeline to access and process GDP data from a website. The goal is to extract GDP information for different countries, transform the data into a specified format, and load it into both a CSV file and a database table.

### Data Source
URL: 
```
https://web.archive.org/web/20230902185326/https://en.wikipedia.org/wiki/List_of_countries_by_GDP_%28nominal%29
```

### Output Requirements
1. **CSV File**: Countries_by_GDP.csv
2. **Database Table**: Countries_by_GDP in World_Economies.db
3. **Attributes**:
   - Country
   - GDP_USD_billion

## Objectives
1. Write a function to extract GDP data from the specified URL.
2. Transform GDP data from millions to billions of USD, rounded to two decimal places.
3. Load the transformed data into a CSV file and a SQLite database.
4. Execute a query to retrieve countries with a GDP greater than 100 billion USD.
5. Log each step of the ETL process with timestamps.

## Setup
### Required Libraries
- requests
- bs4 (BeautifulSoup)
- pandas
- sqlite3
- numpy
- datetime

### Installation Commands
```bash
python3.11 -m pip install pandas
python3.11 -m pip install numpy
python3.11 -m pip install bs4
```
## Output
![image](https://github.com/Mahmoud-khaled-m/ETL-For-Top-10-GDP-Countries/assets/85359683/e771df02-e242-4e55-b8e2-b1d55a69bba3)



