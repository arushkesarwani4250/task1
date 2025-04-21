Objective The goal of this task was to clean and preprocess a raw dataset containing missing values, duplicates, inconsistent formats, and mixed data types using Python (Pandas).

🧼 Cleaning Steps Performed Missing Values

Found missing values in the Income column.

Replaced missing entries with the median income to preserve distribution and avoid skew from outliers.

Duplicate Records

Checked for duplicate rows using .drop_duplicates().

No duplicates were found in the dataset.

Column Name Standardization

Converted all column names to lowercase and replaced spaces with underscores for consistency.

Text Cleaning

Cleaned and standardized string fields like education and marital_status:

Removed extra spaces

Converted to title case (e.g., single → Single)

Date Format

Converted dt_customer column to datetime format (dd-mm-yyyy style) using pd.to_datetime().

Data Type Fixes

Ensured all numeric fields were of type int or float.

Checked and confirmed correct type for categorical and datetime fields. Outcome Created a cleaned and well-structured dataset ready for analysis or modeling.

Learned and applied practical data cleaning techniques using Pandas.
