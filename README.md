# 🛒 Retail Sales Analysis Project

## 📌 Overview
This project performs a comprehensive analysis of retail sales data using **Python (Jupyter Notebook)** and **Power BI**. It explores sales trends, product performance, and customer behavior to generate actionable business insights.

---

## 🛠️ Tools Used
- **Python (Jupyter Notebook)**: For data cleaning, analysis, and visualizations.
- **Power BI**: For interactive dashboards and business reporting.
- **Pandas, NumPy, Matplotlib, Seaborn**: Python libraries used for data manipulation and EDA.

---

## 🔍 Dataset
- **Source:** [Online Retail Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Description:** Contains transactions from a UK-based online retail company between **2010–2011**.
- **Columns:**
  - `InvoiceNo`: Invoice number
  - `StockCode`: Product/item code
  - `Description`: Product name
  - `Quantity`: Number of units purchased
  - `InvoiceDate`: Date and time of purchase
  - `UnitPrice`: Price per unit
  - `CustomerID`: Unique customer identifier
  - `Country`: Customer’s country of residence

---

## 📂 Project Structure

| File/Folder | Description |
|-------------|-------------|
| `data/sales_data.csv.zip` | Zipped dataset to reduce file size |
| `Retail_Sales_Analysis.ipynb` | Jupyter Notebook for data cleaning, analysis, and visualizations |
| `Retail_Sales_Dashboard.pbix` | Power BI Dashboard file |
| `README.md` | Project documentation |

---

## 🚀 Getting Started

### 🔽 1. Download and Extract the Dataset
- Go to the `data` folder in this repo
- Download the file `retail_cleaned.csv.zip`
- Extract the CSV file using any unzip tool

### ▶️ 2. Run the Jupyter Notebook
- Open `Retail_Sales_Analysis.ipynb` in Jupyter Notebook or VS Code
- Make sure the extracted CSV file is in the same folder or update the file path accordingly
- Run the cells to see data cleaning, EDA, and visualizations

### 📊 3. Open Power BI Dashboard
- Open `Retail_Sales_Dashboard.pbix` in Power BI Desktop
- If the dashboard says it can’t find the data, re-link it to your extracted `retail_cleaned.csv` file
  - Click “Transform Data” > “Edit Queries” > update the file path

---

## 📈 Key Insights

- **Sales Peaks** in November and December indicate strong holiday season performance.
- A small number of **top products** generate the bulk of revenue.
- Most sales originate from the **UK**, but international markets show potential.
- **Customer behavior** varies widely — some high-spending, others one-time buyers.

---

## 💡 Recommendations

- Target promotions during high-sales months to maximize revenue.
- Review underperforming products or categories for discontinuation.
- Implement retention strategies for one-time buyers.

---

## 📅 Last Updated
- May 2025

---

## 🧑‍💻 Author
- Zafar Moin | Data Analyst 

---

## 📎 License
This project is open-source and free to use for educational purposes.
