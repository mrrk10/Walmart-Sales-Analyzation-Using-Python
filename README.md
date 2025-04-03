# Project Title
## Project Title: Walmart Retail Sales Analysis
### **Description**
This project analyzes Walmart retail sales data from **2012 to 2015** using **Python** and **SQLite**. The script processes sales data, calculates the sales growth rate per state, and identifies the most profitable products by state and region.  
### **Getting Started**
### **Prerequisites**  
Ensure you have the following installed:  
- **Python 3.x**  
- Required Python libraries:  
  ```bash
  pip install pandas sqlite3 openpyxl
  ```
### Installing
 1. **Clone the Repository**  
   ```sh
   git clone https://github.com/KshitizSee/Individual-Project-1.git
 2. **Navigate to the Project Folder**
  ```sh
  cd walmart-sales-analysis
3. Ensure the Dataset is in the Directory
```sh
Place the WalmartRetailSales.xlsx file in the project directory
## Running the Script
-Execute the Python script:
```sh
python script.py
--The script will:
  --Load and process the dataset from an Excel file.
  --Store the data in an in-memory SQLite database.
  --Calculate the sales growth rate per state.
  --Identify the most profitable products in each region and state.
  --Print results to the console.
## SQL Query Used
1. Sales Growth Rate per State
  Calculates yearly sales growth per state and determines if sales are decreasing in most states.
2. Most Profitable Products
  Finds the most profitable products for each region and state.

