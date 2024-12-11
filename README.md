**Excel Data Cleaning with Power Query**

**Overview**
This project demonstrates data cleaning techniques using Microsoft Excel's Power Query. The dataset used is a simulated e-commerce sales dataset with multiple rows of raw data. Key objectives include handling missing values, ensuring data consistency, and deriving insights by adding calculated columns.

**Dataset**
The dataset simulates e-commerce transactions and includes the following columns:

Order ID: Unique identifier for each order.
Customer Name: Name of the customer.
Order Date: Date when the order was placed.
Shipping Date: Date when the order was shipped.
Product: Name of the product purchased.
Quantity: Number of units ordered.
Price: Price per unit of the product.
Total: Total cost of the order (Quantity × Price).
Notes: Additional comments or remarks (if any).

**Project Goals
Data Cleaning:**

Remove unnecessary spaces and non-printable characters.
Handle missing or null values in the dataset.
Ensure consistent formatting for dates and text fields.
Data Transformation:

Calculate the number of days between Order Date and Shipping Date.
Format columns to appropriate data types (e.g., Date, Text, Number).
Power Query Usage:

Leverage Power Query for no-code data cleaning and transformation.
Ensure all steps are easily reproducible.
Steps to Reproduce
Open the Dataset in Excel:

Open the provided dataset (Raw_Dataset.xlsx) in Excel.
Load Data into Power Query:

Select the dataset, go to the Data tab, and click on Get & Transform Data > From Table/Range.

**Clean the Data:**

Trim spaces and clean text fields.
Replace missing values in Total and Notes.
Calculate the Days to Ship column using the formula:
mathematica
Copy code
Duration.Days([Shipping Date] - [Order Date])

**Transform and Save:**

Ensure correct data types for all columns.
Click Close & Load to save the cleaned dataset into a new worksheet.

**Results
**The cleaned dataset is saved as Cleaned_Dataset.xlsx.
Key insights, such as shipping delays and order summaries, can now be derived easily.
Project Files
Raw_Dataset.xlsx: Original dataset before cleaning.
Cleaned_Dataset.xlsx: Final dataset after cleaning.
Screenshots/: Step-by-step visuals of the cleaning process in Power Query.


**Tools Used**
Microsoft Excel: For data management and analysis.
Power Query: For no-code data cleaning and transformation.
Acknowledgments
Dataset: Simulated dataset created for learning purposes.
Tools: Thanks to Microsoft Excel's Power Query for simplifying data cleaning.

**License**
This project is licensed under the MIT License. Feel free to use and modify it for learning and personal projects.

