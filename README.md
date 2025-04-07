# Market-dataset-analysis

 Summary of Supermarket Sales Dataset Code File

In this code file, we conducted a thorough data cleaning and preprocessing of the Supermarket Sales dataset, which contains transactional data from a supermarket, including details about products, customers, and sales. The main steps undertaken in the code are as follows:

1. *Data Loading*: We began by loading the Supermarket Sales dataset from a CSV file into a Pandas DataFrame for analysis.

2. *Missing Value Handling*: We identified and addressed missing values in critical columns such as 'Customer type' and 'Gender' by filling them with appropriate placeholders (e.g., 'Unknown') to ensure completeness.

3. *Duplicate Removal*: We checked for and removed any duplicate rows in the dataset to maintain data integrity and accuracy.

4. *Text Standardization*: We standardized text values in columns such as 'Gender' and 'City' by converting them to lowercase and stripping any leading or trailing whitespace, ensuring consistency across the dataset.

5. *Column Renaming*: We renamed the columns to follow a consistent naming convention by converting them to lowercase and replacing spaces with underscores, making it easier to reference them in analysis.

6. *Data Type Verification*: We ensured that numeric columns such as 'Unit price' and 'Quantity' were converted to the appropriate numeric types, allowing for accurate calculations and analyses.

7. *Data Quality Checks*: We filtered the dataset to include only valid customer types (e.g., 'Member' and 'Normal'), ensuring that the data is clean and reliable for further analysis.

8. *Documentation of Changes*: We documented the changes made during the cleaning process in a summary dictionary, providing a clear overview of the modifications.

9. *Output*: Finally, we displayed the cleaned dataset and saved it to a new CSV file for future use.
