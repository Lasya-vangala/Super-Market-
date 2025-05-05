
# 🛍️ Supermarket Sales Data Analysis

This project performs comprehensive data cleaning and analysis on raw supermarket transaction data. The goal is to understand product-wise sales and profit contributions at each branch. The results are exported for visualization in Tableau.

---

### 📌 Objectives

- Clean and format raw transaction data  
- Calculate total prices and profit percentages  
- Reshape the dataset using pivot tables for better analysis  
- Summarize total product sales and profits by branch  
- Identify the most sold product in each branch  
- Export final output as a clean `.csv` for Tableau dashboarding

---

### 🔧 Tools Used

- **Python 3**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Tableau Public** for data visualization

---

### 🚀 Features

- 🧹 **Data Cleaning**
  - Converts date and time into readable formats  
  - Replaces invalid/missing values  
  - Drops unnecessary columns  

- 📊 **Data Transformation**
  - Creates a pivot table showing total prices by product line  
  - Merges pivoted product prices back into the main dataset  

- 📈 **Branch-wise Summary**
  - Sums up total sales per product per branch  
  - Identifies the most sold product in each branch  
  - Calculates total profit using profit percentages  

- 💾 **Final Output**
  - Saves a summarized CSV file named: `supermarket_analysis_output.csv`

---

### 📁 Output File

You can view or download the final processed data here:  
📄 [`supermarket_analysis_output.csv`](./supermarket_analysis_output.csv)

---

### 📈 Tableau Dashboard

Explore the visual interpretation of the analysis here:  
🔗 [View on Tableau Public](https://public.tableau.com/app/profile/lasya.vangala/viz/super_market_sales_17457405094810/Super_Market_sales)

> 
