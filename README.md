# Sales Data Analysis

## Project Overview
This project analyzes sales data from an Excel file, extracting key metrics and insights to understand business performance over time. The data includes sales values for different months and calculates growth trends. The dashboard is designed to automatically include new month's data when updated.

## 📂 Repository Structure
```
📂 Sales-Data-Analysis/
├── 📂 Data/  (Stores the original Excel files)
├── 📂 Notebooks/  (Jupyter Notebook for analysis)
├── 📄 README.md  (Project summary)
├── 📄 analysis.py  (Python script for automated analysis)
```

## 📊 Data Insights
### **1. Sales Performance Overview**
- **Latest Month Sales**: 5,187,471
- **Previous Month Sales**: 4,802,968
- **Growth Rate**: ~8.01%

### **2. Dashboard Visualization**
- The dashboard visualizes sales trends and key KPIs.

## 🛠️ Steps Followed in Analysis

### **1. Drafting the Dashboard**
- Designed an interactive Excel dashboard from scratch.
- Planned the structure to ensure a user-friendly and insightful layout.

### **2. Importing and Connecting Data**
- Used Power Query to import data from multiple sources.
- Established connections between various datasets for seamless integration.
- Ensured that new month's data can be automatically included when updated.

### **3. Data Modeling**
- Created relationships between different datasets using the Excel Data Model.
- Ensured efficient data handling and optimized query performance.

### **4. Calculations and Visualizations**
- Set up calculations using PivotTables to aggregate sales data.
- Created PivotCharts and linked shapes to present key insights interactively.

### **5. Extracting Insights Using Python**
- Loaded and processed Excel data using `pandas`.
- Extracted key performance indicators (KPIs) from the calculations sheet.
- Saved a cleaned dataset for further analysis and visualization.

## ⚙️ How to Run the Analysis
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Sales-Data-Analysis.git
   cd Sales-Data-Analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas openpyxl
   ```
3. Run the Python script:
   ```bash
   python analysis.py
   ```
4. Open the Jupyter Notebook in the `Notebooks/` folder for a detailed analysis.


## 📧 Contact
For any inquiries, reach out via [LinkedIn]https://www.linkedin.com/in/saraahmedbadawi/
