
# Getting Data Ready with Python and Pandas on Google Colab

## Data Exploration
Initial exploration allows us to identify necessary fixes and understand the dataset's structure. For this project, I inspected the data using standard commands like `data.head(10)` to verify column headers and data types (integers, floats, or strings). 

> **Tip:** When dealing with large tables, it is best practice to view only the first and last few rows. Loading entire datasets at once can significantly slow down your environment.

During this phase, we also check for:
* **Missing Values:** Identifying empty spaces or null entries.
* **Duplicates:** Locating redundant information.
* **Shape:** Confirming the total number of rows and columns.

## Data Cleaning & Consistency
The quality of data often depends on the source system. Depending on how information was collected, consistency can vary wildly. 

In this case, I performed specific transformations to ensure compatibility:
* **Date Formatting:** Standardised the date format to maintain consistency with other datasets, enabling seamless merging and time-series analysis.
