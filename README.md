# Task1_DataCleaning
The main goal of this project is to utilize Python (Pandas) to clean and prepare a raw dataset. By handling missing values, eliminating duplicates, standardizing text, formatting dates, and making sure that data types are consistent across columns.
Tools Used : Python 3.10.14 , Pandas,  Jupyter Notebook

**Cleaning Steps Performed**

1. Handled Missing Values:
   - Detected using `.isnull()` and handled by either filling with defaults or dropping rows/columns.

2. Removed Duplicate Records:
   - Used `.drop_duplicates()` to eliminate repeated entries.

3. Standardized Text Values:
   - Converted inconsistent entries (e.g., "Male", "male", "M") to a unified format like "Male".
   - Cleaned country names, gender, and other categorical fields.Performed only on country as my dataset doesn't contain Gender entity.

4. Formatted Dates:
   - Converted date columns to `datetime` objects using `pd.to_datetime()`.
   - Reformatted dates to a consistent `dd-mm-yyyy` style for readability.

5. Cleaned Column Headers
   - Renamed column names to be lowercase and replaced spaces with underscores for easier handling in code.

6. Verified & Fixed Data Types
   - Ensured numeric fields like age, sales, and phone were of appropriate types (`int64`, `float64`).
   - Confirmed date fields are in `datetime` format where needed.
  
7. Output:
   - A fully cleaned dataset saved as `cleaned_data.csv`
   - Ready for analysis, dashboarding, or modeling.   - 
