# World Economies ETL Project

This project focuses on extracting, transforming, and loading data related to countries and their GDP. The primary script (`etl_script.py`) performs these ETL operations and stores the transformed data in both a CSV file (`Countries_by_GDP.csv`) and an SQLite database (`World_Economies.db`).

## Requirements

- Python 3.x
- Libraries:
  - requests
  - pandas
  - numpy
  - BeautifulSoup
  - sqlite3
  - datetime

Install the required libraries using the following command:

```bash
pip install pandas numpy beautifulsoup4
```  
## Usage  
### Clone the repository  
```
git clone https://github.com/shajon1211045/ETL_process_GDP_per_Billions.git    
cd ETL_process_GDP_per_Billions  
```
### Run the ETL script  
```
python etl_script.py  
```
### Project Structure

- `etl_script.py`: Main Python script for ETL operations.
- `Countries_by_GDP.csv`: CSV file containing the transformed data.
- `World_Economies.db`: SQLite database containing the transformed data.

## ETL Process Steps
`Extract`: The script extracts data from the specified URL, focusing on countries and their GDP.

`Transform`: Data transformation includes converting GDP values to numeric format and rounding to two decimal places.

`Load`: The transformed data is loaded into both a CSV file and an SQLite database.


