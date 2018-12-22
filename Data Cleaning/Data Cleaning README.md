# Data Cleaning README

## 1.0

- Exported csv file from https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95 (version that was updated 12.13.18)

## 1.1

- Did data cleaning in Pandas in Jupyter notebook file: creating_data_1.1.ipynb 
- Saved a CSV and Excel File

### 1.2

- Removed the following in Excel:
    - Unspecified from CFV1 and CFV2
    - Removed rows with values in V3, V4 and V5
- Saved a CSV and Excel File

### 1.3

- Did data cleaning in Pandas in Jupyter notebook file: creating_data_1.3.1.ipynb 
- Did data cleaning in Pandas in Jupyter notebook file: creating_data_1.3.2.ipynb 
    - data_1.3.1.csv contains no null values (~76K records)
    - data_1.3.2.csv contains some null values but gives a larger same size for CFV1 column (~183K records)