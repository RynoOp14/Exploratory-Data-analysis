Task 1 – Data Cleaning and Preprocessing: Netflix Dataset 

Dataset Used:
Netflix Movies and TV Shows Dataset (netflix_titles.csv) from Kaggle.

 Cleaning Steps Performed:

1. Loaded the dataset using Pandas.
2. Renamed column names to lowercase and snake_case format.
3. Handled missing values in columns like:
   - director, cast, country, rating, duration → filled with "Unknown"
4. Converted date_added column to proper datetime format.
5. Removed duplicates using drop_duplicates().
6. Standardized text values in type, country, rating using str.strip(), str.title(), and str.upper().

 Tools Used:
- Python
- Pandas
- Jupyter Notebook 

Final Output:
- Cleaned dataset: cleaned_netflix_titles.csv
- Code script: netflix_titles
-Python file: python_file_cleaned_netflix_titles.py
