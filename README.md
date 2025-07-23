# Blinkit-Dataset-Analysis-Visualization
BlinkIT sales and operations data for analysis. in Excel
Blinkit Item Data
This dataset contains information about various retail items listed on a grocery delivery platform, modeled after Blinkit. The dataset is stored in an Excel file and includes details such as fat content, item identifiers, item types, and the outlet establishment year.

📁 Dataset Overview
Column Name	Description
Item Fat Content	The fat content category of the item (e.g., Regular, Low Fat, LF, etc.)
Item Identifier	A unique alphanumeric code used to identify each item
Item Type	The category/type of the item (e.g., Fruits and Vegetables, Household, etc.)
Outlet Establishment Year	The year when the outlet was established

📊 Sample Data
Here are a few rows from the dataset:

Item Fat Content	Item Identifier	Item Type	Outlet Establishment Year
Regular	FDX32	Fruits and Vegetables	2012
Low Fat	NCB42	Health and Hygiene	2022
Regular	FDR28	Frozen Foods	2016
Low Fat	DRI25	Soft Drinks	2015
LF	FDX21	Snack Foods	2018

🧼 Data Cleaning Notes
Normalize inconsistent fat content values such as low fat, Low Fat, and LF.

Verify missing or incorrect entries, such as the missing year in some rows.

Check for duplicate Item Identifier values.

📈 Potential Uses
Market trend analysis by item type and outlet age

Nutritional segmentation of products

Inventory planning and categorization

🧰 Tools Used
Excel / Google Sheets: Data entry and formatting

Python / Pandas (optional): For advanced processing and analysis
