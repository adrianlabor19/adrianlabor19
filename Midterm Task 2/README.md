### Midterm Lab Task 2 - Data Cleaning and Transformation
## Using Power Query Editor
Company X would like to extract some useful information from the Uncleaned_DS_jobs.csv dataset taken
from a Job Posting site available on Kaggle. The goal is to answer:
1. Which Job Roles pay the highest and least?
2. What size companies pay the best?
3. Which Job Roles or Job Titles pay the best and least in a specific state?
## Instructions:
1. Download the dataset (Uncleaned_DS_jobs.csv).
2. Load Data in Excel -> Data -> New Query -> Open File -> Text/CSV.
3. Load and edit dataset using Power Query Editor.
4. Duplicate the raw data.
## Data Cleaning Tasks:
- Remove characters in Salary Estimate column after the '('.
- Create Min Salary and Max Salary columns from Salary Estimate.
- Add a Role Type column categorizing jobs as Data Scientist, Data Analyst, etc.
- Split columns by delimiters and correct location data.
- Handle negative values in Competitors, Revenue, and Industry columns.
- Clean company names and remove unnecessary descriptions.
- Copy Applied Steps as proof of data cleaning (Advanced Editor).
## Reshape and Group Data:
1. Duplicate raw data -> Rename as 'Sal By Role Type dup' -> Select Role Type, Min Sal, Max Sal -> Convert
to currency -> Group by Role Type.
2. Reference raw data -> Rename as 'Sal By Role Size ref' -> Select Size, Min Sal, Max Sal -> Convert to
currency -> Group by Company Size.
3. Merge dataset with state mapping files to correct and map location data.
4. Reference raw data -> Rename as 'Sal By State ref' -> Select State Full Name, Min Sal, Max Sal ->
Convert to currency -> Group by State.
View dependencies and references of Queries using the View -> Dependencies feature in Power Query.
## Here's the screenshot of my output before I started data cleaning (See screenshot)
![image alt](https://github.com/adrianlabor19/adrianlabor19/blob/2f5976b048a18059c9e8a096ed25514541798e92/Midterm%20Task%202/Screenshot/Screenshot%202025-03-12%20095546.png)
![image alt](https://github.com/adrianlabor19/adrianlabor19/blob/b5fcda79bf57ff4fe60e8be17b238c4d496e4d3a/Midterm%20Task%202/Screenshot/Screenshot%202025-03-12%20095607.png)
## Here's the screenshot of my output after I started data cleaning (See screenshot)
![image alt](https://github.com/adrianlabor19/adrianlabor19/blob/2679674675805809d14b9763014450c5861710fb/Midterm%20Task%202/Screenshot/Screenshot%202025-03-12%20095946.png)

## Here's the Final Data Cleaning and Transformation
![image alt](https://github.com/adrianlabor19/adrianlabor19/blob/f8ee4d98fcf54e6f742f657378b952749890493f/Midterm%20Task%202/Screenshot/Screenshot%202025-03-12%20100523.png)
![image alt](https://github.com/adrianlabor19/adrianlabor19/blob/0e60d4d5aa57cd9d86fef96ac11c7ce65ce7b0d6/Midterm%20Task%202/Screenshot/Screenshot%202025-03-12%20100554.png)
